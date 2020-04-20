## The Kernel#itself method.
It's a method that you can call on an object & the object will return itself.

```ruby
[1,2,3,nil].select(&:itself)
# =>  [1, 2 ,3]
```
This example filters nil & false values.


Reference: https://www.rubyguides.com/2020/04/self-in-ruby/?tl_inbound=1&tl_target_all=1&tl_period_type=3
