# Small Problems I've Pondered

This repo can be interpreted as math/ stats/ econ blog if you will. Folders correspond to problems, ideas, or topics.

### Hot-Hand:

Suppose you flip a fair coin $N$ times to produce a sequence of "H" and "T". You look at the coin flips that are preceded by $k < N$ straight "H". Do you expect the fraction of these flips that are "H" to be bigger than, less than, or equal to $0.5$? The answer is less than $0.5$.

### Ménage Problem: 

How many ways can $n$ couples sit around a circular table of $2n$ seats so that no two partners sit side-by-side? How many ways can $n$ couples sit around a circular table of $2n$ seats such that $k$ couples sit together and the remaining couples don't?

### Shrinkage Estimators:

Suppose you observe $N$ iid samples $X_1,...,X_N$ from some distribution $X$ that has mean parameter $x$. Your sample average $\bar{X} := \frac{1}{N}\sum\limits_{i=1}^{N}X_i$ is a good estimate of $x$ in the sense that it's unbiased. But, suppose you also have some prior information saying that $x_0$ should be a good estimate for $x$. How can you combine these two pieces of information to come up with an estimator for $x$ that's "better" than $\bar{X}$?

### Interpreting Winning Percentage:

Suppose that player $A$ and player $B$ will play a tennis match. Each player has played "many" games this season and had the same schedule: Player $A$ won $80$\% of his matches and meanwhile player $B$ has won $50$\% of his matches. What is the probability that player $A$ beats player $B$?

### Unbalanced Costs (joint with a friend):

Suppose you have a classification problem from some characteristic set $X \in \mathcal{X}$ to some class set $Y \in \mathcal{Y}$. The classification problem is interesting in the sense that certain errors in classification are more costly than others. For example, suppose that you're classifying individuals into sick or not sick-- labeling someone as sick when they're not sick is less bad than the opposite mistake. In this example, one should have a relatively low threshold for classifying someone as sick. How do you generally find such a classification threshold and how do you train the classifier?
