# **Temperature-Conversion**

This package allows you to convert the temperature
types to _Celsius_ , _Fahrenheit_ , _Kelvin_ , _Rankine_ Scale.

## Docs!

Import the module and call the convert function with the parameters.
> Value : value of the temperature, Eg: 25.

> Type : Conversion type, Eg: c-f.

### Parameters for Type
> c-f : To convert Celsius to Fahrenheit.

> c-k : To convert Celsius to Kelvin.

> c-r : To convert Celsius to Rankine.

> k-c : To convert Kelvin to Celsius.

> k-f : To convert Kelvin to Fahrenheit.

> k-r : To convert Kelvin to Rankine.

> f-c : To convert Fahrenheit to Celsius.

> f-k : To convert Fahrenheit to Kelvin.

> f-r : To convert Fahrenheit to Rankine.

> r-c : To convert Rankine to Celsius.

> r-f : To convert Rankine to Fahrenheit.

> r-k : To convert Rankine to Kelvin.

Sample Code!
```
const convert = require("temperature-conversion")

console.log(convert(25,"C-f"));
console.log(convert(25,"c-k"));
console.log(convert(25,"c-r"));
console.log(convert(25,"f-c"));
console.log(convert(25,"f-k"));
console.log(convert(25,"f-r"));
console.log(convert(25,"k-c"));
console.log(convert(25,"k-f"));
console.log(convert(25,"k-r"));
console.log(convert(25,"r-c"));
console.log(convert(25,"r-f"));
console.log(convert(25,"r-k"));

```
Output
```
C:\Users\Desktop\Npm\Conversion>node script.js
77
298.15
536.6700000000001
-3.888888888888889
269.26111111111106
484.67
-248.14999999999998
-414.66999999999996
45
-259.2611111111111
-434.67
13.88888888888889
```
