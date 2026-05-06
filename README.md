# IHG Smart Stay — Points Calculator

A single-file HTML calculator that helps IHG One Rewards members decide whether to pay cash or redeem points for a hotel stay.

## Features

- **Membership tier selector** — Club / Silver / Gold / Platinum / Diamond, with automatic points rate adjustment
- **Stay cost breakdown** — calculates service fee and tax on top of the base room rate, converted from TWD to USD via a configurable exchange rate
- **Add-on points** — toggle to include purchased bonus points and their cost
- **Redemption value analysis** — compares the opportunity cost of redeeming points against the cash-back value of points earned, giving a clear "worth it or not" verdict

## Mobile Support

Optimized for mobile browsers. Touch targets meet the 44×44px minimum, card grids reflow to single-column on narrow screens, and layout padding is reduced on viewports ≤ 480px.

## Usage

Open `index.html` directly in any browser. No build step or server required.

## Configuration defaults

| Field | Default |
|---|---|
| Room rate | NT$ 5,000 |
| Service fee | 10% |
| Tax rate | 5% |
| Exchange rate | 32 TWD / USD |
| Points threshold | 0.005 USD / pt |
| Redemption cost | 50,000 pts |
