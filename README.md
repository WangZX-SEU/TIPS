# __TIPS: Tiered Information-Rich Planning Strategy for Efficient AGV Autonomous Exploration__

🎇🎇🎇 Our paper has been accpeted by _IEEE Robotics and Automation Letters (RAL)_ on October 16, 2025. 

## 📖 Abstract
We propose a tiered systematic framework to enhance the overall efficiency and environmental coverage of autonomous exploration for Autonomous GroundVehicle (AGV) in complex environments with narrow regions. At the local level, we introduce a novel Multi-cause Triggering Sensor Model (MTSM) to improve informative observation acquisition in narrow regions. Furthermore, the Frontier set is defined from a probabilistic distribution perspective and utilized to optimize the initial training pool of Bayesian optimization, thereby accelerating convergence toward the optimal navigation target point. At the global level, we incrementally maintain an Information-Rich Sparse Roadmap (IRSR) by leveraging accumulated historical exploration knowledge. When a dead zone situation is detected, the heuristic guidance is activated and realized by graph search considering information content and distance between IRSR vertices, enabling AGV to maintain a continuous and sustained exploration process.

<p align="center">
  <img src="./figures/MTSM_three_causes.png" width = "400" height = "273"/>
    &nbsp;&nbsp;&nbsp;  &nbsp;&nbsp;&nbsp;
  <img src="./figures/BKIO_with_Frontier.png" width = "500" height = "373"/>
</p>

## 🔗 Paper Link 
[TIPS: Tiered Information-Rich Planning Strategy for Efficient AGV Autonomous Exploration](https://ieeexplore.ieee.org/abstract/document/11214391)

## 🎥 Demonstration Video 
Please Check out our demonstration video on [YouTube](https://www.youtube.com/watch?v=0_vi6ks_7sw):

[![Watch the video](./figures/TIPS_cover.png)](https://www.youtube.com/watch?v=0_vi6ks_7sw)

## 🧩 Source code
The code will be open-source after re-organization.

## ✒️ Cite
Please cite our paper if you think our work is useful to your scientific research:
```
@ARTICLE{wang2025tips,
  title={TIPS: Tiered Information-Rich Planning Strategy for Efficient AGV Autonomous Exploration},
  author={Wang, Zhuoxuan and Pan, Shuguo and Xu, Jinle and Tao, Xianlu and Gao, Wang and Wang, Qiang},
  journal={IEEE Robotics and Automation Letters}, 
  year={2025},
  volume={10},
  number={12},
  pages={12764-12771},
}
```
## 🔈 Acknowledgements
