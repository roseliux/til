# Ruby Style: Predicate Methods

A method that returns true or false is called a "predicate method".

In Ruby, there is a naming convention where predicate methods end with a question mark. For instance, if you have an Invoice class and are writing an instance method that returns whether the invoice has been paid or not, you would name the method paid?

This idiom helps improve readability by making Ruby code read more like English:

```ruby
  puts "This invoice has been paid" if invoice.paid?
```

Reference: http://pragmati.st/2012/03/24/the-elements-of-ruby-style-predicate-methods/
