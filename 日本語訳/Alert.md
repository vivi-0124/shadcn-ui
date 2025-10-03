---
title: アラート
description: ユーザーの注意を引くためのコールアウトを表示します。
component: true
---

<ComponentPreview
  name="alert-demo"
  title="アイコン、タイトル、説明を持つアラート。"
  description="アイコン、タイトル、説明を持つアラート。タイトルは「注意！」で、説明は「CLIを使用してアプリにコンポーネントを追加できます。」です。"
/>

## インストール

<CodeTabs>

<TabsList>
  <TabsTrigger value="cli">CLI</TabsTrigger>
  <TabsTrigger value="manual">手動</TabsTrigger>
</TabsList>
<TabsContent value="cli">

```bash
npx shadcn@latest add alert
```

</TabsContent>

<TabsContent value="manual">

<Steps>

<Step>以下のコードをプロジェクトにコピー＆ペーストしてください。</Step>

<ComponentSource name="alert" title="components/ui/alert.tsx" />

<Step>プロジェクトの設定に合わせてインポートパスを更新してください。</Step>

</Steps>

</TabsContent>

</CodeTabs>

## 使用方法

```tsx showLineNumbers
import { Alert, AlertDescription, AlertTitle } from "@/components/ui/alert"
```

```tsx showLineNumbers
<Alert variant="default | destructive">
  <Terminal />
  <AlertTitle>注意！</AlertTitle>
  <AlertDescription>
    CLIを使用してアプリにコンポーネントと依存関係を追加できます。
  </AlertDescription>
</Alert>
```
