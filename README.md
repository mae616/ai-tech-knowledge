# @mae616/ai-tech-knowledge

フレームワーク・ライブラリ・ツールごとの技術判断軸を、Claude Code や AI エージェントに提供するスキルパッケージです。関連する会話で自動的にスキルが適用されます。

関連: https://github.com/mae616/ai-template

## インストール

```bash
npx skills add mae616/ai-tech-knowledge
```

## 含まれるスキル

| スキル | 自動適用されるタイミング |
|--------|------------------------|
| `react` | React/Next.js のコンポーネント設計、状態管理、レンダリング、SSR/RSC の相談 |
| `astro` | Astro プロジェクトの設計・実装、Islands Architecture、SSG/SSR の相談 |
| `svelte` | Svelte/SvelteKit の設計・パフォーマンス・構造の相談 |
| `tailwind` | Tailwind CSS の設計、クラス設計、デザインシステムの相談 |
| `threejs` | Three.js/WebGL/R3F を使ったウェブ 3D 表現の相談 |
| `gsap` | GSAP アニメーション、ScrollTrigger、スクロール連動の相談 |
| `p5js` | p5.js クリエイティブコーディング、ジェネラティブアートの相談 |
| `playwright` | Playwright E2E テスト設計、ブラウザテストの相談 |
| `blender` | Blender MCP を使った 3D モデリング・シーン構築の相談 |

## 仕組み

1. スキルを**インストール**する
2. 関連する会話で**自動的に**スキルが適用される（明示的な呼び出しは不要）

### 会話の例

```
ユーザー: 「React でダッシュボードのコンポーネント設計をしたい」
→ react スキルが適用

ユーザー: 「Astro で SSG サイトを作りたい」
→ astro スキルが適用

ユーザー: 「Three.js でパーティクルエフェクトを実装したい」
→ threejs スキルが適用

ユーザー: 「GSAP でスクロール連動アニメーションを作りたい」
→ gsap スキルが適用

ユーザー: 「Playwright で E2E テストを書きたい」
→ playwright スキルが適用
```

## ファイル構成

```
ai-tech-knowledge/
├── skills/
│   ├── astro/
│   │   └── SKILL.md
│   ├── blender/
│   │   └── SKILL.md
│   ├── gsap/
│   │   └── SKILL.md
│   ├── p5js/
│   │   └── SKILL.md
│   ├── playwright/
│   │   └── SKILL.md
│   ├── react/
│   │   └── SKILL.md
│   ├── svelte/
│   │   └── SKILL.md
│   ├── tailwind/
│   │   └── SKILL.md
│   └── threejs/
│       └── SKILL.md
├── package.json
├── README.md
└── LICENSE.txt
```

## ライセンス

MIT
