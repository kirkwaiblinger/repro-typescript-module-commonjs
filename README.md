# repro-typescript-module-commonjs

1. `yarn`
2. `yarn build`. Observe

    > There are types at '/path/to/repo/node_modules/@demo/a/dist/foo.d.ts', but this result could not be resolved under your current 'moduleResolution' setting. Consider updating to 'node16', 'nodenext', or 'bundler'.

Note that changing the "module" setting to "node16" in package b resolves this error.
