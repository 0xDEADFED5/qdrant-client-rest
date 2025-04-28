This is quick hack job to make qdrant-client compatible with Python 3.13t (free-threaded)

portalocker and grpcio have been removed, because they're not free-threaded compatible.

this leaves only the REST interface.

it's not ideal, but if you need a qdrant-client that works with 3.13t right now, here it is.

i've barely tested it, hopefully i didn't miss anything.