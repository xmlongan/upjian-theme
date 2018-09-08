---
title: "Math1"
date: 2018-08-09T22:52:58+08:00
linktitle: counting
menu:
  main:
    title: "math counting"
    parent: "数学"
---

<div class = "w3-container">
<h3 class="w3-center">幂数、无理数（非比例数）</h3>

<hr>
<h3>1. 幂数（power function）</h3>
<p>在乘法的运算中，常出现同一数字多次相乘的情况。为了熟练处理这样的计算，幂数
  被定义为</p>
\begin{equation}\label{def_power}
  a^n \triangleq \quad \stackrel{n\text{个}a\text{相乘}}
  {\overbrace{a\times\cdots\times a}}
\end{equation}

<h4>几条运算法则</h4>
<table class="w3-table-all w3-centered w3-card-4">
  <tr>
    <td>a<sup>m</sup>&times;a<sup>n</sup> = a<sup>m+n</sup></td>
    <td style="width:12%;"><a class="w3-btn w3-green w3-round" href="#">证明 »</a></td>
  </tr>
  <tr>
    <td>a<sup>m</sup>&divide;a<sup>n</sup> = a<sup>m-n</sup></td>
    <td> <a class="w3-btn w3-green w3-round" href="#">证明 »</a></td>
  </tr>
  <tr>
    <td>(a<sup>m</sup>)<sup>n</sup> = a<sup>m&times;n</sup></td>
    <td> <a class="w3-btn w3-round" href="#">证明 »</a></td>
  </tr>
  <tr>
    <td>a<sup>n</sup>&times;b<sup>n</sup> = (a&times;b)<sup>n</sup></td>
    <td> <a class="w3-btn w3-round" href="#">证明 »</a></td>
  </tr>
  <tr>
    <td>a<sup>n</sup>&divide;b<sup>n</sup> = (a&divide;b)<sup>n</sup></td>
    <td><a class="w3-btn w3-round" href="#">证明 »</a></td>
  </tr>
</table>

<hr>
<h3>2. 平方（square）和开方（square root）</h3>
<h4>平方（square）</h4>
<p>幂数中最常见的是，同一个数字相乘2次，这就是平方。</p>
<table class="w3-table-all w3-centered w3-card-4">
  <tr>
    <td>1<sup>2</sup></td><td>2<sup>2</sup></td><td>3<sup>2</sup></td><td>4<sup>2</sup></td><td>5<sup>2</sup></td>
    <td>6<sup>2</sup></td><td>7<sup>2</sup></td><td>8<sup>2</sup></td><td>9<sup>2</sup></td><td>10<sup>2</sup></td>
  </tr>
  <tr>
    <td>1</td><td>4</td><td>9</td><td>16</td><td>25</td>
    <td>36</td><td>49</td><td>64</td><td>81</td><td>100</td>
  </tr>
</table>
<p>上面是1-10各自平方的值，更一般地是，对任意数\(a\)，其平方为</p>
\[a^2\]
<div class="w3-container w3-card-2 w3-pale-green w3-leftbar w3-border-green">
  <p>
    任何整数的平方，仍然是整数；
    <br>
    任何比例数的平方，仍然是比例数；
  </p>
</div>
<br>

<h4>开方（square root）</h4>
<p>平方的思路是，从一个已知数出发，计算其平方值。开方的思路相反，已知平方值，
  计算被平方的数。</p>
<table class="w3-table-all w3-centered w3-card-4">
  <tr class="w3-teal">
    <th>开方</th><th class="w3-border-right" style="width:25%;">\(x\)</th><th>开方</th><th style="width:25%;">\(x\)</th>
  </tr>
  <tr>
    <td>x<sup>2</sup>=1</td><td class="w3-border-right">1</td><td>x<sup>2</sup>=2</td><td>?</td>
  </tr>
  <tr>
    <td>x<sup>2</sup>=4</td><td class="w3-border-right">2</td><td>x<sup>2</sup>=3</td><td>?</td>
  </tr>
  <tr>
    <td>x<sup>2</sup>=9</td><td class="w3-border-right">3</td><td>x<sup>2</sup>=5</td><td>?</td>
  </tr>
  <tr>
    <td>x<sup>2</sup>=16</td><td class="w3-border-right">4</td><td>x<sup>2</sup>=6</td><td>?</td>
  </tr>
  <tr>
    <td>x<sup>2</sup>=25</td><td class="w3-border-right">5</td><td>x<sup>2</sup>=7</td><td>?</td>
  </tr>
  <tr>
    <td>x<sup>2</sup>=36</td><td class="w3-border-right">6</td><td>x<sup>2</sup>=8</td><td>?</td>
  </tr>
  <tr>
    <td>x<sup>2</sup>=49</td><td class="w3-border-right">7</td><td>x<sup>2</sup>=10</td><td>?</td>
  </tr>
  <tr>
    <td>x<sup>2</sup>=64</td><td class="w3-border-right">8</td><td>x<sup>2</sup>=11</td><td>?</td>
  </tr>
  <tr>
    <td>x<sup>2</sup>=81</td><td class="w3-border-right">9</td><td>x<sup>2</sup>=12</td><td>?</td>
  </tr>
  <tr>
    <td>x<sup>2</sup>=100</td><td class="w3-border-right">10</td><td>x<sup>2</sup>=13</td><td>?</td>
  </tr>
</table>
<p>上表中，第一列的开方很容易，x有确切的值；第三列的开方却不容易，我们不知道
  x确切的值。为了便于书写开方后的值，我们引入下面的记号：</p>
  \[\sqrt{a}\]
<p>所以，上表可以写成：</p>
<table class="w3-table-all w3-centered w3-card-4">
  <tr class="w3-teal">
    <th>开方</th><th class="w3-border-right" style="width:25%;">\(x\)</th><th>开方</th><th style="width:25%;">\(x\)</th>
  </tr>
  <tr>
    <td>x<sup>2</sup>=1</td><td class="w3-border-right">\(\sqrt{1}\)</td><td>x<sup>2</sup>=2</td><td>\(\sqrt{2}\)</td>
  </tr>
  <tr>
    <td>x<sup>2</sup>=4</td><td class="w3-border-right">\(\sqrt{4}\)</td><td>x<sup>2</sup>=3</td><td>\(\sqrt{3}\)</td>
  </tr>
  <tr>
    <td>x<sup>2</sup>=9</td><td class="w3-border-right">\(\sqrt{9}\)</td><td>x<sup>2</sup>=5</td><td>\(\sqrt{5}\)</td>
  </tr>
  <tr>
    <td>x<sup>2</sup>=16</td><td class="w3-border-right">\(\sqrt{16}\)</td><td>x<sup>2</sup>=6</td><td>\(\sqrt{6}\)</td>
  </tr>
  <tr>
    <td>x<sup>2</sup>=25</td><td class="w3-border-right">\(\sqrt{25}\)</td><td>x<sup>2</sup>=7</td><td>\(\sqrt{7}\)</td>
  </tr>
  <tr>
    <td>x<sup>2</sup>=36</td><td class="w3-border-right">\(\sqrt{36}\)</td><td>x<sup>2</sup>=8</td><td>\(\sqrt{8}\)</td>
  </tr>
  <tr>
    <td>x<sup>2</sup>=49</td><td class="w3-border-right">\(\sqrt{49}\)</td><td>x<sup>2</sup>=10</td><td>\(\sqrt{10}\)</td>
  </tr>
  <tr>
    <td>x<sup>2</sup>=64</td><td class="w3-border-right">\(\sqrt{64}\)</td><td>x<sup>2</sup>=11</td><td>\(\sqrt{11}\)</td>
  </tr>
  <tr>
    <td>x<sup>2</sup>=81</td><td class="w3-border-right">\(\sqrt{81}\)</td><td>x<sup>2</sup>=12</td><td>\(\sqrt{12}\)</td>
  </tr>
  <tr>
    <td>x<sup>2</sup>=100</td><td class="w3-border-right">\(\sqrt{100}\)</td><td>x<sup>2</sup>=13</td><td>\(\sqrt{13}\)</td>
  </tr>
</table>
<div class="w3-container w3-leftbar w3-pale-green w3-border-green w3-card-4">
  <p>
    任何整数的开方，不一定还是整数；
    <br>
    任何比例数的开方，不一定还是比例数。
  </p>
</div>

<hr>
<h3>3. \(\sqrt{2}\)到底是多少呢？</h3>
<div class="w3-container w3-card-4">
  <p>
    假设存在整数n和m，使得
  </p>
  \[\sqrt{2} = \frac{n}{m}\]
  <p>且 \(\frac{n}{m}\) 不可约。那么，有如下推导</p>
  \begin{align*}
   \sqrt{2} &= \frac{n}{m} \\
   2 &= \frac{n^2}{m^2} \\
   2m^2 &= n^2
  \end{align*}
  <p>因为\(2m^2\)是偶数，也即\(n^2\)是偶数，从而n也是偶数（偶数的平方是
    偶数，奇数的平方是奇数）。从而n可以写成</p>
    \[n = 2k\]
  <p>其中k是另外一个整数，从而</p>
  \begin{align*}
   2m^2 &= (2k)^2 \\
   2m^2 &= 4k^2 \\
    m^2 &= 2k^2
  \end{align*}
  从而m也是一个偶数。综合得，n和m都是偶数，然而，这与我们的起点——假设
  \(\frac{n}{m}\)不可约相矛盾！所以，我们的出发点是不对的，也即
  \[\sqrt{2}\text{ 不能表示成 } \frac{n}{m} \]
</div>
<p>
  通过变化n和m，n/m可以任意大，也可以任意小，但是却不能表示\(\sqrt{2}\)！
</p>

<br>
<div class="w3-card-4 w3-center" style="margin:auto;width:250px;">
  <div class="w3-orange w3-text-white">
    <p style="font-size:100px;line-height:200px;margin:0px;">?</p>
  </div>
  <div style="padding:10px;">
    \(\sqrt{2}\)到底是多少呢？
  </div>
</div>

<br>
<hr>
<h3>4. 非比例数（irrational number）</h3>
<p>
  非比例数，也即一般所说的无理数。
</p>
<p>
  虽然，比例数可以任意大，也可以任意小，但是，就是表示不了\(\sqrt{2}\)！
  那么，数字应该是什么呢？
</p>
<p>
  数数的时候，{1,2,3,4···}，大家基本一致认为，这样
  的整数是合理的、与现实生活经验一致、理所当然的，比如，1个人、2个人、3个人
  等等，如此下去。
</p>
<div class="w3-container w3-leftbar w3-pale-green w3-border-green">
  <p>
    数字从经验出发，却舍弃经验，逐渐抽象化、虚构化，成为一种理论。
  </p>
</div>
<p>
  其实，如果严格按经验标准（要么有现实对应，要么现实可以做到），\(\frac{1}{3}\)
  是个不存在的数，因为现有的手段无法做到，将1平均等分成3份，尽管，可以
  将3等分成3份。但是，我们还是心安理得地，接纳了\(\frac{1}{3}\)这样的比例数。
  这也意味着，大家放弃了经验标准，超脱了现实世界，构造了自己想要的数字，形成
  了数字理论。
</p>
<p>
  \(\sqrt{2}\)在超脱现实世界方面，走的更远一点。\(\sqrt{2}\)只是一个简洁的
  记号，实际指代满足下面等式的x:
  \[x^2 = 2\]
  我们从整数里找不到这样的x，从比例数中也找不到x。就像，\(\frac{1}{3}\)也只
  是一个记号，实际指代满足下式的x：
  \[x\times3=1\]
  我们从整数里找不到这样的x，于是“虚构”出比例数\(\frac{1}{3}\)，其他的比例
  数类推。对于\(\sqrt{2}\)这样的情况，于是我们也“虚构”出非比例数\(\sqrt{2}\)
  ，其他非比例数类推。
</p>
<div class="w3-container w3-leftbar w3-pale-green w3-border-green">
  <p>
    到目前为止，我们引入如下几类数字：
    <ol>
      <li>整数，包括自然数、0、负的自然数；</li>
      <li>比例数，也称为有理数；</li>
      <li>非比例数，也称为无理数；</li>
    </ol>
    这些数字统称为<strong>实数</strong>，英文名称是 real number，数学符号
    用\(\mathcal{R}\)表示（取real第一个单词r）。
  </p>
  <p>
    虚数，是一种更抽象的数字，英文名称是imaginary number。就像虚数这个名字
    的字面意思那样，虚数是一种虚构的数字。
  </p>
</div>

</div>
