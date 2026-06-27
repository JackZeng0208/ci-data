# SGLang-Diffusion Nightly Performance Dashboard

*Generated: Jun 27 | Commit: `a526ca2`*

## SGLang-Diffusion Performance

| Model | Risk | sglang (s) |
|-------|------|---------|
| FLUX.1-dev | ❌ | N/A |
| FLUX.2-dev | ❌ | N/A |
| Qwen-Image-2512 | ❌ | N/A |
| Qwen-Image-Edit-2511 | ❌ | N/A |
| Z-Image-Turbo | ❌ | N/A |
| Wan2.2-T2V-A14B-Diffusers | ✅ | **209.33** |
| Wan2.2-TI2V-5B-Diffusers | ✅ | **65.19** |
| LTX-2.3 | ✅ | **15.05** |
| ideogram-4-fp8 | ❌ | N/A |
| Cosmos3-Super | ✅ | **113.74** |
| Wan2.2-I2V-A14B-Diffusers | ✅ | **204.61** |

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


### Latency Trend: cosmos3_super_t2v_2gpu

![Latency Trend cosmos3_super_t2v_2gpu](https://raw.githubusercontent.com/sgl-project/ci-data/main/diffusion-comparisons/charts/latency_cosmos3_super_t2v_2gpu.png)


### Latency Trend: wan22_i2v_a14b_720p

![Latency Trend wan22_i2v_a14b_720p](https://raw.githubusercontent.com/sgl-project/ci-data/main/diffusion-comparisons/charts/latency_wan22_i2v_a14b_720p.png)


## SGLang Performance Trend (Last 29 Runs)

| Date | Commit | flux1_dev_t2i_1024 (s) | flux2_dev_t2i_1024 (s) | qwen_image_2512_t2i_1024 (s) | qwen_image_edit_2511 (s) | zimage_turbo_t2i_1024 (s) | wan22_t2v_a14b_720p (s) | wan22_ti2v_5b_720p (s) | ltx2.3_twostage_ti2v_2gpus (s) | ideogram4_fp8_t2i_2gpu (s) | cosmos3_super_t2v_2gpu (s) | wan22_i2v_a14b_720p (s) | Trend |
|------|--------|---------|---------|---------|---------|---------|---------|---------|---------|---------|---------|---------|-------|
| Jun 27 | `a526ca2` | N/A | N/A | N/A | N/A | N/A | 209.33 | 65.19 | 15.05 | N/A | 113.74 | 204.61 |      :left_right_arrow:  :left_right_arrow:  :left_right_arrow:    |
| Jun 27 | `13b5bd9` | 4.68 | 14.31 | 12.79 | 23.65 | 0.65 | 209.32 | 64.20 | 15.05 | N/A | N/A | N/A | :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:    |
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
| Jun 04 | `14ed9b4` | 7.03 | 24.53 | 12.73 | 23.56 | 0.90 | 212.01 | 64.21 | 18.07 | N/A | N/A | 207.65 | :left_right_arrow:  :arrow_down:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :arrow_down:    :left_right_arrow: |
| Jun 03 | `83bc776` | 7.06 | 25.15 | 12.73 | 23.57 | 0.90 | 212.26 | 64.20 | 21.08 | N/A | N/A | 207.65 | :left_right_arrow:  :arrow_up:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :left_right_arrow:  :arrow_down:    :left_right_arrow: |
| Jun 01 | `373cadc` | 7.04 | 24.59 | 12.74 | 23.65 | 0.90 | 212.46 | 64.16 | 23.08 | N/A | N/A | 207.52 | -- |

> [!CAUTION]
> **Action Required — Performance Alert**
>
> The following cases need attention:
> - flux1_dev_t2i_1024: SGLang latency is N/A (broken)
> - flux2_dev_t2i_1024: SGLang latency is N/A (broken)
> - qwen_image_2512_t2i_1024: SGLang latency is N/A (broken)
> - qwen_image_edit_2511: SGLang latency is N/A (broken)
> - zimage_turbo_t2i_1024: SGLang latency is N/A (broken)
> - ideogram4_fp8_t2i_2gpu: SGLang latency is N/A (broken)


---
*Generated by `generate_diffusion_dashboard.py` in SGLang nightly CI.*
