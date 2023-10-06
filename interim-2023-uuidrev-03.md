# uuidrev - Revise Universally Unique Identifier Definitions

* Friday, 06 October 2023, 8:00 PST, 11:00 EDT, 1500 UTC.


### INFO:

info: https://datatracker.ietf.org/wg/uuidrev/meetings/

Meetecho: https://meetings.conf.meetecho.com/interim/?short=b85d9b68-3e38-43dc-83ee-1b58f9e920ec
Notes:    https://notes.ietf.org/notes-ietf-interim-2023-uuidrev-04-uuidrev

note that chat is now Zulip:
   https://zulip.ietf.org/login/#narrow/stream/uuidrev
but is accessible via meetecho interface.

# AGENDA

## Hello, logistics, expected schedule of work.

## NoteWell.
    https://www.ietf.org/about/note-well/

## Code of Conduct
    BCP 54 / RFC 7154
    1. Treat colleagues with respect
    2. Speak slowly and limit the use of slang
    3. Dispute ideas by using reasoned argument
    4. Use best engineering judgment
    5. Find the best solution for the whole Internet
    6. Contribute to the ongoing work of the group and the IETF

## Status Update on WG documents

```mermaid
graph LR
    classDef current fill:orange
    classDef lastIETF fill:pink

    WG-Adopt --editing--> WGLC
    WGLC --consensus--> AD-Review
    AD-Review --> IETF-LC
    IETF-LC --> IANA-Review
    IETF-LC --> IESG-Review
    IANA-Review --> IESG-Review
    IESG-Review --> RFC-Editor
    RFC-Editor((RFC-Editor)) --> RFC
    [you are here] --> IESG-Review

    class IESG-Review lastIETF
    class RFC-Editor current
```


## IANA considerations needs

https://github.com/ietf-wg-uuidrev/rfc4122bis/issues/144

* IANA UUID Variants Registry and Registration {#iana1}
* What is the DNS reference and namespace?
** Namespace ID Usage and Allocation {#namespaces}
* IANA Reserved UUIDs Registry and Registration {#iana3}
* IANA UUID Subtype Registry and Registration {#iana2} 

## open and closed issues from sectorial / AD reviews

* 
* 

## UUIDv9 issues

* are these concerns now resolved into v8 "name-based" text?

## discussion and chair questions

* what things might need a subsequent document?
* if we are accepting any significant changes, then do we reset to WGLC?
* 

## Open Mic and AOB

* things back to the WG mailing list: IETF process oriented issues!
  ** should the WG reset back to WGLC?
  ** all decisions made "today" need to come back to the ML, period.
  ** 
