# Investigating collision in secure Pseudo RNG

Testing random 8-bit integers before duplicates appear:

```openssl rand -hex 1```

Average number of attempts per duplicate = 22 (about 2<sup>8⁄2</sup> integers)
