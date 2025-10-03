---
title: ラジオグループ
description: 一度に1つまでのボタンのみがチェックできる、チェック可能なボタンのセット（ラジオボタンとして知られる）。
component: true
links:
  doc: https://www.radix-ui.com/docs/primitives/components/radio-group
  api: https://www.radix-ui.com/docs/primitives/components/radio-group#api-reference
---

<ComponentPreview
  name="radio-group-demo"
  title="異なるオプションを持つラジオグループ。"
  description="異なるオプションを持つラジオグループ。"
/>

## インストール

<CodeTabs>

<TabsList>
  <TabsTrigger value="cli">CLI</TabsTrigger>
  <TabsTrigger value="manual">手動</TabsTrigger>
</TabsList>
<TabsContent value="cli">

```bash
npx shadcn@latest add radio-group
```

</TabsContent>

<TabsContent value="manual">

<Steps>

<Step>以下の依存関係をインストールしてください：</Step>

```bash
npm install @radix-ui/react-radio-group
```

<Step>以下のコードをプロジェクトにコピー＆ペーストしてください。</Step>

<ComponentSource name="radio-group" title="components/ui/radio-group.tsx" />

<Step>プロジェクトの設定に合わせてインポートパスを更新してください。</Step>

</Steps>

</TabsContent>

</CodeTabs>

## 使用方法

```tsx showLineNumbers
import { RadioGroup, RadioGroupItem } from "@/components/ui/radio-group"
import { Label } from "@/components/ui/label"
```

```tsx showLineNumbers
<RadioGroup defaultValue="option-one">
  <div className="flex items-center space-x-2">
    <RadioGroupItem value="option-one" id="option-one" />
    <Label htmlFor="option-one">オプション1</Label>
  </div>
  <div className="flex items-center space-x-2">
    <RadioGroupItem value="option-two" id="option-two" />
    <Label htmlFor="option-two">オプション2</Label>
  </div>
</RadioGroup>
```
