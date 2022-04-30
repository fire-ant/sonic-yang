# sonic-db jsonschema validator 

A small tool to convert the yang model that Azure Sonic NOS uses to a reusable jsonschema with which configs can be tested.



example usage:
`jsonschema -i config_db.json  models/policy/config_db.jsonschema  -o pretty`
with the cli tool:
`jsonschema-cli validate models/policy/config_db.jsonschema config_db.json`