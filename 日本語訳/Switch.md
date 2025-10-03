---
title: スイッチ
description: ユーザーがチェック済みと未チェックの間で切り替えることができるコントロール。
component: true
links:
  doc: https://www.radix-ui.com/docs/primitives/components/switch
  api: https://www.radix-ui.com/docs/primitives/components/switch#api-reference
---

<ComponentPreview
  name="switch-demo"
  title="異なる状態を持つスイッチ。"
  description="異なる状態を持つスイッチ。"
/>

## インストール

<CodeTabs>

<TabsList>
  <TabsTrigger value="cli">CLI</TabsTrigger>
  <TabsTrigger value="manual">手動</TabsTrigger>
</TabsList>
<TabsContent value="cli">

```bash
npx shadcn@latest add switch
```

</TabsContent>

<TabsContent value="manual">

<Steps>

<Step>以下の依存関係をインストールしてください：</Step>

```bash
npm install @radix-ui/react-switch
```

<Step>以下のコードをプロジェクトにコピー＆ペーストしてください。</Step>

<ComponentSource name="switch" title="components/ui/switch.tsx" />

<Step>プロジェクトの設定に合わせてインポートパスを更新してください。</Step>

</Steps>

</TabsContent>

</CodeTabs>

## 使用方法

```tsx showLineNumbers
import { Switch } from "@/components/ui/switch"
```

```tsx showLineNumbers
<Switch />
```
