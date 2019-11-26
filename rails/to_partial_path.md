## to_partial_path

When 
`render @user.comments`
 
Under the hood, render calls `to_partial_path` on each of our objects to determine which partial to render. 
 
```ruby
User.new.to_partial_path
# => 'users/user'
```

You can override this method on your models/classes and use the render.

Reference: https://thoughtbot.com/blog/rendering-collections-in-rails
