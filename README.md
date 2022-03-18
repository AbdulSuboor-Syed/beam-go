# beam-go

## To check the version of GO 

go version in powershell

## To get sdk

go get -u github.com/apache/beam/sdks/v2/go/pkg/beam

## Downloading wordcount

go mod tidy(I entered this command as I was experiencing some errors)
go install github.com/apache/beam/sdks/v2/go/examples/wordcount


## Execution commands

wordcount --input sample.txt --output AbdulSuboorCounts.txt
