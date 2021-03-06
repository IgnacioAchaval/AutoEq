# Monoprice M1060

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 21 0.0; 23 6.0; 25 6.0; 28 6.0; 31 6.0; 34 6.0; 37 6.0; 41 6.0; 45 6.0; 49 6.0; 54 6.0; 60 6.0; 66 6.0; 72 5.6; 79 5.0; 87 4.3; 96 3.5; 106 2.7; 116 1.8; 128 1.0; 141 0.2; 155 -0.5; 170 -1.0; 187 -1.5; 206 -1.9; 227 -1.9; 249 -1.7; 274 -1.2; 302 -0.5; 332 0.1; 365 0.4; 402 0.6; 442 0.5; 486 0.0; 535 -0.4; 588 -0.8; 647 -1.1; 712 -1.3; 783 -1.2; 861 -0.5; 947 0.0; 1042 -0.2; 1146 -0.6; 1261 -1.1; 1387 -1.2; 1526 -1.3; 1678 -1.9; 1846 -2.4; 2031 -2.1; 2234 -1.9; 2457 -1.8; 2703 -1.7; 2973 -1.7; 3270 -1.2; 3597 -0.5; 3957 -1.0; 4353 -2.2; 4788 -0.7; 5267 0.9; 5793 0.9; 6373 3.2; 7010 2.5; 7711 0.3; 8482 0.0; 9330 0.0; 10263 0.0; 11289 -0.3; 12418 0.0; 13660 0.0; 15026 -1.3; 16529 -7.5; 18182 -14.0; 20000 -20.3
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Monoprice M1060 GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.
Set volume attenuation in the Connection tab for both channels to **-61**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Monoprice M1060 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.4dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-6.4dB**.

| Type    | Fc       |     Q | Gain     |
|:--------|:---------|:------|:---------|
| Peaking | 52 Hz    |  0.2  | 6.8 dB   |
| Peaking | 181 Hz   |  0.86 | -6.3 dB  |
| Peaking | 3010 Hz  |  0.5  | -3.9 dB  |
| Peaking | 9466 Hz  |  0.27 | 4.3 dB   |
| Peaking | 19557 Hz |  1    | -21.4 dB |
| Peaking | 4311 Hz  | 10.21 | -1.9 dB  |
| Peaking | 6565 Hz  |  5.76 | 3.7 dB   |
| Peaking | 8636 Hz  |  1.68 | -1.8 dB  |
| Peaking | 14635 Hz |  3.11 | 3.0 dB   |
| Peaking | 17606 Hz |  2.82 | -2.7 dB  |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/oratory1990/harman_over-ear_2018/Monoprice%20M1060/Monoprice%20M1060.png)