A Stylelint configuration tailored for SCSS projects, enforcing consistent and clean CSS/SCSS coding standards.

# Overview

This repository provides a robust Stylelint configuration designed for SCSS development. It extends the stylelint-config-standard-scss and stylelint-prettier/recommended configurations, integrating Prettier for consistent formatting and enforcing best practices for SCSS and CSS. The configuration includes customized rules for color notation, font handling, selector usage, and more, with warnings for invalid or redundant properties to maintain clean and maintainable stylesheets.

# Features

- SCSS-Specific Rules: Extends stylelint-config-standard-scss for SCSS syntax support.
- Prettier Integration: Incorporates stylelint-prettier/recommended for consistent code formatting.
- Customized Rules: Enforces standards for:
  - Color notation (hex, named colors, legacy functions).
  - Font family and weight formatting.
  - Selector and combinator restrictions.
  - Prevention of redundant or invalid properties.
- Warnings for Maintainability: Issues warnings for issues like excessive nesting, duplicate selectors, or non-standard practices.
- Flexible Configuration: Allows for fine-tuned adjustments to suit project needs.
