# MAPTA Security section maps and charts

This repository contains the code of the React App that was developed by 
Sociopublico for the Climate, Environment, and Security Division of the 
Sahel and West Africa Club (SWAC/OECD). This React application creates the 
interactive maps and charts that are used in the **Security** section of
the [MAPTA](https://mapping-africa-transformations.org/) platform.

The application used data up to December 2021, and was delivered to SWAC 
during late 2022. The original ccode of this application is stored on GitHub in 
a private repository owned by Sociopublico.

SWAC requested a copy of the repository to be able to implement yearly 
data updates and received a copy of it in June 2023. There is no 
documentation related to the application code.

## Yearly update note
The data used in the maps and charts were updated up to December 2022. 
The new datasets were processed in R and the input dataset files (csv and json) 
were replaced. The update also included corrections to the data used in the 
**Borders** tab. This correction included generating new buffers from 
country boundaries, checking and correcting region's boundaries 
and selecting ACLED violent events within the new buffers.
The [ACLED](https://acleddata.com/) input data was preprocessed by the 
[Sahel Research Group](https://sahelresearch.africa.ufl.edu/people/). 
Texts relative to the year of the charts and sources were updated as well.

The data update process was implemented by Jorge Patino (jorge.patino@oecd.org),
and tested locally on September 2023.
