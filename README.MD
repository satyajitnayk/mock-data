# Random Data Generator Website

## Overview

This site generates random data based on a predefined schema. Perfect for testing and development purposes.

## Features

- Define custom schemas for data generation.
- supports `string`, `number` & `generic` as of now.
- Instant JSON formatted data output.
- User-friendly interface with real-time data generation.

## Schema Definition

Our current schema is structured as follows:

```json
[
  {
    "name": "full_name",
    "type": "string"
  },
  {
    "name": "age",
    "type": "number"
  },
  {
    "name": "rating",
    "type": "generic"
  }
]
```

## Example Output

Upon generation, data will resemble:

```json
{ "full_name": "Innovatech Ltd", "age": 25, "rating": "4.7" }
```

## How to Use

1. Load the website.
2. Enter the desired schema in the provided form.
3. Hit the 'Generate' button to produce random data.
4. The generated data will be displayed on the screen.

## Local Setup

To run the website locally:

1. Clone the repo to your machine.
2. Open the `index.html` file in a web browser.

## Contributions

Feel free to contribute to the project by submitting pull requests or issues on the repository.
