---
title: アコーディオン
description: 各セクションのコンテンツを表示するインタラクティブな見出しの縦積みセット。
component: true
links:
  doc: https://www.radix-ui.com/docs/primitives/components/accordion
  api: https://www.radix-ui.com/docs/primitives/components/accordion#api-reference
---

<ComponentPreview
  name="accordion-demo"
  className="[&_.preview>[data-orientation=vertical]]:sm:max-w-[80%] **:[.preview]:min-h-[400px]"
  description="3つのアイテムを持つアコーディオン"
  align="start"
/>

## インストール

<CodeTabs>

<TabsList>
  <TabsTrigger value="cli">CLI</TabsTrigger>
  <TabsTrigger value="manual">手動</TabsTrigger>
</TabsList>

<TabsContent value="cli">

```bash
npx shadcn@latest add accordion
```

</TabsContent>

<TabsContent value="manual">

<Steps>

<Step>以下の依存関係をインストールしてください：</Step>

```bash
npm install @radix-ui/react-accordion
```

<Step>以下のコードをプロジェクトにコピー＆ペーストしてください。</Step>

<ComponentSource name="accordion" title="components/ui/accordion.tsx" />

<Step>プロジェクトの設定に合わせてインポートパスを更新してください。</Step>

</Steps>

</TabsContent>

</CodeTabs>

## 使用方法

```tsx showLineNumbers
import {
  Accordion,
  AccordionContent,
  AccordionItem,
  AccordionTrigger,
} from "@/components/ui/accordion"
```

```tsx showLineNumbers
<Accordion type="single" collapsible>
  <AccordionItem value="item-1">
    <AccordionTrigger>アクセシブルですか？</AccordionTrigger>
    <AccordionContent>
      はい。WAI-ARIAデザインパターンに準拠しています。
    </AccordionContent>
  </AccordionItem>
</Accordion>
```
