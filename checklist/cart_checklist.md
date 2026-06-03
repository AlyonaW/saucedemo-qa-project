# Cart Checklist — SauceDemo
## Project: SauceDemo QA Testing
## Module: Shopping Cart functionality
## URL: https://www.saucedemo.com

---

## Functional checks
- [ ] User can add item to cart
- [ ] User can remove item from cart
- [ ] Cart displays correct items
- [ ] Cart badge updates correctly
- [ ] Cart page loads successfully

---

## UI checks
- [ ] Product image is displayed correctly in cart
- [ ] Product name is correct
- [ ] Product price is correct
- [ ] Remove button is visible and clickable

---

## Negative checks
- [ ] Cart is empty when no items added
- [ ] Removing last item leaves empty cart state

---

## Basic data integrity checks
- [ ] User cannot modify cart items without action (no phantom items)
- [ ] Cart does not contain duplicated items after single add action
- [ ] Cart quantity cannot be negative
- [ ] Removed items are not accessible in cart page
- [ ] Cart data persists correctly during navigation (no data leakage between sessions/users)
- [ ] Unauthorized access to cart is not possible without login
