---
title: トースト
description: 一時的に表示される簡潔なメッセージ。
component: true
---

<ComponentPreview
  name="toast-demo"
  title="異なるバリアントとアクションを持つトースト。"
  description="異なるバリアントとアクションを持つトースト。"
/>

## インストール

<CodeTabs>

<TabsList>
  <TabsTrigger value="cli">CLI</TabsTrigger>
  <TabsTrigger value="manual">手動</TabsTrigger>
</TabsList>
<TabsContent value="cli">

```bash
npx shadcn@latest add toast
```

</TabsContent>

<TabsContent value="manual">

<Steps>

<Step>以下のコードをプロジェクトにコピー＆ペーストしてください。</Step>

<ComponentSource name="toast" title="components/ui/toast.tsx" />

<Step>プロジェクトの設定に合わせてインポートパスを更新してください。</Step>

</Steps>

</TabsContent>

</CodeTabs>

## 使用方法

```tsx showLineNumbers
import { useToast } from "@/hooks/use-toast"
```

```tsx showLineNumbers
const { toast } = useToast()

return (
  <Button
    onClick={() => {
      toast({
        title: "スケジュール: キャッチアップ",
        description: "2023年2月10日金曜日 午後5:57",
      })
    }}
  >
    カレンダーに追加
  </Button>
)
```
