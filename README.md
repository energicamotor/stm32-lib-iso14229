# ISO-14229 UDS

An implementation of the ISO-14229 protocol in a platform agnosteic C library. 

> ISO 14229 has been established in order to define common requirements for diagnostic systems, whatever the serial data link is.
> To achieve this, ISO 14229 is based on the Open Systems Interconnection (OSI) Basic Reference Model in accordance with ISO/IEC 7498-1 and ISO/IEC 10731,
> which structures communication systems into seven layers.

How to use:
- Include the header file `lib-iso14229.h`.
- Define `iso14229_t`, create and attach the required shim/callbacks (`on_opening` `on_unlocking` `on_closing`) of the handler.
