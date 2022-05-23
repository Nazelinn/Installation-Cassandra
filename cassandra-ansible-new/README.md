Command line instructions
You can also upload existing files from your computer using the instructions below.


Git global setup
git config --global user.name "Nazelin Özalp"
git config --global user.email "nazelin.ozalp@.com"

Create a new repository
git clone (https://github.com/Nazelinn/Installation-Cassandra/edit/main/cassandra-ansible-new/)
cd inventory
touch README.md
git add README.md
git commit -m "add README"
git push -u origin master

Push an existing folder
cd existing_folder
git init
--git remote add origin (https://github.com/Nazelinn/Installation-Cassandra/edit/main/cassandra-ansible-new/)
git pull --originalde değişiklik olur ise
git add .
git commit -m "Initial commit"
git push -u origin master

Push an existing Git repository
cd existing_repo
git remote rename origin old-origin
git remote add origin (https://github.com/Nazelinn/Installation-Cassandra/edit/main/cassandra-ansible-new/)
git push -u origin --all
git push -u origin --tags

git clone in local 
git clone https://github.com/Nazelinn/Installation-Cassandra/edit/main/cassandra-ansible-new/
cd cassandra-ansible-new
