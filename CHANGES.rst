Changelog
=========

0.5.2 (2013-08-05)
------------------

- Important security update. Don't expose the Strophe connection object globally. [jcbrand]

0.5.1 (2013-08-04)
------------------

- #13, #14: Messages sent between to GTalk accounts weren't being received. [jcbrand]
- #32: Default status was offline when user didn't have contacts. [jcbrand]
- Attach panels to the DOM upon initialize. [jcbrand]

0.5.0 (2013-07-30)
------------------

- #09 Remove dependency on AMD/require.js [jcbrand]
- #22 Fixed compare operator in strophe.muc [sonata82]
- #23 Add Italian translations [ctrlaltca]
- #24 Add Spanish translations [macagua]
- #25 Using span with css instead of img [matheus-morfi]
- #26 Only the first minute digit shown in chatbox. [jcbrand]
- #28 Add Brazilian Portuguese translations [matheus-morfi]
- Use Bower to manage 3rd party dependencies. [jcbrand]

0.4.0 (2013-06-03)
------------------

- CSS tweaks: fixed overflowing text in status message and chatrooms list. [jcbrand]
- Bugfix: Couldn't join chatroom when clicking from a list of rooms. [jcbrand]
- Add better support for kicking or banning users from chatrooms. [jcbrand]
- Fixed alignment of chat messages in Firefox. [jcbrand]
- More intelligent fetching of vCards. [jcbrand]
- Fixed a race condition bug. Make sure that the roster is populated before sending initial presence. [jcbrand]
- Reconnect automatically when the connection drops. [jcbrand]
- Add support for internationalization. [jcbrand]

0.3.0 (2013-05-21)
------------------

- Add vCard support [jcbrand]
- Remember custom status messages upon reload. [jcbrand]
- Remove jquery-ui dependency. [jcbrand]
- Use backbone.localStorage to store the contacts roster, open chatboxes and chat messages. [jcbrand]
- Fixed user status handling, which wasn't 100% according to the spec. [jcbrand]
- Separate messages according to day in chats. [jcbrand]
- Add support for specifying the BOSH bind URL as configuration setting. [jcbrand]
- #8 Improve the message counter to only increment when the window is not focused [witekdev]
- Make fetching of list of chatrooms on a server a configuration option. [jcbrand]
- Use service discovery to show all available features on a room. [jcbrand]
- Multi-user chatrooms are now configurable. [jcbrand]


0.2.0 (2013-03-28)
------------------

- Performance enhancements and general script cleanup [ichim-david]
- Add "Connecting to chat..." info [alecghica]
- Various smaller improvements and bugfixes [jcbrand]


0.1.0 (2012-06-12)
------------------

- Created [jcbrand]
