NASM
====
NASM by example for Mac OS x64

1. [Hello world](hello/)
2. [Echo](echo/)
3. [Procedural echo](echo-procedural/)
4. [Passing parameters to procedures via registers](echo-parameters-via-registers/)

Following the list in this order is not a MUST, however first examples should be much easier to start with.

Install NASM
------------
`$ brew install nasm`

Build an run
------------
`$ make`

builds the first target (all) that appears in makefile.

To run the executable:

`$ ./hello`

Also there is a make rule for cleaning folder from executables and .o files:

`$ make clean`

License
-------

```
Copyright 2016 Ivan Baranov

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```
