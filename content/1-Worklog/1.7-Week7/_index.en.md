---
title: "Week 7: IAM Roles for EC2"
menuTitle: "Worklog Week 7"
date: 2026-09-28
weight: 7
chapter: false
pre: " <b>1.7.</b> "
---

**Period:** 28 September–2 October 2026

## Objectives

- Understand why applications on EC2 use IAM roles.
- Distinguish permission policies from trust policies.
- Study instance profiles and temporary credentials.
- Understand least privilege for application access.

## Daily learning activities

| Day | Learning activity | Start date | Completion date | Reference |
| --- | --- | --- | --- | --- |
| Monday | Read an introduction to IAM Roles for EC2 and study why applications need permissions to access AWS services. | 28/09/2026 | 28/09/2026 | [First Cloud AI Journey](https://cloudjourney.awsfcaj.com/) |
| Tuesday | Study permission policies attached to roles and read examples of allowed actions and resources. | 29/09/2026 | 29/09/2026 | [First Cloud AI Journey](https://cloudjourney.awsfcaj.com/) |
| Wednesday | Read about trust policies; distinguish who can assume a role from what the role is allowed to do. | 30/09/2026 | 30/09/2026 | [First Cloud AI Journey](https://cloudjourney.awsfcaj.com/) |
| Thursday | Study instance profiles and their relationship with IAM roles; read how applications obtain temporary credentials on EC2. | 01/10/2026 | 01/10/2026 | [First Cloud AI Journey](https://cloudjourney.awsfcaj.com/) |
| Friday | Compare IAM users and roles for application access; summarize least privilege and the reasons to avoid storing long-term access keys on servers. | 02/10/2026 | 02/10/2026 | [First Cloud AI Journey](https://cloudjourney.awsfcaj.com/) |

## Learning summary

- Understood how roles support AWS service access for applications on EC2.
- Distinguished permission policies from trust policies.
- Understood the purpose of an instance profile.
- Learned why temporary credentials are used and refreshed.
- Understood that AWS SDK credential providers can obtain credentials without hard-coded keys.
- Distinguished AWS service permissions from operating system login access.
- Learned to limit permissions to the required actions and resources.

This week's reading connected my IAM and EC2 knowledge and clarified how applications receive permissions through roles.
