# Changelog

## [v1.12.0](https://github.com/openebs/api/tree/v1.12.0) (2020-07-15)

**Merged pull requests:**

- refact\(cvr\): add builder to initialize cvr zvolworkers [\#57](https://github.com/openebs/api/pull/57) ([prateekpandey14](https://github.com/prateekpandey14))
- feat\(upgrade\): add upgradeTask CR definition [\#56](https://github.com/openebs/api/pull/56) ([shubham14bajpai](https://github.com/shubham14bajpai))
- feat\(cspi status\): add provisioned and healthy replica count in CSPI status [\#54](https://github.com/openebs/api/pull/54) ([mittachaitu](https://github.com/mittachaitu))

## [v1.11.0](https://github.com/openebs/api/tree/v1.11.0) (2020-06-15)

**Merged pull requests:**

- fix\(volume-mgmt\): handle mutual exclusion while updating istgt conf file [\#53](https://github.com/openebs/api/pull/53) ([mittachaitu](https://github.com/mittachaitu))
- fix\(backup, restore\): add backup and restore resources into known scheme [\#52](https://github.com/openebs/api/pull/52) ([mittachaitu](https://github.com/mittachaitu))
- feat\(backup, restore\): add backup and restore APIs [\#51](https://github.com/openebs/api/pull/51) ([mittachaitu](https://github.com/mittachaitu))
- feat\(migrate\): add migration related keys [\#50](https://github.com/openebs/api/pull/50) ([shubham14bajpai](https://github.com/shubham14bajpai))
- fix\(base path\): fix base path inside the containers [\#48](https://github.com/openebs/api/pull/48) ([mittachaitu](https://github.com/mittachaitu))
- fix\(cspi\): update the Capacity fields of CStorPoolInstance [\#47](https://github.com/openebs/api/pull/47) ([mittachaitu](https://github.com/mittachaitu))
- refact\(vendor\): remove unnecessary vendor deps [\#45](https://github.com/openebs/api/pull/45) ([prateekpandey14](https://github.com/prateekpandey14))

## [v1.10.0](https://github.com/openebs/api/tree/v1.10.0) (2020-05-15)

**Merged pull requests:**

- fix\(deps\): remove version dependency to openebs/maya [\#43](https://github.com/openebs/api/pull/43) ([prateekpandey14](https://github.com/prateekpandey14))
- fix\(SnapshotInfo\): Remove Used field under CVRs SnapshotInfo [\#42](https://github.com/openebs/api/pull/42) ([mittachaitu](https://github.com/mittachaitu))
- feat\(crd-gen\): automate the CRDs generation with OpenAPIV3 validations  [\#41](https://github.com/openebs/api/pull/41) ([prateekpandey14](https://github.com/prateekpandey14))
-  fix\(CSPI\): update type of Capacity field in CStorPoolInstanceBlockdevice [\#40](https://github.com/openebs/api/pull/40) ([mittachaitu](https://github.com/mittachaitu))
- chore\(volume replica\): add snapshot information in CVR status [\#39](https://github.com/openebs/api/pull/39) ([mittachaitu](https://github.com/mittachaitu))
- chore\(cspc\): add builder functions for cspc [\#38](https://github.com/openebs/api/pull/38) ([sonasingh46](https://github.com/sonasingh46))
- chore\(cspi\): add various conditions in CStorPoolInstance [\#37](https://github.com/openebs/api/pull/37) ([mittachaitu](https://github.com/mittachaitu))
- feat\(bdc\): update bdc builder with adding tag [\#36](https://github.com/openebs/api/pull/36) ([kmova](https://github.com/kmova))
- chore\(cspc\): update cspc api [\#35](https://github.com/openebs/api/pull/35) ([sonasingh46](https://github.com/sonasingh46))
- feat\(api\): add label selector in BDC spec [\#34](https://github.com/openebs/api/pull/34) ([akhilerm](https://github.com/akhilerm))
- feat\(apis\): add new fields into BlockDevice api [\#33](https://github.com/openebs/api/pull/33) ([akhilerm](https://github.com/akhilerm))
- chore\(cspi\): add zpool status type [\#32](https://github.com/openebs/api/pull/32) ([sonasingh46](https://github.com/sonasingh46))
- fix\(cspc\): fix json key of cspc resource [\#31](https://github.com/openebs/api/pull/31) ([sonasingh46](https://github.com/sonasingh46))
- oep\(volume\): propose enhancements for all cstorvolumes related APIs [\#30](https://github.com/openebs/api/pull/30) ([prateekpandey14](https://github.com/prateekpandey14))
- chore\(cvc\): rename cstorvolumeclaim to cstorvolumeconfig apis [\#29](https://github.com/openebs/api/pull/29) ([prateekpandey14](https://github.com/prateekpandey14))
- chore\(env\): make openebs service account configurable [\#28](https://github.com/openebs/api/pull/28) ([prateekpandey14](https://github.com/prateekpandey14))
- chore\(cspc\): change priority class field to pointer [\#27](https://github.com/openebs/api/pull/27) ([sonasingh46](https://github.com/sonasingh46))
- fix\(helper functions\): update helper functions to access updated API [\#25](https://github.com/openebs/api/pull/25) ([mittachaitu](https://github.com/mittachaitu))
- fix\(pool config\): update the ROThresholdLimit data type [\#24](https://github.com/openebs/api/pull/24) ([mittachaitu](https://github.com/mittachaitu))
- chore\(cstor\_pool\_apis\) : update cstor pool apis [\#23](https://github.com/openebs/api/pull/23) ([sonasingh46](https://github.com/sonasingh46))
- oep\(cstorpool\) : propose enhancements in cstor pool related APIs. [\#22](https://github.com/openebs/api/pull/22) ([sonasingh46](https://github.com/sonasingh46))
- fix\(apis\): fix changes for internal API's to generate conversion func [\#21](https://github.com/openebs/api/pull/21) ([mittachaitu](https://github.com/mittachaitu))
- feat\(ROThresholdLimit\): add support to set roThresholdLimit on CStor Pool API's [\#20](https://github.com/openebs/api/pull/20) ([mittachaitu](https://github.com/mittachaitu))
- fix\(cspi\): add required helper functions for cspi [\#19](https://github.com/openebs/api/pull/19) ([mittachaitu](https://github.com/mittachaitu))
- feat\(apis\): add lease API with leader elections [\#18](https://github.com/openebs/api/pull/18) ([prateekpandey14](https://github.com/prateekpandey14))
- chore\(apis\): add snapshot grpc APIs and server configs [\#17](https://github.com/openebs/api/pull/17) ([prateekpandey14](https://github.com/prateekpandey14))
- chore\(apis\): add k8s service APIs builder [\#16](https://github.com/openebs/api/pull/16) ([prateekpandey14](https://github.com/prateekpandey14))
- chore\(apis\): add utility func for APIs [\#15](https://github.com/openebs/api/pull/15) ([prateekpandey14](https://github.com/prateekpandey14))
- add constructor for volume struct [\#13](https://github.com/openebs/api/pull/13) ([sonasingh46](https://github.com/sonasingh46))
- feat\(apis\): add cstor volumes APIs builders and utils [\#12](https://github.com/openebs/api/pull/12) ([prateekpandey14](https://github.com/prateekpandey14))
- add deployment builder code [\#11](https://github.com/openebs/api/pull/11) ([sonasingh46](https://github.com/sonasingh46))
- chore\(volume\): update volume policy and claim with poolinfo [\#10](https://github.com/openebs/api/pull/10) ([prateekpandey14](https://github.com/prateekpandey14))
- add cspi filter functions [\#9](https://github.com/openebs/api/pull/9) ([sonasingh46](https://github.com/sonasingh46))
- fix\(ci\): set GOPATH env in github actions [\#8](https://github.com/openebs/api/pull/8) ([prateekpandey14](https://github.com/prateekpandey14))
- add cspi types [\#7](https://github.com/openebs/api/pull/7) ([sonasingh46](https://github.com/sonasingh46))
- Add GH actions and Makefile target to verify kubegen [\#6](https://github.com/openebs/api/pull/6) ([prateekpandey14](https://github.com/prateekpandey14))
- chore\(apis\): add zfs pool topology utils as internal apis [\#5](https://github.com/openebs/api/pull/5) ([prateekpandey14](https://github.com/prateekpandey14))
- refact\(apis\): add volume policy and volume config APIs [\#4](https://github.com/openebs/api/pull/4) ([prateekpandey14](https://github.com/prateekpandey14))
- refact\(utils\): add utility package [\#3](https://github.com/openebs/api/pull/3) ([prateekpandey14](https://github.com/prateekpandey14))
- add k8s vendor dpendency [\#2](https://github.com/openebs/api/pull/2) ([sonasingh46](https://github.com/sonasingh46))
- Add cstor apis [\#1](https://github.com/openebs/api/pull/1) ([sonasingh46](https://github.com/sonasingh46))


\* *This Changelog was automatically generated by [github_changelog_generator](https://github.com/github-changelog-generator/github-changelog-generator)*
