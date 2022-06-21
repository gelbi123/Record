Overview
========

This fork is used for my Zope4 buildout
with customized code.

Record provides special objects used in some Zope2 internals like ZRDB.

Records are used to provide compact storage for catalog query results.

They don't use instance dictionaries. Rather, they store they data in
a compact array internally. They use a record schema to map names to
positions within the array.
