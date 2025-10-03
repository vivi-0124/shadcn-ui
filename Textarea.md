---
title: Textarea
description: Displays a form textarea or a component that looks like a textarea.
component: true
---

<ComponentPreview
  name="textarea-demo"
  title="A textarea with different states."
  description="A textarea with different states."
/>

## Installation

<CodeTabs>

<TabsList>
  <TabsTrigger value="cli">CLI</TabsTrigger>
  <TabsTrigger value="manual">Manual</TabsTrigger>
</TabsList>
<TabsContent value="cli">

```bash
npx shadcn@latest add textarea
```

</TabsContent>

<TabsContent value="manual">

<Steps>

<Step>Copy and paste the following code into your project.</Step>

<ComponentSource name="textarea" title="components/ui/textarea.tsx" />

<Step>Update the import paths to match your project setup.</Step>

</Steps>

</TabsContent>

</CodeTabs>

## Usage

```tsx showLineNumbers
import { Textarea } from "@/components/ui/textarea"
```

```tsx showLineNumbers
<Textarea placeholder="Type your message here." />
```
