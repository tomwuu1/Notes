使用Git遇到的错误

# 1 error: src refspec master does not match any.

 [解决链接](https://stackoverflow.com/questions/4181861/message-src-refspec-master-does-not-match-any-when-pushing-commits-in-git)

## 解决的方法：

把` git push origin master` 改成` git push origin HEAD:main`



## 报错原因

Todo