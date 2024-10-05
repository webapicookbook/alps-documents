# API Person Service Vocabulary

## Resources
* home (semantic), Home (starting point) of the person service
* collection (semantic), List of person records
* item (semantic), Single person record

## Actions
* doCreate (unsafe), Create a new person record
* doRemove (idempotent), Remove an existing person record
* doStatus (idempotent), Change the status of an existing person record
* doUpdate (idempotent), Update an existing person record
* goFilter (safe), Filter the list of person records
* goHome (safe), Go to the Home resource
* goItem (safe), Go to a single person record
* goList (safe), Go to the list of person records

## Containers
* person (semantic), The properties of a person record

## Properties
* id (semantic), Id of the person record
* familyName (semantic), The family name of the person
* givenName (semantic), The given name of the person
* email (semantic), Email address associated with the person
* telephone (semantic), Telephone associated with the person
* status (semantic), Status of the person record (active, inactive)
