# PCS Beratungscontor AG Sample
## Sample Project for SAP HANA Cloud Deployment and WebIDE Development

### Limitations of the SAP HANA Cloud
* HANA CDS is not supported with SAP HANA Cloud

### Creating SAP HANA Cloud Instance
Space -- SAP HANA Cloud -- Create Database <br>

### Creating User-Provieded Service (HDI Containter to Non-HDI Container)
Space -- Service Instances -- Create Instance -- Create User-Provided Service Instance <br>
grant-service.json <br>
(The definition is later used in the pcs-example project, see also mta.yaml as cross-container-service-1) <br> <br>

### Clone Project 
Right-Click Workspace -- Git -- Clone Repository <br>
https://github.com/scherbinek/pcs-example.git <br>
(Right-click imported project for the build process) <br>

### Open HDI Container
Right-click db -- Open HDI Container -- SQL Console <br>
Paste Inseert statements of /sql/01-insert-data.sql of the project
</p>
Source Data: https://github.com/SAP-samples/cloud-hana-shine-sp8