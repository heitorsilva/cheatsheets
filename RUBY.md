# RUBY Cheatsheet

```ruby
value = 1
value.nil?

list = []
hash = {}

if 1 == 1
  foo = "bar"
elsif 2 == 2
  bar = "foo"
else
  foobar = "barfoo"
end

list.each do | item |
  puts item
end

list.each_with_index do | item, index |
  puts "#{index}: #{item}"
end

foobar.each_char do | char |
  puts char
end

def name(arg1, arg2) do
  arg1 + arg2
end
```
