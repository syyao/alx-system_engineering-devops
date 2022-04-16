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
