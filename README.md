Describe flow how work with this repo and branches

# Clone repo
via http
```
git clone https://github.com/ViktorDevOpsCourse/new-project.git
```

via ssh 
```
git clone git@github.com:bakercp/PacketSerial.git
```


# Work flow in a project

1. Change branch on development
```
git checkout development
```
2. Do some feature and commit it
```
git add file.name
git status
git commit -m "commit text"
```
3. Push changes on reviews
```
git push origin development
```
4. Merge it inot master(git should be main branch)
```
git merge develoment
```