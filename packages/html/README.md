# design-system-sample（HTML版）

design-system-sampleのHTML版です。
純粋なHTMLをベースに、Tailwind CSSを使用してデザイントークンとコンポーネントを実装しています。

## コンセプト

<img alt="この画像では、UI開発を効率化し、デザイナーと実装者間のコミュニケーションを円滑にするためのデザインシステムサンプルについて説明しています。FigmaとTailwind CSSを活用し、デザインのルールを形式知化。デザイントークンを共通言語とすることで、一貫性のあるUIを効率的に開発できる環境を整備することを目指しています。" src="../../docs/packages/html/image_html_readme_1.webp" style="width: 100%; height: auto;" height="2160" width="3840" />

- [Figmaファイル](https://www.figma.com/design/jYvAjaxrZXhx57FNuDAv3Q/design-system-sample?node-id=4006-1775&t=zGfBsyz0AaqGoA6m-0)
- [GitHubリポジトリ](https://github.com/d120145/design-system-sample)

<img alt="この画像では、デザインの一貫性を保つための「デザイントークン」という手法が解説されています。これは、具体的なデザインの値を「プリミティブトークン」と使用場面を示す「セマンティックトークン」の2段階で定義するものです。これにより、誰でも判断に迷わず、効率的に意匠の一貫性を保った設計や実装が可能になります。" src="../../docs/packages/html/image_html_readme_2.webp" style="width: 100%; height: auto;" height="2160" width="3840" />

- [デザイントークンに関する記事の執筆例](https://tech.excite.co.jp/entry/2024/12/04/082041)

<img alt="この画像では、デザイントークンの定義方法を紹介しています。FigmaではVariablesとStyles、Tailwind CSSではTheme variables を使用し、ツールを超えた連続的なルール化を実現。FigmaのScope機能で誤った適用を防止し、デザイントークンを共通言語化しています。" src="../../docs/packages/html/image_html_readme_3.webp" style="width: 100%; height: auto;" height="2160" width="3840" />

<img alt="この画像では、コンポーネントの定義方法を紹介しています。HTMLタグと対になるパーツをコンポーネント化。Figma Variants でhoverやアイコンの有無といった状態をシミュレーション可能とし、パズルのように組み合わせてUIを設計・実装できる状態を構築。Tailwind CSSではComponents classとしてスタイルを定義しています。" src="../../docs/packages/html/image_html_readme_4.webp" style="width: 100%; height: auto;" height="2160" width="3840" />

<img alt="この画像では、Tailwind CSS採用に伴う可読性低下の対策を紹介しています。Prettierとprettier-plugin-tailwindcssを導入し、pre-commitでPrettierを実行し、ユーティリティクラスの並び替えを自動化。GitHub Actionsでコードスタイルのチェックも実施し、UI開発の仕組み化を推進しています" src="../../docs/packages/html/image_html_readme_5.webp" style="width: 100%; height: auto;" height="2160" width="3840" />

- [prettier-plugin-tailwindcssに関して執筆した記事](https://tech.excite.co.jp/entry/2024/06/10/145429)
- [pre-commitに関して執筆した記事](https://tech.excite.co.jp/entry/2024/06/24/125911)
