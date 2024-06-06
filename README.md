# Waifu2x-buda

An attempt to get waifu2x to work on Tenstorrent devices using the [BUDA](https://github.com/tenstorrent/tt-buda) compiler.

**NOTHING WORKS YET**

## Running

* Grab the model `noise0_scale2x.onnx` from [deepghs/waifu2x_onnx on hugginghace](https://huggingface.co/deepghs/waifu2x_onnx/blob/main/20230504/onnx_models/cunet/art/noise0_scale2x.onnx)
* Place test.jpg in the CWD
* Run `python3 main.py`
