## Read More

- [Apache Beam Go SDK Quickstart](https://beam.apache.org/get-started/quickstart-go/)

## Windows Tools

- PowerShell (cross-platform)
- Git
- Chocolatey (Windows Package Manager)

## Install Go

```PowerShell
choco install golang -y
refreshenv
choco list --local-only 
```

## Verify

```PowerShell
go version
```

Review the installed files at C:\Program Files\Go.

## Get Beam Go SDK

```PowerShell
go get -u github.com/apache/beam/sdks/v2/go/pkg/beam
```

## Run WordCount Example

```PowerShell
go install github.com/apache/beam/sdks/v2/go/examples/wordcount@latest
wordcount --input <PATH_TO_INPUT_FILE> --output counts
```
