---
title: タブ
description: 一度に1つずつ表示される、コンテンツの階層化されたセクション（タブパネルとして知られる）のセット。
component: true
links:
  doc: https://www.radix-ui.com/docs/primitives/components/tabs
  api: https://www.radix-ui.com/docs/primitives/components/tabs#api-reference
---

<ComponentPreview
  name="tabs-demo"
  title="異なるコンテンツを持つタブコンポーネント。"
  description="異なるコンテンツを持つタブコンポーネント。"
/>

## インストール

<CodeTabs>

<TabsList>
  <TabsTrigger value="cli">CLI</TabsTrigger>
  <TabsTrigger value="manual">手動</TabsTrigger>
</TabsList>
<TabsContent value="cli">

```bash
npx shadcn@latest add tabs
```

</TabsContent>

<TabsContent value="manual">

<Steps>

<Step>以下の依存関係をインストールしてください：</Step>

```bash
npm install @radix-ui/react-tabs
```

<Step>以下のコードをプロジェクトにコピー＆ペーストしてください。</Step>

<ComponentSource name="tabs" title="components/ui/tabs.tsx" />

<Step>プロジェクトの設定に合わせてインポートパスを更新してください。</Step>

</Steps>

</TabsContent>

</CodeTabs>

## 使用方法

```tsx showLineNumbers
import { Tabs, TabsContent, TabsList, TabsTrigger } from "@/components/ui/tabs"
```

```tsx showLineNumbers
<Tabs defaultValue="account" className="w-[400px]">
  <TabsList>
    <TabsTrigger value="account">アカウント</TabsTrigger>
    <TabsTrigger value="password">パスワード</TabsTrigger>
  </TabsList>
  <TabsContent value="account">
    ここでアカウントの変更を行ってください。
  </TabsContent>
  <TabsContent value="password">
    ここでパスワードを変更してください。
  </TabsContent>
</Tabs>
```
