# sh

```sh
# get file from remote
scp dctalbot@login.itd.umich.edu:./Downloads/some.pdf .
```

```sh
# deploy pwd to remote
rsync -r --delete ./. dctalbot@login.itd.umich.edu:./Public/html/
```
