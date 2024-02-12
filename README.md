# Variables for Ecosystem Modelling


## Satellite Variables

In this section, we list various satellite data variables along with relevant details:

| Serial No | Variable Name                                      | Unit              | Category                    | Source                                                |
|-----------|----------------------------------------------------|-------------------|-----------------------------|-------------------------------------------------------|
| 1         | Chlorophyll-a concentration (CHL)                 | mg m⁻³            | Water quality (Nutrient)    | [CMEMS](https://marine.copernicus.eu/product/OCEANCOLOUR_GLO_BGC_L4_MY_009_104/services) |
| 2         | Micro-phytoplankton                                | mg m⁻³            | Water quality (Nutrient)    |                                                         |
| 3         | Nano-phytoplankton                                 | mg m⁻³            | Water quality (Nutrient)    |                                                         |
| 4         | Pico-phytoplankton                                 | mg m⁻³            | Water quality (Nutrient)    |                                                         |
| 5         | Diatoms                                            | mg m⁻³            | Ecology (Planktonic)        |                                                         |
| 6         | Dinophytes                                         | mg m⁻³            | Ecology (Planktonic)        |                                                         |
| 7         | Green Algae                                        | mg m⁻³            | Ecology (Planktonic)        |                                                         |
| 8         | Haptophytes                                        | mg m⁻³            | Ecology (Planktonic)        |                                                         |
| 9         | Prokaryotes                                        | mg m⁻³            | Ecology (Planktonic)        |                                                         |
| 10        | Prochlorococcus                                    | mg m⁻³            | Ecology (Planktonic)        |                                                         |
| 11        | Particulate back-scattering coefficient            | %                 | Light                       |                                                         |
| 12        | Backwards scattering coefficient                   | m⁻¹               | Light                       |                                                         |
| 13        | Absorption coefficient due to DOM (CDOM)           | m⁻¹               | Light                       |                                                         |
| 14        | Primary productivity of biomass (C)                | mg/m²/day         | Water quality (Nutrient)    |                                                         |
| 15        | Remote sensing reflectance at 412 nm               | Sr⁻¹              | Light                       |                                                         |
| 16        | Remote sensing reflectance at 443 nm               | Sr⁻¹              | Light                       |                                                         |
| 17        | Remote sensing reflectance at 490 nm               | Sr⁻¹              | Light                       |                                                         |
| 18        | Remote sensing reflectance at 555 nm               | Sr⁻¹              | Light                       |                                                         |
| 19        | Remote sensing reflectance at 670 nm               | Sr⁻¹              | Light                       |                                                         |
| 20        | Volume Attenuation coefficient (KD490)             | m⁻¹               | Light                       |                                                         |
| 21        | Secchi disk depth (ZSD)                           | m                 | Light                       |                                                         |
| 22        | Suspended Particle Matter (SPM)                    | g/m⁻³             | Water quality (Nutrient)    |                                                         |
| 23        | Water surface temperature                          | °C                | Water quality (PhysChm)     | [NASA](https://oceancolor.gsfc.nasa.gov/l3/)                                              |
| 24        | Particulate Organic carbon (POC)                   | mg/m³             | Water quality (Nutrient)    |                                                         |
| 25        | Particulate Inorganic carbon (PIC)                 | mg/m³             | Water quality (Nutrient)    |                                                         |
| 26        | Diffuse attenuation coefficient (PAR)              | m⁻¹               | Light                       |                                                         |
| 27        | Heated layer depth, ZSL                            | m                 | Light                       | [ACRI](https://hermes.acri.fr/index.php?class=archive)                                                 |
| 28        | Euphotic layer depth, ZEU                          | m                 | Light                       |                                                         |
| 29        | Air Density                                        | kg/m³             | Meteorology                 | [CMEMS](https://data.marine.copernicus.eu/product/WIND_GLO_PHY_L4_NRT_012_004/description) |
| 30        | Wind Speed                                         | m/s               | Meteorology                 |                                                         |
| 31        | Wind-to Direction                                  | degree            | Meteorology                 |                                                         |
| 32        | Zonal (Eastward) Wind Velocity                     | m/s               | Meteorology                 |                                                         |
| 33        | Meridional (Northward) Wind Velocity               | m/s               | Meteorology                 |                                                         |
| 34        | Wind Divergence                                    | 1/s               | Meteorology                 |                                                         |
| 35        | Wind Curl                                          | 1/s               | Meteorology                 |                                                         |
| 36        | Wind Stress Magnitude                              | N/m²              | Meteorology                 |                                                         |
| 37        | Sea surface height (sla)                           | m                 | Hydrodynamics               | [CMEMS](https://data.marine.copernicus.eu/product/SEALEVEL_GLO_PHY_L4_MY_008_047/description) |
| 38        | Sea surface height above geoid, adt                | m                 | Hydrodynamics               |                                                         |
| 39        | Surface geostrophic eastward sea water velocity, ugos | m/s           | Hydrodynamics               |                                                         |
| 40        | Surface geostrophic northward sea water velocity, vgos | m/s          | Hydrodynamics               |                                                         |
| 41        | Surface geostrophic northward sea water velocity assuming sea level for geoid, vgosa | m/s | Hydrodynamics |                                                 |
| 42        | Sea surface height above sea level, noise          | m                 | Hydrodynamics               | [CMEMS](https://data.marine.copernicus.eu/product/SEALEVEL_GLO_PHY_NOISE_L4_STATIC_008_033/services) |

## Variables from the Model Output

In this section, we list various  variables from model output along with relevant details:

| Serial No | Variable No                                   | Unit       | Category                | Source   |
|-----------|----------------------------------------------|------------|-------------------------|----------|
| 1         | Total alkalinity                             | mol/m³      | Water Quality (Nutrient)| [CMEMS](https://data.marine.copernicus.eu/product/GLOBAL_ANALYSISFORECAST_BGC_001_028/description)    |
| 2         | Concentration of chlorophyll                 | mg/m³      | Water Quality (Nutrient)|          |
| 3         | Concentration of dissolved inorganic carbon  | mol/m³     | Water Quality (Nutrient)|          |
| 4         | Concentration of dissolved iron               | mmol/m³    | Water Quality (Nutrient)|          |
| 5         | Concentration of nitrate                     | mmol/m³    | Water Quality (Nutrient)|          |
| 6         | Net primary production of biomass            | mg/m³/day  | Water Quality (Nutrient)|          |
| 7         | Concentration of dissolved molecular oxygen   | mmol/m³    | Water Quality (Nutrient)|          |
| 8         | pH                                           |            | Water Quality (PhysChm)  |          |
| 9         | Concentration of phytoplankton               | mmol/m³    | Water Quality (Nutrient)|          |
| 10        | Concentration of phosphate                   | mmol/m³    | Water Quality (Nutrient)|          |
| 11        | Concentration of silicate                    | mmol/m³    | Water Quality (Nutrient)|          |
| 12        | Surface partial pressure of carbon dioxide   | Pa         | Water Quality (PhysChm)  |          |
| 13        | Light attenuation coefficient, KD            | m⁻¹        | Light                   |          |
| 14        | Eastward sea water velocity (uo)             | m/s        | Hydrodynamics           | [CMEMS](https://data.marine.copernicus.eu/product/GLOBAL_ANALYSISFORECAST_PHY_001_024/description)    |
| 15        | Northward sea water velocity (vo)            | m/s        | Hydrodynamics           |          |
| 16        | Sea water salinity (so)                     | 10⁻³        | Water Quality (PhysChm)  |          |
| 17        | Sea water potential temperature (thetao)     | °C         | Water Quality (PhysChm)  |          |
| 18        | Upward sea water velocity, wo                | m/s        | Hydrodynamics           |          |
| 20        | Ocean mixed layer thickness, sigma theta, mlotst | m     | Hydrodynamics           |          |
| 21        | Sea water pressure at sea floor, pbo         | dbar       | Hydrodynamics           |          |
| 22        | Surface sea water x velocity due to tide, utide | m/s    | Hydrodynamics           |          |
| 23        | Surface sea water y velocity due to tide , vtide | m/s   | Hydrodynamics           |          |
| 24        | Surface sea water x velocity, utotal         | m/s        | Hydrodynamics           |          |
| 25        | Surface sea water y velocity, vtotal         | m/s        | Hydrodynamics           |          |
| 26        | Sea floor depth below geoid, deptho          | m          | Hydrodynamics           |          |
| 27        | Sea water potential temperature vertical mean over pelagic layer, T | °C | Ecology (Pelagic)   | [CMEMS](https://data.marine.copernicus.eu/product/GLOBAL_MULTIYEAR_BGC_001_033/description)    |
| 28        | Eastward sea water velocity vertical mean over pelagic layer, U | m/s | Ecology (Pelagic)   |          |
| 29        | Northward sea water velocity vertical mean over pelagic layer, V | m/s | Ecology (Pelagic)   |          |
| 30        | Sea water pelagic layer bottom depth, pelagic_layer_depth | m | Ecology (Pelagic)   |          |
| 31        | Epipelagic micronekton                      | g/m²       | Ecology (Pelagic)       |          |
| 32        | Highly migrant lower mesopelagic micronekton | g/m²    | Ecology (Pelagic)       |          |
| 33        | Lower mesopelagic micronekton                | g/m²       | Ecology (Pelagic)       |          |
| 34        | Migrant lower mesopelagic micronekton       | g/m²       | Ecology (Pelagic)       |          |
| 35        | Migrant upper mesopelagic micronekton       | g/m²       | Ecology (Pelagic)       |          |
| 36        | Upper mesopelagic micronekton                | g/m²       | Ecology (Pelagic)       |          |
| 37        | Net primary productivity of biomass         | mg/m²/day   | Water Quality (Nutrient)|          |
| 38        | Euphotic zone depth                          | m          | Light                   |          |
| 39        | Zooplankton                                 | g/m²       | Water Quality (Nutrient)|          |
| 40        | Sea surface wave maximum height, VCMX        | m          | Hydrodynamics           | [CMEMS](https://data.marine.copernicus.eu/product/GLOBAL_ANALYSISFORECAST_WAV_001_027/description)    |
| 41        | Sea surface wave significant height, VHM0   | m          | Hydrodynamics           |          |
| 42        | Sea surface primary swell wave significant height, VHM0_SW1 | m | Hydrodynamics     |          |
| 43        | Sea surface secondary swell wave significant height, VHM0_SW2 | m | Hydrodynamics     |          |
| 44        | Sea surface wind wave significant height, VHM0_WW | m       | Hydrodynamics           |          |
| 45        | Sea surface wave from direction, VMDR        | °          | Hydrodynamics           |          |
| 46        | Sea surface primary swell wave from direction, VMDR_SW1 | ° | Hydrodynamics       |          |
| 47        | Sea surface secondary swell wave from direction, VMDR_SW2 | ° | Hydrodynamics     |          |
| 48        | Sea surface wind wave from direction, VMDR_WW | °         | Hydrodynamics           |          |
| 49        | Sea surface wave from direction at variance spectral density maximum, VPED | ° | Hydrodynamics |          |
| 50        | Sea surface wave stokes drift x velocity, VSDX | m/s   | Hydrodynamics           |          |
| 51        | Sea surface wave stokes drift y velocity, VSDY | m/s   | Hydrodynamics           |          |
| 52        | Sea surface primary swell wave mean period, VTM01_SW1 | s | Hydrodynamics        |          |
| 53        | Sea surface secondary swell wave mean period, VTM01_SW2 | s | Hydrodynamics      |          |
| 54        | Sea surface wind wave mean period, VTM01_WW  | s         | Hydrodynamics           |          |
| 55        | Sea surface wave mean period from variance spectral density second frequency moment, VTM02 | s | Hydrodynamics | |
| 56        | Sea surface wave mean period from variance spectral density inverse frequency moment, VTM10 | s | Hydrodynamics | |
| 57        | Sea surface wave period at variance spectral density maximum, VTPK | s | Hydrodynamics |          |


## How to Downlaod/acess the data variables

In the variable list under the column of source, I have used the variable from three websites, for example, `CMEMS, NASA, ACRI`. 

We will visit each website to understand how to download the data. For sites like CMEMS, NASA, ACRI, you have to register yourself, meaning you have to open an account to download the data from the site. Here, we will use the command-line tools to access the data from each site. 

First, I will demonstrate how to download Copernicus data. We will use the Copernicus Marine Toolbox. Although we can download the dataset manually by visiting their site, it covers only up to 1024 MB. When you have to download more than that, you have to use the command-line tool or Python interface. But we will show here the command-line tools for our demonstration.

## Accessing  CMEMS variables

First, I will demonstrate how to access oceanographic data from CMEMS using the Copernicus Marine Toolbox. CMEMS provides a rich source of marine environmental data, and we'll explore how to download data using command-line tools.

### Prerequisites

Before you begin, make sure you have the following installed:

- Register yourself to [CMEMS](https://data.marine.copernicus.eu/register?redirect=/products)
- Copernicus Marine Toolbox installation

### Install Copernicus Marine Toolbox 

Let's see how to create an environment containing the Copernicus Marine Toolbox via Mamba. You can replace Mamba with Conda if you haven't installed it yet.

### Step 1. 

Create, using your favorite text editor, the file `copernicusmarine_env.yml` that describes the local environment and contains:

```yaml
name: cmt_1.0
channels:
  - conda-forge
dependencies:
  - pip
  - pip:
    - copernicusmarine>=1.0,<=2.0
  - python>=3.9,<3.12
```
### Step 2: Open the terminal

Open the Miniforge Prompt (or your favorite terminal) and move to the directory where you have saved the `.yml` file.

```bash
cd path/to/directory
```

### Step 3: Create the environment

Run the following command to create the environment `cmt_1.0`:

```bash
mamba env create -f copernicusmarine_env.yml
```
### Step 4: Activate the new environment

Activate the new `cmt_1.0` environment using the following command:

```bash
mamba activate cmt_1.0

```
### Step 5: Log in (for the first time), then it will be automatically configured.

```bash
copernicusmarine login
```

This command will prompt you to provide your username and password. After successful login, the configuration will be automatically set up. By default, the configuration file is saved in your home directory, but you can customize the destination by using the `--configuration-file-directory` option.

### Download the Data (Subset)

To download a subset of the data, use the following `copernicusmarine subset` command:

```bash
copernicusmarine subset
   --dataset-id cmems_obs-oc_glo_bgc-plankton_my_l4-multi-4km_P1M
   --force-dataset-version 202311
   --variable CHL
   --variable DIATO
   --variable DINO
   --variable GREEN
   --variable HAPTO
   --variable MICRO
   --variable NANO
   --variable PICO
   --variable PROCHLO
   --variable PROKAR
   --start-datetime 1998-01-01T00:00:00
   --end-datetime 2024-01-01T00:00:00
   --minimum-longitude 109.48920891362069
   --maximum-longitude 116.74702757932604
   --minimum-latitude -35.97509160510578
   --maximum-latitude -26.44373938146864
```

## Accessing NASA variables

### Create a .netrc file

The recommended method is to configure your username and password for authentication using a `.netrc` file. If you experience errors or redirects when using a cookie file, delete any existing cookie files and generate a new one for your current session.

You can use the following commands:

```bash
echo "machine urs.earthdata.nasa.gov login USERNAME password PASSWD" > ~/.netrc ; > ~/.urs_cookies
chmod  0600 ~/.netrcw.
```
Replace USERNAME and PASSWD with your Earthdata Login credentials.

To sign up for Earthdata, visit https://urs.earthdata.nasa.gov/users/new

### Retrieve a Single File Using Cookies to Pass Credentials

To retrieve a single file using cookies to pass credentials, you can use the `wget` command with the following options:

```bash
wget --load-cookies ~/.urs_cookies --save-cookies ~/.urs_cookies --auth-no-challenge=on --content-disposition 'https://oceandata.sci.gsfc.nasa.gov/ob/getfile/T2017004001500.L1A_LAC.bz2'
```
## Accessing ACRI variables

### Accessing Data via Direct FTP on the GlobColour Archive

Direct FTP access to the entire GlobColour database of Global and Europe products is available to registered users at `ftp://ftp.hermes.acri.fr`. To obtain access, follow these steps:

1. **Fill the Registration Form:**
   Visit [GlobColour FTP Registration](ftp://ftp.hermes.acri.fr) and fill out the registration form. Provide the required information, including your email, first name, last name, institution, etc.

2. **FTP Server Information:**
   Once registered, you can access the FTP server at `ftp://ftp.hermes.acri.fr`. Use the login credentials obtained during the registration process.

3. **Database Structure:**
   The structure of the FTP archive is organized hierarchically:

   - `(globcolour|OSS2015)/zone (GLOB|EURO)`
     - `/sensor (merged|seawifs|meris|modis|viirsn|olcia|viirsj1|olcib)`
       - `/binning period (day|8-day|month)`
         - `/yyyy/mm/dd`

   Each directory contains the following types of files:

   - NetCDF4 Products:
     - `L3b*.nc`
     - `L3m*.nc`
   - "Quicklook" Images:
   ges (L3m*.png).dd


You're welcome! If you have any further questions or need assistance in the future, feel free to drop an email at `mdrony.golder@postgrad.curtin.edu.au`. I'm here to help. Have a great day!
