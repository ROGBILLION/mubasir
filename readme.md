# Effortless SINGLE GPU Mining with XENBLOCKS

Easily set up a GPU mining server for XENBLOCKS with just a single command. Here's how you get started:

1. **Clone this Repository**: 
   - First, clone this repository to your own public repository.

2. **Update Your Address**:
   - Navigate to `gpu.sh` and replace the existing address with your own as illustrated below:
   ![image](https://github.com/JozefJarosciak/xgpu/assets/3492464/807a9935-17ec-4cd8-8dd3-bfff04b65060)


3. **Kickstart Mining**:
   - Now you're all set! Use the command below to get your new GPU server up and running—from 0 to full-speed mining 
   - Note: of course replace (JozefJarosciak/xgpu/main/gpu.sh) with path to your repo
   ```
   apt update && apt -y install wget && wget https://raw.githubusercontent.com/JozefJarosciak/xgpu/main/gpu.sh && chmod +x gpu.sh && ./gpu.sh
   ```


# Execute multi deployment 
Same idea as above, but now you can run multi-GPU with one command (if you order such a setup.
```
apt update && apt -y install wget && wget https://raw.githubusercontent.com/JozefJarosciak/xgpu/main/gpu2.sh && chmod +x gpu2.sh && ./gpu2.sh
```

# USEFUL COMMANDS 

Tail logs:
```
tail -f /XENGPUMiner/miner.log
tail -f /XENGPUMiner/xengpuminer.log
```

Maintenance kill multiple instances when needed
```
pkill -f "xengpuminer"
```
