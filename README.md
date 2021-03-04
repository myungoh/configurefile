# configurefile
The configuration file of Multilayer VVC and SHVC used in the experiment.

How to execute
===============================
* VTM Encoder example
  - ./EncoderAppStatic -c [encoder environment cfg].cfg -c cfg/multi-layer/two_layers.cfg -l0 -c cfg/per-sequence/[l0 sequence cfg].cfg -l1 -c cfg/per-sequence/[l1 sequence cfg].cfg -q [qp] -l0 --InputFile=[input yuv file1] -l1 --InputFile=[input yuv file2] -b [bin file]

* VTM Decoder
  - ./DecoderAppStatic -b [bin file]
