---
title: セパレーター
description: コンテンツを視覚的または意味的に分離します。
component: true
---

<ComponentPreview
  name="separator-demo"
  title="異なる向きを持つセパレーター。"
  description="異なる向きを持つセパレーター。"
/>

## インストール

<CodeTabs>

<TabsList>
  <TabsTrigger value="cli">CLI</TabsTrigger>
  <TabsTrigger value="manual">手動</TabsTrigger>
</TabsList>
<TabsContent value="cli">

```bash
npx shadcn@latest add separator
```

</TabsContent>

<TabsContent value="manual">

<Steps>

<Step>以下のコードをプロジェクトにコピー＆ペーストしてください。</Step>

<ComponentSource name="separator" title="components/ui/separator.tsx" />

<Step>プロジェクトの設定に合わせてインポートパスを更新してください。</Step>

</Steps>

</TabsContent>

</CodeTabs>

## 使用方法

```tsx showLineNumbers
import { Separator } from "@/components/ui/separator"
```

```tsx showLineNumbers
<div>
  <div className="space-y-1">
    <h4 className="text-sm font-medium leading-none">Radix Primitives</h4>
    <p className="text-sm text-muted-foreground">
      オープンソースのUIコンポーネントライブラリ。
    </p>
  </div>
  <Separator className="my-4" />
  <div className="flex h-5 items-center space-x-4 text-sm">
    <div>ブログ</div>
    <Separator orientation="vertical" />
    <div>ドキュメント</div>
    <Separator orientation="vertical" />
    <div>ソース</div>
  </div>
</div>
```
