---
description: GEAR token contract and distribution information.
---

# GEAR Overview

GEAR token is an ERC20 utility token, starting off as a governance token for the protocol - and then possibly taking any other new function the DAO could envision for it. The supply of GEAR is capped at 10,000,000,000 (10 billion) which can't be technically changed. See in source code.

Token contract: [0xba3335588d9403515223f109edc4eb7269a9ab5d](https://etherscan.io/token/0xba3335588d9403515223f109edc4eb7269a9ab5d)\
Decimals: 18\
Symbol: $GEAR

## GEAR Distribution

{% hint style="success" %}
All of the vestings can be verified on-chain, no trust required. Community retains the largest portions both in terms of the distribution and in terms of voting weights.

**You can check those by going to the TokenDistributor contract**:

* check contributorsList \[3] to find yourself/someone;
* fill in your/eligible address from \[3] into \[2] contributorVestingContracts. That will give you the corresponding personal vesting contract for that address.
{% endhint %}

{% embed url="https://etherscan.io/address/0xf7512B2B20Cf427ADD8b01D8CDEef97a4B0E2C27#readContract" %}
[https://etherscan.io/address/0xf7512B2B20Cf427ADD8b01D8CDEef97a4B0E2C27#readContract](https://etherscan.io/address/0xf7512B2B20Cf427ADD8b01D8CDEef97a4B0E2C27#readContract)
{% endembed %}

GEAR supply has been split according to a handful of contributor groups:

![Early community maintain majority of voting power. See governance page. Or the early article.](<../.gitbook/assets/Screen Shot 2021-12-10 at 18.26.31.png>)

{% hint style="info" %}
As a result of community members performing [on-chain sleuthing](https://gov.gearbox.fi/t/botting-findings/88/148) \[finding bot behavior in tester accounts], a solid portion of GEAR tokens was saved and repurposed for other genuine user activities. If you find slightly different numbers online on GEAR distribution, please treat the information below as the most up-to-date source.
{% endhint %}

### Community Portion: \~58%. No vesting.

* **DAO Treasury Multisig**: originally 51.00%. Up to DAO to decide, managed by the DAO-enacted [treasury multisig](../governance/setup/guards-multisigs.md#financial-treasury-multisig-or-5-9). Address[: 0x7b065fcb0760df0cea8cfd144e08554f3cea73d1](https://etherscan.io/address/0x7b065fcb0760df0cea8cfd144e08554f3cea73d1).
  * Out of that, 2.766% to [DAO Round Part 1](https://gov.gearbox.fi/t/gip-10-strategic-dao-funding-proposal-part-1/1315/17). Lockup ends on July 15 of 2023, upon which 1 year of linear vesting will take place throughout 365 days, until July 2024.
  * Out of that, 1.057% to [DAO Round Part 2](https://gov.gearbox.fi/t/gip-18-dao-round-part-2-community-proposal/1374/112). Lockup ends on September 15 of 2023, upon which 1 year of linear vesting throughout 365 days, until September 2024.
  * Out of that, 0.1% to [VIBES metaDAO](https://gov.gearbox.fi/t/gip-13-vibes-internal-metadao-focusing-on-onboarding-marketing/1387) committee for marketing Q3+ 2022.

{% hint style="success" %}
All further distributions can be found in [monthly-quarterly DAO reports](https://gearboxprotocol.notion.site/Monthly-Reports-6849871a9bae44dfb903531c0a997e8f) & budgets. For example, the \~3% cumulative passive LPs & Credit Account users liquidity mining. The proposal and details can be found on forum, currently distributor contract [is this](https://etherscan.io/address/0xa7df60785e556d65292a2c9a077bb3a8fbf048bc).
{% endhint %}

* **Credit Account Mining**: 5%. Mined by 5,000 participants in the ceremony. No vesting.

{% content-ref url="../overview/launch-phases/credit-account-mining.md" %}
[credit-account-mining.md](../overview/launch-phases/credit-account-mining.md)
{% endcontent-ref %}

* **Community Testers**: \~1.085%. No vesting. _Originally, 1.267% were allocated, but community members performed_ [_on-chain sleuthing_](https://gov.gearbox.fi/t/botting-findings/88/148) _and reduced this number._ [_Old istributor contract_](https://etherscan.io/address/0xadc72d5c034c189f5c0b03c7bac21ac50b9d01f1)_._&#x20;
* **Early Discord members**: \~0.348%. No vesting. _Originally, 0.476% were allocated, but after 9 months of claimants now showing up, the tokens were repurposed._ [_Old distributor contract_](https://etherscan.io/address/0xadc72d5c034c189f5c0b03c7bac21ac50b9d01f1)_._&#x20;

{% content-ref url="../overview/launch-phases/early-drop.md" %}
[early-drop.md](../overview/launch-phases/early-drop.md)
{% endcontent-ref %}

* **Retroactive rewards for 2021**: approximately 0.5% \[with 0.041% repurposed for other activities]. No vesting. As we set on to a few stages of the community distribution, we expected technical difficulties with some claimants. Instead, community members performed [on-chain sleuthing](https://gov.gearbox.fi/t/botting-findings/88/148) an a good portion of GEARs was saved. This was [decided to be used as a retroactive LP + CA GEAR reward](https://gov.gearbox.fi/t/gip-22-gearbox-v2-liquidity-mining-programs/1550) program. _This is from where the drop for testers and discord users happened, and remaining used for repurposed activities like retroactive drop._

{% hint style="info" %}
_Launch time_ is technically TGE, when the DAO was formed: December 15, 2021. If you read this in December 2022, treat this as the start of vesting, linearly over 1+ years.
{% endhint %}

### Initial External Contributors: 1.28%. Locked > 1 year + vesting.

These are some amazing people who have contributed to the technical development but weren't committing capital, yet we wanted to incentivize them to work further. Lockup: 12 months since token deployment (launch), and then linear vesting over 18 months.&#x20;

### Initial сore contributors: 29.20%. Locked > 1 year + vesting.

**Initial core members 20%** (usually referred to as "team" but here the DAO took over during the launch time, so that naming wouldn't make sense). Lockup: 12 months since token deployment (launch), and then linear vesting over 18 months.

**Initial contributors 9.20%** (usually referred to as "investors" but here they were all forced to put a lot of time, so that naming wouldn't make sense - see at the bottom of the page for details). Lockup: 12 months since token deployment (launch), and then linear vesting over 12 months. See their contributions and work over 2021 clearly here:

{% embed url="https://medium.com/gearbox-protocol/product-evolution-from-an-idea-to-an-app-0-to-1-contributors-united-832154e3c7ba" %}

### Initial company wallet: 11.52%. Locked > 1 year + vesting.

**Company wallet** lockup: 12 months since token deployment (launch), and then linear vesting over 18 months. Address: [0xa8b1d00b1d224e83760963e361b7f676581a622d](https://etherscan.io/address/0xa8b1d00b1d224e83760963e361b7f676581a622d). This is outside of the scope of the DAO, and can be used for discretionary activities. This is a company that kickstarted the first protocol development pre-DAO launch. Not related to the DAO. _Keep in mind that some of those reserves were used to onboard new pre-DAO contributors, auditor engagements, external work performed before the DAO was established, etc._

<figure><img src="../.gitbook/assets/IMG_6227 1.png" alt=""><figcaption><p>The information on rounds, aka early contributors with vested GEAR, can be found at the bottom of <a href="https://gearboxprotocol.notion.site/Gearbox-DAO-23966f122ae4421492819242b30a0e7a">Notion page</a>.</p></figcaption></figure>
