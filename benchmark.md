## Qwen/Qwen3-4B-Thinking-2507

FA/FI Prefill/Decode:
Total: 133966tok, Time: 27.40s, Throughput: 4888.83tok/s

QFA Prefill/Decode: 
Total: 133966tok, Time: 116.61s, Throughput: 1148.80tok/s
POST: Total: 133966tok, Time: 137.37s, Throughput: 975.23tok/s

QFA/FI Prefill/Decode: 
Total: 133966tok, Time: 67.09s, Throughput: 1996.83tok/s

FI/QFA Prefill/Decode: 
Total: 133966tok, Time: 75.20s, Throughput: 1781.42tok/s
POST: Total: 133966tok, Time: 88.20s, Throughput: 1518.88tok/s

Bottleneck seems to be QFA on decode rather than prefill?