### for remove Merge branch 'main' of https://github.com
```sh
$ git config --global pull.rebase true
link: https://stackoverflow.com/questions/13846300/how-to-make-git-pull-use-rebase-by-default-for-all-my-repositories
```


### interactive rebase 
- how to change commit massage 

```bash
git log --oneline
```
- now you want to change number 3 commit massage 

```bash
git rebase -i HEAD~3
```

- replace pick to reword

- close 
- now open another window

- no change commit massage 

- we successfully change commit massage 
- how to combine two commit into one commit 

- git rebase -i HEAD~4
- open a new window

- now replace `pick` to `squash`

- save and close 
- open a new window 

- now commit a new commit and close 

### cherry picking






### taging




### reflog




### submodules




### search & find




### 
### 



![IMG_4841](https://user-images.githubusercontent.com/58136550/143461142-042e332b-9fd5-48a0-8e76-ee357678ae14.JPG)
![IMG_4840](https://user-images.githubusercontent.com/58136550/143461162-42eff790-cb6d-44a8-b96e-0bbfda0277c5.JPG)
![IMG_4839](https://user-images.githubusercontent.com/58136550/143461174-49373b61-6207-46ca-8072-57d78dc5d197.JPG)
![IMG_4838](https://user-images.githubusercontent.com/58136550/143461182-34c522f2-1a50-4346-be77-73fbd857b6f0.JPG)



# that is quick bugfix
# that is quick bugfix 2