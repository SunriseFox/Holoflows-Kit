<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@holoflows/kit](./kit.md) &gt; [LiveSelector](./kit.liveselector.md) &gt; [closest](./kit.liveselector.closest.md)

## LiveSelector.closest() method

Reversely select element in the parent

<b>Signature:</b>

```typescript
closest<T>(parentOfNth: number): LiveSelector<T>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  parentOfNth | <code>number</code> |  |

<b>Returns:</b>

`LiveSelector<T>`

## Example


```ts
ls.closest('div')
ls.closest(2) // parentElement.parentElement

```
