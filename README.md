# Decentralized Wordpress Authentication

Decentralized Wordpress Authentication is a WordPress authentication
integration that works with [Decentralized
Identity](https://github.com/jetpen/decent-identity) and
[Decentralized Wallet](https://github.com/jetpen/decent-wallet) in the
[Decentralized Ecosystem](https://github.com/jetpen/decent-ecosystem).

The proposed design keeps authentication challenges and application
sessions in WordPress, using wallet proof delivered through an
asynchronous browser flow and current key resolution from an Identity
Record. It also covers separate consent and user-owned, site-specific
Account Entity onboarding without handling wallet secrets.

The GitHub issues describe a specification effort and implementation
target, not functionality verified as implemented in this
repository. Challenge verification and replay handling, browser
transport, identity disclosure and onboarding, session handoff, and
failure and security behavior remain open design work.
