
tx_clients 0.3.1 (2016-09-09)
================================

Deprecations and Removals
-------------------------
- Updated dependencies to twisted 16.4.0
- Updated dependencies to pyopenssl 16.0.0
- Updated dependencies to service_identity 16.0.0
- Updated dependencies to wrapt 1.10.0


tx_clients 0.3.0 (2016-08-30)
================================

Features
--------
- Added tx_clients.utils.web.AsyncJSON which is a PushProducer that will help
    to iteratively encode bytes to json in an asynchrnous manner by cooperating
    with objects that implement the IConsumer interface.
- Added the service_identity module which is necessary to perform client side
    cert validation. Adheres to [RFC 6125](http://www.rfc-editor.org/info/rfc6125)

Deprecations and Removals
-------------------------
- Dropped support for the line client and removed txconnpool as a dependency
