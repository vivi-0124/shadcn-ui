---
title: Toast
description: A succinct message that is displayed temporarily.
component: true
---

<ComponentPreview
  name="toast-demo"
  title="A toast with different variants and actions."
  description="A toast with different variants and actions."
/>

## Installation

<CodeTabs>

<TabsList>
  <TabsTrigger value="cli">CLI</TabsTrigger>
  <TabsTrigger value="manual">Manual</TabsTrigger>
</TabsList>
<TabsContent value="cli">

```bash
npx shadcn@latest add toast
```

</TabsContent>

<TabsContent value="manual">

<Steps>

<Step>Copy and paste the following code into your project.</Step>

<ComponentSource name="toast" title="components/ui/toast.tsx" />

<Step>Update the import paths to match your project setup.</Step>

</Steps>

</TabsContent>

</CodeTabs>

## Usage

```tsx showLineNumbers
import { useToast } from "@/hooks/use-toast"
```

```tsx showLineNumbers
const { toast } = useToast()

return (
  <Button
    onClick={() => {
      toast({
        title: "Scheduled: Catch up",
        description: "Friday, February 10, 2023 at 5:57 PM",
      })
    }}
  >
    Add to calendar
  </Button>
)
```
