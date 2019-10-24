## Ruby 'Ghost' Methods

They are called ghost methods because you can call them but they won't show up in lists of methods
available or be explicitly defined. They are there, but invisible. You can make them by hijacking
and writing your own `method_missing`.

Example on rails

```ruby
User.find_by_name('rocela')

User.instance_methods(false).sort
# => [:name, :name=, :role, :role=]
```

Reference: https://gist.github.com/spaceghoul/bb5f18d18ae796d8504335de9d9a41b0
