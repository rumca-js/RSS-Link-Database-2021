## Go is pass-by-value — but it might not always feel like it | neilalexander.dev
 - [https://neilalexander.dev/2021/08/29/go-pass-by-value.html](https://neilalexander.dev/2021/08/29/go-pass-by-value.html)
 - RSS feed: https://neilalexander.dev
 - date published: 2021-09-11 07:45:05.313418+00:00

Go is a programming language which passes by value, which effectively means that if you give a value as a parameter to a function, the received value within the function is actually a copy of the original. You can modify it however you wish and your changes will not affect the original value or escape the function scope. This is in contrast to some languages which pass values by reference instead of copying them.

