---
title: BASIC TYPESCRIPT TYPES FOR REACTJS DEVELOPEMENT

date: 2019-11-29T12:51:00.000Z
---

## <a name="top"></a> Table of Contents

* [Commonly used props types](#Commonprops)
* [Array - props types](#arrayProps)
* [Function - props types](#functionProps)

***
# <a name="commonProps"></a>Commonly used props types

```ts

type AppProps = {
  message: string,
  count: number,
  disabled: boolean,
  status: "waiting" | "success",
}

```

# <a name="arrayProps"></a>Array - props types
<br />


<h4>array of a type!</h4>

```ts
type AppProps = {
  names: string[],
}
```
<br />

<h4>Life cycle:</h4>

```ts
type AppProps = {
 objArr: {
   id: string;
   title: string;
 }[];
 ```

# <a name="functionProps"></a>Function - props types

<br />

<h4>function that doesn't take or return anything</h4>

```ts
type AppProps = {
  onClick: () => void,
}
```
<br />


<h4>function with named prop</h4>

```ts
type AppProps = {
  onChange: (id: number) => void,
}
```
<br />

<h4>alternative function type syntax that takes an event</h4>

```ts
type AppProps = {
  onClick(event: 
  React.MouseEvent
  <HTMLButtonElement>): void,
}
```