# 🐾 PetApp2

AIペットアプリ第2弾 — 犬・猫・うさぎのデモ版とテンプレート版をまとめた公式ページ。  
笑顔（顔認識）や声掛け（音声認識）に反応する AI ペットアプリの進化版です。

---

## 🔹 概要

**PetApp2** は、前作 DesktopPetApp の機能を拡張した AI ペットアプリです。  
ユーザーが飼っているペット（犬・猫・うさぎ）の画像や動画を登録し、  
デスクトップ上で表情や動作を再現できます。  

このリポジトリでは、**デモ版（動作確認用）** と **テンプレート版（カスタマイズ用）** をまとめて公開しています。

---

## 🔹 主な特徴

- **15種類の状態（n1～n3, p1〜p12）に対応**  
  ペットの表情や動作を細かく再現。通常・休憩・睡眠などの中立状態（n1〜n3）と、  
  遊び・喜び・お手・ごはんなどのポジティブ状態（p1〜p12）を切り替え可能。

- **AI画像/動画生成ガイド（Gemini / Copilot / Pika）を搭載**  
  ペット素材が不足している場合でも、外部AIツールで簡単に補完できるよう、  
  生成手順や利用方法をガイドします。

- **ペットのプロフィール（名前・種類・毛色など）を元に、15種類の状態に応じたAI生成プロンプト（日本語・英語）を自動生成**  
  各状態に最適化されたプロンプトを作成し、AI画像/動画生成を強力に支援します。

---

## 🔹 動作環境

- OS：Windows 10 / Windows 11  
- GPU：外部GPU不要（CPUで動作します）  
- Python：3.10〜3.12（Portable版を同梱）  
- インストール：不要（ZIP展開のみ）

---

## 🔹 ファイル構成

| ファイル名 | 内容 |
|-------------|------|
| `index.html` | PetApp2 の公式紹介ページ |
| `hero.png` | ペットアプリのロゴ画像 |
| `README.md` | この説明ファイル |

---

## 🔹 関連リンク

- **PetApp2 Portable（現行版）**  
  https://github.com/usakowhity/PetApp2-portable

- **DesktopPetApp（前作）**  
  https://usakowhity.github.io/DesktopPetApp/

- **PetApp3 – Taro Edition（次期英語版）**  
  https://github.com/usakowhity/PetApp3

- **公式サイト（PetAppシリーズ）**  
  https://usakowhity.github.io/

---

## 📄 License

MIT License  
Copyright (c) 2026 usakowhity

