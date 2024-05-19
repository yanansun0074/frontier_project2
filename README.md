# frontier_project2

This is a project for Frontier of Computation Journalism. 

Data sources: 
- DOB Now Issued Permits: https://data.cityofnewyork.us/Housing-Development/DOB-NOW-Build-Approved-Permits/rbx6-tga4/data_preview

| Colname  | meaning |
| ------------- | ------------- |
| Job Filling Number  | Unique identifier for each premit |
| Filling Reason  | "Initial Permit", "Renewal Permit Without Changes", "Renewal Permit with Changes", "No Work Permit"  |
| House No  | |
| Street Name |  |
| Borough | |
| BIN  | Building Identifier Number. Used to join with building footprints data |
| Work Type | Work type of permit. In this case, I filtered with "Sidewalk Shed" |
| Issued Date |  |
| Expired Date | |

- DOB Issued Permits: https://data.cityofnewyork.us/Housing-Development/DOB-Permit-Issuance/ipu4-2q9a/data_preview

| Colname  | meaning |
| ------------- | ------------- |
| Job #  | Unique identifier for each premit |
| House No  | |
| Street Name |  |
| Borough | |
| BIN  | Building Identifier Number. Used to join with building footprints data |
| Filling Status  | "INITIAL" "RENEWAL"  |
| Permit Type | Work type of permit. In this case, I filtered with "SH" |
| Issued Date |  |
| Expired Date | |
| LATITUDE |  |
| LONGITUDE | |

- Building Footprints: https://data.cityofnewyork.us/Housing-Development/Building-Footprints/nqwf-w8eh
  Used to join with DOB NOW with BIN to get geographical location



