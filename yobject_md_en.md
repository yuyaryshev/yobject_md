How can this list be used? When you are planning a new application or module you start from domains.
This list have some questions which might change your vision about how you should a specific domain.
Also this might help when deciding which language would be the most suitable for implementation.

# Object properties

  - **Typing, schemaless/schemafull** - are all fields of the object are known?
  - **Presence of ID** - presence or missing of an Id property (or alike) on an object
  - **Multiple ID** - presence of several Id's for one
  - **Separate ID** - is Id for object stored in map<objectRef, Id> and not inside the object
  - **Persistent or Runtime** - if an object can be saved and loaded to/from an external storage - server/database
  - **RAII disposial** - does this kind of object requires to be "disposed" or "released"
  - **Created on stack or on Heap** - close to "RAII disposal", but still different in some languages
  - **Mutablity** - can an object fileds be changed once created? Or you want them to be frozen and Immutable?
  - **Versions / Change layers** - does this object have change history? Or maybe different fields' data is attached to this ID for different environments?
  - **Memory management** - manual/garbage-collection/reference counting
  - **Inheritance** - is this object type inherited from some type? Can some other type inherit this object's type?
  - **Multi-base (Diamond) inheritance** - self descriptive
  - **components style** - does this object have different components (see this Article to know what it is: https://thelinuxlich.github.io/artemis_CSharp/)
