# doc2hpo

doc2hpo is a java spring mvc based webapp to parse clinical note and get the HPO for phenolyzer analysis.

## Getting Started
It is not enough to use this git repo to deploy the webapp.

### Prerequisites
- java version "1.8.0_144"
- apache-tomcat-9.0.5
- metamap-api-2.0.jar (Optional) (https://metamap.nlm.nih.gov/MainDownload.shtml)
- MetaMap 2016v2 Linux Version (https://metamap.nlm.nih.gov/MainDownload.shtml)
- Api key for ncbo annotator (http://data.bioontology.org/documentation)


### Configure
- Please change MetamapBinPath in config.properties
- Please change Api key for ncbo annotator in config.properties
- make sure metamap service is running (https://metamap.nlm.nih.gov/Docs/README.html)

## Versioning

V_0.1.2
## Authors

Cong Liu, Chi Yuan, Kai Wang, Chunhua Weng