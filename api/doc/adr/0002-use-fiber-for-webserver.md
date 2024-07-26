# 2. use fiber for webserver

Date: 2024-07-27

## Status

Accepted

## Context

We want a webserver framework.  It should be simple and extensible.

## Decision

Use Fiber https://docs.gofiber.io/

## Consequences

Fiber is inspired by expressjs so it's api should be familiar and easy to work within.
When compared to other frameworks such as [gin](https://gin-gonic.com/) and [echo](https://echo.labstack.com/) fiber excels in most performance metrics
`https://medium.com/deno-the-complete-reference/go-gin-vs-fiber-vs-echo-hello-world-performance-a69a76a64d34`
