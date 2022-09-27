# Untitled Workflow #28

## Description

test description

## Components

The present workflow is composed by the following unique components (Note that some components may be repeated):

### lifebitai_fastqc

**Description**: Quality control assessment of FastQ files using FastQC.\
**Inputs**: 1\
**Outputs**: 1\
**Parameters**: 0

### lifebitai_downsample

**Description**: Downsamples FastQ samples.\
**Inputs**: 1\
**Outputs**: 1\
**Parameters**: 1

## Inputs

- `--fastq`: FastQ files, which can be compressed or uncompressed
## Parameters

### Required



### Optional

- `--downsample_1.ratio`: Provide the desired estimated coverage as a ratio (e.g.: 50X)
    - **Component**: downsample_1 
    - Type: number
    - Default: `50` 

