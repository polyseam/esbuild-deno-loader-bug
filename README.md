# demonstrate `esbuild_deno_loader` imports failure

This repo contains a module in the folder `src/examples/example.ts` which is
imported by `src/greeter/greet.ts` by leveraging the `src/` import in
`deno.json`.

This works as intended with `deno run`, but fails when building with
`esbuild_deno_loader` in `./build.ts`.
