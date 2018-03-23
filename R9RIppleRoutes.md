![Ripple](/images/ripple.png)

# What is Ripple?
Ripple is a network of computers which use the [Ripple consensus algorithm]
(http://ripplescan.com/accounts/rPVMhWBsfF9iMXYj3aAzJVkPDTFNSyWdKy)
to atomically settle and recordtransactions on a secure distributed
database, the Ripple Consensus Ledger(RCL). Because of its distributed nature,
the RCL offers transaction immutabilitywithout a central operator. The RCL 
contains a built-incurrency exchange and itspath-finding algorithm finds 
competitive exchange rates across order booksand currency pairs.

R9RIppleRoutes 
Account rPVMhWBsfF9iMXYj3aAzJVkPDTFNSyWdKy
Balances
http://ripplescan.com/accounts/rbwE6wsxzYat1YyGGxzAwq6wBSF5MdoAg

Transactions
Creation
Account Balances
Search:
Currency	Value	Counterparty

http://ripplescan.com/accounts/rHGotDKeWvwns12E1A9SMUCaW7U42HZpVr

BTC	0.000000	rfdkfsTy5mYaMZhsnbSmwz9v8bgKvCLF5k

BTC	0.000000	rJhcNXqDfAvZVAE5xnxmJ1cTwdPwubSx6u

BTC	0.000000	rupiahgZvKp1qaP6hqAqAZ3A44ARcnGSM

BTC	0.000000	rEydBn69dkR3dTNTYXjTu8NRrQvQ5GwTZW

BTC	0.000000	rGDvGC9rHALGBXRLaTAfQVtfydtTh8Q1qb

BTC	0.000000	rNii15cVeKHxdfCX4mzXVQXfdf3xB3DDq6

http://ripplescan.com/accounts/r9Xc9N4LpQGcem9yDWLV91186jY6zJRrR9

BTC	0.000000	rfmVk6FYb55DGtxTYwPRaM3Uvvq8joVoJc

BTC	0.000000	rPRuysDxGUiqnMmTZoAihXijcwPnP1r64U

BTC	0.000000	rpmHuwqCMDAiMe8nCjmC5E7GAKiaS6qgh8

BTC	0.000000	r9bDi4hogdCx3vCjnwtFEAUhT5fwgzmyUc

BTC	0.000000	rP5qvdY6AgvmM4fYMxscC5PjkGfKqwnwwE

http://ripplescan.com/accounts/rJAU2GZgVDMSXbYvppFSEqGoZyKaCtCRRR

EUR	0.000000	rGVZ8GUQ62wqhs3617n4poPuvLEYtEUF2t

GCB	0.000000	rHGotDKeWvwns12E1A9SMUCaW7U42HZpVr

GSM	0.000000	rPRuysDxGUiqnMmTZoAihXijcwPnP1r64U

IDR	0.000000	rPRuysDxGUiqnMmTZoAihXijcwPnP1r64U

PYC	0.000000	rHGotDKeWvwns12E1A9SMUCaW7U42HZpVr

http://ripplescan.com/accounts/rNdwi8ain5ibXNB9A7H3zzKtSxgVzAqqAe

USD	0.000000	rLuXhVBS86bCMCJehu2xHWwbFgJkWENmz

USD	0.000000	rHEvchpCJHp18HaVQtxLgEyyth9uHGH6yc

USD	0.000000	rnLgGey2Mwg6hcqW6uyjKffSYuifFMikJg

USD	0.000000	rPRuysDxGUiqnMmTZoAihXijcwPnP1r64U

USD	0.000000	rP5qvdY6AgvmM4fYMxscC5PjkGfKqwnwwE

http://ripplescan.com/accounts/rvYAfWj5gh67oV6fW32ZzP3Aw4Eubs59B

http://ripplescan.com/accounts/rbwE6wsxzYat1YyGGxzAwq6wBSF5MdoAg

GCB/BTC Trade   rPVMhWBsfF9iMXYj3aAzJVkPDTFNSyWdKy XRP	1,033,624,904.186635	

### Key Features
- **Distributed**
  - Direct account-to-account settlement with no central operator
  - Decentralized global market for competitive FX
- **Secure**
  - Transactions are cryptographically signed using ECDSA or Ed25519
  - Multi-signing capabilities
- **Scalable**
  - Capacity to process the world’s cross-border payments volume
  - Easy access to liquidity through a competitive FX marketplace

## Cross-border payments
Ripple enables banks to settle cross-border payments in real-time, with
end-to-end transparency, and at lower costs. Banks can provide liquidity
for FX themselves or source it from third parties.

As Ripple adoption grows, so do the number of currencies and counterparties.
Liquidity providers need to maintain accounts with each counterparty for
each currency – a capital- and time-intensive endeavor that spreads liquidity
thin. Further, some transactions, such as exotic currency trades, will require
multiple trading parties, who each layer costs to the transaction. Thin
liquidity and many intermediary trading parties make competitive pricing
challenging.

![Flow - Direct](images/flow1.png)

### XRP as a Bridge Currency
Ripple can bridge even exotic currency pairs directly through XRP. Similar to
USD in today’s currency market, XRP allows liquidity providers to focus on
offering competitive FX rates on fewer pairs and adding depth to order books.
Unlike USD, trading through XRP does not require bank accounts, service fees,
counterparty risk, or additional operational costs. By using XRP, liquidity
providers can specialize in certain currency corridors, reduce operational
costs, and ultimately, offer more competitive FX pricing.

![Flow - Bridged over XRP](images/flow2.png)

# rippled - Ripple server
`rippled` is the reference server implementation of the Ripple
protocol. To learn more about how to build and run a `rippled`
server, visit https://ripple.com/build/rippled-setup/

[![travis-ci.org: Build Status](https://travis-ci.org/ripple/rippled.png?branch=develop)](https://travis-ci.org/ripple/rippled)
[![codecov.io: Code Coverage](https://codecov.io/gh/ripple/rippled/branch/develop/graph/badge.svg)](https://codecov.io/gh/ripple/rippled)

### License
`rippled` is open source and permissively licensed under the
ISC license. See the LICENSE file for more details.

#### Repository Contents

| Folder  | Contents |
|---------|----------|
| ./bin   | Scripts and data files for Ripple integrators. |
| ./build | Intermediate and final build outputs.          |
| ./Builds| Platform or IDE-specific project files.        |
| ./doc   | Documentation and example configuration files. |
| ./src   | Source code.                                   |
| ./test  | Javascript / Mocha tests.                      |


Some of the directories under `src` are external repositories inlined via
git-subtree. See the corresponding README for more details.

##For more information:

* [Ripple Knowledge Center](https://ripple.com/learn/)
* [Ripple Developer Center](https://ripple.com/build/)
* [Ripple Whitepapers & Reports](https://ripple.com/whitepapers-reports/)
  * [Ripple Consensus Whitepaper](https://ripple.com/consensus-whitepaper/)
  * [Ripple Solutions Guide](https://ripple.com/files/ripple_solutions_guide.pdf)

To learn about how Ripple is transforming global payments visit
[https://ripple.com/contact/](https://ripple.com/contact/)

- - -

Copyright © 2015, Ripple Labs. All rights reserved.

Portions of this document, including but not limited to the Ripple logo,
images and image templates are the property of Ripple Labs and cannot be
copied or used without permission.
