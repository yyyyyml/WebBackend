## 文献总结




### 基本信息
1. Title: System resource utilization analysis and prediction for cloud based applications under bursty workloads (云计算应用下的系统资源利用率分析和预测在突发工作负载下)
2. Authors: Jianwei Yin, Xingjian Lu, Hanwei Chen, Xinkui Zhao, Neal N. Xiong (尹建伟, 陆兴健, 陈寒威, 赵欣魁, Neal N. Xiong)
3. Affiliation: College of Computer Science and Technology, Zhejiang University (浙江大学计算机科学与技术学院)
4. Keywords: Burstiness, Workload generation, Fine-grained prediction, Index of dispersion for count (突发性、负载生成、细粒度预测、计数的离散度指标)
5. Urls: [Paper](https://www.sciencedirect.com/science/article/pii/S0020025514003761)

### 简要总结      
6. Summary:

(1): 本文的研究背景是云计算应用下的系统资源利用率分析和预测。研究者们意识到突发工作负载对资源分配和系统性能的重要影响，因此突发工作负载下的性能分析和预测对云计算应用至关重要。

(2): 过去的方法在突发工作负载下的性能分析和预测方面存在问题。没有准确有效的突发工作负载生成器，也缺乏细粒度的突发工作负载分析和预测方法。本文的方法能够解决这些问题，并有很好的动机。

(3): 本文提出了一种基于2-state Markovian Arrival Process (MAP2) 的突发工作负载生成器，并在此基础上提出了一种细粒度的性能分析方法，可以预测CPU利用率的概率密度函数。这些方法能够支持更好的资源分配决策和系统性能优化。

(4): 方法的实验验证了其准确性和有效性。通过与实际数据比较，实验结果表明新方法的性能优于现有方法。通过比较生成器产生的不同突发工作负载下的实际和预测的系统资源利用率，实验也证明了所提出的细粒度资源利用率预测方法的有效性和准确性。





### 详细总结
8. Conclusion: 

- (1):重要性：本文对云计算应用下的突发工作负载的系统资源利用率分析和预测进行了研究，对于确保系统性能和资源分配决策具有重要意义。

- (2):创新点: 本文的创新点主要体现在以下三个方面：

  - 突发工作负载生成器：提出了一种基于2-state Markovian Arrival Process (MAP2) 的突发工作负载生成器，可以产生符合实际情况的突发工作负载，解决了以往方法中突发工作负载生成器的准确性和有效性问题。
  - 细粒度性能分析方法：通过使用概率密度函数预测CPU利用率，提出了一种细粒度的性能分析方法，能够更准确地分析和预测突发工作负载下的系统资源利用率。
  - 实验结果验证：通过实验证明所提出的方法的准确性和有效性，并与现有方法进行比较，实验结果表明新方法的性能优于现有方法。

- (3):性能: 本文通过使用细粒度的性能分析方法，能够更准确地预测突发工作负载下的系统资源利用率。实验结果与实际数据对比显示，所提出的方法在性能方面表现出色，并与现有方法相比具有优势。

- (4):工作量: 本文中提出的方法需要对突发工作负载进行建模和分析，涉及到对系统资源利用率的预测和优化。因此，在实施该方法时需要一定的工作量来开发和测试相应的工具和算法。但通过实验结果的验证，所提出的方法对于提高系统资源利用率和性能优化是值得的工作量投入。



