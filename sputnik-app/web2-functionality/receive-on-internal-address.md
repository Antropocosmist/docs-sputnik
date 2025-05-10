# Receive on Internal Address

When sending tokens or NFTs by username or email, [**Sputnik App**](../) accesses the Internal Record&#x20;

If the [**Internal Record**](internal-record.md) does not contain information about the connection of the username or email with the user's [**Internal Address**](../../glossary-of-terms-and-scheme/internal-address.md):&#x20;

* Tokens or NFTs are sent to the [**App Address**](../../glossary-of-terms-and-scheme/app-address.md), and [**Sputnik App**](../) records information into the [**Internal Record**](internal-record.md) that these tokens arrived via the specified username or email&#x20;
* Once a [**User**](../../glossary-of-terms-and-scheme/user.md) connects to [**Sputnik App**](../) with the specified username or email, [**Sputnik App**](../) will look into the [**Internal Record**](internal-record.md), see that the [**App Address**](../../glossary-of-terms-and-scheme/app-address.md) has tokens or NFTs for that user, and send those tokens from the [**App Address**](../../glossary-of-terms-and-scheme/app-address.md) to the [**Internal Address**](../../glossary-of-terms-and-scheme/internal-address.md)
* If tokens or NFTs were sent via username or email, but during the year no one attached these usernames or email to their [**Personal Account**](../personal-account.md) - [**Sputnik App**](../) will send these tokens from the [**App Address**](../../glossary-of-terms-and-scheme/app-address.md) to the [**Sputnik Network App-chain**](../../sputnik-network-app-chain/) **Community Pool**&#x20;

If the [**Internal Record**](internal-record.md) contains information about the association of a username or email with the user's [**Internal Address**](../../glossary-of-terms-and-scheme/internal-address.md):&#x20;

* Tokens or NFTs will be sent to the user's [**Internal Address**](../../glossary-of-terms-and-scheme/internal-address.md), which is associated with the specified username or email&#x20;

If the [**Internal Record**](internal-record.md) contains information about the association of a username or email with the user’s [**Personal Address**](../../glossary-of-terms-and-scheme/personal-address.md):&#x20;

* Tokens or NFTs will be sent to the user’s [**Personal Address**](../../glossary-of-terms-and-scheme/personal-address.md), which is associated with the specified username or email
