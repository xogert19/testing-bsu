# Test cases for Jack Wolfskin website

## Test Case 1: Add a backpack to a Cart

### Preconditions:

- Website https://us.jackwolfskin.com/ is opened.

### Test steps:

| ID  | Action                              | Expected result                                                                   |
| --- | ----------------------------------- | --------------------------------------------------------------------------------- |
| 1   | Click on _Equipment_ category       | Page with equipment will open                                                     |
| 2   | Click on backpack you want to order | Page with that backpack will open                                                 |
| 3   | Choose a color of a backpack        | Pictures of a certain color backpack will be loaded                               |
| 4   | Choose a size of a backpack         | A backpack with a certain size will be chosen, a button _Add to Cart_ will appear |
| 5   | Click on a button _Add to Cart_     | A popup _Added to Cart_ will appear                                               |

## Test Case 2: Buying a backpack from a Cart as a Guest

### Preconditions:

- Website https://us.jackwolfskin.com/ is opened.
- A backpack is added to a _Cart_.

### Test steps:

| ID  | Action                                                                                         | Expected result                                                            |
| --- | ---------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------- |
| 1   | Click on _Cart_ icon in header                                                                 | _Cart_ page will open                                                      |
| 2   | Click on _Checkout_ button                                                                     | A page will open, offering you either to login or to continue as a _Guest_ |
| 3   | Click on _Continue as Guest_ button                                                            | A page with _Shipping_ and _Payment_ information will open                 |
| 4   | Write correct information about shipping: name, surname, address, etc.                         | A _Shipping method_ form will appear                                       |
| 5   | Choose either _Ground Shipping_ or _Expedited Shipping_ and click _Continue to Payment_ button | A _Payment_ form will appear                                               |
| 6   | Click on _Place Order_ button                                                                  | An _Order_ will be placed                                                  |
