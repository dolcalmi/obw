Simple Bitcoin Wallet (aka SBW) is an [IMMORTAN](https://github.com/btcontract/IMMORTAN)-powered non-custodial Bitcoin wallet for Android with extensive Lightning Network support. It is fully autonomus and does not rely on any kind of centralized service (such as Google services, routing servers, special LSP nodes etc). It is the first mobile wallet which supports routing of 3rd-party Lightning payments and thus allows users to avoid private channel closings as well as earn routing fees in a non-custodial way.    

<a href="https://play.google.com/store/apps/details?id=com.btcontract.wallet"><img alt="Get it on Google Play" src="https://play.google.com/intl/en_us/badges/images/apps/en-play-badge.png" height="80pt"/></a>&nbsp;<a href="https://f-droid.org/repository/browse/?fdid=com.btcontract.wallet"><img alt="Get it on F-Droid" src="https://f-droid.org/wiki/images/5/55/F-Droid-button_get-it-on_bigger.png" height="80pt"/></a>  

## Bitcoin part roadmap

- [ ] Implement BIP157/158, let users choose between Electrum and Client Side Filters as a sync mechanism.
- [ ] Support watch-only Bitcoin wallets for xPub importing from hardware wallets.
- [ ] Allow Lightning channels to be funded from imported hardware wallets.
- [ ] Add RBF-based outgoing transaction boosting and cancelling.
- [ ] Add CPFP-based incoming transaction boosting.
- [ ] Implement Taproot wallet type.

## Lightning part roadmap

- [ ] Finalize and enable private hosted channels.
- [ ] Achieve complete LNURL spec support (as far as non-custodial wallet can go).
- [ ] Incorporate Rene Pickhardt and Stefan Richter [research](https://arxiv.org/abs/2107.05322) to futher improve pathfinding.
- [ ] Develop an Eclair plugin which would allow full LN nodes to easily utilize SBW routing capabilities.
- [ ] Develop a decentralized backup Eclair plugin which would allow channels to be restored without closing.
- [ ] Implement Addon system for integration of 3rd party Lightning-enabled services.
- [ ] Implement UI for fine controlling of routed Lightning payments.
