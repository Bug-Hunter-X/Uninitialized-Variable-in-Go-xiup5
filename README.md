# Uninitialized Variable Bug in Go

This repository demonstrates a common, yet subtle, bug in Go: using uninitialized variables.  Uninitialized variables in Go have default zero values (0 for integers, false for booleans, etc.), which can lead to unexpected behavior if not handled carefully.

The `bug.go` file showcases the problem, while `bugSolution.go` provides the corrected version.

**How to reproduce:**

1. Clone this repository.
2. Run `go run bug.go`.
3. Observe the unexpected output.
4. Run `go run bugSolution.go` to see the correct output.