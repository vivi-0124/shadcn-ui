---
title: ボタン
description: ボタンまたはボタンのような見た目のコンポーネントを表示します。
component: true
---

<ComponentPreview
  name="button-demo"
  title="異なるバリアントとサイズを持つボタン。"
  description="異なるバリアントとサイズを持つボタン。"
/>

## インストール

<CodeTabs>

<TabsList>
  <TabsTrigger value="cli">CLI</TabsTrigger>
  <TabsTrigger value="manual">手動</TabsTrigger>
</TabsList>
<TabsContent value="cli">

```bash
npx shadcn@latest add button
```

</TabsContent>

<TabsContent value="manual">

<Steps>

<Step>以下のコードをプロジェクトにコピー＆ペーストしてください。</Step>

<ComponentSource name="button" title="components/ui/button.tsx" />

<Step>プロジェクトの設定に合わせてインポートパスを更新してください。</Step>

</Steps>

</TabsContent>

</CodeTabs>

## 使用方法

```tsx showLineNumbers
import { Button } from "@/components/ui/button"
```

```tsx showLineNumbers
<Button variant="default" size="default">
  ボタン
</Button>
```
