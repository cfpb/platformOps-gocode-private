### CFPB PlatformOps EC 


## Installation

 - Install Go 
 - Set up GOPATH
 - Clone this repo to $GOPATH/src
 
----

## Evidence Collection (EC)

**Description**:  Evidence Collection project is written in Golang to support the automated process of collecting 
evidence from a set of baselines. 

**Project code structure**:

 ```
 - models/
        - baseline.go
        - control.go
        - manifest.go
 - services/
        - crudBaselineControl.go
        - readExcelBaseline.go
 - ec_agent.go
 - parse_Excel_convertTo_Json.go
 - parse_Excel_loadTo_Sql.go
```

## Dependencies

- github.com/tealeg/xlsx - Excel parser
- github.com/lib/pq - PostgreSQL Go driver

## Installation


## Configuration

- Please email __DL_CFPB_Platform_Operations_Team_ for configuration setup.

## Usage


## How to test the software


## Known issues


## Getting help


## Getting involved


----

## Open source licensing info
1. [TERMS](TERMS.md)
2. [LICENSE](LICENSE)
3. [CFPB Source Code Policy](https://github.com/cfpb/source-code-policy/)


----

## Credits and references
1. GoLang
2. Git
3. [Design Pattern - The Gang of Four](https://www.amazon.com/Design-Patterns-Object-Oriented-Addison-Wesley-Professional-ebook/dp/B000SEIBB8)
