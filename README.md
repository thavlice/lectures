# Lectures

This repository contains lecture slides for Course Go.

## Content

1. Introduction
    - Course introduction & requirements
    - Course overview
    - Origins of Go
    - Comparison with other languages
    - Concurrency
    - Use Cases
    - Why learn it
    - Installation
    - Tooling
2. Fundamentals #1
    - Keywords
    - Data types
    - Operators
    - Variables
    - Pointers
    - Visibility
    - Packages
    - Control flow
    - Functions
    - Structures
3. Fundamentals #2
    - Interfaces
    - Errors
    - Arrays
    - Slices
    - Maps
    - Range
    - Generics
    - Standard library

## Tooling

The slides are made using the [go present syntax](https://pkg.go.dev/golang.org/x/tools/present).
You can run the slides locally using the go present CLI command.


### Installation

You can install the CLI command via go install like so:

```
go install golang.org/x/tools/cmd/present
```

This installs the **present** executable into your **$GOPATH/bin** directory.

### Usage

Running the present tool is simple:

```
present
```

A webserver is run on localhost where you can preview the slides using your favourite web browser.

## Atribution

Some of the lecture slides are based on the [GoCourse](https://github.com/RedHatOfficial/GoCourse) 
project developed under [Red Hat](https://github.com/RedHatOfficial). The GoCourse is licensed under 
[CC BY-SA 4.0 DEED license](https://creativecommons.org/licenses/by-sa/4.0/deed.en), which this 
repository respects and therefore shares.

