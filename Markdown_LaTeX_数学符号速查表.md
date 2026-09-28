---
title: "Markdown + LaTeX 数学符号速查表"
---

<style>
.latex-cheatsheet { width: 100%; border-collapse: collapse; }
.latex-cheatsheet th, .latex-cheatsheet td { border: 1px solid #d0d7de; padding: .65rem .8rem; vertical-align: middle; }
.latex-cheatsheet .chapter th { background: #0969da; color: white; font-size: 1.15rem; text-align: left; }
.latex-cheatsheet .section th { background: #ddf4ff; color: #24292f; text-align: left; }
.latex-cheatsheet .columns th { background: #f6f8fa; text-align: left; }
.latex-cheatsheet .formula { min-width: 38%; text-align: center; font-size: 1.08rem; }
.latex-cheatsheet pre { margin: 0; white-space: pre-wrap; }
</style>

<table class="latex-cheatsheet">
  <thead>
    <tr>
      <th colspan="2">Markdown + LaTeX 数学符号速查表</th>
    </tr>
    <tr class="columns">
      <th>效果</th>
      <th>代码</th>
    </tr>
  </thead>
  <tbody>
  <tr class="chapter">
    <th colspan="2">基本写法</th>
  </tr>
  <tr class="section">
    <th colspan="2">行内公式</th>
  </tr>
  <tr>
    <td class="formula">\(x+y=z\)</td>
    <td><pre><code>$x+y=z$</code></pre></td>
  </tr>
  <tr class="section">
    <th colspan="2">独立公式</th>
  </tr>
  <tr>
    <td class="formula">\(x+y=z\)</td>
    <td><pre><code>$$
x+y=z
$$</code></pre></td>
  </tr>
  <tr class="chapter">
    <th colspan="2">上标、下标</th>
  </tr>
  <tr>
    <td class="formula">\(x_1\)</td>
    <td><pre><code>x_1</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(x_i\)</td>
    <td><pre><code>x_i</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(x_{ij}\)</td>
    <td><pre><code>x_{ij}</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(x_{i,j}\)</td>
    <td><pre><code>x_{i,j}</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(x^2\)</td>
    <td><pre><code>x^2</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(x^n\)</td>
    <td><pre><code>x^n</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(x^{n+1}\)</td>
    <td><pre><code>x^{n+1}</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(x_i^2\)</td>
    <td><pre><code>x_i^2</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(x_{ij}^{(t)}\)</td>
    <td><pre><code>x_{ij}^{(t)}</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(x_t^{(i)}\)</td>
    <td><pre><code>x_t^{(i)}</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(x_{t+1}\)</td>
    <td><pre><code>x_{t+1}</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(x^{(l+1)}\)</td>
    <td><pre><code>x^{(l+1)}</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\[
x_{i+1}
x^{n+1}
\]</td>
    <td><pre><code>x_{i+1}
x^{n+1}</code></pre></td>
  </tr>
  <tr class="chapter">
    <th colspan="2">向量</th>
  </tr>
  <tr class="section">
    <th colspan="2">推荐写法</th>
  </tr>
  <tr>
    <td class="formula">\(\mathbf{x}\)</td>
    <td><pre><code>\mathbf{x}</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\mathbf{v}\)</td>
    <td><pre><code>\mathbf{v}</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\boldsymbol{x}\)</td>
    <td><pre><code>\boldsymbol{x}</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\vec{x}\)</td>
    <td><pre><code>\vec{x}</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\overrightarrow{AB}\)</td>
    <td><pre><code>\overrightarrow{AB}</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\[
\mathbf{x}
\mathbf{h}
\mathbf{v}
\]</td>
    <td><pre><code>\mathbf{x}
\mathbf{h}
\mathbf{v}</code></pre></td>
  </tr>
  <tr class="chapter">
    <th colspan="2">矩阵</th>
  </tr>
  <tr>
    <td class="formula">\[
\mathbf{A}
\mathbf{W}
\mathbf{X}
\]</td>
    <td><pre><code>\mathbf{A}
\mathbf{W}
\mathbf{X}</code></pre></td>
  </tr>
  <tr class="section">
    <th colspan="2">矩阵写法</th>
  </tr>
  <tr>
    <td class="formula">\[
\begin{bmatrix}
a &amp; b \\
c &amp; d
\end{bmatrix}
\]</td>
    <td><pre><code>\begin{bmatrix}
a &amp; b \\
c &amp; d
\end{bmatrix}</code></pre></td>
  </tr>
  <tr class="section">
    <th colspan="2">常见矩阵括号</th>
  </tr>
  <tr class="section">
    <th colspan="2">方括号</th>
  </tr>
  <tr>
    <td class="formula">\[
\begin{bmatrix}
a &amp; b\\
c &amp; d
\end{bmatrix}
\]</td>
    <td><pre><code>\begin{bmatrix}
a &amp; b\\
c &amp; d
\end{bmatrix}</code></pre></td>
  </tr>
  <tr class="section">
    <th colspan="2">圆括号</th>
  </tr>
  <tr>
    <td class="formula">\[
\begin{pmatrix}
a &amp; b\\
c &amp; d
\end{pmatrix}
\]</td>
    <td><pre><code>\begin{pmatrix}
a &amp; b\\
c &amp; d
\end{pmatrix}</code></pre></td>
  </tr>
  <tr class="section">
    <th colspan="2">行列式</th>
  </tr>
  <tr>
    <td class="formula">\[
\begin{vmatrix}
a &amp; b\\
c &amp; d
\end{vmatrix}
\]</td>
    <td><pre><code>\begin{vmatrix}
a &amp; b\\
c &amp; d
\end{vmatrix}</code></pre></td>
  </tr>
  <tr class="chapter">
    <th colspan="2">长矩阵</th>
  </tr>
  <tr>
    <td class="formula">\[
\mathbf{A}
=
\begin{bmatrix}
a_{11} &amp; a_{12} &amp; \cdots &amp; a_{1n}\\
a_{21} &amp; a_{22} &amp; \cdots &amp; a_{2n}\\
\vdots &amp; \vdots &amp; \ddots &amp; \vdots\\
a_{m1} &amp; a_{m2} &amp; \cdots &amp; a_{mn}
\end{bmatrix}
\]</td>
    <td><pre><code>\mathbf{A}
=
\begin{bmatrix}
a_{11} &amp; a_{12} &amp; \cdots &amp; a_{1n}\\
a_{21} &amp; a_{22} &amp; \cdots &amp; a_{2n}\\
\vdots &amp; \vdots &amp; \ddots &amp; \vdots\\
a_{m1} &amp; a_{m2} &amp; \cdots &amp; a_{mn}
\end{bmatrix}</code></pre></td>
  </tr>
  <tr class="chapter">
    <th colspan="2">向量列表示</th>
  </tr>
  <tr>
    <td class="formula">\[
\mathbf{x}
=
\begin{bmatrix}
x_1\\
x_2\\
\vdots\\
x_n
\end{bmatrix}
\]</td>
    <td><pre><code>\mathbf{x}
=
\begin{bmatrix}
x_1\\
x_2\\
\vdots\\
x_n
\end{bmatrix}</code></pre></td>
  </tr>
  <tr class="chapter">
    <th colspan="2">转置、逆矩阵、共轭</th>
  </tr>
  <tr>
    <td class="formula">\(\mathbf{A}^T\)</td>
    <td><pre><code>\mathbf{A}^T</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\mathbf{A}^{\mathsf T}\)</td>
    <td><pre><code>\mathbf{A}^{\mathsf T}</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\mathbf{A}^{-1}\)</td>
    <td><pre><code>\mathbf{A}^{-1}</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\mathbf{A}^{*}\)</td>
    <td><pre><code>\mathbf{A}^{*}</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\mathbf{A}^{\dagger}\)</td>
    <td><pre><code>\mathbf{A}^{\dagger}</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\mathbf{A}^{H}\)</td>
    <td><pre><code>\mathbf{A}^{H}</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\mathbf{A}^{\mathsf T}\)</td>
    <td><pre><code>\mathbf{A}^{\mathsf T}</code></pre></td>
  </tr>
  <tr class="chapter">
    <th colspan="2">分数</th>
  </tr>
  <tr>
    <td class="formula">\(\frac{a}{b}\)</td>
    <td><pre><code>\frac{a}{b}</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\frac{x_1+x_2}{y_1+y_2}\)</td>
    <td><pre><code>\frac{x_1+x_2}{y_1+y_2}</code></pre></td>
  </tr>
  <tr class="chapter">
    <th colspan="2">根号</th>
  </tr>
  <tr>
    <td class="formula">\(\sqrt{x}\)</td>
    <td><pre><code>\sqrt{x}</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\sqrt{x+y}\)</td>
    <td><pre><code>\sqrt{x+y}</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\sqrt[n]{x}\)</td>
    <td><pre><code>\sqrt[n]{x}</code></pre></td>
  </tr>
  <tr class="chapter">
    <th colspan="2">希腊字母</th>
  </tr>
  <tr class="section">
    <th colspan="2">小写</th>
  </tr>
  <tr>
    <td class="formula">\(\alpha\)</td>
    <td><pre><code>\alpha</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\beta\)</td>
    <td><pre><code>\beta</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\gamma\)</td>
    <td><pre><code>\gamma</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\delta\)</td>
    <td><pre><code>\delta</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\epsilon\)</td>
    <td><pre><code>\epsilon</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\varepsilon\)</td>
    <td><pre><code>\varepsilon</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\zeta\)</td>
    <td><pre><code>\zeta</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\eta\)</td>
    <td><pre><code>\eta</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\theta\)</td>
    <td><pre><code>\theta</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\vartheta\)</td>
    <td><pre><code>\vartheta</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\iota\)</td>
    <td><pre><code>\iota</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\kappa\)</td>
    <td><pre><code>\kappa</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\lambda\)</td>
    <td><pre><code>\lambda</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\mu\)</td>
    <td><pre><code>\mu</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\nu\)</td>
    <td><pre><code>\nu</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\xi\)</td>
    <td><pre><code>\xi</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\pi\)</td>
    <td><pre><code>\pi</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\rho\)</td>
    <td><pre><code>\rho</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\sigma\)</td>
    <td><pre><code>\sigma</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\tau\)</td>
    <td><pre><code>\tau</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\upsilon\)</td>
    <td><pre><code>\upsilon</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\phi\)</td>
    <td><pre><code>\phi</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\varphi\)</td>
    <td><pre><code>\varphi</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\chi\)</td>
    <td><pre><code>\chi</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\psi\)</td>
    <td><pre><code>\psi</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\omega\)</td>
    <td><pre><code>\omega</code></pre></td>
  </tr>
  <tr class="section">
    <th colspan="2">大写</th>
  </tr>
  <tr>
    <td class="formula">\(\Gamma\)</td>
    <td><pre><code>\Gamma</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\Delta\)</td>
    <td><pre><code>\Delta</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\Theta\)</td>
    <td><pre><code>\Theta</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\Lambda\)</td>
    <td><pre><code>\Lambda</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\Xi\)</td>
    <td><pre><code>\Xi</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\Pi\)</td>
    <td><pre><code>\Pi</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\Sigma\)</td>
    <td><pre><code>\Sigma</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\Phi\)</td>
    <td><pre><code>\Phi</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\Psi\)</td>
    <td><pre><code>\Psi</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\Omega\)</td>
    <td><pre><code>\Omega</code></pre></td>
  </tr>
  <tr class="chapter">
    <th colspan="2">字体</th>
  </tr>
  <tr class="section">
    <th colspan="2">普通</th>
  </tr>
  <tr>
    <td class="formula">\(x\)</td>
    <td><pre><code>x</code></pre></td>
  </tr>
  <tr class="section">
    <th colspan="2">粗体</th>
  </tr>
  <tr>
    <td class="formula">\(\mathbf{x}\)</td>
    <td><pre><code>\mathbf{x}</code></pre></td>
  </tr>
  <tr class="section">
    <th colspan="2">黑板粗体</th>
  </tr>
  <tr>
    <td class="formula">\(\mathbb{R}\)</td>
    <td><pre><code>\mathbb{R}</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\[
\mathbb{R}
\mathbb{N}
\mathbb{Z}
\mathbb{Q}
\mathbb{C}
\]</td>
    <td><pre><code>\mathbb{R}
\mathbb{N}
\mathbb{Z}
\mathbb{Q}
\mathbb{C}</code></pre></td>
  </tr>
  <tr class="section">
    <th colspan="2">花体 / 手写体</th>
  </tr>
  <tr>
    <td class="formula">\(\mathcal{L}\)</td>
    <td><pre><code>\mathcal{L}</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\[
\mathcal{L}
\mathcal{D}
\mathcal{X}
\mathcal{F}
\]</td>
    <td><pre><code>\mathcal{L}
\mathcal{D}
\mathcal{X}
\mathcal{F}</code></pre></td>
  </tr>
  <tr class="section">
    <th colspan="2">更像手写体</th>
  </tr>
  <tr>
    <td class="formula">\(\mathscr{L}\)</td>
    <td><pre><code>\mathscr{L}</code></pre></td>
  </tr>
  <tr class="section">
    <th colspan="2">正体文字</th>
  </tr>
  <tr>
    <td class="formula">\(\mathrm{d}\)</td>
    <td><pre><code>\mathrm{d}</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\[
\mathrm{d}x
\mathrm{d}t
\]</td>
    <td><pre><code>\mathrm{d}x
\mathrm{d}t</code></pre></td>
  </tr>
  <tr class="section">
    <th colspan="2">算子文字</th>
  </tr>
  <tr>
    <td class="formula">\(\operatorname{rank}\)</td>
    <td><pre><code>\operatorname{rank}</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\[
\operatorname{Var}
\operatorname{Cov}
\operatorname{diag}
\operatorname{Tr}
\operatorname{softmax}
\]</td>
    <td><pre><code>\operatorname{Var}
\operatorname{Cov}
\operatorname{diag}
\operatorname{Tr}
\operatorname{softmax}</code></pre></td>
  </tr>
  <tr class="chapter">
    <th colspan="2">加帽、横线、波浪线</th>
  </tr>
  <tr>
    <td class="formula">\(\hat{x}\)</td>
    <td><pre><code>\hat{x}</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\widehat{x}\)</td>
    <td><pre><code>\widehat{x}</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\bar{x}\)</td>
    <td><pre><code>\bar{x}</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\overline{x}\)</td>
    <td><pre><code>\overline{x}</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\tilde{x}\)</td>
    <td><pre><code>\tilde{x}</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\widetilde{x}\)</td>
    <td><pre><code>\widetilde{x}</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\dot{x}\)</td>
    <td><pre><code>\dot{x}</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\ddot{x}\)</td>
    <td><pre><code>\ddot{x}</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\[
\hat{\mathbf{x}}_0
\hat{\mathbf{x}}_1
\tilde{\mathbf{x}}_t
\]</td>
    <td><pre><code>\hat{\mathbf{x}}_0
\hat{\mathbf{x}}_1
\tilde{\mathbf{x}}_t</code></pre></td>
  </tr>
  <tr class="chapter">
    <th colspan="2">极限</th>
  </tr>
  <tr>
    <td class="formula">\(\lim_{x\to 0} f(x)\)</td>
    <td><pre><code>\lim_{x\to 0} f(x)</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\lim_{n\to\infty} a_n\)</td>
    <td><pre><code>\lim_{n\to\infty} a_n</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\lim_{x\to a^-} f(x)\)</td>
    <td><pre><code>\lim_{x\to a^-} f(x)</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\lim_{x\to a^+} f(x)\)</td>
    <td><pre><code>\lim_{x\to a^+} f(x)</code></pre></td>
  </tr>
  <tr class="chapter">
    <th colspan="2">求和</th>
  </tr>
  <tr>
    <td class="formula">\(\sum_{i=1}^{n} x_i\)</td>
    <td><pre><code>\sum_{i=1}^{n} x_i</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\sum_{i=1}^{\infty} x_i\)</td>
    <td><pre><code>\sum_{i=1}^{\infty} x_i</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\sum_{i=1}^{n}\sum_{j=1}^{m} a_{ij}\)</td>
    <td><pre><code>\sum_{i=1}^{n}\sum_{j=1}^{m} a_{ij}</code></pre></td>
  </tr>
  <tr class="chapter">
    <th colspan="2">累乘</th>
  </tr>
  <tr>
    <td class="formula">\(\prod_{i=1}^{n} x_i\)</td>
    <td><pre><code>\prod_{i=1}^{n} x_i</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\[
p(\mathcal{D})
=
\prod_{i=1}^{N} p(x_i)
\]</td>
    <td><pre><code>p(\mathcal{D})
=
\prod_{i=1}^{N} p(x_i)</code></pre></td>
  </tr>
  <tr class="chapter">
    <th colspan="2">积分</th>
  </tr>
  <tr class="section">
    <th colspan="2">普通积分</th>
  </tr>
  <tr>
    <td class="formula">\(\int f(x)\,\mathrm{d}x\)</td>
    <td><pre><code>\int f(x)\,\mathrm{d}x</code></pre></td>
  </tr>
  <tr class="section">
    <th colspan="2">定积分</th>
  </tr>
  <tr>
    <td class="formula">\(\int_a^b f(x)\,\mathrm{d}x\)</td>
    <td><pre><code>\int_a^b f(x)\,\mathrm{d}x</code></pre></td>
  </tr>
  <tr class="section">
    <th colspan="2">从负无穷到正无穷</th>
  </tr>
  <tr>
    <td class="formula">\(\int_{-\infty}^{+\infty} f(x)\,\mathrm{d}x\)</td>
    <td><pre><code>\int_{-\infty}^{+\infty} f(x)\,\mathrm{d}x</code></pre></td>
  </tr>
  <tr class="section">
    <th colspan="2">二重积分</th>
  </tr>
  <tr>
    <td class="formula">\(\iint f(x,y)\,\mathrm{d}x\,\mathrm{d}y\)</td>
    <td><pre><code>\iint f(x,y)\,\mathrm{d}x\,\mathrm{d}y</code></pre></td>
  </tr>
  <tr class="section">
    <th colspan="2">三重积分</th>
  </tr>
  <tr>
    <td class="formula">\(\iiint f(x,y,z)\,\mathrm{d}x\,\mathrm{d}y\,\mathrm{d}z\)</td>
    <td><pre><code>\iiint f(x,y,z)\,\mathrm{d}x\,\mathrm{d}y\,\mathrm{d}z</code></pre></td>
  </tr>
  <tr class="section">
    <th colspan="2">环路积分</th>
  </tr>
  <tr>
    <td class="formula">\(\oint_C f(z)\,\mathrm{d}z\)</td>
    <td><pre><code>\oint_C f(z)\,\mathrm{d}z</code></pre></td>
  </tr>
  <tr class="chapter">
    <th colspan="2">微分</th>
  </tr>
  <tr>
    <td class="formula">\(\mathrm{d}x\)</td>
    <td><pre><code>\mathrm{d}x</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\mathrm{d}t\)</td>
    <td><pre><code>\mathrm{d}t</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\frac{\mathrm{d}y}{\mathrm{d}x}\)</td>
    <td><pre><code>\frac{\mathrm{d}y}{\mathrm{d}x}</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\frac{\mathrm{d}^2y}{\mathrm{d}x^2}\)</td>
    <td><pre><code>\frac{\mathrm{d}^2y}{\mathrm{d}x^2}</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\mathrm{d}x\)</td>
    <td><pre><code>\mathrm{d}x</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(dx\)</td>
    <td><pre><code>dx</code></pre></td>
  </tr>
  <tr class="chapter">
    <th colspan="2">偏导</th>
  </tr>
  <tr>
    <td class="formula">\(\frac{\partial f}{\partial x}\)</td>
    <td><pre><code>\frac{\partial f}{\partial x}</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\frac{\partial^2 f}{\partial x^2}\)</td>
    <td><pre><code>\frac{\partial^2 f}{\partial x^2}</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\frac{\partial^2 f}{\partial x\partial y}\)</td>
    <td><pre><code>\frac{\partial^2 f}{\partial x\partial y}</code></pre></td>
  </tr>
  <tr class="chapter">
    <th colspan="2">梯度</th>
  </tr>
  <tr>
    <td class="formula">\(\nabla f\)</td>
    <td><pre><code>\nabla f</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\nabla_{\theta}\mathcal{L}\)</td>
    <td><pre><code>\nabla_{\theta}\mathcal{L}</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\nabla_{\mathbf{x}} f(\mathbf{x})\)</td>
    <td><pre><code>\nabla_{\mathbf{x}} f(\mathbf{x})</code></pre></td>
  </tr>
  <tr class="chapter">
    <th colspan="2">Laplacian</th>
  </tr>
  <tr>
    <td class="formula">\(\nabla^2 f\)</td>
    <td><pre><code>\nabla^2 f</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\Delta f\)</td>
    <td><pre><code>\Delta f</code></pre></td>
  </tr>
  <tr class="chapter">
    <th colspan="2">期望</th>
  </tr>
  <tr>
    <td class="formula">\(\mathbb{E}[X]\)</td>
    <td><pre><code>\mathbb{E}[X]</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\mathbb{E}_{x\sim p(x)}[f(x)]\)</td>
    <td><pre><code>\mathbb{E}_{x\sim p(x)}[f(x)]</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\[
\mathbb{E}_{t,x_0,x_1}
\left[
\left\|
v_\theta(x_t,t)-u_t
\right\|^2
\right]
\]</td>
    <td><pre><code>\mathbb{E}_{t,x_0,x_1}
\left[
\left\|
v_\theta(x_t,t)-u_t
\right\|^2
\right]</code></pre></td>
  </tr>
  <tr class="chapter">
    <th colspan="2">概率分布 ~</th>
  </tr>
  <tr>
    <td class="formula">\(X \sim p(x)\)</td>
    <td><pre><code>X \sim p(x)</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(X \sim \mathcal{N}(\mu,\sigma^2)\)</td>
    <td><pre><code>X \sim \mathcal{N}(\mu,\sigma^2)</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\[
\mathbf{x}
\sim
\mathcal{N}
(
\boldsymbol{\mu},
\mathbf{\Sigma}
)
\]</td>
    <td><pre><code>\mathbf{x}
\sim
\mathcal{N}
(
\boldsymbol{\mu},
\mathbf{\Sigma}
)</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\[
\boldsymbol{\epsilon}
\sim
\mathcal{N}(\mathbf{0},\mathbf{I})
\]</td>
    <td><pre><code>\boldsymbol{\epsilon}
\sim
\mathcal{N}(\mathbf{0},\mathbf{I})</code></pre></td>
  </tr>
  <tr class="chapter">
    <th colspan="2">概率</th>
  </tr>
  <tr>
    <td class="formula">\(p(x)\)</td>
    <td><pre><code>p(x)</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(p(x,y)\)</td>
    <td><pre><code>p(x,y)</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(p(x\mid y)\)</td>
    <td><pre><code>p(x\mid y)</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(p_\theta(x)\)</td>
    <td><pre><code>p_\theta(x)</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(p_t(x)\)</td>
    <td><pre><code>p_t(x)</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(p(x_1\mid x_0)\)</td>
    <td><pre><code>p(x_1\mid x_0)</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\mid\)</td>
    <td><pre><code>\mid</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(|\)</td>
    <td><pre><code>|</code></pre></td>
  </tr>
  <tr class="chapter">
    <th colspan="2">方差与协方差</th>
  </tr>
  <tr>
    <td class="formula">\(\operatorname{Var}(X)\)</td>
    <td><pre><code>\operatorname{Var}(X)</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\operatorname{Cov}(X,Y)\)</td>
    <td><pre><code>\operatorname{Cov}(X,Y)</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\mathbf{\Sigma}\)</td>
    <td><pre><code>\mathbf{\Sigma}</code></pre></td>
  </tr>
  <tr class="chapter">
    <th colspan="2">范数</th>
  </tr>
  <tr class="section">
    <th colspan="2">L1</th>
  </tr>
  <tr>
    <td class="formula">\(\|\mathbf{x}\|_1\)</td>
    <td><pre><code>\|\mathbf{x}\|_1</code></pre></td>
  </tr>
  <tr class="section">
    <th colspan="2">L2</th>
  </tr>
  <tr>
    <td class="formula">\(\|\mathbf{x}\|_2\)</td>
    <td><pre><code>\|\mathbf{x}\|_2</code></pre></td>
  </tr>
  <tr class="section">
    <th colspan="2">平方 L2</th>
  </tr>
  <tr>
    <td class="formula">\(\|\mathbf{x}\|_2^2\)</td>
    <td><pre><code>\|\mathbf{x}\|_2^2</code></pre></td>
  </tr>
  <tr class="section">
    <th colspan="2">无穷范数</th>
  </tr>
  <tr>
    <td class="formula">\(\|\mathbf{x}\|_\infty\)</td>
    <td><pre><code>\|\mathbf{x}\|_\infty</code></pre></td>
  </tr>
  <tr class="section">
    <th colspan="2">Frobenius norm</th>
  </tr>
  <tr>
    <td class="formula">\(\|\mathbf{A}\|_F\)</td>
    <td><pre><code>\|\mathbf{A}\|_F</code></pre></td>
  </tr>
  <tr class="chapter">
    <th colspan="2">绝对值</th>
  </tr>
  <tr>
    <td class="formula">\(|x|\)</td>
    <td><pre><code>|x|</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\left|x+y\right|\)</td>
    <td><pre><code>\left|x+y\right|</code></pre></td>
  </tr>
  <tr class="chapter">
    <th colspan="2">内积</th>
  </tr>
  <tr>
    <td class="formula">\(\langle \mathbf{x},\mathbf{y}\rangle\)</td>
    <td><pre><code>\langle \mathbf{x},\mathbf{y}\rangle</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\mathbf{x}^{\mathsf T}\mathbf{y}\)</td>
    <td><pre><code>\mathbf{x}^{\mathsf T}\mathbf{y}</code></pre></td>
  </tr>
  <tr class="chapter">
    <th colspan="2">集合</th>
  </tr>
  <tr>
    <td class="formula">\(x\in A\)</td>
    <td><pre><code>x\in A</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(x\notin A\)</td>
    <td><pre><code>x\notin A</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(A\subset B\)</td>
    <td><pre><code>A\subset B</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(A\subseteq B\)</td>
    <td><pre><code>A\subseteq B</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(A\supseteq B\)</td>
    <td><pre><code>A\supseteq B</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(A\cup B\)</td>
    <td><pre><code>A\cup B</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(A\cap B\)</td>
    <td><pre><code>A\cap B</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\varnothing\)</td>
    <td><pre><code>\varnothing</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(A\setminus B\)</td>
    <td><pre><code>A\setminus B</code></pre></td>
  </tr>
  <tr class="chapter">
    <th colspan="2">集合定义</th>
  </tr>
  <tr>
    <td class="formula">\[
A
=
\{x\in\mathbb{R}\mid x&gt;0\}
\]</td>
    <td><pre><code>A
=
\{x\in\mathbb{R}\mid x&gt;0\}</code></pre></td>
  </tr>
  <tr class="chapter">
    <th colspan="2">常见数集</th>
  </tr>
  <tr>
    <td class="formula">\(\mathbb{N}\)</td>
    <td><pre><code>\mathbb{N}</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\mathbb{Z}\)</td>
    <td><pre><code>\mathbb{Z}</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\mathbb{Q}\)</td>
    <td><pre><code>\mathbb{Q}</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\mathbb{R}\)</td>
    <td><pre><code>\mathbb{R}</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\mathbb{C}\)</td>
    <td><pre><code>\mathbb{C}</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\mathbb{R}^n\)</td>
    <td><pre><code>\mathbb{R}^n</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\mathbb{R}^{m\times n}\)</td>
    <td><pre><code>\mathbb{R}^{m\times n}</code></pre></td>
  </tr>
  <tr class="chapter">
    <th colspan="2">映射</th>
  </tr>
  <tr>
    <td class="formula">\(f:\mathbb{R}^n\to\mathbb{R}^m\)</td>
    <td><pre><code>f:\mathbb{R}^n\to\mathbb{R}^m</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(f_\theta:\mathcal{X}\to\mathcal{Y}\)</td>
    <td><pre><code>f_\theta:\mathcal{X}\to\mathcal{Y}</code></pre></td>
  </tr>
  <tr class="chapter">
    <th colspan="2">箭头</th>
  </tr>
  <tr>
    <td class="formula">\(\to\)</td>
    <td><pre><code>\to</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\rightarrow\)</td>
    <td><pre><code>\rightarrow</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\leftarrow\)</td>
    <td><pre><code>\leftarrow</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\leftrightarrow\)</td>
    <td><pre><code>\leftrightarrow</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\Rightarrow\)</td>
    <td><pre><code>\Rightarrow</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\Leftarrow\)</td>
    <td><pre><code>\Leftarrow</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\Leftrightarrow\)</td>
    <td><pre><code>\Leftrightarrow</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\mapsto\)</td>
    <td><pre><code>\mapsto</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\uparrow\)</td>
    <td><pre><code>\uparrow</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\downarrow\)</td>
    <td><pre><code>\downarrow</code></pre></td>
  </tr>
  <tr class="chapter">
    <th colspan="2">等号与关系符号</th>
  </tr>
  <tr>
    <td class="formula">\(=\)</td>
    <td><pre><code>=</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\neq\)</td>
    <td><pre><code>\neq</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\approx\)</td>
    <td><pre><code>\approx</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\sim\)</td>
    <td><pre><code>\sim</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\simeq\)</td>
    <td><pre><code>\simeq</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\equiv\)</td>
    <td><pre><code>\equiv</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\propto\)</td>
    <td><pre><code>\propto</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(&lt;\)</td>
    <td><pre><code>&lt;</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(&gt;\)</td>
    <td><pre><code>&gt;</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\leq\)</td>
    <td><pre><code>\leq</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\geq\)</td>
    <td><pre><code>\geq</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\ll\)</td>
    <td><pre><code>\ll</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\gg\)</td>
    <td><pre><code>\gg</code></pre></td>
  </tr>
  <tr class="chapter">
    <th colspan="2">定义符号</th>
  </tr>
  <tr>
    <td class="formula">\(x := y\)</td>
    <td><pre><code>x := y</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(x \coloneqq y\)</td>
    <td><pre><code>x \coloneqq y</code></pre></td>
  </tr>
  <tr class="chapter">
    <th colspan="2">逻辑符号</th>
  </tr>
  <tr>
    <td class="formula">\(\forall\)</td>
    <td><pre><code>\forall</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\exists\)</td>
    <td><pre><code>\exists</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\nexists\)</td>
    <td><pre><code>\nexists</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\neg\)</td>
    <td><pre><code>\neg</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\land\)</td>
    <td><pre><code>\land</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\lor\)</td>
    <td><pre><code>\lor</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\therefore\)</td>
    <td><pre><code>\therefore</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\because\)</td>
    <td><pre><code>\because</code></pre></td>
  </tr>
  <tr class="chapter">
    <th colspan="2">最大值、最小值</th>
  </tr>
  <tr>
    <td class="formula">\(\max_x f(x)\)</td>
    <td><pre><code>\max_x f(x)</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\min_x f(x)\)</td>
    <td><pre><code>\min_x f(x)</code></pre></td>
  </tr>
  <tr class="chapter">
    <th colspan="2">argmax / argmin</th>
  </tr>
  <tr>
    <td class="formula">\[
x^*
=
\arg\min_x f(x)
\]</td>
    <td><pre><code>x^*
=
\arg\min_x f(x)</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\[
x^*
=
\arg\max_x f(x)
\]</td>
    <td><pre><code>x^*
=
\arg\max_x f(x)</code></pre></td>
  </tr>
  <tr class="chapter">
    <th colspan="2">无穷</th>
  </tr>
  <tr>
    <td class="formula">\(\infty\)</td>
    <td><pre><code>\infty</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\[
-\infty
+\infty
\]</td>
    <td><pre><code>-\infty
+\infty</code></pre></td>
  </tr>
  <tr class="chapter">
    <th colspan="2">点乘</th>
  </tr>
  <tr>
    <td class="formula">\(\mathbf{x}\cdot\mathbf{y}\)</td>
    <td><pre><code>\mathbf{x}\cdot\mathbf{y}</code></pre></td>
  </tr>
  <tr class="chapter">
    <th colspan="2">叉乘</th>
  </tr>
  <tr>
    <td class="formula">\(\mathbf{x}\times\mathbf{y}\)</td>
    <td><pre><code>\mathbf{x}\times\mathbf{y}</code></pre></td>
  </tr>
  <tr class="chapter">
    <th colspan="2">Hadamard 逐元素乘法</th>
  </tr>
  <tr>
    <td class="formula">\(\mathbf{x}\odot\mathbf{y}\)</td>
    <td><pre><code>\mathbf{x}\odot\mathbf{y}</code></pre></td>
  </tr>
  <tr class="chapter">
    <th colspan="2">Kronecker Product</th>
  </tr>
  <tr>
    <td class="formula">\(\mathbf{A}\otimes\mathbf{B}\)</td>
    <td><pre><code>\mathbf{A}\otimes\mathbf{B}</code></pre></td>
  </tr>
  <tr class="chapter">
    <th colspan="2">除法、集合商等</th>
  </tr>
  <tr>
    <td class="formula">\(a/b\)</td>
    <td><pre><code>a/b</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(A/B\)</td>
    <td><pre><code>A/B</code></pre></td>
  </tr>
  <tr class="chapter">
    <th colspan="2">特殊乘法符号</th>
  </tr>
  <tr>
    <td class="formula">\(a\cdot b\)</td>
    <td><pre><code>a\cdot b</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(a\times b\)</td>
    <td><pre><code>a\times b</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(a\ast b\)</td>
    <td><pre><code>a\ast b</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(a\star b\)</td>
    <td><pre><code>a\star b</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(a\circ b\)</td>
    <td><pre><code>a\circ b</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(a\odot b\)</td>
    <td><pre><code>a\odot b</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(a\otimes b\)</td>
    <td><pre><code>a\otimes b</code></pre></td>
  </tr>
  <tr class="chapter">
    <th colspan="2">函数组合</th>
  </tr>
  <tr>
    <td class="formula">\((f\circ g)(x)\)</td>
    <td><pre><code>(f\circ g)(x)</code></pre></td>
  </tr>
  <tr class="chapter">
    <th colspan="2">矩阵迹</th>
  </tr>
  <tr>
    <td class="formula">\(\operatorname{Tr}(\mathbf{A})\)</td>
    <td><pre><code>\operatorname{Tr}(\mathbf{A})</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\operatorname{tr}(\mathbf{A})\)</td>
    <td><pre><code>\operatorname{tr}(\mathbf{A})</code></pre></td>
  </tr>
  <tr class="chapter">
    <th colspan="2">行列式</th>
  </tr>
  <tr>
    <td class="formula">\(\det(\mathbf{A})\)</td>
    <td><pre><code>\det(\mathbf{A})</code></pre></td>
  </tr>
  <tr class="chapter">
    <th colspan="2">秩</th>
  </tr>
  <tr>
    <td class="formula">\(\operatorname{rank}(\mathbf{A})\)</td>
    <td><pre><code>\operatorname{rank}(\mathbf{A})</code></pre></td>
  </tr>
  <tr class="chapter">
    <th colspan="2">核空间</th>
  </tr>
  <tr>
    <td class="formula">\(\ker(\mathbf{A})\)</td>
    <td><pre><code>\ker(\mathbf{A})</code></pre></td>
  </tr>
  <tr class="chapter">
    <th colspan="2">像空间</th>
  </tr>
  <tr>
    <td class="formula">\(\operatorname{Im}(\mathbf{A})\)</td>
    <td><pre><code>\operatorname{Im}(\mathbf{A})</code></pre></td>
  </tr>
  <tr class="chapter">
    <th colspan="2">Span</th>
  </tr>
  <tr>
    <td class="formula">\[
\operatorname{span}
\{
\mathbf{v}_1,\ldots,\mathbf{v}_n
\}
\]</td>
    <td><pre><code>\operatorname{span}
\{
\mathbf{v}_1,\ldots,\mathbf{v}_n
\}</code></pre></td>
  </tr>
  <tr class="chapter">
    <th colspan="2">维数</th>
  </tr>
  <tr>
    <td class="formula">\(\dim(V)\)</td>
    <td><pre><code>\dim(V)</code></pre></td>
  </tr>
  <tr class="chapter">
    <th colspan="2">对角矩阵</th>
  </tr>
  <tr>
    <td class="formula">\[
\operatorname{diag}
(\lambda_1,\ldots,\lambda_n)
\]</td>
    <td><pre><code>\operatorname{diag}
(\lambda_1,\ldots,\lambda_n)</code></pre></td>
  </tr>
  <tr class="chapter">
    <th colspan="2">单位矩阵</th>
  </tr>
  <tr>
    <td class="formula">\(\mathbf{I}\)</td>
    <td><pre><code>\mathbf{I}</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\mathbf{I}_n\)</td>
    <td><pre><code>\mathbf{I}_n</code></pre></td>
  </tr>
  <tr class="chapter">
    <th colspan="2">零向量与零矩阵</th>
  </tr>
  <tr>
    <td class="formula">\(\mathbf{0}\)</td>
    <td><pre><code>\mathbf{0}</code></pre></td>
  </tr>
  <tr class="chapter">
    <th colspan="2">特征值与特征向量</th>
  </tr>
  <tr>
    <td class="formula">\[
\mathbf{A}\mathbf{v}
=
\lambda\mathbf{v}
\]</td>
    <td><pre><code>\mathbf{A}\mathbf{v}
=
\lambda\mathbf{v}</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\det(\mathbf{A}-\lambda\mathbf{I})=0\)</td>
    <td><pre><code>\det(\mathbf{A}-\lambda\mathbf{I})=0</code></pre></td>
  </tr>
  <tr class="chapter">
    <th colspan="2">SVD</th>
  </tr>
  <tr>
    <td class="formula">\[
\mathbf{A}
=
\mathbf{U}
\mathbf{\Sigma}
\mathbf{V}^{\mathsf T}
\]</td>
    <td><pre><code>\mathbf{A}
=
\mathbf{U}
\mathbf{\Sigma}
\mathbf{V}^{\mathsf T}</code></pre></td>
  </tr>
  <tr class="chapter">
    <th colspan="2">方程组</th>
  </tr>
  <tr>
    <td class="formula">\[
\begin{cases}
x+y=1,\\
2x-y=3.
\end{cases}
\]</td>
    <td><pre><code>\begin{cases}
x+y=1,\\
2x-y=3.
\end{cases}</code></pre></td>
  </tr>
  <tr class="chapter">
    <th colspan="2">分段函数</th>
  </tr>
  <tr>
    <td class="formula">\[
f(x)
=
\begin{cases}
x, &amp; x\geq 0,\\
-x, &amp; x&lt;0.
\end{cases}
\]</td>
    <td><pre><code>f(x)
=
\begin{cases}
x, &amp; x\geq 0,\\
-x, &amp; x&lt;0.
\end{cases}</code></pre></td>
  </tr>
  <tr class="chapter">
    <th colspan="2">多行公式对齐</th>
  </tr>
  <tr>
    <td class="formula">\[
\begin{aligned}
x_t
&amp;=
(1-t)x_0+tx_1\\
&amp;=
x_0+t(x_1-x_0)
\end{aligned}
\]</td>
    <td><pre><code>\begin{aligned}
x_t
&amp;=
(1-t)x_0+tx_1\\
&amp;=
x_0+t(x_1-x_0)
\end{aligned}</code></pre></td>
  </tr>
  <tr class="chapter">
    <th colspan="2">括号自动伸缩</th>
  </tr>
  <tr>
    <td class="formula">\((\frac{a}{b})\)</td>
    <td><pre><code>(\frac{a}{b})</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\[
\left(
\frac{a}{b}
\right)
\]</td>
    <td><pre><code>\left(
\frac{a}{b}
\right)</code></pre></td>
  </tr>
  <tr class="chapter">
    <th colspan="2">各种括号</th>
  </tr>
  <tr>
    <td class="formula">\((x)\)</td>
    <td><pre><code>(x)</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\([x]\)</td>
    <td><pre><code>[x]</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\{x\}\)</td>
    <td><pre><code>\{x\}</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\langle x\rangle\)</td>
    <td><pre><code>\langle x\rangle</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\lfloor x\rfloor\)</td>
    <td><pre><code>\lfloor x\rfloor</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\lceil x\rceil\)</td>
    <td><pre><code>\lceil x\rceil</code></pre></td>
  </tr>
  <tr class="chapter">
    <th colspan="2">省略号</th>
  </tr>
  <tr>
    <td class="formula">\(1,2,\ldots,n\)</td>
    <td><pre><code>1,2,\ldots,n</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(x_1+\cdots+x_n\)</td>
    <td><pre><code>x_1+\cdots+x_n</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\vdots\)</td>
    <td><pre><code>\vdots</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\ddots\)</td>
    <td><pre><code>\ddots</code></pre></td>
  </tr>
  <tr class="chapter">
    <th colspan="2">下划线、上划线</th>
  </tr>
  <tr>
    <td class="formula">\(\underline{x}\)</td>
    <td><pre><code>\underline{x}</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\overline{x}\)</td>
    <td><pre><code>\overline{x}</code></pre></td>
  </tr>
  <tr class="chapter">
    <th colspan="2">上括号</th>
  </tr>
  <tr>
    <td class="formula">\(\overbrace{a+b+c}^{3\text{ terms}}\)</td>
    <td><pre><code>\overbrace{a+b+c}^{3\text{ terms}}</code></pre></td>
  </tr>
  <tr class="chapter">
    <th colspan="2">下括号</th>
  </tr>
  <tr>
    <td class="formula">\(\underbrace{a+b+c}_{3\text{ terms}}\)</td>
    <td><pre><code>\underbrace{a+b+c}_{3\text{ terms}}</code></pre></td>
  </tr>
  <tr class="chapter">
    <th colspan="2">文本插入数学公式</th>
  </tr>
  <tr>
    <td class="formula">\[
x&gt;0
\quad
\text{if}
\quad
y&gt;0
\]</td>
    <td><pre><code>x&gt;0
\quad
\text{if}
\quad
y&gt;0</code></pre></td>
  </tr>
  <tr class="chapter">
    <th colspan="2">空格</th>
  </tr>
  <tr>
    <td class="formula">\(\,\)</td>
    <td><pre><code>\,</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\:\)</td>
    <td><pre><code>\:</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\;\)</td>
    <td><pre><code>\;</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\quad\)</td>
    <td><pre><code>\quad</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\qquad\)</td>
    <td><pre><code>\qquad</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(f(x)\,\mathrm{d}x\)</td>
    <td><pre><code>f(x)\,\mathrm{d}x</code></pre></td>
  </tr>
  <tr class="chapter">
    <th colspan="2">ODE</th>
  </tr>
  <tr>
    <td class="formula">\[
\frac{\mathrm{d}\mathbf{x}_t}{\mathrm{d}t}
=
\mathbf{v}(\mathbf{x}_t,t)
\]</td>
    <td><pre><code>\frac{\mathrm{d}\mathbf{x}_t}{\mathrm{d}t}
=
\mathbf{v}(\mathbf{x}_t,t)</code></pre></td>
  </tr>
  <tr class="chapter">
    <th colspan="2">SDE</th>
  </tr>
  <tr>
    <td class="formula">\[
\mathrm{d}\mathbf{x}_t
=
\mathbf{f}(\mathbf{x}_t,t)\,\mathrm{d}t
+
g(t)\,\mathrm{d}\mathbf{W}_t
\]</td>
    <td><pre><code>\mathrm{d}\mathbf{x}_t
=
\mathbf{f}(\mathbf{x}_t,t)\,\mathrm{d}t
+
g(t)\,\mathrm{d}\mathbf{W}_t</code></pre></td>
  </tr>
  <tr class="chapter">
    <th colspan="2">条件分布</th>
  </tr>
  <tr>
    <td class="formula">\(p(\mathbf{x}_t\mid\mathbf{x}_0)\)</td>
    <td><pre><code>p(\mathbf{x}_t\mid\mathbf{x}_0)</code></pre></td>
  </tr>
  <tr class="chapter">
    <th colspan="2">独立</th>
  </tr>
  <tr>
    <td class="formula">\(X \perp Y\)</td>
    <td><pre><code>X \perp Y</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(X\perp Y\mid Z\)</td>
    <td><pre><code>X\perp Y\mid Z</code></pre></td>
  </tr>
  <tr class="chapter">
    <th colspan="2">Indicator Function</th>
  </tr>
  <tr>
    <td class="formula">\(\mathbb{I}[x&gt;0]\)</td>
    <td><pre><code>\mathbb{I}[x&gt;0]</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\mathbf{1}_{x&gt;0}\)</td>
    <td><pre><code>\mathbf{1}_{x&gt;0}</code></pre></td>
  </tr>
  <tr class="chapter">
    <th colspan="2">概率</th>
  </tr>
  <tr>
    <td class="formula">\(\mathbb{P}(X&gt;x)\)</td>
    <td><pre><code>\mathbb{P}(X&gt;x)</code></pre></td>
  </tr>
  <tr class="chapter">
    <th colspan="2">正态分布</th>
  </tr>
  <tr>
    <td class="formula">\(\mathcal{N}(\mu,\sigma^2)\)</td>
    <td><pre><code>\mathcal{N}(\mu,\sigma^2)</code></pre></td>
  </tr>
  <tr class="chapter">
    <th colspan="2">均匀分布</th>
  </tr>
  <tr>
    <td class="formula">\(\mathcal{U}(a,b)\)</td>
    <td><pre><code>\mathcal{U}(a,b)</code></pre></td>
  </tr>
  <tr class="chapter">
    <th colspan="2">Bernoulli</th>
  </tr>
  <tr>
    <td class="formula">\(\operatorname{Bernoulli}(p)\)</td>
    <td><pre><code>\operatorname{Bernoulli}(p)</code></pre></td>
  </tr>
  <tr class="chapter">
    <th colspan="2">Categorical</th>
  </tr>
  <tr>
    <td class="formula">\(\operatorname{Cat}(\mathbf{p})\)</td>
    <td><pre><code>\operatorname{Cat}(\mathbf{p})</code></pre></td>
  </tr>
  <tr class="chapter">
    <th colspan="2">Dirac Delta</th>
  </tr>
  <tr>
    <td class="formula">\(\delta(x)\)</td>
    <td><pre><code>\delta(x)</code></pre></td>
  </tr>
  <tr class="chapter">
    <th colspan="2">常见函数</th>
  </tr>
  <tr>
    <td class="formula">\(\sin x\)</td>
    <td><pre><code>\sin x</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\cos x\)</td>
    <td><pre><code>\cos x</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\tan x\)</td>
    <td><pre><code>\tan x</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\log x\)</td>
    <td><pre><code>\log x</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\ln x\)</td>
    <td><pre><code>\ln x</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\exp(x)\)</td>
    <td><pre><code>\exp(x)</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\max x\)</td>
    <td><pre><code>\max x</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\min x\)</td>
    <td><pre><code>\min x</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(sin(x)\)</td>
    <td><pre><code>sin(x)</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\sin(x)\)</td>
    <td><pre><code>\sin(x)</code></pre></td>
  </tr>
  <tr class="chapter">
    <th colspan="2">指数</th>
  </tr>
  <tr>
    <td class="formula">\(e^x\)</td>
    <td><pre><code>e^x</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\exp(x)\)</td>
    <td><pre><code>\exp(x)</code></pre></td>
  </tr>
  <tr class="chapter">
    <th colspan="2">Softmax</th>
  </tr>
  <tr>
    <td class="formula">\(\operatorname{softmax}(\mathbf{x})\)</td>
    <td><pre><code>\operatorname{softmax}(\mathbf{x})</code></pre></td>
  </tr>
  <tr class="chapter">
    <th colspan="2">Sigmoid</th>
  </tr>
  <tr>
    <td class="formula">\[
\sigma(x)
=
\frac{1}{1+e^{-x}}
\]</td>
    <td><pre><code>\sigma(x)
=
\frac{1}{1+e^{-x}}</code></pre></td>
  </tr>
  <tr class="chapter">
    <th colspan="2">ReLU</th>
  </tr>
  <tr>
    <td class="formula">\[
\operatorname{ReLU}(x)
=
\max(0,x)
\]</td>
    <td><pre><code>\operatorname{ReLU}(x)
=
\max(0,x)</code></pre></td>
  </tr>
  <tr class="chapter">
    <th colspan="2">Loss</th>
  </tr>
  <tr>
    <td class="formula">\(\mathcal{L}\)</td>
    <td><pre><code>\mathcal{L}</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\mathcal{L}_{\mathrm{MSE}}\)</td>
    <td><pre><code>\mathcal{L}_{\mathrm{MSE}}</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\mathcal{L}_{\mathrm{CE}}\)</td>
    <td><pre><code>\mathcal{L}_{\mathrm{CE}}</code></pre></td>
  </tr>
  <tr class="chapter">
    <th colspan="2">参数</th>
  </tr>
  <tr>
    <td class="formula">\(\theta\)</td>
    <td><pre><code>\theta</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\theta,\phi,\psi\)</td>
    <td><pre><code>\theta,\phi,\psi</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(f_\theta(x)\)</td>
    <td><pre><code>f_\theta(x)</code></pre></td>
  </tr>
  <tr class="chapter">
    <th colspan="2">时间变量</th>
  </tr>
  <tr>
    <td class="formula">\(t\in[0,1]\)</td>
    <td><pre><code>t\in[0,1]</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(t=0,1,\ldots,T\)</td>
    <td><pre><code>t=0,1,\ldots,T</code></pre></td>
  </tr>
  <tr class="chapter">
    <th colspan="2">Tensor Shape</th>
  </tr>
  <tr>
    <td class="formula">\[
\mathbf{X}
\in
\mathbb{R}^{B\times N\times d}
\]</td>
    <td><pre><code>\mathbf{X}
\in
\mathbb{R}^{B\times N\times d}</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\[
\mathbf{Q}
\in
\mathbb{R}^{B\times H\times N\times d_h}
\]</td>
    <td><pre><code>\mathbf{Q}
\in
\mathbb{R}^{B\times H\times N\times d_h}</code></pre></td>
  </tr>
  <tr class="chapter">
    <th colspan="2">Einstein 下标形式</th>
  </tr>
  <tr>
    <td class="formula">\[
y_i
=
\sum_j A_{ij}x_j
\]</td>
    <td><pre><code>y_i
=
\sum_j A_{ij}x_j</code></pre></td>
  </tr>
  <tr class="chapter">
    <th colspan="2">矩阵乘法</th>
  </tr>
  <tr>
    <td class="formula">\[
\mathbf{Y}
=
\mathbf{X}\mathbf{W}
\]</td>
    <td><pre><code>\mathbf{Y}
=
\mathbf{X}\mathbf{W}</code></pre></td>
  </tr>
  <tr class="chapter">
    <th colspan="2">Attention</th>
  </tr>
  <tr>
    <td class="formula">\[
\operatorname{Attention}
(\mathbf{Q},\mathbf{K},\mathbf{V})
=
\operatorname{softmax}
\left(
\frac{
\mathbf{Q}\mathbf{K}^{\mathsf T}
}{
\sqrt{d_k}
}
\right)
\mathbf{V}
\]</td>
    <td><pre><code>\operatorname{Attention}
(\mathbf{Q},\mathbf{K},\mathbf{V})
=
\operatorname{softmax}
\left(
\frac{
\mathbf{Q}\mathbf{K}^{\mathsf T}
}{
\sqrt{d_k}
}
\right)
\mathbf{V}</code></pre></td>
  </tr>
  <tr class="chapter">
    <th colspan="2">Flow Matching 常用</th>
  </tr>
  <tr>
    <td class="formula">\[
\mathbf{x}_t
=
(1-t)\mathbf{x}_0+t\mathbf{x}_1
\]</td>
    <td><pre><code>\mathbf{x}_t
=
(1-t)\mathbf{x}_0+t\mathbf{x}_1</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\[
\mathbf{u}_t
=
\frac{\mathrm{d}\mathbf{x}_t}{\mathrm{d}t}
\]</td>
    <td><pre><code>\mathbf{u}_t
=
\frac{\mathrm{d}\mathbf{x}_t}{\mathrm{d}t}</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\mathbf{v}_\theta(\mathbf{x}_t,t)\)</td>
    <td><pre><code>\mathbf{v}_\theta(\mathbf{x}_t,t)</code></pre></td>
  </tr>
  <tr class="chapter">
    <th colspan="2">Diffusion 常用</th>
  </tr>
  <tr>
    <td class="formula">\[
\mathbf{x}_t
=
\alpha_t\mathbf{x}_0
+
\sigma_t\boldsymbol{\epsilon}
\]</td>
    <td><pre><code>\mathbf{x}_t
=
\alpha_t\mathbf{x}_0
+
\sigma_t\boldsymbol{\epsilon}</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\[
\boldsymbol{\epsilon}
\sim
\mathcal{N}(\mathbf{0},\mathbf{I})
\]</td>
    <td><pre><code>\boldsymbol{\epsilon}
\sim
\mathcal{N}(\mathbf{0},\mathbf{I})</code></pre></td>
  </tr>
  <tr class="chapter">
    <th colspan="2">常用特殊符号总表</th>
  </tr>
  <tr>
    <td class="formula">\(\partial\)</td>
    <td><pre><code>\partial</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\nabla\)</td>
    <td><pre><code>\nabla</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\Delta\)</td>
    <td><pre><code>\Delta</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\infty\)</td>
    <td><pre><code>\infty</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\sum\)</td>
    <td><pre><code>\sum</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\prod\)</td>
    <td><pre><code>\prod</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\int\)</td>
    <td><pre><code>\int</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\iint\)</td>
    <td><pre><code>\iint</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\iiint\)</td>
    <td><pre><code>\iiint</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\oint\)</td>
    <td><pre><code>\oint</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\sqrt{x}\)</td>
    <td><pre><code>\sqrt{x}</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\pm\)</td>
    <td><pre><code>\pm</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\mp\)</td>
    <td><pre><code>\mp</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\times\)</td>
    <td><pre><code>\times</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\cdot\)</td>
    <td><pre><code>\cdot</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\div\)</td>
    <td><pre><code>\div</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\circ\)</td>
    <td><pre><code>\circ</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\ast\)</td>
    <td><pre><code>\ast</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\star\)</td>
    <td><pre><code>\star</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\otimes\)</td>
    <td><pre><code>\otimes</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\odot\)</td>
    <td><pre><code>\odot</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\oplus\)</td>
    <td><pre><code>\oplus</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\dagger\)</td>
    <td><pre><code>\dagger</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\ell\)</td>
    <td><pre><code>\ell</code></pre></td>
  </tr>
  <tr class="chapter">
    <th colspan="2">最推荐的统一书写规范</th>
  </tr>
  <tr class="section">
    <th colspan="2">标量</th>
  </tr>
  <tr>
    <td class="formula">\(x,y,z,t\)</td>
    <td><pre><code>x,y,z,t</code></pre></td>
  </tr>
  <tr class="section">
    <th colspan="2">向量</th>
  </tr>
  <tr>
    <td class="formula">\(\mathbf{x}\)</td>
    <td><pre><code>\mathbf{x}</code></pre></td>
  </tr>
  <tr class="section">
    <th colspan="2">矩阵</th>
  </tr>
  <tr>
    <td class="formula">\(\mathbf{A}\)</td>
    <td><pre><code>\mathbf{A}</code></pre></td>
  </tr>
  <tr class="section">
    <th colspan="2">Tensor</th>
  </tr>
  <tr>
    <td class="formula">\(\mathbf{X}\)</td>
    <td><pre><code>\mathbf{X}</code></pre></td>
  </tr>
  <tr class="section">
    <th colspan="2">参数</th>
  </tr>
  <tr>
    <td class="formula">\(\theta,\phi\)</td>
    <td><pre><code>\theta,\phi</code></pre></td>
  </tr>
  <tr class="section">
    <th colspan="2">集合</th>
  </tr>
  <tr>
    <td class="formula">\(\mathcal{X}\)</td>
    <td><pre><code>\mathcal{X}</code></pre></td>
  </tr>
  <tr class="section">
    <th colspan="2">数据集</th>
  </tr>
  <tr>
    <td class="formula">\(\mathcal{D}\)</td>
    <td><pre><code>\mathcal{D}</code></pre></td>
  </tr>
  <tr class="section">
    <th colspan="2">Loss</th>
  </tr>
  <tr>
    <td class="formula">\(\mathcal{L}\)</td>
    <td><pre><code>\mathcal{L}</code></pre></td>
  </tr>
  <tr class="section">
    <th colspan="2">实数空间</th>
  </tr>
  <tr>
    <td class="formula">\(\mathbb{R}\)</td>
    <td><pre><code>\mathbb{R}</code></pre></td>
  </tr>
  <tr class="section">
    <th colspan="2">期望</th>
  </tr>
  <tr>
    <td class="formula">\(\mathbb{E}\)</td>
    <td><pre><code>\mathbb{E}</code></pre></td>
  </tr>
  <tr class="section">
    <th colspan="2">概率</th>
  </tr>
  <tr>
    <td class="formula">\(\mathbb{P}\)</td>
    <td><pre><code>\mathbb{P}</code></pre></td>
  </tr>
  <tr class="section">
    <th colspan="2">分布</th>
  </tr>
  <tr>
    <td class="formula">\(p(\mathbf{x})\)</td>
    <td><pre><code>p(\mathbf{x})</code></pre></td>
  </tr>
  <tr class="section">
    <th colspan="2">随机采样</th>
  </tr>
  <tr>
    <td class="formula">\(\mathbf{x}\sim p(\mathbf{x})\)</td>
    <td><pre><code>\mathbf{x}\sim p(\mathbf{x})</code></pre></td>
  </tr>
  <tr class="section">
    <th colspan="2">梯度</th>
  </tr>
  <tr>
    <td class="formula">\(\nabla_{\theta}\mathcal{L}\)</td>
    <td><pre><code>\nabla_{\theta}\mathcal{L}</code></pre></td>
  </tr>
  <tr class="section">
    <th colspan="2">微分</th>
  </tr>
  <tr>
    <td class="formula">\(\mathrm{d}t\)</td>
    <td><pre><code>\mathrm{d}t</code></pre></td>
  </tr>
  <tr class="section">
    <th colspan="2">偏导</th>
  </tr>
  <tr>
    <td class="formula">\(\partial\)</td>
    <td><pre><code>\partial</code></pre></td>
  </tr>
  <tr class="chapter">
    <th colspan="2">高频组合直接复制</th>
  </tr>
  <tr class="section">
    <th colspan="2">向量属于空间</th>
  </tr>
  <tr>
    <td class="formula">\(\mathbf{x}\in\mathbb{R}^d\)</td>
    <td><pre><code>\mathbf{x}\in\mathbb{R}^d</code></pre></td>
  </tr>
  <tr class="section">
    <th colspan="2">矩阵属于空间</th>
  </tr>
  <tr>
    <td class="formula">\(\mathbf{A}\in\mathbb{R}^{m\times n}\)</td>
    <td><pre><code>\mathbf{A}\in\mathbb{R}^{m\times n}</code></pre></td>
  </tr>
  <tr class="section">
    <th colspan="2">随机变量服从分布</th>
  </tr>
  <tr>
    <td class="formula">\(\mathbf{x}\sim p(\mathbf{x})\)</td>
    <td><pre><code>\mathbf{x}\sim p(\mathbf{x})</code></pre></td>
  </tr>
  <tr class="section">
    <th colspan="2">高斯噪声</th>
  </tr>
  <tr>
    <td class="formula">\[
\boldsymbol{\epsilon}
\sim
\mathcal{N}(\mathbf{0},\mathbf{I})
\]</td>
    <td><pre><code>\boldsymbol{\epsilon}
\sim
\mathcal{N}(\mathbf{0},\mathbf{I})</code></pre></td>
  </tr>
  <tr class="section">
    <th colspan="2">期望 Loss</th>
  </tr>
  <tr>
    <td class="formula">\[
\mathcal{L}
=
\mathbb{E}_{\mathbf{x}\sim p(\mathbf{x})}
[
\ell(\mathbf{x})
]
\]</td>
    <td><pre><code>\mathcal{L}
=
\mathbb{E}_{\mathbf{x}\sim p(\mathbf{x})}
[
\ell(\mathbf{x})
]</code></pre></td>
  </tr>
  <tr class="section">
    <th colspan="2">最优化</th>
  </tr>
  <tr>
    <td class="formula">\[
\theta^*
=
\arg\min_{\theta}
\mathcal{L}(\theta)
\]</td>
    <td><pre><code>\theta^*
=
\arg\min_{\theta}
\mathcal{L}(\theta)</code></pre></td>
  </tr>
  <tr class="section">
    <th colspan="2">参数更新</th>
  </tr>
  <tr>
    <td class="formula">\[
\theta_{t+1}
=
\theta_t
-
\eta
\nabla_{\theta}
\mathcal{L}
\]</td>
    <td><pre><code>\theta_{t+1}
=
\theta_t
-
\eta
\nabla_{\theta}
\mathcal{L}</code></pre></td>
  </tr>
  <tr class="section">
    <th colspan="2">积分形式</th>
  </tr>
  <tr>
    <td class="formula">\[
\mathbf{x}_t
=
\mathbf{x}_0
+
\int_0^t
\mathbf{v}(\mathbf{x}_s,s)
\,\mathrm{d}s
\]</td>
    <td><pre><code>\mathbf{x}_t
=
\mathbf{x}_0
+
\int_0^t
\mathbf{v}(\mathbf{x}_s,s)
\,\mathrm{d}s</code></pre></td>
  </tr>
  <tr class="chapter">
    <th colspan="2">最需要记住的 LaTeX 规律</th>
  </tr>
  <tr>
    <td class="formula">\(_\)</td>
    <td><pre><code>_</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(^\)</td>
    <td><pre><code>^</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\frac{}{}\)</td>
    <td><pre><code>\frac{}{}</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\sqrt{}\)</td>
    <td><pre><code>\sqrt{}</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\mathbf{}\)</td>
    <td><pre><code>\mathbf{}</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\mathcal{}\)</td>
    <td><pre><code>\mathcal{}</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\mathbb{}\)</td>
    <td><pre><code>\mathbb{}</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\mathrm{}\)</td>
    <td><pre><code>\mathrm{}</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\operatorname{}\)</td>
    <td><pre><code>\operatorname{}</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\hat{}\)</td>
    <td><pre><code>\hat{}</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\tilde{}\)</td>
    <td><pre><code>\tilde{}</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\bar{}\)</td>
    <td><pre><code>\bar{}</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\sum\)</td>
    <td><pre><code>\sum</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\prod\)</td>
    <td><pre><code>\prod</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\int\)</td>
    <td><pre><code>\int</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\lim\)</td>
    <td><pre><code>\lim</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\mathbb{E}\)</td>
    <td><pre><code>\mathbb{E}</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\nabla\)</td>
    <td><pre><code>\nabla</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\partial\)</td>
    <td><pre><code>\partial</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\infty\)</td>
    <td><pre><code>\infty</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\in\)</td>
    <td><pre><code>\in</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\sim\)</td>
    <td><pre><code>\sim</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\to\)</td>
    <td><pre><code>\to</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\(\left( \right)\)</td>
    <td><pre><code>\left( \right)</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\[
\begin{aligned}
\]</td>
    <td><pre><code>\begin{aligned}</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\[
\begin{bmatrix}
\]</td>
    <td><pre><code>\begin{bmatrix}</code></pre></td>
  </tr>
  <tr>
    <td class="formula">\[
\begin{cases}
\]</td>
    <td><pre><code>\begin{cases}</code></pre></td>
  </tr>
  </tbody>
</table>
