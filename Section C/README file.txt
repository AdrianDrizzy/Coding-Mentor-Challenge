Number-to-Word Converter
This is a simple Java program that converts a given numeral (just digits without separators) to its standard English word form, complete with punctuation.

Installation
To use this program, simply download the SayNumber.java file and include it in your project. The SayNumber class contains a single static method, sayNumber, which takes a long argument and returns a String containing the English word form of the number.

Usage
To use the sayNumber method, simply call it with a long argument containing the numeral you wish to convert. For example:

long number = 123456789;
String wordForm = SayNumber.sayNumber(number);
System.out.println(wordForm);
// Output: "One hundred and twenty three million, four hundred and fifty six thousand, seven hundred and eighty nine."

Note that the sayNumber method only works for numbers up to 999 trillion (i.e., 15 digits long).

Contributing
If you find any bugs or issues with this program, please feel free to submit an issue or pull request. Any contributions are welcome!