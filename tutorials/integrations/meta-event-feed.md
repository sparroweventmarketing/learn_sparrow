# Meta Event Feed

Sparrow can pass event information into Meta's 'Commerce Manager'.  This allows you to use Sparrow data to quickly create Meta ads, as well as have an 'always on' carousel ads that allow your ads to automatically swap in and out based on what's on sale.

<div align="left">

<figure><img src="../../.gitbook/assets/CleanShot 2023-12-14 at 21.48.05@2x.jpg" alt="" width="250"><figcaption></figcaption></figure>

</div>

### Set up.

1. Ask your account manager to set up the product feed.
2. They will send you a link that will add the feed to your business manager
3. Once the feed is imported into your business manager account, [visit the Commerce Manager here](https://business.facebook.com/commerce/catalogs/) to see your imported events.

### Creating "Product Sets"&#x20;

Within Commerce Manager, "Product Sets" allow you to create segments for your events that you can then advertise as one group.  For example, you can create a segment for just Country events that runs ads only with that genre.

To create a set:

1. Go to Commerce Manager and go to Catalog > Sets
2.  Click "Create Set" and use filters to dynamically choose which events get grouped together.  Reference the table below to help you determine which filters to select.  For example, to group all Country events together you will choose "Custom Label 0 contains Country" as your filter:\


    <figure><img src="../../.gitbook/assets/CleanShot 2023-12-14 at 22.11.27@2x.jpg" alt=""><figcaption></figcaption></figure>
3. Give the product set a name (e.g. Country Shows) and click Create

### Product Mapping Table

<table><thead><tr><th>Meta Commerce Field</th><th width="281.3333333333333">Sparrow Field</th><th>Notes</th></tr></thead><tbody><tr><td>Title</td><td>Event Name</td><td><mark style="color:red;">Required</mark></td></tr><tr><td>Description</td><td>Date (MM/DD) + Event Name</td><td></td></tr><tr><td>Link</td><td>Ticket Link</td><td><mark style="color:red;">Required</mark></td></tr><tr><td>Image</td><td>'On Sale' Graphic OR Press Photo</td><td><mark style="color:red;">Required</mark>. Defaults to press photo if on sale graphic doesn't exist.</td></tr><tr><td>Brand</td><td>Type of Show</td><td></td></tr><tr><td>Price</td><td>Minimum event price</td><td><mark style="color:red;">Required</mark>. Defaults to 0 if no price exists.</td></tr><tr><td>Custom Label 0</td><td>Genre</td><td></td></tr><tr><td>Custom Number 0</td><td>Event Days Out</td><td></td></tr><tr><td>Custom Number 1</td><td>On Sale Days Out</td><td></td></tr><tr><td>Custom Number 2</td><td>Remaining Budget</td><td>Defaults to 0</td></tr></tbody></table>

### Advertising Using The Event Feed

When creating a new ad in Meta's Ads Manager, choose "Sales" as an objective.  This will allow you to select a "Catalog" and "Product Set" from your Commerce Manager.  Additionally you can use fields from the Product Mapping table above in your ad text.

<figure><img src="../../.gitbook/assets/CleanShot 2023-12-14 at 22.19.30@2x.jpg" alt=""><figcaption></figcaption></figure>





