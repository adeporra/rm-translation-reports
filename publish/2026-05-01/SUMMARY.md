# AEM PROD Publish Error Report — 2026-05-01
Report date: 2026-05-01
Generated from aemerror.log — general error validation.
## Summary
- **ERROR**: 1118
- **WARN**: 94594
## By Class
| Class | ERROR | WARN |
|-------|-------|------|
| org.apache.jackrabbit.vault.fs.io.ImportOptions | 0 | 40971 |
| com.adobe.cq.updateprocessor.impl.ProcessorUtils | 0 | 29342 |
| GET | 1078 | 14887 |
| com.adobe.granite.workflow.core.WorkflowSessionImpl | 0 | 5652 |
| com.adobe.cq.dam.cfm.graphql.ModelManagerImpl | 0 | 3059 |
| org.apache.felix.webconsole | 0 | 256 |
| org.apache.felix.hc.core.impl.executor.HealthCheckExecutorImpl | 0 | 93 |
| org.apache.felix.configadmin.plugin.interpolation.InterpolationConfigurationPlugin | 0 | 72 |
| com.adobe.granite.ims.yamlloader.ImsYamlLoader | 0 | 32 |
| com.adobe.cq.dam.assethandler.internal.events.consumer.impl.AssetBatchDeliveryConsumerImpl | 0 | 24 |
| com.adobe.granite.repository.impl.SystemPrincipalsValidation | 0 | 24 |
| com.adobe.granite.probes.impl.K8SProbes | 0 | 16 |
| com.day.cq.commons.impl.PredicateProviderImpl | 0 | 16 |
| org.apache.sling.resourceresolver.impl.VanityPathConfigurer | 0 | 16 |
| com.day.cq.dam.handler.gibson.fontmanager.impl.FontManagerServiceImpl | 0 | 16 |
| com.adobe.cq.wcm.translation.impl.utils.I18nUtils | 0 | 16 |
| com.adobe.granite.maintenance.impl.MaintenanceTaskInfoImpl | 0 | 14 |
| com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | 12 | 0 |
| com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | 12 | 0 |
| io.prometheus.client.dropwizard.DropwizardExports | 0 | 9 |
| com.azure.core.http.netty.implementation.Utility | 0 | 8 |
| org.apache.jackrabbit.oak.plugins.index.elastic.query.inference.InferenceIndexConfig | 0 | 8 |
| com.adobe.granite.ims.client.config.ExpiryChecker | 0 | 8 |
| com.adobe.granite.workflow.console.generate.WorkflowModelGeneratorImpl | 0 | 8 |
| org.apache.jackrabbit.oak.jcr.lock.LockDeprecation | 0 | 8 |
| com.day.cq.commons.servlets.AbstractListServlet | 0 | 8 |
| com.day.crx.sling.server.impl.jmx.SecureContentRepositoryAccess | 0 | 7 |
| Events.Framework.org.apache.felix.log | 6 | 0 |
| LogService.org.apache.felix.eventadmin | 5 | 0 |
| org.apache.sling.commons.scheduler.impl.QuartzScheduler | 4 | 0 |
| [bde90838-826b-431d-92dc-1a55afcd9b47] | 0 | 2 |
| [9980beb3-5d7a-4a94-bc72-0cfd8e880c65] | 1 | 0 |
| org.apache.jackrabbit.oak.plugins.index.lucene.directory.CopyOnReadDirectory | 0 | 1 |
| org.apache.jackrabbit.oak.plugins.index.lucene.IndexCopier | 0 | 1 |
| org.apache.jackrabbit.oak.plugins.index.AsyncCheckpointCreator | 0 | 1 |
| [431bc223-145d-449a-9ac0-9f7e4e1310b3] | 0 | 1 |
| [0a01ee1d-8ac3-4e28-a575-f82c56c9be6d] | 0 | 1 |
| [0a2c0925-1d30-4227-8664-152995c2c148] | 0 | 1 |
| [d9cae279-7cba-48a9-8e3f-a51928e4d816] | 0 | 1 |
| [498f527d-40c4-4697-9c89-24feebd31645] | 0 | 1 |
| [df87ab42-52c1-4798-b04d-bc5bbc6b5361] | 0 | 1 |
| [4ac9754c-f647-4e89-80f2-ce39d7f1bdb3] | 0 | 1 |
| [efa64741-8f12-4ded-9db5-b489a4ea9088] | 0 | 1 |
| [ff286fc5-c6e6-4397-95cd-b3e6ee266096] | 0 | 1 |
| [9e5cbce3-9b16-4593-8319-81df6a0a3d1a] | 0 | 1 |
| [8a50829e-b707-4370-bcd4-e6dfc2e73170] | 0 | 1 |
| [b1d6754a-001b-4b80-8e2c-67fc8b5f1bd7] | 0 | 1 |
| [66a6fcdd-1ef4-409e-8a2c-a1b8861f82d1] | 0 | 1 |
| [0b614691-005b-46f2-9f67-00e1f86846d7] | 0 | 1 |
| [513f37cb-75f6-4d58-b011-509f3ad912a7] | 0 | 1 |
| [9219398e-a133-4875-b687-d5b5c813e633] | 0 | 1 |
| [4e2680fe-2e67-4289-bc19-d529b9efcb0f] | 0 | 1 |
| [998d8fbb-8b4c-4d75-8233-cf3b5a0228cf] | 0 | 1 |
| [f9294869-4263-48f6-8755-00fea7bf21a0] | 0 | 1 |

## Recent Errors (sample)
| Date | Time | Class | Message |
|------|------|-------|--------|
| 02.05.2026 | 00:00:00.078 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [657] |
| 02.05.2026 | 00:00:00.079 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 02.05.2026 | 00:00:00.090 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [657] |
| 02.05.2026 | 00:00:00.091 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 02.05.2026 | 00:00:00.100 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 02.05.2026 | 00:00:00.100 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [657] |
| 02.05.2026 | 00:00:00.107 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 02.05.2026 | 00:00:00.107 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [657] |
| 02.05.2026 | 00:00:00.134 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 02.05.2026 | 00:00:00.134 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [657] |
| 02.05.2026 | 00:00:00.152 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 02.05.2026 | 00:00:00.152 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [657] |
| 02.05.2026 | 00:00:24.522 | GET | /graphql/execute.json/madridistas/madridistasLandingPlatinumByPath%3bpath=/content/dam/portals/madri |
| 02.05.2026 | 00:01:06.183 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 02.05.2026 | 00:01:06.276 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 02.05.2026 | 00:01:06.315 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 02.05.2026 | 00:01:06.360 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 02.05.2026 | 00:01:06.410 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 02.05.2026 | 00:01:06.453 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 02.05.2026 | 00:01:13.159 | GET | /graphql/execute.json/realmadridmastersite/news-section-detail-assembly%3bpath=%252Fcontent%252Fdam% |
| 02.05.2026 | 00:02:20.393 | GET | /graphql/execute.json/madridistas/madridistasLandingPlatinumByPath%3bpath=/content/dam/portals/madri |
| 02.05.2026 | 00:02:58.150 | GET | /graphql/execute.json/realmadridmastersite/diaryV2;fromDate=2026-05-02T00:00:00.000Z;toDate=2026-07- |
| 02.05.2026 | 00:03:08.789 | GET | /graphql/execute.json/madridistas/madridistasLandingPlatinumByPath%3bpath=/content/dam/portals/madri |
| 02.05.2026 | 00:07:36.586 | org.apache.sling.commons.scheduler.impl.QuartzScheduler | Exception during job execution of job 'org.apache.jackrabbit.oak.plugins.index.lucene.directory.Luce |
| 02.05.2026 | 00:07:55.826 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 02.05.2026 | 00:07:55.933 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 02.05.2026 | 00:07:55.977 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 02.05.2026 | 00:08:08.685 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 02.05.2026 | 00:08:08.755 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 02.05.2026 | 00:08:08.817 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 02.05.2026 | 00:08:08.862 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 02.05.2026 | 00:08:08.891 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 02.05.2026 | 00:08:08.931 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 02.05.2026 | 00:08:10.122 | GET | /graphql/execute.json/madridistas/madridistasLandingPlatinumByPath%3bpath=/content/dam/portals/madri |
| 02.05.2026 | 00:08:20.063 | GET | /graphql/execute.json/madridistas/madridistasLandingPlatinumByPath%3bpath=/content/dam/portals/madri |
| 02.05.2026 | 00:09:31.510 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 02.05.2026 | 00:09:31.512 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 02.05.2026 | 00:09:31.512 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.servlets.re |
| 02.05.2026 | 00:09:31.512 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.servlets.re |
| 02.05.2026 | 00:09:31.513 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 02.05.2026 | 00:09:32.657 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 02.05.2026 | 00:09:32.659 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.servlets.re |
| 02.05.2026 | 00:09:32.659 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.servlets.re |
| 02.05.2026 | 00:09:32.660 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 02.05.2026 | 00:09:32.661 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 02.05.2026 | 00:09:33.016 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 02.05.2026 | 00:09:33.017 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.servlets.re |
| 02.05.2026 | 00:09:33.018 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.servlets.re |
| 02.05.2026 | 00:09:33.018 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 02.05.2026 | 00:09:33.018 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |

## Recent Warnings (sample)
| Date | Time | Class | Message |
|------|------|-------|--------|
| 02.05.2026 | 00:00:04.033 | GET | /graphql/execute.json/areavip/eventList%3bfromDate=2026-05-02T00:00%3btoDate=2027-05-02T00:00%3b.jso |
| 02.05.2026 | 00:00:04.915 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.search.impl.builder.Roo |
| 02.05.2026 | 00:00:04.916 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.search.impl.builder.Roo |
| 02.05.2026 | 00:00:04.917 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.tagging.impl.JcrTagImpl |
| 02.05.2026 | 00:00:04.918 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.tagging.impl.JcrTagImpl |
| 02.05.2026 | 00:00:04.918 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.tagging.impl.JcrTagImpl |
| 02.05.2026 | 00:00:04.918 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.tagging.impl.JcrTagImpl |
| 02.05.2026 | 00:00:04.919 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.tagging.impl.JcrTagImpl |
| 02.05.2026 | 00:00:04.919 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.tagging.impl.JcrTagImpl |
| 02.05.2026 | 00:00:04.920 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.tagging.impl.JcrTagImpl |
| 02.05.2026 | 00:00:04.920 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.tagging.impl.JcrTagImpl |
| 02.05.2026 | 00:00:04.920 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.tagging.impl.JcrTagImpl |
| 02.05.2026 | 00:00:04.921 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.tagging.impl.JcrTagImpl |
| 02.05.2026 | 00:00:04.921 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.tagging.impl.JcrTagImpl |
| 02.05.2026 | 00:00:04.921 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.tagging.impl.JcrTagImpl |
| 02.05.2026 | 00:00:08.375 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 02.05.2026 | 00:00:08.387 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 02.05.2026 | 00:00:08.392 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 02.05.2026 | 00:00:08.704 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 02.05.2026 | 00:00:08.705 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 02.05.2026 | 00:00:08.705 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 02.05.2026 | 00:00:09.147 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 02.05.2026 | 00:00:09.147 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 02.05.2026 | 00:00:09.148 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 02.05.2026 | 00:00:09.532 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 02.05.2026 | 00:00:09.533 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 02.05.2026 | 00:00:09.533 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 02.05.2026 | 00:00:09.932 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 02.05.2026 | 00:00:09.936 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 02.05.2026 | 00:00:09.942 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 02.05.2026 | 00:00:10.346 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 02.05.2026 | 00:00:10.347 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 02.05.2026 | 00:00:10.347 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 02.05.2026 | 00:00:10.393 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1607ms to become available through index. |
| 02.05.2026 | 00:00:10.414 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1591ms to become available through index. |
| 02.05.2026 | 00:00:10.493 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1576ms to become available through index. |
| 02.05.2026 | 00:00:10.679 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 02.05.2026 | 00:00:10.681 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 02.05.2026 | 00:00:10.685 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 02.05.2026 | 00:00:11.290 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 02.05.2026 | 00:00:11.291 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 02.05.2026 | 00:00:11.292 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 02.05.2026 | 00:00:11.862 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 02.05.2026 | 00:00:11.863 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 02.05.2026 | 00:00:11.863 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 02.05.2026 | 00:00:12.134 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1617ms to become available through index. |
| 02.05.2026 | 00:00:12.400 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1572ms to become available through index. |
| 02.05.2026 | 00:00:12.931 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 02.05.2026 | 00:00:12.934 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 02.05.2026 | 00:00:12.936 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
