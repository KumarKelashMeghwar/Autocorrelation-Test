
---

# Autocorrelation Tests and Input Validation

This project provides PHP functions for calculating autocorrelation in numerical sequences and validating user input to ensure it follows a specific format. The system checks that the sequence is composed of comma-separated numbers with optional spaces around commas and performs autocorrelation calculations based on user-defined parameters.

## Features

- **Autocorrelation Calculations**: Uses the sequence and user-specified parameters (`i`, `m`, `N`, and `alpha`) to compute autocorrelation values.
- **Input Validation**: Ensures the sequence format is strictly comma-separated numbers, rejecting incorrect formats with an error message.

## Requirements

- PHP installed on the server.

## Usage

1. **Input Format**: Accepts sequences in the format `n1, n2, ..., nN` (numbers separated by commas with optional spaces).
2. **Form Data**: Requires `sequence`, `i`, `m`, `N`, and `alpha` values.
3. **Error Handling**: If input is invalid, the system returns a JSON error response.

## Functions Overview

- **calculateAutocorrelation**: The main function for performing autocorrelation calculations, taking the sequence and additional parameters for customized analysis.

---
