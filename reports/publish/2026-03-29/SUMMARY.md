# AEM PROD Publish Error Report — 2026-03-29
Report date: 2026-03-29
Generated from aemerror.log — general error validation.
## Summary
- **ERROR**: 1234
- **WARN**: 91965
## By Class
| Class | ERROR | WARN |
|-------|-------|------|
| org.apache.jackrabbit.vault.fs.io.ImportOptions | 0 | 40025 |
| com.adobe.cq.updateprocessor.impl.ProcessorUtils | 0 | 29727 |
| GET | 1204 | 13900 |
| com.adobe.granite.workflow.core.WorkflowSessionImpl | 0 | 5507 |
| com.adobe.cq.dam.cfm.graphql.ModelManagerImpl | 0 | 2235 |
| org.apache.felix.webconsole | 0 | 209 |
| org.apache.felix.hc.core.impl.executor.HealthCheckExecutorImpl | 0 | 88 |
| org.apache.felix.configadmin.plugin.interpolation.InterpolationConfigurationPlugin | 0 | 63 |
| com.adobe.granite.ims.yamlloader.ImsYamlLoader | 0 | 24 |
| com.adobe.cq.dam.assethandler.internal.events.consumer.impl.AssetBatchDeliveryConsumerImpl | 0 | 18 |
| com.adobe.granite.probes.impl.K8SProbes | 0 | 14 |
| org.apache.sling.resourceresolver.impl.VanityPathConfigurer | 0 | 14 |
| com.day.cq.dam.handler.gibson.fontmanager.impl.FontManagerServiceImpl | 0 | 14 |
| com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | 12 | 0 |
| com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | 12 | 0 |
| com.day.cq.commons.impl.PredicateProviderImpl | 0 | 12 |
| com.adobe.granite.repository.impl.SystemPrincipalsValidation | 0 | 12 |
| com.adobe.cq.wcm.translation.impl.utils.I18nUtils | 0 | 12 |
| com.adobe.granite.maintenance.impl.MaintenanceTaskInfoImpl | 0 | 10 |
| com.azure.core.http.netty.implementation.Utility | 0 | 7 |
| org.apache.jackrabbit.oak.plugins.index.elastic.query.inference.InferenceIndexConfig | 0 | 7 |
| com.adobe.granite.queries.impl.hc.QueryLimitsHealthCheck | 0 | 6 |
| org.apache.jackrabbit.oak.jcr.lock.LockDeprecation | 0 | 6 |
| com.adobe.granite.workflow.console.generate.WorkflowModelGeneratorImpl | 0 | 6 |
| com.day.cq.commons.servlets.AbstractListServlet | 0 | 6 |
| com.day.cq.dam.core.impl.malware.QuarantineServiceImpl | 0 | 6 |
| com.day.crx.sling.server.impl.jmx.SecureContentRepositoryAccess | 0 | 6 |
| com.day.cq.audit.impl.AuditLogMaintenanceTask | 0 | 6 |
| io.prometheus.client.dropwizard.DropwizardExports | 0 | 5 |
| org.apache.sling.commons.scheduler.impl.QuartzScheduler | 3 | 0 |
| org.apache.jackrabbit.oak.plugins.index.lucene.IndexCopier | 0 | 2 |
| org.apache.jackrabbit.oak.plugins.index.lucene.directory.CopyOnReadDirectory | 0 | 2 |
| com.adobe.granite.repository.impl.SlingRepositoryManager | 1 | 0 |
| com.adobe.granite.panic.impl.PanicLoggerDetail | 1 | 0 |
| com.adobe.granite.maintenance.impl.TaskScheduler | 1 | 0 |
| org.apache.jackrabbit.oak.plugins.index.AsyncCheckpointCreator | 0 | 1 |
| [b0ab6a21-8e08-469d-8f0c-b17c93818728] | 0 | 1 |
| [1b4cd2e6-ccab-479b-971d-7476375b5885] | 0 | 1 |
| [9a9d53d8-9ec7-4e93-a730-d34ee7b70d7c] | 0 | 1 |
| [45072d4d-2e45-47f2-801d-88de29e8dcf1] | 0 | 1 |
| [3cf0b5bf-2c62-4688-8d2a-50e8a338c449] | 0 | 1 |
| [9d874eb0-45ad-4229-b209-1a87d10fef3b] | 0 | 1 |
| [29daecd9-71d9-41f2-8c8f-26d4074592e0] | 0 | 1 |
| [942b866a-e6cc-4c82-91d7-c69fa22e3756] | 0 | 1 |
| [ab1785ab-bf70-42b6-b0a3-c3131472b3ca] | 0 | 1 |
| [43b3475d-5b3b-4d14-b3a0-48e5e191a648] | 0 | 1 |
| [62e5d6a9-e599-426f-83c1-9d7aa8435d29] | 0 | 1 |
| [dff8bdb4-88c1-40fd-ada1-20fdcdb48f5a] | 0 | 1 |
| [dbeb477b-f7fe-4c72-b0b9-850bda6ff896] | 0 | 1 |
| [305b527e-6b97-4886-85d6-933cd6929676] | 0 | 1 |
| [fd4d95a8-5059-482d-b87e-3380f232fee8] | 0 | 1 |

## Recent Errors (sample)
| Date | Time | Class | Message |
|------|------|-------|--------|
| 30.03.2026 | 00:00:00.085 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [654] |
| 30.03.2026 | 00:00:00.086 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 30.03.2026 | 00:00:00.098 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [654] |
| 30.03.2026 | 00:00:00.098 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 30.03.2026 | 00:00:00.100 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 30.03.2026 | 00:00:00.100 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [654] |
| 30.03.2026 | 00:00:00.140 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [654] |
| 30.03.2026 | 00:00:00.140 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 30.03.2026 | 00:00:00.163 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 30.03.2026 | 00:00:00.163 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [654] |
| 30.03.2026 | 00:00:00.183 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [654] |
| 30.03.2026 | 00:00:00.183 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 30.03.2026 | 00:00:12.051 | GET | /graphql/execute.json/realmadridmastersite/news-section-detail-assembly%3bpath=%252Fcontent%252Fdam% |
| 30.03.2026 | 00:01:09.663 | GET | /content/dam/portals/realmadrid-com/en-us/news/generic/2026/03/28/videos/240326%20S7%20WEB%20CALENDA |
| 30.03.2026 | 00:01:25.553 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 30.03.2026 | 00:01:25.692 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 30.03.2026 | 00:01:25.742 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 30.03.2026 | 00:01:38.781 | GET | /content/dam/portals/realmadrid-com/en-us/news/generic/2026/03/28/videos/240326%20S7%20WEB%20CALENDA |
| 30.03.2026 | 00:01:55.999 | GET | /content/dam/portals/realmadrid-com/pt-pt/news/generic/2026/03/28/videos/240326%20S7%20WEB%20CALENDA |
| 30.03.2026 | 00:01:59.726 | GET | /content/dam/portals/realmadrid-com/en-us/news/generic/2026/03/28/videos/240326%20S7%20WEB%20CALENDA |
| 30.03.2026 | 00:02:58.762 | GET | /graphql/execute.json/realmadridmastersite/diaryV2;fromDate=2026-03-30T00:00:00.000Z;toDate=2026-06- |
| 30.03.2026 | 00:03:12.414 | GET | /content/dam/portals/realmadrid-com/en-us/news/generic/2026/03/28/videos/240326%20S7%20WEB%20CALENDA |
| 30.03.2026 | 00:04:10.311 | GET | /content/dam/portals/realmadrid-com/en-us/news/generic/2026/03/28/videos/240326%20S7%20WEB%20CALENDA |
| 30.03.2026 | 00:05:45.017 | GET | /content/dam/portals/realmadrid-com/en-us/news/generic/2026/03/28/videos/240326%20S7%20WEB%20CALENDA |
| 30.03.2026 | 00:05:55.334 | GET | /content/dam/portals/realmadrid-com/en-us/news/generic/2026/03/28/videos/240326%20S7%20WEB%20CALENDA |
| 30.03.2026 | 00:07:23.704 | org.apache.sling.commons.scheduler.impl.QuartzScheduler | Exception during job execution of job 'org.apache.jackrabbit.oak.plugins.index.lucene.directory.Luce |
| 30.03.2026 | 00:07:32.598 | GET | /content/dam/portals/realmadrid-com/en-us/news/generic/2026/03/28/videos/240326%20S7%20WEB%20CALENDA |
| 30.03.2026 | 00:08:00.747 | GET | /content/dam/portals/realmadrid-com/en-us/news/generic/2026/03/28/videos/240326%20S7%20WEB%20CALENDA |
| 30.03.2026 | 00:08:07.075 | GET | /content/dam/portals/realmadrid-com/en-us/news/generic/2026/03/28/videos/240326%20S7%20WEB%20CALENDA |
| 30.03.2026 | 00:09:01.569 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 30.03.2026 | 00:09:01.586 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 30.03.2026 | 00:09:01.605 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 30.03.2026 | 00:09:01.635 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 30.03.2026 | 00:09:01.654 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 30.03.2026 | 00:09:01.682 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 30.03.2026 | 00:10:07.174 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 30.03.2026 | 00:10:07.254 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 30.03.2026 | 00:10:07.280 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 30.03.2026 | 00:10:44.595 | GET | /graphql/execute.json/realmadridmastersite/diaryV2;fromDate=2026-03-30T00:00:00.000Z;toDate=2026-06- |
| 30.03.2026 | 00:11:42.630 | GET | /content/dam/portals/realmadrid-com/en-us/news/generic/2026/03/28/videos/240326%20S7%20WEB%20CALENDA |
| 30.03.2026 | 00:11:46.327 | GET | /content/dam/portals/realmadrid-com/en-us/news/generic/2026/03/28/videos/240326%20S7%20WEB%20CALENDA |
| 30.03.2026 | 00:13:22.635 | GET | /content/dam/portals/realmadrid-com/fr-fr/news/generic/2026/03/28/videos/240326%20S7%20WEB%20CALENDA |
| 30.03.2026 | 00:13:40.849 | GET | /content/dam/portals/realmadrid-com/en-us/news/generic/2026/03/28/videos/240326%20S7%20WEB%20CALENDA |
| 30.03.2026 | 00:13:41.588 | GET | /content/dam/portals/realmadrid-com/de-de/news/generic/2026/03/28/videos/240326%20S7%20WEB%20CALENDA |
| 30.03.2026 | 00:15:18.265 | GET | /graphql/execute.json/estadio/newsListByTagV2;alang=/content/dam/portals/estadio/en-us/;tag=%7b%22_e |
| 30.03.2026 | 00:15:22.478 | GET | /content/dam/portals/realmadrid-com/ar-ae/news/generic/2026/03/28/videos/240326%20S7%20WEB%20CALENDA |
| 30.03.2026 | 00:15:26.190 | GET | /graphql/execute.json/realmadridmastersite/news-section-detail-assembly%3bpath=%252Fcontent%252Fdam% |
| 30.03.2026 | 00:15:27.366 | GET | /content/dam/portals/realmadrid-com/en-us/news/generic/2026/03/28/videos/240326%20S7%20WEB%20CALENDA |
| 30.03.2026 | 00:17:13.296 | GET | /content/dam/portals/realmadrid-com/en-us/news/generic/2026/03/28/videos/240326%20S7%20WEB%20CALENDA |
| 30.03.2026 | 00:18:15.113 | GET | /content/dam/portals/realmadrid-com/ar-ae/news/generic/2026/03/28/videos/240326%20S7%20WEB%20CALENDA |

## Recent Warnings (sample)
| Date | Time | Class | Message |
|------|------|-------|--------|
| 30.03.2026 | 00:00:06.711 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 30.03.2026 | 00:00:06.715 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 30.03.2026 | 00:00:06.716 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 30.03.2026 | 00:00:06.717 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 30.03.2026 | 00:00:06.717 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 30.03.2026 | 00:00:06.763 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 30.03.2026 | 00:00:06.905 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 30.03.2026 | 00:00:06.927 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 30.03.2026 | 00:00:06.931 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 30.03.2026 | 00:00:06.933 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 30.03.2026 | 00:00:06.938 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 30.03.2026 | 00:00:06.979 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 30.03.2026 | 00:00:07.297 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 30.03.2026 | 00:00:07.299 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 30.03.2026 | 00:00:07.299 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 30.03.2026 | 00:00:07.300 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 30.03.2026 | 00:00:07.301 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 30.03.2026 | 00:00:07.305 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 30.03.2026 | 00:00:07.681 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 30.03.2026 | 00:00:07.683 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 30.03.2026 | 00:00:07.684 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 30.03.2026 | 00:00:07.685 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 30.03.2026 | 00:00:07.686 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 30.03.2026 | 00:00:07.686 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 30.03.2026 | 00:00:07.863 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 30.03.2026 | 00:00:07.873 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 30.03.2026 | 00:00:07.874 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 30.03.2026 | 00:00:07.907 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 30.03.2026 | 00:00:07.907 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 30.03.2026 | 00:00:07.939 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 30.03.2026 | 00:00:08.161 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 30.03.2026 | 00:00:08.161 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 30.03.2026 | 00:00:08.162 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 30.03.2026 | 00:00:08.162 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 30.03.2026 | 00:00:08.165 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 30.03.2026 | 00:00:08.177 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 30.03.2026 | 00:00:08.470 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 30.03.2026 | 00:00:08.471 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 30.03.2026 | 00:00:08.476 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 30.03.2026 | 00:00:08.480 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 30.03.2026 | 00:00:08.483 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 30.03.2026 | 00:00:08.487 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 30.03.2026 | 00:00:08.687 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1608ms to become available through index. |
| 30.03.2026 | 00:00:08.699 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1625ms to become available through index. |
| 30.03.2026 | 00:00:08.704 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1611ms to become available through index. |
| 30.03.2026 | 00:00:08.745 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1620ms to become available through index. |
| 30.03.2026 | 00:00:08.745 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1619ms to become available through index. |
| 30.03.2026 | 00:00:08.763 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1579ms to become available through index. |
| 30.03.2026 | 00:00:09.009 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 30.03.2026 | 00:00:09.011 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
