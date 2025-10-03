---
title: トグル
description: オンまたはオフのいずれかになることができる2状態ボタン。
component: true
links:
  doc: https://www.radix-ui.com/docs/primitives/components/toggle
  api: https://www.radix-ui.com/docs/primitives/components/toggle#api-reference
---

<ComponentPreview
  name="toggle-demo"
  title="異なるバリアントとサイズを持つトグル。"
  description="異なるバリアントとサイズを持つトグル。"
/>

## インストール

<CodeTabs>

<TabsList>
  <TabsTrigger value="cli">CLI</TabsTrigger>
  <TabsTrigger value="manual">手動</TabsTrigger>
</TabsList>
<TabsContent value="cli">

```bash
npx shadcn@latest add toggle
```

</TabsContent>

<TabsContent value="manual">

<Steps>

<Step>以下の依存関係をインストールしてください：</Step>

```bash
npm install @radix-ui/react-toggle
```

<Step>以下のコードをプロジェクトにコピー＆ペーストしてください。</Step>

<ComponentSource name="toggle" title="components/ui/toggle.tsx" />

<Step>プロジェクトの設定に合わせてインポートパスを更新してください。</Step>

</Steps>

</TabsContent>

</CodeTabs>

## 使用方法

```tsx showLineNumbers
import { Toggle } from "@/components/ui/toggle"
```

```tsx showLineNumbers
<Toggle>トグル</Toggle>
```
