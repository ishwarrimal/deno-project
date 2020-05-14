### Test demo for DENO Project

## Setup

1. install deno

```bash
iwr https://deno.land/x/install/install.ps1 -useb | iex

```

2. Test if its installed properly

```bash
deno --help
```

## Running file

NOTE: file extension can be either `js` or `ts`. Typescript is supported by default

1. helloWorld.ts

```bash
deno run helloWorld.ts
```

You should seee "Hello World" in your console.

2. server.ts

```bash
deno run --allow-net=0.0.0.0:8000 server.ts
```

Open `localhost:8000` in your browser and you should see hello world.  
As you can see above, we are setting permission to access localhost:8000  
If you check its document, this the feature deno is boasting about. it needs permission for creting a server.
