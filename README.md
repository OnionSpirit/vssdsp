# VssDsp
## Installation
#### 1)Clone to project repository

#### 2)Add to cmake:

   ```
   add_subdirectory(vssdsp)
   target_include_directories(${PROJECT_NAME} PRIVATE vssdsp/include)  
   target_link_libraries(${PROJECT_NAME} PRIVATE vssdsp)  
   ```
   
   _It might be any executable file name instead of ${PROJECT_NAME}_
   *Also lib requiers libliquidsrd to be installed*
