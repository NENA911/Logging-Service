# NG9-1-1 Logging Service

The Logging Service in NG9‑1‑1 is a standardized functional element used by all elements in an ESInet to log all significant events; logging is not restricted to events within a PSAP. All significant steps in processing a call are logged. NG9‑1‑1 defines an external Logging Service interface so that the logging function can be provided in the ESInet (i.e., external to a PSAP). Logging includes external events, internal events, media, and messages. All forms of media described in this document MUST be logged (see the Media section for details). Media recording SHOULD begin at the earliest point possible, which can be before the call has been answered if early media are available; recording media both at or near ESInet ingress and within a PSAP is desirable. The Logging Service is sometimes referred to as simply “the Logging Service” in this document. Each agency can have its own Logging Service, or Logging Services can be shared. Since incidents may involve multiple agencies, obtaining logging records from multiple Logging Services may be required. The Agency Locator record includes the URI to the Logging Service for a particular agency.

## Owner

The owner of this repository approves all changes to the repository. 

This repository is owned by the NENA Core Services Committee, i3 Architecture working group.

#### Rules:

Specification Required. 

#### Contact:

[https://www.nena.org/page/911CoreSvcs](https://www.nena.org/page/911CoreSvcs) 

## Version History

### Logging Service v 1.0

A REST/JSON definition for the Logging Service was originally defined in NENA-STA-010.3.2021. See https://www.nena.org/page/i3_Stage3
