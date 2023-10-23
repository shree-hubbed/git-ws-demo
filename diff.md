# Git diff
The `git diff` command shows the line-by-line modifications
between HEAD (i.e. last commit on current branch) and the 
current working tree modifications (not yet staged/committed).
Here's an example of the diff output:
```
$ git diff
diff --git a/README.md b/README.md
index 4140743..0574b0e 100644
--- a/README.md
+++ b/README.md
@@ -2,3 +2,11 @@
 
 This is the README file of my awesome project.
 More to come soon...
+
+## Querying the current git repo state
+
+In a terminal type:
+
+```
+git status
+```
```
