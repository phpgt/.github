# PHP.GT

**PHP.GT** is a collection of web development tools that form **[WebEngine](https://www.php.gt/webengine/)** — an ergonomic toolkit for building web applications. WebEngine follows a static-first approach: development begins using plain static HTML, with PHP introduced only when needed. Dynamic behavior is handled through server-side DOM manipulation, mirroring well-known client-side techniques.

> + Start with static HTML
> + Split pages into templates and components
> + Bind data automatically to the DOM
> + Plain HTTP techniques for easy debugging
> + Live-updating pages built in

## Minimalist, modular, modern PHP development

Web frameworks offer many features, but often come with steep learning curves or imposing rules. The motivation behind this project is the belief that what a framework can offer can be achieved by **eliminating code rather than adding more**.

// TODO: Example code

Who is GT for?
--------------

The overall aim throughout GT repositories is to provide an alternative, minimalistic approach to web development. If you're tired of working with the so called "full stack", there might be something of interest to you here.

All GT repositories are designed to be inclusive to novice developers. Each repository is designed to operate independently, allowing developers to leverage individual components without necessarily needing to adopt the entire framework or possess prior knowledge of WebEngine. This modular approach not only enhances flexibility but also promotes a more focused, purpose-driven development experience.

WebEngine itself provides a "batteries-included" default configuration and has an accessible entry point for beginners. However, its capabilities extend far beyond basic use-cases; WebEngine is robust enough to power large-scale, real-world applications serving millions of users.

Whether you're just starting your web development journey or seeking a new perspective on established practices, you are invited to explore WebEngine further by visiting the [Getting Started][webengine-getting-started] page.

Get to know GT
--------------

### WebEngine

Jump right in to some [full featured tutorials][webengine-tutorials], or follow the [getting started guide][webengine-getting-started] for a good overview of the development process in WebEngine applications.

The user guide starts at ["the request-response lifecycle"][webengine-request-response], which exposes the logic that makes WebEngine work, from the first line of the first PHP script, all the way through to the page being sent back to the browser.

### The Document Object Model (DOM)

Modern web development is underpinned by the DOM, but using its benefits is usually constrained to the client-side.

Having a [full-featured DOM][dom] in your server-side code enhances the way dynamic pages can be built. Utilising a standardised object-oriented interface means the page can be ready-processed as [Multi-page Applications (MPAs)][webengine-mpa], benefitting browsers, web servers, content delivery networks, and end-users.

On top of the [standard DOM API][dom-standards], you can take advantage of [intuitive templating][domtemplate], [server-side validation][domvalidation], and more.

### Bring your own database

There's [no database connection made until you use one][webengine-lazy-services], so you're not forced to use any technologies until they're a requirement of your application's functionality - sometimes a directory structure or a CSV file is all you need!

The [Object Relational Mapper (ORM)][orm] automates database persistence, but allows you to get your hands dirty with [custom SQL queries][orm-custom-sql] when you need to.

### The full stack

Client-side development is handled automatically through the [build process][build]. A sensible set of [default build steps][webengine-build] can be extended when needed.

**Turbo** is a [micro framework on the client side][turbo-pages] gives your pages live updates and transitions out of the box.

## Get involved

If you've never developed anything in PHP before, take a look at [the basics of PHP and WebEngine][webengine-basics]. The guide covers the steps involved in getting a PHP development environment up and running on your computer, and then goes on to explain the basics of PHP syntax and getting started with WebEngine application development.

If you're familiar with starting PHP projects using Composer, head over to the [quick start guide][webengine-quick-start] - you'll be up and running in 30 seconds.

### Contributing to open source

If you've found a bug, or have a feature request, read the guide on [how to contribute issues to PHP.GT][issues].

If you're interested in contributing code, but don't know where to start, learn [how to contribute to open source by creating a pull request][gt-contributing] to be guided in finding an issue to implement or fix, coding the feature, and submitting your first pull request.

[gt-issues]: https://www.php.gt/docs/gt/issues/
[gt-contributing]: https://www.php.gt/docs/gt/contributing/
[webengine-tutorials]: https://www.php.gt/docs/webengine/tutorials/
[webengine-getting-started]: https://www.php.gt/docs/webengine/getting-started/
[webengine-request-response]: https://www.php.gt/docs/webengine/request-response-lifecycle/
[webengine-example-applications]: https://www.php.gt/docs/webengine/example-applications/
[dom]: https://www.php.gt/dom/
[dom-standards]: https://www.php.gt/docs/dom/standards/
[webengine-mpa]: https://www.php.gt/docs/webengine/multi-pass-rendering/
[domtemplate]: https://www.php.gt/domtemplate/
[domvalidation]: https://www.php.gt/domvalidation/
[orm]: https://www.php.gt/orm/
[orm-custom-sql]: https://www.php.gt/docs/orm/custom-sql/
[webengine-lazy-services]: https://www.php.gt/docs/webengine/service-loader/
[build]: https://www.php.gt/build/
[webengine-build]: https://www.php.gt/docs/webengine/build/
[turbo-pages]: https://www.php.gt/turbo/
[webengine-basics]: https://www.php.gt/docs/webengine/basics/
[webengine-quick-start]: https://www.php.gt/docs/webengine/quick-start/
