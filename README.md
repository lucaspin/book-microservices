# Transitioning from Monolith to Microservices Handbook

## TODOS

1. Migration to final repo: <https://github.com/semaphoreci/book-microservices>
X. Check title: Transitioning from Monolith to Microservices Handbook
3. Determine Tweet share link in introduction/final
X. Add authors
X. Remove sample codefence and see how to remove error
6. Check Campaign: book-microservices
X. Check chapter/header/subheader numbers
X. Check image/text flow in final PDF
X. Rewrite final words section
X. Rewrite introduction/chapter descriptions
X. Make a preview-only version of the book

## Production

[![Build Status](https://semaphore-oss.semaphoreci.com/badges/book-monorepo-cicd/branches/master.svg)](https://semaphore-oss.semaphoreci.com/projects/book-microservices)

Content is written in Markdown, final PDF made with [Pandoc][pandoc].

We're using official [Docker images of Pandoc][pandoc-docker].
You need to have Docker installed to build the PDF. See `Makefile`.

Semaphore automatically creates and uploads the PDF as an artifact from the
latest version of source text. See [project on Semaphore][semaphore-project].

## Writing

Markdown source intentionally doesn't include new lines at 80 characters. This
is so that text is easy to paste and edit in editors like iA Writer and
Hemingway.

## Contributing

Feel free to contribute to the quality of this book by opening issues or
submitting PRs for improvements to explanations, code snippets, etc.

## Copyright & License

Copyright © 2022 Rendered Text.

This work is licensed under CC BY-NC-ND 4.0 <a href="https://creativecommons.org/licenses/by-nc-nd/4.0"><img height="16" style="margin-left: 3px;vertical-align:text-bottom;" src="https://search.creativecommons.org/static/img/cc_icon.svg" /><img height="16" style="margin-left: 3px;vertical-align:text-bottom;" src="https://search.creativecommons.org/static/img/cc-by_icon.svg" /><img height="16" style="margin-left: 3px;vertical-align:text-bottom;" src="https://search.creativecommons.org/static/img/cc-nc_icon.svg" /><img height="16" style="important;margin-left: 3px;vertical-align:text-bottom;" src="https://search.creativecommons.org/static/img/cc-nd_icon.svg" /></a>

[pandoc]: https://pandoc.org
[pandoc-docker]: https://github.com/pandoc/dockerfiles
[semaphore-project]: https://semaphore-oss.semaphoreci.com/projects/book-microservices
