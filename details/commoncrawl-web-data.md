# CommonCrawl Web Data

**URL:** http://commoncrawl.org/the-data/get-started/

## Overview
CommonCrawl Web Data is a public, petabyte-scale repository of web crawl data collected over many years. It provides raw web page content and associated metadata from regular crawls of the public web, enabling large-scale analytics, research, and machine learning applications.

## Features
- **Long-term crawl history**  
  - Multiple named crawl releases from 2015 through 2025 (e.g., `CC-MAIN-2025-51`, `CC-MAIN-2025-47`, …, `CC-MAIN-2015-32`).  
  - Enables longitudinal and time-based analyses of web content.

- **Petabyte-scale web corpus**  
  - Large-scale collection of raw web pages and metadata.  
  - Suitable for big data processing, web mining, and training large models.

- **Public AWS S3 hosting**  
  - Data stored in Amazon S3 in region **`us-east-1`** (access from this region is mandatory for S3-based access).  
  - Accessible via `s3://commoncrawl/...` paths.  
  - Many AWS services (e.g., EMR) can directly consume the S3 paths, often with wildcard support.

- **S3 access recommendations**  
  - Access from within `us-east-1` to avoid inter-region data transfer charges and improve latency.  
  - Caution about using Elastic IPs or load balancers, which may incur additional routed traffic costs.  
  - On non-EMR Hadoop clusters, use the **S3A protocol** (e.g., `s3a://commoncrawl/...`) for improved compatibility and performance.

- **HTTP/HTTPS access without AWS account**  
  - Data can be downloaded directly over HTTPS via URLs of the form:  
    `https://data.commoncrawl.org/[path_to_file]`  
  - Compatible with standard HTTP download tools such as **cURL** and **wget**.  
  - No AWS account required for HTTP-based access.

- **AWS CLI integration**  
  - Data can be accessed and managed using the **AWS Command Line Interface**, pointing to the Common Crawl S3 bucket.  
  - Works with AWS services that support S3 as an input data source.

## Access Methods
- **From AWS (recommended for large-scale processing)**  
  - Region: `us-east-1`  
  - S3 URL scheme: `s3://commoncrawl/path_to_file`  
  - Hadoop (non-EMR): use `s3a://commoncrawl/path_to_file`.

- **From local machines or external clusters**  
  - HTTPS URL scheme: `https://data.commoncrawl.org/path_to_file`  
  - Use tools like `curl` or `wget` to download files.  
  - No AWS account needed for this method.

## Pricing
- The content provided does not specify explicit pricing plans.  
- Noted cost considerations relate to **AWS infrastructure charges** when accessing via S3 (e.g., inter-region data transfer, Elastic IP or load balancer traffic), which are billed by AWS, not by Common Crawl itself.