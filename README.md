# Go Webcrawler

## Usage

- make sure that you have [Go](https://go.dev/) installed
- run `go build -o crawler && ./crawler <URL> <maxConcurrency> <maxPages>`

## Description

This webcrawler fetches all internal links on a webpage. It uses concurrency to be faster and can be limited to a max number of pages.

