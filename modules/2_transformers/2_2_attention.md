---
title: 2.2 Attention
nav_order: 2
parent: 2. Transformers
---

# Attention

{: .key-concepts }
> Multi-Head Attention, Self-Attention, Rotary Positional Encoding, Attention Masking.

<!--
    Notes:
    * Refresher on dot product and softmax.
    * Intuition behind attention:
        * It is sort of like a fuzzy key-value store.
        * Each token "asks" the other tokens for relevant information, by multiplying itself with W_q,
        * The other tokens broadcast their keys, by multiplying themselves with W_k.
        * Softmax is then applied to the responses, to amplify the signals that are most relevant to the query, and diminish the rest.
        * We then multiply by V to get the weighted values.
-->

