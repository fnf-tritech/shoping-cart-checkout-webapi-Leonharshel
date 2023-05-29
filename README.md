[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/hHR_U_zd)
# sc-checkout-api-hack-01
## Getting Started Shoping Cart Checkout WebApi

We’re going to see how far we can get in implementing a supermarket checkout that calculates the total price of a number of items. In a normal supermarket, things are identified using Stock Keeping Units, or SKUs. In our store, we’ll use individual letters of the alphabet (A, B, C, and so on). Our goods are priced individually. In addition, some items are multipriced: buy n of them, and they’ll cost you y rupees. For example, item ‘A’ might cost 50 pounds individually, but this week we have a special offer: buy three ‘A’s and they’ll cost you 130. The price and offer table:

|Item | Price |  Offer |
|-----|-------|--------|
|A    | 50    |3 for 130|
|B    | 30    |   2 for 45|
|C    | 20    |
|D    | 15 |

Our checkout Api accepts items in any order, so that if we scan a B, an A, and another B, we’ll recognize the two B’s and price them at 45 (for a total price so far of 95).

The interface to your checkout can be anything you like but we’d suggest passing in a string of SKUs to begin with
Here are the first few tests from a  implementation, Use language, and write the tests in any order you prefer:

  assert_equal(  0, checkout(""))
  assert_equal( 50, checkout("A"))
  assert_equal( 80, checkout("AB"))
  
  ### Expectations
  ----------
  - Design and Develop Checkout WebApi 
  - Write Unit Tests using xUnit for Checkout Api Code with 90% code coverage
  - Setup Azure Build Pipeline and verify build  for Checkout Api Code
  - Configure Azure Pilpeline to run xUnit tests
  - Set up code coverage reports in Azure DevOps pipeline
