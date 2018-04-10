# Cartpole-Algs
Solving the CartPole environment using deep Q-Learning, random search, and evolution strategies

Turns out that random search is the most effective by far (finds solution within on average 10-20 episodes). Consequently, need to find a more challenging problem to compare RS/ES with GA. The deep Q-Learning implementation is separate and not comparable to any algorithms based on the given state.

To run jupyter notebooks with gym on a server:

    xvfb-run --auto-servernum -s "-screen 0 1400x900x24" jupyter notebook
