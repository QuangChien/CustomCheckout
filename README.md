# CustomCheckout
Module: Advanced Checkout

Create a new product attribute: Allow multi-order (Yes/No).
When customer adds product to cart and Allow multi-order is No
If the cart is not empty -> Show popup alert.
The popup has 2 buttons: Clear Cart and Go to checkout
If click Clear Cart, we remove all items from cart and reload the page.
If click Go to checkout -> redirect to checkout page.
If the cart is empty -> add product to cart normally.

Advanced requirement: On the last step on checkout page, when customer clicks Place Order
Check if the customer has order with order status is not complete -> Show popup alert: You have an order that is not complete. Please wait to complete order before create new order.
On popup, add Ok button, when click button -> go to homepage.
