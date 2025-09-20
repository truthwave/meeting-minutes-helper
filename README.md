<p align="center">
<img width="1536" height="1024" alt="議事録、もう書かなくていい。" src="https://github.com/user-attachments/assets/dfa13c09-cd54-41fe-a5ec-f30d27129edd" />

</p>


# 議事録らくらく GPT

> 会議の要点を「3行」で即整理。Slack投稿も、ToDo抽出も、これひとつ。

---

## 🎯 概要

会議メモや議事録をもとに、「3行要約」「ToDo整理」「共有文」を一瞬で仕上げるGPTです。

---

## プロジェクト概要
[スライド資料はこちら](https://github.com/truthwave/meeting-minutes-helper/tree/main/%E8%B3%87%E6%96%99/%E8%AD%B0%E4%BA%8B%E9%8C%B2%E3%82%89%E3%81%8F%E3%82%89%E3%81%8FGPT)

[動画資料はこちら](https://youtu.be/BX_dgQVtI_g)

---

## 💡 特徴

- **3行要約／構造化要約／Slack共有文**の3形式に対応
- **ToDo項目**を担当者・期限付きで抽出
- 曖昧な発言は「要確認」と明示し、過剰な推測を防止
- ChatGPTを開いたまま、そのままコピペして使える設計

---

## 🔢 出力形式

| 番号 | 出力内容 |
|--|--|
| 1 | 3行要約（概要のみ） |
| 2 | 構造化要約（議題／決定事項／ToDo） |
| 3 | Slack共有用の自然な要約文 |

---

## 📸 **体験イメージ**
![デモ動画](https://github.com/TomoProgrammingDayori/meeting-minutes-helper/blob/main/%E8%B3%87%E6%96%99/%E3%83%87%E3%83%A2%E5%8B%95%E7%94%BB.gif)

![定例ミーティングの要点まとめ](https://github.com/TomoProgrammingDayori/meeting-minutes-helper/blob/main/%E8%B3%87%E6%96%99/%E3%82%B9%E3%82%AF%E3%83%AA%E3%83%BC%E3%83%B3%E3%82%B7%E3%83%A7%E3%83%83%E3%83%88/%E5%AE%9A%E4%BE%8B%E3%83%9F%E3%83%BC%E3%83%86%E3%82%A3%E3%83%B3%E3%82%B0%E3%81%AE%E8%A6%81%E7%82%B9%E3%81%BE%E3%81%A8%E3%82%81.jpeg)

![新規プロジェクトの要点まとめ](https://github.com/TomoProgrammingDayori/meeting-minutes-helper/blob/main/%E8%B3%87%E6%96%99/%E3%82%B9%E3%82%AF%E3%83%AA%E3%83%BC%E3%83%B3%E3%82%B7%E3%83%A7%E3%83%83%E3%83%88/%E6%96%B0%E8%A6%8F%E3%83%97%E3%83%AD%E3%82%B8%E3%82%A7%E3%82%AF%E3%83%88%E3%81%AE%E8%A6%81%E7%82%B9%E3%81%BE%E3%81%A8%E3%82%81.jpeg)

![議事録の概要例](https://github.com/TomoProgrammingDayori/meeting-minutes-helper/blob/main/%E8%B3%87%E6%96%99/%E3%82%B9%E3%82%AF%E3%83%AA%E3%83%BC%E3%83%B3%E3%82%B7%E3%83%A7%E3%83%83%E3%83%88/%E8%AD%B0%E4%BA%8B%E9%8C%B2%E3%81%AE%E8%A6%81%E7%B4%84%E4%BE%8B.jpeg)

---

## 🧠 入力例

```

## 形式：2

・A社との契約条件について再確認
・B機能の仕様を詰める
・リリース日を再設定 → 9/10予定

```

---

## 📄 出力例（構造化）

■ 議題  
- A社契約条件の再確認  
- 新機能Bの仕様検討

■ 決定事項  
- 契約金額は据え置きで確定  
- リリースは9月10日に決定

■ ToDo  
- [担当：佐藤] 契約書ドラフト修正 → 8/22まで  
- [担当：鈴木] B機能のプロトタイプ作成 → 8/25まで

---

## 📌 想定利用シーン

- SlackやNotionに会議要点だけ投稿したいとき  
- 議事録をまとめる時間がないとき  
- チームでToDoを素早く共有したいとき

---

## 🧾 制作背景

このGPTは、Microsoft認定「生成AIによる生産性の向上」講座の知識をもとに、  
実際の会議現場での「要約・共有・指示出し」の負担を減らすために開発しました。
「議事録を読み返す時間がない」「ToDoだけ見たい」—— そんな現場の声に応えました。

💡 導入前は、30分かけて書いていた議事録を、3分でSlack投稿できるようになります。

---

## 🛒 ココナラで販売中！

このプロジェクトは、現在ココナラにて有償版を販売しています。  
AIプロンプト設計・カスタマイズ・導入サポートをご希望の方は、以下よりご相談ください。

🎯 先着3名様限定｜初回販売キャンペーン中
<br>初めての方にも安心してご利用いただけるよう、レビューにご協力いただける方へ特別価格でご提供しています。

👉 [ココナラ販売ページはこちら](https://coconala.com/contents_market/pictures/cmfkjunz2046t8n0hwiupnd2e)

👉 [オプション販売ページはこちら](https://coconala.com/services/3875043)

---

## 🔗 関連リンク

- [Microsoft認定スキル × GPTs活用リポジトリ](https://github.com/TomoProgrammingDayori/ai-productivity-cert-practical-output)
- [社内FAQ即答アシスタント GPT](https://chatgpt.com/g/g-68a5cf5fc62c81919d198dfa6f0ef496-she-nei-faqji-da-asisutanto-gpt)

---

## 🧑‍💻 作者

**[Truth Wave ― 真理の波](https://github.com/truthwave)**  
AIツールやポートフォリオ開発に関する情報も発信中。

## お気軽にご連絡ください
[📩 ご相談・お見積もりはこちら](mailto:realmadrid71214591@gmail.com)

---

> 「議事録を“残す”だけじゃ意味がない。“伝える”が仕事だ。」
