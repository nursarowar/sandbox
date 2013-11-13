# git mergetool
~/.gitconfig

[merge]
	tool = kdiff3

[mergetool "kdiff3"]
	cmd = \"D:\\\\KDiff3\\\\kdiff3\" "$BASE" "$LOCAL" "$REMOTE" -o "$MERGED"
  keepBackup = false
  trustExitCode = false	

[diff]
    tool = kdiff3
    guitool = kdiff3    

[difftool "kdiff3"]
    cmd = \"D:\\\\KDiff3\\\\kdiff3\" "$LOCAL" "$REMOTE"
    keepBackup = false
    trustExitCode = false

[mergetool]
    keepBackup = false

abc
