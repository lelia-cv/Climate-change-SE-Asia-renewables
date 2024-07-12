In this repository, you will find two types of files:
\begin{itemize}
	\item dataset files, listed in folders whose names contain "data", followed by the source of the data
	\item code files, in .ipynb format
\end{itemize}
The datasets contain:
\begin{itemize}
	\item flowrate daily data for Stung Treng (1910-2024), Kratie (1924-2024), and Chiang Khan (1967-2024) (source: Mekong River Commission data portal)
 	\item rainfall daily data for Stung Treng (2007-2024) and Chiang Khan (2008-2024) (source: Mekong River Commission data portal)
  	\item GDP annual data and forecasts for Thailand and Laos (1980-2029) (source: IMF)
   	\item annual hydro and solar generation in Laos and Cambodia (2005-2021) (source: IEA)
    	\item Cambodia annual mean temperature (2007-2022) and monthly mean temperatures averaged by decade (1051-2020) (source: )
     	\item annual rice production in Cambodia and Laos (2005-2022) (source: FAO)
\end{itemize}
The details of the code files are the following:
\begin{itemize}
	\item \texttt{nested_crossval.ipynb}: nested cross-validation based on Stung Treng dataset
 	\item \texttt{nested_cv_nobaseline.ipynb}: nest cross-validation based on Stung Treng dataset without the monthly minimum flowrate feature
  	\item \texttt{nested_cv_CK.ipynb}: nested cross-validation based on Chiang Khan dataset
   	\item \texttt{kratie_pred.ipynb}: nested cross-validation for models predicting Kratie flowrate based on Stung Treng inputs
    	\item \texttt{pred_COVID.ipynb}: nested cross-validation for models predicting 2020-2021 flowrate based on Stung Treng dataset
