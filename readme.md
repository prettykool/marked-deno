# Marked Deno Module (for `deno.land/x`)
This is a simple, stupid way to get a good ESM version of Marked into Deno.

This is just to prevent squatters from taking the `marked` name on `deno.land/x` for something unrelated/malicious, and that
users getting this will always get the latest version of Marked on their machine.

For the full documentation, see: https://github.com/markedjs/marked/tree/master/docs

## Usage
```ts
import { marked } from 'https://deno.land/x/marked/mod.ts';

marked.parse('Hello, World!');
```
