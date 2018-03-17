# navbar-zurbpatch
A patch for the Navbar module to fix an enlarging font issue with Zurb Foundation.  

diff --git a/css/navbar.module.css b/css/navbar.module.css
index 04586fb..8f0dfd0 100644
--- a/css/navbar.module.css
+++ b/css/navbar.module.css
@@ -136,6 +136,7 @@
 }
 
 #navbar-administration ul.navbar-menu {
+  font-size: 1em;
   border: none;
   list-style: none;
   text-align: left; /* LTR */
