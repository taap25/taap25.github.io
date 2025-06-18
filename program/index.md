---
title: "TAAP25: Program"
---


# Workshop schedule

08:30 -- 09:00: _Registration_

09:00 -- 09:10 _Welcome_  
09:10 -- 09:50 **Sami Davies**: Fair Online Correlation Clustering (invited talk)  
09:50 -- 10:10 **Golnoosh Shahkarami**: Randomized Strategic Facility Location with Predictions

10:30 -- 11:00 _Coffee break_

11:00 -- 11:20 **Shikha Singh**: Designing Learned Data Structures via Prediction Decomposition  
11:20 -- 11:40 **Magnus Berg**: On the Complexity of Online Problems with Predictions  
11:40 -- 12:00 **Alison Hsiang-Hsuan Liu**: CAP: Consistencising the Analysis with Predictions in Online Algorithms  

12:00 -- 14:00 _Break_

14:00 -- 14:40 **Sebastian Forster**: TBA (invited talk)  
14:40 -- 15:00 **Joan Boyar**: Distributed Graph Algorithms with Predictions  

15:30 -- 16:00 _Coffee break_

16:00 -- 16:20 **Kim Thang Nguyen**: Online Covering with Multiple Experts  
16:20 -- 16:40 **Kim Thang Nguyen**: Online Primal-Dual Algorithm with Predictions for Non-Linear Packing and Covering Problems  
16:40 -- 17:30 _Open problem session_

# List of invited talks:

#### Sami Davies: Fair Online Correlation Clustering
Abstract: This talk will discuss the online correlation clustering problem with respect to two objectives: minimizing the total number of disagreements (ℓ1-norm), and minimizing the maximum number of disagreements adjacent to a vertex (ℓ∞ -norm).  Both problems have an Ω(n) lower bound on the competitive ratio, where n is the number of vertices.  To break through these lower bounds, we consider the online-with-a-sample model, a beyond-worst-case model in which the algorithm is given a small random sample of the graph upfront (a type pf prediction), and the remainder arrives adversarially online. We give the first non-trivial online algorithm for the ℓ∞ -norm objective in this model with a competitive ratio of O(log n), which we show is asymptotically tight. Further, we show that this algorithm is simultaneously O(1)-competitive for the ℓ1-norm objective; thus one can balance fairness and aggregate performance.

#### Sebastian Forster: TBA

# List of contributed talks:

#### Joan Boyar, Faith Ellen, and Kim S. Larsen:	Distributed Graph Algorithms with Predictions
Abstract: Algorithms with predictions have not previously been studied for distributed graph algorithms; we initiate such a study in synchronous message passing systems. Each node in the graph is given a prediction, which is some extra, possibly incorrect, information about the problem instance. We present a framework for evaluating distributed graph algorithms with predictions and transforming existing algorithms without predictions to effectively use predictions.

#### Eric Balkanski, Vasilis Gkatzelis and Golnoosh Shahkarami:	Randomized Strategic Facility Location with Predictions
Abstract: In the strategic facility location problem, a set of agents report their locations in a metric space and the goal is to use these reports to open a new facility, minimizing an aggregate distance measure from the agents to the facility. However, agents are strategic and may misreport their locations to influence the facility’s placement in their favor. The aim is to design truthful mechanisms, ensuring agents cannot gain by misreporting. This problem was recently revisited through the learning-augmented framework, aiming to move beyond worst-case analysis and design truthful mechanisms that are augmented with (machine-learned) predictions. The focus of this prior work was on mechanisms that are deterministic and augmented with a prediction regarding the optimal facility location. In this paper, we provide a deeper understanding of this problem by exploring the power of randomization as well as the impact of different types of predictions on the performance of truthful learning-augmented mechanisms. We study both the single-dimensional and the Euclidean case and provide upper and lower bounds regarding the achievable approximation of the optimal egalitarian social cost.

#### Magnus Berg, Joan Boyar, Lene M. Favrholdt and Kim S. Larsen:	On the Complexity of Online Problems with Predictions
Abstract: We initiate the development of a complexity theory for online problems with predictions, focusing on binary predictions. Based on the most generic hard online problem type, string guessing, we define a family of hierarchies of complexity classes (indexed by pairs of error measures) and develop notions of reductions, class membership, hardness, and completeness. Our framework contains all the tools one expects to find when working with complexity, and we illustrate our tools by analyzing problems with different characteristics.

#### Kim Thang Nguyen and Eniko Kevi:	Online Primal-Dual Algorithm with Predictions for Non-Linear Packing and Covering Problems
Abstract: Designing online algorithms with predictions is a new paradigm to go beyond the worst-case analysis by leveraging machine learning performance in predictions,
with several applications like scheduling, caching, clustering.
While in recent years, learning-augmented algorithms have been extensively studied, most of them deal with linear objective functions and covering problems.
Having been motivated by many non-linear (even non-convex) practical problems, we study and design competitive algorithms with predictions for non-linear objectives and
both packing and covering problems
through unified primal-dual frameworks. We show theoretical guarantees for these broad classes of problems, illustrate the applicability of our framework through various problems, such as load balancing, energy-related minimization, and submodular maximization/minimization, and provide experiments justifying the theoretical results. 

#### Kim Thang Nguyen and Enikö Kevi:	Online Covering with Multiple Experts
Abstract: Designing online algorithms with machine learning predictions is a recent approach beyond the worst-case paradigm for various practically relevant online problems like scheduling, caching, and clustering. While many previous learning-augmented algorithms focus on integrating the predictions of a single oracle, we study the design of online algorithms with multiple prediction sources (experts). To go beyond the performance guarantee of the popular static best expert in hindsight benchmark, we introduce a new benchmark that can be seen as the linear combination of predictions that change over time.
We present competitive algorithms in the new dynamic benchmark for 0-1 online covering problems with a performance guarantee of O(log K) if the objective is linear and O(ln(K)\frac{\lambda}{(1-\mu\ln(K))} if the objective is non-linear, where K is the number of experts and (\lambda, \mu) are parameters of the objective function.
Our approach gives a new perspective on combining multiple algorithms in an online manner using machine learning techniques.

#### Po-An Chen, Alison Hsiang-Hsuan Liu and Rick van de Bovenkamp:	CAP: Consistencising the Analysis with Predictions in Online Algorithms
Abstract: A recent model allows online algorithms to access predictions about future events, often generated by machine learning. However, predictions may be imperfect or even adversarial, so blindly trusting them can lead to poor performance. Ideally, we seek algorithms that are both consistent—performance improves with prediction quality and matches the optimum under perfect predictions—and robust—remaining competitive even when predictions are highly inaccurate or adversarial.  
We are interested in online algorithms whose analysis can be consistencised. For algorithms that involve a numerical parameter in their decision-making rules, we propose to consistencise them by introducing a range for this parameter. This range is defined by the algorithm’s trust parameter \lambda, and the algorithm only follows the prediction when it falls within this range.  
In the analysis, this parameter typically plays a key role. By extending it into a range, we embed both the prediction and the trust parameter into the existing analysis and demonstrate that the resulting mixed-strategy algorithm is consistent and robust. We apply this framework to two problems: online firefighting on trees (with at most two firefighters) and online busy time scheduling.

#### Samuel McCauley, Benjamin Moseley, Aidin Niaparast, Helia Niaparast and Shikha Singh:	Designing Learned Data Structures via Prediction Decomposition
Abstract: This talk will discuss the prediction decomposition technique that has been used in the design of recent learning-augmented data structures such as the data structure for maintaining incremental topological ordering and the list labeling problem. It is based on joint work with Samuel McCauley, Benjamin Moseley, Aidin Niaparast and Helia Niaparast. 
