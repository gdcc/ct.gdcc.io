---
title: Home
---

## Motivation and goals

The Containerization Working Group aims to support running the [Dataverse software](https://dataverse.org) within [containers](https://kubernetes.io/docs/concepts/containers/).
Containers may be used in very different contexts such as development, testing, staging and production.
They also are a way to run the Dataverse software and its dependencies and integrations in enclosed units on different platforms of operating systems and/or hardware.
This working group aims to include many perspectives and use cases to make sure the Dataverse community's needs are covered.

## New features and bug fixes 🎁

- 2023-04-25 Application images (Dataverse, not just the base image) are being pushed to registries (Docker Hub and GitHub Container Registry). See <https://github.com/IQSS/dataverse/pull/9447> and [related discussion](https://dataverse.zulipchat.com/#narrow/stream/375812-containers/topic/push.20to.20registry).
- 2023-04-04 DOI JVM options can now be configured using MPCONFIG. See <https://github.com/IQSS/dataverse/pull/8828>.
- 2023-03-20 If you have Java and Maven installed, you can spin up Dataverse in Docker! See [dev usage][] and <https://github.com/IQSS/dataverse/pull/9439>.

[dev usage]: https://preview.guides.gdcc.io/en/develop/container/dev-usage.html

## Roadmap

We presented a roadmap as a [proposal](https://docs.google.com/document/d/14DHDB24Cp_kzpYqhHCKCtnzOw8_WuLOOONyqJHSsaYM/edit) as a series of milestone during the 2023-04-18 [Dataverse Community Call](https://dataverse.org/community-calls) ([notes](https://docs.google.com/document/d/1TmvLrvDJ2dtPN6e6Iu4RT-qFQo4XeR5Tn-TGhvB9mFE/edit?usp=sharing), [recording](https://harvard.zoom.us/rec/share/qQJLuOQYIX5FA5Fsandjuu3L4qIgmV9AKOZ0tZu3ZPcdDmcVw-2D7qn9VcCAojIk.PHPDAOdOWYI_hXCr)):

- Milestone A: For backend (Java) developers
- Milestone B: For API client testing
- Milestone C: For an integration/frontend developer (w/o Java)
- Milestone D: Improve developer experience
- Milestone E: Demo or evaluation
- Milestone F: Demo with some configurability
- Milestone G: Run API tests in containers

As we merge pull requests, we will update "new features" list above. We'll use the [Containerization](https://github.com/orgs/IQSS/projects/34/views/17) column of the Dataverse Global Backlog board to indicate specific issues or pull requests we plan to work on next.

## Working group meetings

We welcome anyone to join our meetings, which occur on Zoom using <https://harvard.zoom.us/j/91061519853?pwd=U1lQR1ExMlo3Ty9XUVJIM2ZPNW1mdz09> (except community calls).

- [2023-03-21, 15:00 UTC](https://time.is/compare/1500_21_Mar_2023_in_UTC) kickoff, during the [Dataverse Community Call](https://dataverse.org/community-calls) ([notes](https://docs.google.com/document/d/1r_GMYqYzUyQR2LQ2cqSLWPDuFRzd18PJ-4UFC4Nvnpw/edit#), [recording](https://harvard.zoom.us/rec/share/qb3gd3pboooRa9UHyLyIvPfxVgoahbGWFaxLdJDO2VD-MGMqWnZIsJjc3Rxao6Wu.-Y-CiwvgRwVj8v6c)).
- [2023-03-23, 14:00 UTC](https://time.is/compare/1400_23_Mar_2023_in_UTC) meeting ([notes](https://docs.google.com/document/d/1UmKajGpOH8tkvyEbgIYvHDKZBAMfdvCp8AZC0ZEEtWs/edit?usp=sharing), [recording](https://harvard.zoom.us/rec/share/kviiT4GO2zruomf0T-QHCWqDksK6jT525bPrENNGWf01MhLtZOS0mU3b6Gw-_usp.CnoqlfsFqvOhXEyY))
- [2023-03-30, 14:00 UTC](https://time.is/compare/1400_30_Mar_2023_in_UTC) meeting ([notes](https://docs.google.com/document/d/1Z1PUOp19zJVEGNcFsV7tqPErWQnkVV6qkDo5ZQUHMVM/edit?usp=sharing), [recording](https://harvard.zoom.us/rec/share/HsGlcXqaY-PR0pCWkZFzmmP6zus5pdXq4AlKhM4EgRTF-3OEB74wZhv7e7dueebp.RsriUxxBS4KYdSa3))
- [2023-04-06, 14:00 UTC](https://time.is/compare/1400_06_Apr_2023_in_UTC) meeting ([notes](https://docs.google.com/document/d/1YVIKW7stAiGwJtuijDlC85cBnBGdEsi_z0mJb0FOysw/edit?usp=sharing), [recording](https://harvard.zoom.us/rec/share/nv8YUZ4T0XwHLCJOZHTtNUORe5hhMSnpVnfDalAVgqM_i_OLnpttQHz-0wPDBOk.Cd-4oWXs-tJUaCg_))
- [2023-04-13, 14:00 UTC](https://time.is/compare/1400_13_Apr_2023_in_UTC) meeting ([notes](https://docs.google.com/document/d/1qmMRiXoRl_mKugD0qXynzep4pL0hHwCKHMBDF5jCtWs/edit?usp=sharing), [recording](https://harvard.zoom.us/rec/share/9tnJO4URrE9W1YnB3gu71LHadV480KFDZovxaPkOv0k6_0h9AAqzxej7_fEcD0an.uY_9scBGRb1YIVoW))
- [2023-04-18, 15:00 UTC](https://time.is/compare/1500_18_Apr_2023_in_UTC) during the [Dataverse Community Call](https://dataverse.org/community-calls) ([notes](https://docs.google.com/document/d/1TmvLrvDJ2dtPN6e6Iu4RT-qFQo4XeR5Tn-TGhvB9mFE/edit?usp=sharing), [recording](https://harvard.zoom.us/rec/share/qQJLuOQYIX5FA5Fsandjuu3L4qIgmV9AKOZ0tZu3ZPcdDmcVw-2D7qn9VcCAojIk.PHPDAOdOWYI_hXCr))
- 2023-04-20 no meeting!
- [2023-04-27, 14:00 UTC](https://time.is/compare/1400_27_Apr_2023_in_UTC) meeting ([notes](https://docs.google.com/document/d/1Hz47lLjE9h1-YE5zD2wu4tT1ObB6vB6Nr3m16pQ4LF4/edit?usp=sharing), recording)



## Get in touch

Please join us in [Zulip](https://dataverse.zulipchat.com/#narrow/stream/375812-containers/) (preferred) or [chat.dataverse.org](https://chat.dataverse.org).

## References

Outputs:

- [Draft Proposal](https://docs.google.com/document/d/14DHDB24Cp_kzpYqhHCKCtnzOw8_WuLOOONyqJHSsaYM/edit)
- [Dataverse Container Guide](https://guides.dataverse.org/en/latest/container/index.html) ([pre-release preview](https://preview.guides.gdcc.io/en/develop/container/index.html))

Existing prior containerization efforts:
- Dataverse on K8s: [gdcc/dataverse-kubernetes](https://github.com/gdcc/dataverse-kubernetes), [k8s-docs.gdcc.io](https://k8s-docs.gdcc.io)
   - Derived: [EOSC-synergy/dataverse-kubernetes](https://github.com/EOSC-synergy/dataverse-kubernetes/tree/5.12)
- Archive in a Box: [IQSS/dataverse-docker](https://github.com/IQSS/dataverse-docker)
- Docker All In One (AIO): [IQSS/dataverse/conf/docker-aio](https://github.com/IQSS/dataverse/tree/develop/conf/docker-aio)
- KU Leuven RDM Repository: [libis/rdm-build](https://github.com/libis/rdm-build)
- LIP Computing: [lip-computing/dataverse](https://gitlab.com/lip-computing/dataverse)
- Patrick Carlson: [PR 8709](https://github.com/IQSS/dataverse/pull/8709)
- NDS Labs Service Catalog: [nds-org/ndslabs-specs](https://github.com/nds-org/ndslabs-specs/blob/2.0.1/dataverse/dataverse.json)

## Improving this website

Please feel free open an issue or create a pull request at <https://github.com/gdcc/ct.gdcc.io>
