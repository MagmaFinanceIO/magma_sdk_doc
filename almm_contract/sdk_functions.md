## retrieve reward

TODO:

## collect fees

TODO:

## add liquidity

TODO:

## remove liquidity

TODO:

## swap

### Function

```typescript
async swap({
  pair: string
  coinTypeA: string
  coinTypeB: string
  amountIn: number
  minAmountOut: number
  swapForY: boolean
  to: string
}: ALMMSwapParams): Promise<Transaction>
```

### Parameters

Please refer to the original function for specific parameter types.

- `pair`: pool object id
- `coinTypeA`: the coin type address about coinA.
- `coinTypeB`: the coin type address about coinB.
- `amountIn`: the amount of input coin (coinX when `swapForY` = `true`; coinY when `swapForY` = `false`).
- `minAmountOut`: the amount limit of coin what you get.
- `swapForY`: `true` means swap coinX to coinY, `false` means swap coinY to coinX.
- `to`: string
