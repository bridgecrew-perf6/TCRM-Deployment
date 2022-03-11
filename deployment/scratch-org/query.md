# Querying Scratch org

## Query

```
cat ~/.soql/scratchOrg.soql
```

```sql
SELECT Name ,IsDeleted,CreatedDate,LastViewedDate,LastReferencedDate,Edition,OrgName,DurationDays 
FROM ScratchOrgInfo

```


## Example
```
sfdx mohanc:data:query -q ~/.soql/scratchOrg.soql -u mohan.chinnappan.n_ea2@gmail.com -f json
```

```json
[
    {
        "attributes": {
            "type": "ScratchOrgInfo",
            "url": "/services/data/v53.0/sobjects/ScratchOrgInfo/2SR3h000000YAvqGAG"
        },
        "Name": "00000002",
        "IsDeleted": false,
        "CreatedDate": "2021-10-26T16:25:30.000+0000",
        "LastViewedDate": null,
        "LastReferencedDate": null,
        "Edition": "Developer",
        "OrgName": "mchinnappan company",
        "DurationDays": null
    },
    {
        "attributes": {
            "type": "ScratchOrgInfo",
            "url": "/services/data/v53.0/sobjects/ScratchOrgInfo/2SR3h000000YAvvGAG"
        },
        "Name": "00000003",
        "IsDeleted": false,
        "CreatedDate": "2021-10-26T16:27:25.000+0000",
        "LastViewedDate": null,
        "LastReferencedDate": null,
        "Edition": "Developer",
        "OrgName": "mchinnappan company",
        "DurationDays": null
    },
    {
        "attributes": {
            "type": "ScratchOrgInfo",
            "url": "/services/data/v53.0/sobjects/ScratchOrgInfo/2SR3h000000YAvlGAG"
        },
        "Name": "00000001",
        "IsDeleted": false,
        "CreatedDate": "2021-10-26T16:24:33.000+0000",
        "LastViewedDate": null,
        "LastReferencedDate": null,
        "Edition": "Developer",
        "OrgName": "mchinnappan company",
        "DurationDays": null
    }
]
```
