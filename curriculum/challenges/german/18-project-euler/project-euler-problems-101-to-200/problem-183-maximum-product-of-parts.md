---
id: 5900f4231000cf542c50ff36
title: 'Problem 183: Maximum product of parts'
challengeType: 1
forumTopicId: 301819
dashedName: problem-183-maximum-product-of-parts
---

# --description--

Lasse $N$ eine positive Integer sein und lasse $N$ in $k$ gleiche Teile zerlegen, $r = \frac{N}{k}$, sodass $N = r + r + \cdots + r$.

Lasse $P$ das Produkt dieser Teile sein, $P = r × r × \cdots × r = r^k$.

Wenn zum Beispiel 11 in fünf gleiche Teile aufgeteilt wird, 11 = 2.2 + 2.2 + 2.2 + 2.2 + 2.2, dann ist $P = {2.2}^5 = 51,53632$.

Lass $M(N) = P_{max}$ für einen gegebenen Wert von $N$.

It turns out that the maximum for $N = 11$ is found by splitting eleven into four equal parts which leads to $P_{max} = {(\frac{11}{4})}^4$; that is, $M(11) = \frac{14641}{256} = 57.19140625$, which is a terminating decimal.

However, for $N = 8$ the maximum is achieved by splitting it into three equal parts, so $M(8) = \frac{512}{27}$, which is a non-terminating decimal.

Let $D(N) = N$ if $M(N)$ is a non-terminating decimal and $D(N) = -N$ if $M(N)$ is a terminating decimal.

For example, $\sum D(N)$ for $5 ≤ N ≤ 100$ is 2438.

Find $\sum D(N)$ for $5 ≤ N ≤ 10000$.

# --hints--

`maximumProductOfParts()` should return `48861552`.

```js
assert.strictEqual(maximumProductOfParts(), 48861552);
```

# --seed--

## --seed-contents--

```js
function maximumProductOfParts() {

  return true;
}

maximumProductOfParts();
```

# --solutions--

```js
// solution required
```
