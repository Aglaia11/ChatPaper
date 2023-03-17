## Paper:1




1. Title: "Good Robot!": Efficient Reinforcement Learning for Multi-Step Visual Tasks with Sim to Real Transfer

2. Authors: Andrew Hundt, Benjamin Killeen, Nicholas Greene, Hongtao Wu, Heeyeon Kwon, Chris Paxton, and Gregory D. Hager

3. Affiliation: The first author's affiliation is The Johns Hopkins University.

4. Keywords: reinforcement learning, multi-step tasks, sim to real transfer, computer vision, grasping and manipulation, action safety zones, deep learning

5. Urls: Paper: None, Code: https://github.com/jhulcsr/good_robot

6. Summary: 

- (1): 本论文研究的背景是针对实现复杂多步骤视觉任务的效率和准确性方面的问题。

- (2): 过去的机器学习算法存在遗漏和进展倒退的问题，本文的方法受到了正强化（Positive Conditioning）训练方法的启发，并且引入了安全区域、不探索危险区域、学习反向进程等策略进行训练。

- (3): 本论文的研究方法是首先建立安全区域，并且开发一种策略来探索这些区域，以及在不探索危险区域的前提下了解这些区域的信息，并将处理的重点转移到逆反向进程的经验数据上，从而实现效率的提高和提高任务成功率。

- (4): 论文使用所提出的方法完成了多个复杂任务的模拟试验，并在4个方块的叠放任务中将成功率从13％提高到100％，在创建四个方块组成的一排中将成功率从13％提高到99％，在对抗模式玩具的清除任务中将成功率从84％提高到95％。行动次数的效率通常提高30％或以上，训练时间仅为1-20 k个太阳活动。此外，该论文还成功地演示了从模拟情况到真实情况的直接迁移。这些结果支持了本文提出的方法的有效性和可行性。
7. Methods: 

- (1): 本研究针对实现复杂多步骤视觉任务的效率和准确性方面，提出了一种新的正强化（Positive Conditioning）训练方法，引入了安全区域、不探索危险区域、学习反向进程等策略进行训练。
 
- (2): 本文的研究方法是首先建立安全区域，并且开发一种策略在不探索危险区域的前提下了解这些区域的信息，在逆反向进程的经验数据上进行重点处理，提高效率和任务成功率。同时，针对奖励挖掘，提出了奖励修正的方法，通过引入 Block Approach、Situation Removal、SPOT-Q Learning 和 Masked Softmax 等算法，提高学习效率和训练安全性。

- (3): 本文首先在模拟试验中使用 SPOT 框架完成多个复杂任务的组装、堆叠和清理等测试，并在多项任务中大幅度提高成功率和行动效率，尤其是在实现四个方块叠放任务的成功率从 13% 提高到 100%，创建四个方块组成的一排中成功率从 13% 提高到 99%，在对抗模式玩具的清除任务中成功率从84%提高到95%。这些结果证明了 SPOT 框架具有良好的可行性和有效性。随后，本文在真实机器人上对所提出的 SPOT 算法进行验证，并取得了较好





8. Conclusion: 

- (1): 本研究对于实现多步骤复杂视觉任务具有重要的实际意义，其方法能够提高任务成功率和效率，同时具有良好的迁移性，可直接应用于真实机器人的操作中。

- (2): 创新点：文章提出了正强化训练方法和SPOT框架，引入了安全区域、奖励修正等策略，具有提高训练效率的优点。性能：文章通过模拟试验和真实操作验证了提出方法的有效性和可行性，同时成功率和效率等指标有较大程度的提升。工作量：文章对于算法的实现和验证工作较为细致，但是在奖励函数挖掘方面，需要更精细的设计和参数调整。




