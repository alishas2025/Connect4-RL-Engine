# Connect4-RL-Engine
A reinforcement learning study comparing two agent architectures — Policy Gradient (REINFORCE) and Double Deep Q-Network (DDQN) — trained to play Connect-4 competitively using self-play.
Both agents are initialized from a pretrained CNN base (M1) that mimics Monte Carlo Tree Search, then fine-tuned through adversarial training. Performance is validated via an internal round-robin tournament across four agents.
Key Results: DDQN finished 1st (58.2% win rate), Policy Gradient 2nd (55.0%), both significantly outperforming the base CNN model.
