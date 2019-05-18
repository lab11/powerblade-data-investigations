Unique Waveform Detection
-------------------------

A single cycle of both voltage and current (42 samples each) is sent from the
MSP430 to the nRF51822 on PowerBlade each second. A high-level goal in
PowerBlade is to collect several samples of waveforms from each unique device
state. This means the nRF51822 should determine when a waveform is unique from
a local set of already-collected waveforms so that it can signal for it to be
uploaded to the cloud.

This directory contains efforts to mathematically identify unique waveforms.

