# shell redirection 
echo "Hello, World" : prints hello world
echo "\"(Ôo)'" : display  a confused smiley
cat /tc/passwd : displaythe content ont the etc/passwd
cat /etc/passwd /etc/hosts: display the content to the etc/paswwd and etc/hosts
tail -n 10 /etc/passwd : display the last 10 lines to the /etc/passwd
head -n 10 /etc/passwd : display the first 10 lines to the /etc/passwd
head -n 3 iacta | tail -n 1 : display the third line of the file iacta
echo "BEst schoool" | cat > '"'' Best School": creates files named Best School containing the text best school to the end
ls -la > ls_cwd_content : write the result of ls la in ls_cwd_content
tail -n 1 iacta >> iacta : duplicate the last line of the file iacta
find . -type f -name "*.js" -delete : delete all the regular with th .js extention in the current directory
fing . -type d -not -name '.' | wc -l : count the numbre of directories and subirectories in the current directory 
ls -t1 | head -n 10: create a script that displays 10 new lines in the current directory
sort | uniq -u : create a script that takes a list of words as input and prints only words that appear exactly onces
grep -i "root" /etc/passwd : displays lines containning the partern "root" from the file /etc/passwd
grep -c -i "bin" /etc/passwd: displays the number of lines that contain the patern bin in the file /etc/passwd
grep -i "root" -A /etc/passwd : displays line containing the patern "root" and lines and three lines after them
grep -i -v "bin" /etc/passwd:dsplay all lines in the files /etc/passwd that not conteet the patern "bin"
grep -i "^[a-z]" /etc/ssh/sshd_config: displays all lines of the sshd_configstarting with a letter
tr "A" "Z" | tr "c" "e": replace all characters A and Z by c and e respectively
tr -d "cC" : creates a scripts that remove all letters c and C
rev: reverse the input
cut -d ':' -f 1,6 /etc/passwd | sort : displays all users and their homedirectories, sorted by users
find . -empty | rev | cut -d '/' -f 1 | rev : find all empty files and directories in the current directory an sub_directories 
