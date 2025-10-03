---
title: スクロールエリア
description: カスタムのクロスブラウザスタイリングのためにネイティブスクロール機能を拡張します。
component: true
links:
  doc: https://www.radix-ui.com/docs/primitives/components/scroll-area
  api: https://www.radix-ui.com/docs/primitives/components/scroll-area#api-reference
---

<ComponentPreview
  name="scroll-area-demo"
  title="異なるコンテンツを持つスクロールエリア。"
  description="異なるコンテンツを持つスクロールエリア。"
/>

## インストール

<CodeTabs>

<TabsList>
  <TabsTrigger value="cli">CLI</TabsTrigger>
  <TabsTrigger value="manual">手動</TabsTrigger>
</TabsList>
<TabsContent value="cli">

```bash
npx shadcn@latest add scroll-area
```

</TabsContent>

<TabsContent value="manual">

<Steps>

<Step>以下の依存関係をインストールしてください：</Step>

```bash
npm install @radix-ui/react-scroll-area
```

<Step>以下のコードをプロジェクトにコピー＆ペーストしてください。</Step>

<ComponentSource name="scroll-area" title="components/ui/scroll-area.tsx" />

<Step>プロジェクトの設定に合わせてインポートパスを更新してください。</Step>

</Steps>

</TabsContent>

</CodeTabs>

## 使用方法

```tsx showLineNumbers
import { ScrollArea } from "@/components/ui/scroll-area"
```

```tsx showLineNumbers
<ScrollArea className="h-72 w-48 rounded-md border">
  <div className="p-4">
    <h4 className="mb-4 text-sm font-medium leading-none">タグ</h4>
    {tags.map((tag) => (
      <div key={tag} className="text-sm">
        {tag}
      </div>
    ))}
  </div>
</ScrollArea>
```
