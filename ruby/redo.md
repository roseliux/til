## redo inside a loop

Will repeat the current iteration if the condition is met.

```ruby
5.times do |i|
  p i
  redo if i == 4
end

# 0
# 1
# 2
# 3
# 4
# 4
# Infinite loop
```

Reference: https://devblast.com/b/overview-loops-ruby/
