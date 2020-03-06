# SuiCon International 2020
- SuiCon International 2020
  - https://www.suicon.com/

# 日本語訳共同編集シート
- https://docs.google.com/spreadsheets/d/13ki5tmhhLI394_B8JARvUUqhaQW9ugEC/edit#gid=333595223

# Mirror
- https://true-runes.github.io/suicon-international-2020/

# wget

```bash
$ wget --mirror --page-requisites --span-hosts --show-progress --no-parent --convert-links --adjust-extension --execute robots=off --verbose --output-file=wget_log.log --tries=2 --no-if-modified-since --random-wait --waitretry=5 --backup-converted --domain=suicon.com https://www.suicon.com/
```
