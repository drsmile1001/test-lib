# github ci 測試專案
本專案示範master被推送後，進行build-pack-publish到github packages

## 使用lib
 [Password 由github生成](https://help.github.com/en/github/authenticating-to-github/creating-a-personal-access-token-for-the-command-line)
```shell
nuget sources Add -Name "drsmile1001" /
-Source "https://nuget.pkg.github.com/drsmile1001/index.json" /
-UserName drsmile1001 -Password *************
```