set(SUBITEMS SubItems/SubItem1.cpp
             SubItems/SubItem1.h)

source_group("My SubItems" FILES ${SUBITEMS})

set(FILEITEMS file1.cpp
              file2.cpp)

source_group("Some Files" FILES ${FILEITEMS})

add_library(Example SHARED
                ${SUBITEMS}
                ${FILEITEMS}
                file3.cpp)

