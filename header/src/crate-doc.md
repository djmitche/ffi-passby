This crate supports generating a C header for a library crate, directly in the library itself.

Typically the crate would be annotated with the exported macros to define the header content.
Then, the header is generated by calling [`generate`].