# Person Service API

## Purpose
The Person Service allows users to keep track of important people. 

## Action
The Person Service API supports the following actions:
* Create Person
* Get Person List
* Filter Person List
* Remove Person
* Get Person
* Update Person
* Update Person Status
* Remove Person

## Data
The service keeps tracks of important persons. For each person there is a unique `id` for each person record stored. Each record also contains values for `givenName`, `familyName`, `telephone`, and `email`. Each record also has an internal `status` value. 

## Rules
* When a new record is created the client application can establish the value for `id` or allow the service to assign one. If the client attempts to apply an `id` value that is alreay in use, the new service will reject the record.
* The only valid values for `status` are `active` and `inactive`. Any other value will be rejected by the service.
* The following fields are required when storing updated or new records: `id`, `givenName`, `familyName`, `status`

## Processing
*NONE*


