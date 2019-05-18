# Data Details

The PowerBlade is running code from
[this commit](https://github.com/lab11/powerblade/commit/5b41a642327b4730de4426084f99b33f4209f141).
The PowerBlade has not been calibrated in any way, with values below.

```
Reading calibration values from PowerBlade...
  Voff= -1 (ff)
  Ioff= -16 (f0)
  Curoff= 0 (0000)
  PScale= 17034 (8a42)
  VScale= 121 (79)
  WHScale= 9 (09)
Complete
```

Data is collected with the `visualize_waveforms.js` script. With 51 waveforms
collected for each device over about 2 minutes.

Devices include an incandescent lightbulb (resistive load, 75-100 W), a water
kettle (resistive load, ~1000 W), and a small fan (~0.5 power factor, ~50 W in
maximum state 3) in both the on and off states for the lightbulb and kettle,
and multiple power states for the fan.

