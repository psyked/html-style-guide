---
title: HTML Development Guidelines
---
<div class='row'>
<div class='large-4 columns'>
{{#markdown}}
## ** tl;dr **
Background reading can get a little boring, so you can skip past that and onto the good stuff by reading our summary.

<a href='summary.html' class='button'>Open the Summary now.</a>
{{/markdown}}
</div>
<div class='large-8 columns'>
{{#markdown}}
    <!doctype html>
    <html class="no-js" lang="en">
        <head>
            <title>Website Title</title>
            <link rel="stylesheet" href="css/style.css"/>
            <script src="js/modernizr.js"></script>
        </head>
        <body>
            <header>
                <brand>Website Title</brand>
            </header>
            <nav>
                <ul>
                    <li>Link 1</li>
                    <li>Link 2</li>
                    <li>Link 3</li>
                </ul>
            </nav>
            <section>
                <article>
                    <h2>Article header</h2>
                    <p>Lorem ipsum...</p>
                </article>
            </section>
            <footer>(c) 2013 MMT Digital</footer>
        </body>
    </html>
{{/markdown}}
</div>
</div>

<div class='row'>
<div class='large-12 columns'>
<hr/>
</div>
<div class='large-4 columns'>
{{#markdown}}
### Formatting & <br/>Validating your HTML

Making your code work is easy. Sticking to the rules and making it look pretty is hard.

Which leaves you with the questions:
- Do you 'Lint' your HTML?
- Does it **Need** to validate?
- **How** do you validate it?
- Should you make it look *pretty*, <br/>or make it as *small as possible?*

<!-- There's a time and a place for optimising and minifying your HTML code, and that's not during development. -->
... questions to which you can find the answers in the [HTML Validation Best Practice Guidelines.]()
{{/markdown}}
</div>

<div class='large-4 columns'>
{{#markdown}}
![HTML5 Logo](assets/HTML5.png)
{{/markdown}}
</div>

<div class='large-4 columns'>
{{#markdown}}
### Which version of HTML?

> **HTML5**, of course. *Duh.*
> <cite>James Ford</cite>

It's a brave new world, and we don't need the burden of all that cumbersome XHTML rubbish. **HTML5 + Polyfils** are the way
forward, whilst admirably dealing with the browsers of yesteryear.

You'll need a little guidance of course, which is why we've documented our preferred setup in the [summary]() page.
{{/markdown}}
</div>
</div>

<div class='row'>
<div class='large-6 columns'>
{{#markdown}}
### Search Engine Optimisation

Clean, well-structured, **semantic HTML** has huge benefits for your SEO; as does using **RDFa**, **metadata** and appropriate
**Microformats** in your pages, but there's also sitemaps, URL structures and all manner of additional elements to consider.

Regardless of whether Search Engine Optimisation is a top priority for your website, you should always be following the
Best Practice Guidelines for SEO and using the appropriate semantic elements.

<a href='#' class='button'>Read the full HTML + SEO Guidelines now.</a>
{{/markdown}}
</div>

<div class='large-6 columns'>
{{#markdown}}
### Background Reading

For some interesting background reading, you might like to take a look at the following resources:

- [I Can Smell Your CMS]() [ Presentation, 40mins ]

{{/markdown}}
</div>
</div>