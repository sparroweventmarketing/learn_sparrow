# Connecting Prism

{% embed url="https://www.youtube.com/watch?v=43VXJB-5zLo" %}

### Step 1 - Log into Prism

#### From your browser, log into your Prism account.&#x20;

{% hint style="info" %}
Since Sparrow uses your accounts credentials to integrate, please make sure you have access to view and edit all events, venues, and settings.
{% endhint %}

***

### Step 2 - Open up your browsers "Inspect" tools

Left-click with your mouse and click on "Inspect" or "Inspect Element" in the menu.

<figure><img src="../../.gitbook/assets/CleanShot 2023-12-19 at 10.56.05.jpg" alt=""><figcaption></figcaption></figure>

***

### Step 3 - Click on "Console"

In the panel that appears, click "Console" along the top menu bar.

<figure><img src="../../.gitbook/assets/CleanShot 2023-12-19 at 11.01.09 (1).jpg" alt=""><figcaption></figcaption></figure>

***

### Step 4 - Copy your API key

In the console, copy and paste the following and hit Enter to copy your  API Key to your clipboard.

```
clear();let apiKey="Here's the Prism API Key: " + localStorage.getItem('token');copy(apiKey);console.log("Copied to your clipboard! Paste this in an email to your Sparrow rep. \n\n" + apiKey);
```

<figure><img src="../../.gitbook/assets/CleanShot 2023-12-19 at 11.05.38.jpg" alt=""><figcaption></figcaption></figure>

***

### Step 5 - Paste your API Key to your Account Manager

Your API key is now copied to your clipboard.  Paste that into an email to your account manager. &#x20;

{% hint style="info" %}
Your API Key should look like a very long string of characters.
{% endhint %}

<figure><img src="../../.gitbook/assets/CleanShot 2023-12-19 at 11.41.02.jpg" alt=""><figcaption></figcaption></figure>
