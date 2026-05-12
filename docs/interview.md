---
title: 面談メモ
---

<style>
body { max-width: 860px; font-size: 0.92rem; }
h2 { border-left: 4px solid #555; padding-left: 0.6rem; margin-top: 1.6rem; }
h3 { margin-top: 1rem; color: #333; }
table { width: 100%; border-collapse: collapse; }
td, th { border: 1px solid #ccc; padding: 0.4rem 0.6rem; vertical-align: top; }
tr:nth-child(even) td { background: #f9f9f9; }
.tag { display:inline-block; background:#eee; border-radius:3px; padding:0.1rem 0.4rem; font-size:0.85rem; margin:0.1rem; }
</style>

# 面談メモ

---

## ポジション一言

> **設計と実装を両立できる、シニア寄りのクラウド・インフラエンジニア**
> GCP / AWS の設計・構築・改善から、Terraform / IaC 実装、生成 AI 基盤の導入まで手を動かして推進。技術議論もできるが、PM 専業・管理専業ではない。

---

## 経歴サマリー

| 期間 | 会社 | 役割 |
|------|------|------|
| 2024.10〜 | フリーランス | GCP クラウド運用最適化（建設業向け Web サービス） |
| 2023.10〜2024.11 | KDDI ウェブコミュニケーションズ | 情シス責任者 / 生成 AI 基盤（Azure OpenAI）設計・導入 |
| 2023.07〜 | フリーランス | DB 負荷対策（MariaDB・自動車業務システム） |
| 2023.02〜2023.09 | フリーランス | 情シス支援（従業員 200 名規模） |
| 2022.01〜2023.07 | Luup | IoT・SRE エンジニア / GCP・AWS 基盤構築・運用 |
| 2018.12〜2022.01 | BIGLOBE | CCoE / AWS 移行推進（約 200 サービス） |
| 2001.04〜2018.10 | ソフトバンク | コアネットワーク開発検証・MVNO 接続受け入れ |

---

## 強み・使い方（3 本柱）

### 1. クラウド基盤 / SRE（メイン）

GCP・AWS の設計・構築・改善。IaC（Terraform）による属人化解消。監視・コスト・IAM・バックアップ・障害対応の一式整備。スタートアップの「壊れない基盤をつくる」フェーズが得意。

**具体的数字：** GCP コスト月額 10% 以上削減・不要リソース 20% 削除

### 2. 生成 AI 基盤の設計・導入

Azure OpenAI / Dify / RAG を使った社内ボット・文書検索・業務自動化の設計と実装。「どう使うか」の方針決定から実際の構築まで担える。

### 3. 技術の横断調整・レビュー

BIGLOBE CCoE のように、複数チームのアーキテクチャ相談を受けて「これで問題ないか」を判断・後押しする役割。管理専業でなく、トレードオフを説明できる立場。

---

## 直近の実績（数字あり）

| 実績 | 内容 |
|------|------|
| GCP コスト削減 | 月額 10% 以上削減・不要リソース約 20% 削除 |
| IAM 整備 | GCP 環境の最小権限化・付与削除フロー整備 |
| 障害対応体制 | バックアップ・リストア手順・復旧訓練の実施 |
| AI 基盤導入 | Azure OpenAI 問い合わせボット・RAG・Teams/Slack 連携 |
| DB 負荷調査 | MariaDB 5 台構成のスロークエリ・接続集中・フェイルオーバー方針整理 |

---

## 技術スタック（一覧）

<span class="tag">GCP</span>
<span class="tag">AWS</span>
<span class="tag">Azure</span>
<span class="tag">Terraform</span>
<span class="tag">Cloud Run</span>
<span class="tag">Cloud SQL</span>
<span class="tag">Datadog</span>
<span class="tag">CloudWatch</span>
<span class="tag">Azure OpenAI</span>
<span class="tag">Dify</span>
<span class="tag">RAG</span>
<span class="tag">MariaDB</span>
<span class="tag">RDS</span>
<span class="tag">IAM</span>
<span class="tag">Entra ID</span>
<span class="tag">Microsoft 365</span>
<span class="tag">Claude Code</span>
<span class="tag">GitHub Copilot</span>

---

## よく聞かれること（想定 QA）

**Q. コードは書けますか？**
Terraform でリソースを書く、GCP / AWS の設定を自分で確認・変更する、Dify ワークフローを設計・実装するのは日常業務。アプリ開発のフルスタック実装は専門外。

**Q. マネジメント経験はありますか？**
KDDI では 6 名チームの情シス責任者を経験。ただし「管理専業」ではなく、技術的な設計・構築も自分で担いながら推進するスタイル。

**Q. 得意な規模感は？**
スタートアップ〜数百名規模。開発チームが少人数でも、基盤整備を「自分で動きながら」前に進められるのが強み。大規模は BIGLOBE・ソフトバンクで経験あり。

**Q. 最近の技術トレンドへの対応は？**
Claude Code / GitHub Copilot / Cursor を日常的に利用。生成 AI の基盤導入（RAG・ボット・業務自動化）の実務経験あり。

---

## 自己紹介（アイスブレイク用）

チワワのちわ丸と暮らしており、毎日癒されています。趣味は珈琲焙煎で、豆の産地・焙煎度・抽出方法をあれこれ試行錯誤しながら楽しんでいます。

---

## リンク

- [フル版レジュメ](./)
- [概要版レジュメ](./short)
