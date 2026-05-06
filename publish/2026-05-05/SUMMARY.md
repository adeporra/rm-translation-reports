# AEM PROD Publish Error Report — 2026-05-05
Report date: 2026-05-05
Generated from aemerror.log — general error validation.
## Summary
- **ERROR**: 1173
- **WARN**: 98996
## By Class
| Class | ERROR | WARN |
|-------|-------|------|
| org.apache.jackrabbit.vault.fs.io.ImportOptions | 0 | 42626 |
| com.adobe.cq.updateprocessor.impl.ProcessorUtils | 0 | 28862 |
| GET | 1117 | 15798 |
| com.adobe.granite.workflow.core.WorkflowSessionImpl | 0 | 6032 |
| com.adobe.cq.dam.cfm.graphql.ModelManagerImpl | 0 | 4557 |
| org.apache.felix.webconsole | 0 | 384 |
| org.apache.felix.hc.core.impl.executor.HealthCheckExecutorImpl | 0 | 160 |
| org.apache.felix.configadmin.plugin.interpolation.InterpolationConfigurationPlugin | 0 | 108 |
| org.apache.jackrabbit.oak.plugins.index.lucene.IndexCopier | 0 | 55 |
| com.adobe.granite.ims.yamlloader.ImsYamlLoader | 0 | 48 |
| io.prometheus.client.dropwizard.DropwizardExports | 0 | 46 |
| com.adobe.granite.repository.impl.SystemPrincipalsValidation | 0 | 36 |
| com.adobe.cq.dam.assethandler.internal.events.consumer.impl.AssetBatchDeliveryConsumerImpl | 0 | 36 |
| org.apache.sling.resourceresolver.impl.VanityPathConfigurer | 0 | 24 |
| com.day.cq.dam.handler.gibson.fontmanager.impl.FontManagerServiceImpl | 0 | 24 |
| com.adobe.cq.wcm.translation.impl.utils.I18nUtils | 0 | 24 |
| com.day.cq.commons.impl.PredicateProviderImpl | 0 | 24 |
| com.adobe.granite.probes.impl.K8SProbes | 0 | 24 |
| com.adobe.granite.maintenance.impl.MaintenanceTaskInfoImpl | 0 | 19 |
| LogService.org.apache.felix.eventadmin | 15 | 0 |
| com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | 12 | 0 |
| com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | 12 | 0 |
| com.azure.core.http.netty.implementation.Utility | 0 | 12 |
| org.apache.jackrabbit.oak.plugins.index.elastic.query.inference.InferenceIndexConfig | 0 | 12 |
| com.adobe.granite.ims.client.config.ExpiryChecker | 0 | 12 |
| org.apache.jackrabbit.oak.jcr.lock.LockDeprecation | 0 | 12 |
| com.day.cq.commons.servlets.AbstractListServlet | 0 | 12 |
| com.adobe.granite.workflow.console.generate.WorkflowModelGeneratorImpl | 0 | 12 |
| org.apache.sling.commons.scheduler.impl.QuartzScheduler | 7 | 0 |
| com.day.crx.sling.server.impl.jmx.SecureContentRepositoryAccess | 0 | 7 |
| Events.Framework.org.apache.felix.log | 6 | 0 |
| org.apache.jackrabbit.oak.plugins.index.lucene.directory.CopyOnReadDirectory | 0 | 4 |
| Events.Framework.com.adobe.cq.dam.cq-dam-processor-nui | 3 | 0 |
| org.apache.jackrabbit.oak.plugins.index.AsyncCheckpointCreator | 0 | 3 |
| ROOT | 1 | 0 |
| [56b6ea79-9e5a-4ad1-8f16-a7574fcd0841] | 0 | 1 |
| com.adobe.cq.assetcompute.impl.smartcrop.CreateCropAssetComputeService | 0 | 1 |
| com.adobe.cq.assetcompute.impl.smartcrop.CreateCropAssetComputeEventHandler | 0 | 1 |
| com.adobe.cq.assetcompute.impl.connection.ConnectionServiceImpl | 0 | 1 |
| [a93b90fc-079f-43f9-8036-2b2a9f1d9322] | 0 | 1 |
| [4ec3d22a-24a9-4c3e-8be6-693ad2d2e515] | 0 | 1 |
| [28298209-5534-4e69-aa02-f3156e1bd2bf] | 0 | 1 |
| [a0ed16de-cf0e-4431-b568-08615a739bff] | 0 | 1 |
| [edec8e54-0a14-4667-b172-f652c0d49009] | 0 | 1 |
| [edde9893-77ea-4ee6-b4b8-9374e9ac8ac0] | 0 | 1 |
| [164bb295-0841-4512-9d44-a7a1cf20ed16] | 0 | 1 |
| [70b0dd22-00ab-4aee-a341-f10287469977] | 0 | 1 |
| [6c8337c9-0fc5-45a3-88e0-b7de6fc99dff] | 0 | 1 |
| [d998fc0f-b421-4782-b343-8b8b1d719d94] | 0 | 1 |
| [fd148c7e-ead1-4b2b-9ec4-b05573af0350] | 0 | 1 |
| [73b53877-b460-4351-9218-89738a76afcb] | 0 | 1 |
| [7e9d6161-9533-4844-bb21-89b40f198836] | 0 | 1 |
| [49f0d6d1-7ddd-4e66-be67-1fbe91be5eb3] | 0 | 1 |
| [9ebb6a9b-49c7-450a-94b3-79925325c37a] | 0 | 1 |
| [732d9b51-1752-4703-b493-268122203e4c] | 0 | 1 |
| [a3ed41cf-6161-44d5-8110-43a8e8f3164c] | 0 | 1 |
| [1ae3bff9-7783-4eff-90fb-b7f9dd77d5a6] | 0 | 1 |
| [a5ad71a0-5e59-4966-85c9-360c0105e404] | 0 | 1 |

## Recent Errors (sample)
| Date | Time | Class | Message |
|------|------|-------|--------|
| 06.05.2026 | 00:00:00.307 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 06.05.2026 | 00:00:00.307 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [673] |
| 06.05.2026 | 00:00:00.316 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [673] |
| 06.05.2026 | 00:00:00.318 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 06.05.2026 | 00:00:00.329 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [673] |
| 06.05.2026 | 00:00:00.332 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 06.05.2026 | 00:00:00.345 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 06.05.2026 | 00:00:00.345 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [673] |
| 06.05.2026 | 00:00:00.386 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [673] |
| 06.05.2026 | 00:00:00.386 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 06.05.2026 | 00:00:00.775 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 06.05.2026 | 00:00:00.775 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [673] |
| 06.05.2026 | 00:00:05.858 | GET | /graphql/execute.json/madridistas/madridistasLandingPlatinumByPath%3bpath=/content/dam/portals/madri |
| 06.05.2026 | 00:01:13.042 | GET | /graphql/execute.json/madridistas/madridistasLandingPlatinumByPath%3bpath=/content/dam/portals/madri |
| 06.05.2026 | 00:01:21.435 | GET | /graphql/execute.json/madridistas/madridistasLandingPlatinumByPath%3bpath=/content/dam/portals/madri |
| 06.05.2026 | 00:02:21.599 | GET | /graphql/execute.json/madridistas/madridistasLandingPlatinumByPath%3bpath=/content/dam/portals/madri |
| 06.05.2026 | 00:03:21.528 | GET | /graphql/execute.json/madridistas/madridistasLandingPlatinumByPath%3bpath=/content/dam/portals/madri |
| 06.05.2026 | 00:03:57.816 | GET | /graphql/execute.json/realmadridmastersite/news-section-detail-assembly%3bpath=%252Fcontent%252Fdam% |
| 06.05.2026 | 00:04:20.052 | GET | /content/dam/portals/realmadrid-com/es-es/core-content/assemblies/pages/generic-pages/madridistas/ve |
| 06.05.2026 | 00:04:20.512 | GET | /content/dam/portals/realmadrid-com/es-es/core-content/assemblies/pages/generic-pages/madridistas/ve |
| 06.05.2026 | 00:04:20.632 | GET | /content/dam/portals/realmadrid-com/es-es/core-content/assemblies/pages/generic-pages/madridistas/ve |
| 06.05.2026 | 00:04:43.753 | GET | /content/dam/portals/realmadrid-com/es-es/core-content/assemblies/pages/generic-pages/madridistas/ve |
| 06.05.2026 | 00:04:43.875 | GET | /content/dam/portals/realmadrid-com/es-es/core-content/assemblies/pages/generic-pages/madridistas/ve |
| 06.05.2026 | 00:04:43.995 | GET | /content/dam/portals/realmadrid-com/es-es/core-content/assemblies/pages/generic-pages/madridistas/ve |
| 06.05.2026 | 00:05:45.182 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 06.05.2026 | 00:05:45.323 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 06.05.2026 | 00:05:45.373 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 06.05.2026 | 00:06:55.922 | org.apache.sling.commons.scheduler.impl.QuartzScheduler | Exception during job execution of job 'org.apache.jackrabbit.oak.plugins.index.lucene.directory.Luce |
| 06.05.2026 | 00:08:20.250 | GET | /graphql/execute.json/madridistas/madridistasLandingPlatinumByPath%3bpath=/content/dam/portals/madri |
| 06.05.2026 | 00:08:28.253 | org.apache.sling.commons.scheduler.impl.QuartzScheduler | Exception during job execution of job 'org.apache.jackrabbit.oak.plugins.index.lucene.directory.Luce |
| 06.05.2026 | 00:08:32.868 | GET | /content/dam/common/statics/public-content/badge/basket/default-badge.app.svg HTTP/1.1] com.realmadr |
| 06.05.2026 | 00:08:32.973 | GET | /content/dam/common/statics/public-content/badge/basket/default-badge.app.svg HTTP/1.1] com.realmadr |
| 06.05.2026 | 00:08:33.012 | GET | /content/dam/common/statics/public-content/badge/basket/default-badge.app.svg HTTP/1.1] com.realmadr |
| 06.05.2026 | 00:09:05.018 | GET | /graphql/execute.json/madridistas/madridistasLandingPlatinumByPath%3bpath=/content/dam/portals/madri |
| 06.05.2026 | 00:09:07.440 | org.apache.sling.commons.scheduler.impl.QuartzScheduler | Exception during job execution of job 'org.apache.jackrabbit.oak.plugins.index.lucene.directory.Luce |
| 06.05.2026 | 00:09:52.364 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 06.05.2026 | 00:09:52.367 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.servlets.re |
| 06.05.2026 | 00:09:52.367 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.servlets.re |
| 06.05.2026 | 00:09:52.368 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 06.05.2026 | 00:09:52.369 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 06.05.2026 | 00:09:53.026 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 06.05.2026 | 00:09:53.028 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.servlets.re |
| 06.05.2026 | 00:09:53.028 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.servlets.re |
| 06.05.2026 | 00:09:53.029 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 06.05.2026 | 00:09:53.030 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 06.05.2026 | 00:09:53.598 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 06.05.2026 | 00:09:53.599 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.servlets.re |
| 06.05.2026 | 00:09:53.600 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 06.05.2026 | 00:09:53.600 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.servlets.re |
| 06.05.2026 | 00:09:53.601 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |

## Recent Warnings (sample)
| Date | Time | Class | Message |
|------|------|-------|--------|
| 06.05.2026 | 00:00:02.259 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.tagging.impl.JcrTagImpl |
| 06.05.2026 | 00:00:08.680 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 06.05.2026 | 00:00:08.683 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 06.05.2026 | 00:00:08.683 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 06.05.2026 | 00:00:08.685 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 06.05.2026 | 00:00:08.687 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 06.05.2026 | 00:00:08.696 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 06.05.2026 | 00:00:08.968 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 06.05.2026 | 00:00:08.996 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 06.05.2026 | 00:00:09.036 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 06.05.2026 | 00:00:09.069 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 06.05.2026 | 00:00:09.070 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 06.05.2026 | 00:00:09.101 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 06.05.2026 | 00:00:09.718 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 06.05.2026 | 00:00:09.719 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 06.05.2026 | 00:00:09.721 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 06.05.2026 | 00:00:09.723 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 06.05.2026 | 00:00:09.725 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 06.05.2026 | 00:00:09.743 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 06.05.2026 | 00:00:10.433 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 06.05.2026 | 00:00:10.434 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 06.05.2026 | 00:00:10.435 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 06.05.2026 | 00:00:10.437 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 06.05.2026 | 00:00:10.440 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 06.05.2026 | 00:00:10.534 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 06.05.2026 | 00:00:10.831 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 06.05.2026 | 00:00:10.836 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 06.05.2026 | 00:00:10.853 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 06.05.2026 | 00:00:10.870 | GET | /content/sling/app-servlets/realmadrid/ical.3kq9cckrnlogidldtdie2fkbl.ja-jp.ics HTTP/1.1] com.day.cq |
| 06.05.2026 | 00:00:10.870 | GET | /content/sling/app-servlets/realmadrid/ical.3kq9cckrnlogidldtdie2fkbl.ja-jp.ics HTTP/1.1] com.day.cq |
| 06.05.2026 | 00:00:10.873 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 06.05.2026 | 00:00:10.877 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 06.05.2026 | 00:00:10.902 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 06.05.2026 | 00:00:11.155 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 06.05.2026 | 00:00:11.164 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 06.05.2026 | 00:00:11.214 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 06.05.2026 | 00:00:11.214 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 06.05.2026 | 00:00:11.237 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 06.05.2026 | 00:00:11.238 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 06.05.2026 | 00:00:11.524 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 06.05.2026 | 00:00:11.532 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 06.05.2026 | 00:00:11.534 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 06.05.2026 | 00:00:11.540 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 06.05.2026 | 00:00:11.553 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 06.05.2026 | 00:00:11.572 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 06.05.2026 | 00:00:11.973 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 06.05.2026 | 00:00:11.987 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 06.05.2026 | 00:00:12.016 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 06.05.2026 | 00:00:12.017 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 06.05.2026 | 00:00:12.018 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
