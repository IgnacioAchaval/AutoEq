# Sony WI-1000X

### EqualizerAPO
In case of using EqualizerAPO without any GUI, replace `C:\Program Files\EqualizerAPO\config\config.txt`
with:
```
Preamp: -2.7dB
GraphicEQ: 21 0.0; 23 1.1; 25 0.5; 28 0.2; 31 0.4; 34 0.7; 37 0.9; 41 1.2; 45 1.2; 49 1.2; 54 1.0; 60 0.4; 66 -0.1; 72 -0.6; 79 -1.1; 87 -1.7; 96 -2.4; 106 -3.1; 116 -3.7; 128 -4.3; 141 -4.7; 155 -4.9; 170 -5.1; 187 -5.2; 206 -5.3; 227 -5.3; 249 -5.3; 274 -5.4; 302 -5.5; 332 -5.4; 365 -5.2; 402 -4.6; 442 -4.0; 486 -3.8; 535 -4.0; 588 -4.3; 647 -3.3; 712 -2.2; 783 -1.5; 861 -1.1; 947 -0.9; 1042 0.6; 1146 -0.1; 1261 -0.4; 1387 -0.2; 1526 0.2; 1678 -0.3; 1846 -1.1; 2031 -2.3; 2234 -2.7; 2457 -2.1; 2703 -1.1; 2973 -1.2; 3270 -2.8; 3597 -4.4; 3957 -4.9; 4353 -3.7; 4788 -4.0; 5267 -5.9; 5793 -5.5; 6373 -3.2; 7010 -2.1; 7711 -1.9; 8482 -2.3; 9330 -6.0; 10263 -11.1; 11289 -12.3; 12418 -8.9; 13660 -4.4; 15026 -1.7; 16529 -0.4; 18182 -0.5; 20000 -2.8
```

### HeSuVi
HeSuVi 2.0 ships with most of the pre-processed results. If this model can't be found in HeSuVi add
`Sony WI-1000X GraphicEQ.txt` to `C:\Program Files\EqualizerAPO\config\HeSuVi\eq\custom\` folder.
Set volume attenuation in the Connection tab for both channels to **-26**

### Peace
In case of using Peace, click *Import* in Peace GUI and select `Sony WI-1000X ParametricEQ.txt`.

### Parametric EQs
In case of using other parametric equalizer, apply preamp of **-2.4dB** and build filters manually
with these parameters. The first 5 filters can be used independently.
When using independent subset of filters, apply preamp of **-0.0dB**.

| Type    | Fc       |    Q | Gain     |
|:--------|:---------|:-----|:---------|
| Peaking | 148 Hz   | 1.39 | -3.3 dB  |
| Peaking | 333 Hz   | 0.76 | -5.1 dB  |
| Peaking | 3807 Hz  | 2.36 | -4.0 dB  |
| Peaking | 5486 Hz  | 4.74 | -4.8 dB  |
| Peaking | 11160 Hz | 2.46 | -13.3 dB |
| Peaking | 18 Hz    | 2.28 | 3.0 dB   |
| Peaking | 46 Hz    | 2.36 | 1.8 dB   |
| Peaking | 1884 Hz  | 1.12 | 1.7 dB   |
| Peaking | 2124 Hz  | 3.14 | -3.7 dB  |
| Peaking | 8194 Hz  | 8.1  | 1.8 dB   |

![](https://raw.githubusercontent.com/jaakkopasanen/AutoEq/master/results/rtings/avg/Sony%20WI-1000X/Sony%20WI-1000X.png)