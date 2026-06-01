### Usage guide

Run the app:
```bash
./gradlew run
```
Build:
```bash
./gradlew build
```
Clean:
```bash
./gradlew clean
```
Show all tasks:
```bash
./gradlew tasks
```

### How to copy a repository
```bash
mkdir foo; cd foo 
# move to a scratch dir

git clone --bare https://github.com/exampleuser/old-repository.git
# Make a bare clone of the repository

cd old-repository.git
git push --mirror https://github.com/exampleuser/new-repository.git
# Mirror-push to the new repository

cd ..
rm -rf old-repository.git  
# Remove our temporary local repository
```

### Reference
https://medium.com/ringcentral-developers/how-to-start-a-new-java-project-without-an-ide-2713614938d0

![image](https://myoctocat.com/assets/images/base-octocat.svg)


![image](https://github.com/huaius/java-gradle-template/blob/main/config/images/sample.png?raw=true)
