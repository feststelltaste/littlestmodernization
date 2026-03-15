# Software Modernization Strategies

A comprehensive visual guide to 32 strategies for modernizing legacy software systems, organized into four categories: Business, Development, Infrastructure, and Enablement.

## About

This is the companion website for *The Littlest Book of Software Modernization Strategies — Approaches to revitalize and right-size your legacy system according to business needs*, available on [Leanpub](https://leanpub.com/littlestmodernization/).

Collected and enhanced by [Markus Harrer](https://markusharrer.de), enabled by [INNOQ](https://www.innoq.com).

## Features

- Bilingual content (English and German)
- Downloadable strategy cards (PDF) and overview posters (PDF, SVG, PNG up to 4K/A1)
- Fully self-contained static site — no build step or dependencies required

## Running Locally

Open `index.html` in a browser, or serve the directory with any HTTP server:

```sh
python -m http.server
```

## Project Structure

```
index.html              # entry point (redirects to en/)
en/index.html           # English version
de/index.html           # German version
strategy_cards*.pdf     # printable strategy cards (EN & DE)
strategy_overview*.svg  # overview posters in various formats
```

## Contributing

This website and its assets are generated from the original book sources. As such, content changes cannot be accepted via pull requests. If you have suggestions or feedback, please open an issue instead.

## License

The website content and poster versions are licensed under [Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0)](https://creativecommons.org/licenses/by-sa/4.0/).
