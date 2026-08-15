# モデル一覧（2026年8月時点）

主要プレイヤーが提供中の現行モデルの早見表。会社名・モデル名のリンク先は解説カード。

- 対象はモデルのみ。製品・エージェント（ChatGPT、Claude Code、Cowork、Sakana Marlin等）は各カード参照
- 現行世代の主要モデルに絞る（旧世代・提供終了は載せない。サイズ違いは代表のみ）
- 「重み」＝モデルウェイトの公開有無。「オープン」でもライセンス条件は各社で異なる
- 価格・コンテキスト長などのAPIスペックは変化が速いため扱わない（各社の公式ドキュメント参照）
- 更新ルールはREADME「更新・メンテナンス」参照（Web調査必須・四半期目安）

## フロンティアラボ（米国）

| 会社 | モデル | 種別 | 重み | 公開 | ひとこと |
|---|---|---|---|---|---|
| [OpenAI](09-labs-models/openai.md) | [GPT-5.6 Sol](09-labs-models/gpt.md) | リーズニング | 非公開 | 2026/7 | フラッグシップ |
| | GPT-5.6 Terra | 汎用 | 非公開 | 2026/7 | 標準グレード |
| | GPT-5.6 Luna | 軽量 | 非公開 | 2026/7 | 高速・低価格帯 |
| | gpt-oss-120b／20b | 汎用 | オープン | 2025/8 | 唯一の現役オープン版 |
| | GPT Image 2 | 画像生成 | 非公開 | 2026/4 | 画像フラッグシップ |
| | GPT-5.6-Cyber | サイバー特化 | 非公開 | 2026/8 | 承認組織限定（Daybreak） |
| | Sora 2 | 動画生成 | 非公開 | 2025/9 | 提供終了へ・後継未発表 |
| [Anthropic](09-labs-models/anthropic.md) | [Claude Fable 5](09-labs-models/fable.md) | リーズニング | 非公開 | 2026/6 | Mythos級の一般提供版 |
| | [Claude Mythos 5](09-labs-models/fable.md) | リーズニング | 非公開 | 2026/6 | 承認組織限定・分類器なし |
| | [Claude Opus 5](09-labs-models/claude.md) | 汎用 | 非公開 | 2026/7 | Fable級を半額帯で |
| | Claude Sonnet 5 | 汎用 | 非公開 | 2026/6 | 速度と知能の両立 |
| | Claude Haiku 4.5 | 軽量 | 非公開 | 2025/10 | 最速・低価格帯 |
| [Google DeepMind](09-labs-models/google-deepmind.md) | [Gemini 3.1 Pro](09-labs-models/gemini.md) | リーズニング | 非公開 | 2026/2 | フラッグシップ |
| | Gemini 3.7 Flash | 汎用 | 非公開 | 2026/8 | 高速な普及帯の主力 |
| | [Gemma 4](09-labs-models/gemma.md) | 汎用 | オープン | 2026/4 | オープン側の旗艦 |
| | Nano Banana 2 | 画像生成 | 非公開 | 2026/2 | Gemini統合の画像生成 |
| | Veo 3.1 | 動画生成 | 非公開 | 2025/10 | 音声同時生成の映像特化 |
| | Genie 3 | ワールドモデル | 非公開 | 2025/8 | 商用化の先行例 |
| [Microsoft（MAI）](09-labs-models/mai.md) | MAI-Thinking-1 | リーズニング | 非公開 | 2026/6 | 初の自社リーズニング |
| | MAI-Code-1.1-Flash | コーディング | 非公開 | 2026/8 | GitHub Copilot向け |
| | MAI-Image-2.6 | 画像生成 | 非公開 | 2026/8 | 画像アリーナ上位 |
| | MAI-Voice-2 | 音声 | 非公開 | 2026/6 | 低遅延の音声生成 |
| [xAI（SpaceXAI）](09-labs-models/xai.md) | [Grok 4.6](09-labs-models/grok.md) | 汎用 | 非公開 | 2026/8 | 旗艦・コスト競争路線 |
| | Grok Imagine Image 2.0 | 画像生成 | 非公開 | 2026/8 | X統合・精密編集 |
| | Grok Imagine Video 1.5 | 動画生成 | 非公開 | 2026/7 | 1080pネイティブ動画 |
| [Meta](09-labs-models/meta-ai.md) | Muse Spark 1.2 | リーズニング | 非公開 | 2026/8 | 初の非公開旗艦 |
| | Muse Glimmer | 汎用 | オープン | 2026/8 | 30B・単一GPU向け |
| | [Llama 4](09-labs-models/llama.md) | 汎用 | オープン | 2025/4 | 現行＝最終世代 |

## 欧州・その他

| 会社 | モデル | 種別 | 重み | 公開 | ひとこと |
|---|---|---|---|---|---|
| [Mistral](09-labs-models/mistral.md) | Mistral Large 3 | 汎用 | オープン | 2025/12 | 675B MoE・欧州の旗艦 |
| | Mistral Medium 3.5 | コーディング | オープン | 2026/5 | エージェント用途特化 |
| | Mistral Small 4 | 汎用 | オープン | 2026/3 | 単一GPU級の万能型 |
| | Ministral 3 | 軽量 | オープン | 2025/12 | エッジ向け小型3サイズ |
| [Liquid AI](09-labs-models/liquid-ai.md) | LFM2.5シリーズ | 軽量 | オープン | 2026/1〜8 | 非Transformerのエッジ特化 |
| [Apple](09-labs-models/apple-intelligence.md) | AFM 3（Core／Core Advanced） | 軽量 | 非公開 | 2026/6 | 端末内基盤・搭載は26年秋 |
| | AFM 3 Cloud（／Pro） | 汎用 | 非公開 | 2026/6 | 自社クラウドPCC上で稼働 |

## 中国

| 会社 | モデル | 種別 | 重み | 公開 | ひとこと |
|---|---|---|---|---|---|
| [DeepSeek](09-labs-models/deepseek.md) | DeepSeek-V4-Pro | 汎用 | オープン | 2026/8 | リーズニング統合の旗艦 |
| | DeepSeek-V4-Flash | 軽量 | オープン | 2026/7 | 高速・低コスト版 |
| [Qwen（Alibaba）](09-labs-models/qwen.md) | Qwen3.8-Max | 汎用 | オープン（条件付き） | 2026/8 | 2.4T MoEの旗艦 |
| | Qwen3.8-27B | 軽量 | オープン | 2026/8 | ローカル定番の中核 |
| | Qwen3-Coder-Next | コーディング | オープン | 2026/2 | エージェント向けコード |
| [Kimi（Moonshot AI）](09-labs-models/kimi.md) | Kimi K3 | 汎用 | オープン | 2026/7 | 2.8T・オープン最大級 |
| | Kimi K2.7-Code | コーディング | オープン | 2026/6 | 1Tのコード特化 |
| [GLM（Zhipu AI）](09-labs-models/glm.md) | GLM-5.3 | 汎用 | 公開予定 | 2026/8 | コード・エージェント強化 |
| | GLM-5.2 | 汎用 | オープン | 2026/6 | MIT公開の主力 |
| [MiniMax](09-labs-models/minimax.md) | MiniMax-M3 | 汎用 | オープン | 2026/6 | 428B・1M文脈の旗艦 |
| | Hailuo 3 | 動画生成 | オープン | 2026/7 | 2K・音声同時の動画 |
| [ByteDance](09-labs-models/seedance.md) | Seedance 2.5 | 動画生成 | 非公開 | 2026/7 | 30秒ワンカット生成 |
| | Seedream 5.0 | 画像生成 | 非公開 | 2026/2 | 検索連動の画像生成 |
| | Doubao Seed 2.1 | 汎用 | 非公開 | 2026/6 | 中国市場の旗艦LLM |

## 日本

| 会社 | モデル | 種別 | 重み | 公開 | ひとこと |
|---|---|---|---|---|---|
| [Sakana AI](09-labs-models/sakana-ai.md) | Sakana Namazu | 汎用 | 非公開 | 2026/8 | 日本語特化の主力LLM |
| | Sakana Fugu | オーケストレーション | 非公開 | 2026/6 | 複数モデルを束ねる |
| [Preferred Networks](09-labs-models/preferred-networks.md) | PLaMo 3.0 Prime | 汎用 | 非公開 | 2026/6 | 国産初のリーズニング含む |
| | PLaMo 3 NICT | 汎用 | オープン | 2025/11 | 重み公開のベース版 |
| | PLaMo翻訳 | 翻訳 | オープン | 2025/5 | 日英特化 |

## メディア生成

| 会社 | モデル | 種別 | 重み | 公開 | ひとこと |
|---|---|---|---|---|---|
| [Suno](09-labs-models/suno.md) | Suno v5.5 | 音楽 | 非公開 | 2026/3 | フル楽曲生成の代表格 |
| [ElevenLabs](09-labs-models/elevenlabs.md) | Eleven v3 | 音声 | 非公開 | 2026/2 | 感情タグ対応TTS |
| | Eleven Music v2 | 音楽 | 非公開 | 2026/5 | 許諾先行の音楽生成 |
| [Midjourney](09-labs-models/midjourney-stable-diffusion.md) | Midjourney V8.2 | 画像生成 | 非公開 | 2026/7 | 品質重視の定番 |
| | Video V1 | 動画生成 | 非公開 | 2025/6 | 画像から動画生成 |
| [Stability AI](09-labs-models/midjourney-stable-diffusion.md) | Stable Diffusion 3.5 | 画像生成 | オープン | 2024/10 | ローカル画像文化の土台 |
| | Stable Audio 3 | 音楽 | オープン | 2026/5 | 許諾データで学習 |

## 開発ツール・インフラ系の自社モデル

| 会社 | モデル | 種別 | 重み | 公開 | ひとこと |
|---|---|---|---|---|---|
| [Cursor](10-tools-products/cursor.md) | [Composer 2.5](10-tools-products/composer.md) | コーディング | 非公開 | 2026/5 | IDE最適化の高速特化 |
| [NVIDIA](11-platforms/nvidia.md) | [Nemotron 3（Nano／Super／Ultra）](11-platforms/nemotron.md) | 汎用 | オープン | 2025/12〜26/6 | 米国オープン勢の柱 |
| | Cosmos 3 | ワールドモデル | オープン | 2026/5 | フィジカルAI向け |
