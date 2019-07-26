# code-guide
This is a high level set of guidelines for c# MVC web development. The purpose is to gather commonly used best practices in a single place.


# High Level Concepts
## Code must be
- Understandable (by a junior/mid-weight developer)
- Concise
- Elegant  

## Class & Interface Naming
- Naming should be meaningful and understandable 
- Avoid calling everything a Service/Helper



# Presentation Layer
## MVC Controllers
- Use constructor injection
- Actions should typically be no longer than 10-20 lines


## MVC View Models
- Simple plain old c# objects with public properties
- Contains everything the view actually requires
- Generally should not contain public methods


## MVC Views
- Contains clean HTML
- Only render data from View Models
- Do not fetch/query data from a view (see MVC View Models) 
- C#/logic should be kept to an absolute minimum



# Domain Logic
## Extension Methods

## Builders

## Helpers

## Services







