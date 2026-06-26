# Vellix

> Stop debugging.
> Start asking your code why.

Vellix is an Explainability Runtime.

Every value knows:

• where it came from

• why it exists

• what changed it

• what it affects

Instead of guessing why software behaves a certain way,
just ask it.

```ts
const total = multiply(price, quantity);

console.log(total.why());
