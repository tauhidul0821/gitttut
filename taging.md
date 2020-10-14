
### git tag 

- for create git tag // light wait tag 
```
git tag v1.0
```
- for create anotated tag 
```
git tag -a v1.1 -m 'tag for relese  ver 1.1'
```
- for push a particular ta 
```
git push origin v1.0
``` 
- for push all tag
```
git push --tags
```

- for delete tag in local
```
git tag -d v1.0
```
- for delete tag in origin 
```
git push origin -d v1.0
or 
git push origin --delete v1.1
```
- for identify a tag with git commit id 
```
git tag v1.3 5f83462
and push 
git push --tags
```

