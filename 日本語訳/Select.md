---
title: セレクト
description: ボタンによってトリガーされる、ユーザーが選択できるオプションのリストを表示します。
component: true
links:
  doc: https://www.radix-ui.com/docs/primitives/components/select
  api: https://www.radix-ui.com/docs/primitives/components/select#api-reference
---

<ComponentPreview
  name="select-demo"
  title="異なるオプションを持つセレクト。"
  description="異なるオプションを持つセレクト。"
/>

## インストール

<CodeTabs>

<TabsList>
  <TabsTrigger value="cli">CLI</TabsTrigger>
  <TabsTrigger value="manual">手動</TabsTrigger>
</TabsList>
<TabsContent value="cli">

```bash
npx shadcn@latest add select
```

</TabsContent>

<TabsContent value="manual">

<Steps>

<Step>以下の依存関係をインストールしてください：</Step>

```bash
npm install @radix-ui/react-select
```

<Step>以下のコードをプロジェクトにコピー＆ペーストしてください。</Step>

<ComponentSource name="select" title="components/ui/select.tsx" />

<Step>プロジェクトの設定に合わせてインポートパスを更新してください。</Step>

</Steps>

</TabsContent>

</CodeTabs>

## 使用方法

```tsx showLineNumbers
import {
  Select,
  SelectContent,
  SelectItem,
  SelectTrigger,
  SelectValue,
} from "@/components/ui/select"
```

```tsx showLineNumbers
<Select>
  <SelectTrigger>
    <SelectValue placeholder="果物を選択してください" />
  </SelectTrigger>
  <SelectContent>
    <SelectItem value="apple">りんご</SelectItem>
    <SelectItem value="banana">バナナ</SelectItem>
    <SelectItem value="blueberry">ブルーベリー</SelectItem>
    <SelectItem value="grapes">ぶどう</SelectItem>
    <SelectItem value="pineapple">パイナップル</SelectItem>
  </SelectContent>
</Select>
```
