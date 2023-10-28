diff is used to compare files and directories. This often-used utility program has many useful options (see: man diff) including:

-c
Provides a listing of differences that include three lines of context before and after the lines differing in content
-r Used to recursively compare subdirectories, as well as the current directory
-i Ignore the case of letters
-w Ignore differences in spaces and tabs (white space)
-q Be quiet: only report if files are different without listing the differences

diff [options] <filename1> <filename2>
