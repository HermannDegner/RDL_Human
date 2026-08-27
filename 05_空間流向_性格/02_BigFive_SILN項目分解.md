# 02_BigFive_SILN項目分解

*RDL Human / 空間流向診断・性格分解 T2 / DRAFT v1.0 (仮配置)*  
*依存: RDL_Core / 人格空間生成仮説 / 04_既知心理・行動理論のRDL翻訳マッピング*

---

## ■ 0. 目的

Big Five（OCEAN）の各因子を、「人間の固定部品」ではなく、**個体 $M_B^{\text{person}}$ の認知パラメータと流向（Flow）の観測断面**として数理分解する。

---

## ■ 1. 各因子の SILN 力学分解

### 1. Extraversion（外向性 / 外部駆動性）
$$E_{\text{obs}} \approx \frac{R_{\text{out}}(\text{external}) \cdot B_{\text{in/out}}(\text{human})}{\theta_{\text{diff}} \cdot w_{\text{diff}}}$$
- **力学**: 外部（人間・刺激・タスク）への接近反応性 $R_{\text{out}}$ の高さ、および他者との越境コストの低さ。

### 2. Agreeableness（協調性 / 同期結合性）
$$A_{\text{obs}} \approx \frac{w_{\text{relation}}}{\theta_{\text{sync}}}$$
- **力学**: 他者の内部状態に対する自己同期閾値 $\theta_{\text{sync}}$ の低さと、関係維持重み $w_{\text{relation}}$ の高さ。

### 3. Conscientiousness（誠実性 / 空間別慣性維持性）
$$C_{\text{obs}} \approx R(d_{\text{goal}}) \cdot w_{\text{goal}} \cdot P_{\text{hold}}$$
- **力学**: 時間的に離れた未来目標 $d_{\text{goal}}$ を現在価値として保持する解像度と、一度引いた境界・計画を維持する性能 $P_{\text{hold}}$。

### 4. Neuroticism（神経症傾向 / 危機・熱反応性）
$$N_{\text{obs}} \approx \frac{R(d_{\text{threat}}) \cdot w_{\text{threat}} \cdot H_{\text{response}}}{\text{Recovery}}$$
- **力学**: 遠距離の危機を敏感に検知する解像度、および誤差 $E$ を内部熱 $H$ へと急速変換する反応強度。

### 5. Openness（開放性 / 境界可塑・探索性）
$$O_{\text{obs}} \approx R(d) \cdot w_{\text{novel}} \cdot P_{\text{redraw}}$$
- **力学**: 未確定領域 $\xi$ に対する新奇性重み $w_{\text{novel}}$、および必要に応じて境界を引き直す可塑性 $P_{\text{redraw}}$。
