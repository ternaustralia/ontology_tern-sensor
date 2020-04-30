# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).


## [0.0.12] - 2020-04-16
### Added
- tern-ssn:ImagingRadar
- tern-ssn:Lidar


## [0.0.11] - 2020-04-16
### Changed
- tern-ssn:EarthObservingSatellite to tern-ssn:EarthObservationSatellite same as naming in GCMD.
### Added
- tern-ssn:CosmOzSite


## [0.0.10] - 2020-04-15
### Removed
- Mobile platform class
### Changed
- tern-ssn:Satellite to tern-ssn:EarthObservingSatellite


## [0.0.9] - 2020-04-08
### Removed
- tern-ssn:Variable
### Added
- tern-ssn:Parameter


## [0.0.8] - 2020-04-08
### Removed
- tern-ssn:QuantitativeVariable
### Added
- tern-ssn:CategoricalVariable


## [0.0.7] - 2020-04-06
### Changed
- tern-ssn:FixedPlatform to tern-ssn:InSituLandBasedPlatform
- tern-ssn:WeatherStation to tern-ssn:AutomaticWeatherStation
- tern-ssn:Site to tern-ssn:EcologySite
- tern-ssn:Drone to tern-ssn:UAV
### Added
- tern-ssn:CORVEGSite
- tern-ssn:SurveillanceSite
- tern-ssn:SoilMoisturePlatform


## [0.0.6] - 2020-03-27
### Added
- tern-ssn:ObservationTheme


## [0.0.5] - 2020-03-27
### Added
- Import of ssn-ext ontology for sosa:hasUltimateFeatureOfInterest
- sosa:ObservableProperty
- sosa:Procedure
- tern-ssn:Variable
- tern-ssn:Method
- tern-ssn:QuantitativeVariable


## [0.0.4] - 2020-03-24
### Added
- tern-ssn:ozfluxID
- Class restrictions for tern-ssn:Site


## [0.0.3] - 2020-03-23
### Changed
- Moved restrictions for class tern-ssn:FixedPlatform for properties tern-ssn:igbpCode and tern-ssn:climateCode to tern-ssn:EddyCovarianceFluxTower
### Added
- tern-ssn:locationDescription
- tern-ssn:Site class restriction


## [0.0.2] - 2020-03-23
### Added
- Class restrictions for sosa:Platform and its subclasses. 
- tern-ssn:landOwnershipType
- tern-ssn:fluxnetID
- tern-ssn:terrainType
- tern-ssn:powerSupplyType
- tern-ssn:DroneCampaign
- tern-ssn:hasDrone
- Class restrictions for ssn:Deployment
- Class restrictions for prov classes Entity and Activity
- Class restrictions for tern-ssn:SensorConfiguration and tern-ssn:Calibration
- tern-ssn:hasConfiguration
- tern-ssn:hasCalibration
- tern-ssn:SensorConfiguration
- tern-ssn:Calibration
- tern-ssn:sensorConfigurationValue
- tern-ssn:averageDataInterval
- tern-ssn:measurementInterval
- tern-ssn:sensorCalibrationValue
- tern-ssn:calibrationOffset
- tern-ssn:calibrationSlope
- tern-ssn:deploymentType
- tern-ssn:deploymentHeight
- tern-ssn:deploymentDepth
- tern-ssn:deploymentOrientation
- schema:location



## [0.0.1] - 2020-02-12
### Added
- Initial release.