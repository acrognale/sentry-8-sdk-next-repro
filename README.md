Setup with `npx @sentry/wizard@latest -i nextjs` after a vanilla `create-next-app`

```
❯ npx next dev  
  ▲ Next.js 14.2.3
  - Local:        http://localhost:3000
  - Experiments (use with caution):
    · instrumentationHook

 ✓ Starting...
[@sentry/nextjs] It appears you've configured a `sentry.server.config.ts` file. Please ensure to put this file's content into the `register()` function of a Next.js instrumentation hook instead. To ensure correct functionality of the SDK, `Sentry.init` must be called inside `instrumentation.ts`. Learn more about setting up an instrumentation hook in Next.js: https://nextjs.org/docs/app/building-your-application/optimizing/instrumentation. You can safely delete the `sentry.server.config.ts` file afterward.
[@sentry/nextjs] It appears you've configured a `sentry.edge.config.ts` file. Please ensure to put this file's content into the `register()` function of a Next.js instrumentation hook instead. To ensure correct functionality of the SDK, `Sentry.init` must be called inside `instrumentation.ts`. Learn more about setting up an instrumentation hook in Next.js: https://nextjs.org/docs/app/building-your-application/optimizing/instrumentation. You can safely delete the `sentry.edge.config.ts` file afterward.
 ○ Compiling /instrumentation ...
 ✓ Compiled /instrumentation in 1010ms (1187 modules)
 ✓ Ready in 2.5s
```


