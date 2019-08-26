# Object properties

**Typing, schemaless/schemafull** - are all fields of the object are known?
**Presence of ID** - presence or missing of an Id property (or alike) on an object
**Multiple ID** - presence of several Id's for one
**Separate ID** - is Id for object stored in map<objectRef, Id> and not inside the object
**Persistent or Runtime** - if an object can be saved and loaded to/from an external storage - server/database
**RAII disposial** - does this kind of object requires to be "disposed" or "released"
**Created on stack or on Heap** - close to "RAII disposal".
**Mutablity** - can an object fileds be changed once created?
**Versions / Change layers** - does this object have change history? Or maybe different fields' data is attached to this ID for different environments?
**Memory management** - manual/garbage-collection/reference counting
