Download Link: https://assignmentchef.com/product/solved-cs1331-homework-02-temperature-converter
<br>



<strong> </strong>

<h1>Problem Description</h1>

The company that has hired you has a problem. Half of their thermostats display in degrees Celsius and the other half display in degrees Fahrenheit. All of their thermostats display in integers. Unfortunately there is no way to change the unit of a given thermometer. To remedy this problem your company has asked you to write a simple Java program that will allow your co-workers to easily convert between the two units. Your company has provided you with a Java class Converter.java, so all you will have to do is fill in the provided methods.

<h1>Solution Description</h1>

For this assignment you have been provided Converter.java. This class has several methods where only a method header has been written. To complete this assignment you should correctly fill in the body of each method as specified here and in the provided java file.

The methods you will have to fill in are listed here.

<strong>fahrenheitToCelsius(int temp)</strong>

This method takes in a temperature in Fahrenheit and should return that temperature in Celsius as a double.

<strong>celsiusToFahrenheit(int temp)</strong>

This method takes in a temperature in Celsius and should return that temperature in Fahrenheit as a double.

<h2>printFahrenheitConversionTable(int lower, int upper)</h2>

This method prints out a table of Fahrenheit temperatures from the specified lower bound (inclusive) to the specified upper bound (inclusive) and that temperature converted to Celsius. Round to three decimal places.

Ex) if we ran printFahrenheitConversionTable(32, 33) we should get what’s printed below. Please make sure to use this format exactly or you will not get credit.

Fahrenheit: 32 -&gt; Celsius: 0.000

Fahrenheit: 33 -&gt; Celsius: 0.556

Note: This method should be completed using a FOR loop. <strong>You MAY NOT use a while loop anywhere in this method. </strong>Doing so will yield no credit

<h2>printCelsiusConversionTable(int lower, int upper)</h2>

This method prints out a table of Celsius temperatures from the specified lower bound (inclusive) to the specified upper bound (inclusive) and that temperature converted to Fahrenheit. Round to three decimal places.

Ex) if we ran printCelsiusConversionTable(32, 33) we should get what’s printed below. Please make sure to use this format exactly or you will not get credit.

Celsius: 32 -&gt; Fahrenheit: 89.600

Celsius: 33 -&gt; Fahrenheit: 91.400

Note: This method should be completed using a WHILE loop. <strong>You MAY NOT use a for loop anywhere in this method. </strong>Doing so will yield no credit.

<h2>celsiusWarmer(int celsius, int fahrenheit)</h2>

This method takes in two temperatures, the first in Celsius and the second in Fahrenheit, it should return true if the first temperature is warmer than the second.

Note: <strong>Do NOT use a ternary expression. </strong>Doing so will yield no credit.

<h2>fahrenheitWarmer(int fahrenheit, int celsius)</h2>

<em>This method takes in two temperatures, the first in Fahrenheit and the second in Celsius, it should return true if the first temperature is warmer than the second.</em>

Note: you should use a ternary expression to complete this method. <strong>Do NOT use an if statement. </strong>Doing so will yield no credit.

<h1>Testing your code</h1>

If you want to test out your own code before submitting, we’ve provided some sample cases in the main method. If you run java Converter after compiling your code, this will be the output from the provided cases.

fahrenheitToCelsius: 1.1111111111111112 celsiusToFahrenheit: 39.2 printFahrenheitConversionTable: Fahrenheit: 32 -&gt; Celsius: 0.000

Fahrenheit: 33 -&gt; Celsius: 0.556

Fahrenheit: 34 -&gt; Celsius: 1.111

Fahrenheit: 35 -&gt; Celsius: 1.667

Feel free to create your own tests in the main method! Try to write tests for the remaining methods in the file!

<h1>Rubric</h1>

<ul>

 <li>[15] celsisusToFahrenheit</li>

 <li>[15] fahrenheitToCelsius</li>

 <li>[20] printFahrenheitConversionTable</li>

 <li>[20] printCelsiusConversionTable</li>

 <li>[15] fahrenheitWarmer</li>

 <li>[15] celsiusWarmer</li>

</ul>


