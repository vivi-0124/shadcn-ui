---
title: ナビゲーションメニュー
description: ウェブサイトをナビゲートするためのリンクのコレクション。
component: true
links:
  doc: https://www.radix-ui.com/docs/primitives/components/navigation-menu
  api: https://www.radix-ui.com/docs/primitives/components/navigation-menu#api-reference
---

<ComponentPreview
  name="navigation-menu-demo"
  title="異なるアイテムを持つナビゲーションメニュー。"
  description="異なるアイテムを持つナビゲーションメニュー。"
/>

## インストール

<CodeTabs>

<TabsList>
  <TabsTrigger value="cli">CLI</TabsTrigger>
  <TabsTrigger value="manual">手動</TabsTrigger>
</TabsList>
<TabsContent value="cli">

```bash
npx shadcn@latest add navigation-menu
```

</TabsContent>

<TabsContent value="manual">

<Steps>

<Step>以下の依存関係をインストールしてください：</Step>

```bash
npm install @radix-ui/react-navigation-menu
```

<Step>以下のコードをプロジェクトにコピー＆ペーストしてください。</Step>

<ComponentSource name="navigation-menu" title="components/ui/navigation-menu.tsx" />

<Step>プロジェクトの設定に合わせてインポートパスを更新してください。</Step>

</Steps>

</TabsContent>

</CodeTabs>

## 使用方法

```tsx showLineNumbers
import {
  NavigationMenu,
  NavigationMenuContent,
  NavigationMenuItem,
  NavigationMenuLink,
  NavigationMenuList,
  NavigationMenuTrigger,
} from "@/components/ui/navigation-menu"
```

```tsx showLineNumbers
<NavigationMenu>
  <NavigationMenuList>
    <NavigationMenuItem>
      <NavigationMenuTrigger>アイテム1</NavigationMenuTrigger>
      <NavigationMenuContent>
        <NavigationMenuLink>リンク</NavigationMenuLink>
      </NavigationMenuContent>
    </NavigationMenuItem>
  </NavigationMenuList>
</NavigationMenu>
```
