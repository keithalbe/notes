## Query NVIDIA GPU Info
```bash
nvidia-smi --query-gpu=timestamp,temperature.gpu,utilization.gpu,power.draw --format=csv -l 1
```
