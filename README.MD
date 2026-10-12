# ESEP Grade Calculator

This library is a simple utility to calculate your grades.

Runtime requirements:
Golang 1.24+

Installing Go:
```
winget install GoLang.Go
```

Run unit tests:
```
cd grade-calculator/
go test ./...
```

Run unit tests with code coverage:
```
cd grade_calculator/
go test -coverprofile=coverage.txt ./...
```

### Structure

Code: graade_calculator.go
Tests: grade_calculator_test.go

### Grading Specifications:

Assignments: 50%
Exams: 35%
Essays: 15%

A: >=90%
B: >=80%
C: >=70% (C and above: Passing)
D: >=60% (D and below: Failing)
F: <60%

