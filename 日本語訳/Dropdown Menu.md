---
title: ドロップダウンメニュー
description: ボタンによってトリガーされる、アクションや機能のセットなどのメニューをユーザーに表示します。
component: true
links:
  doc: https://www.radix-ui.com/docs/primitives/components/dropdown-menu
  api: https://www.radix-ui.com/docs/primitives/components/dropdown-menu#api-reference
---

<ComponentPreview
  name="dropdown-menu-demo"
  title="異なるアイテムを持つドロップダウンメニュー。"
  description="異なるアイテムを持つドロップダウンメニュー。"
/>

## インストール

<CodeTabs>

<TabsList>
  <TabsTrigger value="cli">CLI</TabsTrigger>
  <TabsTrigger value="manual">手動</TabsTrigger>
</TabsList>
<TabsContent value="cli">

```bash
npx shadcn@latest add dropdown-menu
```

</TabsContent>

<TabsContent value="manual">

<Steps>

<Step>以下の依存関係をインストールしてください：</Step>

```bash
npm install @radix-ui/react-dropdown-menu
```

<Step>以下のコードをプロジェクトにコピー＆ペーストしてください。</Step>

<ComponentSource name="dropdown-menu" title="components/ui/dropdown-menu.tsx" />

<Step>プロジェクトの設定に合わせてインポートパスを更新してください。</Step>

</Steps>

</TabsContent>

</CodeTabs>

## 使用方法

```tsx showLineNumbers
import {
  DropdownMenu,
  DropdownMenuContent,
  DropdownMenuItem,
  DropdownMenuLabel,
  DropdownMenuSeparator,
  DropdownMenuTrigger,
} from "@/components/ui/dropdown-menu"
```

```tsx showLineNumbers
<DropdownMenu>
  <DropdownMenuTrigger>開く</DropdownMenuTrigger>
  <DropdownMenuContent>
    <DropdownMenuLabel>マイアカウント</DropdownMenuLabel>
    <DropdownMenuSeparator />
    <DropdownMenuItem>プロフィール</DropdownMenuItem>
    <DropdownMenuItem>請求</DropdownMenuItem>
    <DropdownMenuItem>チーム</DropdownMenuItem>
    <DropdownMenuItem>サブスクリプション</DropdownMenuItem>
  </DropdownMenuContent>
</DropdownMenu>
```
