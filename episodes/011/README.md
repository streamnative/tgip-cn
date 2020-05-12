# Episode 011: Deep dive into authentication and authorization

- Hosted by Sijie
- Recorded on 05/10/2020

![](/image/011.png)

## Table of Content

- 00:00:00 - Week in review
- 00:07:00 - Content
- 01:11:00 - Q&A

## Week in Review

- Apache Pulsar 2.5.2 release is coming
- PIP-63: [Readonly Topic Ownership](https://github.com/apache/pulsar/wiki/PIP-63%3A-Readonly-Topic-Ownership-Support)
- Upcoming webinar:
    - 05/26: "Lessons From Managing A Pulsar Cluster" by Shivji Kumar Jha from Nutanix
        - https://us02web.zoom.us/webinar/register/2015887356422/WN_gZqEn6KTRu25wh4d36bdCw


## Show Notes

- Understand Role
- Authentication: who are you?
- Authorization
    - superusers
    - tenant-admin
    - user roles: produce/consume/functions
- Enable Authentication/Authorization
    - Component by Component
- Role
    - Single Step
        - mTLS: common name
        - JWT: token subject
            - PIP-55
    - Multiple Steps
        - Kerberos

## Reference 

- Recorded video: https://www.bilibili.com/video/BV1T741147B6?p=10
- Tech blog: 
