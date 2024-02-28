[Next.js Route Groups Documentation](https://nextjs.org/docs/app/building-your-application/routing/route-groups)

[Next.js Pages and Layouts Documentation](https://nextjs.org/docs/app/building-your-application/routing/pages-and-layouts)


![Next.js Layout Special File](https://nextjs.org/_next/image?url=%2Fdocs%2Flight%2Flayout-special-file.png&w=3840&q=75&dpl=dpl_HKaTZdkuaarspU2J2iNiqNmkbJqv)


```
export default function DashboardLayout({
  children, // will be a page or nested layout
}: {
  children: React.ReactNode
}) {
  return (
    <section>
      {/* Include shared UI here e.g. a header or sidebar */}
      <nav></nav>
 
      {children}
    </section>
  )
}
```

![Next.js Dynamic Routes](https://nextjs.org/docs/app/building-your-application/routing/dynamic-routes)