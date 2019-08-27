# Pulsar-stars
The following data set describes a sample of pulsar candidates.

## Description
Pulsars are a rare type of Neutron star that produce radio emission detectable here on Earth. They are of considerable scientific interest as probes of space-time, the inter-stellar medium, and states of matter.

As pulsars rotate, their emission beam sweeps across the sky, and when this crosses our line of sight, produces a detectable pattern of broadband radio emission. As pulsars rotate rapidly, this pattern repeats periodically. Thus pulsar search involves looking for periodic radio signals with large radio telescopes.

Each pulsar produces a slightly different emission pattern, which varies slightly with each rotation . Thus a potential signal detection known as a 'candidate', is averaged over many rotations of the pulsar, as determined by the length of an observation. In the absence of additional info, each candidate could potentially describe a real pulsar. However in practice almost all detections are caused by radio frequency interference (RFI) and noise, making legitimate signals hard to find.

## Dataset
The dataset contains numerous attributes to determine whether a candidate is a pulsar star or not.
These attributes are:
  -  Mean of the integrated profile
  -  Standard deviation of the integrated profile
  -  Excess kurtosis of the integrated profile
  -  Skewness of the integrated profile
  -  Mean of the DM-SNR curve
  -  Standard deviation of the DM-SNR curve
  -  Excess kurtosis of the DM-SNR curve
  -  Skewness of the DM-SNR curve
  
  The data set contains 16,259 spurious examples caused by RFI/noise, and 1,639 real pulsar examples. These examples have all been checked by human annotators.
  
 The target variable decides whether a candidate is a pulsar star or not.
  - 0 (Is not a pulsar star)
  - 1 (Is a pulsar star)
  
 ## Objective
 The objective of this project is to build various classification machine learning models and to choose a model which predicts the most accurate results as to determine whether a candidate is a pulsar star or not.
 
 
