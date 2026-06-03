## Cart Bug #1: Cart icon does not change cursor on hover
**ID:** BUG-002

**Module:** Cart 

**Severity:** Trivial 

**Priority:** Low  
 
**Preconditions:**
User is logged in. User is on products page.

**Steps to reproduce:**
1. Open products page.
2. Hover over cart icon.

**Actual result:**
Cursor remains default arrow and does not change to pointer.

**Expected result:**
Cursor should indicate clickable element (pointer cursor on hover).

**Notes:**
Cart icon is still clickable despite cursor behavior.

**Environment:**
Windows 10, Firefox

---

## Cart Bug #2: Cart allows checkout with empty cart
**ID:** BUG-003

**Module:** Cart 

**Severity:** Major

**Priority:** Medium

**Preconditions:**
User is logged in. Cart is empty.

**Steps to reproduce:**
1. Go to Products page.
2. Ensure no items are added to cart.
3. Open Cart.
4. Click “Checkout”.

**Actual result:**
User is able to proceed to checkout step even when cart appears empty.

**Expected result:**
System should prevent checkout when cart is empty or display message like: “Your cart is empty”.

**Environment:**
Windows 10, Firefox
