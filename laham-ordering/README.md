# Laham by Shab Foods: QR ordering page

A single-file ordering page for a button parotta and mutton food cart.

- **Customer page:** menu (Half 2 pcs, Full 4 pcs, Large 6 pcs), cart, UPI payment with QR, order token and a live wait time based on the pieces being cooked.
- **Counter page** (`#counter`): verify UPI payments, hand over ready orders, cancel and refund, pause orders.
- **Kitchen page** (`#kitchen`): cooking queue, mark ready, sold-out switches.
- **Owner page** (`#owner`): menu prices, daily summary, settings (cart name, UPI ID, staff links).

## Running it

Open `index.html` in a browser. Opened on its own, the page runs in **demo mode**: orders are kept in that browser only and are not shared between phones. A live version needs a shared database behind it (the version hosted on claude.ai uses its built-in storage).

Payment is confirmed by hand: the customer pays the cart's UPI ID with a note like `BPM-K7Q2`, and the counter taps "Payment received" after checking the bank app.
