git diff 7910 5455



	diff --git a/file2 b/file2
	index cb80a5f..e1e96b4 100644
	--- a/file2
	+++ b/file2
	@@ -1 +1,2 @@
	 file2 is created

echo file1 is modified > file1
git diff HEAD
	diff --git a/file1 b/file1
	index 3ad59b6..b92c452 100644
	--- a/file1
	+++ b/file1
	@@ -1 +1 @@
	-file1 is created
	+file1 is modified
git diff maint
	diff --git a/file1 b/file1
	index 3ad59b6..b92c452 100644
	--- a/file1
	+++ b/file1
	@@ -1 +1 @@
	-file1 is created
	+file1 is modified
	diff --git a/file2 b/file2
	new file mode 100644
	index 0000000..e1e96b4
	--- /dev/null
	+++ b/file2
	@@ -0,0 +1,2 @@
	+file2 is created
	+this file is modified
	diff --git a/file3 b/file3
	new file mode 100644
	index 0000000..b42a3d2
	--- /dev/null
	+++ b/file3
	@@ -0,0 +1 @@
	+file3 is modified

git diff --cached
	diff --git a/file1 b/file1
	index 3ad59b6..b92c452 100644
	--- a/file1
	+++ b/file1
	@@ -1 +1 @@
	-file1 is created
	+file1 is modified

git diff
	diff --git a/file2 b/file2
	index e1e96b4..45b983b 100644
	--- a/file2
	+++ b/file2
	@@ -1,2 +1 @@
	-file2 is created
	-this file is modified
	+hi
	diff --git a/file3 b/file3
	index b42a3d2..45b983b 100644
	--- a/file3
	+++ b/file3
	@@ -1 +1 @@
	-file3 is modified
	+hi

