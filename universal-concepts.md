# Universal Concepts

## Good Code Is
- Understandable 
  - Junior/mid-weight developers should be able to understand it
- Concise 
  - Only write the minimum that you need
- Elegant 
  - Beautiful code does not need to be complex
  

## SOLID Principals And Balancing Granularity
- Aim for methods and classes to be Single responsibility
- Be aware of the tradeoffs of being too granular


## Unit Testing
- Appropriate test coverage is almost never 100%.
  - There are diminising returns. 
- There is no point writing code now, thinking that you will write tests later. It probably won't happen!
- Use unit tests to help you architect your code  


## Naming
- Naming should be meaningful and understandable 
  - Avoid calling everything a Service/Helper/Handler
- Avoid abbreviations where possible
  - Acceptable exceptions may include commonly understood abbreviations eg. Intro. 


## Methods/Functions/Constructors
- Number of parameters: ~<5 
  - Exceeding ~5 is a signal to possibly reconsider the architecture
- Avoid God-methods 
  - Splitting a God-method into multiple methods in the same file only masks the problem. It's still a God-method!

