# 电商商品图提示词合集

可以直接复制的商品图提示词：主图、场景图、广告创意、模特图、改图。每条都配了它真实生成出来的图，先看效果再动手。

**共 20 条**（文生图 20 条、改图 0 条）· 更新于 2026-11-24 · 每周新增

[English](README.md) · [许可](LICENSE)

## 怎么用

1. 挑一条，原样复制。
2. 把商品名称、颜色、材质换成你的；背景、光线和最后那句“不要文字 / 不要标志”保留。
3. 任何能写文字提示词的生图模型都能用（GPT Image、Nano Banana、即梦 / Seedream、Midjourney、Flux 等）。不同模型出图不同，示例图只代表一次真实结果。
4. “改图”类要先上传你自己的照片，再粘贴提示词。

## 这些提示词的共同写法

- **先写商品、写明无品牌**：颜色、材质、件数说清楚。
- **再写背景与布景**：无缝浅灰背景、浅色石台、亚麻布。
- **写光线**：柔和棚拍光、侧逆光、暖色轮廓光。
- **写要看清的细节**：编织纹理、缝线、釉色变化、真实接触阴影。
- **写构图**：整件入镜、左侧留白放文案。
- **最后一句排除项**：不要人物、文字、标志、可识别的品牌设计。
- **改图要写哪些不能变**：商品本身、角度、光线方向保持不变。

## 目录

- 01 商品主图（纯色 / 白底）（5 条）· [分类文件](prompts/01-clean-catalog.md)
- 02 场景图与俯拍（4 条）· [分类文件](prompts/02-lifestyle.md)
- 03 广告创意图（5 条）· [分类文件](prompts/03-ad-creative.md)
- 04 多场景套图与节日礼盒（2 条）· [分类文件](prompts/04-mockup-holiday.md)
- 05 模特图（2 条）· [分类文件](prompts/05-on-model.md)
- 07 店铺海报（带中文字）（2 条）· [分类文件](prompts/07-shop-poster.md)

## 01 商品主图（纯色 / 白底）

列表主图：单个商品、无缝纯色背景、柔和均匀的光、真实的接触阴影。

### Ceramic Bowl Collection

<img src="images/01-clean-catalog-ceramic-bowls.webp" alt="White, clay-pink and moss-green ceramic bowls on a light-gray studio background" width="420">

```text
Create a clean catalog photograph of three original handmade ceramic bowls in chalk white, clay pink and moss green, arranged at different heights on a seamless light-gray background. Show glaze variation and believable contact shadows, crisp edges, broad softbox lighting. No food, people, text, logos or recognizable branded patterns.
```

- 类型：文生图
- 比例：`1:1`
- 来源页预设模型：`gpt-image-2`
- 来源：`image2ai.cloud/templates/product-photos`

### Trail Backpack Detail

<img src="images/01-clean-catalog-trail-backpack.webp" alt="Rust-orange hiking backpack on a stone plinth against a muted blue background" width="420">

```text
Photograph a single unbranded rust-orange hiking backpack standing on a pale stone studio plinth. Three-quarter view, believable woven fabric, visible stitching, straps and zipper pulls, soft directional light and a muted blue background. Keep the entire bag inside the frame. No people, labels, text, logos or recognizable branded design.
```

- 类型：文生图
- 比例：`3:4`
- 来源页预设模型：`gpt-image-2`
- 来源：`image2ai.cloud/templates/product-photos`

### 竹编收纳篮主图

<img src="images/01-clean-catalog-bamboo-basket.webp" alt="竹编收纳篮置于浅色背景上，呈现竹条纹理与编织细节" width="420">

```text
原创电商商品摄影，一只无品牌的浅色竹编收纳篮放在米白无缝背景上，四分之三视角，完整展示篮口、提手和细密编织纹理，篮内只放一块折叠素色棉布，柔和棚拍光，真实接触阴影，画面干净。不要人物、文字、标签、品牌标志、水印或可识别的品牌专属造型。
```

- 类型：文生图
- 比例：`1:1`
- 来源页预设模型：`gpt-image-2`
- 来源：`image2ai.cloud/zh/templates/product-photos`

### 手工茶壶细节图

<img src="images/01-clean-catalog-clay-teapot.webp" alt="手工茶壶的壶身、壶嘴与釉面细节" width="420">

```text
原创商品摄影，一把无品牌的紫砂小茶壶放在浅灰石台上，壶盖正常合拢，壶嘴与把手完整入镜，侧后方柔光表现细腻砂粒和温润质感，背景为低饱和暖灰，不摆茶杯，不加装饰文字。不要人物、印章、款识、品牌标志、水印或知名器型的直接复制。
```

- 类型：文生图
- 比例：`3:4`
- 来源页预设模型：`gpt-image-2`
- 来源：`image2ai.cloud/zh/templates/product-photos`

### 冰淇淋商品静物

<img src="images/01-clean-catalog-ice-cream-spoon.webp" alt="极简商品图：银色勺子上一球粉色草莓冰淇淋，暖米色纯色背景" width="420">

```text
极简静物商品图：银色勺子上一球粉色草莓冰淇淋，暖米色纯色背景，柔和侧光，浅景深，干净的电商风格
```

- 类型：文生图
- 比例：`3:4`
- 来源页预设模型：`nano-banana-2`
- 来源：`image2ai.cloud/zh/templates/product-photos`

## 02 场景图与俯拍

把商品放进使用场景或布景里：俯拍、室内、氛围光。

### Handmade Soap Flat Lay

<img src="images/02-lifestyle-soap-flat-lay.webp" alt="Three oat soap bars on ivory linen with scattered oats and a wooden tray" width="420">

```text
Create an original overhead product photograph of three unbranded handmade oat soap bars on ivory linen, with scattered oats and a small wooden tray. Show the cut texture clearly, soft morning side light, warm neutral colors, generous space between objects. No people, packaging text, logos, watermarks or recognizable branded shapes.
```

- 类型：文生图
- 比例：`1:1`
- 来源页预设模型：`gpt-image-2`
- 来源：`image2ai.cloud/templates/product-photos`

### Sculptural Table Lamp

<img src="images/02-lifestyle-table-lamp.webp" alt="Cream pleated table lamp with a walnut base glowing against a dusk wall" width="420">

```text
Create an original interior product photograph of an unbranded sculptural table lamp with a cream pleated shade and walnut base on a simple side table. Warm lamp glow against a cool dusk wall, realistic fabric and wood grain, restrained styling, empty space to the left. No people, lettering, logos or recognizable designer-product replicas.
```

- 类型：文生图
- 比例：`4:3`
- 来源页预设模型：`gpt-image-2`
- 来源：`image2ai.cloud/templates/product-photos`

### Perfume on wet stones

<img src="images/02-lifestyle-perfume-wet-stones.webp" alt="Unbranded amber perfume bottle on wet black stones with warm rim light and a teal glow" width="420">

```text
Unbranded amber glass perfume bottle on wet black stones, gentle ripples, warm rim light and teal background glow, luxury ad look, empty space on the left for copy
```

- 类型：文生图
- 比例：`16:9`
- 来源页预设模型：`nano-banana-pro`
- 来源：`image2ai.cloud/templates/product-photos`

### 原木文具俯拍

<img src="images/02-lifestyle-wooden-stationery.webp" alt="原木文具整齐排列的俯拍静物" width="420">

```text
原创电商俯拍图，一套无品牌原木文具整齐摆在暖白桌面上，包括木尺、无字封面的线装笔记本、素色铅笔和小号木笔筒，各物件之间留出清晰间隔，柔和窗光，真实木纹，克制的米棕配色。尺面不写数字，笔记本与铅笔不写字，不要人物、品牌标志或水印。
```

- 类型：文生图
- 比例：`4:3`
- 来源页预设模型：`gpt-image-2`
- 来源：`image2ai.cloud/zh/templates/product-photos`

## 03 广告创意图

飞溅、爆炸图、风格化静物，用于广告和首屏横幅。

### Protein shake splash ad

<img src="images/03-ad-creative-protein-shake-splash.webp" alt="Matte blue "PEAKLINE" protein shake bottle leaning into a creamy milk splash with blueberries" width="420">

```text
Hyper-real product ad: a matte blue protein shake bottle labeled "PEAKLINE" leaning into a creamy milk splash with blueberries, condensation drops, studio light
```

- 类型：文生图
- 比例：`3:4`
- 来源页预设模型：`gpt-image-2`
- 来源：`image2ai.cloud/templates/product-photos`

### Exploded headphones

<img src="images/03-ad-creative-exploded-headphones.webp" alt="Exploded view of unbranded over-ear headphones with parts floating in alignment on white" width="420">

```text
Exploded view of unbranded over-ear headphones: ear cups, drivers, cushions, circuit board and screws floating in perfect alignment on a white seamless background
```

- 类型：文生图
- 比例：`1:1`
- 来源页预设模型：`nano-banana-pro`
- 来源：`image2ai.cloud/templates/product-photos`

### 气泡酒飞溅广告

<img src="images/03-ad-creative-cider-splash.webp" alt="绿色玻璃瓶苹果气泡酒立在冰块和青苹果片中，酒液向四周飞溅的商品广告图" width="420">

```text
苹果气泡酒商品广告：绿色玻璃瓶立在冰块和青苹果片中，酒液向四周飞溅，亮绿色背景，高速摄影质感，瓶身不出现文字
```

- 类型：文生图
- 比例：`9:16`
- 来源页预设模型：`nano-banana-pro`
- 来源：`image2ai.cloud/zh/templates/product-photos`

### 口红甜品挞静物

<img src="images/03-ad-creative-lipstick-tart.webp" alt="复古静物广告：红格子桌布上的樱桃甜品挞，两支红色口红插在奶油上，天蓝色背景" width="420">

```text
复古静物广告：红格子桌布上一只樱桃甜品挞，两支红色口红插在奶油上，红丝带和樱桃散落，天蓝色背景，明亮硬光
```

- 类型：文生图
- 比例：`4:3`
- 来源页预设模型：`nano-banana-2`
- 来源：`image2ai.cloud/zh/templates/product-photos`

### 折叠雨伞雨滴广告

<img src="images/03-ad-creative-umbrella-raindrops.webp" alt="带有雨滴的折叠雨伞商品广告图" width="420">

```text
原创商品广告，一把无品牌的深青色折叠雨伞完全撑开，伞柄朝下，完整悬置在浅蓝灰背景中央，伞面布料纹理清晰，少量晶莹雨滴附着，斜向柔光表现防雨质感，构图简洁可信，不做液体飞溅。不要人物、文字、品牌标志、复杂花纹或水印。
```

- 类型：文生图
- 比例：`3:4`
- 来源页预设模型：`gpt-image-2`
- 来源：`image2ai.cloud/zh/templates/product-photos`

## 04 多场景套图与节日礼盒

一张图里出同一商品的多个场景，以及节日礼盒主图。

### Skincare mockup grid

<img src="images/04-mockup-holiday-skincare-mockup-grid.webp" alt="Grid of product mockups for a frosted sage-green "VERDA" dropper bottle on stone, in water and with botanicals" width="420">

```text
3x3 grid of designer mockups for one frosted sage-green dropper bottle labeled "VERDA": on stone, in water, with botanicals, in hand, flat lay
```

- 类型：文生图
- 比例：`3:4`
- 来源页预设模型：`nano-banana-2`
- 来源：`image2ai.cloud/templates/product-photos`

### 中秋月饼礼盒主图

<img src="images/04-mockup-holiday-mooncake-gift-box.webp" alt="深红色中秋月饼礼盒电商主图，盒里六个金黄月饼，背景圆月，金色书法“月满人团圆”" width="420">

```text
中秋月饼礼盒电商主图：深红礼盒配金色云纹，六个金黄月饼，切开一个看到莲蓉和咸蛋黄，背景圆月和桂花，金色书法“月满人团圆”
```

- 类型：文生图
- 比例：`1:1`
- 来源页预设模型：`nano-banana-2`
- 来源：`image2ai.cloud/zh/templates/product-photos`

## 05 模特图

美妆特写，以及把你的衣服穿到已有的模特照片上。

### Lipstick beauty close-up

<img src="images/05-on-model-lipstick-beauty-closeup.webp" alt="Beauty ad close-up of a model with short wet-look blonde hair holding a silver lipstick near her lips" width="420">

```text
High-end beauty ad close-up: a model with wet-look short blonde hair and freckles holds a silver lipstick near her glossy lips, soft frontal light, off-white background
```

- 类型：文生图
- 比例：`16:9`
- 来源页预设模型：`nano-banana-2`
- 来源：`image2ai.cloud/templates/product-photos`

### 水光肌美妆特写

<img src="images/05-on-model-lipstick-beauty-closeup-zh.webp" alt="美妆广告特写：短发女生手拿口红贴近嘴唇，皮肤水润，米白背景" width="420">

```text
美妆广告特写：短发女生手拿口红贴近嘴唇，皮肤水润有光泽，米白背景，柔和正面光，干净高级
```

- 类型：文生图
- 比例：`16:9`
- 来源页预设模型：`nano-banana-2`
- 来源：`image2ai.cloud/zh/templates/product-photos`

## 07 店铺海报（带中文字）

画面里直接出标题文字的促销海报。

### 新中式春茶海报

<img src="images/07-shop-poster-spring-tea-poster.webp" alt="新中式茶饮海报：青瓷杯里冒热气的绿茶，宣纸底上书法标题“春茶上新”和红色印章" width="420">

```text
新中式茶饮海报：青瓷杯里的绿茶冒着热气，米色宣纸背景，几片茶叶和一枝梅花，书法大标题“春茶上新”，小字“明前绿茶 · 每日现泡”，红色印章点缀，大量留白
```

- 类型：文生图
- 比例：`3:4`
- 来源页预设模型：`gpt-image-2`
- 来源：`image2ai.cloud/zh/templates/posters`

### 夏日冰粉新品海报

<img src="images/07-shop-poster-summer-jelly-poster.webp" alt="青花瓷碗里的红糖冰粉，大字“冰粉上新”" width="420">

```text
夏日甜品店新品海报：青花瓷碗里一份红糖冰粉，配山楂碎、葡萄干和花生碎，碗边冒着冷气，背景是竹帘和绿荷叶，大字“冰粉上新”，小字“一碗清凉 · 12 元”，清爽蓝绿配色
```

- 类型：文生图
- 比例：`3:4`
- 来源页预设模型：`gpt-image-2`
- 来源：`image2ai.cloud/zh/templates/posters`

## 示例从哪来

本仓库所有示例图和提示词都取自 https://image2ai.cloud/zh/ 站上公开的示例（模板页、工具页、首页示例墙），提示词逐字照抄，没有改写，也没有为本仓库另外生成。“来源页预设模型”是来源页为这条提示词预填的模型。改图类的输入图是站上示例自带的输入图。每张图的来源页、原图地址和 SHA-256 见 [data/sources.md](data/sources.md)。

## 许可

提示词文字：CC0 1.0，随意复制改写。图片：见 [LICENSE](LICENSE)。
