# Fibonacci

```ruby runnable
def fibonacci(i)
  return i if (0..1).include?(i)
  fibonacci(i - 1) + fibonacci(i - 2)
end
print (1..20).map{|i|fibonacci(i)}
```
