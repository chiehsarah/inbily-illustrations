# 生图提示词模板

每张图单独生成。根据正文内容替换变量，不要把多张图拼在一起。

```text
Generate one standalone 16:9 horizontal Chinese article illustration in INBILY Xiaohei-style.

Visual DNA:
Pure white background. Minimalist black hand-drawn line art. Slightly wobbly pen lines. Lots of empty white space. Sparse red/orange/blue handwritten Chinese annotations. Clean absurd product-sketch feeling. Clear structure but not instructional. No gradients, no shadows, no paper texture, no complex background, no commercial vector style, no PPT infographic look, no brand poster, no cute mascot poster, no children's illustration, no realistic UI.

Recurring IP character required:
INBILY粉卫衣星钥少女, a simplified hand-drawn brand IP girl used as the core action subject. She has brown shoulder-length bob hair with slightly outward curled ends, airy bangs, one small ahoge hair tuft, large round brown eyes, light blush, restrained warm expression, bright pink oversized hoodie with a simple clear white INBILY mark, white shorts, a pink star-shaped keychain at the waist, white socks with pink stripes, and pink-white sneakers. Keep her simplified and sketch-like: black line art first, pink only as restrained character accents. She must perform the core conceptual action, not decorate the scene. Make her serious, focused, slightly deadpan and a little bizarre, not a commercial cute mascot.

Theme:
{正文配图主题}

Structure type:
{结构类型：Workflow / 系统局部 / 前后对比 / 角色状态 / 概念隐喻 / 方法分层 / 地图路线 / 小漫画分镜}

Core idea:
{这张图要表达的核心意思}

Composition:
{具体画面：INBILY IP 在哪里、正在做什么、主要物件是什么、信息如何流动}

Suggested elements:
{元素1} / {元素2} / {元素3} / {元素4}

Chinese handwritten labels:
{标注词1} / {标注词2} / {标注词3} / {标注词4} / {可选标注词5}

Color use:
Black for main line art, structures, objects, and labels. Pink only for the INBILY hoodie, shoes, star keychain, and tiny brand accents. Orange for main flow/path/arrows. Red only for key warnings/problems/results. Blue only for secondary notes or feedback/system state.

Constraints:
One image explains only one core structure. Keep the main subject around 40%-60% of the canvas. Preserve at least 35% blank white space. Use at most 5-8 short handwritten Chinese labels. Do not write a title in the top-left corner. Do not write the structure type on the image. Do not make it a formal diagram, course slide, brand poster, or dense explainer. Do not copy prior examples or reuse known case compositions unless explicitly requested; invent a fresh visual metaphor for this specific article. The image should feel strange, sparse, clever, and hand-drawn, while the INBILY IP remains recognizable.

Avoid:
No black monster. No black mascot. No unrelated mascot. No 3D. No photorealistic person. No glossy anime poster. No full pink background. No copied reference-card border or title. No oversized logo splash. No sexy styling. No toddler proportions. No malformed hands or backwards feet.
```

## 图像编辑提示

去掉左上角标题：

```text
Edit the provided image. Remove only the handwritten title "{要删除的文字}" and its underline from the top-left corner. Fill that area with the same clean white background, matching the surrounding blank paper. Preserve everything else exactly: INBILY character, labels, paths, line style, composition, aspect ratio, and image quality. Do not add any new text or objects.
```

增强怪诞感和动作主体：

```text
Regenerate this illustration with the same core meaning and simple layout, but make INBILY粉卫衣星钥少女 more central to the conceptual action. She should be doing the strange work that explains the idea, not standing beside the diagram. Keep the pure white background, sparse black hand-drawn line art, restrained pink character accents, and minimal red/orange/blue handwritten notes. Make it clean, sparse, deadpan, strange, and not a brand poster.
```
