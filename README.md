1. `npm init svelte@next env-var-vercel-sveltekit`
2. Choose skeleton and choose no on everything to keep it simple
3. `cd env-var-vercel-sveltekit`
4. `npm i`
5. `npm i @sveltejs/adapter-vercel@next`
6. Add the adapter to svelte.config.js like I did in https://github.com/baukevanderlaan/env-var-vercel-sveltekit/blob/main/svelte.config.js
7. Import and export the system environment variables like I did in https://github.com/baukevanderlaan/env-var-vercel-sveltekit/blob/main/src/env.js
8. Import and display the variables on the frontend like I did in https://github.com/baukevanderlaan/env-var-vercel-sveltekit/blob/main/src/routes/index.svelte
9. Deploy on Vercel with zero-config framework preset SvelteKit.
10. Notice the var is undefined
11. Change framework preset to Vite and override build settings to mirror those of SvelteKit
12. Notice the var is defined.
