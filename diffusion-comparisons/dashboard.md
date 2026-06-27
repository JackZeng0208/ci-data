# SGLang-Diffusion Nightly Performance Dashboard

*Generated: Jun 27 | Commit: `528f170`*

> [!WARNING]
> **Performance Regression Detected**
>
> - **flux1_dev_t2i_1024** (sglang): 4.68s -> 10.97s (+134.3%)
> - **flux2_dev_t2i_1024** (sglang): 14.31s -> 24.21s (+69.2%)
> - **qwen_image_2512_t2i_1024** (sglang): 12.81s -> 26.21s (+104.7%)
> - **qwen_image_edit_2511** (sglang): 23.77s -> 36.95s (+55.4%)
> - **zimage_turbo_t2i_1024** (sglang): 0.65s -> 13.46s (+1970.5%)
> - **wan22_t2v_a14b_720p** (sglang): 209.17s -> 221.57s (+5.9%)
> - **wan22_ti2v_5b_720p** (sglang): 65.22s -> 70.21s (+7.6%)
> - **ltx2.3_twostage_ti2v_2gpus** (sglang): 16.06s -> 40.16s (+150.0%)
> - **ideogram4_fp8_t2i_2gpu** (sglang): 5.19s -> 11.50s (+121.7%)
> - **cosmos3_super_t2v_2gpu** (sglang): 113.80s -> 143.65s (+26.2%)


## SGLang-Diffusion Performance

| Model | Risk | sglang (s) |
|-------|------|---------|
| FLUX.1-dev | ⚠️ | **10.97** |
| FLUX.2-dev | ⚠️ | **24.21** |
| Qwen-Image-2512 | ⚠️ | **26.21** |
| Qwen-Image-Edit-2511 | ⚠️ | **36.95** |
| Z-Image-Turbo | ⚠️ | **13.46** |
| Wan2.2-T2V-A14B-Diffusers | ⚠️ | **221.57** |
| Wan2.2-TI2V-5B-Diffusers | ⚠️ | **70.21** |
| LTX-2.3 | ⚠️ | **40.16** |
| ideogram-4-fp8 | ⚠️ | **11.50** |
| Cosmos3-Super | ⚠️ | **143.65** |
| Wan2.2-I2V-A14B-Diffusers | ✅ | **211.72** |

### Latency Trend: flux1_dev_t2i_1024

![Latency Trend flux1_dev_t2i_1024](https://raw.githubusercontent.com/sgl-project/ci-data/main/diffusion-comparisons/charts/latency_flux1_dev_t2i_1024.png)


### Latency Trend: flux2_dev_t2i_1024

![Latency Trend flux2_dev_t2i_1024](https://raw.githubusercontent.com/sgl-project/ci-data/main/diffusion-comparisons/charts/latency_flux2_dev_t2i_1024.png)


### Latency Trend: qwen_image_2512_t2i_1024

![Latency Trend qwen_image_2512_t2i_1024](https://raw.githubusercontent.com/sgl-project/ci-data/main/diffusion-comparisons/charts/latency_qwen_image_2512_t2i_1024.png)


### Latency Trend: qwen_image_edit_2511

![Latency Trend qwen_image_edit_2511](https://raw.githubusercontent.com/sgl-project/ci-data/main/diffusion-comparisons/charts/latency_qwen_image_edit_2511.png)


### Latency Trend: zimage_turbo_t2i_1024

![Latency Trend zimage_turbo_t2i_1024](https://raw.githubusercontent.com/sgl-project/ci-data/main/diffusion-comparisons/charts/latency_zimage_turbo_t2i_1024.png)


### Latency Trend: wan22_t2v_a14b_720p

![Latency Trend wan22_t2v_a14b_720p](https://raw.githubusercontent.com/sgl-project/ci-data/main/diffusion-comparisons/charts/latency_wan22_t2v_a14b_720p.png)


### Latency Trend: wan22_ti2v_5b_720p

![Latency Trend wan22_ti2v_5b_720p](https://raw.githubusercontent.com/sgl-project/ci-data/main/diffusion-comparisons/charts/latency_wan22_ti2v_5b_720p.png)


### Latency Trend: ltx2.3_twostage_ti2v_2gpus

![Latency Trend ltx2.3_twostage_ti2v_2gpus](https://raw.githubusercontent.com/sgl-project/ci-data/main/diffusion-comparisons/charts/latency_ltx2.3_twostage_ti2v_2gpus.png)


### Latency Trend: ideogram4_fp8_t2i_2gpu

![Latency Trend ideogram4_fp8_t2i_2gpu](https://raw.githubusercontent.com/sgl-project/ci-data/main/diffusion-comparisons/charts/latency_ideogram4_fp8_t2i_2gpu.png)


### Latency Trend: cosmos3_super_t2v_2gpu

![Latency Trend cosmos3_super_t2v_2gpu](https://raw.githubusercontent.com/sgl-project/ci-data/main/diffusion-comparisons/charts/latency_cosmos3_super_t2v_2gpu.png)


### Latency Trend: wan22_i2v_a14b_720p

![Latency Trend wan22_i2v_a14b_720p](https://raw.githubusercontent.com/sgl-project/ci-data/main/diffusion-comparisons/charts/latency_wan22_i2v_a14b_720p.png)


## SGLang Performance Trend (Last 30 Runs)

| Date | Commit | flux1_dev_t2i_1024 (s) | flux2_dev_t2i_1024 (s) | qwen_image_2512_t2i_1024 (s) | qwen_image_edit_2511 (s) | zimage_turbo_t2i_1024 (s) | wan22_t2v_a14b_720p (s) | wan22_ti2v_5b_720p (s) | ltx2.3_twostage_ti2v_2gpus (s) | ideogram4_fp8_t2i_2gpu (s) | cosmos3_super_t2v_2gpu (s) | wan22_i2v_a14b_720p (s) | Trend |
|------|--------|---------|---------|---------|---------|---------|---------|---------|---------|---------|---------|---------|-------|
| Jun 27 | `528f170` | 10.97 | 24.21 | 26.21 | 36.95 | 13.46 | 221.57 | 70.21 | 40.16 | 11.50 | 143.65 | 211.72 | :arrow_up:  :arrow_up:  :arrow_up:  :arrow_up:  :arrow_up:  :arrow_up:  :arrow_up:  :arrow_up:  :arrow_up:  :arrow_up:  :arrow_up: |
| Jun 27 | `b78e95c` | 4.68 | 14.31 | 12.81 | 23.77 | 0.65 | 209.17 | 65.22 | 16.06 | 5.19 | 113.80 | 204.59 |      :left_right_arrow:  :left_right_arrow:  :arrow_up:   :left_right_arrow:  :left_right_arrow: |
| Jun 27 | `a526ca2` | N/A | N/A | N/A | N/A | N/A | 209.33 | 65.19 | 15.05 | N/A | 113.74 | 204.61 |      :left_right_arrow:  :left_right_arrow:  :left_right_arrow:    |
| Jun 27 | `13b5bd9` | 4.68 | 14.31 | 12.79 | 23.65 | 0.65 | 209.32 | 64.20 | 15.05 | N/A | N/A | N/A | :left_right_arrow:  :arrow_down:  :left_right_arrow:  :left_right_arrow:  :arrow_down:  :left_right_arrow:  :left_right_arrow:  :arrow_up:    |
| Jun 26 | `781537b` | 4.63 | 15.76 | 12.69 | 23.60 | 0.82 | 208.96 | 64.24 | 14.05 | N/A | N/A | 205.62 | :left_right_arrow:  :arrow_up:  :left_right_arrow:  :left_right_arrow:  :arrow_up:  :left_right_arrow:  :left_right_arrow:  :arrow_down:    :left_right_arrow: |
| Jun 25 | `7002a37` | 4.68 | 14.32 | 12.75 | 23.62 | 0.66 | 209.34 | 64.22 | 15.06 | N/A | N/A | 204.64 | :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :arrow_up:  :left_right_arrow:  :left_right_arrow:  :arrow_up:    :left_right_arrow: |
| Jun 24 | `5e6d7c1` | 4.68 | 14.36 | 12.82 | 23.75 | 0.64 | 209.73 | 65.22 | 14.06 | N/A | N/A | 205.65 | :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:    :left_right_arrow: |
| Jun 23 | `7e6587c` | 4.68 | 14.35 | 12.84 | 23.79 | 0.64 | 209.91 | 65.20 | 14.05 | N/A | N/A | 205.65 | :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:    :left_right_arrow: |
| Jun 23 | `a17753e` | 4.68 | 14.34 | 12.80 | 23.72 | 0.64 | 211.07 | 65.22 | 14.05 | N/A | N/A | 205.68 | :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:    :left_right_arrow: |
| Jun 22 | `6779ca8` | 4.65 | 14.37 | 12.83 | 23.76 | 0.64 | 209.96 | 65.23 | 14.05 | N/A | N/A | 205.58 | :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :arrow_down:    :left_right_arrow: |
| Jun 21 | `2552b86` | 4.67 | 14.33 | 12.74 | 23.63 | 0.65 | 209.38 | 64.15 | 19.07 | N/A | N/A | 204.55 | :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :arrow_down:  :left_right_arrow:  :left_right_arrow:  :arrow_up:    :left_right_arrow: |
| Jun 20 | `2cbe1e6` | 4.65 | 14.33 | 12.78 | 23.63 | 0.66 | 209.30 | 64.20 | 15.05 | N/A | N/A | 205.54 | :arrow_down:  :arrow_down:  :left_right_arrow:  :left_right_arrow:  :arrow_down:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:    :left_right_arrow: |
| Jun 19 | `05ee93c` | 6.99 | 24.86 | 12.81 | 23.75 | 0.91 | 209.14 | 65.23 | 15.06 | N/A | N/A | 204.65 | :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :arrow_down:    :left_right_arrow: |
| Jun 18 | `74e2e48` | 6.93 | 24.48 | 12.71 | 23.57 | 0.92 | 209.03 | 64.21 | 24.08 | N/A | N/A | 204.67 | :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :arrow_up:    :left_right_arrow: |
| Jun 17 | `d86a7e7` | 6.99 | 24.66 | 12.85 | 23.70 | 0.91 | 211.01 | 65.22 | 20.08 | N/A | N/A | 206.64 | :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :arrow_up:    :left_right_arrow: |
| Jun 16 | `2dd449c` | 6.91 | 24.46 | 12.71 | 23.52 | 0.90 | 210.42 | 64.23 | 18.07 | N/A | N/A | 205.75 | :arrow_down:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :arrow_down:    :left_right_arrow: |
| Jun 15 | `1a66059` | 7.10 | 24.61 | 12.75 | 23.64 | 0.91 | 210.43 | 65.21 | 31.11 | N/A | N/A | 206.72 | :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :arrow_up:    :left_right_arrow: |
| Jun 14 | `a3fd5c2` | 7.12 | 24.65 | 12.82 | 23.76 | 0.90 | 212.96 | 65.22 | 20.07 | N/A | N/A | 208.71 | :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :arrow_up:    :left_right_arrow: |
| Jun 13 | `5633ca8` | 7.11 | 24.65 | 12.82 | 23.83 | 0.91 | 212.92 | 65.26 | 19.07 | N/A | N/A | 207.70 | :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:    :left_right_arrow: |
| Jun 12 | `2e74ff1` | 7.08 | 24.55 | 12.75 | 23.70 | 0.91 | 212.40 | 64.23 | 19.15 | N/A | N/A | 207.67 | :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :arrow_up:    :left_right_arrow: |
| Jun 11 | `99ab90c` | 7.11 | 24.61 | 12.85 | 23.75 | 0.92 | 212.92 | 65.22 | 17.07 | N/A | N/A | 207.70 | :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :arrow_up:  :left_right_arrow:  :left_right_arrow:  :arrow_down:    :left_right_arrow: |
| Jun 10 | `f3ecc36` | 7.09 | 24.67 | 12.81 | 23.74 | 0.90 | 212.87 | 65.22 | 26.09 | N/A | N/A | 208.68 | :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :arrow_up:    :left_right_arrow: |
| Jun 10 | `0f86738` | 7.03 | 24.49 | 12.70 | 23.57 | 0.90 | 212.18 | 64.21 | 18.07 | N/A | N/A | 207.70 | :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :arrow_down:    :left_right_arrow: |
| Jun 09 | `0f86738` | 7.05 | 24.60 | 12.79 | 23.61 | 0.91 | 212.41 | 64.20 | 26.11 | N/A | N/A | 207.70 | :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :arrow_up:    :left_right_arrow: |
| Jun 09 | `317fc6a` | 7.04 | 24.48 | 12.73 | 23.54 | 0.89 | 212.28 | 64.19 | 17.07 | N/A | N/A | 207.71 | :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :arrow_down:    :left_right_arrow: |
| Jun 08 | `303757c` | 7.04 | 24.48 | 12.70 | 23.54 | 0.90 | 212.35 | 64.19 | 22.08 | N/A | N/A | 207.62 | :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :arrow_down:  :left_right_arrow:  :left_right_arrow:  :arrow_up:    :left_right_arrow: |
| Jun 07 | `5160f79` | 7.09 | 24.65 | 12.85 | 23.81 | 0.93 | 212.69 | 65.18 | 17.06 | N/A | N/A | 207.62 | :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :arrow_down:    :left_right_arrow: |
| Jun 06 | `b3e4c20` | 7.11 | 24.64 | 12.83 | 23.78 | 0.92 | 212.35 | 65.23 | 31.11 | N/A | N/A | 207.70 | :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :arrow_up:    :left_right_arrow: |
| Jun 05 | `5af02c1` | 7.12 | 24.59 | 12.81 | 23.77 | 0.90 | 212.94 | 65.18 | 17.06 | N/A | N/A | 208.67 | :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :arrow_down:    :left_right_arrow: |
| Jun 04 | `14ed9b4` | 7.03 | 24.53 | 12.73 | 23.56 | 0.90 | 212.01 | 64.21 | 18.07 | N/A | N/A | 207.65 | -- |

> [!CAUTION]
> **Action Required — Performance Alert**
>
> The following cases need attention:
> - flux1_dev_t2i_1024: SGLang regression +134.5% vs 3-run avg (10.97s vs 4.68s)
> - flux2_dev_t2i_1024: SGLang regression +69.2% vs 3-run avg (24.21s vs 14.31s)
> - qwen_image_2512_t2i_1024: SGLang regression +104.8% vs 3-run avg (26.21s vs 12.80s)
> - qwen_image_edit_2511: SGLang regression +55.9% vs 3-run avg (36.95s vs 23.71s)
> - zimage_turbo_t2i_1024: SGLang regression +1978.5% vs 3-run avg (13.46s vs 0.65s)
> - wan22_t2v_a14b_720p: SGLang regression +5.9% vs 3-run avg (221.57s vs 209.27s)
> - wan22_ti2v_5b_720p: SGLang regression +8.2% vs 3-run avg (70.21s vs 64.87s)
> - ltx2.3_twostage_ti2v_2gpus: SGLang regression +161.0% vs 3-run avg (40.16s vs 15.39s)
> - ideogram4_fp8_t2i_2gpu: SGLang regression +121.7% vs 3-run avg (11.50s vs 5.19s)
> - cosmos3_super_t2v_2gpu: SGLang regression +26.3% vs 3-run avg (143.65s vs 113.77s)


---
*Generated by `generate_diffusion_dashboard.py` in SGLang nightly CI.*
