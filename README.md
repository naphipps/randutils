# Randutils

This repo brings [imneme's randutils.hpp gist](https://gist.github.com/imneme/540829265469e673d045) into a normal repo so I can add a CMakeLists.txt, and use [this techinique](https://gist.github.com/naphipps/9784df722d45c8e1bbe7108d182c466a) to use randutils.hpp with [imneme's pcg-cpp random generator](https://github.com/imneme/pcg-cpp). Imneme describes [the usefulness of randutils.hpp in her blog](https://www.pcg-random.org/posts/developing-a-seed_seq-alternative.html).

## Build with cmake

- Don't forget to add the subdirectory you put randutils and link to it like so: ```target_link_libraries(${PROJECT_NAME} PUBLIC randutils)```