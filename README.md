# Nemotron 3 Diarization (GGUF, q8_0), mirror

An unchanged copy of `Nemotron-3-Diarization.q8_0.gguf` from
[nvidia/Nemotron-3-Diarization](https://huggingface.co/nvidia/Nemotron-3-Diarization), the speaker
diarization model by NVIDIA (Streaming Sortformer, up to eight speakers). The Plotdesk desktop app
downloads it to tell the speakers of a meeting apart on the device, run by
[NeMo-Speech.cpp](https://github.com/NVIDIA/NeMo-Speech.cpp). No audio leaves the computer.

The file is mirrored, not modified: the desktop app loads all its models from GitHub, so customers whose
proxy allows github.com need no further address.

## File

Release [`v1`](https://github.com/plotdesk/nemotron-3-diarization-gguf/releases/tag/v1):

| File | Bytes | SHA-256 |
|---|---|---|
| `Nemotron-3-Diarization.q8_0.gguf` | 107012128 | `08456d9e22cd9a323c0364d98375f3746d6e68507ebb705cd46438c534c7a3a1` |

The release also carries `SHA256SUMS` and `LICENSE`.

## Origin

- Model: **Nemotron 3 Diarization** by NVIDIA, released September 23, 2026.
- Source: `nvidia/Nemotron-3-Diarization` on Hugging Face, revision
  [`f667ed73aee57d40cc39428eb768b4fd87a0a29e`](https://huggingface.co/nvidia/Nemotron-3-Diarization/tree/f667ed73aee57d40cc39428eb768b4fd87a0a29e),
  file `Nemotron-3-Diarization.q8_0.gguf`.
- Check: the SHA-256 above equals the LFS object id Hugging Face lists for that file at that revision.

## License

Use of this model is governed by the
[OpenMDW License Agreement, version 1.1](https://openmdw.ai/license/1-1/) (OpenMDW-1.1), as stated by
NVIDIA on the model card. A copy of the agreement is in [`LICENSE`](LICENSE). Plotdesk adds no terms of its
own and gives no warranty.
