# Changelog

## [8.7.0-alpha5](https://github.com/aabouzaid/camunda-platform-helm/compare/camunda-platform-alpha-v8.6.0-alpha5...camunda-platform-alpha-8.7.0-alpha5) (2024-09-08)


### Features

* add camunda license config into all components ([#2053](https://github.com/aabouzaid/camunda-platform-helm/issues/2053)) ([46900ae](https://github.com/aabouzaid/camunda-platform-helm/commit/46900aec3666e5d2c14a90826465c0057ebc3805))
* adding `adaptSecurityContext` option in values.yaml for OpenShift SCC ([#2212](https://github.com/aabouzaid/camunda-platform-helm/issues/2212)) ([d9aae33](https://github.com/aabouzaid/camunda-platform-helm/commit/d9aae33801d9e58459199f116b984ea5101c4c50))
* adding aws config in apps for OpenSearch ([#2232](https://github.com/aabouzaid/camunda-platform-helm/issues/2232)) ([9b77ec5](https://github.com/aabouzaid/camunda-platform-helm/commit/9b77ec59cb71bd68438e503d8423c318777c03ed))
* adding play env var to web-modeler ([#2269](https://github.com/aabouzaid/camunda-platform-helm/issues/2269)) ([fa99b6d](https://github.com/aabouzaid/camunda-platform-helm/commit/fa99b6d7dee41857330307074ece21e7e78fd719))
* configurable update strategy ([#2036](https://github.com/aabouzaid/camunda-platform-helm/issues/2036)) ([675ce34](https://github.com/aabouzaid/camunda-platform-helm/commit/675ce341395987f42707592a2e00b4e47c749b6d))
* configure camunda database to be used by v2 API ([#2040](https://github.com/aabouzaid/camunda-platform-helm/issues/2040)) ([216e7c2](https://github.com/aabouzaid/camunda-platform-helm/commit/216e7c2d229138ef5cae49078cc6028f058656ca))
* configure Webapps with REST v2 Api ([#1995](https://github.com/aabouzaid/camunda-platform-helm/issues/1995)) ([340dd3b](https://github.com/aabouzaid/camunda-platform-helm/commit/340dd3b804f8b34482ebd94932054d065f73bcfb))
* execution identity integration ([#2247](https://github.com/aabouzaid/camunda-platform-helm/issues/2247)) ([31a8ab1](https://github.com/aabouzaid/camunda-platform-helm/commit/31a8ab1debf6eca66a516ff700b161cdfaf2db22))
* increase elasticsearch nodes to 3 ([#2298](https://github.com/aabouzaid/camunda-platform-helm/issues/2298)) ([3b8f5eb](https://github.com/aabouzaid/camunda-platform-helm/commit/3b8f5eb64e0d3ad72885d77d1d9e07adf310fe13))
* support dnsPolicy and dnsConfig for all components ([#2009](https://github.com/aabouzaid/camunda-platform-helm/issues/2009)) ([6e3045c](https://github.com/aabouzaid/camunda-platform-helm/commit/6e3045c6247af3d356564541dcae980eec5d7419))
* support Keycloak v25 ([#2255](https://github.com/aabouzaid/camunda-platform-helm/issues/2255)) ([e72000e](https://github.com/aabouzaid/camunda-platform-helm/commit/e72000e47075a9817371a18adbc0cf660ff335b3))
* support migration init container for operate ([#2144](https://github.com/aabouzaid/camunda-platform-helm/issues/2144)) ([0262935](https://github.com/aabouzaid/camunda-platform-helm/commit/026293570c021f97cf73d25047e63083d9f1392f))
* support optional chart secrets auto-generation ([#2257](https://github.com/aabouzaid/camunda-platform-helm/issues/2257)) ([37085aa](https://github.com/aabouzaid/camunda-platform-helm/commit/37085aa650208e20568553b72f813a7c6a1216eb))
* use web-modeler public docker images ([#1974](https://github.com/aabouzaid/camunda-platform-helm/issues/1974)) ([714c01b](https://github.com/aabouzaid/camunda-platform-helm/commit/714c01b75e0013fb6211354007a09674a7105b3b))


### Bug Fixes

* add constraint for contextPath and rest path to be the same for zeebe gateway ([#2166](https://github.com/aabouzaid/camunda-platform-helm/issues/2166)) ([e878815](https://github.com/aabouzaid/camunda-platform-helm/commit/e878815ba43202802b07bdb9f2a807220ebc9ef9))
* add volumeClaimTemplates label selector in zeebe statefulSet ([cba241a](https://github.com/aabouzaid/camunda-platform-helm/commit/cba241ac62d3ceee6e350cd27e3dc1f29f5c10b8))
* add zeebe opensearch retention to app config file ([#2250](https://github.com/aabouzaid/camunda-platform-helm/issues/2250)) ([62c9c31](https://github.com/aabouzaid/camunda-platform-helm/commit/62c9c31e3cb9c9bd92208bf65c6cb82ca7715152))
* added helper function smtp auth for webmodeler ([#2245](https://github.com/aabouzaid/camunda-platform-helm/issues/2245)) ([b54fa13](https://github.com/aabouzaid/camunda-platform-helm/commit/b54fa13a1de20e2ae54c143449fcd11dbec85afa))
* added recreate strategy to all Operate deployments ([#2143](https://github.com/aabouzaid/camunda-platform-helm/issues/2143)) ([c2d70dc](https://github.com/aabouzaid/camunda-platform-helm/commit/c2d70dc36088e67c5acb6fc5e51cc1fc64cf9e33))
* advertisedHost relies on global.multiregion.regions and not global.multiregion.enabled ([#2226](https://github.com/aabouzaid/camunda-platform-helm/issues/2226)) ([59ac01a](https://github.com/aabouzaid/camunda-platform-helm/commit/59ac01a20ef7f2b673e4fb9ee8de3ad126559440))
* **alpha:** default camunda license key ([cc675cf](https://github.com/aabouzaid/camunda-platform-helm/commit/cc675cf9bd0fc53adf8361c4a18b22d93641714a))
* **alpha:** encrypt camunda license key ([62ab593](https://github.com/aabouzaid/camunda-platform-helm/commit/62ab59344a782cdb06354dbe8df6562c5089f230))
* changed restAddress in Tasklist with helper function ([#2152](https://github.com/aabouzaid/camunda-platform-helm/issues/2152)) ([9e45221](https://github.com/aabouzaid/camunda-platform-helm/commit/9e45221a4fae96d51d105fb8a6e84fe589c3153c))
* correct ingress nginx annotation to activate proxy buffering by default ([#2304](https://github.com/aabouzaid/camunda-platform-helm/issues/2304)) ([1e260e9](https://github.com/aabouzaid/camunda-platform-helm/commit/1e260e9db34c349420237251156575f235d077f2))
* correctly intend operate migration envs ([#2238](https://github.com/aabouzaid/camunda-platform-helm/issues/2238)) ([b795cfe](https://github.com/aabouzaid/camunda-platform-helm/commit/b795cfea0c672b7598250b91621967acb161a0ff))
* **deps:** update module github.com/gruntwork-io/terratest to v0.46.16 ([#2088](https://github.com/aabouzaid/camunda-platform-helm/issues/2088)) ([33d5b61](https://github.com/aabouzaid/camunda-platform-helm/commit/33d5b61e27fb4a6e3e30506fb557c65626995130))
* drop namespace from zeebe advertisedHost and initialContactPoints ([#2170](https://github.com/aabouzaid/camunda-platform-helm/issues/2170)) ([564581d](https://github.com/aabouzaid/camunda-platform-helm/commit/564581d1f136f055a72975f362812b567937ccfc))
* dynamically set advertisedHosts based on multiregion ([#2222](https://github.com/aabouzaid/camunda-platform-helm/issues/2222)) ([0b17624](https://github.com/aabouzaid/camunda-platform-helm/commit/0b1762449c448e3d97ac88119a2c5737a32a3ded))
* enable secrets deprecation flag in alpha by default ([#2081](https://github.com/aabouzaid/camunda-platform-helm/issues/2081)) ([b791f4c](https://github.com/aabouzaid/camunda-platform-helm/commit/b791f4cd6ac3859112b07a89fa6bc89a46d08313))
* existingSecret for OpenSearch password can be used without defining password literal ([#2168](https://github.com/aabouzaid/camunda-platform-helm/issues/2168)) ([71e4e4b](https://github.com/aabouzaid/camunda-platform-helm/commit/71e4e4b7af7cef7e4d4e5348a94f1bcc09b0eea9))
* **follow-up:** correct existingSecretKey for connectors inbound auth ([712ea6a](https://github.com/aabouzaid/camunda-platform-helm/commit/712ea6a6b387f063e67238321b8a59134d4b2d16))
* gives port-forward hostnames to external urls when no ingress is… ([#1897](https://github.com/aabouzaid/camunda-platform-helm/issues/1897)) ([d28a790](https://github.com/aabouzaid/camunda-platform-helm/commit/d28a7902237340350027fb4709daa3bc278c9d21))
* reload identity when its config changed ([#2234](https://github.com/aabouzaid/camunda-platform-helm/issues/2234)) ([cb41059](https://github.com/aabouzaid/camunda-platform-helm/commit/cb41059630597c4239886dff577c33b8488cb3f8))
* remove openshift post-render script ([#2188](https://github.com/aabouzaid/camunda-platform-helm/issues/2188)) ([3b8cd72](https://github.com/aabouzaid/camunda-platform-helm/commit/3b8cd728fb94c53bc681a2a1e0d30c29fd649f0e))
* set the network host and port to the zeebeGateway config ([#1910](https://github.com/aabouzaid/camunda-platform-helm/issues/1910)) ([b472f4f](https://github.com/aabouzaid/camunda-platform-helm/commit/b472f4f52389e119d70409fc0da6dde767b4762d))
* template grpc url in console config ([#2165](https://github.com/aabouzaid/camunda-platform-helm/issues/2165)) ([2e83c49](https://github.com/aabouzaid/camunda-platform-helm/commit/2e83c491c31947ef65891458bb8b884ba5895a8d))
* use correct operate image for version label ([#2183](https://github.com/aabouzaid/camunda-platform-helm/issues/2183)) ([3ed7fd2](https://github.com/aabouzaid/camunda-platform-helm/commit/3ed7fd2e75f3cd1330af7b56e401c462081165de))


### Documentation

* notice of separated ingress being deprecated ([#2263](https://github.com/aabouzaid/camunda-platform-helm/issues/2263)) ([2091f38](https://github.com/aabouzaid/camunda-platform-helm/commit/2091f381d6d278a2ee4750e5270cef33a0c805a7))
* update of outdated url in the local kubernetes  section ([#2274](https://github.com/aabouzaid/camunda-platform-helm/issues/2274)) ([83f8230](https://github.com/aabouzaid/camunda-platform-helm/commit/83f8230d8f5b34d52294e6d3d1be449ffe6aee9c))


### Refactors

* configure operate management port ([#1660](https://github.com/aabouzaid/camunda-platform-helm/issues/1660)) ([6c47540](https://github.com/aabouzaid/camunda-platform-helm/commit/6c475400b4540d73d3ea781dd6b790a944a53545))
* configure Tasklist's management port ([#1709](https://github.com/aabouzaid/camunda-platform-helm/issues/1709)) ([024c063](https://github.com/aabouzaid/camunda-platform-helm/commit/024c0636100f110835b4aa923635fe8f50a15ba8))
* configure zeebe-gateway context path ([#1672](https://github.com/aabouzaid/camunda-platform-helm/issues/1672)) ([67cadfa](https://github.com/aabouzaid/camunda-platform-helm/commit/67cadfa53b77a6a3507570662ce7236b4978f23f))
* hardcoding strategy for all components and removing ability to configure strategy ([#2155](https://github.com/aabouzaid/camunda-platform-helm/issues/2155)) ([127162a](https://github.com/aabouzaid/camunda-platform-helm/commit/127162a83a13b85c60247926d638a037a1077a36))
* remove the global image tag value and use it from the components ([#2069](https://github.com/aabouzaid/camunda-platform-helm/issues/2069)) ([0c34cd5](https://github.com/aabouzaid/camunda-platform-helm/commit/0c34cd56d12fe257e0feca3fcf52fca3ea4c3fb5))
* update Tasklist with monorepo configuration ([#1718](https://github.com/aabouzaid/camunda-platform-helm/issues/1718)) ([edbe2fe](https://github.com/aabouzaid/camunda-platform-helm/commit/edbe2fe1f89497b9ef4ae76140b06187d3482636))
* use gatewayAddress property instead of brokerContactPoint ([#1647](https://github.com/aabouzaid/camunda-platform-helm/issues/1647)) ([eb6f179](https://github.com/aabouzaid/camunda-platform-helm/commit/eb6f17924d9b30a598d4bbb1bb00ffc9b7824c90))
