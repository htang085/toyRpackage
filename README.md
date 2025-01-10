# toyRpackage

A simple R package to demonstrate package creation and distribution for DSCI 524.

---

## Features
- A simple `add_numbers(a, b)` function that returns the sum of two numbers.
- Example code to demonstrate how to package and distribute an R project.

---

## Installation

To install this package from GitHub, use:

```r
# Install devtools if not already installed
install.packages("devtools")

# Install the package
devtools::install_github("htang085/toyRpackage")

## Here’s a simple example to demonstrate how to use this package:
# Load the package
library(toyRpackage)

# Use the add_numbers function
result <- add_numbers(2, 3)
print(result)  # Outputs: 5

##Development
To install this package for development purposes:
# Clone the repository
git clone https://github.com/htang085/toyRpackage.git

# Navigate to the package directory
cd toyRpackage

# Load the package in RStudio for development
devtools::load_all()

# To run the tests:
# Install the testthat package
install.packages("testthat")

# Run tests
devtools::test()

##TODO
Add more functions to the package.
Improve testing coverage.

