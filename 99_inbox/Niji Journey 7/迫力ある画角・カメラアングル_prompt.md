---
サブタイトル:
タグ:
  - やりたいこと
  - デザイン
情報元: https://x.com/tokyo_Valentine/status/2011763614034903280?s=20
作成日: 2026年1月17日
最終更新日時:
---
#nijiJourney, #Midjourney, #プロンプト, #戦闘シーン, #カメラアングル, 

## 3) 推奨（優先度付き）／アクションプラン（ステップ）
### 優先度A：アングル検証を“再現可能”にする
1. キャラ条件（年齢/髪/目/衣装/世界観）を固定し、**Camera/Angle + Pose + 背景エフェクト**だけ差し替える。
2. “カメラ方向を直接指定”よりも、**動き（dash/charge/slash）＋角度（top-down/dutch）＋遠近（foreshortening）**で迫力を作る。
3. 1アングルにつき「エフェクト強め/弱め」をA/Bで回して、破綻しやすい境界を掴む。

## 4) 戦闘向きアングル構成（MECE：角度×レンズ×動き）

### A. 俯瞰（Top-down）× 長物武器（槍）：戦術的・冷静
- ねらい：戦場全体の配置/動線を把握しやすい。槍で直線構図が強調されシャープにまとまる。

#### 例プロンプト（原文）
```text
Quality: High-resolution anime-style illustration. Realistic characters. Cyberpunk-themed illustration.
Camera/Angle: Top-down.
Pose: Dynamic action pose with a spear. The spear is pointed at the camera.
Theme: A beautiful, fair-skinned 18-year-old woman wearing a skin-tight cyberpunk leather spacesuit, holding a spear.
Eyes: Green and gold gradient with white highlights.
Hair: Shiny white hair with pink undertones.
Background: A cyberpunk space base. A magic circle glows blue at her feet.
````

### B. 傾き（Dutch angle）× 近接：混乱・緊張感・乱戦

- ねらい：画面を傾けることで不安定さを視覚化。niji7では傾きが過剰になりにくく、近接戦と相性が良い、という所感。
    
#### 例プロンプト（原文）

```text
Camera/Angle: Dutch angle
Theme: A beautiful 18-year-old cyborg woman with fair skin and a tight, leather-framed cyberpunk mechanical body.
Pose: A dynamic action pose in a low stance with an energy sword. Iaijutsu stance.
```

### C. ダイナミックアングル × ワイド（Wide shot）× 爆発：スケール感・破壊力

- ねらい：ワイド＋爆発でスケールを作りつつ、キャラの動きとエフェクトが連動しやすいのが強み、という主張。
    

#### 例プロンプト（原文）

```text
Theme: A beautiful, fair-skinned 18-year-old woman wearing a skin-tight, leather cyberpunk space suit.
Pose: Dynamic action pose with an energy sword.
Camera/Angle: Dynamic action angle + Wide shot
Background: A huge explosion.
```

（同内容の順序違いも原文にあるため統合）

### D. 広角（Wide-angle lens）× ダッシュ：速度感・距離感の誇張

- ねらい：広角で背景が引き伸ばされ、突進/ダッシュの速度感を演出できる。

#### 例プロンプト（原文）

```text
Camera/Angle: Wide-angle lens, dynamic angle.
Theme: A beautiful, fair-skinned 18-year-old woman in a skin-tight, cyberpunk leather spacesuit sprints forward, her sprint activation glowing blue.
Background: A futuristic Shibuya Scramble Crossing illuminated by neon lights. Heavy motion blur.
```

### E. 魚眼（Fisheye lens）× 銃撃：歪みで銃口/腕の迫力を強調

- ねらい：画面全体の歪みで誇張。niji7では破綻しにくく、実験カットとして比較的安定、という所感。
    

#### 例プロンプト（原文）

```text
Quality: High-resolution anime-style illustration. Realistic characters. Cyberpunk-themed illustration. Fisheye lens.
Camera/Angle: Fisheye lens
Theme: A beautiful 18-year-old cyborg woman with a cyberpunk mechanical body and fair skin.
Pose: A dynamic action pose, crouched, firing a large laser from a futuristic ray gun.
```

---
## 5) 純プロンプト検証（記事最下部チェック枠：戦闘アクション一覧）

※原文は「英語/日本語」とあるが、ここでは **英語 → 意味（日本語）** の順に整理。

### 5-1. アクション短文（コピペ用）

```text
dual pistols, flying through the air, dynamic action
# → 2丁拳銃で空中を飛びながら戦闘

dual wielding pistols, mid-air combat, muzzle flash
# → 空中戦で2丁拳銃を乱射、マズルフラッシュ

high-speed charge, strong foreshortening
# → 高速突進、強い遠近感

jumping slash with energy blade, dramatic motion
# → エネルギーブレードで跳躍斬り、ダイナミックな動き

close combat clash, sparks flying
# → 近接戦の衝突、火花が散る演出

aerial combat above neon city, wide shot
# → ネオン都市上空での空中戦、ワイド構図

acrobatic flip attack, cinematic motion
# → アクロバティックな回転攻撃

sliding on the ground while firing, low stance
# → 地面を滑りながら射撃、低い姿勢

rapid melee combo, afterimage effect
# → 高速近接コンボ、残像エフェクト

slow motion gunfight, dramatic lighting
# → スローモーションの銃撃戦、ドラマチックな照明

mid-air kick attack, dynamic pose
# → 空中キック攻撃、ダイナミックなポーズ

battlefield chaos, multiple enemies
# → 戦場の混沌、複数の敵が入り乱れる状況
```

### 5-2. 例：遠近強調（foreshortening）テンプレ（原文の断片を整理）

```text
Camera/Angle: Strong foreshortening with a large energy sword pointing towards the camera. Dynamic range.
```
