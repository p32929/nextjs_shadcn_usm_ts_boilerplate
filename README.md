# nextjs_shadcn_usm_ts_boilerplate

A Next.js starter template with shadcn/ui and usm-redux, with every shadcn component already installed. Setting up a new Next.js project usually means running `add` for one component after another and wiring up state by hand. Clone this and start building your pages right away.

## What's included

1. **Next.js** (app router) with TypeScript.
2. **All the shadcn/ui components** already installed, from accordion to tooltip, on Tailwind and Radix.
3. **usm-redux** state with a `StatesController`, provided to the whole app.
4. **Providers in their own files** (`app/providers.tsx` and `app/redux-provider.tsx`), so adding another one is one line.
5. **Lucide icons, `date-fns`, `cmdk` and `react-day-picker`** already added.
6. **ESLint** with `eslint-config-next`.

## Project layout

```
app/layout.tsx          root layout, wraps the providers
app/providers.tsx       theme and other providers
app/redux-provider.tsx  usm-redux store provider
app/page.tsx            your first page
lib/StatesController.ts the usm-redux state
lib/utils.ts            the cn() helper
components/ui/          the shadcn components
```

## Getting started

```bash
git clone https://github.com/p32929/nextjs_shadcn_usm_ts_boilerplate.git
cd nextjs_shadcn_usm_ts_boilerplate
npm install
npm run dev        # http://localhost:3000
```

Build with `npm run build`, and check the code with `npm run lint`.

> It uses Next.js 13. You can upgrade with Next.js's own upgrade guide after cloning.

## Related templates

1. [nextjs-typescript-overmind-shadcn-boilerplate](https://github.com/p32929/nextjs-typescript-overmind-shadcn-boilerplate): the same UI, with Overmind instead of usm-redux.
2. [react_shadcn_ts_usm_boilerplate](https://github.com/p32929/react_shadcn_ts_usm_boilerplate): the plain React (Vite) version.
3. [nextjs_typescript_materialui_usm_boilerplate](https://github.com/p32929/nextjs_typescript_materialui_usm_boilerplate): usm-redux with Material-UI instead of shadcn.

## Contributing

Contributions are very welcome, thank you! Before you start on a pull request, please open an issue and tell me what you would like to add or change. That way we can agree on it first, and your time is not wasted on something that might not fit. Thanks for helping make this template better.

## You might also like

<p><a href="https://openstore.pfay.workers.dev/cards/p32929/0?n=4&amp;repo=nextjs_shadcn_usm_ts_boilerplate"><picture><source media="(prefers-color-scheme: dark)" srcset="https://openstore.pfay.workers.dev/cards/p32929/0.svg?n=4&amp;repo=nextjs_shadcn_usm_ts_boilerplate&amp;theme=dark"><img src="https://openstore.pfay.workers.dev/cards/p32929/0.svg?n=4&amp;repo=nextjs_shadcn_usm_ts_boilerplate&amp;theme=light" width="50%" align="top" alt="More apps by p32929 on OpenStore (1)"></picture></a><a href="https://openstore.pfay.workers.dev/cards/p32929/1?n=4&amp;repo=nextjs_shadcn_usm_ts_boilerplate"><picture><source media="(prefers-color-scheme: dark)" srcset="https://openstore.pfay.workers.dev/cards/p32929/1.svg?n=4&amp;repo=nextjs_shadcn_usm_ts_boilerplate&amp;theme=dark"><img src="https://openstore.pfay.workers.dev/cards/p32929/1.svg?n=4&amp;repo=nextjs_shadcn_usm_ts_boilerplate&amp;theme=light" width="50%" align="top" alt="More apps by p32929 on OpenStore (2)"></picture></a><br><a href="https://openstore.pfay.workers.dev/cards/p32929/2?n=4&amp;repo=nextjs_shadcn_usm_ts_boilerplate"><picture><source media="(prefers-color-scheme: dark)" srcset="https://openstore.pfay.workers.dev/cards/p32929/2.svg?n=4&amp;repo=nextjs_shadcn_usm_ts_boilerplate&amp;theme=dark"><img src="https://openstore.pfay.workers.dev/cards/p32929/2.svg?n=4&amp;repo=nextjs_shadcn_usm_ts_boilerplate&amp;theme=light" width="50%" align="top" alt="More apps by p32929 on OpenStore (3)"></picture></a><a href="https://openstore.pfay.workers.dev/cards/p32929/3?n=4&amp;repo=nextjs_shadcn_usm_ts_boilerplate"><picture><source media="(prefers-color-scheme: dark)" srcset="https://openstore.pfay.workers.dev/cards/p32929/3.svg?n=4&amp;repo=nextjs_shadcn_usm_ts_boilerplate&amp;theme=dark"><img src="https://openstore.pfay.workers.dev/cards/p32929/3.svg?n=4&amp;repo=nextjs_shadcn_usm_ts_boilerplate&amp;theme=light" width="50%" align="top" alt="More apps by p32929 on OpenStore (4)"></picture></a></p>

<p><a href="https://p32929.github.io/share/?repo=nextjs_shadcn_usm_ts_boilerplate"><picture><source media="(prefers-color-scheme: dark)" srcset="https://p32929.github.io/readme/footer-share-dark.svg"><img src="https://p32929.github.io/readme/footer-share-light.svg" width="50%" align="top" alt="Share this project with your friends in one click"></picture></a><a href="https://p32929.github.io/support/"><picture><source media="(prefers-color-scheme: dark)" srcset="https://p32929.github.io/readme/footer-support-dark.svg"><img src="https://p32929.github.io/readme/footer-support-light.svg" width="50%" align="top" alt="If you like my work and want to support me, feel free to support"></picture></a><br><a href="https://openstore.pfay.workers.dev/add"><picture><source media="(prefers-color-scheme: dark)" srcset="https://p32929.github.io/readme/footer-join-dark.svg"><img src="https://p32929.github.io/readme/footer-join-light.svg" width="100%" align="top" alt="Put your own apps on OpenStore: free, your listing lives in your own repo"></picture></a></p>
