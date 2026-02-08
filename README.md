# Tactical Arsenal

game page
https://lukaglyph.github.io/Tactical-Arsenal/

[![GitHub Pages](https://img.shields.io/badge/Status-Live-brightgreen.svg)](https://github.com/Lukaglyph/Tactical-Arsenal)
[![Language](https://img.shields.io/badge/Language-HTML/JS-blue.svg)](#)

# ♟️ TACTICAL ARSENAL (タクティカル・アーセナル)

![Version](https://img.shields.io/badge/version-2.1.0-cyan)
![License](https://img.shields.io/badge/license-MIT-blue)
![Platform](https://img.shields.io/badge/platform-Web-pink)

将棋の伝統的な戦略性と、サイバーパンクな世界観を融合させたタクティカル・ボードゲームです。
限られたコストの中でユニットをカスタマイズし、将棋の思考アルゴリズムをベースとした強化型AIを撃破せよ。

## 🚀 特徴

- **カスタム兵装（アーセナル）システム**: 全8種類のユニットに対し、シールド、EMP、ブースターなどの特殊兵装をコスト制限内で自由に装備可能。
- **戦略強化型AI (Strategic AI v2.0)**: 将棋の評価関数をベースに、「駒の価値」「成りやすさ」「盤面の支配度」を計算して最適な一手を選択する思考エンジンを搭載。
- **プログレッシブ・デザイン**: HTML/JS/CSS（Tailwind CSS）のみで構築され、レスポンシブにも完全対応。サイバーパンクなエフェクトが盤面を彩ります。
- **将棋準拠のルール**: 持ち駒、成り（プロモーション）、二歩（歩兵の制約）など、将棋の奥深さをそのままゲーム性に昇華。

## 🎮 遊び方

### 1. 兵装カスタマイズ
ゲーム開始前に、合計コスト **12** 以内で自軍をカスタマイズします。
- **シールド (Cost 1)**: 1度だけ撃破を無効化。
- **EMP (Cost 2)**: 着地時に周囲を麻痺させ、1ターン行動不能にする。
- **ブースター (Cost 3)**: 移動後に再度行動可能（特定の駒を除く）。
- **グラビティ (Cost 3)**: 着地時に周囲の駒を押し出す。

### 2. 基本ルール
- **勝利条件**: 相手の「コア (K)」をキャプチャする。
- **移動**: 駒ごとに異なる移動特性を持ち、敵陣（奥の3段）に入ると「成り」が可能です。
- **持ち駒**: キャプチャした駒は自分のターンに空いたマスへ配置できます。

## 🛠 技術スタック

- **Frontend**: HTML5 / CSS3 / JavaScript (Vanilla JS)
- **Styling**: [Tailwind CSS](https://tailwindcss.com/)
- **Icons**: [Lucide Icons](https://lucide.dev/)
- **Font**: Share Tech Mono / Noto Sans JP

## 🧠 AI アルゴリズムについて

本プロジェクトのAIは、以下の要素を組み合わせた評価関数を用いています：
1. **マテリアル評価**: 駒の種類に応じた静的なスコア（バスター>スナイパー>...）。
2. **位置評価**: 駒の前進度合いや中央への近
## 📄 ライセンス

このプロジェクトは MIT ライセンスの下で公開されています。

---
Developed by [Lukaglyph]
