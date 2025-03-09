
# サイトマップ

```
🔹Home
🔹公益通報を通じて伝えたいこと📌
🔹原告の勝訴記者会見！
🔹裁判解説
　　🔹厚生労働省への公益通報
　　🔹公益通報者に対する報復
　　🔹８つの争点
　　🔹原告（通報者）の主張
　　🔹被告（病院側）の主張
　　🔹提出された証拠について
　　🔹判決について
🔹裁判書類原文
　　🔹主張書面　通報者
　　🔹主張書面　病院側
　　🔹判決文
🔹最高裁が病院側の上告を却下
🔹医療不正の手口を解説！
🔹医療不正のニュース
🔹ブログ
```

# フォルダー構成

```
content/
├── _index.md                         # Home（トップページ）
│
├── medical-fraud/
│   └── index.md                      # 医療不正の手口を解説！
├── news/
│   └── index.md                      # 医療不正のニュース
├── blog/
│   └── index.md                      # ブログ
└── docs/
    ├── about.md                      # 公益通報を通じて伝えたいこと📌    
    ├── press-conference-victory.md   # 原告の勝訴記者会見
    ├── whistleblowing.md             # 厚生労働省への公益通報
    ├── retaliation.md                # 公益通報者に対する報復
    ├── dispute-point.md              # ８つの争点
    ├── plaintiff-claims.md           # 原告（通報者）の主張
    ├── defendant-claims.md           # 被告（病院側）の主張
    ├── evidence.md                   # 提出された証拠について
    ├── judgment-analysis.md          # 判決について
    ├── plaintiff-claims-original.md  # 主張書面　通報者
    ├── defendant-claims-original.md  # 主張書面　病院側
    ├── judgment-original.md          # 判決文
    └── supreme-court-dismissal.md    # 最高裁が病院側の上告を却下
```

```
tree /f
hugo --cleanDestinationDir
hugo server
git add .
git commit -m "a"
git push
```