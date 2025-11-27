# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [3.2.0](https://github.com/lotusnoir/ansible-system_ldap_users/compare/3.1.0...3.2.0) - 2025-11-26

### Commits

- update main to include success flag at the end to be able to monitor last playbook run [`65060bd`](https://github.com/lotusnoir/ansible-system_ldap_users/commit/65060bd1ff6c07c17dcf844ec95e519e14aa69b5)

## [3.1.0](https://github.com/lotusnoir/ansible-system_ldap_users/compare/3.0.0...3.1.0) - 2025-11-18

### Commits

- fix molecule test image for rhel8 [`f3fa563`](https://github.com/lotusnoir/ansible-system_ldap_users/commit/f3fa5637261edebba027dfb9e4f46b05b8617dde)
- update core and molecule [`94010da`](https://github.com/lotusnoir/ansible-system_ldap_users/commit/94010da85d03f59df2f88d1a9a79abc0400615c7)
- add oraclelinux10 support + lint and core fixes [`c9ded1c`](https://github.com/lotusnoir/ansible-system_ldap_users/commit/c9ded1c898356ecec55202ba38b4f9850de7fb67)

## [3.0.0](https://github.com/lotusnoir/ansible-system_ldap_users/compare/2.0.0...3.0.0) - 2025-10-29

### Commits

- add trixie (debian13) support [`269497f`](https://github.com/lotusnoir/ansible-system_ldap_users/commit/269497f9a3492e09754e5f5f66936ddfadc2d223)
- update core, molecule + gitlab-ci [`b54fad9`](https://github.com/lotusnoir/ansible-system_ldap_users/commit/b54fad9a9d6fe92d7d98944e28eb6b970ce9667e)
- fix lint [`40f6f82`](https://github.com/lotusnoir/ansible-system_ldap_users/commit/40f6f828fb541186aa10e0efe8bc0603156c739c)
- fix molecule paralelism and little updates [`1031c2c`](https://github.com/lotusnoir/ansible-system_ldap_users/commit/1031c2c00d9e9442a6e2da476067fc15da91a902)
- add support for ubuntu24 [`32ec735`](https://github.com/lotusnoir/ansible-system_ldap_users/commit/32ec7353802d10a908cb69a7bdf1ce71c6fdbf9a)
- add version on molecule play image to maintain support on old release [`a2ba1b6`](https://github.com/lotusnoir/ansible-system_ldap_users/commit/a2ba1b6967eb1c3c9e8fcdefa69614ef88ff7ad6)
- update molecule [`17d953b`](https://github.com/lotusnoir/ansible-system_ldap_users/commit/17d953b1fa4437a4ca7d63099f55ed9b276182e6)
- add redhat 9 to default supported distrib [`a3f5d20`](https://github.com/lotusnoir/ansible-system_ldap_users/commit/a3f5d20f53d37ba70de77e19b2d35c101680921e)
- add redhat 8 to default supported distrib [`703ef23`](https://github.com/lotusnoir/ansible-system_ldap_users/commit/703ef236949eb8f983d96340ae7d26130a619c4c)
- sort testing distrib to avoid random changes [`6f6d994`](https://github.com/lotusnoir/ansible-system_ldap_users/commit/6f6d99415c999422f929c091ef22057cd8b03511)

## [2.0.0](https://github.com/lotusnoir/ansible-system_ldap_users/compare/1.1.0...2.0.0) - 2023-09-25

### Commits

- update vars [`801bd8c`](https://github.com/lotusnoir/ansible-system_ldap_users/commit/801bd8cf24b80b0d49968f96f4fbd6c8ab80b1bf)
- update readme + precommit + include vars [`44889d1`](https://github.com/lotusnoir/ansible-system_ldap_users/commit/44889d1122059b14b7f3a91e77aa8b23f86324f3)
- change import tasks to include in order to support facts on name [`048fa56`](https://github.com/lotusnoir/ansible-system_ldap_users/commit/048fa56e45c56add1da8d0f1dc1a98269f4d02df)

## [1.1.0](https://github.com/lotusnoir/ansible-system_ldap_users/compare/1.0.0...1.1.0) - 2023-06-14

### Commits

- remove debian stretch [`1ec22b9`](https://github.com/lotusnoir/ansible-system_ldap_users/commit/1ec22b927320af3c54805939d84dcb6d0d599598)

## [1.0.0](https://github.com/lotusnoir/ansible-system_ldap_users/compare/0.3.0...1.0.0) - 2023-03-23

### Commits

- add code of conduc and small changes [`dc7d9e5`](https://github.com/lotusnoir/ansible-system_ldap_users/commit/dc7d9e56edad6765d50fe493c1477ebbdcd9e971)
- add precommit for lint [`85e531c`](https://github.com/lotusnoir/ansible-system_ldap_users/commit/85e531c1fdd7c8b9e85cf9e87aa110da78c092a3)
- fix checks [`b292f1b`](https://github.com/lotusnoir/ansible-system_ldap_users/commit/b292f1bc0a0a8b35cbdbade9bac6a4e7d41e1d44)
- add new molecule all scenario [`632d818`](https://github.com/lotusnoir/ansible-system_ldap_users/commit/632d8183364b8114a6138e0d2c51e062bb6aa325)
- split distro for molecule tests on ci [`d0b1b2b`](https://github.com/lotusnoir/ansible-system_ldap_users/commit/d0b1b2b70013264e544bc25b23bd1e0999e04122)
- update checks and Readme [`f5fc875`](https://github.com/lotusnoir/ansible-system_ldap_users/commit/f5fc87546c1a11b9cfa77b7ee54ee180c9c71799)
- remove verify [`513602e`](https://github.com/lotusnoir/ansible-system_ldap_users/commit/513602e030b7fc47c7538a303ad9dbbffe6ad569)
- update checks [`10765e2`](https://github.com/lotusnoir/ansible-system_ldap_users/commit/10765e23b1ec064106b46e9ce8105d1ea2154425)
- fix test and pipeline [`92b7eac`](https://github.com/lotusnoir/ansible-system_ldap_users/commit/92b7eacf7d5ca1f7552ee1b953031849e4328c83)
- fix: molecule image and optimize scenario [`0296493`](https://github.com/lotusnoir/ansible-system_ldap_users/commit/0296493b30e2633c102be241303995cecdb8a5cd)

## [0.3.0](https://github.com/lotusnoir/ansible-system_ldap_users/compare/0.2.0...0.3.0) - 2022-07-01

### Commits

- minor: add oracleLinux7 support [`8429ad9`](https://github.com/lotusnoir/ansible-system_ldap_users/commit/8429ad951af6a71905b42044c0222759e5c07b33)
- minor: add oracleLinux support + little fixes [`756ab80`](https://github.com/lotusnoir/ansible-system_ldap_users/commit/756ab80d5201b6321fb2672ee048177806d22d4b)

## [0.2.0](https://github.com/lotusnoir/ansible-system_ldap_users/compare/0.1.1...0.2.0) - 2022-06-02

### Commits

- minor: add ubuntu 22 molecule test + fix lint [`f2f371f`](https://github.com/lotusnoir/ansible-system_ldap_users/commit/f2f371f2c6a3748ba0586c9d56dab59a7cc0993e)

## [0.1.1](https://github.com/lotusnoir/ansible-system_ldap_users/compare/0.1.0...0.1.1) - 2022-03-16

### Commits

- fix: remove centos8 from molecule + fix graphic on README [`435e303`](https://github.com/lotusnoir/ansible-system_ldap_users/commit/435e303886444cca7ce409de2fba818a108e9edc)
- fix: problem with shell command + add stretch support [`39da2b1`](https://github.com/lotusnoir/ansible-system_ldap_users/commit/39da2b14b820c6dd8735e7962f6314f32055e838)
- fix: remove unsupported centos8 + minor fixes [`0666182`](https://github.com/lotusnoir/ansible-system_ldap_users/commit/0666182006afadef8e2d19cad80cf8709dc6ef8a)

## 0.1.0 - 2021-11-18

### Commits

- fix: Changes on README + molecule container names [`03263bc`](https://github.com/lotusnoir/ansible-system_ldap_users/commit/03263bc8d423f3cffbdee61939897e3763f4e160)
- fix: add role name on molecule container names to avoid concurrent conflict on runners [`c4665eb`](https://github.com/lotusnoir/ansible-system_ldap_users/commit/c4665ebbc4874ce2ccac175a74d1ea79ab89878c)
