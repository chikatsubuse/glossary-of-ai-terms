# 用語リスト（v3・確定版）

- 全173語（キャンバス167枚 − 重複2枚 ＋ 追加8語）
- 並び順＝依存順。前のカードの用語は、後のカードで説明なしに使える
- 見出しは日英併記ルール適用済み。メモの「元:」はキャンバス上のカード名

## 整理の記録

- 重複カードの統合：「学習」×2 → 1枚、「Salesforce（Agent force）」×2 → 1枚
- 「Reasoning」は **reasoning effort** のカードとして04へ配置（01の推論＝Inference、02のリーズニングモデルとは別物として3枚に役割分担）
- 「誤回答」はハルシネーションと**別カードで確定**。ハルシネーション以外の間違いを担当
- 追加4語：生成AI（01）、アライメント（03）、ベクトルDB（04）、著作権（06）
- v3確定後の追加（2026年8月）：FDE（08）＝Palantirカード内の記載を独立化、Prefix Caching（04）、Stripe（11）、ローカルとクラウド（07）
- 確認済み：Hermes Agent＝Nous Research のエージェント、Shizuku AI＝a16z出資の日本発AI VTuber
- 表記修正：Transfomer→Transformer、temparature→temperature、Seekdance→Seedance、Unslowth→Unsloth、Preffered Network→Preferred Networks、Reflextion→Reflexion、Self-imporove→Self-improving、Agent force→Agentforce
- **撤回**：「SpaceXAI→xAI」の表記修正は誤りだったため撤回（2026年2月にSpaceXがxAIを買収、5月にSpaceXAIブランドへ統合表明。元カード名が実態に即していた）

## 01 基礎（8語）

| # | 用語（見出し案） | メモ |
|---|---|---|
| 1 | AI（Artificial Intelligence） | |
| 2 | 機械学習（ML / Machine Learning） | |
| 3 | ニューラルネットワーク／パラメータ（Neural Network / Parameter） | 2語1枚 |
| 4 | ディープラーニング（DL / Deep Learning） | |
| 5 | 生成AI（Generative AI） | 追加 |
| 6 | 学習（Training） | カード2枚 → 1枚に統合 |
| 7 | 推論（Inference） | |
| 8 | AGI（Artificial General Intelligence） | ASIもカード内で触れる |

## 02 モデルの仕組みと種類（13語）

| # | 用語（見出し案） | メモ |
|---|---|---|
| 1 | トークン（Token） | 基準サンプル済み |
| 2 | Transformer | 表記修正 |
| 3 | Attention（注意機構） | |
| 4 | LLM（Large Language Model） | |
| 5 | マルチモーダル（Multimodal） | |
| 6 | MoE（Mixture of Experts） | |
| 7 | 拡散モデル（Diffusion Model） | |
| 8 | 基盤モデル（Foundation Model） | |
| 9 | フロンティアモデル（Frontier Model） | |
| 10 | オープンウェイトモデル（Open-weight Model） | |
| 11 | リーズニングモデル（Reasoning Model） | 元:「Reasoning Model」 |
| 12 | ワールドモデル（World Model） | |
| 13 | Physical AI（フィジカルAI） | ヒューマノイド・自動運転を含む |

## 03 モデルの学習（11語）

| # | 用語（見出し案） | メモ |
|---|---|---|
| 1 | 学習データ／合成データ／アノテーション（Training Data / Synthetic Data / Annotation） | 3語1枚 |
| 2 | 事前学習（Pre-training） | |
| 3 | 事後学習（Post-training） | |
| 4 | ファインチューニング（FT / Fine-tuning） | |
| 5 | LoRA（Low-Rank Adaptation） | |
| 6 | 強化学習（RL / Reinforcement Learning） | |
| 7 | RLHF（Reinforcement Learning from Human Feedback） | |
| 8 | アライメント（Alignment） | 追加 |
| 9 | 蒸留（Distillation） | |
| 10 | 量子化（Quantization） | |
| 11 | スケーリング則（Scaling Laws） | |

## 04 活用の基礎（20語）

| # | 用語（見出し案） | メモ |
|---|---|---|
| 1 | API（Application Programming Interface） | |
| 2 | プロンプト（Prompt） | |
| 3 | システムプロンプト（System Prompt） | |
| 4 | Few-shot | Zero-shotも内包 |
| 5 | CoT（Chain of Thought） | |
| 6 | Extended Thinking | 思考過程を長く取る推論モード（Anthropic用語） |
| 7 | reasoning effort | 元:「Reasoning」。思考量を段階指定するパラメータ（low/high等） |
| 8 | temperature | 表記修正 |
| 9 | コンテキスト（Context） | |
| 10 | コンテキストウィンドウ（Context Window） | |
| 11 | コンパクション（Compaction） | 長い対話・エージェント作業でのコンテキスト圧縮 |
| 12 | Prefix Caching | 追加（2026年8月） |
| 13 | プロンプトエンジニアリング（Prompt Engineering） | |
| 14 | コンテキストエンジニアリング（Context Engineering） | |
| 15 | エンベディング（Embedding） | 元: embedding |
| 16 | ベクトルDB（Vector Database） | 追加 |
| 17 | RAG（Retrieval-Augmented Generation） | 基準サンプル済み |
| 18 | Structured Output（構造化出力） | |
| 19 | Function Calling | tool useとほぼ同義。役割分担（API仕様／概念）で書き分け |
| 20 | tool use（ツール使用） | 同上（Anthropic系の呼称） |

## 05 AIエージェント（20語）

| # | 用語（見出し案） | メモ |
|---|---|---|
| 1 | AIエージェント（AI Agent） | |
| 2 | Agentic AI | AIエージェントと重複気味。バズワードとしての用法・ニュアンス差を担当 |
| 3 | Agentic Workflow | ワークフロー型と自律型の対比を扱う |
| 4 | サブエージェント（Subagent） | |
| 5 | マルチエージェント（Multi-agent） | |
| 6 | Agent Swarm | |
| 7 | オーケストレーション（Orchestration） | |
| 8 | Planning / ReAct / Reflexion | エージェント設計パターン3種を1枚に。表記修正 |
| 9 | MCP（Model Context Protocol） | |
| 10 | A2A（Agent2Agent） | |
| 11 | スキル（Skills） | |
| 12 | Rules | CLAUDE.md・rulesファイル等、エージェントへの恒常的指示 |
| 13 | メモリ（Memory） | 元: memory |
| 14 | Computer Use / Browser Use | |
| 15 | Deep Research | |
| 16 | ループ（Loop） | |
| 17 | ハーネスエンジニアリング（Harness Engineering） | |
| 18 | ループエンジニアリング（Loop Engineering） | |
| 19 | ヒューマンインザループ（Human-in-the-Loop） | |
| 20 | Self-improving Agents | 表記修正。フロンティア領域 |

## 06 リスク・評価・ガバナンス（17語）

| # | 用語（見出し案） | 小分類 | メモ |
|---|---|---|---|
| 1 | ハルシネーション（Hallucination） | 出力の問題 | |
| 2 | 誤回答 | 出力の問題 | ハルシネーション以外の間違い（知識の古さ、指示の取り違え、計算・推論ミス等）を担当 |
| 3 | 迎合（Sycophancy） | 出力の問題 | |
| 4 | バイアス／ディープフェイク（Bias / Deepfake） | 出力の問題 | 2語1枚 |
| 5 | プロンプトインジェクション（Prompt Injection） | 攻撃と防御 | |
| 6 | ジェイルブレイク（Jailbreak） | 攻撃と防御 | |
| 7 | ガードレール（Guardrail） | 攻撃と防御 | |
| 8 | レッドチーミング（Red Teaming） | 攻撃と防御 | |
| 9 | サイバーセキュリティ（Cybersecurity） | 攻撃と防御 | AIによる攻撃・防御の両面 |
| 10 | 評価（Evals） | 評価 | 元: eval |
| 11 | ベンチマーク（Benchmark） | 評価 | |
| 12 | Data Contamination（データ汚染） | 評価 | ベンチマークデータの学習混入とスコア信頼性 |
| 13 | 電子透かし（Watermarking） | 社会・企業 | C2PA・SynthID等 |
| 14 | 著作権（Copyright） | 社会・企業 | 追加。学習データ利用と生成物の両面 |
| 15 | オプトアウト（Opt-out） | 社会・企業 | |
| 16 | AI規制（AI Regulation） | 社会・企業 | EU AI法・日本のAI推進法 |
| 17 | AIガバナンス／シャドーAI（AI Governance / Shadow AI） | 社会・企業 | 2語1枚 |

## 07 インフラ（6語）

| # | 用語（見出し案） | メモ |
|---|---|---|
| 1 | GPU（Graphics Processing Unit） | |
| 2 | TPU（Tensor Processing Unit） | |
| 3 | ローカルとクラウド（Local / Cloud） | 追加（2026年8月）。2語1枚 |
| 4 | ローカルLLM（Local LLM） | |
| 5 | エッジAI／オンプレミス（Edge AI / On-premise） | 2語1枚 |
| 6 | ソブリンAI（Sovereign AI） | |

## 08 インターフェース・開発形態（8語）

| # | 用語（見出し案） | メモ |
|---|---|---|
| 1 | CLI（Command Line Interface） | |
| 2 | GUI（Graphical User Interface） | |
| 3 | デスクトップアプリ（Desktop App） | |
| 4 | スマホアプリ（Mobile App） | |
| 5 | IDE（統合開発環境） | |
| 6 | AIブラウザ／ブラウザ拡張（AI Browser / Browser Extension） | 2語1枚 |
| 7 | バイブコーディング（Vibe Coding） | |
| 8 | FDE（Forward Deployed Engineer） | 追加（2026年8月）。Palantirカード内の記載を独立化 |

## 09 プレイヤー：AIラボと主力モデル（37語）

会社 → モデル → 製品を系列ごとに隣接配置。

| # | 用語（見出し案） | 系列 | メモ |
|---|---|---|---|
| 1 | OpenAI | OpenAI | |
| 2 | GPT | OpenAI | 元: GPT model |
| 3 | ChatGPT | OpenAI | |
| 4 | Codex | OpenAI | |
| 5 | Anthropic | Anthropic | |
| 6 | Claude | Anthropic | 元: claude model |
| 7 | Fable | Anthropic | Claude Fable 5。Opus上位の新ティア（Mythos級） |
| 8 | Claude Code | Anthropic | 元: claude code |
| 9 | Cowork | Anthropic | Anthropicのエージェント作業環境 |
| 10 | Google DeepMind | Google | |
| 11 | Gemini | Google | 元: Gemini model |
| 12 | Gemma | Google | Googleのオープンウェイトモデル |
| 13 | NotebookLM | Google | |
| 14 | Antigravity | Google | |
| 15 | MAI（Microsoft AI） | Microsoft | |
| 16 | M365 Copilot | Microsoft | |
| 17 | GitHub Copilot | Microsoft | |
| 18 | Work IQ | Microsoft | |
| 19 | xAI（SpaceXAI） | xAI | 2026年2月にSpaceX傘下入り、5月にSpaceXAIブランド統合表明 |
| 20 | Grok | xAI | 元: Grok model |
| 21 | Meta AI | Meta | 元: Meta model。会社カードとしてLlamaと役割分担 |
| 22 | Llama | Meta | Metaのオープンウェイトモデル |
| 23 | Mistral | 欧州 | |
| 24 | Liquid AI | 米国その他 | |
| 25 | Apple Intelligence | Apple | |
| 26 | DeepSeek | 中国 | 元: Deepseek model |
| 27 | Qwen（Alibaba） | 中国 | |
| 28 | Kimi（Moonshot AI） | 中国 | |
| 29 | GLM（Zhipu AI） | 中国 | |
| 30 | MiniMax | 中国 | |
| 31 | Seedance（ByteDance） | 中国 | 動画生成。表記修正 |
| 32 | Sakana AI | 日本 | |
| 33 | Preferred Networks | 日本 | PLaMo。表記修正 |
| 34 | Shizuku AI | 日本 | a16z出資の日本発AI VTuber |
| 35 | Suno | メディア生成 | 音楽 |
| 36 | ElevenLabs | メディア生成 | 音声 |
| 37 | Midjourney / Stable Diffusion | メディア生成 | 画像。2語1枚 |

## 10 プレイヤー：開発ツール・エージェント製品（22語）

| # | 用語（見出し案） | メモ |
|---|---|---|
| 1 | Cursor | |
| 2 | Composer | 元: composer model。Cursorの自社モデル |
| 3 | Cline | |
| 4 | OpenCode | |
| 5 | Devin（Cognition） | |
| 6 | OpenClaw | 旧Clawdbot。OSSパーソナルエージェント |
| 7 | Hermes Agent | Nous Researchのエージェント |
| 8 | Manus | |
| 9 | Genspark | 表記修正（GenSpark→Genspark） |
| 10 | Perplexity | AI検索 |
| 11 | Notion AI | |
| 12 | Lovable / v0 / Replit | バイブコーディング系。3語1枚 |
| 13 | LangChain | |
| 14 | Dify / n8n | 2語1枚 |
| 15 | Ollama | |
| 16 | LM Studio | |
| 17 | vLLM | 推論サービング基盤 |
| 18 | MLX | Apple Silicon向けML基盤 |
| 19 | Unsloth | 表記修正 |
| 20 | Sierra | |
| 21 | Palantir | |
| 22 | Salesforce（Agentforce） | カード2枚 → 1枚に統合。表記修正 |

## 11 プレイヤー：インフラ・プラットフォーム（11語）

| # | 用語（見出し案） | メモ |
|---|---|---|
| 1 | NVIDIA | |
| 2 | Nemotron | 元: Nemo model。NVIDIAのオープンモデル群 |
| 3 | Groq | 推論特化チップ |
| 4 | Cerebras | 推論特化チップ |
| 5 | Cloudflare | |
| 6 | Stripe | 追加（2026年8月）。エージェントコマースの決済 |
| 7 | AWS Bedrock | |
| 8 | Azure OpenAI | |
| 9 | Vertex AI | |
| 10 | OpenRouter | マルチモデルAPIゲートウェイ |
| 11 | Hugging Face | |
