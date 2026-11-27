---
title: 小さくつくって、早く学ぶ
titleTemplate: '%s - sample'
author: takahiroaoki

theme: default
presenter: true
browserExporter: false
download: false
exportFileName: exported
export:
  format: pdf
  timeout: 30000
lineNumbers: true
record: false
contextMenu: false
wakeLock: true
monaco: false

colorSchema: light
aspectRatio: 16/9
canvasWidth: 980
transition: slide-left
themeConfig:
  primary: '#2563EB'
fonts:
  sans: 'Inter, Noto Sans Japanese'
  serif: 'Noto Serif, Noto Serif Japanese'
  mono: 'JetBrains Mono'
---

# 小さくつくって、
# <span class="text-teal-400">早く学ぶ。</span>

アイデアを、動く形にするための3つの習慣

<div class="abs-br m-6 text-sm opacity-60">SLIDEV SAMPLE · 2026</div>

---

# まず、仮説をひとつ

> 完璧な計画より、確かめられる問い。

<div class="grid grid-cols-3 gap-5 mt-10">
  <div class="rounded-xl bg-teal-500/10 p-5">
    <div class="text-3xl mb-3">①</div>
    <b>誰のため？</b>
    <p class="text-sm opacity-70">困りごとを具体的にする</p>
  </div>
  <div class="rounded-xl bg-blue-500/10 p-5">
    <div class="text-3xl mb-3">②</div>
    <b>何を変える？</b>
    <p class="text-sm opacity-70">届けたい価値を絞る</p>
  </div>
  <div class="rounded-xl bg-violet-500/10 p-5">
    <div class="text-3xl mb-3">③</div>
    <b>どう確かめる？</b>
    <p class="text-sm opacity-70">最小の実験を決める</p>
  </div>
</div>

---

# 学びのループを回す

<div class="h-4/5 text-align-center flex flex-col flex-justify-around">

<span>
```mermaid
flowchart LR
  A[つくる] --> B[見せる]
  B --> C[気づく]
  C --> D[直す]
  D --> A
```
</span>

<span>小さな一周を、何度も。スピードは学びの回数から生まれる。</span>
</div>

<!--
スライドには表れない発表者むけのノート。
-->

---

# まず動くものを見せよう

### 伝える → 試す → 直す

次の一歩は、今日できるサイズに。

```python {monaco}
import numpy as np

def AND(
    x1: int,
    x2: int,
) -> int:
    x = np.array([x1, x2])
    w = np.array([0.5, 0.5])
    b = -0.8
    tmp = np.sum(w*x) + b

    if tmp > 0:
        return 1
    else:
        return 0
```

<div class="abs-br m-6 text-sm opacity-60">THANK YOU · QUESTIONS?</div>
