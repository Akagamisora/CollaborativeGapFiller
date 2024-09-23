# CollaborativeGapFiller（仮）

このプロジェクトは、GitHubを用いた教科書の行間を共同で埋めていくものです。

どんな嬉しいことがあるの？

- 難しい教科書の行間をみんなで埋めることができる
- 貢献度が可視化される
- GitHubの使い方を知れる

現在は、JJサクライの「現代の量子力学」のプロジェクトを作成していますが、新たに教科書を追加することも可能です。

## いくつかの注意？

マークダウンファイルの前に次のようなコードを追加してください。
```
<script type="text/javascript">
  window.MathJax = {
    tex: {
      inlineMath: [['$', '$'], ['\\(', '\\)']],
      displayMath: [['$$', '$$'], ['\\[', '\\]']]
    },
    options: {
      processEscapes: true
    }
  };
</script>
<script async src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/3.2.2/es5/tex-mml-chtml.min.js"></script>
```
