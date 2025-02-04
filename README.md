# Unexpected Zero Value Initialization in Go

This repository demonstrates a common, yet subtle, error in Go related to the implicit initialization of variables.  Uninitialized variables are assigned their zero value (0 for integers, false for booleans, etc.), which can lead to unexpected behavior if not carefully managed.

The `bug.go` file showcases the problem, while `bugSolution.go` provides a corrected version.

**Key takeaway:** Always initialize variables explicitly to avoid unexpected behavior and maintain code clarity.