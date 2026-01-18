# Isaacsim-rl-agent
A layered autonomous RL agent built in Isaac Sim, integrating PID control, reinforcement learning, imitation learning, and lightweight RLHF.

## For TensorBoard Logs

### 1. Install TensorBoard

If not already installed:
```bash
pip install tensorboard
```

### 2. Launch TensorBoard

**View all experiments:**
```bash
tensorboard --logdir logs/rsl_rl
```

**View a specific project (e.g., `pf_tron_1a_flat`):**
```bash
tensorboard --logdir logs/rsl_rl/pf_tron_1a_flat
```

**View a specific run:**
```bash
tensorboard --logdir logs/rsl_rl/pf_tron_1a_flat/2026-01-16_17-01-13
```

### 3. Open the Dashboard

After launching TensorBoard, open your browser to:
```
http://localhost:6006
```

Or use the dev container browser helper:
```bash
$BROWSER http://localhost:6006
```

### Remote Access
If running on a remote server, use SSH port forwarding:
```bash
ssh -L 6006:localhost:6006 user@remote-server
```

Then access `http://localhost:6006` on your local machine.

