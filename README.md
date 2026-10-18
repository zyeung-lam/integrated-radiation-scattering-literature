# Integrated Radiation and Scattering — Literature Reading

# 辐射散射一体化文献导读

本库收录 **12 篇中文文献导读**，覆盖数字天线、有限阵列散射矩阵、同频共极化收发、天线模散射、吸收型共享结构、Van Atta 与预相位单散射波束。

This repository contains **12 Chinese reading guides** on integrated antenna radiation and scattering control, including digital antenna units, finite-array models, full-duplex shared apertures, absorptive structures, Van Atta arrays, and prephased 1-bit scattering control.

## 文献目录 / Paper guides

| 年份 / Year | 文献导读 / Reading guide | 主题 / Focus |
|---|---|---|
| 2021 | [In-Band Scattering and Radiation Tradeoff of Broadband Phased Arrays Based on Scattering-Matrix Approach](2021%20In-Band%20Scattering%20and%20Radiation%20Tradeoff%20of%20Broadband%20Phased%20Arrays%20Based%20on%20Scattering-Matrix%20Approach.md) | 有限阵列匹配网络 / Finite-array matching networks |
| 2021 | [Low RCS Antenna Array With Reconfigurable Scattering Patterns Based on Digital Antenna Units](2021%20Low%20RCS%20Antenna%20Array%20With%20Reconfigurable%20Scattering%20Patterns%20Based%20on%20Digital%20Antenna%20Units.md) | 数字天线与零陷 / Digital antennas and nulls |
| 2023 | [Low-Scattering Phased Arrays With Reconfigurable Scattering Patterns Based on Independent Control of Radiation and Scattering](2023%20Low-Scattering%20Phased%20Arrays%20With%20Reconfigurable%20Scattering%20Patterns%20Based%20on%20Independent%20Control%20of%20Radiation%20and%20Scattering.md) | 单 PIN 与双散射波束 / Single PIN and dual scattering beams |
| 2024 | [A Low-RCS Wideband Antenna Based on Share-Structure of FSA and ME-Dipole](2024%20A%20Low-RCS%20Wideband%20Antenna%20Based%20on%20Share-Structure%20of%20FSA%20and%20ME-Dipole.md) | 共享结构吸收 / Shared absorptive structure |
| 2024 | [A Tri-Functional Multiplexed Linear Array With Simultaneous Transmitting, Receiving, and Backscattering Control for IoT Applications](2024%20A%20Tri-Functional%20Multiplexed%20Linear%20Array%20With%20Simultaneous%20Transmitting%2C%20Receiving%2C%20and%20Backscattering%20Control%20for%20IoT%20Applications.md) | 三功能同时收发与主动散射 / STRAS |
| 2024 | [An In-Band Co-Circularly Polarized Full-Duplex Antenna With Scattering Manipulation](2024%20An%20In-Band%20Co-Circularly%20Polarized%20Full-Duplex%20Antenna%20With%20Scattering%20Manipulation.md) | 全双工与固定角散射 / Full duplex and fixed-angle scattering |
| 2024 | [Broadband Low-RCS Circularly Polarized Antenna Array With Reconfigurable Scattering Patterns](2024%20Broadband%20Low-RCS%20Circularly%20Polarized%20Antenna%20Array%20With%20Reconfigurable%20Scattering%20Patterns.md) | 圆极化与馈网补偿 / CP and feed compensation |
| 2024 | [In-Band RCS Reduction Method for the Vivaldi Array Antennas Based on the Manipulation of the Antenna Mode Scattering Field](2024%20In-Band%20RCS%20Reduction%20Method%20for%20the%20Vivaldi%20Array%20Antennas%20Based%20on%20the%20Manipulation%20of%20the%20Antenna%20Mode%20Scattering%20Field.md) | Vivaldi 模态提取与相消 / Modal extraction and cancellation |
| 2025 | [Independent Scattering and Radiation Beam Steering for Low-Scattering Phased Arrays](2025%20Independent%20Scattering%20and%20Radiation%20Beam%20Steering%20for%20Low-Scattering%20Phased%20Arrays.md) | 两页会议仿真 / Two-page simulation paper |
| 2025 | [Integrated Radiation and Scattering Reconfiguration Broadband Array Based on Antenna Mode Scattering](2025%20Integrated%20Radiation%20and%20Scattering%20Reconfiguration%20Broadband%20Array%20Based%20on%20Antenna%20Mode%20Scattering.md) | 宽带时分切换 / Broadband time-division switching |
| 2025 | [RCS Reconfiguration of an Antenna Array Based on the 1-bit Reconfigurable Load Impedance](2025%20RCS%20Reconfiguration%20of%20an%20Antenna%20Array%20Based%20on%20the%201-bit%20Reconfigurable%20Load%20Impedance.md) | 1-bit 负载与预相位 / 1-bit loads and prephase |
| 2025 | [Van Atta Array With Reconfigurable Scattering Characteristics Based on a Novel Feed Network](2025%20Van%20Atta%20Array%20With%20Reconfigurable%20Scattering%20Characteristics%20Based%20on%20a%20Novel%20Feed%20Network.md) | Van Atta 路由与极化 / Routing and polarization |

## 推荐阅读路线 / Suggested reading routes

1. **机理基础**：Liu 2021 数字天线 → Zhang 2021 散射矩阵 → Zhang 2023 近似独立控制 → Zhang & Chen 2025 会议模型。
2. **单散射波束**：Zhang 2023 二值双主瓣 → Binchao Zhang 2025 负载与预相位。
3. **共享口径系统**：Kang 2024 共圆极化全双工 → Dong 2024 同线极化 STRAS；与 Huang 2025 时分切换对照。
4. **低回波机制**：Zhao 2024 天线模对消 → Wen 2024 吸收型共享结构 → Wang 2024 圆极化相消及补偿。
5. **回溯与可见度切换**：Wu 2025 Van Atta 路由，与 Dong 2024 主动回溯比较。

Start with the foundational models, then compare mechanisms under the same frequency, polarization, termination, and measurement conditions. The routes above distinguish simultaneous operation, switching between modes, and fixed-load proofs of concept.

## 导读规范与证据范围 / Guide format and evidence

每篇文件采用 `YYYY Exact English Paper Title.md`，包含固定 15 节与导读结论：文献信息、BibTeX、问题与机理、关键公式、定量结果、工程代价、局限、复现步骤和组会问题。12 篇均已通过模板结构校验，并在提交后逐篇回读核对。

All guides follow a consistent 15-section format plus a concluding assessment. Reported results, author claims, estimates, and guide-writer evaluations are distinguished. Numerical claims are tied to sections, figures or tables, and the original paper's DOI is linked within each guide.

- 正文依据为本批提供的完整 PDF；检查了相关公式、图注、表格与实验条件。未取得独立补充文件、作者 CAD 或源码的情况已逐篇说明。
- 优先采用出版版首页元数据；可访问的出版网页用于交叉核对，网页不可读取的情况已注明。
- 仿真、实测、UEAEP 测量合成、同时工作和时分切换分别表述。
- RCS 状态差、相对金属板降低量和相对参考天线降低量分别标明基线；原文内部不一致处保留说明。
- Guides are interpretive notes, not replacements for the source papers. Where original metadata pages, supplements or implementation files were unavailable, the limitation is stated explicitly.

## 仓库内容 / Repository contents

本库仅保存本双语 `README.md` 和完成的导读 Markdown。原始 PDF、临时提取文本、渲染图、校验脚本和配置不上传。导读通过 GitHub 直接提交，本地不保留交付副本。

Only this bilingual README and finalized Markdown guides are stored here. Source PDFs, temporary text/images, validators, and configuration files are excluded. GitHub is the delivery location for this collection.
