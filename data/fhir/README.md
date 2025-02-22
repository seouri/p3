```
# install java
brew install openjdk
sudo ln -sfn /opt/homebrew/opt/openjdk/libexec/openjdk.jdk /Library/Java/JavaVirtualMachines/openjdk.jdk

# download https://github.com/synthetichealth/synthea/releases/download/master-branch-latest/synthea-with-dependencies.jar
# generate 100 patient data from age 0 to 18 in Massachusetts
java -jar synthea-with-dependencies.jar Massachusetts -a 0-18 -p 100
```
