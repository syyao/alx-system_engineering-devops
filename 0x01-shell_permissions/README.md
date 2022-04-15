# shell permissions
script for shell permissions
su betty : switch to user betty
whoiam : print the to the current user
groups: prints all the groups of the current user part of
sudo chown betty hello : changes the owner file hello to the user betty
touch hello : create a empty file named hello
chmod u+x hello : execute file hello
chmod +114 hello : add execution permission to the owner and the group owner 
chmod +x hello: add execution permission to the owner, to the group owner andthe other users
chmod 007 hello : sets the permissions to the fie hello as follow : no permsission to the owner and groupand all permissions for users
chmod 753 hello : set the mode of the file hello
chomd --reference= olleh hello : set the mode of the file hello the same as olleh'smode
