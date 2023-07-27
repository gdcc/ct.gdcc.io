---
title: Home
---

## Motivation and goals

The Containerization Working Group aims to support running the [Dataverse software](https://dataverse.org) within [containers](https://kubernetes.io/docs/concepts/containers/).
Containers may be used in very different contexts such as development, testing, staging and production.
They also are a way to run the Dataverse software and its dependencies and integrations in enclosed units on different platforms of operating systems and/or hardware.
This working group aims to include many perspectives and use cases to make sure the Dataverse community's needs are covered.

## New features, bug fixes, and use cases 🎁

- 2023-07-25 Experimental API test runner: <https://github.com/pdurbin/dataverse-api-test-runner>
- 2023-07-18 Frontend end to end tests are using containers. See <https://github.com/IQSS/dataverse-frontend/pull/131>
- 2023-06-23 Lots of documentation enhancements, fulfilling milestone A as well See [PR#9584](https://github.com/IQSS/dataverse/pull/9584) and [dev usage][]
- 2023-06-12 Container-based dev environment for the new React frontend. See [docs](https://github.com/IQSS/dataverse-frontend#local-development-environment), [PR#87](https://github.com/IQSS/dataverse-frontend/pull/87), and [PR#112](https://github.com/IQSS/dataverse-frontend/pull/112).
- 2023-06-01 Config Baker image to streamline tasks in Dataverse setup like bootstrapping. See [Config Baker docs][] and [PR#9574](https://github.com/IQSS/dataverse/pull/9574).
- 2023-05-08 Enable publishing preview application images to ghcr.io for pull requests from forks (`/push-image`). See [PR#9575](https://github.com/IQSS/dataverse/pull/9575) for details.
- 2023-04-25 Application images (Dataverse, not just the base image) are being pushed to registries (Docker Hub and GitHub Container Registry). See [PR#9447](https://github.com/IQSS/dataverse/pull/9447) and [related discussion](https://dataverse.zulipchat.com/#narrow/stream/375812-containers/topic/push.20to.20registry).
- 2023-04-04 DOI JVM options can now be configured using MPCONFIG. See [PR#8828](https://github.com/IQSS/dataverse/pull/8828).
- 2023-03-20 If you have Java and Maven installed, you can spin up Dataverse in Docker! See [dev usage][] and [PR#9439](https://github.com/IQSS/dataverse/pull/9439).

[config baker docs]: https://preview.guides.gdcc.io/en/develop/container/configbaker-image.html
[dev usage]: https://preview.guides.gdcc.io/en/develop/container/dev-usage.html

## Roadmap

We presented a roadmap as a [proposal](https://docs.google.com/document/d/14DHDB24Cp_kzpYqhHCKCtnzOw8_WuLOOONyqJHSsaYM/edit) as a series of milestone during the 2023-04-18 [Dataverse Community Call](https://dataverse.org/community-calls) ([notes](https://docs.google.com/document/d/1TmvLrvDJ2dtPN6e6Iu4RT-qFQo4XeR5Tn-TGhvB9mFE/edit?usp=sharing), [recording](https://harvard.zoom.us/rec/share/qQJLuOQYIX5FA5Fsandjuu3L4qIgmV9AKOZ0tZu3ZPcdDmcVw-2D7qn9VcCAojIk.PHPDAOdOWYI_hXCr)):

- Milestone A: For backend (Java) developers (✅)
- Milestone B: For API client testing (✅)
- Milestone C: For an integration/frontend developer (w/o Java) (70%)
- Milestone D: Improve developer experience (10%)
- Milestone E: Demo or evaluation (0%)
- Milestone F: Demo with some configurability (0%)
- Milestone G: Run API tests in containers (0%)

As we merge pull requests, we will update "new features" list above. We'll use the [Containerization](https://github.com/orgs/IQSS/projects/34/views/17) column of the Dataverse Global Backlog board to indicate specific issues or pull requests we plan to work on next.

## Working group meetings

We welcome anyone to join our meetings! We meet on Thursdays at 9:30am Eastern Time (ET).

The Zoom link is <https://harvard.zoom.us/j/91061519853?pwd=U1lQR1ExMlo3Ty9XUVJIM2ZPNW1mdz09>

- [2023-07-27, 09:30 Eastern](https://time.is/compare/0930_27_July_2023_in_Boston) meeting ([notes](https://docs.google.com/document/d/1RUtQxnadwTPnWf1x3h1bYQ0sh-sG-rGP93Pf0eHETng/edit?usp=sharing) [recording](https://harvard.zoom.us/rec/share/HjZX8HPCyNkvkc1tj6NAxkEMtA_5348Hl8jhCyRyarNNiVztpbUe6oS1UVMZeNs9.NGmm8VnIQh44GwNU))
- [2023-07-20, 09:30 Eastern](https://time.is/compare/0930_20_July_2023_in_Boston) meeting ([notes](https://docs.google.com/document/d/1fGXOKvqJ570XtvCi-6IfUzi3e67s-8XYBz2f8LrtGtM/edit?usp=sharing), [recording](https://harvard.zoom.us/rec/share/nA5CV9wlzjjxaLg3jad-TVCS-Ebc-5HFmC7WcGRRfIGNZA5qjJQgzKwWju9IiBy2.W2A6tuUnCltRdyNd))
- [2023-07-13, 09:30 Eastern](https://time.is/compare/0930_13_July_2023_in_Boston) meeting ([notes](https://docs.google.com/document/d/1NNHuu8pVZmDkNf-decFWHYeo94ZcHX6PauurrACOsU8/edit?usp=sharing), [recording](https://harvard.zoom.us/rec/share/CXBDjG3otG8GuQhYXwjApwTmAP-992Kcy2DWm_DhYN97sQVyrkntsNnLUuUgFsdP.kw0bKkHS1x6jR56i))
- [2023-06-15, 09:30 Eastern](https://time.is/compare/0930_15_June_2023_in_Boston) meeting ([notes](https://docs.google.com/document/d/1Ajoz1TqmeVUQTp6LMP5xP5l5vaiKtlg65mqW3Ep3prI/edit?usp=sharing), [recording](https://harvard.zoom.us/rec/share/X8n8doyhW9jHftXdLVz5yc1NpfOmg4kT-3gfu9jk0tISTYiAL9e3H1GhpV7R7O3P.SWZQyUoaM0KRMKv9))
- 2023-06-07: meeting at #dataverse2023 ([notes](https://docs.google.com/document/d/1bjQtkE8e67suNKQvgXPJm2-5TCVpvz8UAOk6626TJEY/edit?usp=sharing))
- [2023-05-25, 09:30 Eastern](https://time.is/compare/0930_25_May_2023_in_Boston) meeting ([notes](https://docs.google.com/document/d/11wz1xZuzX5SnaGyrJJM8ogCzdgORIdhWfMMpUyDhXUA/edit?usp=sharing), [recording](https://harvard.zoom.us/rec/share/ipvR-ue7MuZ8QEVo0BmykWtCk17HbEGf_FyuN9Djxh_u0gBmA4uIBNZ2racARA2n.iL9gDYgDac-ag9qn))
- [2023-05-18, 09:30 Eastern](https://time.is/compare/0930_18_May_2023_in_Boston) meeting ([notes](https://docs.google.com/document/d/1VuUkGSdL03nPPMepYUMk59qEfljgRkzN0oXvEp9UkqI/edit?usp=sharing), [recording](https://harvard.zoom.us/rec/share/QZ4XDtwJrVjTAI5o_TgnyNjV8LDPYMjrVWiN5Mz0o3u3CXctJj06HVhDprNDTt9T.pKy533mltH4GH07N))
- [2023-05-11, 09:30 Eastern](https://time.is/compare/0930_11_May_2023_in_Boston) meeting ([notes](https://docs.google.com/document/d/1eQVm88dP2rgM9DKn4ivoWBx6MOK6aXfkLhsZN-Y3fsc/edit?usp=sharing), [recording](https://harvard.zoom.us/rec/share/1kOYrK9YRTDPv2OYES_doujAWbEyOp3hNHkcBR_iH4HvAFGYjfdoKADz0Xa1WHP3.nmdgF82lfLUQY_uN))
- [2023-05-04, 14:00 UTC](https://time.is/compare/1400_4_May_2023_in_UTC) meeting ([notes](https://docs.google.com/document/d/1U3yvg9yG5Wnm_tQkDLf5XyREYyFVoRE4_-UvnxuryVE/edit?usp=sharing), [recording](https://harvard.zoom.us/rec/share/YcaITLENsu8xdvaH6XmxENjd00TCeTzI_pIpBVMi97Nyj176C96kPsIjaEtLclG_.pSX9c_GjP79zKdZH))
- [2023-04-27, 14:00 UTC](https://time.is/compare/1400_27_Apr_2023_in_UTC) meeting ([notes](https://docs.google.com/document/d/1Hz47lLjE9h1-YE5zD2wu4tT1ObB6vB6Nr3m16pQ4LF4/edit?usp=sharing), [recording](https://harvard.zoom.us/rec/share/aBdeEowQUqdKH2H9aTF_ypWe1OI3SZj6t4m_KUJi0Sjui2e7g123GnI92Itij2fV.Vi1OWvqiXVJjbRgz))
- [2023-04-18, 15:00 UTC](https://time.is/compare/1500_18_Apr_2023_in_UTC) during the [Dataverse Community Call](https://dataverse.org/community-calls) ([notes](https://docs.google.com/document/d/1TmvLrvDJ2dtPN6e6Iu4RT-qFQo4XeR5Tn-TGhvB9mFE/edit?usp=sharing), [recording](https://harvard.zoom.us/rec/share/qQJLuOQYIX5FA5Fsandjuu3L4qIgmV9AKOZ0tZu3ZPcdDmcVw-2D7qn9VcCAojIk.PHPDAOdOWYI_hXCr))
- [2023-04-13, 14:00 UTC](https://time.is/compare/1400_13_Apr_2023_in_UTC) meeting ([notes](https://docs.google.com/document/d/1qmMRiXoRl_mKugD0qXynzep4pL0hHwCKHMBDF5jCtWs/edit?usp=sharing), [recording](https://harvard.zoom.us/rec/share/9tnJO4URrE9W1YnB3gu71LHadV480KFDZovxaPkOv0k6_0h9AAqzxej7_fEcD0an.uY_9scBGRb1YIVoW))
- [2023-04-06, 14:00 UTC](https://time.is/compare/1400_06_Apr_2023_in_UTC) meeting ([notes](https://docs.google.com/document/d/1YVIKW7stAiGwJtuijDlC85cBnBGdEsi_z0mJb0FOysw/edit?usp=sharing), [recording](https://harvard.zoom.us/rec/share/nv8YUZ4T0XwHLCJOZHTtNUORe5hhMSnpVnfDalAVgqM_i_OLnpttQHz-0wPDBOk.Cd-4oWXs-tJUaCg_))
- [2023-03-30, 14:00 UTC](https://time.is/compare/1400_30_Mar_2023_in_UTC) meeting ([notes](https://docs.google.com/document/d/1Z1PUOp19zJVEGNcFsV7tqPErWQnkVV6qkDo5ZQUHMVM/edit?usp=sharing), [recording](https://harvard.zoom.us/rec/share/HsGlcXqaY-PR0pCWkZFzmmP6zus5pdXq4AlKhM4EgRTF-3OEB74wZhv7e7dueebp.RsriUxxBS4KYdSa3))
- [2023-03-23, 14:00 UTC](https://time.is/compare/1400_23_Mar_2023_in_UTC) meeting ([notes](https://docs.google.com/document/d/1UmKajGpOH8tkvyEbgIYvHDKZBAMfdvCp8AZC0ZEEtWs/edit?usp=sharing), [recording](https://harvard.zoom.us/rec/share/kviiT4GO2zruomf0T-QHCWqDksK6jT525bPrENNGWf01MhLtZOS0mU3b6Gw-_usp.CnoqlfsFqvOhXEyY))
- [2023-03-21, 15:00 UTC](https://time.is/compare/1500_21_Mar_2023_in_UTC) kickoff, during the [Dataverse Community Call](https://dataverse.org/community-calls) ([notes](https://docs.google.com/document/d/1r_GMYqYzUyQR2LQ2cqSLWPDuFRzd18PJ-4UFC4Nvnpw/edit#), [recording](https://harvard.zoom.us/rec/share/qb3gd3pboooRa9UHyLyIvPfxVgoahbGWFaxLdJDO2VD-MGMqWnZIsJjc3Rxao6Wu.-Y-CiwvgRwVj8v6c)).

## Get in touch

We love to hear feedback from you about our goals and outputs not just during meetings, but also using chat.

[![](imgs/zulip.png){: height="30" }](https://dataverse.zulipchat.com/#narrow/stream/375812-containers/) [![](imgs/matrix.png){: height="30" }](https://chat.dataverse.org)

Please join us in [Zulip](https://dataverse.zulipchat.com/#narrow/stream/375812-containers/) (preferred) or [chat.dataverse.org](https://chat.dataverse.org).

## References

Outputs:

- [Dataverse Containerization](https://docs.google.com/document/d/14DHDB24Cp_kzpYqhHCKCtnzOw8_WuLOOONyqJHSsaYM/edit) Proposal/Roadmap
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
