---
title: "ZIGAL: Restoration of a 1980s PC Game as a Technical and Educational Archive"
date: 2025-12-25
categories:
  - RetroComputing
  - Research
tags:  
  - PC-8801
  - 8bit
  - GameRestoration
  - TechnicalHistory
  - Reproducibility
  - Emulator
  - BASIC
  - MachineLanguage

---
**ZIGAL: 1980年代PCゲームの復刻と技術史アーカイブ**

Game Video  
<a href="https://raw.githubusercontent.com/acsdsgn/zigal/main/docs/Video/zigal_play.mp4">
  <img src="https://raw.githubusercontent.com/acsdsgn/zigal/main/docs/screenshots/zigal_screenshot_1.png" width="400">
</a>
---

# 【日本語版】  

## 概要
[ZIGAL](https://github.com/acsdsgn/zigal#日本語版) は、1980年代に私が PC-8801 向けに制作したオリジナルアクションゲームを、現代の技術を用いて復刻・再資料化したプロジェクトです。  
当時の[雑誌掲載](https://github.com/acsdsgn/zigal/blob/main/docs/reconstruction_notes_ja.md#掲載雑誌)プログラム、ダンプリスト、メモリマップ、BASIC＋マシン語の構造を再検証し、エミュレータ上で再現可能な形にまとめています。

## 背景と目的
8bit コンピュータの開発環境は、現代の抽象化されたソフトウェア環境とは異なり、  
**メモリ 64KB・VRAM 48KB・CPU 数MHz** といった極端な制約の中で成立していました。  
この制約は、コンピュータの本質を理解する上で非常に教育的価値が高く、技術史的にも重要です。

本プロジェクトでは、当時の開発プロセスを再現しつつ、  
**現代的な再現性・透明性・資料性** を備えた形で GitHub 上に公開しています。

## プロジェクトの特徴
- 雑誌掲載プログラムのスキャンデータとダンプリストの照合  
- BASIC＋マシン語の復元と動作検証  
- PC-8801 エミュレータでの再現  
- d88 ディスクイメージの生成  
- 復刻ノートによる技術的背景の整理  
- GitHub によるバージョン管理と公開アーカイブ化

詳細は、[復刻ノート](https://github.com/acsdsgn/zigal/blob/main/docs/reconstruction_notes_ja.md)をご覧ください

## 教育的・研究的意義
本プロジェクトは、以下の観点で価値を持ちます。

- **技術史の保存**：8bit 時代の開発手法・制約・文化の記録  
- **再現性の確保**：誰でも同じ環境で動作を確認できる  
- **教育的価値**：メモリ管理・描画・CPU 処理の基礎理解に役立つ  
- **資料としての透明性**：ソース・ノート・イメージをすべて公開  

将来的には、エミュレータ環境を Docker 化し、  
「誰でもワンクリックで 8bit 環境を再現できる教材」としての展開も視野に入れています。

---

# 【English Version】  

## Overview
[ZIGAL](https://github.com/acsdsgn/zigal) is a restoration project of an original PC-8801 action game I developed in the 1980s.  
Using modern tools and archival methods, the game has been reconstructed from [magazine listings](https://github.com/acsdsgn/zigal/blob/main/docs/reconstruction_notes_en.md#published-magazine), memory dumps, and handwritten notes, and is now fully reproducible on contemporary PC-8801 emulators.

## Background and Motivation
The 8-bit computing environment—**64KB of RAM, limited VRAM, and a CPU running at a few MHz**—offers a uniquely transparent view into how computers actually work.  
These constraints make the platform an excellent educational resource and an important part of computing history.

This project aims to preserve that environment while providing **reproducibility, transparency, and archival value** through modern documentation and version control practices.

## Key Features
- Verification of magazine program listings and dump data  
- Reconstruction of BASIC and machine-language routines  
- Execution and testing on PC-8801 emulators  
- Creation of a reproducible d88 disk image  
- Technical restoration notes documenting the process  
- Public archival on GitHub for long-term preservation

For a detailed reconstruction note, see [Reconstruction Notes](https://github.com/acsdsgn/zigal/blob/main/docs/reconstruction_notes_en.md).

## Educational and Research Value
ZIGAL serves as:

- **A historical record** of 8-bit development practices  
- **A reproducible artifact** for researchers and enthusiasts  
- **An educational tool** for understanding memory, graphics, and CPU constraints  
- **A transparent archive** with complete source, notes, and disk images  

Future directions include packaging the emulator environment in Docker, enabling anyone to reproduce the 8-bit computing experience with minimal setup.

---

**Authorship note**: Drafted with Microsoft Copilot · Final responsibility: Seigo Sasaki (revised wording)
