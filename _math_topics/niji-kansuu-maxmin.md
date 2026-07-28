---
layout: math_topic
title: ２次関数の最大最小
subject: 数学I
unit: 2次関数
keywords: [2次関数, 平方完成, 頂点, 最大・最小]
problems:
  - notation: 学園２０２６春２・大問３（２）
    mid: niji-maxmin-26s2
    q: |
      次の２次関数について,
      $0 \leqq x \leqq 5$における最大値と最小値を求めよ。
      \\[
        y = -x^2 + 4x + 1
      \\]
    a: |
      <div>
      \[
      \begin{aligned}
      y &= \colorbox{aqua}{$-$}x^2+4x+1 && \text{\scriptsize \color{gray}（与えられた式）} \\
      &= -(x^2-4x)+1 && \text{\scriptsize \color{gray}（$x^2$の係数 $-1$ で括る）} \\
      &= -\lbrace(x-2)^2-2^2\rbrace+1 && \text{\scriptsize \color{gray}（$x$の係数 $4$ の半分の$2$を使って平方完成）} \\
      &= -\lbrace(x-2)^2-4\rbrace+1 && \text{\scriptsize \color{gray}（$2^2$ を計算）} \\
      &= -(x-2)^2+4+1 && \text{\scriptsize \color{gray}（中括弧をはずす）} \\
      &= -(x-2)^2+5 && \text{\scriptsize \color{gray}（定数項を整理）}
      \end{aligned}
      \]
      </div>
      よって, 軸の方程式は$x=2$である。
      このグラフは上に凸の放物線であるから,
      軸から遠い点が最小値, 軸に近い点が最大値である。
      <br />
      $x=5$のとき　最小値　$y=-5^2+4\cdot{}5+1=-4$
      <br />
      $x=2$のとき　最大値　$y=5$
  - notation: 学園２０２５春２・大問３（２）
    mid: niji-tyouten-25s2
    q: |
      次の２次関数について,
      $0 \leqq x \leqq 5$における最大値と最小値を求めよ。
      \\[
        y = x^2 - 4x
      \\]
    a: |
      <div>
      \[
      \begin{aligned}
      y &= x^2-4x \\
      &= (x-2)^2-2^2 \\
      &= (x-2)^2-4
      \end{aligned}
      \]
      </div>
      よって, 軸の方程式は$x=2$である。
      このグラフは下に凸の放物線であるから,
      軸から遠い点が最大値, 軸に近い点が最小値である。
      <br />
      $x=5$のとき　最大値　$y=5^2-4\cdot{}5=5$
      <br />
      $x=2$のとき　最小値　$y=-4$
  - notation: 学園２０２４春２・大問３（２）
    mid: niji-tyouten-24s2
    q: |
      次の２次関数について,
      $0 \leqq x \leqq 5$における最大値と最小値を求めよ。
      \\[
        y = 2x^2 - 8x +6
      \\]
    a: |
      <div>
      \[
      \begin{aligned}
      y &= 2x^2-8x+6 \\
      &= 2(x^2-4x)+6 \\
      &= 2\lbrace(x-2)^2-2^2\rbrace+6 \\
      &= 2\lbrace(x-2)^2-4\rbrace+6 \\
      &= 2(x-2)^2-8+6 \\
      &= 2(x-2)^2-2
      \end{aligned}
      \]
      </div>
      よって, 軸の方程式は$x=2$である。
      このグラフは下に凸の放物線であるから,
      軸から遠い点が最大値, 軸に近い点が最小値である。
      <br />
      $x=5$のとき　最大値　$y=2\cdot{}5^2-8\cdot{}5+6=16$
      <br />
      $x=2$のとき　最小値　$y=-2$
  - notation: 学園２０２３春２・大問３（１）
    mid: niji-tyouten-23s2
    q: |
      次の２次関数について,
      $3 \leqq x \leqq 5$における最大値と最小値を求めよ。
      \\[
        y = 3x^2 - 6x +2
      \\]
    a: |
      <div>
      \[
      \begin{aligned}
      y &= 3x^2-6x+2 \\
      &= 3(x^2-2x)+2 \\
      &= 3\lbrace(x-1)^2-1^2\rbrace+2 \\
      &= 3\lbrace(x-1)^2-1\rbrace+2 \\
      &= 3(x-1)^2-3+2 \\
      &= 3(x-1)^2-1
      \end{aligned}
      \]
      </div>
      よって, 軸の方程式は$x=1$である。
      このグラフは下に凸の放物線であるから,
      軸から遠い点が最大値, 軸に近い点が最小値である。
      <br />
      $x=5$のとき　最大値　$y=3\cdot{}5^2-6\cdot{}5+2=47$
      <br />
      $x=3$のとき　最小値　$y=3\cdot{}3^2-6\cdot{}3+2=11$
---
２次関数の頂点を求める問題です。基本は平方完成、解の公式を使ったり、微分を使ったり、いろいろな解き方で解けると楽しくなります。
あちこちで使う計算です。何度も手を動かして身につけてしまおう。
