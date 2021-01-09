# CartManagementWithSession

A sessional group task which is to create a session state without using built-in session management techniques of the framework ( ex: C#).

Feature-1: 
Add an item: POST cart/add. This should add an item to the cart. Just an item name is sufficient. For example, cart/add/cricketbat
If this is a new session (that means no session-id was sent in the request), a session ID should be created and sent back to the client.
If the item already exists in the cart, increase the number of items.

Feature-2:
Remove an item DELETE cart/remove/<item>. Remove the item. For example cart/remove/cricketbat.

Feature-3:
Decrease an item DELETE cart/decrease/<item>. Decrease the number of the specified item by one. For example, cart/decrease/cricketbat

Feature-4:
Get the cart GET cart.
