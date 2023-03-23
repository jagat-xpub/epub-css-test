# EPUBリーダーのCSS仕様適合性テスト

このGitHubページのURL: <https://jagat-xpub.github.io/epub-css-test/>

このGitHubリポジトリのURL: <https://github.com/jagat-xpub/epub-css-test>

## EPUBリーダーのCSS仕様適合性チェックリスト

- [EPUBリーダーのCSS仕様適合性チェックリスト](https://gist.github.com/MurakamiShinyu/e8fa4bb1cbf43c2cec5d47427f8fad1f)

## テストするCSSモジュール一覧

### 「CSSの公式的な定義に含まれるCSSモジュール」から

[CSS Snapshot 2023 -- §2.1. Cascading Style Sheets (CSS) — The Official Definition](https://www.w3.org/TR/css-2023/#css-official) からテストするCSSモジュールをピックアップ

- [CSS Conditional Rules Level 3](https://www.w3.org/TR/css-conditional-3/) -- @supports ルール
  - テスト: <a href="xhtml/css-conditional-3.xhtml">xhtml/css-conditional-3.xhtml</a>
- [Selectors Level 3](https://www.w3.org/TR/selectors-3/)
  - テスト: <a href="xhtml/selectors-3.xhtml">xhtml/selectors-3.xhtml</a>
- [CSS Cascading and Inheritance Level 4](https://www.w3.org/TR/css-cascade-4/) -- all プロパティ, プロパティの値 initial, unset, revert
  - テスト: <a href="xhtml/css-cascade-4.xhtml">xhtml/css-cascade-4.xhtml</a>
- [CSS Values and Units Level 3](https://www.w3.org/TR/css-values-3/) -- 長さの単位 ch, rem, vw, vh, vmin, vmax, Q
  - テスト: <a href="xhtml/css-values-3.xhtml">xhtml/css-values-3.xhtml</a>
- [CSS Custom Properties for Cascading Variables Module Level 1](https://www.w3.org/TR/css-variables-1/) -- CSS変数
  - テスト: <a href="xhtml/css-variables-1.xhtml">xhtml/css-variables-1.xhtml</a>
- [CSS Color Level 4](https://www.w3.org/TR/css-color-4/)
  - テスト: <a href="xhtml/css-color-4.xhtml">xhtml/css-color-4.xhtml</a>
- [CSS Backgrounds and Borders Level 3](https://www.w3.org/TR/css-backgrounds-3/)
  - テスト: <a href="xhtml/css-backgrounds-3.xhtml">xhtml/css-backgrounds-3.xhtml</a>
- [CSS Images Level 3](https://www.w3.org/TR/css-images-3/) -- グラデーション関数, object-fit プロパティ, object-position プロパティ
  - テスト: <a href="xhtml/css-images-3.xhtml">xhtml/css-images-3.xhtml</a>
- [CSS Fonts Level 3](https://www.w3.org/TR/css-fonts-3/)
  - テスト🚧: <a href="xhtml/css-fonts-3.xhtml">xhtml/css-fonts-3.xhtml</a>
- [CSS Writing Modes Level 3](https://www.w3.org/TR/css-writing-modes-3/)
  - テスト: <a href="xhtml/css-writing-modes-3.xhtml">xhtml/css-writing-modes-3.xhtml</a>
- [CSS Multi-column Layout Level 1](https://www.w3.org/TR/css-multicol-1/)
  - テスト: <a href="xhtml/css-multicol-1.xhtml">xhtml/css-multicol-1.xhtml</a>
- [CSS Flexible Box Module Level 1](https://www.w3.org/TR/css-flexbox-1/)
  - テスト: <a href="xhtml/css-flexbox-1.xhtml">xhtml/css-flexbox-1.xhtml</a>
- [CSS User Interface Module Level 3](https://www.w3.org/TR/css-ui-3/) -- box-sizing プロパティ, outline プロパティ
  - テスト🚧: <a href="xhtml/css-ui-3.xhtml">xhtml/css-ui-3.xhtml</a>
- [CSS Containment Module Level 1](https://www.w3.org/TR/css-contain-1/) -- contain プロパティ
  - テスト🚧: <a href="xhtml/css-contain-1.xhtml">xhtml/css-contain-1.xhtml</a>
- [CSS Transforms Level 1](https://www.w3.org/TR/css-transforms-1/) -- transform プロパティ
  - テスト🚧: <a href="xhtml/css-transforms-1.xhtml">xhtml/css-transforms-1.xhtml</a>
- [CSS Compositing and Blending Level 1](https://www.w3.org/TR/compositing-1/) -- mix-blend-mode プロパティなど
  - テスト🚧: <a href="xhtml/compositing-1.xhtml">xhtml/compositing-1.xhtml</a>
- [CSS Counter Styles Level 3](https://www.w3.org/TR/css-counter-styles-3/) -- @counter-style ルール, 定義済みカウンタースタイル cjk-decimal など
  - テスト🚧: <a href="xhtml/css-counter-styles-3.xhtml">xhtml/css-counter-styles-3.xhtml</a>

### 「かなり安定しているが実装経験が限定的なCSSモジュール」から

[CSS Snapshot 2023 -- §2.2. Fairly Stable Modules with limited implementation experience](https://www.w3.org/TR/css-2023/#fairly-stable) からテストするCSSモジュールをピックアップ

- [CSS Fragmentation Module Level 3](https://www.w3.org/TR/css-break-3/)
  - テスト🚧: <a href="xhtml/css-break-3.xhtml">xhtml/css-break-3.xhtml</a>
- [CSS Text Module Level 3](https://www.w3.org/TR/css-text-3/)
  - テスト🚧: <a href="xhtml/css-text-3.xhtml">xhtml/css-text-3.xhtml</a>
- [CSS Text Decoration Level 3](https://www.w3.org/TR/css-text-decor-3/)
  - テスト🚧: <a href="xhtml/css-text-decor-3.xhtml">xhtml/css-text-decor-3.xhtml</a>

### 「大まかな相互運用性のあるCSSモジュール」から

[CSS Snapshot 2023 -- §2.3. Modules with Rough Interoperability](https://www.w3.org/TR/css-2023/#rough-interop) からテストするCSSモジュールをピックアップ

- [CSS Grid Layout Module Level 1](https://www.w3.org/TR/css-grid-1/)
  - テスト: <a href="xhtml/css-grid-1.xhtml">xhtml/css-grid-1.xhtml</a>
- [CSS Box Sizing Level 3](https://www.w3.org/TR/css-sizing-3/) -- width・height プロパティの値 min-content と max-content
  - テスト🚧: <a href="xhtml/css-sizing-3.xhtml">xhtml/css-sizing-3.xhtml</a>
- [CSS Logical Properties and Values Level 1](https://www.w3.org/TR/css-logical-1/) -- 論理プロパティ
  - テスト: <a href="xhtml/css-logical-1.xhtml">xhtml/css-logical-1.xhtml</a>
- [CSS Conditional Rules Module Level 4](https://www.w3.org/TR/css-conditional-4/) -- @supports selector() ルール
  - テスト🚧: <a href="xhtml/css-conditional-4.xhtml">xhtml/css-conditional-4.xhtml</a>
- [CSS Cascading and Inheritance Level 5](https://www.w3.org/TR/css-cascade-5/) -- @layer ルール
  - テスト🚧: <a href="xhtml/css-cascade-5.xhtml">xhtml/css-cascade-5.xhtml</a>

### CSS Snapshot 2023 に載っていないが、最新のブラウザで利用できるもの

- [Selectors Level 4](https://www.w3.org/TR/selectors-4/) -- 擬似クラス :is(), :where(), :has()
  - テスト🚧: <a href="xhtml/selectors-4.xhtml">xhtml/selectors-4.xhtml</a>
