---
title: Button
description: Displays a button or a component that looks like a button.
component: true
---

<ComponentPreview
  name="button-demo"
  title="A button with different variants and sizes."
  description="A button with different variants and sizes."
/>

## Installation

<CodeTabs>

<TabsList>
  <TabsTrigger value="cli">CLI</TabsTrigger>
  <TabsTrigger value="manual">Manual</TabsTrigger>
</TabsList>
<TabsContent value="cli">

```bash
npx shadcn@latest add button
```

</TabsContent>

<TabsContent value="manual">

<Steps>

<Step>Copy and paste the following code into your project.</Step>

<ComponentSource name="button" title="components/ui/button.tsx" />

<Step>Update the import paths to match your project setup.</Step>

</Steps>

</TabsContent>

</CodeTabs>

## Usage

```tsx showLineNumbers
import { Button } from "@/components/ui/button"
```

```tsx showLineNumbers
<Button variant="default" size="default">
  Button
</Button>
```
