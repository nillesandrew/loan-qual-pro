# Loan-Qual Pro

This CLI utility enables our loan system to accuratly screen customer loan applications and outputs a list of qualified lenders for the customer and Loan officer to review. This program takes a active look at live data from the companys rate sheet, and screens this list for basic minimum DTI and LTI criteria. Using this program, we can speed up the prequalification process and streamline the loan pipeline.

---

## Technologies

This project leverages python 3.7.13 with the following packages:

* [fire](https://github.com/google/python-fire) - For the command line interface and entry-point.

* [questionary](https://github.com/tmbo/questionary) - For interactive user prompts and dialogs

---

## Installation Guide

Before using, install the following dependencies.

```python
  pip install fire
  pip install questionary
```
## Usage


![Launch the program & Enter in the path to the rate sheets](2.PNG)
Launch the program & Enter in the path to the rate sheets.

![enter in customers loan application information](3.PNG)
Enter in customers loan application information.

![Enter file path for output spreadsheet of qualified banks](5.PNG)
Enter file path for output spreadsheet of qualified banks.

![Finished!](7.PNG)
Finished! Exmaple of output.


---

## Contributors

-Andrew Nilles

Challenge #2 submission for DU Fintech Bootcamp

Special thanks to Katie and Albion

---

## Un-License

This is free and unencumbered software released into the public domain.

Anyone is free to copy, modify, publish, use, compile, sell, or
distribute this software, either in source code form or as a compiled
binary, for any purpose, commercial or non-commercial, and by any
means.

In jurisdictions that recognize copyright laws, the author or authors
of this software dedicate any and all copyright interest in the
software to the public domain. We make this dedication for the benefit
of the public at large and to the detriment of our heirs and
successors. We intend this dedication to be an overt act of
relinquishment in perpetuity of all present and future rights to this
software under copyright law.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS BE LIABLE FOR ANY CLAIM, DAMAGES OR
OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE,
ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR
OTHER DEALINGS IN THE SOFTWARE.

For more information, please refer to <https://unlicense.org>
