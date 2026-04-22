# ColeHart Main-site

`opticheck-site` is the public marketing website for ColeHart Enterprises and its OptiCheck solution.

## What it is

This repo contains a static multi-page website built with:

- HTML (`index.html` and section pages in `about/`, `services/`, `government/`, and `solutions/`)
- Shared CSS (`css/style.css`)
- Static assets (`images/`, `robots.txt`, `sitemap.xml`, and supporting files)

## What it does

The site communicates ColeHart's offerings and routes visitors to key actions:

- Presents company positioning for infrastructure, technology, and operations support
- Highlights service lines and government contracting capability information
- Showcases OptiCheck in `solutions/opticheck.html`
- Sends users to the live OptiCheck app: `https://opticheck.colehartenterprises.com/app`
- Provides contact and lead-capture flows (including licensing interest notification)

## Main OptiCheck Page

`solutions/opticheck.html` explains OptiCheck as an AI-powered operational analysis tool that:

- Collects operational context through structured input
- Scores process maturity across key operational categories
- Identifies bottlenecks and systems integration gaps
- Produces prioritized findings and actionable recommendations in minutes

## Local Preview

Because this is a static site, you can open `index.html` directly in a browser or serve it locally with any static server.

Example (Node):

```bash
npx serve .
```

Then open the local URL shown in your terminal.
