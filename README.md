# メモ

## （高度な話題） article要素を含むセクション関連についてより深く学ぶために、MDNの記事も参考にしてください。
- https://developer.mozilla.org/ja/docs/Web/HTML/Element/article
- https://developer.mozilla.org/ja/docs/orphaned/Web/Guide/HTML/Using_HTML_sections_and_outlines#html5_%E3%81%AE%E5%8C%BA%E5%88%86%E5%8C%96%E8%A6%81%E7%B4%A0
（難しい内容ですが、「こんな話題があるんだな」という感じで一通り目を通してみてください。）

## （高度な話題） この例の場合には、article の代わりにsection でもよい

この昇段試験では article 要素を使用せよという指示がありますが、本例のようにフッター、ヘッダー、ナビゲーション、およびサイドバーを除いたものがarticle である場合、それ自身が単一の組成物であることは自明なので、わざわざarticle にしなくてもよい（しても構わないが、冗長である）という仕様があります。
したがって、本例ではarticleの変わりにsectionを使用してもOKです（同じ意味になります）。
HTMLの仕様書より：
https://momdo.github.io/html/sections.html#the-article-element
> ページの主要コンテンツ（すなわち、フッター、ヘッダー、ナビゲーションブロック、およびサイドバーを除くもの）がすべての1つの自己完結型の組成物である場合、そのコンテンツはarticleでマークしてもよいが、その場合に技術的に冗長である（ページが単一の組成物であることは自明であるので、そのまま単一の文書である）。

