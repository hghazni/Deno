# Deno
Fun with a type safe runtime built for JavaScript/TypeScript/Web Assembly mostly made with Rust under the hood.

Run code using
```
deno --alow-net index.ts
```

`--alow-net` flag is used because for security reasons, Deno does not allow programs to access the network without explicit permission. To allow accessing the network, use a command-line flag: