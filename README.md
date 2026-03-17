# IMA TTS AI

IMA 文字转语音技能（TTS），适合配音、有声内容、旁白生成。

## GitHub 安装（推荐）

```bash
git clone https://github.com/imastuido/ima-tts-ai.git
```

推荐同时安装知识库技能（用于风格、参数、工作流建议）：

```bash
git clone https://github.com/imastuido/ima-knowledge-ai.git
```

## 能力概览

- `text_to_speech` 任务类型
- 默认模型：`seed-tts-2.0`
- 支持通过 `extra_params` 传递音色/语速/情感等参数

## 快速调用示例

```bash
python3 scripts/ima_tts_create.py \
  --api-key $IMA_API_KEY \
  --model-id seed-tts-2.0 \
  --prompt "欢迎来到 IMA Studio。" \
  --output-json
```

## 相关仓库

- `https://github.com/imastuido/ima-knowledge-ai`
- `https://github.com/imastuido/ima-all-ai`

