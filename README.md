# NASA_WEF_Wheat
Repository for Machine Learning to Characterize Hydro-Climate Impacts and Thresholds to Rainfed Agricultural Productivity

Project Abstract: Sparse observational data in developing regions leads to uncertainty about how hydro-climatic factors influence crop phases and productivity, knowledge of which is essential to mitigating food security threats induced by climate change.
In this study, NASA Tropical Rainfall Measuring Mission (TRMM), Global Precipitation Measurement (GPM), and Global Land Data Assimilation System (GLDAS) data products bypass spatiotemporal limitations and drive machine learning algorithms developed to characterize hydro-climate-productivity interactions.
Extensive feature engineering processes these products into nearly 4000 metrics, designed to decompose crop growing season hydro-climate conditions.
Dimensionality reduction with bidirectional step-wise regression, Multi-Adaptive-Regression-Splines (MARS), and Random Forest algorithms are explored to determine key temporal hydro-climate drivers to agricultural productivity, with each method recognizing unique linear and non-linear predictors.
Finally, multi-variate regression, MARS, and Random Forest models are trained on the drivers to predict seasonal crop yield. 
We apply this hydro-climate-productivity framework to investigate \textit{rabi} wheat productivity on Pakistan's Potohar Plateau.
Here, we identify six of wheat's ten phenological phases that display strong hydro-climate responses, with the shooting phase exhibiting sensitivity to precipitation intensity, minimum soil moisture, and sub-zero temperatures.
In addition, the plateau's heterogeneous climate-productivity connections are captured well by the calibrated models, strengthening their application for studying broader climate change impacts.
The integration of remote sensing products and machine learning offers an effective framework to bypass in-situ data limitations and decompose climate-crop productivity relationships, thus improving drought onset recognition and food security forecasting.


Within this repository are NASA GLDAS, TRMM, and GPM hydro-climate data within the HydroClimate_RS_Data.zip file, district resolution wheat productivity data within the WheatProductivity.zip file, the model input dataframe within the ModelInput.zip file, all models variable selection and modeling scripts within the Models.zip file, and all model reslts within the Results.zip file.
