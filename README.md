**Lightweight mock implementations of a [PSR-18 HTTP Client](https://www.php-fig.org/psr/psr-18/), [PSR-17 HTTP Factories](https://www.php-fig.org/psr/psr-17/) and [PSR-7 Messages](https://www.php-fig.org/psr/psr-7/) tailored to simplify unit testing.**

This is a meta-package that includes all of the [PSR Mock](https://github.com/psr-mock) utility suite's HTTP packages.

This suite is largely intended for inclusion in libraries like SDKs that consume PSRs without requiring hard dependencies on specific libraries.

-   [Requirements](#requirements)
-   [Installation](#installation)
-   [Usage](#usage)
-   [Contributing](#contributing)

## Requirements

-   PHP 8.0+
-   Composer 2.0+

## Installation

```bash
composer require psr-mock/http
```

## Usage

Usage instructions for each discovery library can be found at the links below:

-   [PSR-18 HTTP Client](https://github.com/psr-mock/http-client-implementation)
-   [PSR-17 HTTP Factories](https://github.com/psr-mock/http-factory-implementation)
-   [PSR-7 HTTP Messages](https://github.com/psr-mock/http-message-implementation)

## Contributing

Contributions are welcome! Please create issues and pull requests on the repository for the specific discovery library you're interested in.

As a meta-package, this repository is not intended to accept contributions.

---

This library is not produced or endorsed by, or otherwise affiliated with, the PHP-FIG.
