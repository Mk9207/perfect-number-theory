# 完全数の構成理論 / Constructive Theory of Perfect Numbers

## 概要 / Overview

このリポジトリでは、完全数の構成的性質に関する理論を構築し、構成的手法に基づいた証明を提示します。  
This repository develops a constructive theory for the structural properties of perfect numbers, offering a proof based on constructive techniques.

---

## 構成 / Structure

- `README.md`: 本ファイル。理論の概要とナビゲーション。  
- `LICENSE.md`: MITライセンス。特許出願中でない限り、再利用自由。  
- `sections/`: 理論の補足文書・定義・補題・証明などの構文ファイルを格納。  

---

## 理論構造 / Theoretical Structure

### 定義（Definitions）
- 自然数 $n$ が**完全数**であるとは、$n$ の正の約数（自身を除く）の総和が $n$ に等しいときである。

### 補題（Lemmas）
- 補題1：偶数完全数は $2^{p-1}(2^p - 1)$ の形を持つ（ただし $2^p - 1$ はメルセンヌ素数）。

### 定理（Theorem）
- 定理：すべての偶数完全数はメルセンヌ素数に基づいて構成可能であり、この形式以外の偶数完全数は存在しない。

---

## 今後の展望 / Future Work

- 奇数完全数の存在の有無を構成的に証明するためのアプローチ構築。
- 他の完備性概念との接続（例えば友愛数・過剰数との関係）。

---

## ライセンス / License

MIT License（詳細は `LICENSE.md` を参照）。

