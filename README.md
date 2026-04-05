An Odorik centered fork of Linphone. See [the original project for a technical description](https://github.com/belledonnecommunications/linphone-android).

## List of changes compared to original

- changed the name to Odorik Phone
- hidden the UI for choosing between Linphone and 3rd party account, now only 3rd party account
is visible
- the "3rd party SIP account" title has been changed to "SIP account"
- changed the default SIP server to sip.odorik.cz
- added sip.odorik.cz to the list of allowed push notification domains
- made sure that TLS is the default selected option in register screen
- forced using sips scheme in some cases if the transport is TLS
- enabled STUN/ICE by default
- added default push proxy value (flexisip.odorik.chrastecky.dev) to the login screen
