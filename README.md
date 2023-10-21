# greeting-module

Project with an example to import modules in other projects

### Example
Copy the following code in your own project  to use HelloWorld() function from this module:
```
package main

import utils "github.com/Nerfo1124/greeting-module"

func main() {
	utils.HelloWorld()
}
```