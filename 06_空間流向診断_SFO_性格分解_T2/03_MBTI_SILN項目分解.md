# 03_MBTI_SILN項目分解

*RDL Human / 空間流向診断・性格分解 T2 / DRAFT v1.0 (仮配置)*  
*依存: RDL_Core / 人格空間生成仮説 / 01_SFO空間流向診断_統合モデル*

---

## ■ 0. 目的

MBTIの4指標（E/I, S/N, T/F, J/P）および16タイプを、固定的な性格型ではなく、**認知空間における情報処理・境界操作のパラメータ傾向**として分解する。

---

## ■ 1. MBTI 4軸の SILN パラメータ分解

| 軸 | RDL 力学定義 | パラメータ |
| :--- | :--- | :--- |
| **E / I**<br>(外向 / 内向) | エネルギー代謝の主対象が「外部関係 $W_{\text{ext}}$」か「内部整合 $M_B^{\text{self}}$」か。 | $R_{\text{out}}(\text{external}) \text{ vs } R_{\text{in}}(\text{internal})$ |
| **S / N**<br>(感覚 / 直観) | 予測解像度 $R(d)$ の焦点が「近距離の具体事実（Near）」か「遠距離の抽象パターン（Far）」か。 | $R(d_{\text{near}}) \text{ vs } R(d_{\text{far}})$ |
| **T / F**<br>(思考 / 感情) | 判断時に「他者状態と同期せず状態分離するか（高 $E_{\text{sim}}$・低 $E_{\text{sync}}$）」、「他者状態と同期して情動結合するか（低 $\theta_{\text{sync}}$）」。 | $\text{State Isolation} \text{ vs } \theta_{\text{sync}}$ |
| **J / P**<br>(判断 / 知覚) | 境界操作において「一度引いた境界を維持・早期収束させるか（$P_{\text{hold}}$）」、「境界を引き直し未確定を保持するか（$P_{\text{redraw}}$）」。 | $P_{\text{hold}} \text{ vs } P_{\text{redraw}}$ |
