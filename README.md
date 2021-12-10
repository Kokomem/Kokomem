- 👋 Hi, I’m @Kokomem
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Kokomem/Kokomem is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->https://www.xvideos.com/

diff --git a/src/cc/CMakeLists.txt b/src/cc/CMakeLists.txt
index fd6037a..4d6e35b 100644
--- a/src/cc/CMakeLists.txt
+++ b/src/cc/CMakeLists.txt
@@ -42,7 +42,7 @@ set_target_properties(bcc-shared PROPERTIES OUTPUT_NAME bcc)
 add_library(bcc-loader-static STATIC ${bcc_sym_sources} ${bcc_util_sources})
 target_link_libraries(bcc-loader-static elf)
 add_library(bcc-static STATIC
-  ${bcc_common_sources} ${bcc_table_sources} ${bcc_util_sources})
+  ${bcc_common_sources} ${bcc_table_sources} ${bcc_util_sources} ${bcc_sym_sources})
 set_target_properties(bcc-static PROPERTIES OUTPUT_NAME bcc)
 
 include(clang_libs)
