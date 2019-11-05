# Test creation of this website


# Paloma et al. 2019 - Observational Study of the Thermodynamics and Morphological Characteristics of a Midlatitude Continential Cold Pool Event

## Introduction

- Cold pools from first-gen storms
    - Important for initiation, intensity, and lifecycle of secondary storms

- Cold pool importance
    - Has substantial impact on MCSs (able to bring new life to them)
        - Also influences their organization and structure
    - Environmental air moving over the edge of the cold pool can trigger new convection
    - Can lead to flash flooding when cold pool and environmental flow are in balance with one another
    - Wind gusts near the leading edge of cold pools can impact the aviation industry
    - Cold pools impact land-atmosphere interactions which can change PBL characteristics
        - Moisture, heat, momentum, etc. 
    - Results in a stable layer near surface, which inhibits convection

- Cold pools are difficult to model
    - Uncertainty about the microphysical processes
        - Could impact the horizontal extent, depth, or strength

- Often use surface observations
    - OK Mesonet used in the past
        - Temperature, Pressure, Wind Speed, Wind Direction
 
- Use soundings to estimate cold pool depth
    - Need targeted observations (Field Campaigns!)
        - Northern Illinois Meteorological Research on Downburst (NIMROD) (Wakimoto 1982)
        - Thunderstorm Project (Byers and Braham 1949)
        - NSSL Experiments (Sanders and Emanuel 1977, Ogura and Chen 1977, Ogura and Chen 1980, Park and Sikdar 1982)
        - Bow Echo and Mesoscale Convective Vortex Experiment (BAMEX) (Byran et al. 2005, Ahijevych et al. 2006)
        - Second Verification of the Origins of Rotation in Tornadoes Experiment (VORTEX2) (Bryan and Parker 2010)
        - Plains Elevated Convection at Night (PECAN) (Geerts et al. 2017, Hitchcock et al. 2019)

- In this study, used observations from Midlatitude Continential Convective Clouds Experiment (MC3E) (Jensen et al. 2016)
    - When?
     - June 2011
    - Observations included 
        - Atmospheric Radiation Measurment
            - Weather stations, radars, soundings
        - OK Mesonet
            - Weather stations
        - NEXRAD Doppler Radars
            - Reflectivity, dual pol products

- Main Goal
    - Use observations to quantify evolution of cold pool characterisitcs over a time period of a few hours
    - Utilize targeted observations in addition to NEXRAD/OK Mesonet data
        - Use for detection and analysis of intensity, height, and speed of the cold pool
    - Create a new methodology for identifying cold pools from radar
        - Proof of concept using NEXRAD observations

# Datasets
- Primary dates - 23-24 May 2011
- Most data collected from ARM
    - Radar deployments
    - Surface weather stations
    - Disdrometers
    - High temporal frequency sounding array

- Radar observations
    - Scanning precip radars
        - 5.4 GHZ C-Band ARM Precip Radar (CSAPR) (C-Band)
            - Used Range Height Indicator (RHI) scans
        - NEXRAD Dopplers (S-Band)
            - Every 6 minutes up to 230 km from radar
            - Base and dual pol products

- Surface observations
    - OK Mesonet
        - 5 minute observations @ 120 observation sites throughout the state
    - ARM
        - 1 minute observations @ 9 observation sites in the primary domain
    - Combined spatial resolution - 35 km

- Soundings
    - 8 times per day @ 6 sites
    - QC'd data using method from Jensen et al. 2015
    - Used sounding station S1 (160km NW of radar near Pratt, KS)

# Method

## Cold Pool Detection/Estimation of Height and Speed
- Leading edge of cold pool (LECP) identified using thin line echoes on radar
- Edited radar data using NCAR Solo-II radar data processing software
    - Manually isolate thin line from rest of the radar image in each of the PPI images (where possible)
    - Used results from this to analyze radar products
        - Reflectivity, spectrum width, differential reflectivity
        - Speed and depth of cold pool

- Speed and depth of cold pool
    - Mean distance traveled by cold pool between radar images
    - Height = maximum elevation angle where thin line is identified

- Height of cold pool
    - Measured to beam center above ground using 4/3 Earth radius model
        - Ex. @ 2.4 degrees, height = 2.1 km
    - Uncertainty is half radar beamwidth (0.5 degrees) above and below beam
        - Ex. at 2.4 degrees, uncertainty = 440 m
        - Increases as distance from radar increases

# Results
- LECP formation was due to several cells (individual thunderstorms)

- Surface observations
    - Hourly temperature/wind vectors were interpolated from observations
    - Decrease in temp with cold pool passage
    - Shift in low-level flow to easterly component
    - Increase in wind speed

- Radar Observations
    - Narrow distribution around LECP
        - Mean == 8 dBz, Std. Deviation = 2 dBz
        - This was for the more well-defined cold pool

## Cold Pool Characteristics

- 4 Hour period (20:30 UTC - 1:30 UTC)
- Used surface observations to confirm path
    - As cold pool moves west, magnitude of temperature drop decreases
    - Magnitude of wind speed increase also decreases
    - All observations still have a wind shift of a more easterly component

- Cold pool height
    - Radar observations
        - Max height - 2.5 - 4 km
            - More variable with time
        - Mean height - 1-3 km
    - Sounding observations
        - Compared 2:30 UTC (cold pool) with 23:30 UTC (environment)
        - Cold pool sounding drifted 5.11 km within first 3km of ascent
        - Looked at vertical profiles using AGL as vertical coordinate
            - Temperature is cooler for cold pool sounding (from ground to 1.4 km)
            - Maximum wind speed is greater in the middle of the layer (1 km)
            - Wind direction matches surface observation
            - Depth is about 1.4 - 1.6 km
    - Reason for difference in depths
        - Cold pools often have a shape of bulging near leading edge, then taper off
        - Often more shallow away from leading edge

- Propagation Speed
    - Almost constant - 6.7 m/s
    - Agrees with timing of the different surface observations
    - Could use gravity current theory to estimate speed
        - Makes assumption of homogeneous and inactive conditions
        - These assumptions are violated due to spatial/temporal heterogeneity 
