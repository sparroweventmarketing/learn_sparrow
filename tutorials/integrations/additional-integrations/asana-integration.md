# Asana Integration

{% hint style="info" %}
### Supported Plans

Enterprise
{% endhint %}

### Description

This automation allows you to import your Sparrow task templates in to an Asana project.  Optionally, add it to a section.

## Set Up

1. Ask your account manager to activate the Asana Integration.&#x20;
2. **Permission in bot@getsparrow.co** as a user on your Asana account
3. Head to your Event Templates (More > Event Templates) and **Create a new Event Template**
4. In the Event Template, go to **Settings > Asana Integration > Enable Asana Sync**
5. You will need to complete your Workspace ID, Asana Project ID and an optional Section ID.  Your account manager can help fill this out.

## **Creating Tasks and  Subtasks that Sync to Asana**

Sparrow creates tasks in Asana as folllows:

1. Asana Main Task - the Event Name
   1. Asana Subtask - The Sparrow Task Name
      1. Asana sub-subtasks - Each "checkbox" item within the Sparrow task

<figure><img src="../../../.gitbook/assets/CleanShot 2025-01-31 at 14.40.00.jpg" alt=""><figcaption></figcaption></figure>

## Using the Automation

When you select an Event Template Automation in a Sparrow event, simply choose your Asana-synced event template and run it.  Sparrow will handle the rest, creating the Asana tasks for you.



## Notes & Details

* The Asana integration supports **Due Dates** but does not support assignments.
* You can use [merge fields](../../../more-info/supported-merge-tags.md) in both the title and description to replace fields with event data.
* Anything in the Task Description field that _is not_ a checkbox line item will be in the task description field.

