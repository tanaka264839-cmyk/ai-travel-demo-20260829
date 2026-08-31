# AI ツバサ・トラベル — 立体世界デモ

社長1人＋AI従業員3人の小規模旅行会社が、朝から夜まで自律的に動く様子を単一HTMLで可視化したデモ。
「参考画像3枚（静止画）」から「単一HTMLで動く立体世界」への進化の推移を V1〜V4 で並存させている。

## 公開URL

有効化後、以下でアクセス可：

- **入口（V1〜V5 まとめ）**: https://tanaka264839-cmyk.github.io/ai-travel-demo-20260829/
- V1 · 抽象トークン: https://tanaka264839-cmyk.github.io/ai-travel-demo-20260829/20260829_ai_travel_company_demo_v1.html
- V2 · 人型SVG＋会話: https://tanaka264839-cmyk.github.io/ai-travel-demo-20260829/20260829_ai_travel_company_demo_v2.html
- V3 · 時間軸×ズーム×フロー弧線: https://tanaka264839-cmyk.github.io/ai-travel-demo-20260829/20260829_ai_travel_company_demo_v3.html
- V4 · フレーム破壊: https://tanaka264839-cmyk.github.io/ai-travel-demo-20260829/20260829_ai_travel_company_demo_v4.html
- **V5 · AI社長シミュ・1日モード（軽ゲーム／現行）**: https://tanaka264839-cmyk.github.io/ai-travel-demo-20260829/20260829_ai_travel_company_demo.html

## バージョン別の狙い

| Ver | 一手 | 到達点 |
|-----|-----|-------|
| V1  | 単一HTMLでアイソメ床とKPIバーを立てる | 抽象トークン／会話なし |
| V2  | 人型SVG＋夜景背景＋9会話シナリオ同時投入 | 人間らしさ＋世界感＋会話が生まれる |
| V3  | 時間軸ドラマ＋カメラズーム＋タスクフロー弧線 | 8→21時の1日ドラマ／部屋別の立体接写 |
| V4  | フレーム概念を解体、UIを世界内オブジェクト化 | KPIは光柱、時計/天気/タブは空中AR文字 |
| V5  | 訪問者が社長として1日を操作する軽ゲーム化（7決断→称号スコア） | 見るデモから遊べるデモへ／プレイ時間 約1〜2分 |

## 生成

Claude Code によるゴール達成ループ（復唱→現在地→差分→原因→一手→実行物→戻し→書き戻し→ゴール判定）で4周分の反復を経て構築。
