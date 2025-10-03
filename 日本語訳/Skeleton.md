---
title: スケルトン
description: コンテンツが読み込まれている間にプレースホルダーを表示するために使用します。
component: true
---

<ComponentPreview
  name="skeleton-demo"
  title="異なる形状とサイズを持つスケルトン。"
  description="異なる形状とサイズを持つスケルトン。"
/>

## インストール

<CodeTabs>

<TabsList>
  <TabsTrigger value="cli">CLI</TabsTrigger>
  <TabsTrigger value="manual">手動</TabsTrigger>
</TabsList>
<TabsContent value="cli">

```bash
npx shadcn@latest add skeleton
```

</TabsContent>

<TabsContent value="manual">

<Steps>

<Step>以下のコードをプロジェクトにコピー＆ペーストしてください。</Step>

<ComponentSource name="skeleton" title="components/ui/skeleton.tsx" />

<Step>プロジェクトの設定に合わせてインポートパスを更新してください。</Step>

</Steps>

</TabsContent>

</CodeTabs>

## 使用方法

```tsx showLineNumbers
import { Skeleton } from "@/components/ui/skeleton"
```

```tsx showLineNumbers
<div className="flex items-center space-x-4">
  <Skeleton className="h-12 w-12 rounded-full" />
  <div className="space-y-2">
    <Skeleton className="h-4 w-[250px]" />
    <Skeleton className="h-4 w-[200px]" />
  </div>
</div>
```
