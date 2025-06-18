# Perfect Number Theory（完全数の構成理論）

> 🧠 A Constructive Framework for Generating and Classifying Perfect Numbers  
> 🧠 完全数の生成と分類に関する構成的枠組み

---

## 📌 Overview | 概要

This repository presents a constructive theory for **Perfect Numbers**,  
where numbers are defined through exact structural rules and recursive synthesis.  
本リポジトリでは「完全数」を構成的に定義し、明確な構造規則と再帰的生成によってその性質を明示します。

It explores relationships between perfect numbers and prime factors,  
and provides a reusable logic base for further constructive number theories.  
完全数と素因数の関係性を探り、今後の構成的数論への拡張性を持つロジック基盤を提供します。

---

## 📁 Repository Structure | リポジトリ構成

perfect-number-theory/ ├── README.md            # Documentation (English & Japanese) ├── LICENSE              # MIT License (English, GitHub-compatible) ├── sections/            # Supplementary files (proofs, structure) │   ├── core_theorem.tex │   └── proof_outline.md

---

## 📐 Core Proposition | 中心命題

> All even perfect numbers can be generated through the constructive formula  
> based on the Mersenne prime expansion:  
>  
> `P = 2^(p−1) * (2^p − 1)`  
>  
> 全ての偶数完全数は、メルセンヌ素数を基礎とした構成式により生成可能である：

この理論では、**メルセンヌ型構造が自然に導出される構成法**を用いており、  
単なる帰納的推論ではなく、構成的にその存在性と一意性を証明しています。

---

## 🔬 Included Sections | 含まれる補足ファイル

- `core_theorem.tex` : 数式形式の定理本体
- `proof_outline.md` : 構成理論の生成過程と補足的説明
- 今後必要に応じて `.ipynb` などの数値的検証を追加予定

---

## 🌐 License | ライセンス

This project is licensed under the MIT License.  
本プロジェクトは MIT ライセンスのもとで公開されています。

> See [LICENSE](./LICENSE) for details.

---

## 📣 Author | 著者

- **Masaki Koide / 小井手将基**  
- GitHub: [@Mk9207](https://github.com/Mk9207)  
- Note: [note.com/shiny_hebe5818](https://note.com/shiny_hebe5818/portal)

---

## 🚀 Related Projects | 関連リポジトリ

- [AI Phase Evolution](https://github.com/Mk9207/ai-phase-evolution)
- [Collatz-Goldbach Unified Proof](https://github.com/Mk9207/goldbach-collatz-unified)
