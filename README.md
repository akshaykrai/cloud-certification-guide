# Cloud Certification Guide

## Table of Contents
- Introduction
- Why get certified?
- List of Certifications
- Compiling short notes

## Introduction

Cloud Computing forms the infrastructual backbone of nearly every software application or project. 

This guide aims to allow professionals, both new and experienced, to obtain a structured approach to pursuing cloud certifications of their choice by providing:

- A curated list of short notes for every service
- Recommended list of courses and practice exams
- Other useful reading materials such as blogs, videos, etc.

## Why get certified?

One of the best way to learn about the cloud is to pursue the certifications offered by the major players in public cloud, namely Amazon Web Services, Microsoft Azure and Google Cloud Platform. The best teachers and guides are all ortiented around obtaining these certifications.

Other benefits include applying the learned knowledge to present projects, jumping to the next level in your current organization, appealing to recruits for future oppurtunites and of course, boasting rights!

## List of Certifications

The following certifications are included as part of this guide with more coming soon.

### Amazon Web Services (AWS)

01. [AWS Certified Cloud Practitioner](aws/cloud-practitioner/README.md)
02. [AWS Certified Developer – Associate](aws/developer-associate/README.md)
03. [AWS Certified SysOps Administrator – Associate](aws/sysops-adminstrator-associate/README.md)
04. [AWS Certified Solutions Architect – Associate](aws/solutions-architect-associate/README.md)
05. [AWS Certified Big Data – Specialty (Retired)](aws/big-data-specialty/README.md)

### Microsoft Azure

Coming Soon.

### Google Cloud Platform (GCP)

Coming Soon.

## Compiling short notes

If you wish to download & compile the short notes relevant for the exam of your choice, here's the steps to do the same:

1. Pull the repository into your local system.

```
git pull https://github.com/akshaykrai/cloud-certification-guide.git
```

2. Execute the 'create_guide.sh' script with the input parameters as the cloud provider followed by the the certification number.

For example, to compile the short notes of AWS Solutions Architect, use the following command:

```
sh cloud-certification-guide/code/create_guide.sh aws 1
```

This shall create a folder 'notes' in the repository under the appropriate folder for the input certification.

