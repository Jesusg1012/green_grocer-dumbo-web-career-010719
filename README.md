---
languages: ruby
tags: collections, arrays, hashes, named parameters, advanced
---

##Objectives: 
Create a checkout method to calculate the total cost of a cart of items and apply discounts and coupons as necessary.

Dr. Steve Bruhle, your green grocer, isn't ready, but you are!

##Skills: 
any?, all?, none?, each, map/collect, named parameters

##Instructions:

Implement a method `checkout` to calculate total cost of a cart of items and apply discounts and coupons as necessary.

### The `consolidate_cart` method

The cart starts as an array of individual items. Translate it into a hash that includes the counts for each item with the `consolidate_cart` method.

### The `checkout` method

Create a `checkout` method that calculates the total cost of the consolidated cart.

When checking out 

* Apply coupon discounts if the proper number of items are present

* Apply 20% discount if items are on clearance

* If cart's total is over $100, apply 10% discount. Apply coupons first, then check total.


### Named Parameters

The method signature for the checkout method is 
`consolidate_cart(cart:[])`. This, along with the checkout method uses a ruby 2.0 feature called [Named Parameters](http://brainspec.com/blog/2012/10/08/keyword-arguments-ruby-2-0/).

Named parameters give you more expressive code since you are specifying what each parameter is for. Another benefit is the order you pass your parameters doesn't matter!
`checkout(cart: [], coupons: [])` is the same as `checkout(coupons: [], cart: [])`

## Reward
* [Dr. Brule](http://www.adultswim.com/videos/tim-and-eric-awesome-show-great-job/dr-brule-your-green-grocer/)
