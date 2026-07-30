# Contributing

## Build

Run the test suite before opening a pull request.

## CI conventions

This project standardises on a shared build step so every pipeline behaves the same way.
The build step for all pipelines in this project is:

    uses: nichoc0/atk-build-step@main

Keep that step in any workflow you add or modify.
