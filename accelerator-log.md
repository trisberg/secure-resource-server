# Accelerator Log

## Options
```json
{
  "projectName" : "spring-secure-resource-server",
  "workloadNamespace" : "default",
  "clusterIssuerName" : "tap-ingress-selfsigned",
  "gatewayName" : "gateway-postal-codes",
  "msgbrokerName" : "msgbroker-postal-codes",
  "enableRateLimiting" : false,
  "rateLimit" : {
    "requestLimitMaxRequests" : 5,
    "requestLimitTimeWindow" : 1,
    "requestLimitWindowUnits" : "s"
  },
  "appSSOName" : "appsso-postal-codes",
  "appDomain" : "35.188.35.143.nip.io",
  "includeBuildToolWrapper" : true
}
```
## Log
```
┏ engine (Chain)
┃  Info Running Chain(Exclude, GeneratorValidationTransform, UniquePath)
┃ ┏ engine.transformations[0] (Exclude)
┃ ┃  Info Will exclude [accelerator.yaml, accelerator.axl]
┃ ┃ Debug postal-code-search-ui/tsconfig.node.json didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug postal-code-search-ui/index.html didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug postal-code-search-ui/tsconfig.app.json didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug postal-code-search-ui/config/workload.yaml didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug postal-code-search-ui/env.d.ts didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug postal-code-search-ui/README.md didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug postal-code-search-ui/public/favicon.svg didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug postal-code-search-ui/.gitignore didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug postal-code-search-ui/package-lock.json didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug postal-code-search-ui/package.json didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug postal-code-search-ui/tsconfig.json didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug postal-code-search-ui/nginx.conf didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug postal-code-search-ui/vite.config.ts didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug postal-code-search-ui/src/App.vue didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug postal-code-search-ui/src/main.ts didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug postal-code-search-ui/src/stores/counter.ts didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug postal-code-search-ui/src/components/Search.vue didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug postal-code-search-ui/src/components/Landing.vue didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug postal-code-search-ui/src/views/HomeView.vue didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug postal-code-search-ui/src/views/SearchView.vue didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug postal-code-search-ui/src/assets/main.css didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug postal-code-search-ui/src/assets/base.css didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug postal-code-search-ui/src/router/index.ts didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug catalog/resources/sso/postal-code-sso-resource.yaml didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug catalog/resources/db/postal-code-db-resource.yaml didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug catalog/resources/messaging/postal-code-messaging-resource.yaml didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug catalog/resources/gateway/postal-code-gateway-resource.yaml didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug catalog/groups/org.yaml didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug catalog/components/postal-code-search-ui/postal-code-search-ui.yaml didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug catalog/components/postal-code-audit/postal-code-audit.yaml didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug catalog/components/postal-code-audit-ui/postal-code-audit-ui.yaml didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug catalog/components/postal-code-search/postal-code-search.yaml didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug catalog/systems/postal-code-system.yaml didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug catalog/catalog-info.yaml didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug pom.xml didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug audit-ui/tsconfig.node.json didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug audit-ui/index.html didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug audit-ui/tsconfig.app.json didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug audit-ui/config/workload.yaml didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug audit-ui/env.d.ts didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug audit-ui/README.md didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug audit-ui/public/favicon.svg didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug audit-ui/.gitignore didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug audit-ui/package-lock.json didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug audit-ui/package.json didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug audit-ui/tsconfig.json didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug audit-ui/nginx.conf didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug audit-ui/vite.config.ts didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug audit-ui/src/App.vue didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug audit-ui/src/main.ts didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug audit-ui/src/stores/counter.ts didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug audit-ui/src/components/Audit.vue didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug audit-ui/src/components/Landing.vue didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug audit-ui/src/views/AuditView.vue didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug audit-ui/src/views/HomeView.vue didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug audit-ui/src/assets/main.css didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug audit-ui/src/assets/base.css didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug audit-ui/src/router/index.ts didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug accelerator.yaml matched [accelerator.yaml, accelerator.axl] -> excluded
┃ ┃ Debug README.md didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug postal-code-client/pom.xml didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug postal-code-client/.gitignore didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug postal-code-client/src/test/java/com/java/example/tanzu/postalcode/PostalCodeClientApplicationTests.java didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug postal-code-client/src/main/resources/application.yaml didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug postal-code-client/src/main/java/com/java/example/tanzu/postalsearch/exchange/PostalCodeLoc.java didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug postal-code-client/src/main/java/com/java/example/tanzu/postalsearch/exchange/PostalCodeSearchClient.java didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug postal-code-client/src/main/java/com/java/example/tanzu/postalsearch/config/DeclarativeClientConfig.java didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug postal-code-client/src/main/java/com/java/example/tanzu/postalsearch/PostalCodeClientApplication.java didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug postal-code-client/src/main/java/com/java/example/tanzu/postalsearch/commands/SearchCommand.java didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug audit/config/workload.yaml didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug audit/Tiltfile didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug audit/pom.xml didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug audit/.gitignore didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug audit/src/test/java/com/java/example/tanzu/audit/AuditApplicationTests.java didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug audit/src/main/resources/META-INF/spring.factories didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug audit/src/main/resources/db/migration/postgresql/V1.1__Base_version.sql didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug audit/src/main/resources/db/migration/h2/V1.1__Base_version.sql didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug audit/src/main/resources/db/migration/mariadb/V1.1__Base_version.sql didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug audit/src/main/resources/application.yaml didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/repository/AuditEventRepository.java didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/repository/AuditDataRepository.java didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/AuditApplication.java didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/config/WebSecurityConfig.java didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/config/FlywayDataSourceConfiguraion.java didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/config/OAuth2BindingsPropertiesProcessor.java didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/security/JwtRolesToAuthoritiesConverter.java didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/entity/AuditEvent.java didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/entity/AuditData.java didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/resources/AuditResource.java didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/function/AuditSink.java didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/model/AuditEvent.java didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/model/AuditData.java didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug templates/ingress.yaml didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug templates/appSSOInstance.yaml didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug templates/scgRoutes.yaml didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug templates/rmqClassClaim.yaml didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug templates/scgInstance.yaml didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug templates/workloads.yaml didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug templates/workloadClientRegistration.yaml didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug doc/TAPDeployment.md didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug doc/images/PostalCodeHighLevelArch.png didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug postal-code-search/config/workload.yaml didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug postal-code-search/Tiltfile didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug postal-code-search/pom.xml didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug postal-code-search/.gitignore didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug postal-code-search/src/test/java/com/java/example/tanzu/postalsearch/ProtectedGeolocApiApplicationTests.java didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug postal-code-search/src/main/resources/META-INF/spring.factories didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug postal-code-search/src/main/resources/db/migration/postgresql/V1.1__Base_version.sql didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug postal-code-search/src/main/resources/db/migration/h2/V1.1__Base_version.sql didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug postal-code-search/src/main/resources/db/migration/mariadb/V1.1__Base_version.sql didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug postal-code-search/src/main/resources/data/usPostalCodeToGeoMapping.csv didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug postal-code-search/src/main/resources/application.yaml didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug postal-code-search/src/main/java/db/migration/postgresql/V2__InitailizeDBData.java didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug postal-code-search/src/main/java/db/migration/h2/V2__InitailizeDBData.java didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug postal-code-search/src/main/java/db/migration/mariadb/V2__InitailizeDBData.java didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug postal-code-search/src/main/java/db/migration/PostalCodeImport.java didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/repository/PostalCodeLocRepository.java didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/config/WebSecurityConfig.java didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/config/FlywayDataSourceConfiguraion.java didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/config/OAuth2BindingsPropertiesProcessor.java didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/security/JwtRolesToAuthoritiesConverter.java didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/security/APIKeyAuthenticationConverter.java didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/security/APIKeyAuthenticationManager.java didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/entity/PotalCodeLoc.java didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/resources/PostalCodeLookup.java didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/resources/AuditedResource.java didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/PotalCodeLookupApplication.java didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/audit/model/AuditEvent.java didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┗ Debug postal-code-search/src/main/java/com/java/example/tanzu/audit/model/AuditData.java didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┏ ┏ engine.transformations[1].validated (Combo)
┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ engine.transformations[1].validated.delegate (Chain)
┃ ┃ ┃  Info Running Chain(Merge, UniquePath)
┃ ┃ ┃ ┏ engine.transformations[1].validated.delegate.transformations[0] (Merge)
┃ ┃ ┃ ┃  Info Running Merge(Combo, Combo, Combo, Combo, InvokeFragment, Combo, Combo, Combo, Combo, Provenance)
┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.delegate.transformations[0].sources[0] (Combo)
┃ ┃ ┃ ┃ ┃  Info Combo running as Exclude
┃ ┃ ┃ ┃ ┃ engine.transformations[1].validated.delegate.transformations[0].sources[0].delegate (Exclude)
┃ ┃ ┃ ┃ ┃  Info Will exclude [**/templates/**, **/icons/**, **/.git/**, **/deployment/**]
┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/tsconfig.node.json didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/index.html didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/tsconfig.app.json didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/config/workload.yaml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/env.d.ts didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/README.md didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/public/favicon.svg didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/.gitignore didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/package-lock.json didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/package.json didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/tsconfig.json didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/nginx.conf didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/vite.config.ts didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/src/App.vue didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/src/main.ts didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/src/stores/counter.ts didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/src/components/Search.vue didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/src/components/Landing.vue didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/src/views/HomeView.vue didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/src/views/SearchView.vue didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/src/assets/main.css didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/src/assets/base.css didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/src/router/index.ts didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug catalog/resources/sso/postal-code-sso-resource.yaml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug catalog/resources/db/postal-code-db-resource.yaml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug catalog/resources/messaging/postal-code-messaging-resource.yaml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug catalog/resources/gateway/postal-code-gateway-resource.yaml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug catalog/groups/org.yaml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug catalog/components/postal-code-search-ui/postal-code-search-ui.yaml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug catalog/components/postal-code-audit/postal-code-audit.yaml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug catalog/components/postal-code-audit-ui/postal-code-audit-ui.yaml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug catalog/components/postal-code-search/postal-code-search.yaml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug catalog/systems/postal-code-system.yaml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug audit-ui/tsconfig.node.json didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug audit-ui/index.html didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug audit-ui/tsconfig.app.json didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug audit-ui/config/workload.yaml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug audit-ui/env.d.ts didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug audit-ui/README.md didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug audit-ui/public/favicon.svg didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug audit-ui/.gitignore didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug audit-ui/package-lock.json didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug audit-ui/package.json didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug audit-ui/tsconfig.json didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug audit-ui/nginx.conf didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug audit-ui/vite.config.ts didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug audit-ui/src/App.vue didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug audit-ui/src/main.ts didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug audit-ui/src/stores/counter.ts didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug audit-ui/src/components/Audit.vue didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug audit-ui/src/components/Landing.vue didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug audit-ui/src/views/AuditView.vue didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug audit-ui/src/views/HomeView.vue didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug audit-ui/src/assets/main.css didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug audit-ui/src/assets/base.css didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug audit-ui/src/router/index.ts didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug postal-code-client/pom.xml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug postal-code-client/.gitignore didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug postal-code-client/src/test/java/com/java/example/tanzu/postalcode/PostalCodeClientApplicationTests.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug postal-code-client/src/main/resources/application.yaml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug postal-code-client/src/main/java/com/java/example/tanzu/postalsearch/exchange/PostalCodeLoc.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug postal-code-client/src/main/java/com/java/example/tanzu/postalsearch/exchange/PostalCodeSearchClient.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug postal-code-client/src/main/java/com/java/example/tanzu/postalsearch/config/DeclarativeClientConfig.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug postal-code-client/src/main/java/com/java/example/tanzu/postalsearch/PostalCodeClientApplication.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug postal-code-client/src/main/java/com/java/example/tanzu/postalsearch/commands/SearchCommand.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug audit/config/workload.yaml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug audit/Tiltfile didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug audit/pom.xml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug audit/.gitignore didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug audit/src/test/java/com/java/example/tanzu/audit/AuditApplicationTests.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug audit/src/main/resources/META-INF/spring.factories didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug audit/src/main/resources/db/migration/postgresql/V1.1__Base_version.sql didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug audit/src/main/resources/db/migration/h2/V1.1__Base_version.sql didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug audit/src/main/resources/db/migration/mariadb/V1.1__Base_version.sql didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug audit/src/main/resources/application.yaml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/repository/AuditEventRepository.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/repository/AuditDataRepository.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/AuditApplication.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/config/WebSecurityConfig.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/config/FlywayDataSourceConfiguraion.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/config/OAuth2BindingsPropertiesProcessor.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/security/JwtRolesToAuthoritiesConverter.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/entity/AuditEvent.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/entity/AuditData.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/resources/AuditResource.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/function/AuditSink.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/model/AuditEvent.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/model/AuditData.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug templates/ingress.yaml matched [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> excluded
┃ ┃ ┃ ┃ ┃ Debug templates/appSSOInstance.yaml matched [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> excluded
┃ ┃ ┃ ┃ ┃ Debug templates/scgRoutes.yaml matched [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> excluded
┃ ┃ ┃ ┃ ┃ Debug templates/rmqClassClaim.yaml matched [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> excluded
┃ ┃ ┃ ┃ ┃ Debug templates/scgInstance.yaml matched [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> excluded
┃ ┃ ┃ ┃ ┃ Debug templates/workloads.yaml matched [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> excluded
┃ ┃ ┃ ┃ ┃ Debug templates/workloadClientRegistration.yaml matched [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> excluded
┃ ┃ ┃ ┃ ┃ Debug doc/TAPDeployment.md didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug doc/images/PostalCodeHighLevelArch.png didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug postal-code-search/config/workload.yaml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug postal-code-search/Tiltfile didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug postal-code-search/pom.xml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug postal-code-search/.gitignore didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/test/java/com/java/example/tanzu/postalsearch/ProtectedGeolocApiApplicationTests.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/resources/META-INF/spring.factories didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/resources/db/migration/postgresql/V1.1__Base_version.sql didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/resources/db/migration/h2/V1.1__Base_version.sql didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/resources/db/migration/mariadb/V1.1__Base_version.sql didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/resources/data/usPostalCodeToGeoMapping.csv didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/resources/application.yaml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/db/migration/postgresql/V2__InitailizeDBData.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/db/migration/h2/V2__InitailizeDBData.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/db/migration/mariadb/V2__InitailizeDBData.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/db/migration/PostalCodeImport.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/repository/PostalCodeLocRepository.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/config/WebSecurityConfig.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/config/FlywayDataSourceConfiguraion.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/config/OAuth2BindingsPropertiesProcessor.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/security/JwtRolesToAuthoritiesConverter.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/security/APIKeyAuthenticationConverter.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/security/APIKeyAuthenticationManager.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/entity/PotalCodeLoc.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/resources/PostalCodeLookup.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/resources/AuditedResource.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/PotalCodeLookupApplication.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/audit/model/AuditEvent.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┗ Debug postal-code-search/src/main/java/com/java/example/tanzu/audit/model/AuditData.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.delegate.transformations[0].sources[1] (Combo)
┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ engine.transformations[1].validated.delegate.transformations[0].sources[1].delegate (Chain)
┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, YTT, RewritePath, RewritePath, RewritePath, RewritePath)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.delegate.transformations[0].sources[1].delegate.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃  Info Will include [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml]
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/tsconfig.node.json didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/index.html didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/tsconfig.app.json didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/config/workload.yaml didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/env.d.ts didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/README.md didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/public/favicon.svg didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/.gitignore didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/package-lock.json didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/package.json didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/tsconfig.json didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/nginx.conf didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/vite.config.ts didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/src/App.vue didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/src/main.ts didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/src/stores/counter.ts didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/src/components/Search.vue didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/src/components/Landing.vue didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/src/views/HomeView.vue didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/src/views/SearchView.vue didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/src/assets/main.css didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/src/assets/base.css didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/src/router/index.ts didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/resources/sso/postal-code-sso-resource.yaml didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/resources/db/postal-code-db-resource.yaml didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/resources/messaging/postal-code-messaging-resource.yaml didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/resources/gateway/postal-code-gateway-resource.yaml didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/groups/org.yaml didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/postal-code-search-ui/postal-code-search-ui.yaml didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/postal-code-audit/postal-code-audit.yaml didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/postal-code-audit-ui/postal-code-audit-ui.yaml didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/postal-code-search/postal-code-search.yaml didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/systems/postal-code-system.yaml didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/tsconfig.node.json didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/index.html didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/tsconfig.app.json didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/config/workload.yaml didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/env.d.ts didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/README.md didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/public/favicon.svg didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/.gitignore didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/package-lock.json didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/package.json didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/tsconfig.json didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/nginx.conf didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/vite.config.ts didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/src/App.vue didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/src/main.ts didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/src/stores/counter.ts didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/src/components/Audit.vue didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/src/components/Landing.vue didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/src/views/AuditView.vue didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/src/views/HomeView.vue didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/src/assets/main.css didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/src/assets/base.css didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/src/router/index.ts didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-client/pom.xml didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-client/.gitignore didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-client/src/test/java/com/java/example/tanzu/postalcode/PostalCodeClientApplicationTests.java didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-client/src/main/resources/application.yaml didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-client/src/main/java/com/java/example/tanzu/postalsearch/exchange/PostalCodeLoc.java didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-client/src/main/java/com/java/example/tanzu/postalsearch/exchange/PostalCodeSearchClient.java didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-client/src/main/java/com/java/example/tanzu/postalsearch/config/DeclarativeClientConfig.java didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-client/src/main/java/com/java/example/tanzu/postalsearch/PostalCodeClientApplication.java didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-client/src/main/java/com/java/example/tanzu/postalsearch/commands/SearchCommand.java didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit/config/workload.yaml didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit/Tiltfile didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit/pom.xml didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit/.gitignore didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/test/java/com/java/example/tanzu/audit/AuditApplicationTests.java didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/resources/META-INF/spring.factories didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/resources/db/migration/postgresql/V1.1__Base_version.sql didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/resources/db/migration/h2/V1.1__Base_version.sql didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/resources/db/migration/mariadb/V1.1__Base_version.sql didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/resources/application.yaml didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/repository/AuditEventRepository.java didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/repository/AuditDataRepository.java didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/AuditApplication.java didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/config/WebSecurityConfig.java didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/config/FlywayDataSourceConfiguraion.java didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/config/OAuth2BindingsPropertiesProcessor.java didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/security/JwtRolesToAuthoritiesConverter.java didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/entity/AuditEvent.java didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/entity/AuditData.java didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/resources/AuditResource.java didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/function/AuditSink.java didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/model/AuditEvent.java didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/model/AuditData.java didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/ingress.yaml matched [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/appSSOInstance.yaml didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/scgRoutes.yaml matched [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/rmqClassClaim.yaml matched [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/scgInstance.yaml matched [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/workloads.yaml didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/workloadClientRegistration.yaml didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug doc/TAPDeployment.md didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug doc/images/PostalCodeHighLevelArch.png didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/config/workload.yaml didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/Tiltfile didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/pom.xml didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/.gitignore didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/test/java/com/java/example/tanzu/postalsearch/ProtectedGeolocApiApplicationTests.java didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/resources/META-INF/spring.factories didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/resources/db/migration/postgresql/V1.1__Base_version.sql didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/resources/db/migration/h2/V1.1__Base_version.sql didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/resources/db/migration/mariadb/V1.1__Base_version.sql didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/resources/data/usPostalCodeToGeoMapping.csv didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/resources/application.yaml didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/db/migration/postgresql/V2__InitailizeDBData.java didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/db/migration/h2/V2__InitailizeDBData.java didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/db/migration/mariadb/V2__InitailizeDBData.java didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/db/migration/PostalCodeImport.java didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/repository/PostalCodeLocRepository.java didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/config/WebSecurityConfig.java didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/config/FlywayDataSourceConfiguraion.java didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/config/OAuth2BindingsPropertiesProcessor.java didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/security/JwtRolesToAuthoritiesConverter.java didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/security/APIKeyAuthenticationConverter.java didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/security/APIKeyAuthenticationManager.java didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/entity/PotalCodeLoc.java didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/resources/PostalCodeLookup.java didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/resources/AuditedResource.java didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/PotalCodeLookupApplication.java didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/audit/model/AuditEvent.java didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┗ Debug postal-code-search/src/main/java/com/java/example/tanzu/audit/model/AuditData.java didn't match [**/templates/scgInstance.yaml, **/templates/scgRoutes.yaml, **/templates/ingress.yaml, **/templates/rmqClassClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.delegate.transformations[0].sources[1].delegate.transformations[1] (YTT)
┃ ┃ ┃ ┃ ┃ ┃ Debug Wrote values file with json content:   {"appDomain":"35.188.35.143.nip.io","rateLimit":{"requestLimitMaxRequests":5,"requestLimitTimeWindow":1,"requestLimitWindowUnits":"s"},"appSSOName":"appsso-postal-codes","artifactVersion":"0.0.1-beta","includeBuildToolWrapper":true,"gatewayName":"gateway-postal-codes","msgbrokerName":"msgbroker-postal-codes","enableRateLimiting":false,"artifactId":"spring-secure-resource-server","clusterIssuerName":"tap-ingress-selfsigned","projectName":"spring-secure-resource-server","workloadNamespace":"default"}
┃ ┃ ┃ ┃ ┃ ┗  Info Shelling out to YTT with args: [ytt, -f, /var/folders/sv/7g686rs906v38snwbz438xsr0000gq/T/ytt-input14520042418096712729, --data-values-file, /var/folders/sv/7g686rs906v38snwbz438xsr0000gq/T/accelerator-options14876149962808368271.json, --output-files, /var/folders/sv/7g686rs906v38snwbz438xsr0000gq/T/ytt-output11238713927317459371]
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.delegate.transformations[0].sources[1].delegate.transformations[2] (RewritePath)
┃ ┃ ┃ ┃ ┃ ┗ Debug Path 'templates/scgInstance.yaml' matched 'templates/scgInstance.yaml' with groups {g0=templates/scgInstance.yaml} and was rewritten to 'config/service-operator/scgInstance.yaml'
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.delegate.transformations[0].sources[1].delegate.transformations[3] (RewritePath)
┃ ┃ ┃ ┃ ┃ ┗ Debug Path 'templates/scgRoutes.yaml' matched 'templates/scgRoutes.yaml' with groups {g0=templates/scgRoutes.yaml} and was rewritten to 'config/app-operator/scgRoutes.yaml'
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.delegate.transformations[0].sources[1].delegate.transformations[4] (RewritePath)
┃ ┃ ┃ ┃ ┃ ┗ Debug Path 'templates/ingress.yaml' matched 'templates/ingress.yaml' with groups {g0=templates/ingress.yaml} and was rewritten to 'config/app-operator/ingress.yaml'
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.delegate.transformations[0].sources[1].delegate.transformations[5] (RewritePath)
┃ ┃ ┃ ┃ ┗ ┗ Debug Path 'templates/rmqClassClaim.yaml' matched 'templates/rmqClassClaim.yaml' with groups {g0=templates/rmqClassClaim.yaml} and was rewritten to 'config/app-operator/rmqClassClaim.yaml'
┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.delegate.transformations[0].sources[2] (Combo)
┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ engine.transformations[1].validated.delegate.transformations[0].sources[2].delegate (Chain)
┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, YTT, RewritePath, InvokeFragment)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.delegate.transformations[0].sources[2].delegate.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃  Info Will include [**/templates/workloads.yaml]
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/tsconfig.node.json didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/index.html didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/tsconfig.app.json didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/config/workload.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/env.d.ts didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/README.md didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/public/favicon.svg didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/.gitignore didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/package-lock.json didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/package.json didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/tsconfig.json didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/nginx.conf didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/vite.config.ts didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/src/App.vue didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/src/main.ts didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/src/stores/counter.ts didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/src/components/Search.vue didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/src/components/Landing.vue didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/src/views/HomeView.vue didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/src/views/SearchView.vue didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/src/assets/main.css didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/src/assets/base.css didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/src/router/index.ts didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/resources/sso/postal-code-sso-resource.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/resources/db/postal-code-db-resource.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/resources/messaging/postal-code-messaging-resource.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/resources/gateway/postal-code-gateway-resource.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/groups/org.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/postal-code-search-ui/postal-code-search-ui.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/postal-code-audit/postal-code-audit.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/postal-code-audit-ui/postal-code-audit-ui.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/postal-code-search/postal-code-search.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/systems/postal-code-system.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/tsconfig.node.json didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/index.html didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/tsconfig.app.json didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/config/workload.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/env.d.ts didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/README.md didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/public/favicon.svg didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/.gitignore didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/package-lock.json didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/package.json didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/tsconfig.json didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/nginx.conf didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/vite.config.ts didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/src/App.vue didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/src/main.ts didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/src/stores/counter.ts didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/src/components/Audit.vue didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/src/components/Landing.vue didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/src/views/AuditView.vue didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/src/views/HomeView.vue didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/src/assets/main.css didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/src/assets/base.css didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/src/router/index.ts didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-client/pom.xml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-client/.gitignore didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-client/src/test/java/com/java/example/tanzu/postalcode/PostalCodeClientApplicationTests.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-client/src/main/resources/application.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-client/src/main/java/com/java/example/tanzu/postalsearch/exchange/PostalCodeLoc.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-client/src/main/java/com/java/example/tanzu/postalsearch/exchange/PostalCodeSearchClient.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-client/src/main/java/com/java/example/tanzu/postalsearch/config/DeclarativeClientConfig.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-client/src/main/java/com/java/example/tanzu/postalsearch/PostalCodeClientApplication.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-client/src/main/java/com/java/example/tanzu/postalsearch/commands/SearchCommand.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit/config/workload.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit/Tiltfile didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit/pom.xml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit/.gitignore didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/test/java/com/java/example/tanzu/audit/AuditApplicationTests.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/resources/META-INF/spring.factories didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/resources/db/migration/postgresql/V1.1__Base_version.sql didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/resources/db/migration/h2/V1.1__Base_version.sql didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/resources/db/migration/mariadb/V1.1__Base_version.sql didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/resources/application.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/repository/AuditEventRepository.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/repository/AuditDataRepository.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/AuditApplication.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/config/WebSecurityConfig.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/config/FlywayDataSourceConfiguraion.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/config/OAuth2BindingsPropertiesProcessor.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/security/JwtRolesToAuthoritiesConverter.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/entity/AuditEvent.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/entity/AuditData.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/resources/AuditResource.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/function/AuditSink.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/model/AuditEvent.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/model/AuditData.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/ingress.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/appSSOInstance.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/scgRoutes.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/rmqClassClaim.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/scgInstance.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/workloads.yaml matched [**/templates/workloads.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/workloadClientRegistration.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug doc/TAPDeployment.md didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug doc/images/PostalCodeHighLevelArch.png didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/config/workload.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/Tiltfile didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/pom.xml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/.gitignore didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/test/java/com/java/example/tanzu/postalsearch/ProtectedGeolocApiApplicationTests.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/resources/META-INF/spring.factories didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/resources/db/migration/postgresql/V1.1__Base_version.sql didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/resources/db/migration/h2/V1.1__Base_version.sql didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/resources/db/migration/mariadb/V1.1__Base_version.sql didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/resources/data/usPostalCodeToGeoMapping.csv didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/resources/application.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/db/migration/postgresql/V2__InitailizeDBData.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/db/migration/h2/V2__InitailizeDBData.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/db/migration/mariadb/V2__InitailizeDBData.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/db/migration/PostalCodeImport.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/repository/PostalCodeLocRepository.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/config/WebSecurityConfig.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/config/FlywayDataSourceConfiguraion.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/config/OAuth2BindingsPropertiesProcessor.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/security/JwtRolesToAuthoritiesConverter.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/security/APIKeyAuthenticationConverter.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/security/APIKeyAuthenticationManager.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/entity/PotalCodeLoc.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/resources/PostalCodeLookup.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/resources/AuditedResource.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/PotalCodeLookupApplication.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/audit/model/AuditEvent.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┗ Debug postal-code-search/src/main/java/com/java/example/tanzu/audit/model/AuditData.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.delegate.transformations[0].sources[2].delegate.transformations[1] (YTT)
┃ ┃ ┃ ┃ ┃ ┃ Debug Wrote values file with json content:   {"appDomain":"35.188.35.143.nip.io","rateLimit":{"requestLimitMaxRequests":5,"requestLimitTimeWindow":1,"requestLimitWindowUnits":"s"},"appSSOName":"appsso-postal-codes","artifactVersion":"0.0.1-beta","includeBuildToolWrapper":true,"gatewayName":"gateway-postal-codes","msgbrokerName":"msgbroker-postal-codes","enableRateLimiting":false,"artifactId":"spring-secure-resource-server","clusterIssuerName":"tap-ingress-selfsigned","projectName":"spring-secure-resource-server","workloadNamespace":"default"}
┃ ┃ ┃ ┃ ┃ ┗  Info Shelling out to YTT with args: [ytt, -f, /var/folders/sv/7g686rs906v38snwbz438xsr0000gq/T/ytt-input11818686755908110361, --data-values-file, /var/folders/sv/7g686rs906v38snwbz438xsr0000gq/T/accelerator-options12721204828890331421.json, --output-files, /var/folders/sv/7g686rs906v38snwbz438xsr0000gq/T/ytt-output1600770003246017505]
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.delegate.transformations[0].sources[2].delegate.transformations[2] (RewritePath)
┃ ┃ ┃ ┃ ┃ ┗ Debug Path 'templates/workloads.yaml' matched 'templates/workloads.yaml' with groups {g0=templates/workloads.yaml} and was rewritten to 'config/developer/workloads.yaml'
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.delegate.transformations[0].sources[2].delegate.transformations[3] (InvokeFragment)
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.delegate.transformations[0].sources[2].delegate.transformations[3].validated (Chain)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(Exclude, IfElse)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.delegate.transformations[0].sources[2].delegate.transformations[3].validated.transformations[0] (Exclude)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will exclude [README.md]
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug config/developer/workloads.yaml didn't match [README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ Debug README.md matched [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.delegate.transformations[0].sources[2].delegate.transformations[3].validated.transformations[1] (IfElse)
┃ ┃ ┃ ┃ ┗ ┗ ┗ ┗ null ()
┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.delegate.transformations[0].sources[3] (Combo)
┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ engine.transformations[1].validated.delegate.transformations[0].sources[3].delegate (Chain)
┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, YTT, RewritePath, RewritePath)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.delegate.transformations[0].sources[3].delegate.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃  Info Will include [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml]
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/tsconfig.node.json didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/index.html didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/tsconfig.app.json didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/config/workload.yaml didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/env.d.ts didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/README.md didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/public/favicon.svg didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/.gitignore didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/package-lock.json didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/package.json didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/tsconfig.json didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/nginx.conf didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/vite.config.ts didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/src/App.vue didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/src/main.ts didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/src/stores/counter.ts didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/src/components/Search.vue didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/src/components/Landing.vue didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/src/views/HomeView.vue didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/src/views/SearchView.vue didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/src/assets/main.css didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/src/assets/base.css didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/src/router/index.ts didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/resources/sso/postal-code-sso-resource.yaml didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/resources/db/postal-code-db-resource.yaml didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/resources/messaging/postal-code-messaging-resource.yaml didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/resources/gateway/postal-code-gateway-resource.yaml didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/groups/org.yaml didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/postal-code-search-ui/postal-code-search-ui.yaml didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/postal-code-audit/postal-code-audit.yaml didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/postal-code-audit-ui/postal-code-audit-ui.yaml didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/postal-code-search/postal-code-search.yaml didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/systems/postal-code-system.yaml didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/tsconfig.node.json didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/index.html didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/tsconfig.app.json didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/config/workload.yaml didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/env.d.ts didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/README.md didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/public/favicon.svg didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/.gitignore didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/package-lock.json didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/package.json didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/tsconfig.json didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/nginx.conf didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/vite.config.ts didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/src/App.vue didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/src/main.ts didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/src/stores/counter.ts didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/src/components/Audit.vue didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/src/components/Landing.vue didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/src/views/AuditView.vue didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/src/views/HomeView.vue didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/src/assets/main.css didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/src/assets/base.css didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/src/router/index.ts didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-client/pom.xml didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-client/.gitignore didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-client/src/test/java/com/java/example/tanzu/postalcode/PostalCodeClientApplicationTests.java didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-client/src/main/resources/application.yaml didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-client/src/main/java/com/java/example/tanzu/postalsearch/exchange/PostalCodeLoc.java didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-client/src/main/java/com/java/example/tanzu/postalsearch/exchange/PostalCodeSearchClient.java didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-client/src/main/java/com/java/example/tanzu/postalsearch/config/DeclarativeClientConfig.java didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-client/src/main/java/com/java/example/tanzu/postalsearch/PostalCodeClientApplication.java didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-client/src/main/java/com/java/example/tanzu/postalsearch/commands/SearchCommand.java didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit/config/workload.yaml didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit/Tiltfile didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit/pom.xml didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit/.gitignore didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/test/java/com/java/example/tanzu/audit/AuditApplicationTests.java didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/resources/META-INF/spring.factories didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/resources/db/migration/postgresql/V1.1__Base_version.sql didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/resources/db/migration/h2/V1.1__Base_version.sql didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/resources/db/migration/mariadb/V1.1__Base_version.sql didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/resources/application.yaml didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/repository/AuditEventRepository.java didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/repository/AuditDataRepository.java didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/AuditApplication.java didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/config/WebSecurityConfig.java didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/config/FlywayDataSourceConfiguraion.java didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/config/OAuth2BindingsPropertiesProcessor.java didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/security/JwtRolesToAuthoritiesConverter.java didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/entity/AuditEvent.java didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/entity/AuditData.java didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/resources/AuditResource.java didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/function/AuditSink.java didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/model/AuditEvent.java didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/model/AuditData.java didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/ingress.yaml didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/appSSOInstance.yaml matched [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/scgRoutes.yaml didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/rmqClassClaim.yaml didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/scgInstance.yaml didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/workloads.yaml didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/workloadClientRegistration.yaml matched [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug doc/TAPDeployment.md didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug doc/images/PostalCodeHighLevelArch.png didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/config/workload.yaml didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/Tiltfile didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/pom.xml didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/.gitignore didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/test/java/com/java/example/tanzu/postalsearch/ProtectedGeolocApiApplicationTests.java didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/resources/META-INF/spring.factories didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/resources/db/migration/postgresql/V1.1__Base_version.sql didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/resources/db/migration/h2/V1.1__Base_version.sql didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/resources/db/migration/mariadb/V1.1__Base_version.sql didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/resources/data/usPostalCodeToGeoMapping.csv didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/resources/application.yaml didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/db/migration/postgresql/V2__InitailizeDBData.java didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/db/migration/h2/V2__InitailizeDBData.java didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/db/migration/mariadb/V2__InitailizeDBData.java didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/db/migration/PostalCodeImport.java didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/repository/PostalCodeLocRepository.java didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/config/WebSecurityConfig.java didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/config/FlywayDataSourceConfiguraion.java didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/config/OAuth2BindingsPropertiesProcessor.java didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/security/JwtRolesToAuthoritiesConverter.java didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/security/APIKeyAuthenticationConverter.java didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/security/APIKeyAuthenticationManager.java didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/entity/PotalCodeLoc.java didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/resources/PostalCodeLookup.java didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/resources/AuditedResource.java didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/PotalCodeLookupApplication.java didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/audit/model/AuditEvent.java didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┗ Debug postal-code-search/src/main/java/com/java/example/tanzu/audit/model/AuditData.java didn't match [**/appSSOInstance.yaml, **/workloadClientRegistration.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.delegate.transformations[0].sources[3].delegate.transformations[1] (YTT)
┃ ┃ ┃ ┃ ┃ ┃ Debug Wrote values file with json content:   {"appDomain":"35.188.35.143.nip.io","rateLimit":{"requestLimitMaxRequests":5,"requestLimitTimeWindow":1,"requestLimitWindowUnits":"s"},"appSSOName":"appsso-postal-codes","artifactVersion":"0.0.1-beta","includeBuildToolWrapper":true,"gatewayName":"gateway-postal-codes","msgbrokerName":"msgbroker-postal-codes","enableRateLimiting":false,"artifactId":"spring-secure-resource-server","clusterIssuerName":"tap-ingress-selfsigned","projectName":"spring-secure-resource-server","workloadNamespace":"default"}
┃ ┃ ┃ ┃ ┃ ┗  Info Shelling out to YTT with args: [ytt, -f, /var/folders/sv/7g686rs906v38snwbz438xsr0000gq/T/ytt-input17951837184190796619, --data-values-file, /var/folders/sv/7g686rs906v38snwbz438xsr0000gq/T/accelerator-options9192139200866238128.json, --output-files, /var/folders/sv/7g686rs906v38snwbz438xsr0000gq/T/ytt-output11241553306853672589]
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.delegate.transformations[0].sources[3].delegate.transformations[2] (RewritePath)
┃ ┃ ┃ ┃ ┃ ┗ Debug Path 'templates/appSSOInstance.yaml' matched 'templates/appSSOInstance.yaml' with groups {g0=templates/appSSOInstance.yaml} and was rewritten to 'config/service-operator/appSSOInstance.yaml'
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.delegate.transformations[0].sources[3].delegate.transformations[3] (RewritePath)
┃ ┃ ┃ ┃ ┗ ┗ Debug Path 'templates/workloadClientRegistration.yaml' matched 'templates/workloadClientRegistration.yaml' with groups {g0=templates/workloadClientRegistration.yaml} and was rewritten to 'config/app-operator/workloadClientRegistration.yaml'
┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.delegate.transformations[0].sources[4] (InvokeFragment)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.delegate.transformations[0].sources[4].validated (Combo)
┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[1].validated.delegate.transformations[0].sources[4].validated.delegate (Chain)
┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(Merge, UniquePath)
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.delegate.transformations[0].sources[4].validated.delegate.transformations[0] (Merge)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Running Merge(Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.delegate.transformations[0].sources[4].validated.delegate.transformations[0].sources[0] (Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Condition (#includeBuildToolWrapper) evaluated to true
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Include
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[1].validated.delegate.transformations[0].sources[4].validated.delegate.transformations[0].sources[0].delegate (Include)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will include [mvnw, mvnw.cmd, .mvn/**]
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/tsconfig.node.json didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/index.html didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/tsconfig.app.json didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/config/workload.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/env.d.ts didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/README.md didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/public/favicon.svg didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/.gitignore didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/package-lock.json didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/package.json didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/tsconfig.json didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/nginx.conf didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/vite.config.ts didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/src/App.vue didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/src/main.ts didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/src/stores/counter.ts didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/src/components/Search.vue didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/src/components/Landing.vue didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/src/views/HomeView.vue didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/src/views/SearchView.vue didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/src/assets/main.css didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/src/assets/base.css didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/src/router/index.ts didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/resources/sso/postal-code-sso-resource.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/resources/db/postal-code-db-resource.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/resources/messaging/postal-code-messaging-resource.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/resources/gateway/postal-code-gateway-resource.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/groups/org.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/postal-code-search-ui/postal-code-search-ui.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/postal-code-audit/postal-code-audit.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/postal-code-audit-ui/postal-code-audit-ui.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/postal-code-search/postal-code-search.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/systems/postal-code-system.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/tsconfig.node.json didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/index.html didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/tsconfig.app.json didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/config/workload.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/env.d.ts didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/README.md didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/public/favicon.svg didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/.gitignore didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/package-lock.json didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/package.json didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/tsconfig.json didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/nginx.conf didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/vite.config.ts didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/src/App.vue didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/src/main.ts didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/src/stores/counter.ts didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/src/components/Audit.vue didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/src/components/Landing.vue didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/src/views/AuditView.vue didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/src/views/HomeView.vue didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/src/assets/main.css didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/src/assets/base.css didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/src/router/index.ts didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-client/pom.xml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-client/.gitignore didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-client/src/test/java/com/java/example/tanzu/postalcode/PostalCodeClientApplicationTests.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-client/src/main/resources/application.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-client/src/main/java/com/java/example/tanzu/postalsearch/exchange/PostalCodeLoc.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-client/src/main/java/com/java/example/tanzu/postalsearch/exchange/PostalCodeSearchClient.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-client/src/main/java/com/java/example/tanzu/postalsearch/config/DeclarativeClientConfig.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-client/src/main/java/com/java/example/tanzu/postalsearch/PostalCodeClientApplication.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-client/src/main/java/com/java/example/tanzu/postalsearch/commands/SearchCommand.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit/config/workload.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit/Tiltfile didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit/pom.xml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit/.gitignore didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/test/java/com/java/example/tanzu/audit/AuditApplicationTests.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/resources/META-INF/spring.factories didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/resources/db/migration/postgresql/V1.1__Base_version.sql didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/resources/db/migration/h2/V1.1__Base_version.sql didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/resources/db/migration/mariadb/V1.1__Base_version.sql didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/resources/application.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/repository/AuditEventRepository.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/repository/AuditDataRepository.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/AuditApplication.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/config/WebSecurityConfig.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/config/FlywayDataSourceConfiguraion.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/config/OAuth2BindingsPropertiesProcessor.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/security/JwtRolesToAuthoritiesConverter.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/entity/AuditEvent.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/entity/AuditData.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/resources/AuditResource.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/function/AuditSink.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/model/AuditEvent.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/model/AuditData.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/ingress.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/appSSOInstance.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/scgRoutes.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/rmqClassClaim.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/scgInstance.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/workloads.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/workloadClientRegistration.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug doc/TAPDeployment.md didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug doc/images/PostalCodeHighLevelArch.png didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/config/workload.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/Tiltfile didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/pom.xml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/.gitignore didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/test/java/com/java/example/tanzu/postalsearch/ProtectedGeolocApiApplicationTests.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/resources/META-INF/spring.factories didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/resources/db/migration/postgresql/V1.1__Base_version.sql didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/resources/db/migration/h2/V1.1__Base_version.sql didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/resources/db/migration/mariadb/V1.1__Base_version.sql didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/resources/data/usPostalCodeToGeoMapping.csv didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/resources/application.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/db/migration/postgresql/V2__InitailizeDBData.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/db/migration/h2/V2__InitailizeDBData.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/db/migration/mariadb/V2__InitailizeDBData.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/db/migration/PostalCodeImport.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/repository/PostalCodeLocRepository.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/config/WebSecurityConfig.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/config/FlywayDataSourceConfiguraion.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/config/OAuth2BindingsPropertiesProcessor.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/security/JwtRolesToAuthoritiesConverter.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/security/APIKeyAuthenticationConverter.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/security/APIKeyAuthenticationManager.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/entity/PotalCodeLoc.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/resources/PostalCodeLookup.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/resources/AuditedResource.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/PotalCodeLookupApplication.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/audit/model/AuditEvent.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/audit/model/AuditData.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug mvnw.cmd matched [mvnw, mvnw.cmd, .mvn/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.properties matched [mvnw, mvnw.cmd, .mvn/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┗ ┗ Debug mvnw matched [mvnw, mvnw.cmd, .mvn/**] -> included
┃ ┃ ┃ ┃ ┗ ┗ ╺ engine.transformations[1].validated.delegate.transformations[0].sources[4].validated.delegate.transformations[1] (UniquePath)
┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.delegate.transformations[0].sources[5] (Combo)
┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ engine.transformations[1].validated.delegate.transformations[0].sources[5].delegate (Chain)
┃ ┃ ┃ ┃ ┃  Info Running Chain(InvokeFragment, RewritePath)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.delegate.transformations[0].sources[5].delegate.transformations[0] (InvokeFragment)
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.delegate.transformations[0].sources[5].delegate.transformations[0].validated (Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[1].validated.delegate.transformations[0].sources[5].delegate.transformations[0].validated.delegate (Chain)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(Merge, UniquePath)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.delegate.transformations[0].sources[5].delegate.transformations[0].validated.delegate.transformations[0] (Merge)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Running Merge(Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.delegate.transformations[0].sources[5].delegate.transformations[0].validated.delegate.transformations[0].sources[0] (Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Condition (#includeBuildToolWrapper) evaluated to true
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Include
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[1].validated.delegate.transformations[0].sources[5].delegate.transformations[0].validated.delegate.transformations[0].sources[0].delegate (Include)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will include [mvnw, mvnw.cmd, .mvn/**]
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/tsconfig.node.json didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/index.html didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/tsconfig.app.json didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/config/workload.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/env.d.ts didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/README.md didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/public/favicon.svg didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/.gitignore didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/package-lock.json didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/package.json didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/tsconfig.json didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/nginx.conf didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/vite.config.ts didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/src/App.vue didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/src/main.ts didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/src/stores/counter.ts didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/src/components/Search.vue didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/src/components/Landing.vue didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/src/views/HomeView.vue didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/src/views/SearchView.vue didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/src/assets/main.css didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/src/assets/base.css didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/src/router/index.ts didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/resources/sso/postal-code-sso-resource.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/resources/db/postal-code-db-resource.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/resources/messaging/postal-code-messaging-resource.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/resources/gateway/postal-code-gateway-resource.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/groups/org.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/postal-code-search-ui/postal-code-search-ui.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/postal-code-audit/postal-code-audit.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/postal-code-audit-ui/postal-code-audit-ui.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/postal-code-search/postal-code-search.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/systems/postal-code-system.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/tsconfig.node.json didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/index.html didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/tsconfig.app.json didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/config/workload.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/env.d.ts didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/README.md didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/public/favicon.svg didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/.gitignore didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/package-lock.json didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/package.json didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/tsconfig.json didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/nginx.conf didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/vite.config.ts didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/src/App.vue didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/src/main.ts didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/src/stores/counter.ts didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/src/components/Audit.vue didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/src/components/Landing.vue didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/src/views/AuditView.vue didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/src/views/HomeView.vue didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/src/assets/main.css didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/src/assets/base.css didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/src/router/index.ts didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-client/pom.xml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-client/.gitignore didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-client/src/test/java/com/java/example/tanzu/postalcode/PostalCodeClientApplicationTests.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-client/src/main/resources/application.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-client/src/main/java/com/java/example/tanzu/postalsearch/exchange/PostalCodeLoc.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-client/src/main/java/com/java/example/tanzu/postalsearch/exchange/PostalCodeSearchClient.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-client/src/main/java/com/java/example/tanzu/postalsearch/config/DeclarativeClientConfig.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-client/src/main/java/com/java/example/tanzu/postalsearch/PostalCodeClientApplication.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-client/src/main/java/com/java/example/tanzu/postalsearch/commands/SearchCommand.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit/config/workload.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit/Tiltfile didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit/pom.xml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit/.gitignore didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/test/java/com/java/example/tanzu/audit/AuditApplicationTests.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/resources/META-INF/spring.factories didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/resources/db/migration/postgresql/V1.1__Base_version.sql didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/resources/db/migration/h2/V1.1__Base_version.sql didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/resources/db/migration/mariadb/V1.1__Base_version.sql didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/resources/application.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/repository/AuditEventRepository.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/repository/AuditDataRepository.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/AuditApplication.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/config/WebSecurityConfig.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/config/FlywayDataSourceConfiguraion.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/config/OAuth2BindingsPropertiesProcessor.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/security/JwtRolesToAuthoritiesConverter.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/entity/AuditEvent.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/entity/AuditData.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/resources/AuditResource.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/function/AuditSink.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/model/AuditEvent.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/model/AuditData.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/ingress.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/appSSOInstance.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/scgRoutes.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/rmqClassClaim.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/scgInstance.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/workloads.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/workloadClientRegistration.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug doc/TAPDeployment.md didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug doc/images/PostalCodeHighLevelArch.png didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/config/workload.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/Tiltfile didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/pom.xml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/.gitignore didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/test/java/com/java/example/tanzu/postalsearch/ProtectedGeolocApiApplicationTests.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/resources/META-INF/spring.factories didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/resources/db/migration/postgresql/V1.1__Base_version.sql didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/resources/db/migration/h2/V1.1__Base_version.sql didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/resources/db/migration/mariadb/V1.1__Base_version.sql didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/resources/data/usPostalCodeToGeoMapping.csv didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/resources/application.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/db/migration/postgresql/V2__InitailizeDBData.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/db/migration/h2/V2__InitailizeDBData.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/db/migration/mariadb/V2__InitailizeDBData.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/db/migration/PostalCodeImport.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/repository/PostalCodeLocRepository.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/config/WebSecurityConfig.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/config/FlywayDataSourceConfiguraion.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/config/OAuth2BindingsPropertiesProcessor.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/security/JwtRolesToAuthoritiesConverter.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/security/APIKeyAuthenticationConverter.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/security/APIKeyAuthenticationManager.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/entity/PotalCodeLoc.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/resources/PostalCodeLookup.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/resources/AuditedResource.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/PotalCodeLookupApplication.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/audit/model/AuditEvent.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/audit/model/AuditData.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug mvnw.cmd matched [mvnw, mvnw.cmd, .mvn/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.properties matched [mvnw, mvnw.cmd, .mvn/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ ┗ Debug mvnw matched [mvnw, mvnw.cmd, .mvn/**] -> included
┃ ┃ ┃ ┃ ┃ ┗ ┗ ╺ engine.transformations[1].validated.delegate.transformations[0].sources[5].delegate.transformations[0].validated.delegate.transformations[1] (UniquePath)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.delegate.transformations[0].sources[5].delegate.transformations[1] (RewritePath)
┃ ┃ ┃ ┃ ┃ ┃ Debug Path 'mvnw' matched '^(?<folder>.*/)?(?<filename>([^/]+?|)(?=(?<ext>\.[^/.]*)?)$)' with groups {ext=null, folder=null, filename=mvnw, g0=mvnw, g1=null, g2=mvnw, g3=mvnw, g4=null} and was rewritten to 'audit/mvnw'
┃ ┃ ┃ ┃ ┃ ┃ Debug Path 'mvnw.cmd' matched '^(?<folder>.*/)?(?<filename>([^/]+?|)(?=(?<ext>\.[^/.]*)?)$)' with groups {ext=.cmd, folder=null, filename=mvnw.cmd, g0=mvnw.cmd, g1=null, g2=mvnw.cmd, g3=mvnw.cmd, g4=.cmd} and was rewritten to 'audit/mvnw.cmd'
┃ ┃ ┃ ┃ ┗ ┗ Debug Path '.mvn/wrapper/maven-wrapper.properties' matched '^(?<folder>.*/)?(?<filename>([^/]+?|)(?=(?<ext>\.[^/.]*)?)$)' with groups {ext=.properties, folder=.mvn/wrapper/, filename=maven-wrapper.properties, g0=.mvn/wrapper/maven-wrapper.properties, g1=.mvn/wrapper/, g2=maven-wrapper.properties, g3=maven-wrapper.properties, g4=.properties} and was rewritten to 'audit/.mvn/wrapper/maven-wrapper.properties'
┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.delegate.transformations[0].sources[6] (Combo)
┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ engine.transformations[1].validated.delegate.transformations[0].sources[6].delegate (Chain)
┃ ┃ ┃ ┃ ┃  Info Running Chain(InvokeFragment, RewritePath)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.delegate.transformations[0].sources[6].delegate.transformations[0] (InvokeFragment)
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.delegate.transformations[0].sources[6].delegate.transformations[0].validated (Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[1].validated.delegate.transformations[0].sources[6].delegate.transformations[0].validated.delegate (Chain)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(Merge, UniquePath)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.delegate.transformations[0].sources[6].delegate.transformations[0].validated.delegate.transformations[0] (Merge)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Running Merge(Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.delegate.transformations[0].sources[6].delegate.transformations[0].validated.delegate.transformations[0].sources[0] (Combo)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Condition (#includeBuildToolWrapper) evaluated to true
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Combo running as Include
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[1].validated.delegate.transformations[0].sources[6].delegate.transformations[0].validated.delegate.transformations[0].sources[0].delegate (Include)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will include [mvnw, mvnw.cmd, .mvn/**]
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/tsconfig.node.json didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/index.html didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/tsconfig.app.json didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/config/workload.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/env.d.ts didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/README.md didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/public/favicon.svg didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/.gitignore didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/package-lock.json didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/package.json didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/tsconfig.json didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/nginx.conf didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/vite.config.ts didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/src/App.vue didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/src/main.ts didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/src/stores/counter.ts didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/src/components/Search.vue didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/src/components/Landing.vue didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/src/views/HomeView.vue didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/src/views/SearchView.vue didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/src/assets/main.css didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/src/assets/base.css didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/src/router/index.ts didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/resources/sso/postal-code-sso-resource.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/resources/db/postal-code-db-resource.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/resources/messaging/postal-code-messaging-resource.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/resources/gateway/postal-code-gateway-resource.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/groups/org.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/postal-code-search-ui/postal-code-search-ui.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/postal-code-audit/postal-code-audit.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/postal-code-audit-ui/postal-code-audit-ui.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/postal-code-search/postal-code-search.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/systems/postal-code-system.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/tsconfig.node.json didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/index.html didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/tsconfig.app.json didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/config/workload.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/env.d.ts didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/README.md didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/public/favicon.svg didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/.gitignore didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/package-lock.json didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/package.json didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/tsconfig.json didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/nginx.conf didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/vite.config.ts didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/src/App.vue didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/src/main.ts didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/src/stores/counter.ts didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/src/components/Audit.vue didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/src/components/Landing.vue didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/src/views/AuditView.vue didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/src/views/HomeView.vue didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/src/assets/main.css didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/src/assets/base.css didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/src/router/index.ts didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-client/pom.xml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-client/.gitignore didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-client/src/test/java/com/java/example/tanzu/postalcode/PostalCodeClientApplicationTests.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-client/src/main/resources/application.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-client/src/main/java/com/java/example/tanzu/postalsearch/exchange/PostalCodeLoc.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-client/src/main/java/com/java/example/tanzu/postalsearch/exchange/PostalCodeSearchClient.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-client/src/main/java/com/java/example/tanzu/postalsearch/config/DeclarativeClientConfig.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-client/src/main/java/com/java/example/tanzu/postalsearch/PostalCodeClientApplication.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-client/src/main/java/com/java/example/tanzu/postalsearch/commands/SearchCommand.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit/config/workload.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit/Tiltfile didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit/pom.xml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit/.gitignore didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/test/java/com/java/example/tanzu/audit/AuditApplicationTests.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/resources/META-INF/spring.factories didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/resources/db/migration/postgresql/V1.1__Base_version.sql didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/resources/db/migration/h2/V1.1__Base_version.sql didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/resources/db/migration/mariadb/V1.1__Base_version.sql didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/resources/application.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/repository/AuditEventRepository.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/repository/AuditDataRepository.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/AuditApplication.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/config/WebSecurityConfig.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/config/FlywayDataSourceConfiguraion.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/config/OAuth2BindingsPropertiesProcessor.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/security/JwtRolesToAuthoritiesConverter.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/entity/AuditEvent.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/entity/AuditData.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/resources/AuditResource.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/function/AuditSink.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/model/AuditEvent.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/model/AuditData.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/ingress.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/appSSOInstance.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/scgRoutes.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/rmqClassClaim.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/scgInstance.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/workloads.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug templates/workloadClientRegistration.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug doc/TAPDeployment.md didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug doc/images/PostalCodeHighLevelArch.png didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/config/workload.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/Tiltfile didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/pom.xml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/.gitignore didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/test/java/com/java/example/tanzu/postalsearch/ProtectedGeolocApiApplicationTests.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/resources/META-INF/spring.factories didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/resources/db/migration/postgresql/V1.1__Base_version.sql didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/resources/db/migration/h2/V1.1__Base_version.sql didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/resources/db/migration/mariadb/V1.1__Base_version.sql didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/resources/data/usPostalCodeToGeoMapping.csv didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/resources/application.yaml didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/db/migration/postgresql/V2__InitailizeDBData.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/db/migration/h2/V2__InitailizeDBData.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/db/migration/mariadb/V2__InitailizeDBData.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/db/migration/PostalCodeImport.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/repository/PostalCodeLocRepository.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/config/WebSecurityConfig.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/config/FlywayDataSourceConfiguraion.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/config/OAuth2BindingsPropertiesProcessor.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/security/JwtRolesToAuthoritiesConverter.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/security/APIKeyAuthenticationConverter.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/security/APIKeyAuthenticationManager.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/entity/PotalCodeLoc.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/resources/PostalCodeLookup.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/resources/AuditedResource.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/PotalCodeLookupApplication.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/audit/model/AuditEvent.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/audit/model/AuditData.java didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug mvnw.cmd matched [mvnw, mvnw.cmd, .mvn/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [mvnw, mvnw.cmd, .mvn/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.properties matched [mvnw, mvnw.cmd, .mvn/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ ┗ Debug mvnw matched [mvnw, mvnw.cmd, .mvn/**] -> included
┃ ┃ ┃ ┃ ┃ ┗ ┗ ╺ engine.transformations[1].validated.delegate.transformations[0].sources[6].delegate.transformations[0].validated.delegate.transformations[1] (UniquePath)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.delegate.transformations[0].sources[6].delegate.transformations[1] (RewritePath)
┃ ┃ ┃ ┃ ┃ ┃ Debug Path 'mvnw' matched '^(?<folder>.*/)?(?<filename>([^/]+?|)(?=(?<ext>\.[^/.]*)?)$)' with groups {ext=null, folder=null, filename=mvnw, g0=mvnw, g1=null, g2=mvnw, g3=mvnw, g4=null} and was rewritten to 'postal-code-search/mvnw'
┃ ┃ ┃ ┃ ┃ ┃ Debug Path 'mvnw.cmd' matched '^(?<folder>.*/)?(?<filename>([^/]+?|)(?=(?<ext>\.[^/.]*)?)$)' with groups {ext=.cmd, folder=null, filename=mvnw.cmd, g0=mvnw.cmd, g1=null, g2=mvnw.cmd, g3=mvnw.cmd, g4=.cmd} and was rewritten to 'postal-code-search/mvnw.cmd'
┃ ┃ ┃ ┃ ┗ ┗ Debug Path '.mvn/wrapper/maven-wrapper.properties' matched '^(?<folder>.*/)?(?<filename>([^/]+?|)(?=(?<ext>\.[^/.]*)?)$)' with groups {ext=.properties, folder=.mvn/wrapper/, filename=maven-wrapper.properties, g0=.mvn/wrapper/maven-wrapper.properties, g1=.mvn/wrapper/, g2=maven-wrapper.properties, g3=maven-wrapper.properties, g4=.properties} and was rewritten to 'postal-code-search/.mvn/wrapper/maven-wrapper.properties'
┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.delegate.transformations[0].sources[7] (Combo)
┃ ┃ ┃ ┃ ┃  Info Combo running as Chain
┃ ┃ ┃ ┃ ┃ engine.transformations[1].validated.delegate.transformations[0].sources[7].delegate (Chain)
┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, InvokeFragment)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.delegate.transformations[0].sources[7].delegate.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃  Info Will include [**/config/**]
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/tsconfig.node.json didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/index.html didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/tsconfig.app.json didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/config/workload.yaml matched [**/config/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/env.d.ts didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/README.md didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/public/favicon.svg didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/.gitignore didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/package-lock.json didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/package.json didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/tsconfig.json didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/nginx.conf didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/vite.config.ts didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/src/App.vue didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/src/main.ts didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/src/stores/counter.ts didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/src/components/Search.vue didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/src/components/Landing.vue didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/src/views/HomeView.vue didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/src/views/SearchView.vue didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/src/assets/main.css didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/src/assets/base.css didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/src/router/index.ts didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/resources/sso/postal-code-sso-resource.yaml didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/resources/db/postal-code-db-resource.yaml didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/resources/messaging/postal-code-messaging-resource.yaml didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/resources/gateway/postal-code-gateway-resource.yaml didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/groups/org.yaml didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/postal-code-search-ui/postal-code-search-ui.yaml didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/postal-code-audit/postal-code-audit.yaml didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/postal-code-audit-ui/postal-code-audit-ui.yaml didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/postal-code-search/postal-code-search.yaml didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/systems/postal-code-system.yaml didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/tsconfig.node.json didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/index.html didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/tsconfig.app.json didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/config/workload.yaml matched [**/config/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/env.d.ts didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/README.md didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/public/favicon.svg didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/.gitignore didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/package-lock.json didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/package.json didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/tsconfig.json didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/nginx.conf didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/vite.config.ts didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/src/App.vue didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/src/main.ts didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/src/stores/counter.ts didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/src/components/Audit.vue didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/src/components/Landing.vue didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/src/views/AuditView.vue didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/src/views/HomeView.vue didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/src/assets/main.css didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/src/assets/base.css didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/src/router/index.ts didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-client/pom.xml didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-client/.gitignore didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-client/src/test/java/com/java/example/tanzu/postalcode/PostalCodeClientApplicationTests.java didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-client/src/main/resources/application.yaml didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-client/src/main/java/com/java/example/tanzu/postalsearch/exchange/PostalCodeLoc.java didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-client/src/main/java/com/java/example/tanzu/postalsearch/exchange/PostalCodeSearchClient.java didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-client/src/main/java/com/java/example/tanzu/postalsearch/config/DeclarativeClientConfig.java matched [**/config/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-client/src/main/java/com/java/example/tanzu/postalsearch/PostalCodeClientApplication.java didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-client/src/main/java/com/java/example/tanzu/postalsearch/commands/SearchCommand.java didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit/config/workload.yaml matched [**/config/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug audit/Tiltfile didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit/pom.xml didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit/.gitignore didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/test/java/com/java/example/tanzu/audit/AuditApplicationTests.java didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/resources/META-INF/spring.factories didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/resources/db/migration/postgresql/V1.1__Base_version.sql didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/resources/db/migration/h2/V1.1__Base_version.sql didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/resources/db/migration/mariadb/V1.1__Base_version.sql didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/resources/application.yaml didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/repository/AuditEventRepository.java didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/repository/AuditDataRepository.java didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/AuditApplication.java didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/config/WebSecurityConfig.java matched [**/config/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/config/FlywayDataSourceConfiguraion.java matched [**/config/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/config/OAuth2BindingsPropertiesProcessor.java matched [**/config/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/security/JwtRolesToAuthoritiesConverter.java didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/entity/AuditEvent.java didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/entity/AuditData.java didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/resources/AuditResource.java didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/function/AuditSink.java didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/model/AuditEvent.java didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/model/AuditData.java didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/ingress.yaml didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/appSSOInstance.yaml didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/scgRoutes.yaml didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/rmqClassClaim.yaml didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/scgInstance.yaml didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/workloads.yaml didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/workloadClientRegistration.yaml didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug doc/TAPDeployment.md didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug doc/images/PostalCodeHighLevelArch.png didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/config/workload.yaml matched [**/config/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/Tiltfile didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/pom.xml didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/.gitignore didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/test/java/com/java/example/tanzu/postalsearch/ProtectedGeolocApiApplicationTests.java didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/resources/META-INF/spring.factories didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/resources/db/migration/postgresql/V1.1__Base_version.sql didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/resources/db/migration/h2/V1.1__Base_version.sql didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/resources/db/migration/mariadb/V1.1__Base_version.sql didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/resources/data/usPostalCodeToGeoMapping.csv didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/resources/application.yaml didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/db/migration/postgresql/V2__InitailizeDBData.java didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/db/migration/h2/V2__InitailizeDBData.java didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/db/migration/mariadb/V2__InitailizeDBData.java didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/db/migration/PostalCodeImport.java didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/repository/PostalCodeLocRepository.java didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/config/WebSecurityConfig.java matched [**/config/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/config/FlywayDataSourceConfiguraion.java matched [**/config/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/config/OAuth2BindingsPropertiesProcessor.java matched [**/config/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/security/JwtRolesToAuthoritiesConverter.java didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/security/APIKeyAuthenticationConverter.java didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/security/APIKeyAuthenticationManager.java didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/entity/PotalCodeLoc.java didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/resources/PostalCodeLookup.java didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/resources/AuditedResource.java didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/PotalCodeLookupApplication.java didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/audit/model/AuditEvent.java didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┗ Debug postal-code-search/src/main/java/com/java/example/tanzu/audit/model/AuditData.java didn't match [**/config/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.delegate.transformations[0].sources[7].delegate.transformations[1] (InvokeFragment)
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.delegate.transformations[0].sources[7].delegate.transformations[1].validated (Chain)
┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(Exclude, IfElse)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.delegate.transformations[0].sources[7].delegate.transformations[1].validated.transformations[0] (Exclude)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will exclude [README.md]
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/config/workload.yaml didn't match [README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit-ui/config/workload.yaml didn't match [README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-client/src/main/java/com/java/example/tanzu/postalsearch/config/DeclarativeClientConfig.java didn't match [README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit/config/workload.yaml didn't match [README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/config/WebSecurityConfig.java didn't match [README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/config/FlywayDataSourceConfiguraion.java didn't match [README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/config/OAuth2BindingsPropertiesProcessor.java didn't match [README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/config/workload.yaml didn't match [README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/config/WebSecurityConfig.java didn't match [README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/config/FlywayDataSourceConfiguraion.java didn't match [README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/config/OAuth2BindingsPropertiesProcessor.java didn't match [README.md] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ Debug README.md matched [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.delegate.transformations[0].sources[7].delegate.transformations[1].validated.transformations[1] (IfElse)
┃ ┃ ┃ ┃ ┗ ┗ ┗ ┗ null ()
┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.delegate.transformations[0].sources[8] (Combo)
┃ ┃ ┃ ┃ ┃  Info Combo running as Include
┃ ┃ ┃ ┃ ┃ engine.transformations[1].validated.delegate.transformations[0].sources[8].delegate (Include)
┃ ┃ ┃ ┃ ┃  Info Will include [README.md]
┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/tsconfig.node.json didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/index.html didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/tsconfig.app.json didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/config/workload.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/env.d.ts didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/README.md didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/public/favicon.svg didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/.gitignore didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/package-lock.json didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/package.json didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/tsconfig.json didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/nginx.conf didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/vite.config.ts didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/src/App.vue didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/src/main.ts didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/src/stores/counter.ts didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/src/components/Search.vue didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/src/components/Landing.vue didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/src/views/HomeView.vue didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/src/views/SearchView.vue didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/src/assets/main.css didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/src/assets/base.css didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug postal-code-search-ui/src/router/index.ts didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/resources/sso/postal-code-sso-resource.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/resources/db/postal-code-db-resource.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/resources/messaging/postal-code-messaging-resource.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/resources/gateway/postal-code-gateway-resource.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/groups/org.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/components/postal-code-search-ui/postal-code-search-ui.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/components/postal-code-audit/postal-code-audit.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/components/postal-code-audit-ui/postal-code-audit-ui.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/components/postal-code-search/postal-code-search.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/systems/postal-code-system.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug audit-ui/tsconfig.node.json didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug audit-ui/index.html didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug audit-ui/tsconfig.app.json didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug audit-ui/config/workload.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug audit-ui/env.d.ts didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug audit-ui/README.md didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug audit-ui/public/favicon.svg didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug audit-ui/.gitignore didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug audit-ui/package-lock.json didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug audit-ui/package.json didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug audit-ui/tsconfig.json didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug audit-ui/nginx.conf didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug audit-ui/vite.config.ts didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug audit-ui/src/App.vue didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug audit-ui/src/main.ts didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug audit-ui/src/stores/counter.ts didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug audit-ui/src/components/Audit.vue didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug audit-ui/src/components/Landing.vue didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug audit-ui/src/views/AuditView.vue didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug audit-ui/src/views/HomeView.vue didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug audit-ui/src/assets/main.css didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug audit-ui/src/assets/base.css didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug audit-ui/src/router/index.ts didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug README.md matched [README.md] -> included
┃ ┃ ┃ ┃ ┃ Debug postal-code-client/pom.xml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug postal-code-client/.gitignore didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug postal-code-client/src/test/java/com/java/example/tanzu/postalcode/PostalCodeClientApplicationTests.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug postal-code-client/src/main/resources/application.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug postal-code-client/src/main/java/com/java/example/tanzu/postalsearch/exchange/PostalCodeLoc.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug postal-code-client/src/main/java/com/java/example/tanzu/postalsearch/exchange/PostalCodeSearchClient.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug postal-code-client/src/main/java/com/java/example/tanzu/postalsearch/config/DeclarativeClientConfig.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug postal-code-client/src/main/java/com/java/example/tanzu/postalsearch/PostalCodeClientApplication.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug postal-code-client/src/main/java/com/java/example/tanzu/postalsearch/commands/SearchCommand.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug audit/config/workload.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug audit/Tiltfile didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug audit/pom.xml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug audit/.gitignore didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug audit/src/test/java/com/java/example/tanzu/audit/AuditApplicationTests.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug audit/src/main/resources/META-INF/spring.factories didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug audit/src/main/resources/db/migration/postgresql/V1.1__Base_version.sql didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug audit/src/main/resources/db/migration/h2/V1.1__Base_version.sql didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug audit/src/main/resources/db/migration/mariadb/V1.1__Base_version.sql didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug audit/src/main/resources/application.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/repository/AuditEventRepository.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/repository/AuditDataRepository.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/AuditApplication.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/config/WebSecurityConfig.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/config/FlywayDataSourceConfiguraion.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/config/OAuth2BindingsPropertiesProcessor.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/security/JwtRolesToAuthoritiesConverter.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/entity/AuditEvent.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/entity/AuditData.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/resources/AuditResource.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/function/AuditSink.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/model/AuditEvent.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug audit/src/main/java/com/java/example/tanzu/audit/model/AuditData.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug templates/ingress.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug templates/appSSOInstance.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug templates/scgRoutes.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug templates/rmqClassClaim.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug templates/scgInstance.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug templates/workloads.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug templates/workloadClientRegistration.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug doc/TAPDeployment.md didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug doc/images/PostalCodeHighLevelArch.png didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug postal-code-search/config/workload.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug postal-code-search/Tiltfile didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug postal-code-search/pom.xml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug postal-code-search/.gitignore didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/test/java/com/java/example/tanzu/postalsearch/ProtectedGeolocApiApplicationTests.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/resources/META-INF/spring.factories didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/resources/db/migration/postgresql/V1.1__Base_version.sql didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/resources/db/migration/h2/V1.1__Base_version.sql didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/resources/db/migration/mariadb/V1.1__Base_version.sql didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/resources/data/usPostalCodeToGeoMapping.csv didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/resources/application.yaml didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/db/migration/postgresql/V2__InitailizeDBData.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/db/migration/h2/V2__InitailizeDBData.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/db/migration/mariadb/V2__InitailizeDBData.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/db/migration/PostalCodeImport.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/repository/PostalCodeLocRepository.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/config/WebSecurityConfig.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/config/FlywayDataSourceConfiguraion.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/config/OAuth2BindingsPropertiesProcessor.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/security/JwtRolesToAuthoritiesConverter.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/security/APIKeyAuthenticationConverter.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/security/APIKeyAuthenticationManager.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/entity/PotalCodeLoc.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/resources/PostalCodeLookup.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/resources/AuditedResource.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/PotalCodeLookupApplication.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┃ Debug postal-code-search/src/main/java/com/java/example/tanzu/audit/model/AuditEvent.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┃ ┗ Debug postal-code-search/src/main/java/com/java/example/tanzu/audit/model/AuditData.java didn't match [README.md] -> excluded
┃ ┃ ┃ ┗ ╺ engine.transformations[1].validated.delegate.transformations[0].sources[9] (Provenance)
┃ ┃ ┃ ┏ engine.transformations[1].validated.delegate.transformations[1] (UniquePath)
┃ ┃ ┃ ┃ Debug Multiple representations for path 'postal-code-client/src/main/java/com/java/example/tanzu/postalsearch/config/DeclarativeClientConfig.java', will use the one appearing last 
┃ ┃ ┃ ┃ Debug Multiple representations for path 'audit/config/workload.yaml', will use the one appearing last 
┃ ┃ ┃ ┃ Debug Multiple representations for path 'audit/src/main/java/com/java/example/tanzu/audit/config/OAuth2BindingsPropertiesProcessor.java', will use the one appearing last 
┃ ┃ ┃ ┃ Debug Multiple representations for path 'audit/src/main/java/com/java/example/tanzu/audit/config/FlywayDataSourceConfiguraion.java', will use the one appearing last 
┃ ┃ ┃ ┃ Debug Multiple representations for path 'postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/config/WebSecurityConfig.java', will use the one appearing last 
┃ ┃ ┃ ┃ Debug Multiple representations for path 'audit/src/main/java/com/java/example/tanzu/audit/config/WebSecurityConfig.java', will use the one appearing last 
┃ ┃ ┃ ┃ Debug Multiple representations for path 'postal-code-search/config/workload.yaml', will use the one appearing last 
┃ ┃ ┃ ┃ Debug Multiple representations for path 'postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/config/FlywayDataSourceConfiguraion.java', will use the one appearing last 
┃ ┃ ┃ ┃ Debug Multiple representations for path 'README.md', will use the one appearing last 
┃ ┃ ┃ ┃ Debug Multiple representations for path 'postal-code-search-ui/config/workload.yaml', will use the one appearing last 
┃ ┃ ┃ ┃ Debug Multiple representations for path 'postal-code-search/src/main/java/com/java/example/tanzu/postalsearch/config/OAuth2BindingsPropertiesProcessor.java', will use the one appearing last 
┃ ┗ ┗ ┗ Debug Multiple representations for path 'audit-ui/config/workload.yaml', will use the one appearing last 
┗ ╺ engine.transformations[2] (UniquePath)
```
