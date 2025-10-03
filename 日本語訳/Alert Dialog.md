---
title: アラートダイアログ
description: 重要なコンテンツでユーザーを中断し、応答を期待するモーダルダイアログ。
featured: true
component: true
links:
  doc: https://www.radix-ui.com/docs/primitives/components/alert-dialog
  api: https://www.radix-ui.com/docs/primitives/components/alert-dialog#api-reference
---

<ComponentPreview
  name="alert-dialog-demo"
  title="キャンセルと続行ボタンを持つアラートダイアログ。"
  description="キャンセルと続行ボタンを持つアラートダイアログ。"
/>

## インストール

<CodeTabs>

<TabsList>
  <TabsTrigger value="cli">CLI</TabsTrigger>
  <TabsTrigger value="manual">手動</TabsTrigger>
</TabsList>
<TabsContent value="cli">

```bash
npx shadcn@latest add alert-dialog
```

</TabsContent>

<TabsContent value="manual">

<Steps>

<Step>以下の依存関係をインストールしてください：</Step>

```bash
npm install @radix-ui/react-alert-dialog
```

<Step>以下のコードをプロジェクトにコピー＆ペーストしてください。</Step>

<ComponentSource name="alert-dialog" title="components/ui/alert-dialog.tsx" />

<Step>プロジェクトの設定に合わせてインポートパスを更新してください。</Step>

</Steps>

</TabsContent>

</CodeTabs>

## 使用方法

```tsx showLineNumbers
import {
  AlertDialog,
  AlertDialogAction,
  AlertDialogCancel,
  AlertDialogContent,
  AlertDialogDescription,
  AlertDialogFooter,
  AlertDialogHeader,
  AlertDialogTitle,
  AlertDialogTrigger,
} from "@/components/ui/alert-dialog"
```

```tsx showLineNumbers
<AlertDialog>
  <AlertDialogTrigger>開く</AlertDialogTrigger>
  <AlertDialogContent>
    <AlertDialogHeader>
      <AlertDialogTitle>本当によろしいですか？</AlertDialogTitle>
      <AlertDialogDescription>
        この操作は取り消すことができません。これにより、アカウントが完全に削除され、
        サーバーからデータが削除されます。
      </AlertDialogDescription>
    </AlertDialogHeader>
    <AlertDialogFooter>
      <AlertDialogCancel>キャンセル</AlertDialogCancel>
      <AlertDialogAction>続行</AlertDialogAction>
    </AlertDialogFooter>
  </AlertDialogContent>
</AlertDialog>
```
