# ESEP Grade Calculator

This library is a simple utility to calculate your grades.

It is written entirely in the Go language.

Runtime requirements:
Golang 1.24+

Run unit tests:
```
cd grade_calculator/
go test ./...
```

Run unit tests with code coverage:
```
cd grade_calculator/
go test -coverprofile=coverage.txt ./...
```

## File summary

-	grade-calculator/go.mod: The purpose of a go.mod file is that it is the root of a collection of packages; it defines a module. The first line describes the module path, and the second line defines the minimum required version of go for the module. 
-	grade-calculator/grade_calculator.go: This file defines the grade calculator and its functions as well as the grade types. 
-	grade-calculator/grade_calculator_test.go: This file contains tests to verify expected behaviors of grade_calculator/grade_calculator.go

## Resources

 Outside of the README, https://go.dev/doc/ is a useful resource for understanding the content of this codebase. 