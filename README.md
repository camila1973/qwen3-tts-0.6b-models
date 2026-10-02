# Qwen3-TTS 0.6B Models

Mirror temporal de los pesos de Qwen3-TTS-12Hz-0.6B (Base + CustomVoice) y su tokenizer,
para transferirlos a una red donde huggingface.co no es accesible.

Fuente original:
- https://huggingface.co/Qwen/Qwen3-TTS-12Hz-0.6B-Base
- https://huggingface.co/Qwen/Qwen3-TTS-12Hz-0.6B-CustomVoice
- https://huggingface.co/Qwen/Qwen3-TTS-Tokenizer-12Hz

## Descarga y reensamblado

```bash
gh release download v1 -R camila1973/qwen3-tts-0.6b-models -D .
sha256sum -c SHA256SUMS.txt
cat Qwen3-TTS-0.6B.tar.gz.part-* > Qwen3-TTS-0.6B.tar.gz
tar -xzf Qwen3-TTS-0.6B.tar.gz
```
