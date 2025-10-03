---
title: カード
description: ヘッダー、コンテンツ、フッターを持つカードを表示します。
component: true
---

<ComponentPreview
  name="card-demo"
  title="ヘッダー、コンテンツ、フッターを持つカード。"
  description="ヘッダー、コンテンツ、フッターを持つカード。"
/>

## インストール

<CodeTabs>

<TabsList>
  <TabsTrigger value="cli">CLI</TabsTrigger>
  <TabsTrigger value="manual">手動</TabsTrigger>
</TabsList>
<TabsContent value="cli">

```bash
npx shadcn@latest add card
```

</TabsContent>

<TabsContent value="manual">

<Steps>

<Step>以下のコードをプロジェクトにコピー＆ペーストしてください。</Step>

<ComponentSource name="card" title="components/ui/card.tsx" />

<Step>プロジェクトの設定に合わせてインポートパスを更新してください。</Step>

</Steps>

</TabsContent>

</CodeTabs>

## 使用方法

```tsx showLineNumbers
import { Card, CardContent, CardDescription, CardFooter, CardHeader, CardTitle } from "@/components/ui/card"
```

```tsx showLineNumbers
<Card>
  <CardHeader>
    <CardTitle>カードタイトル</CardTitle>
    <CardDescription>カードの説明</CardDescription>
  </CardHeader>
  <CardContent>
    <p>カードのコンテンツ</p>
  </CardContent>
  <CardFooter>
    <p>カードのフッター</p>
  </CardFooter>
</Card>
```
