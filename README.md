# PCS Beratungscontor AG Example
## Example Project for SAP HANA Cloud Deployment and WebIDE Development
Introduction for setup: https://developers.sap.com/tutorials/hana-trial-advanced-analytics.html <br>
Example data source: https://github.com/SAP-samples/cloud-hana-shine-sp8 <br>

### Limitations of the SAP HANA Cloud
* HANA CDS is not supported with SAP HANA Cloud. Therefore HDB Tables are used for backward compatibility on any SAP HANA.

### Limitations of HDI Calculation Views
* HDI Calculation Views for integration in CompositeProvider are supported with BW/4HANA 2.0 (after setup in SPRO)

### Alternative to Git-based Repositories
* It's possible to use 'HTA for HDI' for developing HDI objects in ABAP development systems (not part of this setup)
* See also SAP Note 2569651

### Creating SAP HANA Cloud Instance
Space → SAP HANA Cloud → Create Database <br>

### Creating User-Provieded Service (HDI Containter to Non-HDI Container)
Space → Service Instances → Create Instance → Create User-Provided Service Instance <br>
grant-service.json as Template<br>
(The definition is later used in the pcs-example project, see also mta.yaml as cross-container-service-1) <br>

### Clone Project 
Right-Click Workspace → Git → Clone Repository <br>
https://github.com/scherbinek/pcs-example.git <br>
(Right-click imported project for the build process) <br>

### Open HDI Container
Right-click db → Open HDI Container

</p>