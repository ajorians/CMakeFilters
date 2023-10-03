set(SUBITEMS SubItems/SubItem1.cpp
             SubItems/SubItem1.h)

add_library(Example SHARED
                ${SUBITEMS}
                file1.cpp
                file2.cpp
                file3.cpp)