---
title: インプット
description: フォームの入力フィールドまたは入力フィールドのような見た目のコンポーネントを表示します。
component: true
---

<ComponentPreview
  name="input-demo"
  title="異なるタイプと状態を持つインプット。"
  description="異なるタイプと状態を持つインプット。"
/>

## インストール

<CodeTabs>

<TabsList>
  <TabsTrigger value="cli">CLI</TabsTrigger>
  <TabsTrigger value="manual">手動</TabsTrigger>
</TabsList>
<TabsContent value="cli">

```bash
npx shadcn@latest add input
```

</TabsContent>

<TabsContent value="manual">

<Steps>

<Step>以下のコードをプロジェクトにコピー＆ペーストしてください。</Step>

<ComponentSource name="input" title="components/ui/input.tsx" />

<Step>プロジェクトの設定に合わせてインポートパスを更新してください。</Step>

</Steps>

</TabsContent>

</CodeTabs>

## 使用方法

```tsx showLineNumbers
import { Input } from "@/components/ui/input"
```

```tsx showLineNumbers
<Input type="email" placeholder="メールアドレス" />
```
