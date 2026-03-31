# AEM PROD Publish Error Report — 2026-03-30
Report date: 2026-03-30
Generated from aemerror.log — general error validation.
## Summary
- **ERROR**: 1201
- **WARN**: 87843
## By Class
| Class | ERROR | WARN |
|-------|-------|------|
| org.apache.jackrabbit.vault.fs.io.ImportOptions | 0 | 38553 |
| com.adobe.cq.updateprocessor.impl.ProcessorUtils | 0 | 28847 |
| GET | 1172 | 11721 |
| com.adobe.granite.workflow.core.WorkflowSessionImpl | 0 | 5507 |
| com.adobe.cq.dam.cfm.graphql.ModelManagerImpl | 0 | 2597 |
| org.apache.felix.webconsole | 0 | 224 |
| org.apache.felix.hc.core.impl.executor.HealthCheckExecutorImpl | 0 | 92 |
| org.apache.felix.configadmin.plugin.interpolation.InterpolationConfigurationPlugin | 0 | 63 |
| com.adobe.granite.ims.yamlloader.ImsYamlLoader | 0 | 28 |
| com.adobe.cq.dam.assethandler.internal.events.consumer.impl.AssetBatchDeliveryConsumerImpl | 0 | 21 |
| com.adobe.granite.probes.impl.K8SProbes | 0 | 14 |
| com.day.cq.commons.impl.PredicateProviderImpl | 0 | 14 |
| org.apache.sling.resourceresolver.impl.VanityPathConfigurer | 0 | 14 |
| com.day.cq.dam.handler.gibson.fontmanager.impl.FontManagerServiceImpl | 0 | 14 |
| com.adobe.granite.repository.impl.SystemPrincipalsValidation | 0 | 14 |
| com.adobe.cq.wcm.translation.impl.utils.I18nUtils | 0 | 14 |
| com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | 12 | 0 |
| com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | 12 | 0 |
| org.apache.jackrabbit.oak.plugins.index.lucene.IndexCopier | 0 | 11 |
| com.adobe.granite.maintenance.impl.MaintenanceTaskInfoImpl | 0 | 11 |
| org.apache.jackrabbit.oak.plugins.index.lucene.directory.CopyOnReadDirectory | 0 | 10 |
| com.azure.core.http.netty.implementation.Utility | 0 | 7 |
| org.apache.jackrabbit.oak.plugins.index.elastic.query.inference.InferenceIndexConfig | 0 | 7 |
| com.adobe.granite.workflow.console.generate.WorkflowModelGeneratorImpl | 0 | 7 |
| org.apache.jackrabbit.oak.jcr.lock.LockDeprecation | 0 | 7 |
| com.day.cq.commons.servlets.AbstractListServlet | 0 | 7 |
| com.day.cq.dam.core.impl.malware.QuarantineServiceImpl | 0 | 7 |
| com.day.crx.sling.server.impl.jmx.SecureContentRepositoryAccess | 0 | 6 |
| org.apache.sling.commons.scheduler.impl.QuartzScheduler | 5 | 0 |
| com.adobe.granite.queries.impl.hc.QueryLimitsHealthCheck | 0 | 5 |
| io.prometheus.client.dropwizard.DropwizardExports | 0 | 4 |
| org.apache.jackrabbit.oak.plugins.index.AsyncCheckpointCreator | 0 | 2 |
| [c80a7022-97c6-49ea-be80-48da525c0491] | 0 | 2 |
| [e4b7a3b3-1aa7-4903-ab7c-15aa457cfe84] | 0 | 2 |
| [597602b5-9396-4f00-91b8-3880d0dcfbbd] | 0 | 1 |
| [4a7e6544-40e2-49af-b8fc-8404125616e3] | 0 | 1 |
| [f4276994-f344-43ac-a637-7f1a56095094] | 0 | 1 |
| [11685582-1751-4d22-a1ab-5a00cf44d260] | 0 | 1 |
| [ecf0cd05-c66e-41f5-ac54-282a645d6754] | 0 | 1 |
| [11eacf74-8ac3-42ec-9b76-78b13982e905] | 0 | 1 |
| [53fcf1a7-932f-4077-b192-75929b98b7fa] | 0 | 1 |
| [1d93b84e-652e-4592-a1f1-98904a662697] | 0 | 1 |
| [dac4dcbf-e4c7-4444-9356-248ced8c22b6] | 0 | 1 |
| [92e52885-d6c2-4977-bbcc-2c2b558c91f2] | 0 | 1 |
| [4650e48d-8cd3-447f-899f-0735e13ccd1b] | 0 | 1 |

## Recent Errors (sample)
| Date | Time | Class | Message |
|------|------|-------|--------|
| 31.03.2026 | 00:00:00.062 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [654] |
| 31.03.2026 | 00:00:00.063 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 31.03.2026 | 00:00:00.086 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 31.03.2026 | 00:00:00.086 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [654] |
| 31.03.2026 | 00:00:00.106 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [654] |
| 31.03.2026 | 00:00:00.107 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 31.03.2026 | 00:00:00.143 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 31.03.2026 | 00:00:00.143 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [654] |
| 31.03.2026 | 00:00:00.154 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 31.03.2026 | 00:00:00.154 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [654] |
| 31.03.2026 | 00:00:00.167 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [654] |
| 31.03.2026 | 00:00:00.167 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 31.03.2026 | 00:00:10.165 | GET | /content/dam/portals/realmadrid-com/ar-ae/news/generic/2026/03/28/videos/240326%20S7%20WEB%20CALENDA |
| 31.03.2026 | 00:00:50.839 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 31.03.2026 | 00:00:50.883 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 31.03.2026 | 00:00:50.925 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 31.03.2026 | 00:02:33.730 | GET | /graphql/execute.json/estadio/newsListByTagV2;alang=/content/dam/portals/estadio/es-es/;tag=%7b%22_e |
| 31.03.2026 | 00:03:44.121 | GET | /content/dam/portals/realmadrid-com/ar-ae/news/generic/2026/03/28/videos/240326%20S7%20WEB%20CALENDA |
| 31.03.2026 | 00:03:47.873 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 31.03.2026 | 00:03:47.875 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.servlets.re |
| 31.03.2026 | 00:03:47.875 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.servlets.re |
| 31.03.2026 | 00:03:47.876 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 31.03.2026 | 00:03:47.877 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 31.03.2026 | 00:03:48.060 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 31.03.2026 | 00:03:48.061 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.servlets.re |
| 31.03.2026 | 00:03:48.061 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.servlets.re |
| 31.03.2026 | 00:03:48.062 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 31.03.2026 | 00:03:48.062 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 31.03.2026 | 00:03:48.272 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 31.03.2026 | 00:03:48.273 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.servlets.re |
| 31.03.2026 | 00:03:48.274 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.servlets.re |
| 31.03.2026 | 00:03:48.274 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 31.03.2026 | 00:03:48.275 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 31.03.2026 | 00:05:26.599 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 31.03.2026 | 00:05:26.729 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 31.03.2026 | 00:05:26.777 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 31.03.2026 | 00:05:52.010 | org.apache.sling.commons.scheduler.impl.QuartzScheduler | Exception during job execution of job 'org.apache.jackrabbit.oak.plugins.index.lucene.directory.Luce |
| 31.03.2026 | 00:06:38.104 | org.apache.sling.commons.scheduler.impl.QuartzScheduler | Exception during job execution of job 'org.apache.jackrabbit.oak.plugins.index.lucene.directory.Luce |
| 31.03.2026 | 00:07:12.636 | GET | /content/dam/portals/realmadrid-com/ja-jp/news/generic/2026/03/28/videos/240326%20S7%20WEB%20CALENDA |
| 31.03.2026 | 00:07:13.203 | GET | /content/dam/portals/realmadrid-com/en-us/news/generic/2026/03/28/videos/240326%20S7%20WEB%20CALENDA |
| 31.03.2026 | 00:07:55.331 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 31.03.2026 | 00:07:55.376 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 31.03.2026 | 00:07:55.422 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 31.03.2026 | 00:09:02.095 | GET | /content/dam/portals/realmadrid-com/ar-ae/news/generic/2026/03/28/videos/240326%20S7%20WEB%20CALENDA |
| 31.03.2026 | 00:09:52.421 | GET | /content/dam/portals/realmadrid-com/de-de/news/generic/2026/03/28/videos/240326%20S7%20WEB%20CALENDA |
| 31.03.2026 | 00:10:10.643 | GET | /content/dam/portals/realmadrid-com/pt-pt/news/generic/2026/03/28/videos/240326%20S7%20WEB%20CALENDA |
| 31.03.2026 | 00:11:00.105 | GET | /content/dam/portals/realmadrid-com/en-us/news/generic/2026/03/28/videos/240326%20S7%20WEB%20CALENDA |
| 31.03.2026 | 00:11:15.037 | GET | /content/dam/portals/realmadrid-com/fr-fr/news/generic/2026/03/28/videos/240326%20S7%20WEB%20CALENDA |
| 31.03.2026 | 00:11:17.891 | GET | /content/dam/portals/realmadrid-com/en-us/news/generic/2026/03/28/videos/240326%20S7%20WEB%20CALENDA |
| 31.03.2026 | 00:11:18.696 | GET | /content/dam/portals/realmadrid-com/en-us/news/generic/2026/03/28/videos/240326%20S7%20WEB%20CALENDA |

## Recent Warnings (sample)
| Date | Time | Class | Message |
|------|------|-------|--------|
| 31.03.2026 | 00:00:06.444 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 31.03.2026 | 00:00:06.490 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 31.03.2026 | 00:00:06.491 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 31.03.2026 | 00:00:06.511 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 31.03.2026 | 00:00:06.511 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 31.03.2026 | 00:00:06.515 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 31.03.2026 | 00:00:06.929 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 31.03.2026 | 00:00:06.930 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 31.03.2026 | 00:00:06.930 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 31.03.2026 | 00:00:06.931 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 31.03.2026 | 00:00:06.932 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 31.03.2026 | 00:00:06.933 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 31.03.2026 | 00:00:07.390 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 31.03.2026 | 00:00:07.390 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 31.03.2026 | 00:00:07.397 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 31.03.2026 | 00:00:07.404 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 31.03.2026 | 00:00:07.431 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 31.03.2026 | 00:00:07.452 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 31.03.2026 | 00:00:07.609 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 799ms to become available through index. |
| 31.03.2026 | 00:00:07.814 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 807ms to become available through index. |
| 31.03.2026 | 00:00:07.860 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 808ms to become available through index. |
| 31.03.2026 | 00:00:07.869 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 807ms to become available through index. |
| 31.03.2026 | 00:00:07.886 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 804ms to become available through index. |
| 31.03.2026 | 00:00:07.949 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 808ms to become available through index. |
| 31.03.2026 | 00:00:08.075 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 31.03.2026 | 00:00:08.078 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 31.03.2026 | 00:00:08.078 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 31.03.2026 | 00:00:08.078 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 31.03.2026 | 00:00:08.078 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 31.03.2026 | 00:00:08.083 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 31.03.2026 | 00:00:08.088 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.search.impl.builder.Roo |
| 31.03.2026 | 00:00:08.089 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.search.impl.builder.Roo |
| 31.03.2026 | 00:00:08.090 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.search.impl.builder.Roo |
| 31.03.2026 | 00:00:08.091 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.tagging.impl.JcrTagImpl |
| 31.03.2026 | 00:00:08.092 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.tagging.impl.JcrTagImpl |
| 31.03.2026 | 00:00:08.092 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.tagging.impl.JcrTagImpl |
| 31.03.2026 | 00:00:08.092 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.tagging.impl.JcrTagImpl |
| 31.03.2026 | 00:00:08.093 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.tagging.impl.JcrTagImpl |
| 31.03.2026 | 00:00:08.093 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.tagging.impl.JcrTagImpl |
| 31.03.2026 | 00:00:08.093 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.tagging.impl.JcrTagImpl |
| 31.03.2026 | 00:00:08.093 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.tagging.impl.JcrTagImpl |
| 31.03.2026 | 00:00:08.094 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.tagging.impl.JcrTagImpl |
| 31.03.2026 | 00:00:08.094 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.tagging.impl.JcrTagImpl |
| 31.03.2026 | 00:00:08.094 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.tagging.impl.JcrTagImpl |
| 31.03.2026 | 00:00:08.094 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.tagging.impl.JcrTagImpl |
| 31.03.2026 | 00:00:08.421 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 31.03.2026 | 00:00:08.422 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 31.03.2026 | 00:00:08.424 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 31.03.2026 | 00:00:08.425 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 31.03.2026 | 00:00:08.427 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
