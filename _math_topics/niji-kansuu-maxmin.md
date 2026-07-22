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
      y &= -x^2+4x+1 \\
      &= -(x^2-4x)+1 \\
      &= -\lbrace(x-2)^2-2^2\rbrace+1 \\
      &= -\lbrace(x-2)^2-4\rbrace+1 \\
      &= -(x-2)^2+4+1 \\
      &= -(x-2)^2+5
      \end{aligned}
      \]
      </div>
      よって, 軸の方程式は$x=2$である。
      このグラフは上に凸の放物線であるから,
      軸から遠い点が最小値, 軸に近い点が最大値である。  
      <div>
      \[
      \begin{aligned}
      x=5\text{のとき} & \text{最小値}\ y=-5^2+4\cdot{}5+1=-4 \\
      x=2\text{のとき} & \text{最大値}\ y=5
      \end{aligned}
      \]
      </div>
  - notation: 学園２０２５春２・大問３（２）
    mid: niji-tyouten-25s2
    q: |
      次の２次関数の頂点を求めよ。
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
      よって, 頂点$(2,\ -4)$
  - notation: ### 学園２０２４春２・大問３（２）###
    mid: niji-tyouten-24s2
    q: |
      次の２次関数の頂点を求めよ。
      \\[
        y = 2x^2 - 8x +6
      \\]
    a: |
      <div>
      \[
      \begin{aligned}
      y &= 2x^2-8x+6 \\
      &= 2(x^2-4x)+6 \\
      &= 2\lbrace{}(x-2)^2-2^2\rbrace{}+6 \\
      &= 2\lbrace{}(x-2)^2-4\rbrace{}+6 \\
      &= 2(x-2)^2-8+6 \\
      &= 2(x-2)^2-2 \\
      \end{aligned}
      \]
      </div>
      よって, 頂点$(2,\ -2)$
  - notation: ### 学園２０２３春２・大問３（１）###
    mid: niji-tyouten-23s2
    q: |
      次の２次関数の頂点を求めよ。
      \\[
        y = 3x^2 - 6x +2
      \\]
    a: |
      <div>
      \[
      \begin{aligned}
      y &= 3x^2-6x+2 \\
      &= 3(x^2-2x)+2 \\
      &= 3\lbrace{}(x-1)^2-1^2\rbrace{}+2 \\
      &= 3\lbrace{}(x-1)^2-1\rbrace{}+2 \\
      &= 3(x-1)^2-3+2 \\
      &= 3(x-1)^2-1 \\
      \end{aligned}
      \]
      </div>
      よって, 頂点$(1,\ -1)$
  - notation: ### 学園２０２２春２・大問３（１）###
    mid: niji-tyouten-22s2
    q: |
      次の２次関数の頂点を求めよ。
      \\[
        y = -x^2 - 2x +3
      \\]
    a: |
      <div>
      \[
      \begin{aligned}
      y &= -x^2-2x+3 \\
      &= -(x^2+2x)+3 \\
      &= -\lbrace{}(x+1)^2-1^2\rbrace{}+3 \\
      &= -\lbrace{}(x+1)^2-1\rbrace{}+3 \\
      &= -(x+1)^2+1+3 \\
      &= -(x+1)^2+4 \\
      \end{aligned}
      \]
      </div>
      よって, 頂点$(-1,\ 4)$
  - notation: ### 学園２０２１春２・大問３（１）###
    mid: niji-tyouten-21s2
    q: |
      次の２次関数の頂点を求めよ。
      \\[
        y = x^2 - 4x +1
      \\]
    a: |
      <div>
      \[
      \begin{aligned}
      y &= x^2-4x+1 \\
      &= (x-2)^2-2^2+1 \\
      &= (x-2)^2-4+1 \\
      &= (x-2)^2-3
      \end{aligned}
      \]
      </div>
      よって, 頂点$(2,\ -3)$
  - notation: ### 学園２０２０春２・大問３（１）###
    mid: niji-tyouten-20s2
    q: |
      次の２次関数の頂点を求めよ。
      \\[
        y = x^2 + 4x -2
      \\]
    a: |
      <div>
      \[
      \begin{aligned}
      y &= x^2+4x-2 \\
      &= (x+2)^2-2^2-2 \\
      &= (x+2)^2-4-2 \\
      &= (x+2)^2-6
      \end{aligned}
      \]
      </div>
      よって, 頂点$(-2,\ -6)$
  - notation: ### 学園２０１９春２・大問３（１）###
    mid: niji-tyouten-19s2
    q: |
      次の２次関数の頂点を求めよ。
      \\[
        y = x^2 -6x +5
      \\]
    a: |
      <div>
      \[
      \begin{aligned}
      y &= x^2-6x+5 \\
      &= (x-3)^2-3^2+5 \\
      &= (x-3)^2-9+5 \\
      &= (x-3)^2-4
      \end{aligned}
      \]
      </div>
      よって, 頂点$(3,\ -4)$
  - notation: ### 学園２０１８春２・大問３（１）###
    mid: niji-tyouten-18s2
    q: |
      次の２次関数の頂点を求めよ。
      \\[
        y = 2x^2 +4x -1
      \\]
    a: |
      <div>
      \[
      \begin{aligned}
      y &= 2x^2+4x-1 \\
      &= 2(x^2+2x)-1 \\
      &= 2\lbrace{}(x+1)^2-1^2\rbrace{}-1 \\
      &= 2\lbrace{}(x+1)^2-1\rbrace{}-1 \\
      &= 2(x+1)^2-2-1 \\
      &= 2(x+1)^2-3
      \end{aligned}
      \]
      </div>
      よって, 頂点$(-1,\ -3)$
  - notation: ### 学園２０１７春２・大問３（１）###
    mid: niji-tyouten-17s2
    q: |
      次の２次関数の頂点を求めよ。
      \\[
        y = x^2 -8x +12
      \\]
    a: |
      <div>
      \[
      \begin{aligned}
      y &= x^2-8x+12 \\
      &= (x-4)^2-4^2+12 \\
      &= (x-4)^2-16+12 \\
      &= (x-4)^2-4
      \end{aligned}
      \]
      </div>
      よって, 頂点$(4,\ -4)$
  - notation: ### 学園２０１６春２・大問３（１）###
    mid: niji-tyouten-16s2
    q: |
      次の２次関数の頂点を求めよ。
      \\[
        y = x^2 +6x +7
      \\]
    a: |
      <div>
      \[
      \begin{aligned}
      y &= x^2+6x+7 \\
      &= (x+3)^2-3^2+7 \\
      &= (x+3)^2-9+7 \\
      &= (x+3)^2-2
      \end{aligned}
      \]
      </div>
      よって, 頂点$(-3,\ -2)$
  - notation: ### 学園２０１５春２・大問３（１）###
    mid: niji-tyouten-15s2
    q: |
      次の２次関数の頂点を求めよ。
      \\[
        y = x^2 +4x +3
      \\]
    a: |
      <div>
      \[
      \begin{aligned}
      y &= x^2+4x+3 \\
      &= (x+2)^2-2^2+3 \\
      &= (x+2)^2-4+3 \\
      &= (x+2)^2-1
      \end{aligned}
      \]
      </div>
      よって, 頂点$(-2,\ -1)$
  - notation: ### 学園２０１４春２・大問３（１）###
    mid: niji-tyouten-14s2
    q: |
      次の２次関数の頂点を求めよ。
      \\[
        y = (x-1)^2 -4
      \\]
    a: |
      頂点$(1,\ -4)$
  - notation: ### 学園２０１３春２・大問３（２）###
    mid: niji-tyouten-13s2
    q: |
      次の２次関数の頂点を求めよ。
      \\[
        y = x^2 -4x +3
      \\]
    a: |
      <div>
      \[
      \begin{aligned}
      y &= x^2-4x+3 \\
      &= (x-2)^2-2^2+3 \\
      &= (x-2)^2-4+3 \\
      &= (x-2)^2-1
      \end{aligned}
      \]
      </div>
      よって, 頂点$(2,\ -1)$
  - notation: ### 学園２０１２春２・大問３（２）###
    mid: niji-tyouten-12s2
    q: |
      次の２次関数の頂点を求めよ。
      \\[
        y = -x^2 +6x -5
      \\]
    a: |
      <div>
      \[
      \begin{aligned}
      y &= -x^2+6x-5 \\
      &= -(x^2-6x)-5 \\
      &= -\lbrace{}(x-3)^2-3^2\rbrace{}-5 \\
      &= -\lbrace{}(x-3)^2-9\rbrace{}-5 \\
      &= -(x-3)^2+9-5 \\
      &= -(x-3)^2+4
      \end{aligned}
      \]
      </div>
      よって, 頂点$(3,\ 4)$
---
２次関数の頂点を求める問題です。基本は平方完成、解の公式を使ったり、微分を使ったり、いろいろな解き方で解けると楽しくなります。
あちこちで使う計算です。何度も手を動かして身につけてしまおう。
