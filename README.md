# jiraUtils

## 夢
- ブランチ名がチケット番号のみの時、 `git branch` でチケット名が取得できるようにしたい

```
% git branch
  develop
  feature/11829
  feature/12057
* feature/12062
  fix/11890
```

↓


```
% git branch
  develop
  feature/11829 (Add hogehoge screen)
  feature/12057 (Create fugafuga api)
* feature/12062 (Create piyopiyo transition)
  fix/11890 (Fix toto crash)
```
