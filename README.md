# code-guide
This is a high level set of guidelines for c# MVC web development. The purpose is to gather commonly used best practices in a single place.

# Presentation Layer
## MVC Controllers
- Uses constructor injection


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







