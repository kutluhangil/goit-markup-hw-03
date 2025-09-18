<h1>GOIT Markup Homework #03 — Block Model & Flexbox</h1>

<p>
  This homework focuses on the <strong>CSS block (box) model</strong> and <strong>Flexbox</strong> while keeping
  semantic HTML, clean structure, and consistent spacing. The project introduces a shared
  <code>.container</code> utility, section spacing, a header bottom border, and list-based layouts aligned with the design.
</p>

<p><strong>Live Demo:</strong> <a href="#" target="_blank" rel="noopener">https://kutluhangil.github.io/goit-markup-hw-03/</a></p>

<hr>

<h2>📚 Table of Contents</h2>
<ol>
  <li><a href="#about">About the Project</a></li>
  <li><a href="#acceptance">Acceptance Criteria (Mentor Checklist)</a></li>
  <li><a href="#design">Design & Layout Rules</a></li>
  <li><a href="#structure">Project Structure</a></li>
  <li><a href="#validation">Validation & Formatting</a></li>
  <li><a href="#setup">How to Run</a></li>
</ol>

<hr>

<h2 id="about">📖 About the Project</h2>
<ul>
  <li>Images live in <code>images/</code>, styles in <code>css/styles.css</code>.</li>
  <li>Global resets for <code>h1…h6</code>, <code>p</code>, <code>ul</code> with a modern normalizer (<strong>modern-normalize</strong>).</li>
  <li>Common <code>.container</code> (width: <strong>1158px</strong>) centers and constrains content.</li>
  <li>Sections are stacked like a book (no external margins), each using a shared <code>.section</code> with <strong>120px</strong> top/bottom padding.</li>
  <li>Flexbox is used where appropriate (header, nav, horizontal lists inside sections).</li>
</ul>

<hr>

<h2 id="acceptance">✅ Acceptance Criteria (Mentor Checklist)</h2>

<h3>A. Project</h3>
<ul>
  <li><strong>A1</strong> — Project root contains an <code>images/</code> folder with all images.</li>
  <li><strong>A2</strong> — Project root contains a <code>css/</code> folder with a stylesheet.</li>
  <li><strong>A3</strong> — All styles are in a single file: <code>css/styles.css</code>.</li>
  <li><strong>A4</strong> — File names use only lowercase Latin letters and hyphens (no spaces, uppercase, or transliteration).</li>
  <li><strong>A5</strong> — Source code is formatted with <strong>Prettier</strong>.</li>
  <li><strong>A6</strong> — All images and text content are taken from the layout.</li>
  <li><strong>A7</strong> — <strong>modern-normalize</strong> is enabled.</li>
  <li><strong>A8</strong> — Code follows the provided guidelines.</li>
</ul>

<h3 id="design">B. Design & Layout (Block Model / Flexbox)</h3>
<ul>
  <li><strong>B1</strong> — Allow global resets using tag selectors for <code>h1…h6</code>, <code>p</code>, and <code>ul</code>.</li>
  <li><strong>B2</strong> — Elements must not have exterior margins that break container layout.</li>
  <li><strong>B3</strong> — Use <code>margin</code> for vertical gaps <em>between adjacent elements</em>.</li>
  <li><strong>B4</strong> — Use <code>padding</code> to create inner spacing between content and borders.</li>
  <li><strong>B5</strong> — All <code>margin</code> and <code>padding</code> values must exactly match the design.</li>
  <li><strong>B6</strong> — Provide a shared <code>.container</code> utility for centering & max width.</li>
  <li><strong>B8</strong> — <code>.container</code> width is <strong>1158px</strong> to match the layout.</li>
  <li><strong>B9</strong> — <code>.container</code> wraps main regions (header, footer, sections).</li>
  <li><strong>B10</strong> — Use Flexbox only where needed (e.g., header layout, nav, horizontal lists in sections).</li>
  <li><strong>B11</strong> — Final rendered sizes in the browser match the design.</li>
  <li><strong>B12</strong> — No fixed heights; height is determined by content.</li>
  <li><strong>B13</strong> — Header includes a subtle <strong>bottom border</strong> (zoom the design to see it).</li>
  <li><strong>B14</strong> — Sections stack like a book without external margins.</li>
  <li><strong>B15</strong> — All sections use the same <code>.section</code> class with <strong>120px</strong> top & bottom padding.</li>
  <li><strong>B16</strong> — Portfolio cards in the “Our Portfolio” section have a <strong>bottom-only border</strong>.</li>
</ul>

<hr>

<h2 id="structure">📁 Project Structure</h2>
<pre><code>.
├─ index.html
├─ css/
│  └─ styles.css
├─ images/
│  ├─ ...
└─ README.md
</code></pre>

<hr>

<h2 id="validation">🧪 Validation & Formatting</h2>
<ul>
  <li>Use <strong>Prettier</strong> for code formatting.</li>
  <li>Enable <strong>modern-normalize</strong> (via CDN or local copy).</li>
  <li>Check spacing, borders, and sizes against the layout precisely.</li>
</ul>

<hr>

<h2 id="setup">🚀 How to Run</h2>
<ol>
  <li>Clone the repo and open <code>index.html</code> in your browser.</li>
  <li>Ensure paths to <code>css/styles.css</code> and assets in <code>images/</code> are correct.</li>
  <li>Publish via GitHub Pages (Settings → Pages) and add the live link to the repo’s <em>About → Website</em>.</li>
</ol>

<hr>

<p><em>Tip:</em> Be strict with the box model: margins create outer gaps between components; padding creates inner spacing. Use Flexbox intentionally for horizontal alignment; don’t force heights.</p>
