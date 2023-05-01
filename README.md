# promptEngJulia

This repository contains the Jupyter notebooks of the online course [**ChatGPT Prompt Engineering for Developers**](https://www.deeplearning.ai/short-courses/chatgpt-prompt-engineering-for-developers/) course by Isa Fulford and Andrew Ng.

### Notes specific to Julia:
- Instead of using {  } for string interpolation with f strings in Python, __$__ is used in Julia.
- Don't use single backslash, \\, in the text or you will get an "Invalid escape character" error. 
Either use double backslash, \\\\, or don't use it at all. 
- If you have to use \$ sign in a text, write it as \\$ as it is the string interpolation operator in Julia. 
- In Julia, " is used for strings and ' is used for characters. 