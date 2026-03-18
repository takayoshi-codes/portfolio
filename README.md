# 🗂️ Portfolio

AI・機械学習・Web開発・業務自動化の技術を活かした制作物をまとめています。

---

## 🛠 Tech Stack

### ☁️ Application & Data

[![My Skills](https://skillicons.dev/icons?i=python,django,go,js,html,css,vue,nuxt,bootstrap,postgresql,mysql,sqlite,nginx,docker,wordpress,linux,aws,azure,gcp,tensorflow,keras,sklearn,pytorch,opencv,streamlit&perline=10)](https://skillicons.dev)

`BERT` `GPT-2` `Word2Vec` `librosa` `MeCab` `spaCy` `pandas` `NumPy` `openpyxl` `reportlab` `Railway` `HuggingFace`

### 🔧 DevOps & Tools

[![My Skills](https://skillicons.dev/icons?i=git,github,githubactions,gitlab,circleci,vim,terraform,selenium,vscode,bash&perline=10)](https://skillicons.dev)

### ☁️ Cloud & Infra

[![My Skills](https://skillicons.dev/icons?i=aws,azure,gcp,docker,vagrant,vite&perline=10)](https://skillicons.dev)

`Amazon EC2` `Amazon S3` `Route 53` `Amazon RDS` `AWS Lambda` `AWS IAM` `Azure Pipelines` `Google BigQuery`

### 💼 Business Tools

[![My Skills](https://skillicons.dev/icons?i=jquery,vuex&perline=10)](https://skillicons.dev)

`Vue Router` `Vue CLI` `Vuex` `Slack API` `Gmail API` `Google Analytics`

---

## 📦 Projects

### 01｜Web Application

#### 📦 在庫・発注管理 Web アプリ
> Django で構築した本格 CRUD Web アプリ。在庫管理・発注履歴・ログイン認証を一から実装。

| | |
|---|---|
| **使用技術** | Django / PostgreSQL / Bootstrap / Railway |
| **主な機能** | 商品CRUD・在庫アラート・発注履歴・ログイン認証・管理画面 |
| **アピール点** | DB設計・リレーション・認証・デプロイまで一貫実装 |

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![Railway](https://img.shields.io/badge/Railway-0062CC?style=flat-square)

🔗 [Demo](https://your-demo-url.railway.app) ｜ [Code](https://github.com/your-username/inventory-app)

---

### 02｜Machine Learning / Data Analysis

#### 📈 マルチ資産リアルタイム予測ダッシュボード
> 株価・為替・仮想通貨をリアルタイム API で取得し、LSTM・RandomForest・XGBoost でモデル比較。

| | |
|---|---|
| **データ源** | Yahoo Finance API / ExchangeRate API / CoinGecko API |
| **使用技術** | pandas / Keras（LSTM）/ scikit-learn / Matplotlib / Streamlit Cloud |
| **主な機能** | 資産切替・期間選択・モデル比較グラフ・MAE/RMSE表示 |
| **アピール点** | リアルタイムAPI連携・時系列モデル構築・モデル比較評価の一気通貫 |

> ⚠️ 本アプリは学習目的であり、投資助言ではありません。

![Keras](https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=keras&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)

🔗 [Demo](https://your-demo-url.streamlit.app) ｜ [Code](https://github.com/your-username/market-predictor)

---

#### 🖼️ 商品画像 自動分類アプリ
> VGG16 転移学習で商品画像を自動分類。画像アップロード → AI 判定 → 結果表示を Django で一体化。

| | |
|---|---|
| **使用技術** | Keras / TensorFlow / VGG16 / Django / Render |
| **主な機能** | 画像アップロード・転移学習モデル推論・分類結果＋確率表示 |
| **アピール点** | ディープラーニングを実務直結の Web サービスとして提供 |

![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)

🔗 [Demo](https://your-demo-url.onrender.com) ｜ [Code](https://github.com/your-username/image-classifier)

---

#### 🌿 植物診断＆ケアアドバイスアプリ
> 植物の写真から種類・病気・健康状態を AI 判定し、水やり・肥料のアドバイスを自動生成。Slack で水やり通知も配信。

| | |
|---|---|
| **学習データ** | PlantVillage Dataset（54,000枚・38種・病気ラベル付き） |
| **使用技術** | Keras / VGG16 / transformers / Django / PostgreSQL / Slack Webhook / GitHub Actions |
| **主な機能** | 植物種＋病気判定・健康スコア・ケアアドバイス生成・生育記録グラフ・Slack通知 |
| **アピール点** | 画像分類・NLP・DB・通知Bot・デプロイを横断した集大成アプリ |

![Keras](https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=keras&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)

🔗 [Demo](https://your-demo-url.railway.app) ｜ [Code](https://github.com/your-username/plant-care-ai)

---

### 03｜Natural Language Processing

#### 🎭 マルチモーダル複合感情・ストレス分析ツール
> テキスト・音声・表情画像の 3 モダリティを組み合わせて感情・ストレス状態を分析。カウンセリング補助・採用面接・メンタルヘルスなど幅広い用途に対応。

| | |
|---|---|
| **入力モード** | ①テキスト → BERT　②音声 → librosa　③表情画像 → OpenCV |
| **使用技術** | transformers（BERT）/ librosa / OpenCV / MeCab / Streamlit / reportlab |
| **主な機能** | 感情スコア・ストレス指数・矛盾ワードハイライト・レーダーチャート・PDF出力 |
| **アピール点** | NLP・音声・画像を 1 アプリに統合。技術横断力を最大限にアピール |

> ⚠️ AI の判定は参考値であり、診断・法的判断の根拠にはなりません。

![BERT](https://img.shields.io/badge/BERT-transformers-yellow?style=flat-square)
![librosa](https://img.shields.io/badge/librosa-audio-darkred?style=flat-square)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)

🔗 [Demo](https://your-demo-url.streamlit.app) ｜ [Code](https://github.com/your-username/multimodal-emotion)

---

#### 📰 ニュース自動要約＆トレンド検出ダッシュボード
> RSS・スクレイピングでニュースを自動収集し、GPT-2・BERT で要約＋キーワード抽出。トレンドを時系列グラフで可視化。

| | |
|---|---|
| **データ源** | RSSフィード（NHK・日経など）/ BeautifulSoup |
| **使用技術** | transformers（GPT-2・BERT）/ MeCab / pandas / Matplotlib / Streamlit |
| **主な機能** | 記事自動収集・要約生成・キーワードランキング・トレンドグラフ・カテゴリ分類 |
| **アピール点** | データ収集 → NLP処理 → 可視化の一貫フロー |

![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![MeCab](https://img.shields.io/badge/MeCab-NLP-green?style=flat-square)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)

🔗 [Demo](https://your-demo-url.streamlit.app) ｜ [Code](https://github.com/your-username/news-summarizer)

---

#### 📄 求人票×職務経歴書 マッチング診断ツール
> 求人票と職務経歴書を Word2Vec・BERT でベクトル化し、コサイン類似度でマッチングスコアを算出・可視化。

| | |
|---|---|
| **使用技術** | Word2Vec / transformers（BERT）/ MeCab / scikit-learn / Streamlit |
| **主な機能** | テキスト入力・ベクトル化・マッチングスコア・不足スキルハイライト・改善アドバイス |
| **アピール点** | Word2Vec と BERT の両手法を比較実装。実用性の高いキャリアツール |

![Word2Vec](https://img.shields.io/badge/Word2Vec-gensim-lightgrey?style=flat-square)
![BERT](https://img.shields.io/badge/BERT-transformers-yellow?style=flat-square)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)

🔗 [Demo](https://your-demo-url.streamlit.app) ｜ [Code](https://github.com/your-username/job-matcher)

---

### 04｜Business Automation

#### 📊 競合価格モニタリング＆通知 Bot（Slack／メール切替対応）
> 競合商品価格を定期スクレイピングし、変動があれば Slack またはメールで自動通知。GitHub Actions で Cron 実行し常時監視を無人化。

| | |
|---|---|
| **使用技術** | Python / BeautifulSoup / SQLite / Slack Webhook / Gmail API（smtplib）/ GitHub Actions |
| **主な機能** | 価格取得・差分検知・Slack通知・HTMLメール通知・履歴DB保存・日次サマリー |
| **切替設計** | `config.yaml` で `NOTIFY_TYPE: slack / email` を切替。拡張も容易 |
| **アピール点** | 自動運用＋拡張性ある設計力を証明。全ターゲット層にデモ可能 |

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)
![Slack](https://img.shields.io/badge/Slack_API-4A154B?style=flat-square&logo=slack&logoColor=white)
![Gmail](https://img.shields.io/badge/Gmail_API-EA4335?style=flat-square&logo=gmail&logoColor=white)

🔗 [Code](https://github.com/your-username/price-monitor-bot)

---

#### 📄 週次レポート自動生成ツール
> CSV を読み込み、KPI 集計・グラフ生成・Excel／PDF レポートを自動出力。営業・管理部門の週次作業を数クリックで完結。

| | |
|---|---|
| **使用技術** | Python / pandas / openpyxl / Matplotlib / Streamlit / reportlab |
| **主な機能** | CSV取込・KPI集計・グラフ自動生成・Excelテンプレ出力・PDF出力 |
| **アピール点** | 非エンジニア部門でも使えるUIで「業務時間を削減できる」提案を具体化 |

![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![openpyxl](https://img.shields.io/badge/openpyxl-Excel自動化-217346?style=flat-square)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)

🔗 [Demo](https://your-demo-url.streamlit.app) ｜ [Code](https://github.com/your-username/report-generator)

---

## 📬 Contact

- GitHub: [@your-username](https://github.com/your-username)
- Email: your-email@example.com
