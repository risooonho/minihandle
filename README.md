# minihandle

Simple Rust crate for managing handles, a.k.a. weak references, a.k.a. generational indices.

See [http://bitsquid.blogspot.com/2014/08/building-data-oriented-entity-system.html](http://bitsquid.blogspot.com/2014/08/building-data-oriented-entity-system.html)

## Features

"index" (disabled by default) - provides a simplified implementation of an index manager / array which doesn't handle the generation / sequence number.