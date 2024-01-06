# Automations

## Automations Overview

Sparrow is built on an open platform and has a developing automation platform to help event marketers work faster and with less errors.

Automations come in two forms: **Passive** automations are ways for Sparrow to **ingest** information automatically, such as event info, ticket counts, advertising spends, etc. **Active** automations are triggered within the platform to create event assets, such as marketing plans, internal tasks, graphics, etc.

{% hint style="info" %}
Tip: Since many users’ needs are different, automations are built with a lot of flexibility in mind. Your account manager will be hands-on in building out each automation to suit your needs.
{% endhint %}

***

### Active Automations

There are automations that Active automations can be built in two areas:

* In the main navigation click **Automations** **or**
* Within an event, click the three dots next to the **Tasks** tab and select **Automations**

Once you are in the automations panel, you can click **+ Add New** to create a new automation.

***

### Passive Automations

#### Prism

**Summary**

Prism can currently send the following fields over into Sparrow:

* _Event Name_
* _Headliner_
* _Support_
* _Event Date_
* _Announce Date/Time_
* _On Sale Date/Time_
* **Projected Attendance** - As a sum of all “estimated ticket sales” within Prism

A sync to Sparrow is initiated on these actions within Prism:

* _Confirm_
* _Unconfirm_
* _Delete_

Please Note: Currently a sync from Prism to Sparrow is cast _only_ when one of the above events occur. If, for example, a show date changes in Prism, you _must_ unconfirm/reconfirm it to re-sync to Sparrow.

**Setup**

The setup uses webhooks cast from Prism to communicate with Sparrow. To set up, simply follow these steps and ask your account manager if you have any questions.

1.  **Log into Prism and head over to the User Menu > Settings > Web Integrations**


2.  **Scroll down to “Webhooks”, click “Add Webhook”. A popup will appear. Enter the information for each point on the list below and click “Save”:**

    ```xml
    Webhook Name = sparrow_confirm
    Webhook Action = Event Confirmed
    Webhook URL = https://hook.getsparrow.co/webhook/c0e57e65-a999-4822-9d40-0b9fc32d3a47
    ```

    ```xml
    Webhook Name = sparrow_delete
    Webhook Action = Event Deleted
    Webhook URL = https://hook.getsparrow.co/webhook/c0e57e65-a999-4822-9d40-0b9fc32d3a47
    ```

    ```xml
    Webhook Name = sparrow_unconfirm
    Webhook Action = Event Unconfirmed
    Webhook URL = https://hook.getsparrow.co/webhook/c0e57e65-a999-4822-9d40-0b9fc32d3a47
    ```

The final results should look like this:

<figure><img src="../../.gitbook/assets/CleanShot 2022-12-28 at 17.07.19.jpg" alt=""><figcaption></figcaption></figure>

Once completed, please let your account manager know to test the integration.

#### Ticketing

#### Meta Ads

***
