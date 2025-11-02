# Krita AI Diffusion Workflows

## t2i_KAD.json
- テキストから画像を生成するKrita AI Diffusion用のワークフロー  
  *Workflow for generating images from text with Krita AI Diffusion*

---

## CN_KAD.json
- 標準以外のコントロールネットをKrita AI Diffusionで使うためのワークフロー  
- Anytest実装用カスタマイズ  
  *Workflow for using non-standard ControlNet in Krita AI Diffusion*  
  *Customized for Anytest implementation*

### 解説動画 / Tutorial Video
- [Krita AI Diffusion カスタムグラフ完全解説 未実装Anytestを動かす！  
  Using Anytest in Krita AI Diffusion via Custom Graphs](https://youtu.be/NPfkGk0uhJU)

### 使用モデル / Model
- ControlNet "Anytest"  
  [Download site](https://huggingface.co/2vXpSwA7/iroiro-lora/tree/main/test_controlnet2)

---

## WAN2.2_i2v_all_in_one_KAD.json
- Krita AI DiffusionでWAN2.2 i2vを使うためのワークフロー  
- 下記のオールインワンモデルを使用  
  *Workflow for using WAN2.2 i2v with Krita AI Diffusion*  
  *Uses the all-in-one model below*

### 解説動画 / Tutorial Video
- [Krita AI DiffusionとWAN2.2で快適動画生成 ：カスタムグラフで画像から動画生成　完全解説](https://youtu.be/NyBXv8MM4QU)

### 使用モデル / Models
- WAN2.2-14B-Rapid-AllInOne  
  [Download site](https://huggingface.co/Phr00t/WAN2.2-14B-Rapid-AllInOne)

- clip_vision_vit_h.safetensors  
  [Download site](https://huggingface.co/lllyasviel/misc/tree/main)

## Anytest_Region_KAD.json
- AnytestとRegionを組み合わせて、**スケッチのレイアウトを反映しつつ、領域ごとに別のプロンプトを適用できるワークフロー**  
- 複数キャラクターの描き分けや、背景と人物の差異を明確にしたい場合に有効  
*Workflow for combining Anytest with Region support in Krita AI Diffusion.  
Allows sketch layout control with region-specific prompts for multi-character compositions.*

### 解説動画 / Tutorial Video
- Krita AI Diffusion カスタムグラフ上級講座：Anytest × Regionを組み合わせた画像生成  
  ※ 公開準備中

### 使用モデル / Model
- ControlNet "Anytest"  
  [Download site](https://huggingface.co/2vXpSwA7/iroiro-lora/tree/main/test_controlnet2)

