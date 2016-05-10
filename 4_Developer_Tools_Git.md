# 4 Developer Tools - Git

## Assignment
1. From master, create a new branch named **shopping_cart_assignment**.
2. Remove **apple.txt** from the repository using *git rm*.
3. Add the text "Git Checkpoint Assignment." to **banana.txt**.
4. Create a file named **lettuce.txt** and add the output of the *git diff* command as the contents.
5. Commit the changes you have made.
6. Run cat **lettuce.txt** to print the contents of **lettuce.txt**.
7. Copy the output into a Markdown code block and send it to your Mentor for review.

## Output:
```bash
$ cat lettuce.txt
diff --git a/banana.txt b/banana.txt
index e69de29..6046aa1 100644
--- a/banana.txt
+++ b/banana.txt
@@ -0,0 +1 @@
+Git Checkpoint Assignment
```

## History Output:
```bash
  214  git checkout master
  215  git checkout -b shopping_cart_assignment
  216  git rm apple.txt
  217  git status
  218  ls
  219  echo "Git Checkpoint Assignment" >> banana.txt
  220  touch lettuce.txt
  221  git diff >> lettuce.txt
  222  git status
  223  git add banana.txt
  224  git commit -m "Add new text to banana.txt"
  225  git status
  226  git add lettuce.txt
  227  git commit -m "Add lettuce.txt"
  228  git log
  229  cat lettuce.txt
  230  git history
  231  history
```