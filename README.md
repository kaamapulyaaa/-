# money-converter-KZT-to-USD
money converter KZT to USD
**A cli tool to get latest KZT (tenge) exchange rates**

## Installation

``` bash
  $ [sudo] npm install kzt -g
```

## Usage

```bash
kzt [-h] [-c {"USD", "EUR", "RUB"}] [-a]

Options:
  -c, --currencies  choose the currencies to display KZT exchange rates for
           [array] [choices: "USD", "EUR", "RUB"] [default: ["USD","EUR","RUB"]]
  -a, --all         display KZT exchange rates from all sources        [boolean]
  -h, --help        Show help                                          [boolean]

Examples:
  kzt -a -c USD   display exchange rates to USD from all sources
  kzt -c USD EUR  display average exchange rates to USD and EUR
```
