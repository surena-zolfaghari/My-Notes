[[Git]]
#git
# HOW TO GIT TWO FOLDER TOGETHER?
I want to backup folder that named surena
```git
git init
git add .
git satus 
git commit -m "2 March"
```


Now go to folder that you want to backup this file (I named backup)
```git
git init
git remote add origin < path of surena >
```


Now  go to surena
```git
git remote add origin < path of backup >
```

Then go to backup

```git
git pull origin master
```


Ref:

[how to backup on external drive with git](https://www.youtube.com/watch?v=vHzDVPWwIww)


