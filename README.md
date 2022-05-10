Synthea Demo Data for med-united
==============

To load the given demo data execute the following commands

```
export BEARER_TOKEN=""
curl -d @hospitalInformation1652195897531.json -H "Content-Type: application/fhir+json; fhirVersion=4.0" -H "Authorization: Bearer $BEARER_TOKEN" https://fhir.med-united.health/fhir -v
curl -d @practitionerInformation1652195897531.json -H "Content-Type: application/fhir+json; fhirVersion=4.0" -H "Authorization: Bearer $BEARER_TOKEN" https://fhir.med-united.health/fhir -v
curl -d @Yong583_Greenholt190_8e59b17d-0637-dd3e-3140-d5da3af1e13a.json -H "Content-Type: application/fhir+json; fhirVersion=4.0" -H "Authorization: Bearer $BEARER_TOKEN" https://fhir.med-united.health/fhir -v
```
