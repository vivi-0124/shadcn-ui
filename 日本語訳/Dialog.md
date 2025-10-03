---
title: ダイアログ
description: プライマリウィンドウまたは別のダイアログウィンドウの上に重ねられたウィンドウ。
component: true
links:
  doc: https://www.radix-ui.com/docs/primitives/components/dialog
  api: https://www.radix-ui.com/docs/primitives/components/dialog#api-reference
---

<ComponentPreview
  name="dialog-demo"
  title="トリガー、コンテンツ、アクションを持つダイアログ。"
  description="トリガー、コンテンツ、アクションを持つダイアログ。"
/>

## インストール

<CodeTabs>

<TabsList>
  <TabsTrigger value="cli">CLI</TabsTrigger>
  <TabsTrigger value="manual">手動</TabsTrigger>
</TabsList>
<TabsContent value="cli">

```bash
npx shadcn@latest add dialog
```

</TabsContent>

<TabsContent value="manual">

<Steps>

<Step>以下の依存関係をインストールしてください：</Step>

```bash
npm install @radix-ui/react-dialog
```

<Step>以下のコードをプロジェクトにコピー＆ペーストしてください。</Step>

<ComponentSource name="dialog" title="components/ui/dialog.tsx" />

<Step>プロジェクトの設定に合わせてインポートパスを更新してください。</Step>

</Steps>

</TabsContent>

</CodeTabs>

## 使用方法

```tsx showLineNumbers
import {
  Dialog,
  DialogContent,
  DialogDescription,
  DialogFooter,
  DialogHeader,
  DialogTitle,
  DialogTrigger,
} from "@/components/ui/dialog"
```

```tsx showLineNumbers
<Dialog>
  <DialogTrigger>開く</DialogTrigger>
  <DialogContent>
    <DialogHeader>
      <DialogTitle>本当によろしいですか？</DialogTitle>
      <DialogDescription>
        この操作は取り消すことができません。これにより、アカウントが完全に削除され、
        サーバーからデータが削除されます。
      </DialogDescription>
    </DialogHeader>
    <DialogFooter>
      <Button type="submit">確認</Button>
    </DialogFooter>
  </DialogContent>
</Dialog>
```
