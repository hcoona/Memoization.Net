# Memoization #

This project help C# make memoized function.

See [Memoization - Wikipedia](https://en.wikipedia.org/wiki/Memoization) for further details.

## Getting Started ##

```csharp
var m_fib = Memoization.Create(fib);

counter = 0;
m_fib(7);
Assert.Equal(41, counter);

counter = 0;
m_fib(7); // Will read result directly from cache if exist
Assert.Equal(0, counter);
```
