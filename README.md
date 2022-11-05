# Addition of Addition of PPO, Twin Delayed DDPG, Hindsight Experience Replay to RL Codebase 

<p align="center">
<a href="https://summerofcode.withgoogle.com/"><img style="padding: 20px;" alt="drawing" src="GSoC_logo.png" height="200"></a>
<a href="https://www.mlpack.org/"><img style="padding: 20px;" alt="drawing" src="mlpack.png" height="200"></a>
</p>

Hi! Maintaining mlpack's tradition, this page contains weekly updates and report of my contributions at mlpack during Google Summer of Code(2022).



## Overview:
I will spending my summer, working on **PPO** [Schulman et al., 2017](), **TD3** [Fujimoto et. al 2018]() and **Hindsight Experience Replay (HER)** [Andrychowicz et al., 2018](). 

These are in-demand and must-have algorithms, whose implementation in [mlpack](http://mlpack.org/) would be crucial.

So here are the details of what I expect to have accomplished at the end of the summer.
1) Addition of Hindsight Experience Replay along with thorough testing
2) Implementing Proximal Policy Gradient (PPO) along with its tests
3) Implementing TD3 along with test cases.
4) Creating detailed docs for all the above implementations
5) Benchmarking of Current RL Algorithms on various environments and comparing
performances between algorithms - for example : TD3+HER vs TD3 or
DQN+HER vs DQN
    - Addition of simple tutorials demonstrating usability of implemented algorithm
    - Creating necessary environments, for proper testing of algorithms above (after
discussion with mentor)

*The original project proposal can be found on the GSoC website [here](https://summerofcode.withgoogle.com/programs/2022/projects/m6ZxRreD).*

## the Code:
Links to open and merged pull requests can be found [here](PRs.md).

[https://github.com/mlpack/mlpack/pull/3239](https://github.com/mlpack/mlpack/pull/3239) - Proximal Policy Optimization
       
[https://github.com/mlpack/mlpack/pull/3283](https://github.com/mlpack/mlpack/pull/3283) - Hindsight Experience Replay, Bit Flipping Environment, Maze Environment

[https://github.com/mlpack/mlpack/pull/3306](https://github.com/mlpack/mlpack/pull/3306) - HER Tutorial with Maze environment

## Acknowledgements:
There has been a lot of coding, experimentation, thousands of builds and never ending debugging, so much that to think that it is coming to a wrap up doesn’t feel like reality. Special thanks to Sai, Marcus and Fauz, my mentors this year, who had the answers to almost all the problems I faced. With you peopl's support, I had a very smooth and enjoyable experience.

I would also like to acknowledge the help from other members of the community, who were always available whenever needed, just a small chat away. I strongly intend to continue contributing to mlpack in all the ways I can, because it's just too much fun. :)

I would also like to thank @nishantkr9 for their proposal reviews.

Also, thanks to Google for this amazing opportunity and the generous funding.

This has been a summer worth remembering!


