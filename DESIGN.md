---
name: IGUAZU
description: 株式会社イグアスのデザインシステム — IBMパートナーのIT企業として、信頼性・専門性・先進性を体現するビジュアルアイデンティティ
version: alpha
logo:
  primary: "./assets/logo.svg"
  url: "https://raw.githubusercontent.com/matsuo-iguazu/iguazu-design/main/assets/logo.svg"
  usage:
    backgrounds: ["#FFFFFF", "#0077C8"]
    min-width: "120px"
    clear-space: "ロゴ高さ×1の余白"
    dont: ["変形", "回転", "色変更", "背景色なし適用"]
colors:
  primary: "#0077C8"
  primary-dark: "#005A96"
  primary-light: "#E8F4FC"
  text-primary: "#1A1A1A"
  text-secondary: "#555555"
  text-muted: "#888888"
  surface: "#FFFFFF"
  surface-gray: "#F5F5F5"
  border: "#DDDDDD"
  accent: "#0077C8"
  error: "#D32F2F"
typography:
  display:
    fontFamily: "Noto Sans JP, Hiragino Kaku Gothic ProN, Yu Gothic, sans-serif"
    fontSize: "2.5rem"
    fontWeight: "700"
    lineHeight: "1.3"
    letterSpacing: "0.02em"
  h1:
    fontFamily: "Noto Sans JP, Hiragino Kaku Gothic ProN, Yu Gothic, sans-serif"
    fontSize: "2rem"
    fontWeight: "700"
    lineHeight: "1.4"
    letterSpacing: "0.02em"
  h2:
    fontFamily: "Noto Sans JP, Hiragino Kaku Gothic ProN, Yu Gothic, sans-serif"
    fontSize: "1.5rem"
    fontWeight: "700"
    lineHeight: "1.5"
    letterSpacing: "0.02em"
  h3:
    fontFamily: "Noto Sans JP, Hiragino Kaku Gothic ProN, Yu Gothic, sans-serif"
    fontSize: "1.25rem"
    fontWeight: "600"
    lineHeight: "1.6"
    letterSpacing: "0.02em"
  body-lg:
    fontFamily: "Noto Sans JP, Hiragino Kaku Gothic ProN, Yu Gothic, sans-serif"
    fontSize: "1rem"
    fontWeight: "400"
    lineHeight: "1.8"
    letterSpacing: "0.04em"
  body-md:
    fontFamily: "Noto Sans JP, Hiragino Kaku Gothic ProN, Yu Gothic, sans-serif"
    fontSize: "0.9375rem"
    fontWeight: "400"
    lineHeight: "1.8"
    letterSpacing: "0.04em"
  body-sm:
    fontFamily: "Noto Sans JP, Hiragino Kaku Gothic ProN, Yu Gothic, sans-serif"
    fontSize: "0.875rem"
    fontWeight: "400"
    lineHeight: "1.75"
    letterSpacing: "0.04em"
  caption:
    fontFamily: "Noto Sans JP, Hiragino Kaku Gothic ProN, Yu Gothic, sans-serif"
    fontSize: "0.75rem"
    fontWeight: "400"
    lineHeight: "1.7"
    letterSpacing: "0.04em"
  label:
    fontFamily: "Noto Sans JP, Hiragino Kaku Gothic ProN, Yu Gothic, sans-serif"
    fontSize: "0.8125rem"
    fontWeight: "600"
    lineHeight: "1.5"
    letterSpacing: "0.08em"
  english-heading:
    fontFamily: "Helvetica Neue, Arial, sans-serif"
    fontSize: "0.875rem"
    fontWeight: "500"
    lineHeight: "1.4"
    letterSpacing: "0.12em"
rounded:
  sm: "2px"
  md: "4px"
  lg: "8px"
  pill: "100px"
spacing:
  xs: "4px"
  sm: "8px"
  md: "16px"
  lg: "24px"
  xl: "40px"
  xxl: "64px"
  section: "80px"
components:
  button-primary:
    background: "{colors.primary}"
    color: "#FFFFFF"
    borderRadius: "{rounded.md}"
    padding: "12px 32px"
    fontSize: "0.9375rem"
    fontWeight: "600"
    letterSpacing: "0.06em"
  button-secondary:
    background: "transparent"
    color: "{colors.primary}"
    border: "1px solid {colors.primary}"
    borderRadius: "{rounded.md}"
    padding: "11px 31px"
  nav:
    background: "#FFFFFF"
    borderBottom: "1px solid {colors.border}"
    height: "60px"
  card:
    background: "{colors.surface}"
    border: "1px solid {colors.border}"
    borderRadius: "{rounded.lg}"
    padding: "{spacing.lg}"
  section-heading:
    borderLeft: "4px solid {colors.primary}"
    paddingLeft: "{spacing.md}"
---

## Overview

「新たな価値創造にチャレンジ」というキャッチコピーが示す通り、イグアスのビジュアルアイデンティティは **信頼性・専門性・前向きな挑戦心** の3要素で構成される。

IBMのVAD（Value Added Distributor）として長年のB2B実績を持つ企業として、デザインは「頼れるプロフェッショナル」の印象を第一に与える。過度な装飾を避け、情報の明確さと誠実さを優先。ただし無機質になりすぎず、「チャレンジ」を体現する躍動感も忘れない。

ターゲットは企業のIT担当者・経営者・パートナー企業。専門知識を持つ受け手に対して、複雑な情報を整理して届けることが求められる。

## Colors

- **Primary (#0077C8):** イグアスブルー — 信頼・テクノロジー・誠実さを象徴。ボタン・リンク・アクセントの主役。IBMブルーと調和する色調。
- **Primary Dark (#005A96):** ホバー・アクティブ状態、強調見出しに使用。
- **Primary Light (#E8F4FC):** カード背景・バッジ・ハイライト。目立たせすぎない情報強調に。
- **Text Primary (#1A1A1A):** 本文・見出しの基本色。純黒を避けることで柔らかさを保つ。
- **Text Secondary (#555555):** サブコピー・補足テキスト。
- **Text Muted (#888888):** 日付・キャプション・プレースホルダー。
- **Surface (#FFFFFF):** ページ基本背景。清潔感・信頼感の土台。
- **Surface Gray (#F5F5F5):** セクション区切り背景。コンテンツブロックの区別に。
- **Border (#DDDDDD):** 罫線・カード境界。控えめな区切り。
- **Error (#D32F2F):** エラー・警告のみ。アクセントとして使わない。

## Typography

### 和文フォント

- **第一候補:** Noto Sans JP — Googleフォント。可読性・Webパフォーマンスのバランスが良く、B2B資料にも対応。
- **第二候補:** Hiragino Kaku Gothic ProN — macOS/iOSの標準日本語ゴシック。
- **第三候補:** Yu Gothic — Windows標準の游ゴシック。

### 欧文フォント

- **見出し・ラベル:** Helvetica Neue / Arial — "IGUAZU" ロゴタイプと調和するサンセリフ。
- **数字・英数字:** 同上。和文フォントに混植する際も自然に馴染む。

### font-family指定（フォールバック込み）

```css
font-family: "Noto Sans JP", "Hiragino Kaku Gothic ProN", "Yu Gothic", "YuGothic", sans-serif;
```

### 文字サイズ・ウェイト階層

| 用途 | サイズ | ウェイト | 用途例 |
|------|--------|----------|--------|
| display | 2.5rem | 700 | ヒーローキャッチコピー |
| h1 | 2rem | 700 | ページタイトル |
| h2 | 1.5rem | 700 | セクション見出し |
| h3 | 1.25rem | 600 | カード見出し・小見出し |
| body-lg | 1rem | 400 | 標準本文 |
| body-md | 0.9375rem | 400 | リスト・説明文 |
| caption | 0.75rem | 400 | 日付・注記 |
| label | 0.8125rem | 600 | ボタン・タグ・ラベル |
| english-heading | 0.875rem | 500 | "Business & Products" などの英語サブタイトル |

### 行間・字間

- **本文:** line-height 1.8、letter-spacing 0.04em
- **見出し:** line-height 1.3〜1.5、letter-spacing 0.02em
- **英語ラベル・キャプション:** letter-spacing 0.08〜0.12em（英語は広めに）

### 禁則処理

```css
word-break: keep-all;
overflow-wrap: break-word;
line-break: strict;
```

句読点（。、）・閉じ括弧（）」』）の行頭禁止、開き括弧の行末禁止を徹底する。

### OpenType機能

```css
font-feature-settings: "palt" 1, "kern" 1;
```

和欧混植時の字間調整（palt）とカーニング（kern）を有効化。特に見出しで効果的。

## Layout

- **最大幅:** 1200px（コンテンツ幅）、左右padding 24px
- **グリッド:** 12カラム、gap 24px
- **セクション余白:** 上下 80px（PC）、48px（モバイル）
- **カード:** 3カラムまたは2カラムグリッドが基本

レイアウトは左揃えを基本とし、整然とした情報配置を優先。非対称や装飾的な崩しは使わない。セクション間の区切りは背景色の切り替え（白↔グレー）で行い、罫線過多を避ける。

## Components

### ボタン

- **プライマリ:** #0077C8地、白文字、角丸4px、padding 12px 32px。ホバーで#005A96に暗く。
- **セカンダリ:** 白地、#0077C8のボーダー+テキスト。
- **テキストリンク:** #0077C8、下線なし、ホバーで下線表示。
- 角丸は控えめ（4px）。ピル型は「お問い合わせ」CTAなど限定的に使用。

### ナビゲーション

- 白背景、下境界線1px (#DDDDDD)
- ロゴ左、メニュー右
- アクティブ項目はプライマリブルーのテキスト + 下線アクセント
- ドロップダウンは白背景、ボックスシャドウ控えめ

### カード・リスト

- 白背景 + ボーダー1px (#DDDDDD) + 角丸8px
- セクション見出しには左ボーダー4px (#0077C8) を添えてアクセント
- ニュース一覧は日付（グレー） + カテゴリタグ + タイトルの3要素構成

### タグ・バッジ

- カテゴリタグ：Primary Light (#E8F4FC) 地、Primary (#0077C8) テキスト、角丸2px
- 「プレスリリース」「お知らせ」など種別の視覚分類に使用

## Depth & Elevation

影は最小限。フラットデザインを基本とし、カードの浮き上がりは `box-shadow: 0 2px 8px rgba(0,0,0,0.08)` 程度に留める。

ホバー時のインタラクションはトランジション（0.2s ease）で表現。大きな動きよりも色の変化と下線表示で反応を示す。

## Do's and Don'ts

### Do
- 見出しの前に英語サブタイトル（例: "Business & Products"）を小さく添えてリズムを作る
- 重要な情報ほど上位に配置。スクロールを促す仕掛けより、最初の画面での情報完結度を高める
- 写真・動画は全幅または大きく使い、テクノロジーの力強さを表現する
- 英数字（IBM、DX、AI など）は欧文フォントで自然に混植する

### Don't
- グラデーション背景の多用（シンプルな単色背景を優先）
- 明朝体の使用（信頼性より文学的印象になりすぎる）
- 過剰なアニメーション（B2Bユーザーの集中を削ぐ）
- カラフルすぎる配色（ブルー一色を基調に締める）
- 小さすぎる本文（最小14px、推奨15px以上）

## Responsive Behavior

- **PC (1024px〜):** 3カラムカード、横並びナビ、全幅ヒーロー
- **タブレット (768px〜1023px):** 2カラムカード、ハンバーガーメニュー検討
- **モバイル (〜767px):** 1カラム、セクション余白48px、フォント1段階縮小（display→h1相当）

日本語テキストは横幅が狭まると折り返しが増えやすいため、モバイルでは `font-size: 0.9rem` へ微調整してリズムを保つ。

## Japanese Typography Extension

### 混植（和欧混在）ルール

```css
/* 英数字は欧文フォントで自然にレンダリングされるよう、和文フォントを先頭に */
font-family: "Noto Sans JP", "Helvetica Neue", Arial, sans-serif;
```

"IBM"、"VAD"、"DX"、"AI"、"Cloud" などの英略語・英単語は、和文フォントの中でも欧文グリフが自動適用されるため追加指定不要。ただし見出しで強調したい場合は `<span lang="en">` でマークアップしてフォントを明示的に切り替える。

### PowerPoint・社内資料への応用

DESIGN.md の内容を資料作成に転用する場合の対応表：

| Web (CSS) | PowerPoint/資料 |
|-----------|----------------|
| Noto Sans JP | 游ゴシック Medium（Windows）/ ヒラギノ角ゴ W3（Mac） |
| #0077C8 | RGB(0, 119, 200) |
| #1A1A1A | RGB(26, 26, 26)（ほぼ黒） |
| #F5F5F5 | RGB(245, 245, 245) |
| line-height 1.8 | 行間: 固定 → 28pt（16pt本文の場合） |
| letter-spacing 0.04em | 文字間隔: 0.5pt（目安） |
| border-left 4px primary | スライド内の見出し装飾として左端に青い縦線図形 |

### Agent Prompt Guide

AIエージェントへの指示例（Claude Code、Cursor等）:

```
このプロジェクトではIGUAZU社のDESIGN.mdに従ってUIを生成してください。
- メインカラーは #0077C8（イグアスブルー）を使用
- 日本語フォントは Noto Sans JP を第一候補とし、line-height 1.8、letter-spacing 0.04em を本文に適用
- 禁則処理（word-break: keep-all）を必ず有効化
- 装飾は控えめに。グラデーション・過剰なアニメーションは使用禁止
- B2B向けの信頼感を最優先。派手さより整然さを選ぶ
```
