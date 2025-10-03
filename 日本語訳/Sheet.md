---
title: シート
description: 画面のメインコンテンツを補完するコンテンツを表示するためにDialogコンポーネントを拡張します。
component: true
links:
  doc: https://www.radix-ui.com/docs/primitives/components/dialog
  api: https://www.radix-ui.com/docs/primitives/components/dialog#api-reference
---

<ComponentPreview
  name="sheet-demo"
  title="異なる側面とコンテンツを持つシート。"
  description="異なる側面とコンテンツを持つシート。"
/>

## インストール

<CodeTabs>

<TabsList>
  <TabsTrigger value="cli">CLI</TabsTrigger>
  <TabsTrigger value="manual">手動</TabsTrigger>
</TabsList>
<TabsContent value="cli">

```bash
npx shadcn@latest add sheet
```

</TabsContent>

<TabsContent value="manual">

<Steps>

<Step>以下の依存関係をインストールしてください：</Step>

```bash
npm install @radix-ui/react-dialog
```

<Step>以下のコードをプロジェクトにコピー＆ペーストしてください。</Step>

<ComponentSource name="sheet" title="components/ui/sheet.tsx" />

<Step>プロジェクトの設定に合わせてインポートパスを更新してください。</Step>

</Steps>

</TabsContent>

</CodeTabs>

## 使用方法

```tsx showLineNumbers
import {
  Sheet,
  SheetContent,
  SheetDescription,
  SheetHeader,
  SheetTitle,
  SheetTrigger,
} from "@/components/ui/sheet"
```

```tsx showLineNumbers
<Sheet>
  <SheetTrigger>開く</SheetTrigger>
  <SheetContent>
    <SheetHeader>
      <SheetTitle>本当によろしいですか？</SheetTitle>
      <SheetDescription>
        この操作は取り消すことができません。これにより、アカウントが完全に削除され、
        サーバーからデータが削除されます。
      </SheetDescription>
    </SheetHeader>
  </SheetContent>
</Sheet>
```
