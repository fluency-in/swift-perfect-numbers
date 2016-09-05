# Swift: Perfect Numbers

The Greek mathematician Nicomachus devised a classification scheme for natural numbers.

The Greek mathematican Nicomachus devised a classification scheme for
natural numbers, identifying each as belonging uniquely to the
categories of _abundant_, _perfect_, or _deficient_.  A perfect number
equals the sum of its positive divisors — the pairs of numbers whose
product yields the target number, excluding the number itself.

- Perfect: Sum of factors = number
- Abundant: Sum of factors > number
- Deficient: Sum of factors < number

The Aliquot sum is defined as the sum of the factors of a number not
including the number itself.

## Examples

- 6 is a perfect number because its divisors are 1, 2, 3 and 6 = 1 + 2 +
  3.
- 28 is perfect number because 28 = 1 + 2 + 4 + 7 + 14.
- Prime numbers 7, 13, etc are Deficient by the Nicomachus
  classification.

In order to use Swift, you must be running Xcode version 7.3 or greater which is available at [Apple's developer center][appledev].

[appledev]: https://developer.apple.com/xcode/downloads/

The exercises use XCTest.

See [this guide][exercism-xcode-swift] for details about how to create the project in XCode and run the tests.

[exercism-xcode-swift]: https://github.com/exercism/xswift/blob/master/docs/TESTS.md

## Source

Taken from Chapter 2 of Functional Thinking by Neal Ford. [http://shop.oreilly.com/product/0636920029687.do](http://shop.oreilly.com/product/0636920029687.do)

This exercise is from the [Swift][swift] track on [Exercism][exercism]

[exercism]: http://exercism.io
[swift]: http://exercism.io/languages/swift



