# TODO

* Delete support.
* Integrity tests, make sure bindings don't choke or segfault on really bad data.
* Revisit index support, expand and add tests.
* Possibly implement custom backend support, allowing JS callbacks to provide a custom git backend.
* Check for memory leaks
* Support for ref deletion.
* Implement ref packing method call, without breaking shit.
* Cache raw objects properly, so two requests for the same oid don't result in different objects.
* Maybe add convenience methods to all existing wrapped objects to get the raw object equivalent of them.
