# Elixir Enum.each and Process.exit Bug

This repository demonstrates a subtle bug involving the use of `Process.exit` within an `Enum.each` loop in Elixir.  The program attempts to iterate over a list and print each element, but prematurely terminates when a specific condition is met.

The `bug.ex` file contains the buggy code.  The `bugSolution.ex` file provides a corrected version.

The issue highlights the importance of understanding how `Process.exit` affects the overall program execution flow, particularly within parallel or concurrent operations.  The solution demonstrates a more appropriate approach to handling such scenarios.
