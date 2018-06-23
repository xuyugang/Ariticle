```shell
#提交时转换为LF，检出时不转换
git config --global core.autocrlf input
#提交检出均不转换
git config --global core.autocrlf false

IDEA的设置File -> Settings -> Editor -> Code Style -> Line separator 选择：Unix
```