# teleport-registry-packer

This is rollup as a service. Strictly serves only _esm_ bundels to the users whic is bundled with its dependencies.
It started out as a fork from [packd](https://github.com/Rich-Harris/packd) and over the time evolved and
we removed the support for umd. Since, we want it strictly to be _esm_ based beacause of requirements

## Setup

```
$ yarn
$ yarn run dev
```

Then open [http://localhost:8080/confetti@1.0.11](http://localhost:8080/confetti@1.0.11) in browser.

## Deploy
