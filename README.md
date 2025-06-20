# TIPS
## __TIPS: Tiered Information-Rich Planning Strategy for Efficient UGV Autonomous Exploration__

💡 We are working on an information-based autonomous exploring framework for UGV. The paper has been submitted to _IEEE Robotics and Automation Letters (RAL)_, and we plan to open-source the code after the paper is accepted.

🎥 __Check out our demonstration video on [YouTube](https://youtu.be/hofE96Iaikg):__

[![Watch the video](./TIPS_cover.png)](https://youtu.be/hofE96Iaikg)

## Paper abstract
In this letter, we propose a tiered systematic framework to address the potential issues of low efficiency and incomplete environmental coverage of autonomous exploration for Unmanned Ground Vehicle (UGV) in complex environments with narrow regions. At the local level, we introduce a novel Multi-cause Triggering Sensor Model (MTSM) to improve informative observation acquisition in narrow areas. Furthermore, the Frontier set is defined from a probabilistic distribution perspective and utilized to optimize the initial training pool of Bayesian optimization, thereby accelerating convergence toward the optimal navigation target point. At the global level, we incrementally maintain an Information-Rich Sparse Roadmap (IRSR) by leveraging accumulated historical exploration knowledge. When a dead zone situation is detected, the heuristic guidance is activated and realized by solving an ATSP based on IRSR, enabling UGV to maintain a continuous and sustained autonomous exploration process. Three simulation scenarios with increasing complexity are designed, in which comprehensive comparisons and evaluations against different types of state-of-the-art approaches are conducted. The results demonstrate that our framework achieves a favorable balance between algorithm runtime, exploration efficiency and coverage completeness, with superior performance in narrow regions. Subsequent real-world experiments further validate the strong potential of our proposed method for practical applications. 
