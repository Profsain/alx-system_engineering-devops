I/O Redirection Shell Scripting project

List of Script Learned with discription

echo command - Print text to standard outpt screen e.g echo "Hello World"

cat command - To display the content of a file e.g caht /etc/passwd

tail -n 10 fileName - Display the last 10 lines of fileName

head -n 10 fileName - Display the first 10 lines of fileName

cat iacta | head -3 | tail -1 command - Display the third line of the file iacta

ls -la > ls_cwd_content : write the output of ls -la command into ls_cwd_content file

tail iacta >> iacta : To append last lin duplicate of iacta to iacta

find . -name "*.js" -delete  : Delete all .js files from the current working directory and its subfolder

find <dirName> -type d | wc -l : To find and count all the folder in the current working directory both hidden subfolder

ls -t <dirName> | head -10  : To show 10 most recent modified file sorted by date

cat <fileName> | sort | uniq -u : To display words in the list fileName that is not duplicated

grep <pattern> <filename> : to display lines containing the pattern from the file

grep -A3 "root" /etc/passwd  : To display lines containing the pattern root and 3 line after them in the given file /etc/passwd

grep -vi "bin" /etc/passwd  : To display all the lines in the file that do not contain the pattern bin and i option make the search case insensitive

