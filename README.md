Project Data Description
This folder contains datasets related to PV (photovoltaic) generation and forecasting. Below is a description of the available files:
02_PVgeneration/PV#_{start_date}_to_{end_date}.csv
Content: PV generation data generated using the PYwatt library.
Scope: Each file corresponds to a specific PV power building.
Included data:
Weather information
PV generation measurements
Key variable:
P_dc_kW: Represents the PV power output (direct current, in kW).
rooftop_pv_power_forecast_{lat}_{long}.csv
Content: Trial dataset provided by Solcast.
Scope: Rooftop PV power forecasts at the specified latitude and longitude ({lat}, {long}).
📌 Note: File naming conventions use placeholders ({start_date}, {end_date}, {lat}, {long}) that should be replaced with actual values in the dataset.
