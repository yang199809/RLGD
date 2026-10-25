# RLGD

**A High-Resolution UAV Dataset and Benchmark for Semantic Segmentation and Revetment Extraction in Waterway Scenes**

[Paper](https://doi.org/10.3390/rs18213656) · [Download](#download)

RLGD provides 100 UAV images at 3000 × 4000 pixels, with 1.2 billion labeled pixels across eight classes. It supports waterway semantic segmentation and revetment extraction along the Jingjiang section of the Yangtze River, China.

## Dataset

The release contains **1,200 overlapping 1024 × 1024 image tiles** and their semantic masks.

| Split | Source images | Tiles |
|---|---:|---:|
| Train | 70 | 840 |
| Validation | 20 | 240 |
| Test | 10 | 120 |

**Class IDs:** 0 Other · 1 Building · 2 Road · 3 Vegetation · 4 Vehicle · 5 Water · 6 Ship · 7 Revetment.

Masks are single-channel PNGs storing IDs **0–7**; **0 is a valid class**. Optional auxiliary boundary maps are provided in `edges/`.

See [metadata](metadata/) for file descriptions, [splits](splits/) for the fixed partition, and [tools](tools/) for full-image reconstruction.

## Download

- **Baidu Netdisk:** 通过网盘分享的文件：RLGD.zip
链接: https://pan.baidu.com/s/1pXCva9dHZVBagoH7BEoTBA?pwd=ezae 提取码: ezae.
