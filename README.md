## oBundle BigCommerce Technical

## Setup
Sign up for a BigCommerce trial store
	- this will be valid for 15 days and will be needed to complete the test

Install Stencil CLI for local development
	- you will be using the default Cornerstone Theme that comes standard with new BigCommerce stores

* Refer to the BigCommerce developer documentation for any questions you might have. It will contain all the info needed to complete the tasks below


## Task
Create a product called Special Item which will be assigned to a new category called Special Items
	- Be sure to add at least 2 images during the product creation

## Changes made in `card.html`
The Special Item should be the only item which shows in this category 
	- create a feature that will show the product's second image when it is hovered on

## Changes made in `category.html`
Add a button at the top of the category page labeled 'Add All To Cart' 
	- When clicked, the product will be added to the cart. Notify the user that the product has been added


## Response Body (403) for the tasks below and Bonus
If the cart has an item in it 
	- Show a button next to the Add All To Cart button which says 'Remove All Items' 
	- When clicked it should clear the cart and notify the user
	- Both buttons should utilize the Storefront API for completion

    ```
	{
	  "status": 403,
	  "title": "You don't have a required scope to access the endpoint",
	  "type": "https://developer.bigcommerce.com/api-docs/getting-started/api-status-codes",
	  "errors": {}
	}
    ```

## Bonus
If a customer is logged in 
	- At the top of the category page show a banner that shows some customer details (i.e. name, email, phone, etc). This should utilize the data that is rendered via Handlebars on the Customer Object.


## Submission

[BigCommerce Store](https://obundle-technical-assesment.mybigcommerce.com/?ctk=6ac8b164-5125-408d-9a7a-6db5c14ad223)

Preview Code:
ldq3owuai5

