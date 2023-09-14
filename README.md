# LLM
```
1.Exploring Zero-shot, One-shot and Few-shot strategies
2.Implementing LLM finetuning using LoRA/PEFT adapter and RLHF strategies

```

```
3. Quantization using BitsAndBytes(QLoRA-nested_quant) vs GPTQ
   Observations on model (NousResearch/Llama-2-7b-chat-hf)
   * original size: 3,829,940,224 bytes
   * after training/tuning: 4,488,978,432 bytes
   * after loading PEFT adapters: 13,543,948,288 bytes
  GPTQ operation error: unable to perform disk offload on colab free tier (15Gb)
```
```
4. Experimenting  GGUF (Generalizable Generative UTF) to run querys on codellama-13b-instruct
```
