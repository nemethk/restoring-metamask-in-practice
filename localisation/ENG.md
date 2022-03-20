# ENG
>⚠️ **DISCLAIMER** ⚠️
>- Use the explained methods on your own risk.
>- Create a test profile and practice on them before restoring a real wallet.
>- The shared passphrase is for practice purposes only. DO NOT USE the passphrase from manual in real life.

> ⚠️ **IMPORTANT NOTE** ⚠️<br> **Do not share your your secret recovery phrase with anyone.**

## Table of Contents
- [ENG](#eng)
  * [Table of Contents](#table-of-contents)
  * [Introduction](#introduction)
    + [Browser](#browser)
    + [Hardware wallet](#hardware-wallet)
  * [Creating a Metamask account](#creating-a-metamask-account)
  * [Restoring a Metamask account with a Metamask wallet](#restoring-a-metamask-account-with-a-metamask-wallet)
    + [Restoring process](#restoring-process)
    + [Testing 1](#testing-1)
    + [Testing 2](#testing-2)
    + [Conclusion](#conclusion)
  * [Restoring a Metamask account with a hardware wallet](#restoring-a-metamask-account-with-a-hardware-wallet)
    + [Ledger Nano S](#ledger-nano-s)
    + [Use Metamask with a hardware wallet](#use-metamask-with-a-hardware-wallet)

## Introduction
### Browser
The manual is created based on Brave and Firefox browsers. For both of them official Metamask extension is available.

> ℹ️ INFO <br>Creating a new profile in a browser basically will produce a new browser with default settings.

Brave profiles:
- [Metamask 1](../images/A01.png) (red)
- [Metamask 2](../images/B01.png) (green)

### Hardware wallet
For demonstration purposes of hardware wallet I used a Ledger Nano S.

## Creating a Metamask account
The following steps were executed under [_**Metamask 1**_](../images/A01.png) profile.
1. Install Metamask browser extension.
2. [Create a new wallet. It will generate the recovery passphrase.](../images/A02.png)
3. [Make a secure backup of passphrase.](../images/A03.png)
```
impulse enable harsh okay blush force face volcano remind absurd burger vault
```
4. [The initial account has been created (the public and private key pairs).](../images/A04.png)
```
name: Account 1
public key: 0xF7f844FC13f08Ec6B4401e82cD18808E67f6d322
```
5. [Let's add a new account.](../images/A05.png)
6. [The new account is successfully added to the wallet.](../images/A06.png)
```
name: Account 2
public key: 0xb0ae24074899BA96CcCe285141EB0acD2b315520
```
7. [Add the 3rd account.](../images/A07.png)
8. [The public address of the 3rd account.](../images/A08.png)
```
name: Account 3
public key: 0xc4A3877F2eC08fF48D28B7526f09A390d3254523
```
7. [Save the private key of the 3rd account.](../images/A09.png)
```
name: Account 3
privát kulcs: 3def70c36df26560bce748476e56b748a8420718b0038aca63c3fbb77a2c8b07
```

## Restoring a Metamask account with a Metamask wallet
### Restoring process
The following steps were executed under [_**Metamask 2**_](../images/B01.png) profil.
1. Install Metamask browser extension.
2. [The wallet is already existing.](../images/B02.png)
3. [Restore the wallet from the saved passphrase.](../images/B03.png)
4. [The details of the initial account.](../images/B04.png)
```
name: Account 1
public key: 0xF7f844FC13f08Ec6B4401e82cD18808E67f6d322
```
> 👉 The public key is the same as originally.

5. [Add a new account as earlier.](../images/B05.png)
6. [The details of the created account:](../images/B06.png)
``` 
name: Account 2
public key: 0xb0ae24074899BA96CcCe285141EB0acD2b315520
``` 
> 👉 The public key is the same as under 1st profile for "Account 2".

7. [The "Account 3" will be restored from the saved private key.](../images/B07.png)
8. [Specify the private key.](../images/B08.png)
9. [The details of the restored account:](../images/B09.png)
```
name: Account 3
public key: 0xc4A3877F2eC08fF48D28B7526f09A390d3254523
```
> 👉 The public key is the same as under 1st profile for "Account 3".

> 👉 In the menu there is the "imported" tag near account.

### Testing 1
The following steps were executed under _**Metamask 2**_ profile.
1. [For testing purposes, create a new account.](../images/B10.png)
2. [Let's name it "Account 4".](../images/B11.png)
3. [The result is a little bit different than expected.](../images/B12.png)
4. [Try to rename. There is an error message.](../images/B13.png)
5. [For testing purposes, create one more account.](../images/B14.png)
6. [The details of the "Account 5". There is an error message as well.](../images/B15.png)

### Testing 2
The following steps were executed under _**Metamask 1**_ profile.
1. [For testing purposes, create a new account.](../images/B17.png)
2. [The details of the "Account 5". No error message.](../images/B17.png)
```
name: Account 5
public key: 0x85deE2C51718235ac0B0CaD56F267B89bC18ADdF
```

### Conclusion
- In the restored wallet adding a new account from the menu will generate the same accounts as originally.
- An account could be restored with the appropirate private key (Account 3).
- If we add a new account from the menu in case of a wallet which is restored from a private key, it could produce errors. It requires attention.

## Restoring a Metamask account with a hardware wallet
### Ledger Nano S
1. Restore keys with the passphrase. Enter words one by one.
2. Install Ethereum application on the hardware wallet.
3. Connect Ledger device to the Ledger Lie.
4. [The passphrase has generated the same initial account:](../images/C01.png)
```
name: Ethereum 1
public key: 0xF7f844FC13f08Ec6B4401e82cD18808E67f6d322
```
> 👉 The public key is the same as in Metamask for "Account 1".

### Use Metamask with a hardware wallet
1. [Install the Metamask extension for Firefox.](../images/C02.png)
2. [Create an account because only on that way we are able to login to Metamask. This account will not be used.](../images/C03.png)
3. [Connect hardware wallet. ](../images/C04.png)
4. [Select the appropriate hardware wallet. In current case it is Ledger.](../images/C05.png)
5. [In the appears list only the first address is known from earlier.](../images/C06.png)
6. [From the drop down menu select `BIP44` protocol.](../images/C07.png)
7. [In this way, addresses that are known from before will appear.](../images/C08.png)
> 👉 Four accounts have been created in Metamask. The list shows the same public keys, in the same order as originally in Metamask.

> ℹ️ Scroll through the list. There are several key pairs from the same passphrase.

8. Finally confirm the restored accounts:
- [The "Ledger 1" is the same as "Account 1"](../images/C09.png)
```
public key: 0xF7f844FC13f08Ec6B4401e82cD18808E67f6d322
```
- [The "Ledger 2" is the same as "Account 2"](../images/C10.png)
```
public key: 0xb0ae24074899BA96CcCe285141EB0acD2b315520
```
- [The "Ledger 3" is the same as "Account 3"](../images/C11.png)
```
public key: 0xc4A3877F2eC08fF48D28B7526f09A390d3254523
```
- [The "Ledger 4" is the same as "Account 5"](../images/C12.png)
```
public key: 0x85deE2C51718235ac0B0CaD56F267B89bC18ADdF
```