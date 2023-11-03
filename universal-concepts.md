# Universal Concepts

## Good Code Is
- Understandable 
  - Junior/mid-weight developers should be able to understand it (with little explanation)
- Concise 
  - Only write the minimum that you need
- Elegant 
  - Beautiful code does not need to be complex
  

## CUPID Principals And Balancing Granularity
- https://dannorth.net/cupid-for-joyful-coding/
- Aim for methods and classes to be SINGLE responsibility
- Note: Be aware of the tradeoffs of being too granular


## Unit Testing
- Appropriate test coverage does not mean 100%
  - There are diminishing returns, and the 80-20 rule applies here
- There is no point in writing code now, thinking that you will write tests later. It probably won't happen. Moreover, the code you write may not be testable!
- Use unit tests to help you architect your code. If your test is too complicated, then it is likely that your code is too!  


## Naming
- Naming should be meaningful and understandable 
  - Try to avoid calling using these words, as they do not add value to understandability: Service, Helper, Handler, Processor, Utility, Manager
- Avoid abbreviations and acronyms where possible
  - Acceptable exceptions may include VERY commonly understood abbreviations eg. Intro, VPN, PC,  


## Methods/Functions/Constructors
- Try to keep the number of parameters (arguments) <5 
  - Exceeding ~5 is a signal to possibly reconsider your architecture
- Avoid distributed God-methods 
  - Splitting a God-method into multiple methods in the same file only masks the problem. It's still just a decomposed God-method!

