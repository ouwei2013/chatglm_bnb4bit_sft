#### Finetune chatglm with bnb-4bit and lora: a simplified implementation 
#### 基于4 bit和lora的简易版chatglm微调
#### No abstraction, no complicated arguments, everything is simple and straightforward
#### 该代码没有任何抽象设计，也没有复杂的参数，主打一个直观和直接
#### You can easily finetune on your own data simply by replacing your data with mine in the jupyternotebook
#### 只要把我的数据改成你自己的数据，你应该会很容易跑起来
#### Memory footprint: Max GPU VRAM usage is approximately 18GB (max_source_len=1024,max_target_len=512,lora_r=64)
#### 最大现存使用量18G
#### You can reduce the memory footprint by setting lora_r, max_source_len and max_target_len
#### 你也可以调整lora的值，或者source和target句子的长度来进一步减少内存使用量

