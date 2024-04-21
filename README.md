#Train cmd
"/workspace/kohya_ss/venv/bin/accelerate" launch --dynamo_backend no --dynamo_mode default --mixed_precision bf16 --num_processes 1 --num_machines 1 --num_cpu_threads_per_process 2 "/workspace/kohya_ss/sd-scripts/sdxl_train.py" --config_file "/workspace/flowers-reg-sdxl/model/config.toml"


