# PLL
🔍 Python Logging Library

## Usage
##### Code
```PY
from logger import Logger

class Class0:
    def __init__(self):
        self.a = "1"
        self.b = 0

class Class1:
    def __init__(self):
        self.class = Class0()
        self.logger = Logger()

        self.run()

    def run(self):
        self.logger("example")
        self.logger(1)
        self.logger(self.class)
```

##### Output
```
example
1
{"a": "1", "b": "0"}
```
