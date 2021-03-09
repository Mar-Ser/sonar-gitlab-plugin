## Version 4.0.1

### Changed
- Adding support for NONE in QualityGateFailMode [#206](https://github.com/gabrie-allaigre/sonar-gitlab-plugin/pull/206)
- Adding GitLab Merge Request discussions [#216](https://github.com/gabrie-allaigre/sonar-gitlab-plugin/pull/216)

### Fixed
- Fix new rule type [#183](https://github.com/gabrie-allaigre/sonar-gitlab-plugin/pull/183)
- Code Quality Descriptions [#208](https://github.com/gabrie-allaigre/sonar-gitlab-plugin/pull/208)
- Make sure that ReporterBuilder is available during batch [#214](https://github.com/gabrie-allaigre/sonar-gitlab-plugin/pull/214)
- When more than one inline comment issue then display them as a list [#230](https://github.com/gabrie-allaigre/sonar-gitlab-plugin/issues/230)

## Version 4.0.0

**This version is directly in the SonarQube update center, only SonarQube >= 7.0**

### Changed
- Update to sonarqube 7.0 plugin version

### Fixed
- Using properties instead of depending on the deprecated, work with SonarQube 7.2 [#164](https://github.com/gabrie-allaigre/sonar-gitlab-plugin/pull/164) (Thanks dmarin)
- Fix others deprecated
- Fix sonar issues limit 10000 [#140](https://github.com/gabrie-allaigre/sonar-gitlab-plugin/issues/140)
- Fix disable proxy if proxy is enable in system [#168](https://github.com/gabrie-allaigre/sonar-gitlab-plugin/issues/168)

**[Download 4.0.0](https://github.com/gabrie-allaigre/sonar-gitlab-plugin/releases/download/4.0.0/sonar-gitlab-plugin-4.0.0.jar)**

## Version 3.0.2

**This version is directly in the SonarQube update center, only SonarQube 6.7**

### Changed
- Only for SonarQube 6.7

### Fixed
- Fix sonar issues limit 10000 [#140](https://github.com/gabrie-allaigre/sonar-gitlab-plugin/issues/140)
- Add test for covorage

**[Download 3.0.2](https://github.com/gabrie-allaigre/sonar-gitlab-plugin/releases/download/3.0.2/sonar-gitlab-plugin-3.0.2.jar)**

## Version 3.0.1

### Changed
- Support unit test sources #104
- Show user token in project config #89

### Fixed
- Fix bug with QualityGate status NONE #107

**[Download 3.0.1](https://github.com/gabrie-allaigre/sonar-gitlab-plugin/releases/download/3.0.1/sonar-gitlab-plugin-3.0.1.jar)**

## Version 3.0.0

**This version is directly in the SonarQube update center, only SonarQube < 6.7**

### Changed
- Api v4 is now default value
- For publish mode, get quality gate and print in global comment
- For publish mode, get all new issues and print in inline and global comment
- For publish mode, build breaker (status or exit) if quality gate is error or warn (option)
- Add json report for GitLab EE, codeclimate or sast
- Add filter for issues
- Add information rule by issue

### Removed
- Plugin property sonar.gitlab.ref. The property is replaced by sonar.gitlab.ref_name

**[Download 3.0.0](https://github.com/gabrie-allaigre/sonar-gitlab-plugin/releases/download/3.0.0/sonar-gitlab-plugin-3.0.0.jar)**

## Version 2.1.0

### Changed
- Add commit only line
- Add prefix workspace (not found .git folder)
- Support v3 & v4 api for GitLab
- Add all issues options

**[Download 2.1.0](https://github.com/gabrie-allaigre/sonar-gitlab-plugin/releases/download/2.1.0/sonar-gitlab-plugin-2.1.0.jar)**

## Version 2.0.1

### Fixed
- Fixbug : NoClassDefFoundError with internal sonar class #26

**[Download 2.0.1](https://github.com/gabrie-allaigre/sonar-gitlab-plugin/releases/download/2.0.1/sonar-gitlab-plugin-2.0.1.jar)**

## Version 2.0.0
- Use emoticon (Thanks Artpej)
- Change fail rule (Thanks Artpej)
- Add comment for no issue (Thanks frol2103)
- Refactored code (Thanks johnou)
- Disable reporting in global comments
- Disable reporting in inline comments
- Add support Proxy
- Ignore certficate if auto-signed
- Custom global comment (Template)
- Custom inline comment (Template)
- Get multi SHA for comment inline all commits
- Custom comment maybe empty then no comment added
- Add test unit
- Add quality project https://sonarqube.com/dashboard?id=com.talanlabs%3Asonar-gitlab-plugin
- GitLab API is in maven central
- Java 8
- Sonarqube >= 5.6
- Remove personal repository

## Version 1.7.0:
- SonarQube API 5.4
- Java 7
- Order settings

## Version 1.6.6:
- Fix url image

## Version 1.6.0:
- Sort issues in Markdown for not reported on diff

## Version 1.5.0:
 - Remove CheckMode
