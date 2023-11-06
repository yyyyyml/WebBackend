## 文献总结




### 基本信息
1. Title: Evaluating the Impact of Fine-scale Burstiness on the Elasticity of Cloud Applications (评估细粒度突发性对云应用弹性的影响)
2. Authors: Sadeka Islam, Srikumar Venugopal, Anna Liu
3. Affiliation: None
4. Keywords: Cloud Computing, Elasticity, Burstiness
5. Urls: [Paper](https://dl.acm.org/citation.cfm?id=2611820) (No Github code available)

### 简要总结      
6. Summary: 
- (1): 这篇文章主要研究云应用弹性中的细粒度突发性对弹性的影响。
- (2): 过去的方法未考虑到细粒度突发性对弹性的潜在危害，这篇文章提供了一种新的对细粒度突发性进行建模的方法。
- (3): 本文介绍了一种模型工作负载中细粒度突发性的方法，并通过实验案例进行研究和分析。
- (4): 本文研究表明，细粒度突发性对云应用的弹性有负面影响，并对云平台资源的自适应扩展提供了实证支持。
### 方法
7. Methods: 

- (1): 本文的方法针对具有细粒度波动的工作负载进行建模。作者假设工作负载由两个组成部分构成：确定性趋势和高度可变的噪声振荡。作者使用形状函数和规律性函数来描述确定性趋势和噪声振荡随时间的演变，并利用这些模板函数重现工作负载的原型。

- (2): 该方法中的细粒度突发性是通过多分数高斯噪声（mGn）进行合成。mGn是一种非平稳且随时间变化的分形高斯噪声，通过将常数Holder指数h泛化为一个时变的Holder函数h(t)来模拟真实世界现象的波动行为。

- (3): 方法的核心步骤包括：计算点点规律性、合成细粒度突发性、趋势构建和叠加。通过计算噪声振荡的Holder指数，使用cubic spline插值得到插值的Holder函数。然后，在根据Holder函数参数化的mGn过程中采样每个时间点的特定突发性。最后，使用形状函数和样本内插法构建确定性趋势，并通过叠加将细粒度突发性与趋势相结合。





### 详细总结
8. Conclusion: 

- (1): 重要性：该研究的重要性在于提供了对云应用弹性中细粒度突发性影响的深入理解。细粒度突发性是Web请求到达过程的固有特征，在云计算中具有普遍存在的实际意义。

- (2): 创新点：本文在创新点方面表现出色。通过提出一种新的细粒度突发性模拟方法，作者成功地模拟了工作负载中的细粒度突发性，使其能够与原始到达过程的事实相吻合。这为进一步研究云应用弹性提供了有力支持。

- (3): 性能：文章的性能方面值得称赞。通过实验案例在AWS云中验证了该方法的有效性，并探索了其对具有细粒度突发性工作负载的弹性行为。这些实证结果有助于我们更好地理解云平台资源的自适应扩展能力。

- (4): 工作量：文章在工作量方面进行了充分的研究和分析。通过使用形状函数和规律性函数来描述确定性趋势和噪声振荡，以及使用多分数高斯噪声合成细粒度突发性，作者提供了一种对细粒度突发性建模的详细方法。

根据以上优点和分析，本研究为深入理解细粒度突发性对云应用弹性的影响提供了新的视角和实证支持，同时为云平台资源的自适应扩展提供了有益的启示。然而，该研究没有提供开源代码，这可能限制了其他研究人员的进一步研究和应用。



