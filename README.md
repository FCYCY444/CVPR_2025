# CVPR_2025

将 CVPR 2025 **冠层图提取** 与 **叶面斑块提取** 两份研究代码清单合并整理，按原始 GitHub 仓库地址去重。来源文件：`开源代码清单(20261125-004114).md`、`开源代码清单(20261125-004118).md`。

**统计：** 原始清单 32 + 49 = 81 条主表项目记录，去重 19 条，保留 **62 个独立上游项目**。其中 **39 个**已按各自许可证完成源码导入；另外 **23 个**未核实明确再分发授权，仅保存链接。

> 这是一份**单仓库源码快照集合**，不构成 GitHub 官方 Fork；原仓库的著作权及许可证仍归原作者，来源文件夹名照清单保留。上游默认分支源码可能与论文发表时的具体版本不同。

## 去重后的项目目录

| 保存文件夹 | 论文编号 | 研究方向 | 原始仓库 | 授权情况 | 保存方式 |
| --- | --- | --- | --- | --- | --- |
| [SGP](./SGP/) | C25-2025 | 冠层图 | [wangkunyu241/SGP](https://github.com/wangkunyu241/SGP) | 未核实明确再分发授权（仅收录链接） | 仅保存来源链接 |
| [GETA](./GETA/) | C25-1657 | 冠层图；叶面斑块 | [microsoft/GETA](https://github.com/microsoft/GETA) | MIT | 已复制源码 |
| [MDP](./MDP/) | C25-1854 | 冠层图；叶面斑块 | [NVlabs/MDP](https://github.com/NVlabs/MDP) | Apache-2.0；README 提醒 HALP 部分仅限非商业使用 | 已复制源码 |
| [FDConv](./FDConv/) | C25-0192 | 冠层图；叶面斑块 | [Linwei-Chen/FDConv](https://github.com/Linwei-Chen/FDConv) | MIT | 已复制源码 |
| [GCNet](./GCNet/) | C25-2418 | 冠层图；叶面斑块 | [gyyang23/GCNet](https://github.com/gyyang23/GCNet) | MIT | 已复制源码 |
| [BoltzFormer](./BoltzFormer/) | C25-2711 | 冠层图；叶面斑块 | [microsoft/BoltzFormer](https://github.com/microsoft/BoltzFormer) | Apache-2.0 | 已复制源码 |
| [FIMA-Q](./FIMA-Q/) | C25-2211 | 冠层图；叶面斑块 | [ShiheWang/FIMA-Q](https://github.com/ShiheWang/FIMA-Q) | Apache-2.0 | 已复制源码 |
| [DINO_Teacher](./DINO_Teacher/) | C25-0972 | 冠层图 | [TRAILab/DINO_Teacher](https://github.com/TRAILab/DINO_Teacher) | Apache-2.0 | 已复制源码 |
| [DEIM](./DEIM/) | C25-0708 | 冠层图 | [Intellindust-AI-Lab/DEIM](https://github.com/Intellindust-AI-Lab/DEIM) | Apache-2.0 | 已复制源码 |
| [OverLoCK](./OverLoCK/) | C25-1358 | 冠层图；叶面斑块 | [LMMMEng/OverLoCK](https://github.com/LMMMEng/OverLoCK) | Apache-2.0 | 已复制源码 |
| [MobileMamba](./MobileMamba/) | C25-0640 | 冠层图；叶面斑块 | [lewandofskee/MobileMamba](https://github.com/lewandofskee/MobileMamba) | MIT | 已复制源码 |
| [FRACAL](./FRACAL/) | C25-0019 | 冠层图 | [kostas1515/FRACAL](https://github.com/kostas1515/FRACAL) | Apache-2.0 | 已复制源码 |
| [point2rbox-v2](./point2rbox-v2/) | C25-2519 | 冠层图 | [VisionXLab/point2rbox-v2](https://github.com/VisionXLab/point2rbox-v2) | 未核实明确再分发授权（仅收录链接） | 仅保存来源链接 |
| [AODRaw](./AODRaw/) | C25-1150 | 冠层图 | [lzyhha/AODRaw](https://github.com/lzyhha/AODRaw) | CC BY-NC 4.0；需要署名，禁止商业用途 | 已复制源码 |
| [DeepCompress-ViT](./DeepCompress-ViT/) | C25-0009 | 冠层图；叶面斑块 | [ML-Security-Research-LAB/DeepCompress-ViT](https://github.com/ML-Security-Research-LAB/DeepCompress-ViT) | 未核实明确再分发授权（仅收录链接） | 仅保存来源链接 |
| [cropr](./cropr/) | C25-0082 | 冠层图；叶面斑块 | [benbergner/cropr](https://github.com/benbergner/cropr) | MIT | 已复制源码 |
| [QwT](./QwT/) | C25-0485 | 冠层图；叶面斑块 | [wujx2001/QwT](https://github.com/wujx2001/QwT) | Apache-2.0 | 已复制源码 |
| [APHQ-ViT](./APHQ-ViT/) | C25-2192 | 冠层图；叶面斑块 | [GoatWu/APHQ-ViT](https://github.com/GoatWu/APHQ-ViT) | Apache-2.0 | 已复制源码 |
| [OWOBJ](./OWOBJ/) | C25-2659 | 冠层图 | [AI4Math-ShanZhang/OWOBJ](https://github.com/AI4Math-ShanZhang/OWOBJ) | Apache-2.0（仓库文件 LICENCE） | 已复制源码 |
| [Generalized-Diffusion-Detector](./Generalized-Diffusion-Detector/) | C25-0638 | 冠层图 | [heboyong/Generalized-Diffusion-Detector](https://github.com/heboyong/Generalized-Diffusion-Detector) | 未核实明确再分发授权（仅收录链接） | 仅保存来源链接 |
| [SE-COT](./SE-COT/) | C25-2682 | 冠层图 | [ZZ2490/SE-COT](https://github.com/ZZ2490/SE-COT) | 未核实明确再分发授权（仅收录链接） | 仅保存来源链接 |
| [AeroGen](./AeroGen/) | C25-1891 | 冠层图 | [Sonettoo/AeroGen](https://github.com/Sonettoo/AeroGen) | 未核实明确再分发授权（仅收录链接） | 仅保存来源链接 |
| [SearchDet_Long_Tail_Object_Detection](./SearchDet_Long_Tail_Object_Detection/) | C25-1801 | 冠层图 | [Mankeerat/SearchDet_Long_Tail_Object_Detection](https://github.com/Mankeerat/SearchDet_Long_Tail_Object_Detection) | MIT | 已复制源码 |
| [MambaVision](./MambaVision/) | C25-0632 | 冠层图；叶面斑块 | [NVlabs/MambaVision](https://github.com/NVlabs/MambaVision) | NVIDIA Source Code License-NC；仅限非商业研究/评估 | 已复制源码 |
| [MambaOut](./MambaOut/) | C25-2514 | 冠层图；叶面斑块 | [yuweihao/MambaOut](https://github.com/yuweihao/MambaOut) | Apache-2.0 | 已复制源码 |
| [GroupMamba](./GroupMamba/) | C25-1746 | 冠层图；叶面斑块 | [Amshaker/GroupMamba](https://github.com/Amshaker/GroupMamba) | MIT | 已复制源码 |
| [DBPS](./DBPS/) | C25-1643 | 冠层图；叶面斑块 | [Qinrong-NKU/DBPS](https://github.com/Qinrong-NKU/DBPS) | 未核实明确再分发授权（仅收录链接） | 仅保存来源链接 |
| [HVI-CIDNet](./HVI-CIDNet/) | C25-2384 | 冠层图；叶面斑块 | [Fediory/HVI-CIDNet](https://github.com/Fediory/HVI-CIDNet) | MIT | 已复制源码 |
| [quart-depth](./quart-depth/) | C25-1771 | 冠层图；叶面斑块 | [shawnricecake/quart-depth](https://github.com/shawnricecake/quart-depth) | 未核实明确再分发授权（仅收录链接） | 仅保存来源链接 |
| [ReRAW](./ReRAW/) | C25-0081 | 冠层图 | [SonyResearch/ReRAW](https://github.com/SonyResearch/ReRAW) | MIT | 已复制源码 |
| [DarkIR](./DarkIR/) | C25-0454 | 冠层图；叶面斑块 | [cidautai/DarkIR](https://github.com/cidautai/DarkIR) | MIT | 已复制源码 |
| [P2RLoss](./P2RLoss/) | C25-1217 | 冠层图 | [Elin24/P2RLoss](https://github.com/Elin24/P2RLoss) | 未核实明确再分发授权（仅收录链接） | 仅保存来源链接 |
| [UCOD-DPL](./UCOD-DPL/) | C25-2392 | 叶面斑块 | [Heartfirey/UCOD-DPL](https://github.com/Heartfirey/UCOD-DPL) | 未核实明确再分发授权（仅收录链接） | 仅保存来源链接 |
| [PolarNeXt](./PolarNeXt/) | C25-1857 | 叶面斑块 | [Sun15194/PolarNeXt](https://github.com/Sun15194/PolarNeXt) | Apache-2.0 | 已复制源码 |
| [WPFormer](./WPFormer/) | C25-2393 | 叶面斑块 | [yfhdm/WPFormer](https://github.com/yfhdm/WPFormer) | 未核实明确再分发授权（仅收录链接） | 仅保存来源链接 |
| [Foveated-Instance-Segmentation](./Foveated-Instance-Segmentation/) | C25-2563 | 叶面斑块 | [SAI-Lab-NYU/Foveated-Instance-Segmentation](https://github.com/SAI-Lab-NYU/Foveated-Instance-Segmentation) | 未核实明确再分发授权（仅收录链接） | 仅保存来源链接 |
| [DALE](./DALE/) | C25-0448 | 叶面斑块 | [lxFang2022/DALE](https://github.com/lxFang2022/DALE) | 未核实明确再分发授权（仅收录链接） | 仅保存来源链接 |
| [RUE](./RUE/) | C25-1639 | 叶面斑块 | [Qinrong-NKU/RUE](https://github.com/Qinrong-NKU/RUE) | 未核实明确再分发授权（仅收录链接） | 仅保存来源链接 |
| [EASE](./EASE/) | C25-0401 | 叶面斑块 | [xiaohainku/EASE](https://github.com/xiaohainku/EASE) | 未核实明确再分发授权（仅收录链接） | 仅保存来源链接 |
| [SCSegamba](./SCSegamba/) | C25-1325 | 叶面斑块 | [Karl1109/SCSegamba](https://github.com/Karl1109/SCSegamba) | Apache-2.0 | 已复制源码 |
| [MaSS13K](./MaSS13K/) | C25-2295 | 叶面斑块 | [xiechenxi99/MaSS13K](https://github.com/xiechenxi99/MaSS13K) | 未核实明确再分发授权（仅收录链接） | 仅保存来源链接 |
| [POT](./POT/) | C25-2103 | 叶面斑块 | [jianwang91/POT](https://github.com/jianwang91/POT) | 未核实明确再分发授权（仅收录链接） | 仅保存来源链接 |
| [WSSS-PCRE](./WSSS-PCRE/) | C25-2367 | 叶面斑块 | [xxf011/WSSS-PCRE](https://github.com/xxf011/WSSS-PCRE) | 未核实明确再分发授权（仅收录链接） | 仅保存来源链接 |
| [Dinomaly](./Dinomaly/) | C25-0575 | 叶面斑块 | [guojiajeremy/Dinomaly](https://github.com/guojiajeremy/Dinomaly) | Apache-2.0 | 已复制源码 |
| [SegMAN](./SegMAN/) | C25-0486 | 叶面斑块 | [yunxiangfu2001/SegMAN](https://github.com/yunxiangfu2001/SegMAN) | Apache-2.0 | 已复制源码 |
| [MCADS-Decoder](./MCADS-Decoder/) | C25-2165 | 叶面斑块 | [saadwazir/MCADS-Decoder](https://github.com/saadwazir/MCADS-Decoder) | GPL-3.0 | 已复制源码 |
| [ROS-SAM](./ROS-SAM/) | C25-1747 | 叶面斑块 | [ShanZard/ROS-SAM](https://github.com/ShanZard/ROS-SAM) | 未核实明确再分发授权（仅收录链接） | 仅保存来源链接 |
| [CSC-PA](./CSC-PA/) | C25-0375 | 叶面斑块 | [shdkdh/CSC-PA](https://github.com/shdkdh/CSC-PA) | 未核实明确再分发授权（仅收录链接） | 仅保存来源链接 |
| [UniVAD](./UniVAD/) | C25-0559 | 叶面斑块 | [FantasticGNU/UniVAD](https://github.com/FantasticGNU/UniVAD) | CC BY-NC-SA 4.0；署名、非商业、相同方式共享 | 已复制源码 |
| [AA-CLIP](./AA-CLIP/) | C25-1400 | 叶面斑块 | [Mwxinnn/AA-CLIP](https://github.com/Mwxinnn/AA-CLIP) | Apache-2.0 | 已复制源码 |
| [vCLR](./vCLR/) | C25-2694 | 叶面斑块 | [Visual-AI/vCLR](https://github.com/Visual-AI/vCLR) | MIT | 已复制源码 |
| [LPOSS](./LPOSS/) | C25-1830 | 叶面斑块 | [vladan-stojnic/LPOSS](https://github.com/vladan-stojnic/LPOSS) | MIT | 已复制源码 |
| [MaskAdapter](./MaskAdapter/) | C25-1099 | 叶面斑块 | [hustvl/MaskAdapter](https://github.com/hustvl/MaskAdapter) | Apache-2.0 | 已复制源码 |
| [ExCEL](./ExCEL/) | C25-2408 | 叶面斑块 | [zwyang6/ExCEL](https://github.com/zwyang6/ExCEL) | 未核实明确再分发授权（仅收录链接） | 仅保存来源链接 |
| [BHViT](./BHViT/) | C25-0498 | 叶面斑块 | [IMRL/BHViT](https://github.com/IMRL/BHViT) | MIT | 已复制源码 |
| [AnomalyNCD](./AnomalyNCD/) | C25-0700 | 叶面斑块 | [HUST-SLOW/AnomalyNCD](https://github.com/HUST-SLOW/AnomalyNCD) | MIT | 已复制源码 |
| [cups](./cups/) | C25-0603 | 叶面斑块 | [visinf/cups](https://github.com/visinf/cups) | Apache-2.0 | 已复制源码 |
| [EdgeTAM](./EdgeTAM/) | C25-2789 | 叶面斑块 | [facebookresearch/EdgeTAM](https://github.com/facebookresearch/EdgeTAM) | Apache-2.0 | 已复制源码 |
| [LiVOS](./LiVOS/) | C25-1291 | 叶面斑块 | [uncbiag/LiVOS](https://github.com/uncbiag/LiVOS) | MIT | 已复制源码 |
| [Samba](./Samba/) | C25-0643 | 叶面斑块 | [Jia-hao999/Samba](https://github.com/Jia-hao999/Samba) | 未核实明确再分发授权（仅收录链接） | 仅保存来源链接 |
| [rip_currents](./rip_currents/) | C25-0414 | 叶面斑块 | [Irikos/rip_currents](https://github.com/Irikos/rip_currents) | 未核实明确再分发授权（仅收录链接） | 仅保存来源链接 |
| [SSP](./SSP/) | C25-1966 | 叶面斑块 | [FraunhoferIVI/SSP](https://github.com/FraunhoferIVI/SSP) | CC BY-NC-SA 4.0；署名、非商业、相同方式共享 | 已复制源码 |

## 保存与使用边界

- 原清单跨方向出现的 19 个 GitHub 仓库每个只收录一次，在对应 `SOURCE.md` 中记录两个研究方向。
- 保存的源码为原仓库**当前默认分支的浅克隆快照**，不保留上游完整提交历史。每次源码导入在[导入报告](./import-reports/cvpr2025-import.md)中记录上游提交 SHA。
- `MambaVision` 采用 NVIDIA Source Code License-NC，`AODRaw` 为 CC BY-NC 4.0，`UniVAD` 和 `SSP` 为 CC BY-NC-SA 4.0；这些代码存在**非商业使用限制**。
- `MDP` 根目录许可证为 Apache-2.0，但 README 特别说明其中的 HALP 相关代码仅限非商业研究/评估。使用时应区分原始来源与第三方依赖。
- `MCADS-Decoder` 的 GPL-3.0 有相应的再分发义务；所有项目均应保留原许可和著作权声明。
- 上游仓库名称变更：原 `ZZ2490/SE-COT` 迁移至 `2490o/SE-COT`；`yfhdm/WPFormer` 迁移至 `fengyan-cv/WPFormer`；`Mankeerat/SearchDet_Long_Tail_Object_Detection` 迁移至 `Mankeerat/SearchDet`。目录仍保持**清单指定名称**；`SOURCE.md` 另记录现行地址。
- 未核实许可证的项目不复制原始源码，仅在同名文件夹建立 `SOURCE.md`。含 README 或在线公开源码**并不自动代表允许重新分发**。
- Git LFS、外部权重、原始数据、子模块和较大的二进制文件可能不会被镜像。索引中的“已复制源码”仅指实际提交的快照文件。
- 此次只修改 GitHub 仓库，不更改 `D:\mianyeman\paper\CVPR2025\参考代码` 下的任何本地文件。

**导入核验：** [GitHub Actions 成功运行记录](https://github.com/FCYCY444/CVPR_2025/actions/runs/45520598839)。39 个计划复制的项目均已导入，23 个许可证未明确的仓库仅保存来源链接。本次有 8 个超过 20 MiB 的二进制文件/演示素材未复制，需要运行时请从原作者仓库获取。

## 索引、导入与补充链接

- [机器可读索引 projects.csv](./projects.csv)
- [源码导入清单](./.github/import-cvpr2025-sources.tsv)
- [源码导入报告](./import-reports/cvpr2025-import.md)（39 个项目成功，含上游提交 SHA 和省略文件记录）
- [尚待核实的其他论文/项目页](./unverified-sources.md)（不计入 62 个已核实项目）
