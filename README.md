# 
```
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
```

# git master branch 

```
master
[core]
	repositoryformatversion = 0
	filemode = false
	bare = false
	logallrefupdates = true
	symlinks = false
	ignorecase = true
[user]
	name = ChanYeeLi
	email = lichenyiwin@outlook.com
[remote "origin"]
	url = https://github.com/lichenyigit/test.git
	fetch = +refs/heads/*:refs/remotes/origin/*
[branch "master"]
	remote = origin
	merge = refs/heads/master
  
```

```
main
[core]
	repositoryformatversion = 0
	filemode = false
	bare = false
	logallrefupdates = true
	symlinks = false
	ignorecase = true
[user]
	name = ChanYeeLi
	email = lichenyiwin@outlook.com
[remote "origin"]
	url = https://github.com/lichenyigit/test.git
	fetch = +refs/heads/*:refs/remotes/origin/*
[branch "main"]
	remote = origin
	merge = refs/heads/main
  
```

  
# 本地创建远程仓库并推送
```
git init
git config --global user.email "lichenyi@binttech.com"
git config --global user.name "lichenyi"
git remote add origin http://172.22.65.44/lichenyi/10-7course.git
git add .
git commit -m "Initial commit"
git push -u origin master
```
  
  
# unity ignore
```
[Ll]ibrary/
[Tt]emp/
[Oo]bj/
[Bb]uild/
[Bb]uilds/
[Ll]ogs/
Assets/Plugins
Assets/Firebase
Assets/Editor Default Resources
Assets/ExternalDependencyManager
Assets/Parse
Assets/Photon
Assets/FacebookSDK
Assets/Plugins
[Ee]xe/
[Hh]tml/
Assets/GoogleMobileAds
Assets/PlayServicesResolver
JSON/
*.zip
.idea
.iml
*.iml
*.log
*.apk
*.aab
*.sln
*.csproj
.DS_Store
.vs
.vsconfig
```

# unity ignore1
```
[Ll]ibrary/
[Tt]emp/
[Oo]bj/
[Bb]uild/
[Bb]uilds/
[Ll]ogs/
[Ee]xe/
[Hh]tml/
*.zip
.idea
.iml
*.iml
*.log
*.apk
*.aab
*.sln
*.csproj
.DS_Store
.vs
.vsconfig
```

# java ignore
```
# Compiled class file
*.class

# Log file
*.log

# BlueJ files
*.ctxt

# Mobile Tools for Java (J2ME)
.mtj.tmp/

# Package Files #
*.jar
*.war
*.nar
*.ear
*.zip
*.tar.gz
*.rar

# virtual machine crash logs, see http://www.java.com/en/download/help/error_hotspot.xml
hs_err_pid*

.idea
target
```
