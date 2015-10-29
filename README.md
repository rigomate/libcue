# Overview

libcue provides an API for parsing and extracting data from [CUE sheets](https://en.wikipedia.org/wiki/Cue_sheet_%28computing%29).

libcue was originally forked from [cuetools](https://github.com/svend/cuetools) and then enhanced by Jochen Keil to add additional features.

Please refer to [libcue.h](https://github.com/lipnitsk/libcue/blob/master/libcue.h) for the API.

Some usage examples are also available in the test cases under [t/](https://github.com/lipnitsk/libcue/tree/master/t).

# Contributing

One should note that while the CUE format is supported by various tools, such as media players or CD ripping tools, there is no single standard that strictly describes the CUE syntax.

libcue attempts to parse the most commonly known CUE layouts, but it does not claim to support every possible combination.

Therefore, if you would like to contribute to the library, please include a test case with your pull request to ensure that the functionality does not break in the future.
