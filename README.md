# carwash-track

The customer page of the [Car Wash Queue & Membership System](https://github.com/Thilina0101/carwash).

- **Queue ticket QR** → `?s=<deployment>&t=<ticket code>`: ticket number, masked plate, status (waiting → washing → ready → picked up),
  cars ahead and estimated ready time. It updates by itself every 15 seconds, and the phone vibrates when the car is ready.
- **Member card QR** → `?s=<deployment>&m=<member code>`: first name, tier, points and their value, wash credits and unlimited plans.

It's kept separate from the staff app on purpose, so customers never see the staff app's address.
Turn on GitHub Pages (Settings → Pages → Deploy from branch `main`, folder `/`) to publish it at
`https://thilina0101.github.io/carwash-track/`.
