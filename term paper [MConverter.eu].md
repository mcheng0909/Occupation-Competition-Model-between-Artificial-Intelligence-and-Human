**Occupation Competition Model between Artificial Intelligence and
Human**

Ming Cheng

Department of Applied Math, University of Washington

Amath 383: Introduction to Continuous Mathematical Modeling

Dr. Mark Kot

March 9, 2023

**Occupation Competition Model between Artificial Intelligence and
Human**

**Abstract**

The rapid development of artificial intelligence is a hot topic among
people, but many surveys have shown that the efficiency of AI causes
employees in many positions to face the risk of being replaced. To
further study the job competition relationship between humans and AI in
the future, I have established two models to each focus on the impact of
the interaction between humans and AI on their job competition and
predict who will win the job competition eventually. According to the
stability analysis and integration, the Lotka--Volterra competition
model shows that AI is likely to replace humans as the effect of AI on
humans increases, while another model shows that both humans and AI have
the chance to replace each other.

**Introduction**

Over the past few years, humanity has advanced technologically to an
unprecedented degree. With the popularization of general-propose
technology, a new technological revolution will happen. In November
2022, Chatgpt, an intelligent chat robot developed by OpenAI, became the
focus of everyone\'s attention. This artificial intelligence based on
the GPT-3 large-scale language model can allow people to improve work
efficiency in many fields (Aljanabi, 2023) and even beat skilled
employees in some fields.

Technological changes have also occurred many times in history. Since
applying new technologies may lead to job replacement and loss, many
resistances exist to popularizing new technologies. In 1589, William Lee
invented the stocking frame knitting machine and went to London to seek
patent protection, but the Queen rejected it because it might deprive
some people of employment opportunities (Acemoglu & Robinson, 2012). The
\"Luddite\" riots between 1811 and 1816 also demonstrate artificial fear
of technological change (Mantoux, 2015).

The transformation of AI is even more unprecedented than any
technological transformation in history. Although, The Industrial
Revolution created more new jobs while reducing jobs. Like Bruun says,
\"But AI challenges this model, as jobs across the whole employment
spectrum are simultaneously challenged by a technology that combines the
speed and efficiency of a machine with the creativity and agency of a
human\" (Bruun & Duka, 2018). On the other hand, Chat GTP has been able
to replace part of the work of junior doctors to a certain extent and
improve the quality of the discharge summary itself (Patel & Lam, 2023).
AI also has made outstanding achievements in agriculture. Using
mathematical models, AI has designed a very accurate and efficient drip
irrigation system for sustainable agriculture and the environment
(Klyushin & Tymoshenko, 2021). In addition to the outstanding
achievements of AI in these tasks that require many knowledge reserves,
it has even replaced workers in specific jobs. According to Wakefield,
China is investing heavily in robotic workforces. Apple and Samsung
supplier Foxconn has replaced 60,000 factory workers with robots
(Wakefield, 2016). As more data becomes available, AI will become more
competitive with the automatic improvement of capabilities. It
calculates that 47 percent of all jobs in the U.S. economy fall into the
high-risk category, jobs that could be easily automated within the next
two decades (Frey & Osbourne, 2017).

On the contrary, some articles show that there are still many potential
problems with AI. Castelvecchi pointed out in his article that neither
chat GTP nor Alpha Code can only perform limited tasks, and there is
still a long way to go to replace human software engineers
(Castelvecchi, 2022). In addition, OpenAI itself has admitted that there
may be misleading or biased content in ChatGTP\'s output, such as citing
non-existent article references or perpetuating sexist stereotypes. It
can also respond to harmful commands, such as generating malware (The
Lancet Digital Health, 2023).

Given the differences in the above research on the impact of AI on
humans from this introduction, I will build two mathematical models in
the Mathematical Model section and demonstrate the intervention and
competition between AI and humans using graphing and stability analysis
in the analysis section. Lastly, I will summarize my result and describe
the limitations of the models in the conclusion section.

**Mathematical Model**

The relationship between humans and AI may include various forms of
competition. To analyze the competitive relationship between AI and
human beings in future jobs more comprehensively, I will use two
different models to explain the competitive relationship between them.

***Interference Competition***

My model in this approach is to apply the standard Lotka--Volterra
interference competition model. We first assume that there are H human
positions and A artificial intelligence positions, and the number of
these positions increases logistically without heterogeneous
interference. With the continuous advancement of technology, AI will
also advance rapidly, which means that the competitiveness of AI will
continue to grow and the impact of AI on humans in the competition will
also increase. To parameterize this effect, we will use $\alpha_{HA}$
and $\alpha_{AH}$ to explain the strength of the effect of AI on humans
and of humans on AI,

$\ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \frac{dH}{dt} = \ \frac{r_{H}}{K_{H}}H\left( K_{H} - H - \ \alpha_{HA}A \right),$
(1)

$\ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \frac{dA}{dt} = \ \frac{r_{A}}{K_{A}}A\left( K_{A} - A - \ \alpha_{AH}H \right).$
(2)

I use the Lotka--Volterra competition model reflecting how humans and
artificial intelligence interact with each other without introducing
time, \"t\". In the next section, I will analyze how the equilibria
change in response to any changes in $\alpha_{HA}$.

***Limited Jobs Competition Model***

The Multistrain disease model inspires this model. Let\'s assume there
are A AI and H humans in the job market with U unemployed, E employee, I
idle AI and W working AI. And we also suppose the available or
unoccupied, J, increase logistically according to the equation

$\ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \frac{dJ}{dt} = \ \mu\ (K - J) = \ \mu K - \ \mu J.$
(3)

This equation shows linear growth at low job demand but exponentially
approaches the carrying capacity K at high job demand. This means the
number of unoccupied jobs is increasing at a rate of $\mu$ (K－J), that
is, proportional to the differences between job capacity and current
unoccupied jobs.

Since the unemployed AI and humans are looking for jobs, they start to
explore and connect with these unoccupied jobs. In this case, the
unoccupied jobs decrease at the rate of $\beta_{1}JU + \ \beta_{2}JI$,
where $\beta_{1}\ and\ \beta_{2}$ are the proportional coefficients.
Unoccupied jobs fell to the reason that unemployed humans and idle AI
got jobs and became employees and working AI. As the number of
unemployed humans and idle AI goes down, and the number of employees and
working AI goes up at the same rate, $\beta_{1}JU\ and\ \beta_{2}JI.$

According to the assumption above, we can produce the following model,

$\ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \frac{dJ}{dt} = \ \mu K - \ \beta_{1}JU - \ \beta_{2}JI - \ \mu J$,
(4)

$\ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \frac{dE}{dt} = \ \beta_{1}JU,\ \ \ \ \ \ \ \ $
(5)

$\ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \frac{dU}{dt} = \  - \ \beta_{1}JU,$
(6)

$\ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \frac{dW}{dt} = \ \ \beta_{2}JI,$
(7)

$\ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \frac{dI}{dt} = \  - \ \beta_{2}JI.$
(8)

**Analysis**

In this section, we will use the Jacobian matrix to analyze the
stability of the corresponding equilibrium points of each model and
predict the competitive relationship between AI and humans in future
jobs.

***Interference Competition Model Analysis***

As we know, the interference competition model has three or four
equilibriums depending on the interference coefficient. Since we only
focus on positive numbers of humans and AI, we will ignore the
equilibrium point at the origin and pay more attention to the boundary
and interior equilibrium.

To calculate the equilibrium points, we set equations (1) and (2) equal
to zero, solve for A\* and H\* respectively, and then combine the
corresponding values of A\* and H\* obtained by the two equations. The
four equilibriums we get are (0, 0), (0, K~A~), (K~H~, 0) and
($\frac{K_{H} - \alpha_{HA}K_{A}}{1 - \alpha_{AH}\alpha_{HA}},\ \frac{K_{A} - \alpha_{AH}K_{H}}{1 - \alpha_{AH}\alpha_{HA}})$.

Next, we will calculate the Jacobian matrix. In order to simplify the
calculation, we will call
$"\frac{r_{H}}{K_{H}}\left( K_{H} - H - \ \alpha_{HA}A \right)"$ from
equation (1) f and
$"\frac{r_{A}}{K_{A}}\left( K_{A} - A - \ \alpha_{AH}H \right)"$ from
equation(2) g. In this way, the Jacobian matrix we get is

$\ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ J = \ \begin{pmatrix}
f + H\frac{\partial f}{\partial H} & H\frac{\partial f}{\partial A} \\
A\frac{\partial f}{\partial H} & g + H\frac{\partial g}{\partial A}
\end{pmatrix}$, (9)

so that we can check the behavior at each positive equilibrium.

At (0, K~A~),

$\ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ J = \ \begin{pmatrix}
\frac{r_{H}}{K_{H}}\left( K_{H} - \ \alpha_{HA}K_{A} \right) & 0 \\
0 & - r_{A}
\end{pmatrix}.$ (10)

Since this is a diagonal matrix, we directly conclude that the
eigenvalues are

${\ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \lambda}_{1} = \ \frac{r_{H}}{K_{H}}\left( K_{H} - \ \alpha_{HA}K_{A} \right),\ {\ \lambda}_{2} = \  - r_{A}$.
(11)

We notice ${\ \lambda}_{2} = \  - r_{A}$ is always negative. However,
the sign of the other eigenvalue depends entirely on
$\left( K_{H} - \ \alpha_{HA}K_{A} \right).\ $We start to look at when
AI has less of an impact on humans, that is,
$\alpha_{HA} < \ \frac{K_{H}}{K_{A}}$ . Because
$K_{H} > \ \alpha_{HA}K_{A}$ in this case, then one of our eigenvalues
is positive and the other is negative, which means that (0, K~A~) is a
saddle point. This reflects that when AI was first introduced to work,
the interference coefficient to humans was small, and it could not
replace humans in completing various tasks. Nevertheless, with the
innovation of technology, $\alpha_{HA}$ is increasing.
When${\ \alpha}_{HA} > \ \frac{K_{H}}{K_{A}}$ , both eigenvalues become
negative, meaning the original saddle equilibrium becomes a stable node.
This implies that AI will win this competition. Because when the number
of working AI is greater than the number of employed humans initially,
and the number of employed human and AI will approach toward the stable
equilibrium at (0, K~A~), where the number of employed human is equal to
0, as shown in figure 1.

Another place we need to pay attention to is
${\ \alpha}_{HA} = \ \frac{K_{H}}{K_{A}}$, this is a bifurcation point
because it separates the stable and saddle parts of (0, K~A~), producing
a transcritical bifurcation. Similarly, a transcritical bifurcation with
bifurcation point at ${\ \alpha}_{AH} = \ \frac{K_{A}}{K_{H}}$. As shown
in Figure 2, when the human intervention coefficient on AI increases,
${\ \alpha}_{AH} > \ \frac{K_{A}}{K_{H}}$ . At this time, the increased
influence of humans will lead to the change of stability from unstable
to stable.

![图示 描述已自动生成](media/image1.jpg){width="2.0795264654418197in"
height="1.279708005249344in"}
![](media/image2.jpg){width="2.2810181539807526in"
height="1.398688757655293in"}

Figure 1 Figure 2

Additionally, we will focus on the internal equilibrium. For the
convenience of referring to this more complicated equilibrium, we will
call
($\frac{K_{H} - \alpha_{HA}K_{A}}{1 - \alpha_{AH}\alpha_{HA}},\ \frac{K_{A} - \alpha_{AH}K_{H}}{1 - \alpha_{AH}\alpha_{HA}})$
as (x, y), with x and y being both positive numbers. Notice that since x
and y are both positive, then the sign of
$K_{H} - \alpha_{HA}K_{A}\ $and $K_{A} - \alpha_{AH}K_{H}$ must be the
same, and this internal equilibrium only occurs when
${\ \alpha}_{AH} > \ \frac{K_{A}}{K_{H}},\ {\ \alpha}_{HA} > \ \frac{K_{H}}{K_{A}}$
, or
${\ \alpha}_{AH} < \ \frac{K_{A}}{K_{H}},\ {\ \alpha}_{HA} < \ \frac{K_{H}}{K_{A}}$.

Let\'s look at the Jacobian matrix at (x, y),

$\ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ J = \ \begin{pmatrix}
 - \frac{r_{H}}{K_{H}}x & - \frac{r_{H}}{K_{H}}\alpha_{AH}x \\
{- \frac{r_{A}}{K_{A}}\alpha}_{HA}y & - \frac{r_{A}}{K_{A}}y
\end{pmatrix}$. (12)

This matrix has the characteristic equation

${\ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \lambda}^{2} + (\frac{r_{H}}{K_{H}}x + \ $
$\frac{r_{A}}{K_{A}}y)\lambda + \ \frac{r_{A}}{K_{A}}\frac{r_{H}}{K_{H}}\left( 1 - \alpha_{AH}\alpha_{HA} \right)xy = 0,$
(13)

where q
=$\frac{r_{A}}{K_{A}}\frac{r_{H}}{K_{H}}\left( 1 - \alpha_{AH}\alpha_{HA} \right)xy$,
p = $(\frac{r_{H}}{K_{H}}x + \ $ $\frac{r_{A}}{K_{A}}y).$ From here, we
can clearly see that p is always negative and the sign of q depends on
1$- \alpha_{AH}\alpha_{HA}.\ $When it is less than 0, we have
${\ q\ is\ less\ than\ \ 0\ and\ \alpha}_{AH} > \ \frac{K_{A}}{K_{H}},\ {\ \alpha}_{HA} > \ \frac{K_{H}}{K_{A}}$,
then the interior equilibrium is a saddle-node in this case. This
reflects both humans and AI have great interference with each other, and
the advantage of either side\'s initial condition can wipe out the other
side from the competition. And the change of the interference
coefficient on either side will cause (x, y) to approach the boundary
equilibrium, and when the interference coefficient of any side begins to
less than $\frac{K_{H}}{K_{A}}\ or\ \ \frac{K_{A}}{K_{H}},\ $(x, y)
coincides with the boundary equilibrium, resulting only three
equilibriums .

On the contrary, if 1$- \alpha_{AH}\alpha_{HA} > 0$, we have
${\ \alpha}_{AH} < \ \frac{K_{A}}{K_{H}},\ {\ \alpha}_{HA} < \ \frac{K_{H}}{K_{A}},\ $and
q is greater than 0. In order to distinguish whether this is a node or a
focus, we need to justify whether $\frac{p^{2}}{4} - q$ it is greater
than 0. Using basic arithmetic, we get

$\frac{(\frac{r_{H}}{K_{H}}x + \ \ \frac{r_{A}}{K_{A}}y)^{2}}{4} - \frac{r_{A}}{K_{A}}\frac{r_{H}}{K_{H}}\left( 1 - \alpha_{AH}\alpha_{HA} \right)xy = \ \frac{(\frac{r_{H}}{K_{H}}x - \ \ \frac{r_{A}}{K_{A}}y)^{2} + \ \frac{r_{A}}{K_{A}}\frac{r_{H}}{K_{H}}\alpha_{AH}\alpha_{HA}xy}{4} > \ 0\ .$
(14)

This means that (x, y) is indeed a stable node. In this case, humans and
AI have less interference with each other, and the distribution of jobs
between AI and humans are likely to reach a balance point.

Therefore, 0 =$1 - \alpha_{AH}\alpha_{HA}$ is the critical bifurcation
point. The linear change in stability implies that (x, y) is also
transcritical bifurcation. These changes in the stability of the
equilibrium tell us that when the influence between humans and AI are
weak, the competition for jobs between humans and AI will reach a
harmonious balance. And when ${\ \alpha}_{AH}$ and/or ${\ \alpha}_{HA}$
more than $\frac{K_{A}}{K_{H}}\ \ $and /or $\frac{K_{H}}{K_{A}}$, humans
or AI will replace each other depending on the initial condition.

***Limited Jobs competition Model Analysis***

If we pay attention to the model we introduced earlier, we see that if
we add equation (5) and equation (6), we get $\frac{d}{dt}(E + U)$ = 0.
Intuitively, all unemployed and employed humans add up to the total
number of all human practitioners, H. Because its derivative is 0 in
terms of time, H is a constant. Therefore, we can get E by calculating
H - U. The same principle applies to equations (7) and (8). Finally, by
eliminating equations (6) and (8), we can get our final model

$\ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \frac{dJ}{dt} = \ \mu K - \ \beta_{1}JU - \ \beta_{2}JI - \ \mu J$,
(15)

$\ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \frac{dU}{dt} = \  - \ \beta_{1}JU,$
(16)

$\ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \frac{dI}{dt} = \  - \ \beta_{2}JI,$
(17)

By setting these three equations equal to 0, we get (K, 0, 0), which is
the only equilibrium of this system. If we calculate the Jacobian matrix
at this point, we obtain

$\ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ J = \ \begin{pmatrix}
 - \mu & - \beta_{1}K & - \beta_{2}K \\
0 & - \beta_{1}K & 0 \\
0 & 0 & - \beta_{2}K
\end{pmatrix}$ . (18)

Obviously, $- \mu,$ $- \beta_{1}K$ and $- \beta_{2}K$ are three negative
the eigenvalues of this upper triangular matrix, which means (K, 0, 0)
is a stable equilibrium.

Moreover, since we are interested in predicting the performance of AI
and humans in future jobs competition, we can only be concerned about
the model\'s behavior when \"t\" is enormous. From equation (3), we know
that the total number of unoccupied jobs is growing and gradually
approaching its carrying capacity at K. If we substitute K for J for t
large, we can get a linear model that predicts the distribution of jobs
in the future,

$\ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \frac{dJ}{dt} = - \ \beta_{1}KU - \ \beta_{2}KI$,
(19)

$\ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \frac{dU}{dt} = \  - \ \beta_{1}KU,$
(20)

$\ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \frac{dI}{dt} = \  - \ \beta_{2}KI.$
(21)

From this system of the differential equation, we obtain

$\ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \frac{dU}{dI} = \ \frac{\beta_{1}U}{\beta_{2}I}$.
(22)

By separating the variables and integrating them, we obtain

$\ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \frac{1}{\beta_{1}}\left( lnU(t) - lnU_{0} \right) = \ \frac{1}{\beta_{2}}\left( lnI(t) - lnI_{0} \right),$
(23)

so that

$\ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ M \equiv$
$\frac{1}{\beta_{1}}\ln U_{0} - \ \ \frac{1}{\beta_{2}}\ln I_{0}$. (24)

we can also rewrite this as

$\ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ \ I = \ e^{\frac{\beta_{2}}{\beta_{1}}}e^{U} - \ \beta_{2}M$.
(25)

To understand who wins the competition in the end, we need to compute
$e^{\frac{\beta_{2}}{\beta_{1}}}$ $\frac{1}{\beta_{2}}.\ $If M \>
$e^{\frac{\beta_{2}}{\beta_{1}}}$ $\frac{1}{\beta_{2}}$ , then the
number of people in the final career becomes 0, and human beings become
the winners of professional competitions. Otherwise, AI becomes the
winner. I will illustrate the corresponding graph in the next section
using specific parameters.

**Example**

***Example of Interference Competition Model***

To keep the example simple, we first assume that the job capacity of
both AI and humans is 1, and then we have $\frac{K_{A}}{K_{H}}\ \ $=
$\frac{K_{H}}{K_{A}}$=1. Secondly, we will mainly focus on the interior
equilibrium because the boundary equilibrium are constant points. In
addition, since we mainly focus on the impact of AI on humans, we regard
the impact coefficient of humans on AI as a constant and pay attention
to the change of this interior equilibrium as ${\ \alpha}_{HA}$
incresses.

We assume that humans have a minor influence coefficient on AI, then we
let ${\ \ \alpha}_{AH} =$`<!-- -->`{=html}0.6. We plot
($\frac{1 - \alpha_{HA}}{1 - 0.6\alpha_{HA}},\ \frac{1 - 0.6}{1 - 0.6\alpha_{HA}})$
in terms of${\ \ \alpha}_{HA}$. From Figure 3, we can see that if the
number of jobs for AI and humans is to remain positive, then
${\ \alpha}_{AH}$ and ${\ \alpha}_{HA}$ must be less than one. We can
also find that before it is less than 1, the stable internal equilibrium
approaches the equilibrium on the A-axis of the figure 1 as
$\frac{1 - \alpha_{HA}}{1 - 0.6\alpha_{HA}}\ $is moving toward 0. It
shows the influence of AI on human continues to increase, the available
jobs of human will gradually decrease, and AI will become the winner in
competition.

![](media/image3.png){width="1.4392530621172352in"
height="1.4235662729658793in"} ![图示
中度可信度描述已自动生成](media/image4.jpg){width="1.7441371391076115in"
height="1.4253094925634295in"}

Figure 3 Figure 4

However, what is more interesting is if we assume that both AI and
humans have a greater influence on each other, namely,
${\ \alpha}_{AH} > \ \frac{K_{A}}{K_{H}},\ {\ \alpha}_{HA} > \ \frac{K_{H}}{K_{A}}$.
We assume this time${\ \alpha}_{AH}$ = 1.6, then after we plot
($\frac{1 - \alpha_{HA}}{1 - 1.6\alpha_{HA}},\ \frac{1 - 1.6}{1 - 1.6\alpha_{HA}})$
in Figure 2, with the increase of AI's influence on humans, especially
when AI's influence on humans is greater than the impact of humans on
AI, the original unstable equilibrium approaches the H-axis of figure 2
as $\frac{1 - 1.6}{1 - 1.6\alpha_{HA}}\ $is moving toward 0, but it does
not overlap with the stable equilibrium on the original boundary. In
this case, humans may even become the winners of this competition of
jobs.

***Example of Limited Jobs Competition Model***

In this model, we are going to assume that idle AI gets jobs faster than
humans, then $\beta_{2} > \ \beta_{1}.\ $For example, we set
$\beta_{2}$=0.8 and $\beta_{1}$=0.5. According to the previous analysis,
we know M = $e^{\frac{\beta_{2}}{\beta_{1}}}$
$\frac{1}{\beta_{2}} = 6.1913$ is an essential value of M, so we will
pay attention to the cases where M is greater than and less than 6.
1913.

We first let M equal 10, and then equation (25) becomes

$I = \ e^{\frac{0.8}{0.5}}e^{U} - \ 0.8*10$,

shown as the blue line in the figure 5.

![图表
中度可信度描述已自动生成](media/image5.jpg){width="1.4743514873140857in"
height="1.3685761154855642in"}

Figure 5

At this time, we can see that this line intersects with U-axis with a
positive U value. In this case, idle AI no longer exists while there are
still human beings, so AI wins the competition in the case of M=10.

We now let M equal 3, and we have

$I = \ e^{\frac{0.8}{0.5}}e^{U} - \ 0.8*3$.

It is shown as the green line in the figure 5. Similarly, in the case of
M = 3, the unemployed humans will disappear, but there will still be
idle AI.

The red line in the figure 5 is the zero point of M for reference.
Nevertheless, this can also be regarded as a symbiotic line between AI
and humans. Then when M= 6. 1913, humans and AI share all jobs equally,
and neither humans nor AI will be unemployed.

**Conclusion**

My models attempt to predict the future competition between humans and
AI in jobs from the impact of AI on humans and from the two aspects of
AI and humans competing for a limited number of jobs. The first model
uses the change of $\alpha_{HA}\ $to reflect the bifurcation of each
equilibrium point. The result implies that AI\'s impact on humans will
become increasingly considerable. The original symbiotic relationship
between humans and AI may eventually become AI that replaces humans when
the mutual influence between humans and AI is small initially. This
result is consistent with some studies, from which automation will lead
to 15% unemployment in 2023, and it will continue to climb to 30%
(Manyika & Sneader, 2018). However, this model also tells us that AI
will not necessarily replace humans if the mutual influence between
humans and AI is significant initially.

One limitation of the analysis is that I regard the influence
coefficient of AI on humans as an independent variable in the stability
analysis to keep it simple. The model will be more accurate if \"t\" can
be introduced in the original differential system. Another more
realistic way is instead of plotting a 2-dimensional graph, we can plot
a 3-dimensional bifurcation diagram with two independent variables
${\ \alpha}_{AH}$ and ${\ \alpha}_{HA}.$

In the second model, we mainly predict that after many years, the
unemployed, either human or AI, can be eliminated when they jointly
compete for a limited number of jobs. The results tell us that the
winner of future competitions depends entirely on
$e^{\frac{\beta_{2}}{\beta_{1}}}$ $\frac{1}{\beta_{2}}.$ Compared with
the first model, this model shows a greater possibility that humans will
defeat AI. However, to keep the model simple, I ignore that there fired
humans and AI. So if we consider these elements, the model can be more
realistic.

**Acknowledgment**

Words cannot express my gratitude to my professor for his invaluable
patience and help. I could not have undertaken this paper without my
professor, who generously provided knowledge and expertise.

References

Acemoglu, D., & Robinson, J. A. (2012). *Why nations fail: The origins
of power, prosperity, and poverty*. Crown Publishers. New York.

Aljanabi, M., Ghazi, M., Ali, A. H., Abed, S. A., & ChatGpt, (2023,
January 18). ChatGpt: Open Possibilities. *Iraqi Journal For Computer
Science and Mathematics*, 4(1), 62-64.
https://journal.esj.edu.iq/index.php/IJCM/article/view/539

Bruun, E. & Duka, A. (2018, November). Artificial Intelligence, Jobs and
the Future of Work: Racing with the Machines. *Basic Income Studies*,
13(2), 1-15.
https://www-degruyter-com.offcampus.lib.washington.edu/document/doi/10.1515/bis-2018-0018/html#APA

Castelvecchi, D. (2022). *Are ChatGPT and AlphaCode going to replace
programmers?* Nature.
https://www-nature-com.offcampus.lib.washington.edu/articles/d41586-022-04383-z

Frey, C. B., & Osbourne, M. A. (2017, January). The future of
employment: How susceptible are jobs to computerisation? *Technological
Forecasting and Social Change*, 114(1), 254-280.
https://www-sciencedirect-com.offcampus.lib.washington.edu/science/article/abs/pii/S0040162516302244?via%3Dihub

Klyushin, D., & Tymoshenko, A. (2021). Optimization of Drip Irrigation
Systems Using Artificial Intelligence Methods for Sustainable
Agriculture and Environment. In *Artificial Intelligence for Sustainable
Development: Theory, Practice and Future Applications* (pp. 3-17)*.*
Springer, Cham. Switzerlan.

The Lancet Digital Health. (2023, February 6). Chatgpt: Friend or foe?
*The Lancet. Digital Health*., 5(3), 1.
https://www.thelancet.com/journals/landig/article/PIIS2589-7500(23)00023-7/fulltext

Mantoux, P. (2015). *The Industrial Revolution in the eighteenth
century: An outline of the beginnings of the modern factory system in
England* (T. S. Ashton, Ed. M. Vernon, Trans.)*.* Routledge. London.
(Original work published 1928)

Manyika, J., & Sneader, K. (2018, June 1). *AI, Automation, and the
future of work: Ten things to solve for.* McKinsey & Company.
https://www.mckinsey.com/featured-insights/future-of-work/ai-automation-and-the-future-of-work-ten-things-to-solve-for

Patel, S. B., & Lam, K. (2023, February 6). Chatgpt: The future of
discharge summaries? *The Lancet Digital Health*, 5(3), 1-2.
https://www.thelancet.com/journals/landig/article/PIIS2589-7500(23)00021-3/fulltext

Wakefield, J. (2016, May 25). *Foxconn replaces \'60,000 factory workers
with robots\'*. BBC News. https://www.bbc.com/news/technology-36376966
