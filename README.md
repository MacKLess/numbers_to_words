# _Numbers to Words_

#### _Epicodus practice in Ruby, 9/5/17_

#### By _**Kelsey Langlois and L. Devin MacKrell**_

## Description

_This Ruby application translates a number into words._

## Setup/Installation Requirements

* _Clone application from github repository: https://github.com/langlk/numbers_to_words.git_
* _From this repository run numbers_to_words.rb_

## Specifications

* _Returns "zero" if the number is 0_
  * Example input: 0
  * Example output: "zero"
* _Returns the correct word for single digit numbers._
  * Example input: 7
  * Example output: "seven"
* _Returns correct word for numbers 10-19._
  * Example input: 12
  * Example output: "twelve"
* _Returns correct word for 10s places._
  * Example input: 30
  * Example output: "thirty"
* _Returns correct word for powers of ten up to one trillion._
  * Example input: 1,000
  * Example output: "one thousand"
* _For numbers that are not even powers of ten, uses correct term for thousands place._
  * Example input: 900,000
  * Example output: "nine hundred thousand"
* _Constructs string with words for each place._
  * Example input: 1,999
  * Example output: "one thousand nine hundred ninety nine"

## Known Bugs

_We are unaware of any bugs at this time._

## Support and contact details

_If you run into any issues or have questions, ideas or concerns, or if you would like to contribute to the code, please contact: kels.langlois@gmail.com or ldmackrell@gmail.com ._

## Technologies Used

_This application was created using Ruby_

### License

Copyright (c) 2017 **_Kelsey Langlois and L. Devin MacKrell_**

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
