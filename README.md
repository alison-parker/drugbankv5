# Mirror of the Drugbank.ca Database 
To simplify experimentation and use of this dataset by open source developers, this is a mirror of the newest version 5 of the database. 

The file is completely unmodified, the only thing that has been done is removing the `*.zip` archive and replacing it with the `*.bz2` compression algorithm supported both by Linux and OSX by default. The reason is because the original `zip` compression is roughly the same size as a `gzip2` attempt, resulting in a file size above `100 MB`, at `130MB`. 

Using the `bz2` compression brings it below the `100MB` file size and allows it to be uploaded to github. 

### SHA512 Checksum

Checksum for the newly compressed file

```
6df1968f49f07876c688fb2223019c273889fb2be0dbfc04a14beeb5cc8db976679cc044dd940f7b0d0914a3786c5009f49fedb07cc820791fa8cb81cde2b193  drugbank_all_full_database.xml.tar.bz2 
```

And checksum for the contents that third parties can verify with their own versions directly frum drugbank.ca to verify 

```
07d5eb686c358d8ac12f9ce71a73c94f3abbcf85ac1dfe3278ef5c6ec1722a06f449c2ac5bbde4c3bd0d216633a78f549c1e56ad16e7134668f7aafc1bc5b12b  full database.xml
```

### Creative Commons License 
This database is creative commons non-commericial. So commercial developers need to get permission, but open source developers working on projects just go for it. The point of adding it here was to increase the access and get more people using this datasets in their applications or being inspired by this dataset to write software. Review https://drugbank.ca for more information. 
