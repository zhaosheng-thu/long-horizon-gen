# long-horizen-gen

长视频问题浏览器：Self-Forcing、LongLive（官方 / OPSD-V LoRA / 我们的 R、AB10、ABs10）生成的 918 段 60 秒视频，
配 VLM（Claude 子代理）盲评标注的时间轴。纯静态页面：`index.html` + `data.json` + `v/`（416×240 压缩视频）+ `s/`（1 fps 胶片条）。

由 PerceptualDistill 仓库的 `scripts/lhg_site.py`（media / data）生成，原始标注在该仓库 `labels/vlm/`。
