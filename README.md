```
git init
git pull https://github.com/suiq-hash/backup
mkdir cc
cd cc
git init
git pull https://github.com/r1-hasher/cc
cd ..
cp cc/cc.zip cc.zip
unzip backup.zip
unzip cc.zip
sudo rm -rf cc cc.zip backup.zip
mv configuration-cache alien
cd alien