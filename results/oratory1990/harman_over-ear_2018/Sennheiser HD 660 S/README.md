# Sennheiser HD 660 S

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -6.1dB
GraphicEQ: 21 0.0; 23 6.0; 25 6.0; 28 6.0; 31 6.0; 34 6.0; 37 6.0; 41 6.0; 45 6.0; 49 6.0; 54 6.0; 60 6.0; 66 6.0; 72 6.0; 79 6.0; 87 5.6; 96 4.1; 106 3.0; 116 2.1; 128 1.1; 141 0.1; 155 -0.7; 170 -1.3; 187 -1.6; 206 -2.1; 227 -2.2; 249 -2.1; 274 -1.9; 302 -1.6; 332 -1.1; 365 -0.7; 402 -0.4; 442 -0.4; 486 -0.2; 535 0.1; 588 0.3; 647 0.4; 712 0.2; 783 -0.2; 861 -0.3; 947 0.2; 1042 -0.4; 1146 -0.6; 1261 -0.6; 1387 -0.1; 1526 1.0; 1678 2.0; 1846 3.0; 2031 4.1; 2234 4.3; 2457 3.5; 2703 2.6; 2973 1.9; 3270 1.5; 3597 1.4; 3957 2.0; 4353 3.4; 4788 3.7; 5267 -1.3; 5793 -0.4; 6373 4.8; 7010 2.5; 7711 0.3; 8482 0.0; 9330 0.0; 10263 0.0; 11289 0.0; 12418 0.0; 13660 0.0; 15026 0.0; 16529 0.0; 18182 0.0; 20000 -0.2
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Sennheiser HD 660 S GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.
Set volume attenuation in the Connection tab for both channels to **-61**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Sennheiser HD 660 S ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-6.7dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-6.7dB**.

| Type    | Fc       |    Q | Gain    |
|:--------|:---------|:-----|:--------|
| Peaking | 56 Hz    | 0.27 | 7.3 dB  |
| Peaking | 189 Hz   | 0.8  | -6.3 dB |
| Peaking | 2285 Hz  | 1.77 | 4.2 dB  |
| Peaking | 6581 Hz  | 8.04 | 5.1 dB  |
| Peaking | 24000 Hz | 2.26 | 1.2 dB  |
| Peaking | 81 Hz    | 6.81 | 1.0 dB  |
| Peaking | 1224 Hz  | 3.92 | -1.5 dB |
| Peaking | 4623 Hz  | 5.64 | 4.5 dB  |
| Peaking | 5394 Hz  | 7.29 | -3.7 dB |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/oratory1990/harman_over-ear_2018/Sennheiser%20HD%20660%20S/Sennheiser%20HD%20660%20S.png)