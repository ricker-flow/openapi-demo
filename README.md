# Micronaut OpenAPI 

## Remote reference demonstration

See https://github.com/micronaut-projects/micronaut-openapi/issues/1613

### Expected Behavior
OpenAPI supports remote references for schema. 
Instead of reference components inside the document `$ref: '#/components/schema/Foo'` 
it can refer to an external files such as 
`$ref: '../folder/foo.json'`. 

See https://swagger.io/docs/specification/using-ref/

### Actual Behaviour
Using a remote reference returns an error `Failed to get the schema name:`

### Steps to reproduce

Build this project.

