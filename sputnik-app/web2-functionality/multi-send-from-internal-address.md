# Multi-Send from Internal Address

In the [**Personal Account**](../personal-account.md), the [**User**](../../glossary-of-terms-and-scheme/user.md) can send tokens or NFTs from the [**Internal Address**](../../glossary-of-terms-and-scheme/internal-address.md) by a list that consists of blockchain-addresses, usernames, or emails&#x20;

For this:&#x20;

* The [**User**](../../glossary-of-terms-and-scheme/user.md) must select "Multi-Send" in the [**Personal Account**](../personal-account.md) menu&#x20;
* Select own [**Internal Address**](../../glossary-of-terms-and-scheme/internal-address.md) as the sender&#x20;
* As recipients, specify a list of blockchain-addresses, and/or Telegram, Twitter, Discord usernames, or emails&#x20;
* input the amount and type of tokens to multi-send
* Click on the "Multi-send" button&#x20;

For all recipients to blockchain-addresses, [**Sputnik App**](../) will perform a multi-send transaction from the [**Internal Address**](../../glossary-of-terms-and-scheme/internal-address.md) to blockchain-addresses&#x20;

For all recipients by username and/or email address, [**Sputnik App**](../) will access the [**Internal Record**](internal-record.md), and:

* For all usernames and emails that are associated with blockchain-addresses in the [**Internal Record**](internal-record.md) - [**Sputnik App**](../) will perform a multi-send transaction from the [**Internal Address**](../../glossary-of-terms-and-scheme/internal-address.md) to the blockchain-addresses&#x20;
* For all usernames and emails that are not associated with blockchain-addresses in the [**Internal Record**](internal-record.md) - [**Sputnik App**](../) will make a transaction to the [**App Address**](../../glossary-of-terms-and-scheme/app-address.md) and record information into the [**Internal Record**](internal-record.md) that these tokens or NFTs should be sent on [**Internal Addresses**](../../glossary-of-terms-and-scheme/internal-address.md) of users who will link the specified usernames or emails in their [**Personal Account**](../personal-account.md)&#x20;
* If no one links these usernames or emails in their [**Personal Account**](../personal-account.md) within a year, [**Sputnik App**](../) will send these tokens or NFTs from the [**App Address**](../../glossary-of-terms-and-scheme/app-address.md) to the [**Sputnik Network App-chain**](../../sputnik-network-app-chain/) **Community Pool**&#x20;

Sending tokens or NFTs from a [**Personal Address**](../../glossary-of-terms-and-scheme/personal-address.md) by a list consisting of blockchain-addresses, usernames and/or emails is a [**Web3 functionality**](../web3-functionality/), and [**Sputnik App**](../) does not have access to tokens or NFTs on a user's [**Personal Address**](../../glossary-of-terms-and-scheme/personal-address.md), even if the [**User**](../../glossary-of-terms-and-scheme/user.md) has linked a [**Personal Address**](../../glossary-of-terms-and-scheme/personal-address.md) in the [**Personal Account**](../personal-account.md)
