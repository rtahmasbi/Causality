# Causality



# Definitions

suppose you know that carrying a lighter $A$ has no causal effect (causative or preventive) on anyone’s risk of lung cancer $Y$, i.e., $Pr[Y^{a=1} = 1] = Pr[Y^{a=0} = 1], and that cigarette smoking $L$ has a causal effect on both carrying a lighter $A$ and lung cancer $Y$. The causal diagram bellow is the graphical translation of this knowledge.

<p align="center"><img src="pics/causality1.png" width="250"></p>

The lack of an arrow between $A$ and $Y$ indicates that carrying a lighter does not have a causal effect on lung cancer; $L$ is depicted as a common cause of $A$ and $L$.

## collider

Suppose you know that certain genetic haplotype $A$ has no causal effect on anyone’s risk of becoming a cigarette smoker $Y$, i.e., $Pr[Y^{a=1} = 1] = Pr[Y^{a=0} = 1], and that both the haplotype $A$ and cigarette smoking $Y$ have a causal effect on the risk of heart disease $L$. The causal diagram bellow is the graphical translation of this knowledge.

<p align="center"><img src="pics/collider.png" width="250"></p>


The lack of an arrow between $A$ and $L$ indicates that the haplotype does not have a causal effect on cigarette smoking, and $L is depicted as a common effect of $A$ and $Y$. The common effect $L$ is referred to as a *collider* on the path $A \rightarrow L \leftarrow Y$ because two arrowheads collide on this node.


## Randomized experiments

## Observational studies



## Instrumental variables
The instrumental variable $z$ has the property that changes in
$z$ are associated with changes in $x$ but do not led to change in $y$ (aside from the indirect route via $x$). This leads to the following path diagram

<p align="center"><img src="pics/instrumental.png" width="250"></p>


which introduces a variable $z$ that is associated with $x$ but not $u$. It is still the case that $z$ and $y$ will be correlated, but the only source of such correlation is the indirect
path of $z$ being correlated with $x$ which in turn determines $y$.

### Examples of an Instrument

### Instrumental Variables Estimator



## counterfactual


## Causality and graphical models


## Causality and graphons


## Causality and mediators


# Casualty vs prediction
Casualty is identification, not prediction.
Predictive models can simply ignore the T variable during their learning process, while T is the most important factor.







# mediators vs moderators
A mediator variable explains the process through which two variables are related, while a moderator variable affects the strength and direction of that relationship.


https://psychdrop.com/2020/04/05/mediation-versus-moderation-whats-the-difference/


Mediators mediate the relationship between X and Y. This occurs by X affecting M leading to M affecting Y, which is called the indirect effect. The direct effect is the relationship between X and Y in the presence of a mediator. Mediation occurs when (1) there is a statistically significant indirect effect (2) the direct effect is smaller than the total effect.



Moderator variables modify the relationship between X and Y. They affect the strength and direction of the relationship between X and Y. That means that X‘s effect on Y can change depending on the moderator.



# mediator vs confounder
A confounder is a third variable that affects variables of interest and makes them seem related when they are not. In contrast, a mediator is the mechanism of a relationship between two variables: it explains the process by which they are related.


Confounders are often demographic variables such as age, gender, and race that typically cannot be changed in an experimental design. Mediators are by definition capable of being changed and are often selected based on malleability. Suppressor variables may or may not be malleable.


# Mediating Variable Examples
According to research and data, the mortality rate of developed countries is lower than in developing countries because of advanced healthcare facilities. So, here, developed countries are the independent variable, the mortality rate is the dependent variable, and the mediator would be better healthcare facilities that navigate the relationship between both.

Being a developed country cannot influence its mortality rate directly. But after introducing the mediator here, which is better health care facilities, we can see an obvious effect of being a developed country and having a low mortality rate.


https://www.statisticshowto.com/mediator-variable/



# Causality and Recommendation system



# Reference
## Books
Causal Inference: What If, Miguel A. Hernán, James M. Robins, December 31, 2020
https://www.hsph.harvard.edu/miguel-hernan/causal-inference-book/

<img src="pics/Causal Inference What If.png" width="400">






# key people
Miguel Hernan, Kolokotrones Professor of Biostatistics and Epidemiology at Harvard and Broad Institute
https://www.hsph.harvard.edu/profile/miguel-hernan/





## videos
https://www.youtube.com/watch?v=gRkUhg9Wb-I&ab_channel=MITOpenCourseWare






#END
