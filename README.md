# Working-Memory-Demand-in-Social-Cognition
Estimate the demand of working memory in Social Cognition. This was created as a part of [Neuromatch Academy](https://neuromatch.io/academy/) Computational Neuroscience Summer School 2021.

### Final Abstract:
Humans are surrounded by a complex and dynamic social environment in which they need to influence or infer the actions, desires, and thoughts of others irrespective of their nature of participation. Successful interaction in the social environment may require some reminiscing, gathering and updating of mental attributes which are acquired in an ongoing experience is essential for social cognition (Spreng, 2013), which includes perception, interpretation, categorizing their actions, implicit intentions, and their mental states. (APA Dictionary of Psychology, 2020). We, as social agents, often need to “retrieve, maintain and manipulate social information” (Spreng, 2013) to be able to draw a myriad of conclusions about others. Previous studies have shown that social cognition requires working memory function (e.g., Carlson & Moses, 2001), which is a kind of a “temporary storage” of a live event, with which we can encode, hold, manipulate, and retrieve information for limited durations (Baddeley, 2003), However, to our knowledge, it is not yet clearly understood if social cognition demands high or low working memory. Therefore, by taking a neuroscientific perspective, we will try to estimate the demand of working memory in social cognition by looking into the common brain regions for both tasks. More specifically, we will examine if social cognition and working memory share common brain regions and would activations in those regions differ based on different levels of working memory demand. We hypothesize that activations in the common brain regions will vary for different working memory demands. To understand this, we will employ the Human Connectome Project dataset (HCP; Barch et al., 2013). We will operationalize the low working demand with 0-back working memory task and high working memory with the 2-back working memory task. Similarly, we will also use the task fMRI scans of healthy young adults in the HCP while they are performing a social cognition task (i.e., videos of interacting shapes vs. randomly moving shapes). We will then try to predict the behavioral outputs of the social cognition task from the time series fMRI data of common brain regions. To do this, we will build two models: In the first model, we will use the time-series data from common brain regions activated in 2-back and social cognition tasks as our input. Similarly,  in the second model, we will use the time-series data from common brain regions activated in 0-back and social cognition tasks as our input. We will try to predict the participants’ behavioral output in the social cognition task with each of the models. Finally, we will compare the accuracy of those models in terms of estimating the participants’ responses in the social cognition task. 

### Key scientific question:

If social cognition and working memory share common brain regions, would activations in those regions differ based on different levels of working memory demand? 

### What was our hypothesis?

Activations in the common brain regions will be different for different working memory demands.

### Proposed Modelling procedure:

Predicting behavioral outputs of social cognition task from the time series fMRI data of common brain regions.

Model 1: We’ll take the common brain regions activated in 2-back and social cognition tasks as our input. Then, we’ll try to predict the participants’ behavioral output in social cognition task. 

Model 2: We’ll take the common brain regions activated in 0-back and social cognition tasks as our input. Then, we’ll try to predict the participants’ behavioral output in social cognition task. 

We’ll compare the accuracy of those two models. 

### Our prediction based on our modelling:

If one model’s accuracy is higher than the other then we can infer that the brain regions corresponding to a more accurate model might be the better parameters. Hence, we may interpret this result as such: Social cognition task responses might be better estimated by high working memory demand if the model including the regions of high working memory demand as parameters provides higher accuracy (and vice versa). 

### Brief Description of dataset in use:
**The WU-Minn Human Connectome Project (HCP)** -

A broad overview: Objectives of HCP
- Generating maps of macro-connections within the human brain, portraying human brain function 

- Several imaging methods (e.g., MRI, EEG) and modalities (e.g., R-fMRI, T-fMRI), behavioral data (i.e., “testing outside of the scanner”, and genetic data 
360 brain parcels 

**insert image here!!**

### We employed two approaches for identifying brain regions:

1. Correlation between time-series matrices of social cognition tasks and working memory tasks.
2. 2. Looking for common brain regions involved in both working memory and social cognition through t-tests. (Key Contributor: [Sachin Patalasingh] (https://twitter.com/synapticallyurs)


