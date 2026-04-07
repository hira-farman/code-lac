Dataset characteristics:

Source: NASA POWER meteorological dataset
Period: 1990–2025
Records: ≈130,000 daily observations
Cities:
Hyderabad
Karachi
Gharo
Jamshoro
Larkana
Nawabshah
Thatta
Mirpurkhas
Quetta
Hub (Lasbela)

Features include:Dataset Features (Exact Variables Used)

The rainfall occurrence classification framework uses the following meteorological predictors extracted from the NASA POWER dataset:

📍 Location & Time Identifiers
Locations — City/location name
YEAR — Observation year
DOY — Day of year (1–365)
🌡️ Temperature-Based Variables
T2M — Mean air temperature at 2 meters (°C)
T2MDEW — Dew point temperature at 2 meters (°C)
T2M_RANGE — Daily temperature range (°C)
T2M_MAX — Maximum temperature at 2 meters (°C)
T2M_MIN — Minimum temperature at 2 meters (°C)
T2MWET — Wet-bulb temperature at 2 meters (°C)
💧 Moisture & Humidity Variables
QV2M — Specific humidity at 2 meters (kg/kg)
RH2M — Relative humidity at 2 meters (%)
🌧️ Rainfall Variables
PRECTOTCORR — Bias-corrected total precipitation (mm/day)
IMERG_PRECTOT — IMERG satellite precipitation estimate (mm/day)
🌬️ Wind Variables
WS2M_MAX — Maximum wind speed at 2 meters (m/s)
WS2M_MIN — Minimum wind speed at 2 meters (m/s)
WS2M_RANGE — Wind speed range at 2 meters (m/s)
WS10M_MIN — Minimum wind speed at 10 meters (m/s)
WD2M — Wind direction at 2 meters (degrees)
☀️ Radiation & Atmospheric Variables
ALLSKY_SFC_UV_INDEX — Surface UV index (clear + cloudy sky)
ALLSKY_SFC_SW_DNI — Direct normal irradiance (W/m²)
🌍 Pressure Variable
PS — Surface pressure (kPa)
