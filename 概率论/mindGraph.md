## 各种信息
* 期末考可以带计算器
* 期末考可能从课本上摘题目
* 期末考一共**7道大题**，概率论部分**4-5题**，数理统计部分**2-3题**，另外会有附加题
* 题目会偏应用，推导和纯计算相对少一些
* **MLE必考**
* **17章ppt的Confidence Intervals不考**

## 知识框架（根据考试范围）
* ### Intro to *Probability*
  * #### Set Operations between Events
    * ##### Union of events（和事件，并集）

    * ##### Intersection of events (积事件，交集)，EF = E ∩ F
        * ###### mutually exclusive events (互斥事件，交集为空集)

    * ##### Difference of events（差事件，就是一个集合自己减去自己和另一个集合的交集）

    * ##### Complement of event (逆事件，就是补集)

    * ##### 𝐴∪(𝐵∩𝐶) = (𝐴∪𝐵)∩(𝐴∪𝐶)

    * ##### 𝐴∩(𝐵∪𝐶) = (𝐴∩𝐵)∪(𝐴∩𝐶)

    * ##### 德摩根律，记忆：*反*可以作用于每个集合和交并符号，也可以整体提到最上方（没思路就想想能不能用这个公式）

    * ##### 𝑃(𝐸∪𝐹) =𝑃(𝐸) + 𝑃(𝐹) − 𝑃(𝐸𝐹)

  * #### Permutations（排列） and Combinations（组合）
    * ##### 基本计算公式

  * #### Conditional Probability (条件概率)
    * ##### P(E|F) = P(EF) / P(F)
  
  * #### Law of Total Probability (全概率公式)

  * #### Bayes’ Formula（贝叶斯公式）

  * #### Independence of events（独立事件）: 𝑃(𝐸𝐹) = 𝑃(𝐸)𝑃(𝐹)
    * ##### If 𝐸 and 𝐹 are independent, then: P(E|F) = P(E) = P(E|F')

  * #### Mutually exclusive events（互斥事件）: E ∩ F = ∅

* ### (Multi-dimensional) R.V.（多维随机变量）
  * #### discrete random variables（离散型随机变量）
    * ##### PMF，probability mass function
      其实就是概率分布

    * ##### Bernoulli distribution (0-1分布)

    * ##### Binomial distribution (二项分布)
      𝑋~𝑏(𝑛,𝑝) or 𝑋~Bin(𝑛,𝑝)

    * ##### Poisson distribution (泊松分布),
      * 𝑋~𝜋(𝜆)
      * λ = np（和二项分布的联系）

    * ##### CDF，Cumulative Distribution Functions
      其实就是概率的累积，最后和为一

  * #### Continuous Random Variables（连续型随机变量）
    * ##### PDF，probability density function
      * 积分即可得到对应的CDF
      * CDF求导即可得到对应的PDF
      * 对于连续型随机变量来说，具体某一点的概率是0
    
    * ##### Uniform distribution (均匀分布)
      𝑋~𝑈(𝑎,𝑏)

    * ##### Exponential distribution (指数分布)
      * 𝑋~exp(𝜃)
      * θ = 1 / λ（指数分布和泊松分布的联系）


* ### *Statistics* of R.V.（随机变量的统计量）



* ### Related to *C.L.T.*



* ### *Parameter* Estimation