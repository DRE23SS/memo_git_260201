# 【保存版】動画生成の精度を高めるプロンプトのコツ10選

## 1. アスペクト比（比率）の設定

- **キーワード**：16:9（横長）、9:16（縦長）、1:1（正方形）など
    
- **効果**：アスペクト比を指定すると構図が安定し、目的に合った映像を作りやすくなる
    
- **プロンプト例**：未来都市の夜景をドローンで撮影、アスペクト比**16:9**で映画的に仕上げる
    

## 2. 時間帯・季節の指定

- **キーワード**：夏の夕方、雨の夜、秋の夕焼け、冬の朝など
    
- **効果**：時間帯や季節を加えると光や色味が変わり、自然で雰囲気のある映像になる
    
- **プロンプト例**：**夏の夕方**、公園で子どもたちが遊んでいるシーンをオレンジ色の光で表現
    

## 3. 背景・環境設定の設定

- **キーワード**：教室、街中、未来的な研究所、田舎の神社など
    
- **効果**：舞台を指定することで場面が明確になり、余計な要素が入りにくくなる
    
- **プロンプト例**：にぎやかな**教室**で生徒たちがおしゃべりしているシーン
    

## 4. 被写体・キャラクターの指定

- **キーワード**：少年、宇宙飛行士、黒猫、老紳士など
    
- **効果**：主役を明確にすると焦点が定まり、表現したい人物像がはっきり出る
    
- **プロンプト例**：**宇宙飛行士**が月面を歩きながら宇宙空間を見上げているシーン
    

## 5. 動作・アクションの指定

- **キーワード**：歩く、走る、笑う、跳ぶ、踊るなど
    
- **効果**：行動を加えると映像が静止せず、動画らしい動きが自然に表現される
    
- **プロンプト例**：黒猫が庭を**走り抜け**、途中で**振り返って笑う**ような仕草をする
    

## 6. 照明・ライティングの設定

- **キーワード**：映画的な照明、ネオンライト、ゴールデンアワー、逆光など
    
- **効果**：光源や照明を指定すると雰囲気が大きく変わり、映像がドラマチックになる
    
- **プロンプト例**：夜の街で**ネオンライト**に照らされながら歩く人物を**逆光**で撮影
    

## 7. カメラワークの指定

- **キーワード**：ドローンショット、トラッキングショット、クローズアップ、パンなど
    
- **効果**：カメラの動きを指定すると臨場感が増し、演出効果を高められる
    
- **プロンプト例**：**トラッキングショット**でランナーを後ろから追いかけるシーン
    

## 8. カメラレンズ・画角の設定

- **キーワード**：広角レンズ、魚眼レンズ、望遠レンズなど
    
- **効果**：レンズや画角を指定すると遠近感やスケール感を自在にコントロールできる
    
- **プロンプト例**：**広角レンズ**で大都市の高層ビル群を下から見上げる映像
    

## 9. スタイル・質感の指定

- **キーワード**：リアル調、アニメ調、シネマ風、絵画風など
    
- **効果**：仕上がりの質感を決めると映像の世界観が統一され、印象がはっきりする
    
- **プロンプト例**：**アニメ調**で描かれた教室で、生徒たちが授業を受けているシーン
    

## 10. 映像パラメータ・演出要素の指定

- **キーワード**：スローモーション、ループ、分割画面、タイムラプスなど
    
- **効果**：演出効果を加えると完成度が高まり、編集済みのような映像になる
    
- **プロンプト例**：水しぶきが上がる瞬間を**スローモーション**で映したような構図

# 【Midjourney x Veo3】ひとり映画製作。映画監督レベルで確実に狙った動画を生成する方法。

**概要** Midjourneyで画像（キーフレーム）を作成し、Veo3を使って動画化する手法。 「海辺の風」をテーマにしたショート動画の制作フロー。

## 作りたい映像のコンセプトを考える

コンセプトを決めておくと、キーフレーム（動画の元になる画像）を作りやすいです。 今回は**海辺の風**をテーマにショート動画を制作します。

- **シーン1**：波打ち際。砂浜に寄せる波と夕日の反射。
    
- **シーン2**：海辺に立つ主人公の横顔。風で髪が揺れる。
    
- **シーン3**：裸足の足跡が波に消されていく。
    
- **シーン4**：真っ青な空と入道雲。
    
- **シーン5**：堤防に腰かけ、海を見つめる主人公の背中。
    
- **シーン6**：海沿いの道に止められた自転車と主人公の後ろ姿。
    
- **シーン7**：目を閉じ、波音を聴く主人公。
    
- **シーン8**：防波堤を歩く主人公の足元。
    
- **シーン9**：夕暮れの海に立つ主人公のシルエット。
    

## モデル・機材設定

**モデル**

- 画像生成：Midjourney（ミッドジャーニー）
    
- 主人公：ひとり（オムニリファレンスに使用）
    

**カメラやレンズ**

- **カメラプロンプト**：Sony FX3 / 35mm F1.4
    
- **トーン**：青とオレンジを多くする
    

---

## シーン別プロンプト

### シーン1：波打ち際

> **Prompt** A cinematic-style photograph taken from a low angle, almost touching the water surface. The foreground features reflections of sunset light on the wet sand, while gentle white waves roll in at the midground. In the background, the horizon glows orange under the setting sun. The image emphasizes a strong contrast between deep blue and warm orange tones, with vivid reflections and visible film grain texture. Shot on a Sony FX3 with a 35mm f/1.4 lens, capturing the mood of dusk with filmic realism. --ar 9:16

- **日本語訳** 水面ギリギリのローアングルから捉えた、シネマティックなスタイルの写真。前景には濡れた砂浜に反射する夕日の光が揺らめき、中景には白い波が穏やかに寄せている。背景には夕日に染まったオレンジの水平線が広がっている。色調は青とオレンジの強いコントラストが際立ち、強い反射とフィルム粒子が質感を豊かに演出している。Sony FX3 と 35mm F1.4レンズで撮影された、夕暮れ時の空気感を捉えたリアルな一枚。
    

### シーン2：主人公の横顔

> **Prompt** A cinematic side-profile photograph of an 18-year-old Japanese girl standing by the seaside. Her short black bob with blunt bangs flows gently in the wind, slightly translucent in the backlight. The foreground captures the shimmering strands of her hair, while the midground shows her face and shoulders. In the background, the horizon line where the sea meets the sky stretches out softly. The image is bathed in a nostalgic glow, with halation from the strong backlight adding a dreamy, emotional softness. She wears a white short-sleeved shirt, denim shorts, and white sneakers. Shot with a Sony FX3 and a 35mm f/1.4 lens wide open, the scene blends sharp detail with a film-like atmosphere. --ar 9:16 --oref https://[ID] --ow 75

### シーン3：足跡

> **Prompt** A cinematic top-down close-up shot of bare footprints in wet sand. The foreground captures the detailed texture of the sand with strong contrast, while gentle waves in the midground begin to wash over and erase the prints. In the background, soft reflections shimmer across the sea surface. Shot on a Sony FX3 with a 35mm f/1.4 lens, the image conveys a tactile and realistic coastal atmosphere under natural light. --ar 9:16

- **日本語訳** 濡れた砂に残された裸足の足跡を捉えた、俯瞰のクローズアップによるシネマティックな写真。前景では砂の質感が強調され、高コントラストで足跡の形が鮮明に表現されている。中景には、それをやさしく覆って消していく波が映り、背景には海面のぼんやりとした反射が広がっている。Sony FX3と35mm F1.4レンズで撮影されており、自然光の中でリアルで触感的な海辺の空気感を描いている。
    

### シーン4：空と入道雲

> **Prompt** A cinematic low-angle shot looking up at the summer sky, capturing the vivid atmosphere of the season. Cumulus clouds in the midground appear semi-transparent under intense sunlight, while the background reveals a clear, deep blue sky. The blue tones are rich and saturated, with strong highlights bringing out the brightness of the white clouds. Shot on a Sony FX3 with a 35mm f/1.4 lens at f/8, the image delivers crisp contrast and a refreshing sense of openness. --ar 9:16

- **日本語訳** 夏の空気感を切り取った、ローアングルから空を見上げるシネマティックな挿入カット。中景には強い日差しに照らされて透ける入道雲が浮かび、背景には澄んだ青空が広がっている。青は深く鮮やかに描かれ、白い雲のハイライトが明るさを強調している。Sony FX3 と 35mm F1.4、F8 で撮影されており、コントラストが高く、開放感のある構図が特徴。
    

### シーン5：主人公の背中

> **Prompt** A cinematic mid shot from behind, capturing an 18-year-old Japanese girl sitting on a seawall and gazing out at the ocean. Her black bob haircut and white short-sleeved shirt make her silhouette stand out against the vibrant blue sea and sky in the background. The foreground features the rough texture of the concrete seawall, while her relaxed posture and dangling legs suggest a moment of calm. Shot on a Sony FX3 with a 35mm f/1.4 lens, the image balances soft backlighting on the subject with crisp, vivid tones in the background, evoking a quiet summer afternoon. --ar 9:16 --oref https://[ID] --ow 75

### シーン6：自転車と後ろ姿

> **Prompt** A cinematic low-angle shot capturing a quiet seaside moment. In the foreground, a bicycle frame and grass sway in the wind. At midground, an 18-year-old Japanese girl stands barefoot with her back to the camera, gazing out at the ocean that stretches toward the horizon. She wears an open white shirt over denim shorts, her black bob and blunt bangs lightly tousled by the breeze. The scene is tinted in a mix of blue and orange tones, with minimal greens. Shot on a Sony FX3 with a 35mm f/1.4 lens, the image captures a calm, nostalgic summer mood by the sea. --ar 9:16 --oref https://[ID] --ow 75

- **日本語訳** 海沿いに止められた自転車と、その奥で静かに海を見つめる少女の後ろ姿をローアングルで捉えたシネマティックなカット。前景には自転車のフレームと、風に揺れる草が映り、中景には素足で立つ18歳の日本人女性の後ろ姿。彼女は黒髪ボブで前髪パッツン、白シャツを羽織り、デニムショートパンツを履き、スニーカーは脱いで砂浜に立っている。背景には水平線まで続く海が広がり、全体は青とオレンジ寄りの色調でまとめられ、緑のトーンは控えめに。Sony FX3 と 35mm F1.4レンズで撮影され、夏の静けさと開放感が美しく表現された一枚。
    

### シーン7：波音を聴く

> **Prompt** A cinematic bust-up shot of an 18-year-old Japanese girl standing by the sea, eyes gently closed as she touches her ear, immersed in the sound of waves. Her straight black bob and blunt bangs catch the backlight, with strands softly glowing. She wears a white shirt with rolled-up sleeves, her posture calm and reflective. In the background, the ocean surface shimmers with warm, diffused light. Shot on a Sony FX3 with a 35mm f/1.4 lens wide open, the scene emphasizes soft lighting, natural skin tones, and a nostalgic, dreamlike atmosphere. --ar 9:16 --oref https://[ID] --ow 75

- **日本語訳** 海辺で波の音に耳を澄ませる18歳の日本人女性を、逆光でバストアップに捉えたシネマティックな一枚。目を閉じて耳にそっと手を添え、風を感じるその姿は静かで穏やか。逆光に照らされた黒髪ボブが柔らかく透け、彼女のシルエットを優しく際立たせている。白シャツの袖を軽くまくっており、背景には光を受けてきらめく海面が広がる。Sony FX3 と 35mm F1.4 開放で撮影され、柔らかな光と自然な肌色が、どこか懐かしい夏の空気感を美しく演出している。
    

### シーン8：防波堤の足元

> **Prompt** A cinematic low-angle tracking shot focused on the feet of an 18-year-old Japanese girl walking along a seawall. Her white sneakers and sharp shadows move across the concrete surface, while the hem of her denim shorts flutters in the sea breeze. The midground shows the straight line of the seawall, and the background reveals a softly blurred expanse of ocean. Shot on a Sony FX3 with a 35mm f/1.4 lens, the image captures a strong contrast between sunlight and shadow, evoking a dynamic yet tranquil coastal moment. --ar 9:16

- **日本語訳** 防波堤の上を歩く18歳の日本人女性の足元を捉えた、ローアングルの横トラッキングショット。白いスニーカーとその影がコンクリートの上を通り過ぎ、デニムの裾が海風で揺れている様子が印象的。中景にはまっすぐ伸びる防波堤のラインが映り、背景にはぼんやりと広がる海面が広がっている。Sony FX3と35mm F1.4レンズで撮影され、光と影のコントラストが際立つ構図で、動きと静けさが共存する海辺の瞬間を描き出している。
    

### シーン9：夕暮れのシルエット

> **Prompt** A cinematic long shot capturing an 18-year-old Japanese girl as a small silhouette standing near the horizon. She is backlit by the golden hour sun, wearing a white short-sleeved shirt and denim shorts, with her black bob and blunt bangs subtly outlined. The background features the ocean glowing in deep orange and blue tones, as the sun begins to sink into the horizon. Shot on a Sony FX3 with a 35mm f/1.4 lens during golden hour, the scene includes visible film grain, adding a nostalgic, lingering atmosphere. --ar 9:16 --oref https://[ID] --ow 75

- **日本語訳** 夕暮れの海を背景に、18歳の日本人女性が小さなシルエットとして立つ姿をロングショットで捉えた、シネマティックな一枚。白の半袖シャツとデニムショートパンツを着た彼女は、夕日に背を向けて立ち、黒髪ボブと前髪パッツンの輪郭が光に浮かび上がっている。背景には沈みかけた太陽と、オレンジと青が溶け合うような海が広がっている。Sony FX3と35mm F1.4でゴールデンアワーに撮影され、フィルム粒子が余韻とノスタルジーを強調している。

# kkk