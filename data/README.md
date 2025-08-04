# Data
-   **[Dataset]**: This dataset contains GPS tracking data for pet cats in the United States and includes variables such as timestamps, animals IDs, sex, age, location coordinates, and movement attributes. This dataset is published by the [Movebank Data Repository](https://www.datarepository.movebank.org). A version of this published animal tracking dataset can be viewed on [Movebank](https://www.movebank.org) in the study "Pet Cats United States" (Movebank Study ID 10857031). Metadata are maintained at [DataCite](https://datacite.org).

# Codebook for Pet Cats USA Dataset

## Variable Names and Descriptions:

- **algorithm marked outlier**: Identifies events marked as outliers using a filter algorithm. `TRUE` if outlier.
- **animal comments**: Additional information about the animal (e.g. "sibling of #1423").
- **animal ID**: Unique identifier for the animal (e.g. `91876A`, `Gary`).
- **animal life stage**: Age class of the animal at deployment (e.g. `juvenile`, `adult`).
- **animal reproductive condition**: Reproductive status at deployment (e.g. `lactating`).
- **animal sex**: Sex of the animal (`m` = male, `f` = female).
- **animal taxon**: Scientific name of the species (e.g. *Buteo swainsoni*).
- **attachment type**: Tag attachment method (`collar`, `glue`, `harness`, `implant`, `tape`, `other`).
- **data processing software**: Software used for data processing (e.g. `BASTrack`).
- **deploy off timestamp**: Time tag deployment ended (`yyyy-MM-dd HH:mm:ss.SSS`).
- **deploy on timestamp**: Time tag deployment started (`yyyy-MM-dd HH:mm:ss.SSS`).
- **deployment end type**: Classification of deployment end (`captured`, `dead`, `equipment failure`, etc.).
- **deployment ID**: Unique identifier for tag deployment.
- **duty cycle**: Duty cycle remarks describing tag activity schedule.
- **event ID**: Identifier for each event or sensor measurement.
- **ground speed**: Estimated ground speed (m/s).
- **heading**: Movement direction in degrees clockwise from north (0–360).
- **height above ellipsoid**: Height above ellipsoid (m).
- **location lat**: Latitude in decimal degrees (WGS84).
- **location long**: Longitude in decimal degrees (WGS84).
- **manipulation comments**: Notes on manipulation during deployment.
- **manipulation type**: Type of manipulation (`confined`, `none`, `relocated`, `manipulated other`).
- **manually marked outlier**: Events flagged manually as outliers.
- **sensor type**: Type of sensor (`GPS`, `acceleration`, `barometer`, etc.).
- **study name**: Study name in Movebank.
- **study site**: Deployment site or related location.
- **tag ID**: Unique identifier for tag.
- **tag manufacturer name**: Manufacturer of tag (e.g. `Holohil`).
- **tag mass**: Mass of the tag (grams).
- **tag model**: Model of the tag.
- **tag readout method**: Data retrieval method (`satellite`, `phone network`, `tag retrieval`, etc.).
- **timestamp**: Date and time of sensor measurement (`yyyy-MM-dd HH:mm:ss.SSS`).
- **visible**: Event visibility (`TRUE` or `FALSE`).

## Data Types:

- **algorithm marked outlier**: boolean
- **animal comments**: string
- **animal ID**: string
- **animal life stage**: string
- **animal reproductive condition**: string
- **animal sex**: string (categorical)
- **animal taxon**: string
- **attachment type**: string (categorical)
- **data processing software**: string
- **deploy off timestamp**: datetime
- **deploy on timestamp**: datetime
- **deployment end type**: string (categorical)
- **deployment ID**: string
- **duty cycle**: string
- **event ID**: string
- **ground speed**: float
- **heading**: float
- **height above ellipsoid**: float
- **location lat**: float
- **location long**: float
- **manipulation comments**: string
- **manipulation type**: string (categorical)
- **manually marked outlier**: boolean
- **sensor type**: string (categorical)
- **study name**: string
- **study site**: string
- **tag ID**: string
- **tag manufacturer name**: string
- **tag mass**: float
- **tag model**: string
- **tag readout method**: string (categorical)
- **timestamp**: datetime
- **visible**: boolean