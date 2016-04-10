# Mockito: Chainable responses

We can chain different responses for consecutive calls using the same input values.

```java
doReturn(foo).doThrow(new TimeoutException("Test").doReturn(bar).when(mock).method();
```
