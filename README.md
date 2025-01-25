# Tcl Bug: Unexpected Crash Due to Division by Zero

This repository demonstrates a common but subtle issue in Tcl: the lack of explicit exception handling mechanisms.  When an error occurs, such as division by zero, the script may abruptly terminate without providing sufficient diagnostic information. This makes debugging significantly more difficult.

The `bug.tcl` file showcases a simple procedure that can lead to an unhandled exception.

The `bugSolution.tcl` file provides a solution using error handling techniques.