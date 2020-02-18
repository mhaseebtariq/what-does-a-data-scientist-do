
## What does a Data Scientist do?

>Doctor does "treatment"<br>
Teacher does "teaching"<br>
Constructor does "construction"<br>
Marketeer does "marketing"<br>
And the politician does "nothing nothing nothing"<br>
But there's one job (title)<br>
That no one knows<br>
What does the data scientist do?<br>
Ring-ding-ding-ding-dingeringeding!<br>
Gering-AI???-ding-Analytics???-dingeringeding!<br>
Gering-Software-Engineering???-ding-ding-dingeringeding!<br>
What the data scientist do?<br>
Wa-pa-pa-pa-pa-pa-pow!<br>
Wa-Databases???-pa-pa-pa-pa-pow!<br>
Wa-pa-pa-pa-Research???-pa-pow!<br>
What the data scientist do?<br>

#### Short(est) answer: A data scientist does "[models](#what-are-models)"
Of course, to answer this centuries old (the title was coined in 2008) question, we need more explanation. 
First, let's outline the core responsibilities of a data scientist:
1. [Designing](#model-design) models which could help in making better and/or faster decisions
    * Models built on or backed by <b>data</b>
2. Automating the [parameters estimation](#parameters-estimation) for the models
3. Making sure the [models can be updated](#updating-model), with new information, in the fastest; most friction-less way possible
4. [Explaining](#explaining-model); or building tools which could explain the models (or models output)
5. Building [monitoring](#monitoring-model) tools which could assist in improving/controlling the models output

## What are models
A model is a “representation” (or simplification) of a physical object; a process; a system; or a phenomenon. 
A representation is by definition not accurate, therefore, we have the aphorism:
>All models are wrong, but some are useful.

The <b>usefulness</b> of a model depends on the design; parameters; complexity; and assumptions made for the model. In different contexts/scenarios a model can become more or less useful.

### Model Design
Let's suppose our (imagined) newly-hired data scientist is working in an e-commerce company that sells electronic devices on their website. After talking with all the different stakeholders in the company; and doing some initial cost/feasibility analysis - she realises that operational forecasting is one of the most cricial areas where data science can save the company a lot of money. Currently the forecasting is done using some simple calculations. A business analyst looks at the sales of the last few weeks and estimates the expected number of sales for the future weeks using weighted averages. This estimate is then used by the warehouse planning manager to hire more or less temporary workers. 

#### Risks involved with bad forecast
* If the forecast turns out to be too high the warehouse manager ends up with too many workers who have no work to do, and therefore, the workers cost the company extra money
* On the other hand if the forecast is too low, the warehouse does not have enought workers and the customers do not get their packages delivered on time, therefore, there is the risk of loosing customers

#### Considerations for the model design
Given the context:
* Is it more important to make faster decisions or more accurate decisions?
   * As the forecast is going to be used for medium to long term planning it is not really important to make faster decisions, on the other hand, for a model used for making real-time decisions the preference might be made in favor of faster predictions
   * It will be irrational to rely entirely on the model forecast
   * The model forecast should be moderated by the domain specialist - operations analyst in this case
* Is it more important to make more accurate predictions or explainable predictions
   * A more complex model design might give a slight uplift in predictions accuracy but no (or little) explanation
   * On the other hand, a less complex model could explain the predictions really well, which could in return, help the operations analyst make much better (and informed) adjustments
* Is the model going to reduce FTEs
   * No, the model is only supposed to help the operations analyst make more accurate decisions. It might as well be the case that after employing the model, you need more analysts. Analysts who can interpret model outputs; build dahsboards/reporting tools for analysing differnet forecasts; maintain a collaborative feedback loop with the data scientists to help improve the model.
   * On the other hand an NLP (natural language processing) could be employed to build a bot for replying to genral customer services queries, this model could in return, reduce the load on the customer services.
* Which variables should be considered as good predictors for the forecast
* What might be a representative funtional form for the model

#### What is required from our data scientist to come up with a good model design
* Good communcation skills to understand the requirements and problem context
* An extensive vocabulary of models
* Knowledge in linear algebra
* Knowledge in statistics and probability theory

### Parameters Estimation
For our forecasting model the parameters are... [TODO]

### Updating Model
Every model expires... [TODO]

### Explaining Model
Sometimes explaing the model (or model output) is more important than model accuracy... [TODO]

### Monitoring Model
To make sure... [TODO]
