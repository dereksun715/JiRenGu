# The differences and function about the **git reset and git revert**

> This article will explain the differences and functions about the git reset which are the hard option, soft option and git revert.

##The three areas of git

1. Working directory
2. Stage index
3. History

![jinshu](https://upload-images.jianshu.io/upload_images/8048507-9ea56a58f75ebc00.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/617/format/webp)

## git reset -- hard

This goes the whole nine yards. It will first move HEAD and update the index with the contents of the commit HEAD is now pointing at. Then it will update the working directory with the contents of te index, thereby possibly destroying content you changed in the working directory




## git reset -- soft

Soft HEAD means it will return all of things to the last version, and after submited it will change and move to **stage index**


## git revert

Git revert is one of the revocation of order, and the different between reset is forward pointer. Git revert is used to creat a commit to coverage the ole one. 


