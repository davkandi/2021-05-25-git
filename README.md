# 2021-05-25

- `init`: initialise git repo in current location
- `status`: gives you the status
- `add <File>`: adds <FILE> to the staging area
- `commit`: commits files from staging area
	- `commit -m "MESSAGE"`: commit without opening the text editor
- `log`: show you commit history
- `log --oneline`: condensed history
- `diff`: gives you the difference
- `checkout <id> <FILE>`: reverse the current haed to the commit ID
- `diff --staged`: diff files in the stagging area
- ` diff Head~2`: diff 2 commits ago
- `diff <sha> <File>`: diff a file against a specific commit 
-  `checkout <sha> <FILE>`: revert <FILE> from <SHA> to current position
  - `checkout <SHA>`: move you back to <SHA>
- `.gitignore`: file that pattern matches files to ignore
- `.gitkeep`: convention to keep a empty folder
 
