# Westone W40

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 21 0.0; 23 6.0; 25 6.0; 28 6.0; 31 6.0; 34 6.0; 37 6.0; 41 6.0; 45 6.0; 49 6.0; 54 5.9; 60 5.2; 66 4.4; 72 3.8; 79 3.0; 87 2.2; 96 1.3; 106 0.3; 116 -0.6; 128 -1.4; 141 -2.2; 155 -2.9; 170 -3.4; 187 -4.0; 206 -4.4; 227 -4.5; 249 -4.5; 274 -4.4; 302 -4.2; 332 -4.1; 365 -4.0; 402 -3.7; 442 -3.3; 486 -2.7; 535 -1.9; 588 -1.2; 647 -0.4; 712 0.2; 783 0.6; 861 0.7; 947 0.4; 1042 -0.3; 1146 -0.9; 1261 -1.1; 1387 -0.9; 1526 -0.5; 1678 0.2; 1846 1.0; 2031 2.0; 2234 3.8; 2457 5.4; 2703 5.9; 2973 5.1; 3270 4.2; 3597 4.0; 3957 4.3; 4353 5.0; 4788 6.0; 5267 6.0; 5793 6.0; 6373 5.5; 7010 2.5; 7711 0.3; 8482 -1.6; 9330 -6.3; 10263 -5.8; 11289 -1.5; 12418 0.0; 13660 0.0; 15026 -0.0; 16529 -0.6; 18182 -0.4; 20000 -0.9
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Westone W40 GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.
Set volume attenuation in the Connection tab for both channels to **-61**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Westone W40 ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.7dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-6.6dB**.

| Type    | Fc      |     Q | Gain    |
|:--------|:--------|:------|:--------|
| Peaking | 38 Hz   |  0.4  | 6.9 dB  |
| Peaking | 214 Hz  |  0.63 | -5.9 dB |
| Peaking | 2637 Hz |  2.88 | 5.2 dB  |
| Peaking | 5398 Hz |  1.31 | 6.6 dB  |
| Peaking | 9628 Hz |  3.3  | -8.7 dB |
| Peaking | 18 Hz   |  2.07 | 0.7 dB  |
| Peaking | 466 Hz  |  1.47 | -2.0 dB |
| Peaking | 910 Hz  |  0.7  | 3.4 dB  |
| Peaking | 1265 Hz |  1.41 | -3.9 dB |
| Peaking | 7415 Hz | 13.14 | -1.2 dB |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/rtings/avg/Westone%20W40/Westone%20W40.png)