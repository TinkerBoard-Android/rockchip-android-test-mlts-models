Copyright 2017 The Android Open Source Project

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

     http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
------------------------------------------------------------------

This directory contains models data for the Android Neural Networks API benchmarks.

Included models:

------------------------------------------------------------------
- mobilenet_float.tflite
MobileNet tensorflow lite model based on:
"MobileNets: Efficient Convolutional Neural Networks for Mobile Vision Applications"
https://arxiv.org/abs/1704.04861

------------------------------------------------------------------
- mobilenet_quantized.tflite
8bit quantized MobileNet tensorflow lite model based on:
"MobileNets: Efficient Convolutional Neural Networks for Mobile Vision Applications"
https://arxiv.org/abs/1704.04861

------------------------------------------------------------------
- hdrnet_float.tflite
Partial tensorflow lite model based on
"Deep Bilateral Learningfor Real-Time Image Enhancement"
https://groups.csail.mit.edu/graphics/hdrnet/

It's partial because Pack and Transpose operations were not supported at the time
of model creation.

------------------------------------------------------------------
- hdrnet_quantized.tflite
8bit quantized partial tensorflow lite model based on
"Deep Bilateral Learning for Real-Time Image Enhancement"
https://groups.csail.mit.edu/graphics/hdrnet/


TODO(pszczepaniak): Update hdrnet to full model with pack and transpose
TODO(pszczepaniak): Provide at least 5 inputs outputs for each model

