# DistributedVideoProcessor
A scalable video processor that adheres to a distributed environment

## Background

DistributedVideoProcessor (DVP) serves as a utility that abstracts out the challenges of scaling a video processor of any type.

This allows the DVP consumer to focus on the video processing task while leveraging DVP to scale the processing. 

Video process can be tasks such as:
- ML / deep learning ingestion
- ML / deep learning inference
- Computer vision tasks
- Cloud-accelerated video editing / rendering
- etc

## Features
- Support for injectable data stores
- Support for atomic transactions for video processing
- Multi-tenant support 
  - Isolation within the event queue between multiple videos 


## Implementation Details

![image](https://github.com/devalparikh/DistributedVideoProcessor/assets/13604973/b404397e-7c32-47df-9f70-911e9c1d82ef)


