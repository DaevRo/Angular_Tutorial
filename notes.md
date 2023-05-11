
//create new component - Home is the name of the new component being made.  standalone is a new component style that reduces complexity and adds other features.  
ng generate component Home --standalone --inline-template

input properties
ng generate interface houseLocation

*ngFor
angular template syntax. 



// ng = angluar cli
// g = generate
// c = component
// details = name of component generated
// standalone = instruct the cli to to generate the component as a standalone component
// inline-template = instructs cli to include a template property in the compment decorators metadata
ng g c details --standalone --inline-template 

// s = service
ng g s housing

npm install -g json-server

json-server --watch db.json