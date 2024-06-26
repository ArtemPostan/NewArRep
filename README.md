$ ssh-keygen -t rsa -b 4096 -C "arpost89@gmail.com"
$ cat .ssh/id_rsa.pub
$ git clone https://github.com/ArtemPostan/NewArRep.git
$ cd NewArRep
$ git checkout -b branch1
$ echo "Some new words" > File.txt
$ git add File.txt
$ git commit -m "Added file"
$ git push origin branch1
$ git checkout main
$ git pull origin main
$ git checkout -b branch2
$ echo "Erors comes here" > File.txt
$ git add File.txt
$ git commit -m "Changes"
$ git push origin branch2
#Далее делал пулреквесты через графический интерфейс гитхаба
