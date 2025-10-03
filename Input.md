---
title: Input
description: Displays a form input field or a component that looks like an input field.
component: true
---

<ComponentPreview
  name="input-demo"
  title="An input with different types and states."
  description="An input with different types and states."
/>

## Installation

<CodeTabs>

<TabsList>
  <TabsTrigger value="cli">CLI</TabsTrigger>
  <TabsTrigger value="manual">Manual</TabsTrigger>
</TabsList>
<TabsContent value="cli">

```bash
npx shadcn@latest add input
```

</TabsContent>

<TabsContent value="manual">

<Steps>

<Step>Copy and paste the following code into your project.</Step>

<ComponentSource name="input" title="components/ui/input.tsx" />

<Step>Update the import paths to match your project setup.</Step>

</Steps>

</TabsContent>

</CodeTabs>

## Usage

```tsx showLineNumbers
import { Input } from "@/components/ui/input"
```

```tsx showLineNumbers
<Input type="email" placeholder="Email" />
```
