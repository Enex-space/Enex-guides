---
description: How to add a description to your custom token - step by step
---

# 💻 Add a description to custom token

We will use as the example token called: RNR

<figure><img src="../../.gitbook/assets/image (26).png" alt=""><figcaption><p>Test token</p></figcaption></figure>

1\. To add your custom token description you have to go to Enecuum github repository:\
[https://github.com/Enecuum/explorer](https://github.com/Enecuum/explorer)

<figure><img src="../../.gitbook/assets/image (34).png" alt=""><figcaption><p><a href="https://github.com/Enecuum/explorer">https://github.com/Enecuum/explorer</a></p></figcaption></figure>

2\. Fork it to your account's repository

<figure><img src="../../.gitbook/assets/image (25).png" alt=""><figcaption><p>Steps to the fork</p></figcaption></figure>

3\. Check all parameters before the fork

<figure><img src="../../.gitbook/assets/image (42).png" alt=""><figcaption><p>3..2..1 - fork!</p></figcaption></figure>

4\. <mark style="color:green;">Congrats!</mark> The fork is finished.

<figure><img src="../../.gitbook/assets/image (54).png" alt=""><figcaption><p>Your forked repository</p></figcaption></figure>

5\. Select "info" folder

<figure><img src="../../.gitbook/assets/image (57).png" alt=""><figcaption><p>Info</p></figcaption></figure>

5.1. Let's add you **Token Logo** first. To do that - go to "token/logo" folder

<figure><img src="../../.gitbook/assets/image (51).png" alt=""><figcaption><p>token/logo folder</p></figcaption></figure>

5.2. Next step - go into "enq" folder

<figure><img src="../../.gitbook/assets/image (31).png" alt=""><figcaption><p>"enq" folder</p></figcaption></figure>

5.3. Then, add a new file

<figure><img src="../../.gitbook/assets/image (9).png" alt=""><figcaption><p>new file</p></figcaption></figure>

5.4. Download your logo in formats <mark style="color:green;">.png</mark> or <mark style="color:green;">.jpg</mark>. The resolution <mark style="color:green;">512x512</mark> is good enough. \
<mark style="color:red;">Files larger than 256KB will be ignored.</mark>

<figure><img src="../../.gitbook/assets/image (2).png" alt=""><figcaption><p>Download your logo </p></figcaption></figure>

6\. Let's move forward, and add a description. Go into "info"

<figure><img src="../../.gitbook/assets/image (3).png" alt=""><figcaption><p>info</p></figcaption></figure>

6.1. Open "token-info-storage-enq.json"

<figure><img src="../../.gitbook/assets/image (48).png" alt=""><figcaption><p>token-info-storage-enq.json</p></figcaption></figure>

6.2. Select "Edit"

<figure><img src="../../.gitbook/assets/image (28).png" alt=""><figcaption><p>inside the token-info-storage-enq.json</p></figcaption></figure>

6.3. Copy the sample description

<figure><img src="../../.gitbook/assets/image (4).png" alt=""><figcaption><p>sample description</p></figcaption></figure>

6.4. Paste the copy before the sample description&#x20;

<figure><img src="../../.gitbook/assets/image (22).png" alt=""><figcaption><p>seconds before the paste</p></figcaption></figure>

6.5 Insert your token ID&#x20;

<figure><img src="../../.gitbook/assets/image (53).png" alt=""><figcaption><p>token ID</p></figcaption></figure>

6.6. Copy ID from your token "page" in explorer:

<figure><img src="../../.gitbook/assets/image (17).png" alt=""><figcaption><p>Token ID</p></figcaption></figure>

6.7. Paste ID to file to your token description block

<figure><img src="../../.gitbook/assets/image (49).png" alt=""><figcaption><p>token description block</p></figcaption></figure>

6.8. Insert all info you neet to special fields. <mark style="color:yellow;">Don't forget about the Logo.</mark>

<figure><img src="../../.gitbook/assets/image (8).png" alt=""><figcaption><p>Adding the info</p></figcaption></figure>

**Available fields:**

```javascript
    "token_id":"",
    "website":"",
    "logo": "",
    "media": {                            
        "twitter": "",
        "medium": "",
        "github": "",
        "forklog": "",
        "bitcointalk": "",
        "linkedin": "",
        "youtube": "",
        "qq": "",
        "weixin": "",
        "telegram": "",
        "reddit": ""
    },
    "documents": {
        "whitepaper": "",
        "guides": ""
    },     
    "description": {
        "en": "",
        "de": "",
        "fr": "",
        "ru": "",
        "pt": "",
        "vi": "",
        "in": "",
        "tr": ""
    },
    "coingecko_id": "" 
```

6.9. Add a short description and commit your changes.

<figure><img src="../../.gitbook/assets/image.png" alt=""><figcaption><p>Add a short description</p></figcaption></figure>

7\. Go to "Pull request"

<figure><img src="../../.gitbook/assets/image (43).png" alt=""><figcaption><p>Pull request</p></figcaption></figure>

8\. Select "New pull request"

<figure><img src="../../.gitbook/assets/image (15).png" alt=""><figcaption><p>New pull request</p></figcaption></figure>

9\. Check all repositories and branches. Check your data.

<figure><img src="../../.gitbook/assets/image (40).png" alt=""><figcaption><p>New pull request</p></figcaption></figure>

10\. Then click "Create pull request"

<figure><img src="../../.gitbook/assets/image (7).png" alt=""><figcaption><p>Create pull request</p></figcaption></figure>

11\. Create pull request

{% hint style="warning" %}
Add you project short summary: 1-2 sentences;

Add your contact;

Add the project website (if exist);
{% endhint %}

<figure><img src="../../.gitbook/assets/image (52).png" alt=""><figcaption><p>Create pull request</p></figcaption></figure>

12\. Copy pool request number

<figure><img src="../../.gitbook/assets/image (24).png" alt=""><figcaption><p>Copy pool request number</p></figcaption></figure>

13\. Go to your wallet in Enecuum network and send transaction:

{% hint style="danger" %}
Address: 02833f453fb8bf10cc5e8fd362d563851543559f3ea6e662ef114d8db8f72dda19

Token: ENQ

Amount: 0 ENQ

Data: _(insert here your Pull request number)_
{% endhint %}

<figure><img src="../../.gitbook/assets/image (50).png" alt=""><figcaption><p>transaction</p></figcaption></figure>

14\. Copy transaction Hash

<figure><img src="../../.gitbook/assets/image (56).png" alt=""><figcaption><p>transaction hash</p></figcaption></figure>

15\. Paste it as a comment in your pull request

<figure><img src="../../.gitbook/assets/image (55).png" alt=""><figcaption><p>Paste transaction hash</p></figcaption></figure>

16\. Anticipate the team to check your pool request. Generally, it takes 1-2 weeks to check.
