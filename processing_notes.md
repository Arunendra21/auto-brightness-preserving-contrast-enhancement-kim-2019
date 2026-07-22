# Processing Notes — Auto Brightness-Preserving Contrast Enhancement (Kim 2019)

- **Paper:** Suah Kim, Rolf Lussi, Xiaochao Qu, Fangjun Huang, Hyoung Joong Kim, IEEE TCSVT, vol. 29, no. 8, 2019
- **Reproduction tier:** A
- **Status:** Completed (full reproduction)

## What was reproduced
Reversible histogram-expansion CE core with brightness monitoring (AMBE), iterations 2..10 on the standard set, bit-exact reversibility verified.

## Reproduced vs reported
Contrast rises with embedding, brightness stays controlled, recovery exact -- matching the paper. The exact adaptive bin-selection rule is unspecified in the paper, so iteration count + AMBE serve as the control/measurement proxy.

## Honesty note
All numbers are produced by the included code on bundled images; 'reported' cells reflect the paper.
