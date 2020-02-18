Ruby Hashes key can't be a number

```ruby
{ 1: 'one' }
```

you should use:

```ruby
{ 1 => 'one' }
```

explanation:
https://stackoverflow.com/a/33326503/3280686
