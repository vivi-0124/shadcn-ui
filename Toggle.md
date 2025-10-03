---
title: Toggle
description: A two-state button that can be either on or off.
component: true
links:
  doc: https://www.radix-ui.com/docs/primitives/components/toggle
  api: https://www.radix-ui.com/docs/primitives/components/toggle#api-reference
---

<ComponentPreview
  name="toggle-demo"
  title="A toggle with different variants and sizes."
  description="A toggle with different variants and sizes."
/>

## Installation

<CodeTabs>

<TabsList>
  <TabsTrigger value="cli">CLI</TabsTrigger>
  <TabsTrigger value="manual">Manual</TabsTrigger>
</TabsList>
<TabsContent value="cli">

```bash
npx shadcn@latest add toggle
```

</TabsContent>

<TabsContent value="manual">

<Steps>

<Step>Install the following dependencies:</Step>

```bash
npm install @radix-ui/react-toggle
```

<Step>Copy and paste the following code into your project.</Step>

<ComponentSource name="toggle" title="components/ui/toggle.tsx" />

<Step>Update the import paths to match your project setup.</Step>

</Steps>

</TabsContent>

</CodeTabs>

## Usage

```tsx showLineNumbers
import { Toggle } from "@/components/ui/toggle"
```

```tsx showLineNumbers
<Toggle>Toggle</Toggle>
```
