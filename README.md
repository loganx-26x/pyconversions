# pyconversions
Convert all types of Unit Length Datas. The one's in this Package are:

Inches

Feet

Yard
Millimeter

Centimeter

Decimeter

Decameter

Hectometer

Meter

Kilometer


Other than Unit Lengths the ones added in the package are:

Fahrenheit

Celsius


For starters, Import the Class as Shown below:

import pyconversions.pyconv as pycv


After that for an instance, lets say to Convert 12 Inches to Meters use:

pycv.Inches(12).toMeters()


Or to Convert 12 Meters to Centimeters use:

pycv.Meters(12).toCentimeters()


Just like for for Unit Lengths, you can use it for Temperatures too as follows:

pycv.Fahrenheit(35).toCelcius()


Or to Convert it Vice-Versa use:

pycv.Celcius(68).toFahrenheit
