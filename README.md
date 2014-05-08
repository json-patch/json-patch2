# json-patch2


A possibile revision to the JSON-Patch format


## What is This?

The [JSON Patch](http://tools.ietf.org/html/rfc6902) specification was standardised quickly, due to a desire to have *some* format available for
HTTP PATCHing JSON files. 

As a result, the focus of that format is primarily on simplicity, often sacrificing functionality. We were very aware
that specifications are often overly complex, because of the compromises that inevitably happen, and we wanted to avoid
that so that implementation (and adoption) wouldn't be too difficult.

Since [the RFC](http://tools.ietf.org/html/rfc6902) was published, a number of users and implementers have stepped forward,
saying roughly "this is great, but..."

This repo is an attempt to gather and discuss these issues, as a prelude to working on a more-functional-but-still-lean
followup format.

It may or may not be called "json-patch2"; that's just a placeholder.

## How Do I Participate?

If you have a use case, problem or idea, please have a look through the issues list; if you can't find something that
covers it, please submit a new issue, with as complete a description as possible.

Concrete proposals for syntax and semantics are always best.
