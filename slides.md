---
theme: seriph
addons:
  - "@twitwi/slidev-addon-ultracharger"
addonsConfig:
  ultracharger:
    inlineSvg:
      markersWorkaround: false
    disable:
      - metaFooter
      - tocFooter
background: /perplexity_eye.jpeg
highlighter: shiki
routerMode: hash
lineNumbers: false

css: unocss
title: Научная визуализация данных
subtitle: Лекция 3. Зрительное восприятие и цвет
date: 17/11/2026
venue: ВШЭ
author: Алексей Болдырев
---

<br>
<br>

# <span style="font-size:28.0pt" v-html="$slidev.configs.title?.replaceAll(' ', '<br/>')"></span>
# <span style="font-size:28.0pt" v-html="$slidev.configs.subtitle?.replaceAll(' ', '<br/>')"></span>
# <span style="font-size:18.0pt" v-html="$slidev.configs.author?.replaceAll(' ', '<br/>')"></span>

<span style="font-size:18.0pt" v-html="$slidev.configs.date?.replaceAll(' ', '<br/>')"></span>

<div>
<br>
<br>
<span style="color:#b3b3b3ff; font-size: 11px; float: right;">Изображение: Perplexity. Запрос "Human eye at the center connecting visual perception, color, and data visualization"
</span>
</div>

<style>
  :deep(footer) { padding-bottom: 3em !important; }
</style>

---
src: ./slides/0_outline.md
---

---
src: ./slides/1_learning_outcomes.md
---

---
src: ./slides/0_intro.md
---

---
src: ./slides/2_comparison.md
---

---
src: ./slides/2_attention_takeaway.md
---

---
src: ./slides/2_accessibility.md
---

---
src: ./slides/3_color.md
---

---
src: ./slides/4_color_terminology.md
---

---
src: ./slides/4_color_models_takeaway.md
---

---
src: ./slides/4_categorical_takeaway.md
---

---
src: ./slides/5_summary.md
---

---
src: ./slides/0_end.md
---