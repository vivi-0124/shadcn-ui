---
title: Slider
description: An input where the user selects a value from within a given range.
component: true
links:
  doc: https://www.radix-ui.com/docs/primitives/components/slider
  api: https://www.radix-ui.com/docs/primitives/components/slider#api-reference
---

<ComponentPreview
  name="slider-demo"
  title="A slider with different values and ranges."
  description="A slider with different values and ranges."
/>

## Installation

<CodeTabs>

<TabsList>
  <TabsTrigger value="cli">CLI</TabsTrigger>
  <TabsTrigger value="manual">Manual</TabsTrigger>
</TabsList>
<TabsContent value="cli">

```bash
npx shadcn@latest add slider
```

</TabsContent>

<TabsContent value="manual">

<Steps>

<Step>Install the following dependencies:</Step>

```bash
npm install @radix-ui/react-slider
```

<Step>Copy and paste the following code into your project.</Step>

<ComponentSource name="slider" title="components/ui/slider.tsx" />

<Step>Update the import paths to match your project setup.</Step>

</Steps>

</TabsContent>

</CodeTabs>

## Usage

```tsx showLineNumbers
import { Slider } from "@/components/ui/slider"
```

```tsx showLineNumbers
<Slider defaultValue={[50]} max={100} step={1} />
```
