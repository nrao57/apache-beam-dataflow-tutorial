# Overview

## Running Locally

```powershell
mvn compile exec:java -D exec.mainClass=org.apache.beam.examples.WordCount `
-D exec.args="--inputFile=sample.txt --output=counts" -P direct-runner
```

```bash
mvn compile exec:java -Dexec.mainClass=org.apache.beam.examples.WordCount \
    -Dexec.args="--inputFile=sample.txt --output=counts" -Pdirect-runner
```
