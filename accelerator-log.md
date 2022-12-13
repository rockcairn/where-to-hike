# Accelerator Log

## Options
```json
{
  "createRabbitMQCluster" : true,
  "createResourceClaim" : true,
  "dbType" : "h2",
  "enableSecurity" : false,
  "numRabbitMQClusterNodes" : 1,
  "projectName" : "where-to-hike",
  "rabbitMQName" : "rmq-where-to-hike",
  "serviceNamespace" : "apenner",
  "workloadNamespace" : "apenner"
}
```
## Log
```
┏ engine (Chain)
┃  Info Running Chain(GeneratorValidationTransform, UniquePath)
┃ ┏ ┏ engine.transformations[0].validated (Combo)
┃ ┃ ┃  Info Combo running as Chain(Merge(merge), UniquePath(UseLast))
┃ ┃ ┃ engine.transformations[0].validated.merge (Chain)
┃ ┃ ┃  Info Running Chain(Merge, UniquePath)
┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0] (Merge)
┃ ┃ ┃ ┃  Info Running Merge(Combo, Combo, Combo, Combo, Combo, Combo, Combo)
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[0] (Combo)
┃ ┃ ┃ ┃ ┃  Info Combo running as Exclude
┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.merge.transformations[0].sources[0].exclude (Exclude)
┃ ┃ ┃ ┃ ┃  Info Will exclude [**/templates/**, **/icons/**, **/.git/**, **/deployment/**]
┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.properties didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug catalog/components/hungryman-api-gateway/hungryman-api-gateway.yaml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug catalog/components/hungryman-availability/hungryman-availability.yaml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug catalog/components/hungryman-notify/hungryman-notify.yaml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug catalog/components/hungryman-search/hungryman-search.yaml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug catalog/components/hungryman-search-proc/hungryman-search-proc.yaml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug catalog/components/hungryman-ui/hungryman-ui.yaml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug catalog/groups/org.yaml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug catalog/resources/db/hungryman-db-resource.yaml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug catalog/resources/messaging/hungryman-messaging-resource.yaml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug catalog/systems/hungryman-system.yaml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug doc/TAPDeployment.md didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug doc/images/AppHomeScreen.png didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug doc/images/HungrymanHighLevelArch.png didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug doc/images/KNativeEventing.png didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug doc/images/SCSMessaging.png didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug icons/hungryman.png matched [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> excluded
┃ ┃ ┃ ┃ ┃ Debug mvnw didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug mvnw.cmd didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug templates/appSSOInstance.yaml matched [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> excluded
┃ ┃ ┃ ┃ ┃ Debug templates/clientRegistrationResourceClaim.yaml matched [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> excluded
┃ ┃ ┃ ┃ ┃ Debug templates/mysqlInstance.yaml matched [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> excluded
┃ ┃ ┃ ┃ ┃ Debug templates/mysqlResourceClaim.yaml matched [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> excluded
┃ ┃ ┃ ┃ ┃ Debug templates/rmqCluster.yaml matched [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> excluded
┃ ┃ ┃ ┃ ┃ Debug templates/rmqResourceClaim.yaml matched [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> excluded
┃ ┃ ┃ ┃ ┃ Debug templates/workloads.yaml matched [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> excluded
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-api-gateway/.gitignore didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-api-gateway/Tiltfile didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-api-gateway/config/workload.yaml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-api-gateway/pom.xml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-api-gateway/src/main/java/com/java/example/tanzu/hungryman/HungrymanAPIGatewayApplication.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-api-gateway/src/main/resources/application.yaml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-availability/.gitignore didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-availability/.mvn/wrapper/maven-wrapper.properties didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-availability/Tiltfile didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-availability/config/workload.yaml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-availability/mvnw didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-availability/mvnw.cmd didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-availability/pom.xml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-availability/src/main/java/com/java/example/tanzu/hungryman/HungrymanAvailabilityApplication.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-availability/src/main/java/com/java/example/tanzu/hungryman/config/OAuth2BindingsPropertiesProcessor.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-availability/src/main/java/com/java/example/tanzu/hungryman/config/WebSecurityConfig.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-availability/src/main/java/com/java/example/tanzu/hungryman/entity/Availability.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-availability/src/main/java/com/java/example/tanzu/hungryman/entity/AvailabilityWindow.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-availability/src/main/java/com/java/example/tanzu/hungryman/function/AvailabilitySink.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-availability/src/main/java/com/java/example/tanzu/hungryman/model/Availability.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-availability/src/main/java/com/java/example/tanzu/hungryman/repository/AvailabilityRepository.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-availability/src/main/java/com/java/example/tanzu/hungryman/repository/AvailabilityWindowRepository.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-availability/src/main/java/com/java/example/tanzu/hungryman/resources/AvailabilityResource.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-availability/src/main/resources/META-INF/spring.factories didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-availability/src/main/resources/application.yaml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-availability/src/main/resources/schema.sql didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-availability/src/test/java/com/java/example/tanzu/hungryman/HungrymanAvailabilityApplicationTests.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-crawler/.gitignore didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-crawler/.mvn/wrapper/maven-wrapper.properties didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-crawler/config/workload.yaml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-crawler/mvnw didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-crawler/mvnw.cmd didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-crawler/pom.xml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-crawler/src/main/java/com/java/example/tanzu/hungryman/HungrymanCrawlerApplication.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-crawler/src/main/java/com/java/example/tanzu/hungryman/model/Availability.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-crawler/src/main/java/com/java/example/tanzu/hungryman/model/SearchCriteria.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-crawler/src/main/java/com/java/example/tanzu/hungryman/resources/SearchResource.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-crawler/src/main/resources/application.properties didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-crawler/src/test/java/com/java/example/tanzu/hungryman/HungrymanCrawlerApplicationTests.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-notify/.gitignore didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-notify/.mvn/wrapper/maven-wrapper.properties didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-notify/README.md didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-notify/Tiltfile didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-notify/config/workload.yaml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-notify/mvnw didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-notify/mvnw.cmd didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-notify/pom.xml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-notify/src/main/java/com/java/example/tanzu/hungryman/HungrymanNotifyApplication.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-notify/src/main/java/com/java/example/tanzu/hungryman/config/EmailMessageConfigProperties.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-notify/src/main/java/com/java/example/tanzu/hungryman/config/PublisherConfiguration.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-notify/src/main/java/com/java/example/tanzu/hungryman/functions/AvailabilitySink.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-notify/src/main/java/com/java/example/tanzu/hungryman/model/Availability.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-notify/src/main/java/com/java/example/tanzu/hungryman/publisher/EmailPublisher.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-notify/src/main/java/com/java/example/tanzu/hungryman/publisher/LoggerPublisher.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-notify/src/main/java/com/java/example/tanzu/hungryman/publisher/Publisher.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-notify/src/main/resources/application.yml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-notify/src/test/java/com/java/example/tanzu/hungryman/HungrymanNotifyApplicationTests.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search/.gitignore didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search/.mvn/wrapper/maven-wrapper.properties didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search/README.md didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search/Tiltfile didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search/catalog-info.yaml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search/config/workload.yaml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search/mvnw didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search/mvnw.cmd didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search/pom.xml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search/src/main/java/com/java/example/tanzu/hungryman/HungrymanResApplication.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search/src/main/java/com/java/example/tanzu/hungryman/config/OAuth2BindingsPropertiesProcessor.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search/src/main/java/com/java/example/tanzu/hungryman/config/WebSecurityConfig.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search/src/main/java/com/java/example/tanzu/hungryman/entity/Search.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search/src/main/java/com/java/example/tanzu/hungryman/functions/SearchSupplier.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search/src/main/java/com/java/example/tanzu/hungryman/repository/SearchRepository.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search/src/main/java/com/java/example/tanzu/hungryman/resources/SearchResource.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search/src/main/resources/META-INF/spring.factories didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search/src/main/resources/application.yml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search/src/main/resources/schema.sql didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search/src/test/java/com/java/example/tanzu/hungryman/HungrymanResApplicationTests.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search/src/test/java/com/java/example/tanzu/hungryman/SpringBaseTest.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search/src/test/java/com/java/example/tanzu/hungryman/repository/SearchRepositoryTest.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search/src/test/resources/application.yml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search-proc/.gitignore didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search-proc/.mvn/wrapper/maven-wrapper.properties didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search-proc/README.md didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search-proc/Tiltfile didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search-proc/config/workload.yaml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search-proc/mvnw didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search-proc/mvnw.cmd didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search-proc/pom.xml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search-proc/src/main/java/com/java/example/tanzu/hungryman/HungrymanSearchProcApplication.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search-proc/src/main/java/com/java/example/tanzu/hungryman/config/StaticDiningAvailability.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search-proc/src/main/java/com/java/example/tanzu/hungryman/feign/CrawlerClient.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search-proc/src/main/java/com/java/example/tanzu/hungryman/functions/Search.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search-proc/src/main/java/com/java/example/tanzu/hungryman/model/Availability.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search-proc/src/main/java/com/java/example/tanzu/hungryman/model/SearchCriteria.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search-proc/src/main/java/com/java/example/tanzu/hungryman/processor/SearchProcessor.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search-proc/src/main/java/com/java/example/tanzu/hungryman/processor/cache/HashCache.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search-proc/src/main/java/com/java/example/tanzu/hungryman/processor/cache/MemoryHashCache.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search-proc/src/main/java/com/java/example/tanzu/hungryman/searcher/Searcher.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search-proc/src/main/java/com/java/example/tanzu/hungryman/searcher/impl/CrawlerSearcher.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search-proc/src/main/java/com/java/example/tanzu/hungryman/searcher/impl/LocalRandomSearcher.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search-proc/src/main/resources/application.yml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search-proc/src/test/java/com/java/example/tanzu/hungryman/HungrymanSearchProcApplicationTests.java didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-ui/.gitignore didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-ui/README.md didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-ui/httpproxy.yaml didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-ui/package-lock.json didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-ui/package.json didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-ui/public/favicon.png didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-ui/public/index.html didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-ui/public/manifest.json didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-ui/public/robots.txt didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-ui/src/App.css didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-ui/src/App.js didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-ui/src/App.test.js didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-ui/src/Availability.js didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-ui/src/DiningNames.js didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-ui/src/DiningSearch.js didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-ui/src/DiningSearches.js didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-ui/src/DiningTypes.js didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-ui/src/SearchDefForm.js didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-ui/src/TimeWindow.js didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-ui/src/images/delete.png didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-ui/src/index.css didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-ui/src/index.js didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-ui/src/logo.svg didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┃ Debug where-to-hike-ui/src/reportWebVitals.js didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┗ Debug where-to-hike-ui/src/setupTests.js didn't match [**/templates/**, **/icons/**, **/.git/**, **/deployment/**] -> included
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[1] (Combo)
┃ ┃ ┃ ┃ ┃  Info Combo running as Chain(Include, chain...)
┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.merge.transformations[0].sources[1].<combo> (Chain)
┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, YTT, RewritePath)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[1].<combo>.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃  Info Will include [**/templates/workloads.yaml]
┃ ┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.properties didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/hungryman-api-gateway/hungryman-api-gateway.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/hungryman-availability/hungryman-availability.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/hungryman-notify/hungryman-notify.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/hungryman-search/hungryman-search.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/hungryman-search-proc/hungryman-search-proc.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/hungryman-ui/hungryman-ui.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/groups/org.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/resources/db/hungryman-db-resource.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/resources/messaging/hungryman-messaging-resource.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/systems/hungryman-system.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug doc/TAPDeployment.md didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug doc/images/AppHomeScreen.png didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug doc/images/HungrymanHighLevelArch.png didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug doc/images/KNativeEventing.png didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug doc/images/SCSMessaging.png didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug icons/hungryman.png didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug mvnw didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug mvnw.cmd didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/appSSOInstance.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/clientRegistrationResourceClaim.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/mysqlInstance.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/mysqlResourceClaim.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/rmqCluster.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/rmqResourceClaim.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/workloads.yaml matched [**/templates/workloads.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-api-gateway/.gitignore didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-api-gateway/Tiltfile didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-api-gateway/config/workload.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-api-gateway/pom.xml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-api-gateway/src/main/java/com/java/example/tanzu/hungryman/HungrymanAPIGatewayApplication.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-api-gateway/src/main/resources/application.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-availability/.gitignore didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-availability/.mvn/wrapper/maven-wrapper.properties didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-availability/Tiltfile didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-availability/config/workload.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-availability/mvnw didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-availability/mvnw.cmd didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-availability/pom.xml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-availability/src/main/java/com/java/example/tanzu/hungryman/HungrymanAvailabilityApplication.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-availability/src/main/java/com/java/example/tanzu/hungryman/config/OAuth2BindingsPropertiesProcessor.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-availability/src/main/java/com/java/example/tanzu/hungryman/config/WebSecurityConfig.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-availability/src/main/java/com/java/example/tanzu/hungryman/entity/Availability.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-availability/src/main/java/com/java/example/tanzu/hungryman/entity/AvailabilityWindow.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-availability/src/main/java/com/java/example/tanzu/hungryman/function/AvailabilitySink.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-availability/src/main/java/com/java/example/tanzu/hungryman/model/Availability.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-availability/src/main/java/com/java/example/tanzu/hungryman/repository/AvailabilityRepository.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-availability/src/main/java/com/java/example/tanzu/hungryman/repository/AvailabilityWindowRepository.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-availability/src/main/java/com/java/example/tanzu/hungryman/resources/AvailabilityResource.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-availability/src/main/resources/META-INF/spring.factories didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-availability/src/main/resources/application.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-availability/src/main/resources/schema.sql didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-availability/src/test/java/com/java/example/tanzu/hungryman/HungrymanAvailabilityApplicationTests.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-crawler/.gitignore didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-crawler/.mvn/wrapper/maven-wrapper.properties didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-crawler/config/workload.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-crawler/mvnw didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-crawler/mvnw.cmd didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-crawler/pom.xml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-crawler/src/main/java/com/java/example/tanzu/hungryman/HungrymanCrawlerApplication.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-crawler/src/main/java/com/java/example/tanzu/hungryman/model/Availability.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-crawler/src/main/java/com/java/example/tanzu/hungryman/model/SearchCriteria.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-crawler/src/main/java/com/java/example/tanzu/hungryman/resources/SearchResource.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-crawler/src/main/resources/application.properties didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-crawler/src/test/java/com/java/example/tanzu/hungryman/HungrymanCrawlerApplicationTests.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-notify/.gitignore didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-notify/.mvn/wrapper/maven-wrapper.properties didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-notify/README.md didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-notify/Tiltfile didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-notify/config/workload.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-notify/mvnw didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-notify/mvnw.cmd didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-notify/pom.xml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-notify/src/main/java/com/java/example/tanzu/hungryman/HungrymanNotifyApplication.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-notify/src/main/java/com/java/example/tanzu/hungryman/config/EmailMessageConfigProperties.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-notify/src/main/java/com/java/example/tanzu/hungryman/config/PublisherConfiguration.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-notify/src/main/java/com/java/example/tanzu/hungryman/functions/AvailabilitySink.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-notify/src/main/java/com/java/example/tanzu/hungryman/model/Availability.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-notify/src/main/java/com/java/example/tanzu/hungryman/publisher/EmailPublisher.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-notify/src/main/java/com/java/example/tanzu/hungryman/publisher/LoggerPublisher.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-notify/src/main/java/com/java/example/tanzu/hungryman/publisher/Publisher.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-notify/src/main/resources/application.yml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-notify/src/test/java/com/java/example/tanzu/hungryman/HungrymanNotifyApplicationTests.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search/.gitignore didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search/.mvn/wrapper/maven-wrapper.properties didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search/README.md didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search/Tiltfile didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search/catalog-info.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search/config/workload.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search/mvnw didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search/mvnw.cmd didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search/pom.xml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search/src/main/java/com/java/example/tanzu/hungryman/HungrymanResApplication.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search/src/main/java/com/java/example/tanzu/hungryman/config/OAuth2BindingsPropertiesProcessor.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search/src/main/java/com/java/example/tanzu/hungryman/config/WebSecurityConfig.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search/src/main/java/com/java/example/tanzu/hungryman/entity/Search.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search/src/main/java/com/java/example/tanzu/hungryman/functions/SearchSupplier.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search/src/main/java/com/java/example/tanzu/hungryman/repository/SearchRepository.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search/src/main/java/com/java/example/tanzu/hungryman/resources/SearchResource.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search/src/main/resources/META-INF/spring.factories didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search/src/main/resources/application.yml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search/src/main/resources/schema.sql didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search/src/test/java/com/java/example/tanzu/hungryman/HungrymanResApplicationTests.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search/src/test/java/com/java/example/tanzu/hungryman/SpringBaseTest.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search/src/test/java/com/java/example/tanzu/hungryman/repository/SearchRepositoryTest.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search/src/test/resources/application.yml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search-proc/.gitignore didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search-proc/.mvn/wrapper/maven-wrapper.properties didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search-proc/README.md didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search-proc/Tiltfile didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search-proc/config/workload.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search-proc/mvnw didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search-proc/mvnw.cmd didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search-proc/pom.xml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search-proc/src/main/java/com/java/example/tanzu/hungryman/HungrymanSearchProcApplication.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search-proc/src/main/java/com/java/example/tanzu/hungryman/config/StaticDiningAvailability.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search-proc/src/main/java/com/java/example/tanzu/hungryman/feign/CrawlerClient.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search-proc/src/main/java/com/java/example/tanzu/hungryman/functions/Search.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search-proc/src/main/java/com/java/example/tanzu/hungryman/model/Availability.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search-proc/src/main/java/com/java/example/tanzu/hungryman/model/SearchCriteria.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search-proc/src/main/java/com/java/example/tanzu/hungryman/processor/SearchProcessor.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search-proc/src/main/java/com/java/example/tanzu/hungryman/processor/cache/HashCache.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search-proc/src/main/java/com/java/example/tanzu/hungryman/processor/cache/MemoryHashCache.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search-proc/src/main/java/com/java/example/tanzu/hungryman/searcher/Searcher.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search-proc/src/main/java/com/java/example/tanzu/hungryman/searcher/impl/CrawlerSearcher.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search-proc/src/main/java/com/java/example/tanzu/hungryman/searcher/impl/LocalRandomSearcher.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search-proc/src/main/resources/application.yml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search-proc/src/test/java/com/java/example/tanzu/hungryman/HungrymanSearchProcApplicationTests.java didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-ui/.gitignore didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-ui/README.md didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-ui/httpproxy.yaml didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-ui/package-lock.json didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-ui/package.json didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-ui/public/favicon.png didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-ui/public/index.html didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-ui/public/manifest.json didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-ui/public/robots.txt didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-ui/src/App.css didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-ui/src/App.js didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-ui/src/App.test.js didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-ui/src/Availability.js didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-ui/src/DiningNames.js didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-ui/src/DiningSearch.js didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-ui/src/DiningSearches.js didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-ui/src/DiningTypes.js didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-ui/src/SearchDefForm.js didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-ui/src/TimeWindow.js didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-ui/src/images/delete.png didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-ui/src/index.css didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-ui/src/index.js didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-ui/src/logo.svg didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-ui/src/reportWebVitals.js didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┗ Debug where-to-hike-ui/src/setupTests.js didn't match [**/templates/workloads.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[1].<combo>.transformations[1] (YTT)
┃ ┃ ┃ ┃ ┃ ┃ Debug Wrote values file with json content:   {"devDefaultAccountUsername":"where-to-hike","artifactVersion":"0.0.1-beta","dbName":"db-where-to-hike","dbType":"h2","rabbitMQName":"rmq-where-to-hike","devDefaultAccountPassword":"letseat","appSSOIssuerURI":"http://authserver.<domainname>","enableSecurity":false,"createRabbitMQCluster":true,"appSSOName":"appsso-where-to-hike","createResourceClaim":true,"numRabbitMQClusterNodes":1,"enableDefaultDevAccount":true,"artifactId":"where-to-hike","createDBInstance":true,"serviceNamespace":"apenner","projectName":"where-to-hike","workloadNamespace":"apenner","appSSORedirectURI":"http://where-to-hike.<domain name>/login/oauth2/code/sso"}
┃ ┃ ┃ ┃ ┃ ┗  Info Shelling out to YTT with args: [ytt, -f, /tmp/ytt-input14224751306193891201, --data-values-file, /tmp/accelerator-options14121246875412548079.json, --output-files, /tmp/ytt-output13814497061811413609]
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[1].<combo>.transformations[2] (RewritePath)
┃ ┃ ┃ ┃ ┗ ┗ Debug Path 'templates/workloads.yaml' matched 'templates/workloads.yaml' with groups {g0=templates/workloads.yaml} and was rewritten to 'config/developer/workloads.yaml'
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[2] (Combo)
┃ ┃ ┃ ┃ ┃  Info Condition (#createRabbitMQCluster) evaluated to true
┃ ┃ ┃ ┃ ┃  Info Combo running as Chain(Include, chain...)
┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.merge.transformations[0].sources[2].<combo> (Chain)
┃ ┃ ┃ ┃ ┃  Info Condition (#createRabbitMQCluster) evaluated to true
┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, YTT, RewritePath)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[2].<combo>.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃  Info Will include [**/rmqCluster.yaml]
┃ ┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.properties didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/hungryman-api-gateway/hungryman-api-gateway.yaml didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/hungryman-availability/hungryman-availability.yaml didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/hungryman-notify/hungryman-notify.yaml didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/hungryman-search/hungryman-search.yaml didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/hungryman-search-proc/hungryman-search-proc.yaml didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/hungryman-ui/hungryman-ui.yaml didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/groups/org.yaml didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/resources/db/hungryman-db-resource.yaml didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/resources/messaging/hungryman-messaging-resource.yaml didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/systems/hungryman-system.yaml didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug doc/TAPDeployment.md didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug doc/images/AppHomeScreen.png didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug doc/images/HungrymanHighLevelArch.png didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug doc/images/KNativeEventing.png didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug doc/images/SCSMessaging.png didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug icons/hungryman.png didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug mvnw didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug mvnw.cmd didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/appSSOInstance.yaml didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/clientRegistrationResourceClaim.yaml didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/mysqlInstance.yaml didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/mysqlResourceClaim.yaml didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/rmqCluster.yaml matched [**/rmqCluster.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/rmqResourceClaim.yaml didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/workloads.yaml didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-api-gateway/.gitignore didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-api-gateway/Tiltfile didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-api-gateway/config/workload.yaml didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-api-gateway/pom.xml didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-api-gateway/src/main/java/com/java/example/tanzu/hungryman/HungrymanAPIGatewayApplication.java didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-api-gateway/src/main/resources/application.yaml didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-availability/.gitignore didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-availability/.mvn/wrapper/maven-wrapper.properties didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-availability/Tiltfile didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-availability/config/workload.yaml didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-availability/mvnw didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-availability/mvnw.cmd didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-availability/pom.xml didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-availability/src/main/java/com/java/example/tanzu/hungryman/HungrymanAvailabilityApplication.java didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-availability/src/main/java/com/java/example/tanzu/hungryman/config/OAuth2BindingsPropertiesProcessor.java didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-availability/src/main/java/com/java/example/tanzu/hungryman/config/WebSecurityConfig.java didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-availability/src/main/java/com/java/example/tanzu/hungryman/entity/Availability.java didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-availability/src/main/java/com/java/example/tanzu/hungryman/entity/AvailabilityWindow.java didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-availability/src/main/java/com/java/example/tanzu/hungryman/function/AvailabilitySink.java didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-availability/src/main/java/com/java/example/tanzu/hungryman/model/Availability.java didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-availability/src/main/java/com/java/example/tanzu/hungryman/repository/AvailabilityRepository.java didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-availability/src/main/java/com/java/example/tanzu/hungryman/repository/AvailabilityWindowRepository.java didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-availability/src/main/java/com/java/example/tanzu/hungryman/resources/AvailabilityResource.java didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-availability/src/main/resources/META-INF/spring.factories didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-availability/src/main/resources/application.yaml didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-availability/src/main/resources/schema.sql didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-availability/src/test/java/com/java/example/tanzu/hungryman/HungrymanAvailabilityApplicationTests.java didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-crawler/.gitignore didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-crawler/.mvn/wrapper/maven-wrapper.properties didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-crawler/config/workload.yaml didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-crawler/mvnw didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-crawler/mvnw.cmd didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-crawler/pom.xml didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-crawler/src/main/java/com/java/example/tanzu/hungryman/HungrymanCrawlerApplication.java didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-crawler/src/main/java/com/java/example/tanzu/hungryman/model/Availability.java didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-crawler/src/main/java/com/java/example/tanzu/hungryman/model/SearchCriteria.java didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-crawler/src/main/java/com/java/example/tanzu/hungryman/resources/SearchResource.java didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-crawler/src/main/resources/application.properties didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-crawler/src/test/java/com/java/example/tanzu/hungryman/HungrymanCrawlerApplicationTests.java didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-notify/.gitignore didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-notify/.mvn/wrapper/maven-wrapper.properties didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-notify/README.md didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-notify/Tiltfile didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-notify/config/workload.yaml didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-notify/mvnw didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-notify/mvnw.cmd didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-notify/pom.xml didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-notify/src/main/java/com/java/example/tanzu/hungryman/HungrymanNotifyApplication.java didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-notify/src/main/java/com/java/example/tanzu/hungryman/config/EmailMessageConfigProperties.java didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-notify/src/main/java/com/java/example/tanzu/hungryman/config/PublisherConfiguration.java didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-notify/src/main/java/com/java/example/tanzu/hungryman/functions/AvailabilitySink.java didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-notify/src/main/java/com/java/example/tanzu/hungryman/model/Availability.java didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-notify/src/main/java/com/java/example/tanzu/hungryman/publisher/EmailPublisher.java didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-notify/src/main/java/com/java/example/tanzu/hungryman/publisher/LoggerPublisher.java didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-notify/src/main/java/com/java/example/tanzu/hungryman/publisher/Publisher.java didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-notify/src/main/resources/application.yml didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-notify/src/test/java/com/java/example/tanzu/hungryman/HungrymanNotifyApplicationTests.java didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search/.gitignore didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search/.mvn/wrapper/maven-wrapper.properties didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search/README.md didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search/Tiltfile didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search/catalog-info.yaml didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search/config/workload.yaml didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search/mvnw didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search/mvnw.cmd didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search/pom.xml didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search/src/main/java/com/java/example/tanzu/hungryman/HungrymanResApplication.java didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search/src/main/java/com/java/example/tanzu/hungryman/config/OAuth2BindingsPropertiesProcessor.java didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search/src/main/java/com/java/example/tanzu/hungryman/config/WebSecurityConfig.java didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search/src/main/java/com/java/example/tanzu/hungryman/entity/Search.java didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search/src/main/java/com/java/example/tanzu/hungryman/functions/SearchSupplier.java didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search/src/main/java/com/java/example/tanzu/hungryman/repository/SearchRepository.java didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search/src/main/java/com/java/example/tanzu/hungryman/resources/SearchResource.java didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search/src/main/resources/META-INF/spring.factories didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search/src/main/resources/application.yml didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search/src/main/resources/schema.sql didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search/src/test/java/com/java/example/tanzu/hungryman/HungrymanResApplicationTests.java didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search/src/test/java/com/java/example/tanzu/hungryman/SpringBaseTest.java didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search/src/test/java/com/java/example/tanzu/hungryman/repository/SearchRepositoryTest.java didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search/src/test/resources/application.yml didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search-proc/.gitignore didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search-proc/.mvn/wrapper/maven-wrapper.properties didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search-proc/README.md didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search-proc/Tiltfile didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search-proc/config/workload.yaml didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search-proc/mvnw didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search-proc/mvnw.cmd didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search-proc/pom.xml didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search-proc/src/main/java/com/java/example/tanzu/hungryman/HungrymanSearchProcApplication.java didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search-proc/src/main/java/com/java/example/tanzu/hungryman/config/StaticDiningAvailability.java didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search-proc/src/main/java/com/java/example/tanzu/hungryman/feign/CrawlerClient.java didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search-proc/src/main/java/com/java/example/tanzu/hungryman/functions/Search.java didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search-proc/src/main/java/com/java/example/tanzu/hungryman/model/Availability.java didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search-proc/src/main/java/com/java/example/tanzu/hungryman/model/SearchCriteria.java didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search-proc/src/main/java/com/java/example/tanzu/hungryman/processor/SearchProcessor.java didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search-proc/src/main/java/com/java/example/tanzu/hungryman/processor/cache/HashCache.java didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search-proc/src/main/java/com/java/example/tanzu/hungryman/processor/cache/MemoryHashCache.java didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search-proc/src/main/java/com/java/example/tanzu/hungryman/searcher/Searcher.java didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search-proc/src/main/java/com/java/example/tanzu/hungryman/searcher/impl/CrawlerSearcher.java didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search-proc/src/main/java/com/java/example/tanzu/hungryman/searcher/impl/LocalRandomSearcher.java didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search-proc/src/main/resources/application.yml didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search-proc/src/test/java/com/java/example/tanzu/hungryman/HungrymanSearchProcApplicationTests.java didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-ui/.gitignore didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-ui/README.md didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-ui/httpproxy.yaml didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-ui/package-lock.json didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-ui/package.json didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-ui/public/favicon.png didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-ui/public/index.html didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-ui/public/manifest.json didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-ui/public/robots.txt didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-ui/src/App.css didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-ui/src/App.js didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-ui/src/App.test.js didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-ui/src/Availability.js didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-ui/src/DiningNames.js didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-ui/src/DiningSearch.js didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-ui/src/DiningSearches.js didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-ui/src/DiningTypes.js didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-ui/src/SearchDefForm.js didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-ui/src/TimeWindow.js didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-ui/src/images/delete.png didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-ui/src/index.css didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-ui/src/index.js didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-ui/src/logo.svg didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-ui/src/reportWebVitals.js didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┗ Debug where-to-hike-ui/src/setupTests.js didn't match [**/rmqCluster.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[2].<combo>.transformations[1] (YTT)
┃ ┃ ┃ ┃ ┃ ┃ Debug Wrote values file with json content:   {"devDefaultAccountUsername":"where-to-hike","artifactVersion":"0.0.1-beta","dbName":"db-where-to-hike","dbType":"h2","rabbitMQName":"rmq-where-to-hike","devDefaultAccountPassword":"letseat","appSSOIssuerURI":"http://authserver.<domainname>","enableSecurity":false,"createRabbitMQCluster":true,"appSSOName":"appsso-where-to-hike","createResourceClaim":true,"numRabbitMQClusterNodes":1,"enableDefaultDevAccount":true,"artifactId":"where-to-hike","createDBInstance":true,"serviceNamespace":"apenner","projectName":"where-to-hike","workloadNamespace":"apenner","appSSORedirectURI":"http://where-to-hike.<domain name>/login/oauth2/code/sso"}
┃ ┃ ┃ ┃ ┃ ┗  Info Shelling out to YTT with args: [ytt, -f, /tmp/ytt-input1898728247384052719, --data-values-file, /tmp/accelerator-options6853759959844322396.json, --output-files, /tmp/ytt-output4455874831696164408]
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[2].<combo>.transformations[2] (RewritePath)
┃ ┃ ┃ ┃ ┗ ┗ Debug Path 'templates/rmqCluster.yaml' matched 'templates/rmqCluster.yaml' with groups {g0=templates/rmqCluster.yaml} and was rewritten to 'config/service-operator/rmqCluster.yaml'
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[3] (Combo)
┃ ┃ ┃ ┃ ┃  Info Condition (#createDBInstance && #dbType == 'mysql') evaluated to false
┃ ┃ ┃ ┃ ┗ null ()
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[4] (Combo)
┃ ┃ ┃ ┃ ┃  Info Condition (#createResourceClaim) evaluated to true
┃ ┃ ┃ ┃ ┃  Info Combo running as Chain(Include, chain...)
┃ ┃ ┃ ┃ ┃ engine.transformations[0].validated.merge.transformations[0].sources[4].<combo> (Chain)
┃ ┃ ┃ ┃ ┃  Info Condition (#createResourceClaim) evaluated to true
┃ ┃ ┃ ┃ ┃  Info Running Chain(Include, YTT, RewritePath)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[4].<combo>.transformations[0] (Include)
┃ ┃ ┃ ┃ ┃ ┃  Info Will include [**/rmqResourceClaim.yaml]
┃ ┃ ┃ ┃ ┃ ┃ Debug .mvn/wrapper/maven-wrapper.properties didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/catalog-info.yaml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/hungryman-api-gateway/hungryman-api-gateway.yaml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/hungryman-availability/hungryman-availability.yaml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/hungryman-notify/hungryman-notify.yaml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/hungryman-search/hungryman-search.yaml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/hungryman-search-proc/hungryman-search-proc.yaml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/components/hungryman-ui/hungryman-ui.yaml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/groups/org.yaml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/resources/db/hungryman-db-resource.yaml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/resources/messaging/hungryman-messaging-resource.yaml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug catalog/systems/hungryman-system.yaml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug doc/TAPDeployment.md didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug doc/images/AppHomeScreen.png didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug doc/images/HungrymanHighLevelArch.png didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug doc/images/KNativeEventing.png didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug doc/images/SCSMessaging.png didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug icons/hungryman.png didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug mvnw didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug mvnw.cmd didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug pom.xml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/appSSOInstance.yaml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/clientRegistrationResourceClaim.yaml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/mysqlInstance.yaml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/mysqlResourceClaim.yaml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/rmqCluster.yaml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/rmqResourceClaim.yaml matched [**/rmqResourceClaim.yaml] -> included
┃ ┃ ┃ ┃ ┃ ┃ Debug templates/workloads.yaml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-api-gateway/.gitignore didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-api-gateway/Tiltfile didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-api-gateway/config/workload.yaml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-api-gateway/pom.xml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-api-gateway/src/main/java/com/java/example/tanzu/hungryman/HungrymanAPIGatewayApplication.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-api-gateway/src/main/resources/application.yaml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-availability/.gitignore didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-availability/.mvn/wrapper/maven-wrapper.properties didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-availability/Tiltfile didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-availability/config/workload.yaml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-availability/mvnw didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-availability/mvnw.cmd didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-availability/pom.xml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-availability/src/main/java/com/java/example/tanzu/hungryman/HungrymanAvailabilityApplication.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-availability/src/main/java/com/java/example/tanzu/hungryman/config/OAuth2BindingsPropertiesProcessor.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-availability/src/main/java/com/java/example/tanzu/hungryman/config/WebSecurityConfig.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-availability/src/main/java/com/java/example/tanzu/hungryman/entity/Availability.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-availability/src/main/java/com/java/example/tanzu/hungryman/entity/AvailabilityWindow.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-availability/src/main/java/com/java/example/tanzu/hungryman/function/AvailabilitySink.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-availability/src/main/java/com/java/example/tanzu/hungryman/model/Availability.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-availability/src/main/java/com/java/example/tanzu/hungryman/repository/AvailabilityRepository.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-availability/src/main/java/com/java/example/tanzu/hungryman/repository/AvailabilityWindowRepository.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-availability/src/main/java/com/java/example/tanzu/hungryman/resources/AvailabilityResource.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-availability/src/main/resources/META-INF/spring.factories didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-availability/src/main/resources/application.yaml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-availability/src/main/resources/schema.sql didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-availability/src/test/java/com/java/example/tanzu/hungryman/HungrymanAvailabilityApplicationTests.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-crawler/.gitignore didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-crawler/.mvn/wrapper/maven-wrapper.properties didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-crawler/config/workload.yaml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-crawler/mvnw didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-crawler/mvnw.cmd didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-crawler/pom.xml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-crawler/src/main/java/com/java/example/tanzu/hungryman/HungrymanCrawlerApplication.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-crawler/src/main/java/com/java/example/tanzu/hungryman/model/Availability.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-crawler/src/main/java/com/java/example/tanzu/hungryman/model/SearchCriteria.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-crawler/src/main/java/com/java/example/tanzu/hungryman/resources/SearchResource.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-crawler/src/main/resources/application.properties didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-crawler/src/test/java/com/java/example/tanzu/hungryman/HungrymanCrawlerApplicationTests.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-notify/.gitignore didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-notify/.mvn/wrapper/maven-wrapper.properties didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-notify/README.md didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-notify/Tiltfile didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-notify/config/workload.yaml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-notify/mvnw didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-notify/mvnw.cmd didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-notify/pom.xml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-notify/src/main/java/com/java/example/tanzu/hungryman/HungrymanNotifyApplication.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-notify/src/main/java/com/java/example/tanzu/hungryman/config/EmailMessageConfigProperties.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-notify/src/main/java/com/java/example/tanzu/hungryman/config/PublisherConfiguration.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-notify/src/main/java/com/java/example/tanzu/hungryman/functions/AvailabilitySink.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-notify/src/main/java/com/java/example/tanzu/hungryman/model/Availability.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-notify/src/main/java/com/java/example/tanzu/hungryman/publisher/EmailPublisher.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-notify/src/main/java/com/java/example/tanzu/hungryman/publisher/LoggerPublisher.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-notify/src/main/java/com/java/example/tanzu/hungryman/publisher/Publisher.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-notify/src/main/resources/application.yml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-notify/src/test/java/com/java/example/tanzu/hungryman/HungrymanNotifyApplicationTests.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search/.gitignore didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search/.mvn/wrapper/maven-wrapper.properties didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search/README.md didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search/Tiltfile didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search/catalog-info.yaml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search/config/workload.yaml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search/mvnw didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search/mvnw.cmd didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search/pom.xml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search/src/main/java/com/java/example/tanzu/hungryman/HungrymanResApplication.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search/src/main/java/com/java/example/tanzu/hungryman/config/OAuth2BindingsPropertiesProcessor.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search/src/main/java/com/java/example/tanzu/hungryman/config/WebSecurityConfig.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search/src/main/java/com/java/example/tanzu/hungryman/entity/Search.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search/src/main/java/com/java/example/tanzu/hungryman/functions/SearchSupplier.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search/src/main/java/com/java/example/tanzu/hungryman/repository/SearchRepository.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search/src/main/java/com/java/example/tanzu/hungryman/resources/SearchResource.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search/src/main/resources/META-INF/spring.factories didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search/src/main/resources/application.yml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search/src/main/resources/schema.sql didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search/src/test/java/com/java/example/tanzu/hungryman/HungrymanResApplicationTests.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search/src/test/java/com/java/example/tanzu/hungryman/SpringBaseTest.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search/src/test/java/com/java/example/tanzu/hungryman/repository/SearchRepositoryTest.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search/src/test/resources/application.yml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search-proc/.gitignore didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search-proc/.mvn/wrapper/maven-wrapper.properties didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search-proc/README.md didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search-proc/Tiltfile didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search-proc/config/workload.yaml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search-proc/mvnw didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search-proc/mvnw.cmd didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search-proc/pom.xml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search-proc/src/main/java/com/java/example/tanzu/hungryman/HungrymanSearchProcApplication.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search-proc/src/main/java/com/java/example/tanzu/hungryman/config/StaticDiningAvailability.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search-proc/src/main/java/com/java/example/tanzu/hungryman/feign/CrawlerClient.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search-proc/src/main/java/com/java/example/tanzu/hungryman/functions/Search.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search-proc/src/main/java/com/java/example/tanzu/hungryman/model/Availability.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search-proc/src/main/java/com/java/example/tanzu/hungryman/model/SearchCriteria.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search-proc/src/main/java/com/java/example/tanzu/hungryman/processor/SearchProcessor.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search-proc/src/main/java/com/java/example/tanzu/hungryman/processor/cache/HashCache.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search-proc/src/main/java/com/java/example/tanzu/hungryman/processor/cache/MemoryHashCache.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search-proc/src/main/java/com/java/example/tanzu/hungryman/searcher/Searcher.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search-proc/src/main/java/com/java/example/tanzu/hungryman/searcher/impl/CrawlerSearcher.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search-proc/src/main/java/com/java/example/tanzu/hungryman/searcher/impl/LocalRandomSearcher.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search-proc/src/main/resources/application.yml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-search-proc/src/test/java/com/java/example/tanzu/hungryman/HungrymanSearchProcApplicationTests.java didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-ui/.gitignore didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-ui/README.md didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-ui/httpproxy.yaml didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-ui/package-lock.json didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-ui/package.json didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-ui/public/favicon.png didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-ui/public/index.html didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-ui/public/manifest.json didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-ui/public/robots.txt didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-ui/src/App.css didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-ui/src/App.js didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-ui/src/App.test.js didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-ui/src/Availability.js didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-ui/src/DiningNames.js didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-ui/src/DiningSearch.js didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-ui/src/DiningSearches.js didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-ui/src/DiningTypes.js didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-ui/src/SearchDefForm.js didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-ui/src/TimeWindow.js didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-ui/src/images/delete.png didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-ui/src/index.css didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-ui/src/index.js didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-ui/src/logo.svg didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ Debug where-to-hike-ui/src/reportWebVitals.js didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┗ Debug where-to-hike-ui/src/setupTests.js didn't match [**/rmqResourceClaim.yaml] -> excluded
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[4].<combo>.transformations[1] (YTT)
┃ ┃ ┃ ┃ ┃ ┃ Debug Wrote values file with json content:   {"devDefaultAccountUsername":"where-to-hike","artifactVersion":"0.0.1-beta","dbName":"db-where-to-hike","dbType":"h2","rabbitMQName":"rmq-where-to-hike","devDefaultAccountPassword":"letseat","appSSOIssuerURI":"http://authserver.<domainname>","enableSecurity":false,"createRabbitMQCluster":true,"appSSOName":"appsso-where-to-hike","createResourceClaim":true,"numRabbitMQClusterNodes":1,"enableDefaultDevAccount":true,"artifactId":"where-to-hike","createDBInstance":true,"serviceNamespace":"apenner","projectName":"where-to-hike","workloadNamespace":"apenner","appSSORedirectURI":"http://where-to-hike.<domain name>/login/oauth2/code/sso"}
┃ ┃ ┃ ┃ ┃ ┗  Info Shelling out to YTT with args: [ytt, -f, /tmp/ytt-input8272012039326710168, --data-values-file, /tmp/accelerator-options15144682435275545025.json, --output-files, /tmp/ytt-output16416905817854906608]
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[4].<combo>.transformations[2] (RewritePath)
┃ ┃ ┃ ┃ ┗ ┗ Debug Path 'templates/rmqResourceClaim.yaml' matched 'templates/rmqResourceClaim.yaml' with groups {g0=templates/rmqResourceClaim.yaml} and was rewritten to 'config/app-operator/rmqResourceClaim.yaml'
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[5] (Combo)
┃ ┃ ┃ ┃ ┃  Info Condition (#createResourceClaim && #dbType == 'mysql') evaluated to false
┃ ┃ ┃ ┃ ┗ null ()
┃ ┃ ┃ ┃ ┏ engine.transformations[0].validated.merge.transformations[0].sources[6] (Combo)
┃ ┃ ┃ ┃ ┃  Info Condition (#enableSecurity) evaluated to false
┃ ┃ ┃ ┗ ┗ null ()
┃ ┗ ┗ ╺ engine.transformations[0].validated.merge.transformations[1] (UniquePath)
┗ ╺ engine.transformations[1] (UniquePath)
```
