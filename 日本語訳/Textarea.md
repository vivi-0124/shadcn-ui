---
title: テキストエリア
description: フォームのテキストエリアまたはテキストエリアのような見た目のコンポーネントを表示します。
component: true
---

<ComponentPreview
  name="textarea-demo"
  title="異なる状態を持つテキストエリア。"
  description="異なる状態を持つテキストエリア。"
/>

## インストール

<CodeTabs>

<TabsList>
  <TabsTrigger value="cli">CLI</TabsTrigger>
  <TabsTrigger value="manual">手動</TabsTrigger>
</TabsList>
<TabsContent value="cli">

```bash
npx shadcn@latest add textarea
```

</TabsContent>

<TabsContent value="manual">

<Steps>

<Step>以下のコードをプロジェクトにコピー＆ペーストしてください。</Step>

<ComponentSource name="textarea" title="components/ui/textarea.tsx" />

<Step>プロジェクトの設定に合わせてインポートパスを更新してください。</Step>

</Steps>

</TabsContent>

</CodeTabs>

## 使用方法

```tsx showLineNumbers
import { Textarea } from "@/components/ui/textarea"
```

```tsx showLineNumbers
<Textarea placeholder="ここにメッセージを入力してください。" />
```
