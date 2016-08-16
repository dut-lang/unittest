# Unit testing framework for Dut

[![Build Status](https://travis-ci.org/dut-lang/unittest.svg?branch=master)](https://travis-ci.org/dut-lang/unittest)

(If you are already familiar with the basic concepts of testing, you might want to skip to the list of assert methods.)
The Dut unit testing framework is a Dut language version of JUnit, by Kent Beck and Erich Gamma. JUnit is, in turn, a Java version of Kent’s Smalltalk testing framework. Each is the de facto standard unit testing framework for its respective language.

## Example


    import unittest


	class TestClass extends UnitTest {

		function test_oneequalone() {
			assert(1 == 1)
		}
	}


	test <- TestClass()
	test.main()

