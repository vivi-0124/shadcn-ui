---
title: ツールチップ
description: 要素がキーボードフォーカスを受け取るか、マウスがその上にホバーしたときに、その要素に関連する情報を表示するポップアップ。
component: true
links:
  doc: https://www.radix-ui.com/docs/primitives/components/tooltip
  api: https://www.radix-ui.com/docs/primitives/components/tooltip#api-reference
---

<ComponentPreview
  name="tooltip-demo"
  title="異なるコンテンツと位置を持つツールチップ。"
  description="異なるコンテンツと位置を持つツールチップ。"
/>

## インストール

<CodeTabs>

<TabsList>
  <TabsTrigger value="cli">CLI</TabsTrigger>
  <TabsTrigger value="manual">手動</TabsTrigger>
</TabsList>
<TabsContent value="cli">

```bash
npx shadcn@latest add tooltip
```

</TabsContent>

<TabsContent value="manual">

<Steps>

<Step>以下の依存関係をインストールしてください：</Step>

```bash
npm install @radix-ui/react-tooltip
```

<Step>以下のコードをプロジェクトにコピー＆ペーストしてください。</Step>

<ComponentSource name="tooltip" title="components/ui/tooltip.tsx" />

<Step>プロジェクトの設定に合わせてインポートパスを更新してください。</Step>

</Steps>

</TabsContent>

</CodeTabs>

## 使用方法

```tsx showLineNumbers
import {
  Tooltip,
  TooltipContent,
  TooltipProvider,
  TooltipTrigger,
} from "@/components/ui/tooltip"
```

```tsx showLineNumbers
<TooltipProvider>
  <Tooltip>
    <TooltipTrigger>ホバー</TooltipTrigger>
    <TooltipContent>
      <p>ライブラリに追加</p>
    </TooltipContent>
  </Tooltip>
</TooltipProvider>
```
