---
description: How to setup the Elastos Essentials super-wallet.
---

# Essential Setup

{% hint style="info" %}
Before proceeding with the configuration, you must download and install Elastos Essentials:
{% endhint %}

![https://elink.elastos.net/download](../.gitbook/assets/image.png)

## Video Tutorial

{% embed url="https://youtu.be/EFrhyUMVlvg" %}

## Summary

### Step 1: Select the Language

Select one of the Languages supported by <mark style="color:purple;">Essentials</mark>.

![](<../.gitbook/assets/Essentials Setup - Language.png>)

### Step 2: Create a new Identity

By pressing the "<mark style="color:purple;">New</mark>" button you can create a new decentralized identity.

![](<../.gitbook/assets/Essentials Setup - New Identity.png>)

### Step 3: Enter a Name

Enter a _**name**_ of your choice, it will be saved in your _<mark style="color:yellow;">Hive Vault</mark>_, and can be changed later.

![](<../.gitbook/assets/Essentials Setup - Name.png>)

### Step 4: Create the <mark style="color:blue;">Master Password</mark>

The <mark style="color:blue;">Master Password</mark> can contain any character, it will be saved **locally** on your smartphone, and is used to protect the <mark style="color:purple;">super-wallet</mark> from intruders who could access and steal your identity. \
To make transactions or change data, you <mark style="color:red;">**need**</mark>** ** to know the _<mark style="color:blue;">Master Password</mark>_.

{% hint style="warning" %}
The _<mark style="color:blue;">Master Password</mark>_ <mark style="color:blue;"></mark><mark style="color:blue;"></mark> is <mark style="color:red;">**not**</mark> absolutely necessary to restore your identity and your wallet, it is <mark style="color:red;">deleted</mark> and can be <mark style="color:green;">recreated</mark> when Elastos Essentials data is deleted. \
Be sure to[ <mark style="color:orange;"></mark> <mark style="color:orange;"></mark><mark style="color:orange;">**Backup your Mnemonics**</mark>](essential-setup.md#step-6-backup-of-your-mnemonics).
{% endhint %}

![](<../.gitbook/assets/Essentials Setup - Master Password.png>)

### Step 5: Automatic Wallet setup process

At this point, once the <mark style="color:blue;">Master Password</mark> has been created, an automatic process should start which:

* generates and publishes the new <mark style="color:purple;">decentralized identity</mark> (DID) in the public ledger;
* generates and links a <mark style="color:yellow;">Hive Vault</mark> to your own <mark style="color:purple;">decentralized identity</mark> (DID);
* generates a Wallet that is derived from the same <mark style="color:red;">Mnemonic</mark> of the <mark style="color:purple;">decentralized identity</mark> (DID).

![](<../.gitbook/assets/Essentials Setup - Process Screens.png>)

{% hint style="danger" %}
#### **If the process freezes, or takes more than 3 minutes or so, perform this troubleshooting procedure.**
{% endhint %}

<details>

<summary>Resolution Procedure</summary>

1. Close <mark style="color:purple;">**Essentials**</mark> and delete it from Recent apps;
2. Open <mark style="color:purple;">**Essentials**</mark>, on the home screen scroll down, and log out of the "half-created" identity by pressing the "logout" button;
3. You should now be on the Identities screen, proceed by <mark style="color:red;">**deleting**</mark> the old identity, press on the three dots and press <mark style="color:red;">**Delete**</mark>;
4. Create a new Identity starting from[ **Step 1**](essential-setup.md#step-1-select-the-language).

</details>

#### When you return to this screen, you will have <mark style="color:green;">successfully</mark> completed the creation of your First <mark style="color:purple;">**Decentralized Identity**</mark>.

![](<../.gitbook/assets/Essentials Setup - Finals Step.png>)

### Step 6: Backup of your <mark style="color:red;">Mnemonics</mark>

The last step is to _**Backup**_ your _<mark style="color:purple;">**decentralized identity**</mark>_ (DID) and your _<mark style="color:purple;">**Wallet**</mark>_. \
Store in a safe place the _**12 words**_ that are provided to you, because it will be the only way to _<mark style="color:red;">**recover**</mark>_ your Identity and your Funds.

![](<../.gitbook/assets/Essentials Setup - Backup.png>)
