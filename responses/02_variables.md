# Variables and data types
Variables and data type is important in all programing languages. In this section, we will cover how to define a variable and the basic data types.

## Variables
Variable is a name that can refer to the value we have in memory. In Golang, we can define variable in various way.
### Create variable with var
```go
// Without initialize
var integer int         // default value 0
var decimal float64     // default value 0
var str string          // default value ""
var flag bool           // default value false

// With initialise
var integer int = 10
var decimal float64 = 3.14
var str string = "Hello World"
var flag bool = true

// declare multiple variable in a single statement
var a, b int = 10, 11
```

### Short variable declaration
```go
integer := 10
decimal := 3.14
str := "Hello World"
flag := true
```

## Data Types
Basic data types in golang are:
* integer
* float
* boolean
* string

More details can be found below

### Integer
#### Unsigned integer (non negative value)
* uint8 / byte - (0-255)
* uint16 
* uint32
* uint64
#### Signed integer
* int8 (-128 to 127)
* int16
* int32
* int64
#### Machine Dependent types
* uint (32 or 64 depends on the machine)
* int

### Floating Number
#### Floats
* float32 (32 bits floating number)
* float64

#### Complex
* complex64
* complex128

### Strings
* "Hello World"

### Booleans
* true
* false

Pleae see below for the practises.