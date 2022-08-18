# OHW22 ENSO Prediction
### Data description
- Coarsened CESM2 Large Ensemble members (SST fields) from 1° to 3° resolution 
- Used the first 10 of 100 CESM2 LE members

### Deep learning components
- 2D CNN (relu/selu, adam/nadam/adamx)
- 3D CNN (relu/selu, adam/nadam/adamx)
- EOF/LSTM
- CNN/LSTM
- Transformers?
- Create a baseline method to compare these methods to (i.e. persistence method, AR1 model)
- Interpretability– why do the results look this way?
