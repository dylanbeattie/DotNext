# Real World REST and Hands-on Hypermedia

### Presented by Dylan Beattie at DotNext St Petersburg, Russia, May 19-20 2017

So you've built your HTTP API, and now that it's live, you're suddenly dealing with a whole new set of problems. Do you really need to PUT the entire Customer just to change someone's email address? Why does it take you 25 API calls just to render a shopping cart? How do you find the bottlenecks when just drawing a web page requires fifty HTTP requests? What happens when one of your API consumers accidentally tries to GET your entire customer database?

Most of us are familiar with the architectural style known as REST, but even experienced developers often find it difficult to translate REST's architectural principles into running code. In this talk, we'll explore the elements of REST related to hypermedia and the principle of "hypermedia as the engine of application state" (HATEOAS) - we'll talk about why they matter, and when you might want to implement them in your own systems. We'll look at some of the tools that exist to help you design, deliver and debug your HTTP APIs, and we'll do some hands-on coding to show you what these patterns look like in a .NET web application using the NancyFX HTTP framework and the HAL hypermedia application language.

## Contents

* [PDF of the Powerpoint slides ](https://github.com/dylanbeattie/DotNext/raw/master/Real%20World%20REST%20and%20Hands-on%20Hypermedia%20-%20Slides%20from%20DotNext%20St%20Petersburg%202017.pdf)from the presentation
* [Source code for all the examples](https://github.com/dylanbeattie/DotNext/tree/master/src) included in the presentation

## Useful Links

* "[Architectural Styles and the Design of Network-based Software Architectures](https://www.ics.uci.edu/~fielding/pubs/dissertation/top.htm)" - Roy Fielding's PhD thesis in which he first describes the REST architectural style
*  [On choosing a hypermedia type for your API - HAL, JSON-LD, Collection+JSON, SIREN, Oh My!
](https://sookocheff.com/post/api/on-choosing-a-hypermedia-format/) - a great article by Kevin Sookocheff on JSON hypermedia formats
* [HAL - Hypertext Application Language](http://stateless.co/hal_specification.html) - the HAL language specification