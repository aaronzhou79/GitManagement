## 从远程仓库中克隆代码到本地
![alt text](images/gitClone.png)

# 创建feature分支

```bash
git checkout develop
git checkout -b feature-1111
```

# 提交代码到本地仓库
```bash
git add .
git commit -m "feature-1111"
```


# 完成一个feature分支
```bash
git checkout develop
git merge feature-10
```