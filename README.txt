# Adobe Analytics + Adobe Target E-commerce Demo

## Contents
- index.html - working e-commerce demo
- README.txt - implementation guide
- adobe-launch-mapping.txt - suggested Adobe Data Collection / Launch rule mapping

## How to run
1. Open index.html in Chrome/Edge.
2. Open Developer Tools > Console.
3. Click View Product, Add to Cart, Remove, Cart, Search, Category and Checkout.
4. Observe the `adobeDataLayer` events in the console.
5. In Adobe Experience Platform Data Collection, configure rules to listen for these events.
6. Add your Adobe Web SDK / Analytics / Target implementation separately.

## Events
pageView
productView
productSearch
categoryFilter
addToCart
removeFromCart
cartView
checkoutStart

## Important
This is a demo data layer. For production Adobe Experience Platform implementations, map the business data to the appropriate Web SDK/XDM schema and use your organization's approved identity, consent, Analytics and Target configuration.
