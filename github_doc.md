******First install OS: Ubuntu 16.04 LTS

1.install  Git

2.check the git version to confirm the installation

3.configure Git for the first time

```
$ git config --global user.name "pgopal1166"
$ git config --global user.email pgopal1166@gmail.com
```

Locally:
in django root:
```
  $ git init
  $ git add .
  $ git commit -m "write simple message what u've done"
```

To push code to GIthub:
```
$ git remote add origin https://github.com/gopal1166/ram-django.git
$ git push -u origin master
```
