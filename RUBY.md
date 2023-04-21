# RUBY Cheatsheet

```ruby
value = 1
value.nil?

list = []
list[index]
list << value
list.unshift value

list.each do | item |
  puts item
end

list.each_with_index do | item, index |
  puts "#{index}: #{item}"
end

hash = {}
hash[key] || hash.fetch key
hash[:key] = value
hash.has_key? key
hash.has_value? value

hash.each do | key, value |
  puts "#{key}: #{value}"
end

if 1 == 1
  foo = "bar"
elsif 2 == 2
  bar = "foo"
else
  foobar = "barfoo"
end

foobar.each_char do | char |
  puts char
end

def name(arg1, arg2) do
  arg1 + arg2
end

# memoization - @variable = @variable || object.property
@variable ||= object.property
```
