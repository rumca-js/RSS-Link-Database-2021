## API Handyman | Empty list, HTTP status code 200 vs 204 vs 404
 - [https://apihandyman.io/empty-lists-http-status-code-200-vs-204-vs-404/](https://apihandyman.io/empty-lists-http-status-code-200-vs-204-vs-404/)
 - RSS feed: https://apihandyman.io
 - date published: 2021-10-09 10:39:35.541215+00:00

When designing APIs, choosing HTTP status codes is not always that obvious and prone to errors, I hope this post series will help you to avoid common mistakes and choose an adapted one according to the context. This fourth post answers the following question: given that /users is a collection (a list) and no users are named Spock, what should return GET /users?name=spock? 200 OK, 204 No Content or 404 Not Found

