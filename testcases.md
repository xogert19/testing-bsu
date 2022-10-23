# Test cases for Jack Wolfskin website

## Test Case 1: Opening a Women page.

**Preconditions**
- Website https://us.jackwolfskin.com/ is opened.

**Test steps**
1. Click on the __Women__ in the navigation bar.

**Expected Result**
A page with clothes for women is opened.


## Test Case 2: Sorting clothes by price.

**Preconditions**
- Website https://us.jackwolfskin.com/ is opened.
- [Women](https://us.jackwolfskin.com/jw/womens/c/033) page is opened.

**Test steps**
1. Click on the __Sort__ drop-down list.
2. Click on the __Price (Lowest First)__.

**Expected Result**
All goods will be sorted by price, from lowest to highest.


## Test Case 3: Filtering clothes by color.

**Preconditions**
- Website https://us.jackwolfskin.com/ is opened.
- [Women](https://us.jackwolfskin.com/jw/womens/c/033) page is opened.

**Test steps**
1. Click on the __Blue__ color in __Color__ filter category.

**Expected Result**
Only clothes with the color variant __Blue__ will be shown.


## Test Case 4: Filtering clothes by size.

**Preconditions**
- Website https://us.jackwolfskin.com/ is opened.
- [Women](https://us.jackwolfskin.com/jw/womens/c/033) page is opened.

**Test steps**
1. Click on the __XS__ size in __Size__ filter category.

**Expected Result**
Only clothes with the size variant __XS__ will be shown.


## Test Case 5: Filtering clothes by sale.

**Preconditions**
- Website https://us.jackwolfskin.com/ is opened.
- [Women](https://us.jackwolfskin.com/jw/womens/c/033) page is opened.

**Test steps**
1. Click on the __On Sale__ option in __Other__ filter category.

**Expected Result**
Only clothes that are on sale will be shown.


## Test Case 6: Removing search filters.

**Preconditions**
- Website https://us.jackwolfskin.com/ is opened.
- [Women](https://us.jackwolfskin.com/jw/womens/c/033) page is opened.
- __Yellow__ color and __XXL__ size filters are chosen.

**Test steps**
1. Click on the __Clear All__ button near filters list.

**Expected Result**
All filters are removed. All clothes are shown.


## Test Case 7: Choosing a category of clothes.

**Preconditions**
- Website https://us.jackwolfskin.com/ is opened.
- [Women](https://us.jackwolfskin.com/jw/womens/c/033) page is opened.

**Test steps**
1. Click on the __Vests__ option in __Categories__ category in filters.

**Expected Result**
Only clothes that are in __Vests__ category are shown.


## Test Case 8: Choosing a subcategory of clothes.

**Preconditions**
- Website https://us.jackwolfskin.com/ is opened.
- [Women](https://us.jackwolfskin.com/jw/womens/c/033) page is opened.
- [Vests](https://us.jackwolfskin.com/jw/womens/vests/c/0337) category is opened.

**Test steps**
1. Click on the __Insulated__ option in __Categories__ category in filters.

**Expected Result**
Only clothes that are in __Vests__ category and in __Insulated__ subcategory are shown.


## Test Case 9: Changing color of clothes.

**Preconditions**
- [Jacket](https://us.jackwolfskin.com/jw/womens/jackets/waterproof-and-rain/STORMY-POINT-JACKET-W/p/1111201_1910_) page is opened.

**Test steps**
1. Click on __Black__ color.

**Expected Result**
- New pictures of a __Jacket__ (in __Black__ color) will be shown.
- Price for a __Jacket__ with a __Black__ color will be shown.


## Test Case 10: Resetting size of clothes when changing color.

**Preconditions**
- [Jacket](https://us.jackwolfskin.com/jw/womens/jackets/waterproof-and-rain/STORMY-POINT-JACKET-W/p/1111201_1910_) page is opened.
- __Jacket__ with __Midnight Blue__ color is chosen.
- __XS__ size is chosen.

**Test steps**
1. Click on __Dark Aqua__ color.

**Expected Result**
- No __Size__ is chosen.
- New pictures of a __Jacket__ (in __Dark Aqua__ color) will be shown.
- Price for a __Jacket__ with a __Dark Aqua__ color will be shown.


## Test Case 11: Add item to the Cart.

**Preconditions**
- [Perfect Day backpack](https://us.jackwolfskin.com/jw/equipment/packs-and-bags/backpacks-and-totes/PERFECT-DAY/p/2007682_1024_OS) page is opened.

**Test steps**
1. Click on __Add to Cart__ button.

**Expected Result**
- __Backpack__ is added to the __Cart__.
- A popup __Added to Cart!__ is shown.


## Test Case 11: Change item amount in the Cart.

**Preconditions**
- [Cart](https://us.jackwolfskin.com/cart) page is opened.
- Item(e.g. [Perfect Day backpack](https://us.jackwolfskin.com/jw/equipment/packs-and-bags/backpacks-and-totes/PERFECT-DAY/p/2007682_1024_OS)) is added to the __Cart__.

**Test steps**
1. Click on __+__ button.

**Expected Result**
- __Amount__ is increased by 1.
- __Subtotal__ price in __Order Summary__ is recalculated.


## Test Case 12: Remove an item from the Cart.

**Preconditions**
- [Cart](https://us.jackwolfskin.com/cart) page is opened.
- Item(e.g. [Perfect Day backpack](https://us.jackwolfskin.com/jw/equipment/packs-and-bags/backpacks-and-totes/PERFECT-DAY/p/2007682_1024_OS)) is added to the __Cart__.

**Test steps**
1. Click on __Remove__ button.

**Expected Result**
- Item is removed from __Cart__.
- __Subtotal__ price in __Order Summary__ is recalculated.
- Number of items in the __Cart__ is decreased by 1.
