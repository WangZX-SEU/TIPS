# TIPS
## __TIPS: Tiered Information-Rich Planning Strategy for Efficient UGV Autonomous Exploration__

__We are working on an information-based autonomous exploring framework for UGV. The paper has been submitted to _IEEE Robotics and Automation Letters (RAL)_, and we plan to open-source the code after the paper is accepted.__

🎥 __Check out our demonstration video on [YouTube](https://youtu.be/hofE96Iaikg):__

[![Watch the video](./TIPS_cover.png)](https://youtu.be/hofE96Iaikg)

## Paper abstract
In this letter, we propose a novel tiered systematic framework to enhance the overall efficiency of autonomous exploration for Unmanned Ground Vehicles (UGVs) in complex environments with narrow regions. At the local level, we introduce a novel Multi-cause Triggering Sensor Model (MTSM) to improve informative observation acquisition in narrow areas. Furthermore, the frontier set is defined from a probabilistic distribution perspective and utilized to optimize the initial training pool of the Bayesian optimization, thereby accelerating convergence toward the optimal navigation target. Moreover, we incrementally maintain an Information-Rich Sparse Roadmap (IRSR) by leveraging accumulated historical exploration knowledge. At the global level, when a dead-zone situation is detected, the heuristic guidance is activated and realized by solving an ATSP based on IRSR, enabling UGV to maintain a continuous autonomous exploration process. We design three simulation scenarios with increasing complexity and conduct comprehensive evaluations against state-of-the-art approaches. The results demonstrate that our framework achieves a favorable balance between exploration efficiency and coverage completeness, with superior performance in narrow regions. Subsequent real-world experiments further validate the potential of our proposed method for practical applications.
