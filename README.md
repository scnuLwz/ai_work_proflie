# ai_work_profile

AI 三维资产模型库（glTF-Binary / `.glb`）。

模型文件体积较大（单个 60~85 MB），故以 **Release 附件** 形式提供，不放进 git 树，仓库克隆保持轻量。

## 下载

发布页：<https://github.com/scnuLwz/ai_work_proflie/releases>

## 模型清单（v1）

| 文件 | 大小 | 说明 |
| --- | --- | --- |
| [81bdffae172ff9245ff73e6d5a99ec21.glb](https://github.com/scnuLwz/ai_work_proflie/releases/download/v1/81bdffae172ff9245ff73e6d5a99ec21.glb) | 64.40 MB | AI 生成模型（原始哈希命名） |
| [nailong.glb](https://github.com/scnuLwz/ai_work_proflie/releases/download/v1/nailong.glb) | 71.80 MB | 奶龙模型 |
| [welded.glb](https://github.com/scnuLwz/ai_work_proflie/releases/download/v1/welded.glb) | 71.80 MB | 网格焊接/简化中间产物 |
| [table_hunyuan.glb](https://github.com/scnuLwz/ai_work_proflie/releases/download/v1/table_hunyuan.glb) | 74.66 MB | 混元 3D 生成的球台模型（含 PBR 贴图） |
| [paddle_hunyuan.glb](https://github.com/scnuLwz/ai_work_proflie/releases/download/v1/paddle_hunyuan.glb) | 82.10 MB | 混元 3D 生成的球拍模型（含 PBR 贴图） |

合计 **5** 个模型，共 **364.75 MB**。

## 校验

| 文件 | SHA-256 |
| --- | --- |
| `81bdffae172ff9245ff73e6d5a99ec21.glb` | `b715e07fefe469b07633a3ffbbc5b9994d3184a0732b202c8261a0807620365a` |
| `nailong.glb` | `7853405f8e2c9271a99ca1dab48b6cb22dc8d0826a9ae2bd8f69008e9f4cff4a` |
| `welded.glb` | `c2ffe6aec2bc7c7e15978fedd690f147a16ff89c7c29aeab5d999d56941c81cf` |
| `table_hunyuan.glb` | `e1833c7fd02bf1c17fc47eca8397b7d06c8503cbbb9e5d2a7e3d528d6e2b2360` |
| `paddle_hunyuan.glb` | `e4ebb9410a3e8ec67371892e099f80a9d49149b6b36f5d4c63d7f47fdf0408db` |

下载后可用 `sha256sum` / `certutil -hashfile <file> SHA256` 核对。
