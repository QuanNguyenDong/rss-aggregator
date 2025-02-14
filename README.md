# RSS Aggregator

## Overview
The RSS Aggregator package is designed to fetch, parse, and manage RSS feeds from various sources. It allows users to subscribe to multiple RSS feeds and aggregate the content into a unified format for easy consumption and processing.

## Features
- Fetch RSS feeds from multiple sources
- Parse RSS feed content
- Aggregate and manage RSS feed data

## Installation

To install the RSS Aggregator package, follow these steps:

1. Ensure you have Go installed on your system. You can download it from [golang.org](https://golang.org/dl/).
2. Open your terminal and run the following command to install the package:

    ```sh
    go get github.com/yourusername/rss-aggregator
    ```

3. Import the package in your Go project:

    ```go
    import "github.com/yourusername/rss-aggregator"
    ```
    ## Project Structure

    ```
    .
    ├── README.md
    ├── go.mod
    ├── go.sum
    ├── handler_err.go
    ├── handler_readiness.go
    ├── handler_user.go
    ├── internal/
    │   └── database/
    │       ├── db.go
    │       ├── models.go
    │       └── users.sql.go
    ├── json.go
    ├── main.go
    ├── models.go
    ├── rssagg/
    ├── sql/
    │   ├── queries/
    │   │   └── users.sql
    │   └── schema/
    │       └── 001_users.sql
    ├── sqlc.yaml
    └── vendor/
    ```

    - `README.md`: Project documentation.
    - `go.mod`: Go module file.
    - `go.sum`: Go dependencies checksum file.
    - `handler_err.go`, `handler_readiness.go`, `handler_user.go`: Handlers for different endpoints.
    - `internal/database/`: Contains database-related logic.
    - `json.go`: JSON utilities.
    - `main.go`: The entry point of the application.
    - `models.go`: Data models.
    - `rssagg/`: RSS aggregator logic.
    - `sql/`: SQL queries and schema.
    - `sqlc.yaml`: SQLC configuration file.
    - `vendor/`: Vendor dependencies.
    