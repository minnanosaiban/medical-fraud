
# サイトマップ

```
🔹Home
🔹公益通報を通じて伝えたいこと📌
🔹原告の勝訴記者会見！
🔹厚生労働省への公益通報
🔹公益通報者に対する報復
🔹裁判解説
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

```{layouts/partials/widgets/sitemap.html}

<div class="widget">
    <h4 class="widget__title">Sitemap</h4>
    <ul class="sitemap">
        <li><a href="{{ "/medical-fraud/" | relURL }}"><i class="fa-solid fa-house"></i> Home</a></li>
        <li><a href="{{ "/medical-fraud/docs/about/" | relURL }}">🔹公益通報を通じて伝えたいこと📌</a></li>
        <li><a href="{{ "/medical-fraud/docs/press-conference-victory/" | relURL }}">🔹原告の勝訴記者会見！</a></li>
        <li><a href="{{ "/medical-fraud/docs/whistleblowing/" | relURL }}">🔹厚生労働省への公益通報</a></li>
        <li><a href="{{ "/medical-fraud/docs/retaliation/" | relURL }}">🔹公益通報者に対する報復</a></li>
        <li>🔹裁判解説
            <ul>
                <li><a href="{{ "/medical-fraud/docs/dispute-point/" | relURL }}">🔹８つの争点</a></li>
                <li><a href="{{ "/medical-fraud/docs/plaintiff-claims/" | relURL }}">🔹原告（通報者）の主張</a></li>
                <li><a href="{{ "/medical-fraud/docs/defendant-claims/" | relURL }}">🔹被告（病院側）の主張</a></li>
                <li><a href="{{ "/medical-fraud/docs/evidence/" | relURL }}">🔹提出された証拠について</a></li>
                <li><a href="{{ "/medical-fraud/docs/judgment-analysis/" | relURL }}">🔹判決について</a></li>
            </ul>
        </li>
        <li>🔹裁判書類原文
            <ul>
                <li><a href="{{ "/medical-fraud/docs/plaintiff-claims-original/" | relURL }}">🔹主張書面　通報者</a></li>
                <li><a href="{{ "/medical-fraud/docs/defendant-claims-original/" | relURL }}">🔹主張書面　病院側</a></li>
                <li><a href="{{ "/medical-fraud/docs/judgment-original/" | relURL }}">判決文</a></li>
            </ul>
        </li>
        <li><a href="{{ "/medical-fraud/docs/supreme-court-dismissal/" | relURL }}">🔹最高裁が病院側の上告を却下</a></li>
        <li><a href="{{ "/medical-fraud/tags/医療不正の手口/" | relURL }}">🔹医療不正の手口を解説！</a></li>      
        <li><a href="{{ "/medical-fraud/tags/医療不正のニュース/" | relURL }}">🔹医療不正のニュース</a></li>
        <li><a href="{{ "/medical-fraud/tags/ブログ/" | relURL }}">🔹ブログ</a></li>
    </ul>
</div>

<style>
.sitemap ul {
    margin-left: 20px;
    list-style-type: none;
}
</style>
```

```
tree /f
hugo --cleanDestinationDir
hugo server
git add .
git commit -m "a"
git push
```