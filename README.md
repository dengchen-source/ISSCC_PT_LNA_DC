# PT LNA Original Measurement Data

This repository contains the original measurement data used for the noise-figure and S-parameter results of the PT LNA.

## Directory Contents

### `Fig4_bottom_Noise_Figure_temp`

- The CSV files contain the raw noise-figure measurements acquired at different temperatures.
- `Deembedded_Noise_Figure_Summary_Final.xlsx` consolidates the raw noise-figure data at different temperatures. It also contains the fixture insertion loss and the actual noise figure obtained after de-embedding.
- The insertion-loss path includes an approximately 10 dB attenuator, together with the losses introduced by the cables and interconnections.
- In the filenames, `f40C` denotes -40 °C.

### `Fig5_top_left_right_temp_SP`

- The CSV files contain the raw S-parameter measurements acquired at different temperatures.
- The temperature range is from -40 °C to 120 °C in 20 °C increments, giving a total of nine temperature points.
- In the filenames, `f40C` and `f20C` denote -40 °C and -20 °C, respectively.

### `Fig5_bottom_left_more_chips_SP`

- The CSV files contain the raw S-parameter measurements for six different chip samples.
- Each file corresponds to one chip, from `chip1` through `chip6`.

## File Formats

- `.csv`: Raw measurement data
- `.xlsx`: Consolidated noise-figure and de-embedding results
