# latex_miino_thesis

- 卒論・修論用 LaTeX style

## 固有コマンド

```tex
\doctype{2023年度 卒業論文}  % Document type：表紙に出力
\supervisor{
    指導教員 & 美井野 優
}  % 指導者：tabular{ll} 環境を利用，改行可
\organization{◯◯大学 ◯◯学部\\ ◯◯コース}  % 所属：改行可
```

## Overleaf
設定の参考：[Qiita | Overleafを使った日本語論文の作成](https://qiita.com/fujino-fpu/items/d92d185da730e25743cb) 

- latexmkrc の記載内容

```
$latex = 'platex';
$bibtex = 'pbibtex';
$dvipdf = 'dvipdfmx %O -o %D %S';
$makeindex = 'mendex -U %O -o %D %S';
$pdf_mode = 3; 
```

- Settings

<img width="324" alt="Screenshot 2025-01-06 at 1 49 07 PM" src="https://github.com/user-attachments/assets/462aedfd-ec94-4cde-8406-b02806fcc4f6" />
