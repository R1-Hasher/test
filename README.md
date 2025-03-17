```
git init
git pull https://github.com/suiq-hash/backup
cd '~/'
mkdir .gradle
cd .gradle
mkdir caches
cd caches
mkdir fabric-loom
```
```
mkdir archive
cd archive
git init
git pull https://github.com/r1-hasher/cc
cd ..
unzip backup.zip
cd archive
unzip archive.zip
mv configuration-cache '/workspace/'
cd ..
sudo rm -rf cc archive
cd configuration-cahce
mv 1.20.4 '~/.gradle/caches/fabric-loom'
mv minecraftMaven '~/.gradle/caches/fabric-loom'
mv version_manifest.json '~/.gradle/caches/fabric-loom'
cd ..
cd alien
