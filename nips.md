1. git clone https://github.com/ChaoGaoUCR/DiT-mine.git
<!-- Cuda should be 11.7 as well as torch -->
<!-- add peft.tuners.lora.Linear: ['weight'] , add import peft add "lora" not in name -->
2. git clone https://github.com/NVIDIA/apex
3. cd apex
4. pip install -v --disable-pip-version-check --no-cache-dir --no-build-isolation --config-settings "--build-option=--cpp_ext" --config-settings "--build-option=--permutation_search" ./