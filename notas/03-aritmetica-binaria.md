---
tags: [ciberfisicos, estudo]
---

# 03 · Aritmética binária

## Soma
| a | b | soma | vai-um |
|---|---|---|---|
| 0 | 0 | 0 | 0 |
| 0 | 1 | 1 | 0 |
| 1 | 0 | 1 | 0 |
| 1 | 1 | 0 | 1 |

```
  0110   (6)
+ 0011   (3)
------
  1001   (9)
```

## Subtração
Pode ser feita com empréstimo, mas o hardware usa **soma do complemento de dois** (ver nota 05).

## Multiplicação
Como no papel: cada bit do multiplicador gera uma linha (0 ou o multiplicando deslocado); soma-se tudo.

## Overflow
Quando o resultado não cabe nos bits disponíveis. Em 4 bits sem sinal, `1111 + 0001 = 10000` perde o bit mais à esquerda (resultado 0000).

<!-- nav:start -->

---

← [02 · Conversão de bases](02-conversao-de-bases.md) · [Mapa](../00%20-%20Mapa.md) · [04 · Hexadecimal](04-hexadecimal.md) →

**Veja também:** [05 · Complemento de dois](05-complemento-de-dois.md)

<!-- nav:end -->
