# rainBow-T

> make rainbow table

#### code that tries to extract efficiency by running a total of 9 processes simultaneously through multiprocessing

#### each process separately creates a rainbow table file through file io.

#### sha1 hash is 40 bytes, but even if only 8 bytes are stored in the rainbow table, the number of cases is 4.2 billion, so there is almost no overlap, so only 8 bytes of the hash value are stored.
