## Safer Enums in Go
 - [https://threedots.tech/post/safer-enums-in-go/](https://threedots.tech/post/safer-enums-in-go/)
 - RSS feed: https://threedots.tech
 - date published: 2021-10-15 18:34:57.456892+00:00

Enums are a crucial part of web applications. Go doesn&rsquo;t support them out of the box, but there are ways to emulate them. Many obvious solutions are far from ideal. Here are some ideas we use that make enums safer by design. iota Go lets you enumerate things with iota. const ( Guest = iota Member Moderator Admin ) Full source: github.com/ThreeDotsLabs/go-web-app-antipatterns/02-enums/01-iota/role/role.go  While Go is explicit, iota seems relatively obscure.

