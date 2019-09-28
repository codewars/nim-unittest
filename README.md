Nim unittest output formatter for Codewars.

Currently, this is used like the following:
```nim
# tests.nim
import unittest, codewars_output
addOutputFormatter(OutputFormatter(newCodewarsOutputFormatter()))

import solution
include solution_tests
```
