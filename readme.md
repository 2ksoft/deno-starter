# Deno Runtime API

Docs : https://doc.deno.land/builtin/stable

Example :

```
const message: string = "Chào mừng bạn đã đến với tus Deno";

const encoder = new TextEncoder();
const data = encoder.encode(message);

Deno.writeFile("message.txt", data).then(() =>
  console.log("Write file successful !")
);
```

Run :

```
deno run --allow-write=message.txt  index.ts
```
