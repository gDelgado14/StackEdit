# EC450 Midterm 1 Study Guide

Note that this midterm covers **a closed economy**.

We build up a simple macro-economy model. The model is called the 3-equation model b/c there are 3 core elements.

1. The Demand Side (CH1)
2. The Supply Side (CH2)
3. The policy maker (CH3)

## CH 1: The Demand Side

Here we will build models that help analyze the spending decisions of households, firms, and the government. 

###Aggregate Demand

Aggregate demand is **real** expenditure on goods and services produced in the home economy. 

We use $y^D$ to denote Real Aggregate Demand.

Although this Aggregate Demand model assumes a closed economy, the demand side includes foreign spending on home goods and services (exports - X), and domestic spending on foreign goods and services (imports - M). 

For an open open economy
$$AD = y^D = C + I + G + (X-M)$$

<div id="goods"></div>

for a closed economy
$$AD = y^D = C + I + G$$

* $C$ : Household spending on goods and services
	*  Both on durable and non-durable products
* $I$ : Firms' investment decisions
	* Expenditure on capital goods
	* Machinery
	* equipment
	* [Consumers'] **new** houses / other buildings
* $G$ : Government spending on goods and services
	* includes public sector wages  
* $(X-M)$ : net exports

Fluctuations in AD affect unemployment and inflation.

#####**AD and Government Policy**
Monetary and Fiscal policy work by influencing different elements on the demand side. 

**Monetary Policy** seeks to stabilize aggregate demand by changing interest rates, which affect the investment decisions of firms and the purchase of durable goods (i.e. new cars and houses by households). Higher interest rates decrease spending by increasing the cost of financing investment projects. 

Monetary policy also has *indirect effects* because the interest rate affects incentives to save (higher i, means greater return on saving) and therefore shifts spending decisions **over time**. 

**Fiscal Policy** functions through changes in Government Spending; $G$. Therefore, fiscal policy affects AD *directly*. 

Fiscal policy can also be used to affect demand indirectly through its influence on household incomes and through that channel, on household spending. In other words, vis a vis taxing. 

$$T = taxes$$

Note that taxes are net of transfers. 

Transfers are:

* pensions
* social security payments
* disability benefits
* unemployment benefits 

#### Facts about the demand side and Business Cycles

shares of GDP vary from country to country. 

**National Accounts**
The national accounts are used to measure the output of an economy. The most commonly used measure for calculating national output is GDP. Note that GDP can be measured in three different ways: 

---
1 - *The Expenditure Method:* 

Open Economy
$$y = C + I + G + (X - M)$$

Closed Econ
$$y = C + I + G$$

This is the total expenditure on the economy's output of goods and services. 

A note on consumer investments:
**only housing is considered an investment in national accounts**. Cars, furniture, and all other durable goods are treated in the national accounts as consumption.

$G$ does not include government expenditure on transfers (transfers get spent by consumers, and that gets accounted for as $C$).

The expenditure method **only includes final goods**. The only purchases that are counted in GDP are when the firm sells the finished goods to the consumer (avoids double counting). 

---
2 - *The Value Added Method:*

Measures GDP as the value added created in all sectors of the economy.

y = value of output sold - costs of raw materials and intermediate goods
y = net revenue

--- 
3 - *The Income Method:*

Measures GDP as the total income of all agents in the economy. 

y = salaries of workers + profits of the owners of the capital

Note that total income in the economy = total expenditure. What is expenditure for the buyer is income to the seller. 

---

**Relative Volatility**
blah blah blah

**Growth and cycles**
blah blah blah

###The IS Curve
 
The IS curve represents the demand side of a macro-economy. 

Investment = Savings, hence the name. 

This models the goods market. 

####Aggregate Demand in the private sector
<div id="factors"></div>
The level of AD will be affected by current income and by the **following factors**. 

1. *Expectations about the future:* The plans of firms to invest in new equipment and premises depend on their expectations of future post-tax profits. Households will revise upward their estimate of how much they can spend each period if they have new info that leads them to expect their income to grow more strongly. The greater the uncertainty (i.e. unemployment rate increase) the more saving.
2. *The extent of credit constraints:* blahh 
3. *The Interest rate:* blahh 

####The IS Curve

Shows the combinations of the interest rate and output at which aggregate spending in the economy is equal to output. 

![The IS Curve](http://giorgiodelgado.ca/downloads/i-disapprove-face-emoticon-meme-thumbnail.jpg)

###### The IS curve - the effects of changes in optimism and economic policy

Changes in profit / income growth expectations, uncertainty ad the value of collateral all shift the IS curve (exogenous). i.e. pessimistic profit expectations --> firms postpone investment --> IS shifts left. The result is lower investment spending at any interest rate. See figure 1.4. 

To get back to a previous level of output, the **central bank** must now lower its interest rate to encourage more investment at this lower level of expected profits. i.e. the costs to borrow are lowered. 

Alternatively, the government (as opposed to the central bank) could launch a major expenditure programme. This would *shift* the IS to the right (endogenous) - at a given $i$, the gov purchases a larger amount of goods and services. 


###Modelling The Demand Side (IS)

The closed economy IS curve splits demand into its three component parts (Consumption, investment, and government spending). 

We assume that the supply of output adjusts to meet the demand for the goods, services, and labour. 

We include the [above 3 factors](#factors) as additional determinants of aggregate spending to modify the IS equation. 

####Goods Market Equilibrium

The aggregate - or economy-wide - demand for goods and services consists of ([as mentioned before](#goods)):

* Consumption
* Investment
* Government Spending


#####**Goods Market Model**

Recall in a closed economy, AD is:

$$y^D = C + I + G$$

All variables are in **real terms** (aka constant price terms). 

*Equilibrium in the goods market requires that planned real expenditure on goods and services ($y^D$) is equal to real output.*

$$y^D = y$$

$y$ is output, but it's also income (they are one and the same). 


#####**Breaking Down Consumption**

We assume aggregate consumption is a [linear] function of after-tax or disposable aggregate income. 

$$C = c_0 + c_1(y-T)$$

where $T$ is total taxes net of transfers. 

But this is not that useful for us. We make an additional assumption that taxes are a fixed proportion of income. i.e. $T = ty$ where $ 0 < t < 1$. Thus we have the **Keynesian consumption function**: 

$$C = c_0 + c_1(1-t)y$$

$c_0$ : Autonomous consumption
$c_1(y-T)$ : spending of disposable income. 
$c_1$ : <span id="mpc">**Marginal Propensity to Consume**</span>. Shows the change in consumption as the result of a change in post-tax or disposable income. 

$$MPC \equiv \frac{\Delta C}{\Delta y^{disp}} = c_1 $$

Where $$y^{disp} = (1-t)y$$

---

In this model of consumption, savings is $S = y - C$ and adds to one's assets. $y$ is the amount that can be consumed without reducing one's assets.
<div id="mps"></div>
**Marginal propensity to save** is $s_1$.
$$s_1 + c_1 = 1$$
> disposable income is either saved or spent

where $ 0 < c_1 < 1$. 

---

####The Multiplier

Substituting the consumption function into the equation for aggregate demand ... 

Expanding
$$y^D = C + I + G$$
to
$$y^D = c_0 + c_1(1-t)y + I + G$$

We draw this with aggregate demand on the y-axis and output on the x-axis.









![The IS Curve](http://giorgiodelgado.ca/downloads/i-disapprove-face-emoticon-meme-thumbnail.jpg)


<br>



Intercept: $I + G + c_0$ 
Slope: $c_1(1-t)$ where 0 < slope < 1

The goods market equilibrium condition is just a 45$^\circ$ line (at every point on this line, $y = y_D$). This line does not move ever.

The intersection shows the level of output where planned real expenditure on goods (and services) is exactly equal to the level of goods being **supplied** in the economy (one of the assumptions we made). 

--- 
<div id="action"></div>
**The Model In Action**

a shift in $y_d$ has two components:

######Let's say $y_d$ increases.

1. The initial change is matched by a corresponding supply increase. $\therefore y = y_d$. Point *C*.
2. The increase in output creates jobs / income which some portion (**not all**)  is spent and you get a recursively (go back to step one) smaller increase in output
	*  this is the multiplier in action ... which takes you to point *Z*
	
######...vice versa for negative changes to $y_d$

---

if we substitute $y$ into the aggregate demand equation ... 

Compressing 
$$y^D = C + I + G$$
or
$$y^D = c_0 + c_1(1-t)y + I + G$$
to
$$y^D = y$$

we can now define equilibrium output in terms of the **exogenous variables** (only the axis' variables are endogenous).

$$c_0 + c_1(1-t)y + I + G = y$$

isolate for $y$ to get the level of equilibrium output ...

$$y = \underbrace{\frac{1}{1 - c_1(1-t)}}_\text{multiplier}
\underbrace{(c_0 + I + G)}_\text{autonomous demand}$$ 

In a simple model (one that excludes forward-looking behaviour in order to account for savings), the multiplier is always $> 1$.

This just says the same thing [the example says](#action) ... i.e. a 1% change in autonomous demand will [in this simpler model] create a $> 1$% in $y$.

This is the **short run** multiplier.

---

$$\Delta y =  \underbrace{\frac{1}{1 - c_1(1-t)}}_\text{multiplier} \Delta \ell$$

Where $\ell$ is any exogenous variable ($c_0$ or $I$ or $G$ in our model, for example). *Assuming ceteris paribus change*.

---

The larger the multiplier: 

* The larger is the rightward shift of the IS curve associated with any given amount of additional gov spending
* The flatter is the IS curve, since with a larger multiplier, a give cut in the interest rate has a larger effect on output. 

---
###The Paradox of Thrift
#booogagoagoa


###The IS Curve

Recall: The IS curve represents the demand side of the economy. Good way to analyze monetary / fiscal policy. IS curve demonstrates the relationship between output and $r$ at which the goods market is in equilibrium. 

**Derivation**:

Recall the **Fisher equation**...
$$r = i - \pi^E$$

######actual photo of [Irving Fisher](http://josephdenne.com/foundthings/its-a-fish.jpg), Circa 1912.

This just says that the real interest rate is the nominal rate adjusted for **expected** inflation. 

> $r$ is the true cost of borrowing and true return on saving

This is the rate we'll use for the IS curve and the Investment equation.

In this model, consumption is independent of interest rates. 

---
Now, $I$ is no longer just given...

$$I = a_0 - a_1r$$ 

where $a_0$ and $a_1$ are constants. 

$a_0$ is expected future post-tax profits.

--- 
now the actual derivation ...

$$y = \underbrace{\frac{1}{1 - c_1(1-t)}}_\text{multiplier}
(c_0 + I + G)$$ 

######note that the rightmost part is no longer autonomous b/c of I being endogenous.
... expand I

$$y = \underbrace{\frac{1}{1 - c_1(1-t)}}_\text{multiplier}
(c_0 + (a_0 - a_1r)+ G)$$ 

... let multiplier = $k$

$$y = k(c_0 + (a_0 - a_1r)+ G)$$ 

... do some magic

$$y = k(c_0 + a_0 + G) - ka_1r$$ 

... let A = $k(c_0 + a_0 + G)$, and a = $ka_1$

$$y = A - ar$$ 

###### we have got ourselves an IS curve ladies and gents.

Thus, given $r$ equilibrium output, $y$, is found by multiplying autonomous variables by the multiplier, $k$, or **higher sensitivity of investment to the interest rate**, $a_1$, increases the effect of a change in the interest rate on output, making the IS curve flatter. 


![The IS Curve](http://giorgiodelgado.ca/downloads/i-disapprove-face-emoticon-meme-thumbnail.jpg)




#poopiieesss
The Permanent Income Hypothesis: 


### Definitions

* **GDP**: The national accounts measure of national output.
	* GDP captures only the value added created in the economy.  
* **[Marginal Propensity to Consume](#mpc)**:  
* **[Marginal Propensity to Save](#mps)**:  
