# AEM PROD Publish Error Report — 2026-04-30
Report date: 2026-04-30
Generated from aemerror.log — general error validation.
## Summary
- **ERROR**: 1354
- **WARN**: 93894
## By Class
| Class | ERROR | WARN |
|-------|-------|------|
| org.apache.jackrabbit.vault.fs.io.ImportOptions | 0 | 39626 |
| com.adobe.cq.updateprocessor.impl.ProcessorUtils | 0 | 28598 |
| GET | 1324 | 16767 |
| com.adobe.granite.workflow.core.WorkflowSessionImpl | 0 | 5626 |
| com.adobe.cq.dam.cfm.graphql.ModelManagerImpl | 0 | 2653 |
| org.apache.felix.webconsole | 0 | 223 |
| org.apache.felix.hc.core.impl.executor.HealthCheckExecutorImpl | 0 | 102 |
| org.apache.felix.configadmin.plugin.interpolation.InterpolationConfigurationPlugin | 0 | 63 |
| com.adobe.granite.ims.yamlloader.ImsYamlLoader | 0 | 28 |
| com.adobe.cq.dam.assethandler.internal.events.consumer.impl.AssetBatchDeliveryConsumerImpl | 0 | 21 |
| com.adobe.granite.repository.impl.SystemPrincipalsValidation | 0 | 21 |
| com.adobe.granite.probes.impl.K8SProbes | 0 | 14 |
| com.day.cq.commons.impl.PredicateProviderImpl | 0 | 14 |
| org.apache.sling.resourceresolver.impl.VanityPathConfigurer | 0 | 14 |
| com.day.cq.dam.handler.gibson.fontmanager.impl.FontManagerServiceImpl | 0 | 14 |
| com.adobe.cq.wcm.translation.impl.utils.I18nUtils | 0 | 14 |
| com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | 12 | 0 |
| com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | 12 | 0 |
| io.prometheus.client.dropwizard.DropwizardExports | 0 | 12 |
| com.adobe.granite.maintenance.impl.MaintenanceTaskInfoImpl | 0 | 12 |
| com.azure.core.http.netty.implementation.Utility | 0 | 7 |
| org.apache.jackrabbit.oak.plugins.index.elastic.query.inference.InferenceIndexConfig | 0 | 7 |
| com.adobe.granite.ims.client.config.ExpiryChecker | 0 | 7 |
| com.adobe.granite.workflow.console.generate.WorkflowModelGeneratorImpl | 0 | 7 |
| org.apache.jackrabbit.oak.jcr.lock.LockDeprecation | 0 | 7 |
| com.day.cq.commons.servlets.AbstractListServlet | 0 | 7 |
| com.day.crx.sling.server.impl.jmx.SecureContentRepositoryAccess | 0 | 6 |
| org.apache.jackrabbit.oak.plugins.index.lucene.IndexCopier | 0 | 4 |
| org.apache.sling.commons.scheduler.impl.QuartzScheduler | 3 | 0 |
| Events.Framework.org.apache.felix.log | 2 | 0 |
| org.apache.jackrabbit.oak.plugins.index.AsyncCheckpointCreator | 0 | 2 |
| [3a32f6fb-32dd-4f7e-a488-4ee579bf4a0e] | 0 | 2 |
| com.adobe.granite.maintenance.impl.TaskScheduler | 1 | 0 |
| [86692901-34cb-4166-b31c-819e4319613d] | 0 | 1 |
| [f90083dc-8d5e-433a-95a1-7b06f1b73f76] | 0 | 1 |
| [ec0ae5e4-e1f0-4d9e-a70c-9269cf1c6f56] | 0 | 1 |
| [3c073d28-65a4-4027-b167-1fc27a1d93af] | 0 | 1 |
| [0f6edb8a-2d9e-45ae-a9c2-d9aef954b030] | 0 | 1 |
| org.apache.jackrabbit.oak.plugins.index.lucene.directory.CopyOnReadDirectory | 0 | 1 |
| [015be82d-b217-4b89-a20d-80ad3b8deed3] | 0 | 1 |
| [8655208f-2bcb-4515-9ec4-bfce8d904968] | 0 | 1 |
| [b6477acf-55d1-4f4e-84d9-30664590ebd3] | 0 | 1 |
| [d6524d01-b58d-401f-8f57-d94e17c278d1] | 0 | 1 |
| [d4756bca-f306-46bc-934d-3a3d354c4fb3] | 0 | 1 |
| [b4c7bfaf-3fd0-4987-8c03-d2e10224d3c1] | 0 | 1 |
| [334bf0b6-1ffc-4891-b790-18390bfbc569] | 0 | 1 |
| [1efa69b2-5edc-4b52-bffb-564fa4ac9e74] | 0 | 1 |
| [6bc2a63c-e8cc-47d4-aca6-a5b04e162367] | 0 | 1 |
| [2a84df79-05e9-4051-b9f3-d6b201a90579] | 0 | 1 |

## Recent Errors (sample)
| Date | Time | Class | Message |
|------|------|-------|--------|
| 01.05.2026 | 00:00:00.080 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 01.05.2026 | 00:00:00.080 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [657] |
| 01.05.2026 | 00:00:00.081 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 01.05.2026 | 00:00:00.081 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [657] |
| 01.05.2026 | 00:00:00.090 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [657] |
| 01.05.2026 | 00:00:00.091 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 01.05.2026 | 00:00:00.106 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [657] |
| 01.05.2026 | 00:00:00.106 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 01.05.2026 | 00:00:00.149 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [657] |
| 01.05.2026 | 00:00:00.149 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 01.05.2026 | 00:00:00.161 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 01.05.2026 | 00:00:00.161 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [657] |
| 01.05.2026 | 00:00:27.930 | GET | /content/dam/portals/realmadrid-com/es-es/core-content/assemblies/pages/generic-pages/madridistas/ve |
| 01.05.2026 | 00:00:28.517 | GET | /content/dam/portals/realmadrid-com/es-es/core-content/assemblies/pages/generic-pages/madridistas/ve |
| 01.05.2026 | 00:00:28.675 | GET | /content/dam/portals/realmadrid-com/es-es/core-content/assemblies/pages/generic-pages/madridistas/ve |
| 01.05.2026 | 00:01:44.185 | GET | /graphql/execute.json/madridistas/madridistasLandingPlatinumByPath%3bpath=/content/dam/portals/madri |
| 01.05.2026 | 00:02:02.914 | GET | /graphql/execute.json/realmadridmastersite/diaryV2;fromDate=2026-05-01T00:00:00.000Z;toDate=2026-07- |
| 01.05.2026 | 00:02:25.920 | GET | /content/dam/portals/realmadrid-com/en-us/news/generic/2026/03/28/videos/240326%20S7%20WEB%20CALENDA |
| 01.05.2026 | 00:03:13.657 | GET | /graphql/execute.json/madridistas/madridistasLandingPlatinumByPath%3bpath=/content/dam/portals/madri |
| 01.05.2026 | 00:03:16.975 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 01.05.2026 | 00:03:17.108 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 01.05.2026 | 00:03:17.151 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 01.05.2026 | 00:03:19.966 | GET | /graphql/execute.json/realmadridmastersite/news-section-detail-assembly%3bpath=%252Fcontent%252Fdam% |
| 01.05.2026 | 00:03:30.508 | GET | /graphql/execute.json/madridistas/madridistasLandingPlatinumByPath%3bpath=/content/dam/portals/madri |
| 01.05.2026 | 00:04:03.279 | GET | /content/dam/portals/realmadrid-com/es-es/core-content/assemblies/pages/generic-pages/madridistas/ve |
| 01.05.2026 | 00:04:03.316 | GET | /content/dam/portals/realmadrid-com/es-es/core-content/assemblies/pages/generic-pages/madridistas/ve |
| 01.05.2026 | 00:04:03.317 | GET | /content/dam/portals/realmadrid-com/es-es/core-content/assemblies/pages/generic-pages/madridistas/ve |
| 01.05.2026 | 00:04:03.339 | GET | /content/dam/portals/realmadrid-com/es-es/core-content/assemblies/pages/generic-pages/madridistas/ve |
| 01.05.2026 | 00:04:03.342 | GET | /content/dam/portals/realmadrid-com/es-es/core-content/assemblies/pages/generic-pages/madridistas/ve |
| 01.05.2026 | 00:04:03.361 | GET | /content/dam/portals/realmadrid-com/es-es/core-content/assemblies/pages/generic-pages/madridistas/ve |
| 01.05.2026 | 00:04:03.373 | GET | /content/dam/portals/realmadrid-com/es-es/core-content/assemblies/pages/generic-pages/madridistas/ve |
| 01.05.2026 | 00:04:03.403 | GET | /content/dam/portals/realmadrid-com/es-es/core-content/assemblies/pages/generic-pages/madridistas/ve |
| 01.05.2026 | 00:04:03.407 | GET | /content/dam/portals/realmadrid-com/es-es/core-content/assemblies/pages/generic-pages/madridistas/ve |
| 01.05.2026 | 00:04:03.434 | GET | /content/dam/portals/realmadrid-com/es-es/core-content/assemblies/pages/generic-pages/madridistas/ve |
| 01.05.2026 | 00:04:03.459 | GET | /content/dam/portals/realmadrid-com/es-es/core-content/assemblies/pages/generic-pages/madridistas/ve |
| 01.05.2026 | 00:04:03.483 | GET | /content/dam/portals/realmadrid-com/es-es/core-content/assemblies/pages/generic-pages/madridistas/ve |
| 01.05.2026 | 00:04:20.180 | GET | /graphql/execute.json/madridistas/madridistasLandingPlatinumByPath%3bpath=/content/dam/portals/madri |
| 01.05.2026 | 00:06:45.235 | GET | /graphql/execute.json/madridistas/madridistasLandingPlatinumByPath%3bpath=/content/dam/portals/madri |
| 01.05.2026 | 00:07:20.284 | GET | /graphql/execute.json/madridistas/madridistasLandingPlatinumByPath%3bpath=/content/dam/portals/madri |
| 01.05.2026 | 00:07:28.236 | GET | /graphql/execute.json/madridistas/madridistasLandingPlatinumByPath%3bpath=/content/dam/portals/madri |
| 01.05.2026 | 00:07:32.158 | org.apache.sling.commons.scheduler.impl.QuartzScheduler | Exception during job execution of job 'org.apache.jackrabbit.oak.plugins.index.lucene.directory.Luce |
| 01.05.2026 | 00:08:06.620 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 01.05.2026 | 00:08:06.666 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 01.05.2026 | 00:08:06.710 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 01.05.2026 | 00:08:36.448 | GET | /graphql/execute.json/madridistas/madridistasLandingPlatinumByPath%3bpath=/content/dam/portals/madri |
| 01.05.2026 | 00:09:15.638 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 01.05.2026 | 00:09:15.684 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 01.05.2026 | 00:09:15.728 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 01.05.2026 | 00:09:48.235 | GET | /graphql/execute.json/madridistas/madridistasLandingPlatinumByPath%3bpath=/content/dam/portals/madri |
| 01.05.2026 | 00:10:19.010 | GET | /graphql/execute.json/madridistas/madridistasLandingPlatinumByPath%3bpath=/content/dam/portals/madri |

## Recent Warnings (sample)
| Date | Time | Class | Message |
|------|------|-------|--------|
| 01.05.2026 | 00:00:09.473 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 01.05.2026 | 00:00:09.476 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 01.05.2026 | 00:00:09.478 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 01.05.2026 | 00:00:09.479 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 01.05.2026 | 00:00:09.483 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 01.05.2026 | 00:00:09.491 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 01.05.2026 | 00:00:10.214 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 01.05.2026 | 00:00:10.312 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 01.05.2026 | 00:00:10.312 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 01.05.2026 | 00:00:10.315 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 01.05.2026 | 00:00:10.315 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 01.05.2026 | 00:00:10.317 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 01.05.2026 | 00:00:10.936 | GET | /content/sling/app-servlets/realmadrid/ical.3kq9cckrnlogidldtdie2fkbl.de-de.ics HTTP/1.1] com.day.cq |
| 01.05.2026 | 00:00:10.937 | GET | /content/sling/app-servlets/realmadrid/ical.3kq9cckrnlogidldtdie2fkbl.de-de.ics HTTP/1.1] com.day.cq |
| 01.05.2026 | 00:00:11.053 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 01.05.2026 | 00:00:11.054 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 01.05.2026 | 00:00:11.054 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 01.05.2026 | 00:00:11.054 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 01.05.2026 | 00:00:11.055 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 01.05.2026 | 00:00:11.056 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 01.05.2026 | 00:00:11.087 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 799ms to become available through index. |
| 01.05.2026 | 00:00:11.898 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 769ms to become available through index. |
| 01.05.2026 | 00:00:11.928 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 794ms to become available through index. |
| 01.05.2026 | 00:00:11.935 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 804ms to become available through index. |
| 01.05.2026 | 00:00:11.975 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 802ms to become available through index. |
| 01.05.2026 | 00:00:11.976 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 801ms to become available through index. |
| 01.05.2026 | 00:00:12.251 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 01.05.2026 | 00:00:12.254 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 01.05.2026 | 00:00:12.259 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 01.05.2026 | 00:00:12.269 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 01.05.2026 | 00:00:12.323 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 01.05.2026 | 00:00:12.329 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 01.05.2026 | 00:00:12.545 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 01.05.2026 | 00:00:12.546 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 01.05.2026 | 00:00:12.548 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 01.05.2026 | 00:00:12.548 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 01.05.2026 | 00:00:12.548 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 01.05.2026 | 00:00:12.550 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 01.05.2026 | 00:00:12.777 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1649ms to become available through index. |
| 01.05.2026 | 00:00:12.894 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 01.05.2026 | 00:00:12.896 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 01.05.2026 | 00:00:12.897 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 01.05.2026 | 00:00:12.901 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 01.05.2026 | 00:00:12.903 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 01.05.2026 | 00:00:12.917 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 01.05.2026 | 00:00:13.088 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 768ms to become available through index. |
| 01.05.2026 | 00:00:13.134 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 781ms to become available through index. |
| 01.05.2026 | 00:00:13.159 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 768ms to become available through index. |
| 01.05.2026 | 00:00:13.165 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 01.05.2026 | 00:00:13.168 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
