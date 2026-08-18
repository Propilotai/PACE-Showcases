PACE SHOWCASES WEBSITE
======================

Current pages:
- index.html — main PACE landing page
- event.html — PACE Winter Showcase details + Add to Cart
- register.html — player registration form + payment handoff
- styles.css — shared styling

Current checkout flow:
Home -> Select Event -> Event Details -> Add to Cart -> Registration -> Payment handoff

Important:
The registration and cart flow is functional in the browser using localStorage.
Actual card processing is NOT connected yet.

To turn payment live, connect one of:
- Stripe Checkout / Stripe Payment Link
- Square Checkout
- another hosted payment provider

Once a checkout URL or payment provider is selected, the Continue to Payment button can be connected without redesigning the flow.
