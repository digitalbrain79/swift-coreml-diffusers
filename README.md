# Swift Core ML Diffusers

## Tested on

|      Device       | iOS  | coremltools |
|:-----------------:|:----:|:-----------:|
| iPhone 16 Pro Max | 18.0 |     8.0     |

## Performance

|                                       Model                                       | Quantization |  Compute Unit  | Resolution | Latency(s) |
|:---------------------------------------------------------------------------------:|:------------:|:--------------:|:----------:|:---------:|
| [DreamShaper XL Lightning 4step](https://huggingface.co/digitalbrain79/dreamshaper-xl-lightning-4step-ios-6bits-compiled) |    6bits     | SPLIT_EINSUM | 1024x1024  |     10    |
