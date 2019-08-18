
# MVC - Presentation Layer

## Controllers
- Actions should typically be no longer than 10-20 lines
- Buids/acquires View Models with all the data required for a View


## View Models
- Simple plain old objects with public properties
- Contains everything the view actually requires
- Generally should not contain public methods


## Views
- Contains clean HTML
- Does not fetch/query data 
- Rendering logic should be kept to an absolute minimum
