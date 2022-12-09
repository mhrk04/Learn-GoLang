# Number Data Type

- ***Integer***
- ***Floating Point***


## Integer Type(1)
***Case sensitive***
| Data Type       | Min Value           | Max Value  |
| ------------- |:-------------:| -----:|
| int8          | -128          | 127 |
| int16    | -32768   |   32767 |
| int32 | -2147483648    |    2147483647 |
| int64 | -9223372036854775808      |   9223372036854775807 |

## Integer Type(2)

| Data Type       | Min Value           | Max Value  |
| ------------- |:---------------------:| ----------:|
|uint8|  0    |  255   |
|uint16|   0  |  65535    |
|uint32|0| 4294967295|
|uint64|0|18446744073709551615|

## Floating Point Data Type

| Data Type       | Min Value           | Max Value  |
| ------------- |:---------------------:| ----------:|
|float32|1.18×10^−38|3.4×10^38|
|float64|2.23×10^−308|1.80×10^308|
|complex64|***complex numbers with float32 real and imaginary parts.***|***same***|
|complex128|***complex numbers with float64 real and imaginary parts.***|***same***|

## Alias

| Data Type       | Alias For           |
| ------------- |:---------------------:|
|byte           |uint8|
|rune|int32|
|int|Minimal ***int32***(Depend on what system you on)|
|uint|Minimal ***uint32***(Depend on what system you on)|