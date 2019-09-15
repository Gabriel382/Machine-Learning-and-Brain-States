# Machine-Learning-and-Brain-States

## Context

Research project conducted at INSA Rouen on machine learning to test different prediction models in a kaggle database.

## Introduction

The brain is an electrochemical organ. All this electrical activity is responsible for different types of brain waves. Throughout the day, the brain keeps active the 5 types of brainwaves (some act at low frequency, others at a higher frequency). Depending on what we do at any given moment, some waves will show greater activity in certain areas of the brain, and others will work less intensely in other regions. None of them will be, in other words, "disconnected." They are:
 * Delta waves (1 to 3 Hz) : Delta waves are those that have a higher wavelength and are related to deep sleep (but without dreams) and bodily activities that we are not aware of, such as heart rate regulation or digestion ;
 * Theta waves (3.5 to 8 Hz) : is related, above all, to the imaginative capacities, the reflection and the sleep ;
 * **Alpha waves (8 to 13 Hz) :** Appear in the midnight dusk where there is calm, but not sleep, where there is relaxation and a favorable state to meditate. A high level of Alpha waves would prevent us from focusing attention ;
 * Beta waves (12 to 33 Hz) : Accented by states that are related to the daily activities in which we focus all the attention, when we are alert and we need, at the same time, to be attentive to numerous stimuli.
 * Gamma waves (25 to 100 Hz) : This wave is related to tasks of high cognitive processing. They have to do with our learning style, with the ability to record new information, and also with our senses and perceptions, states of happiness and the phases of REM sleep.  
 
Of the 5 waves, 3 of them can be divided into low and high frequencies, because they have strong components in both bands.

Knowing the different types of brain waves allows us to understand the mental processes, emotions, activities and dynamics that generate a type of "energy" in the brain. The Alpha, Beta and Gamma waves are very interesting for recognition of brain states linked to actions, feeling and concentration.

## Objective

A classification model that identifies different mental states is desirable. In other words, given a range of possible mental configurations and a set of training data, it is desired to find a model capable of predicting such states from similar data.

Our intention is to compare different models already existing in the literature to observe which models have the best performance in the bci data.

## Description of the data

### Data Introduction

We chose to work with data from the [Kaggle - Synchronized Brainwave Dataset](https://www.kaggle.com/berkeley-biosense/synchronized-brainwave-dataset). This data set consists of an experiment with 30 patients in an experiment where each one was forced to watch a video showing different mental tasks that must be performed. To simplify our methods, we will focus only on the first experiment that is an experiment that measures the level of concentration of a patient when he makes mental calculations of different equations.

### Description of the type of methods

We will be working with a binary classification algorithm, since we want to know if the patient is relaxed or concentrated. We will use supervised methods since we already know the output types and we have a set of data already with labels.

## Project Structure

 * Article-BCIDATA-ALENCAR_MEDEIROS_Gabriel_Henrique : Short article about the project ;
 * BCI_synchronized-brainwave-dataset : Project Code ;
 * Presentation-BCIDATA-ALENCAR_MEDEIROS_Gabriel_Henrique : Presentation of the project carried out at INSA Rouen.
