---
title: ラベル
description: コントロールに関連付けられたアクセシブルなラベルをレンダリングします。
component: true
links:
  doc: https://www.radix-ui.com/docs/primitives/components/label
  api: https://www.radix-ui.com/docs/primitives/components/label#api-reference
---

<ComponentPreview
  name="label-demo"
  title="異なる状態を持つラベル。"
  description="異なる状態を持つラベル。"
/>

## インストール

<CodeTabs>

<TabsList>
  <TabsTrigger value="cli">CLI</TabsTrigger>
  <TabsTrigger value="manual">手動</TabsTrigger>
</TabsList>
<TabsContent value="cli">

```bash
npx shadcn@latest add label
```

</TabsContent>

<TabsContent value="manual">

<Steps>

<Step>以下の依存関係をインストールしてください：</Step>

```bash
npm install @radix-ui/react-label
```

<Step>以下のコードをプロジェクトにコピー＆ペーストしてください。</Step>

<ComponentSource name="label" title="components/ui/label.tsx" />

<Step>プロジェクトの設定に合わせてインポートパスを更新してください。</Step>

</Steps>

</TabsContent>

</CodeTabs>

## 使用方法

```tsx showLineNumbers
import { Label } from "@/components/ui/label"
```

```tsx showLineNumbers
<Label htmlFor="email">メールアドレス</Label>
```
