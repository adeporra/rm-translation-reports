# AEM PROD Publish Error Report — 2026-04-21
Report date: 2026-04-21
Generated from aemerror.log — general error validation.
## Summary
- **ERROR**: 2221
- **WARN**: 203611
## By Class
| Class | ERROR | WARN |
|-------|-------|------|
| org.apache.jackrabbit.vault.fs.io.ImportOptions | 0 | 118359 |
| com.adobe.cq.updateprocessor.impl.ProcessorUtils | 0 | 45401 |
| GET | 1771 | 17449 |
| com.adobe.granite.workflow.core.WorkflowSessionImpl | 0 | 16677 |
| com.adobe.cq.dam.cfm.graphql.ModelManagerImpl | 0 | 4461 |
| org.apache.felix.webconsole | 0 | 384 |
| com.realmadridclubdefutbol.core.util.ResourceUtils | 186 | 0 |
| org.apache.jackrabbit.vault.fs.io.AutoSave | 157 | 0 |
| org.apache.jackrabbit.vault.fs.io.Importer | 0 | 157 |
| org.apache.felix.hc.core.impl.executor.HealthCheckExecutorImpl | 0 | 132 |
| org.apache.felix.configadmin.plugin.interpolation.InterpolationConfigurationPlugin | 0 | 108 |
| com.adobe.granite.ims.yamlloader.ImsYamlLoader | 0 | 48 |
| com.adobe.granite.workflow.core.job.JobHandler | 39 | 0 |
| org.apache.sling.event.impl.jobs.queues.JobQueueImpl.Granite | 0 | 39 |
| com.adobe.granite.repository.impl.SystemPrincipalsValidation | 0 | 36 |
| com.adobe.cq.dam.assethandler.internal.events.consumer.impl.AssetBatchDeliveryConsumerImpl | 0 | 36 |
| LogService.org.apache.felix.eventadmin | 32 | 1 |
| io.prometheus.client.dropwizard.DropwizardExports | 0 | 26 |
| org.apache.sling.resourceresolver.impl.VanityPathConfigurer | 0 | 24 |
| com.day.cq.dam.handler.gibson.fontmanager.impl.FontManagerServiceImpl | 0 | 24 |
| com.adobe.granite.maintenance.impl.MaintenanceTaskInfoImpl | 0 | 24 |
| com.day.cq.commons.impl.PredicateProviderImpl | 0 | 24 |
| com.adobe.cq.wcm.translation.impl.utils.I18nUtils | 0 | 24 |
| com.adobe.granite.probes.impl.K8SProbes | 0 | 24 |
| com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | 12 | 0 |
| com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | 12 | 0 |
| com.azure.core.http.netty.implementation.Utility | 0 | 12 |
| org.apache.jackrabbit.oak.plugins.index.elastic.query.inference.InferenceIndexConfig | 0 | 12 |
| com.adobe.granite.ims.client.config.ExpiryChecker | 0 | 12 |
| org.apache.jackrabbit.oak.jcr.lock.LockDeprecation | 0 | 12 |
| com.day.cq.commons.servlets.AbstractListServlet | 0 | 12 |
| com.adobe.granite.workflow.console.generate.WorkflowModelGeneratorImpl | 0 | 12 |
| org.apache.jackrabbit.oak.plugins.index.lucene.IndexCopier | 0 | 8 |
| org.apache.jackrabbit.oak.plugins.index.lucene.directory.CopyOnReadDirectory | 0 | 7 |
| com.day.crx.sling.server.impl.jmx.SecureContentRepositoryAccess | 0 | 7 |
| org.apache.sling.commons.scheduler.impl.QuartzScheduler | 6 | 0 |
| org.apache.jackrabbit.oak.plugins.index.AsyncCheckpointCreator | 0 | 5 |
| [f1c35d93-ccce-41b3-ac9b-175813d4e75c] | 0 | 4 |
| [dfd372f1-f6e9-46d4-948f-5dfbd5e0b3b0] | 0 | 4 |
| [283d616d-ec71-41db-ac2e-31b7740e3009] | 0 | 4 |
| [099b681c-a7e1-46c2-95b6-09b38b887d35] | 0 | 4 |
| [f79fc511-4051-457c-8db9-636711ddb496] | 0 | 4 |
| com.adobe.granite.maintenance.impl.TaskScheduler | 3 | 0 |
| com.adobe.granite.queries.impl.hc.QueryLimitsHealthCheck | 0 | 3 |
| org.apache.sling.distribution.journal.impl.subscriber.DistributionSubscriber | 2 | 0 |
| [894e9aab-2a7c-4284-9307-d8abd69bc134] | 0 | 2 |
| [1aab4f4f-8edf-4ce3-9be2-8e7e3d8f0fcb] | 0 | 2 |
| [9842a6db-715c-4b57-82ee-1dd8e8c324c9] | 0 | 2 |
| [ddd3b83f-8d67-4353-9ed7-5bd3f20fc450] | 0 | 2 |
| [fbfe18b7-4d53-4be0-a97d-02d31869dac7] | 1 | 0 |
| [5856cded-62bf-47e0-a962-ac7a72489cfc] | 0 | 1 |
| [9c652aa2-9e39-4f9a-b7e3-ec376f008785] | 0 | 1 |
| [960f8ffb-0262-43c3-b6d8-6a616eb45ba2] | 0 | 1 |
| [4eb6e6b8-d20d-4b69-837d-58146d1acbfb] | 0 | 1 |
| [a7f45409-c8d3-48dc-aaaa-94588f5f8081] | 0 | 1 |
| [cd171506-8ffa-4aaf-885a-db4d4211c2e2] | 0 | 1 |
| [6214b992-0206-4aed-a436-00fb57490c41] | 0 | 1 |
| [2d5e7003-51d4-4f66-8c19-15d3649eef3d] | 0 | 1 |
| [445af821-0cf3-4c6a-8fca-3711fa399196] | 0 | 1 |
| [ba47bae8-d690-46d5-af0f-c0d53b5b0a55] | 0 | 1 |
| [6c71b764-05c4-43d9-a4b0-69d05bf0ec05] | 0 | 1 |
| [f5ee672d-5266-47c6-9ef8-8fa316b34963] | 0 | 1 |
| [dcdc9b9a-0b5b-4324-8da2-b3b39a047db3] | 0 | 1 |
| [44b30dcf-149d-4e4b-8ce9-b0b48929161b] | 0 | 1 |
| [4a5dda1d-2327-4cd7-a56b-08752b4fc4ce] | 0 | 1 |
| [38a24f6d-e084-4f13-9b39-f6ebff4eaa81] | 0 | 1 |
| [04076dfd-18e3-4006-983b-ac32955b095d] | 0 | 1 |
| [5fed014a-ab68-4bf2-a4ea-53716830d05a] | 0 | 1 |
| [72f82f8f-141d-4601-a4db-3af9ae5957f4] | 0 | 1 |
| [56eda044-8a75-4efe-92f2-af4cb2552ba4] | 0 | 1 |
| [3819b6bc-3a10-455f-ba78-938d755afa86] | 0 | 1 |
| [9d78d5af-68a4-427b-a214-d7366f4f5dd6] | 0 | 1 |
| [229e95b8-9fda-4f3e-99b3-74d752bbdc27] | 0 | 1 |

## Recent Errors (sample)
| Date | Time | Class | Message |
|------|------|-------|--------|
| 22.04.2026 | 00:00:00.070 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 22.04.2026 | 00:00:00.070 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [672] |
| 22.04.2026 | 00:00:00.077 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [672] |
| 22.04.2026 | 00:00:00.077 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 22.04.2026 | 00:00:00.093 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 22.04.2026 | 00:00:00.093 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [672] |
| 22.04.2026 | 00:00:00.102 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [672] |
| 22.04.2026 | 00:00:00.102 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 22.04.2026 | 00:00:00.109 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [672] |
| 22.04.2026 | 00:00:00.109 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 22.04.2026 | 00:00:00.137 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [672] |
| 22.04.2026 | 00:00:00.137 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 22.04.2026 | 00:00:47.557 | GET | /content/dam/portals/realmadrid-com/en-us/news/generic/2026/04/21/(fut)-rm-alaves-j33-liga/videos/21 |
| 22.04.2026 | 00:01:14.779 | GET | /graphql/execute.json/realmadridmastersite/diaryV2;fromDate=2026-04-22T00:00:00.000Z;toDate=2026-05- |
| 22.04.2026 | 00:01:40.393 | org.apache.jackrabbit.vault.fs.io.AutoSave | Error during auto save, retrying after refresh: javax.jcr.InvalidItemStateException: OakState0001: U |
| 22.04.2026 | 00:01:40.651 | org.apache.jackrabbit.vault.fs.io.AutoSave | Error during auto save, retrying after refresh: javax.jcr.InvalidItemStateException: OakState0001: U |
| 22.04.2026 | 00:01:42.583 | org.apache.jackrabbit.vault.fs.io.AutoSave | Error during auto save, retrying after refresh: javax.jcr.InvalidItemStateException: OakState0001: U |
| 22.04.2026 | 00:01:43.342 | com.realmadridclubdefutbol.core.util.ResourceUtils | Error occured while committing resource resolver |
| 22.04.2026 | 00:01:43.731 | com.realmadridclubdefutbol.core.util.ResourceUtils | Error occured while committing resource resolver |
| 22.04.2026 | 00:01:44.025 | com.realmadridclubdefutbol.core.util.ResourceUtils | Error occured while committing resource resolver |
| 22.04.2026 | 00:01:44.360 | com.realmadridclubdefutbol.core.util.ResourceUtils | Error occured while committing resource resolver |
| 22.04.2026 | 00:01:44.425 | com.realmadridclubdefutbol.core.util.ResourceUtils | Error occured while committing resource resolver |
| 22.04.2026 | 00:01:44.439 | com.adobe.granite.workflow.core.job.JobHandler | Error executing workflow step |
| 22.04.2026 | 00:02:12.719 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 22.04.2026 | 00:02:12.853 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 22.04.2026 | 00:02:12.901 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 22.04.2026 | 00:02:38.743 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 22.04.2026 | 00:02:38.785 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 22.04.2026 | 00:02:38.827 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 22.04.2026 | 00:03:31.166 | GET | /content/dam/portals/realmadrid-com/ja-jp/news/generic/2026/04/21/(fut)-rm-alaves-j33-liga/videos/21 |
| 22.04.2026 | 00:04:42.423 | GET | /content/dam/portals/realmadrid-com/en-us/news/generic/2026/04/21/(fut)-rm-alaves-j33-liga/videos/21 |
| 22.04.2026 | 00:04:43.567 | GET | /content/dam/portals/realmadrid-com/en-us/news/generic/2026/04/21/(fut)-rm-alaves-j33-liga/videos/21 |
| 22.04.2026 | 00:05:56.241 | GET | /content/dam/portals/realmadrid-com/ja-jp/news/generic/2026/04/21/(fut)-rm-alaves-j33-liga/videos/21 |
| 22.04.2026 | 00:06:07.721 | GET | /content/dam/portals/realmadrid-com/en-us/news/generic/2026/04/21/(fut)-rm-alaves-j33-liga/videos/21 |
| 22.04.2026 | 00:07:16.206 | com.adobe.granite.maintenance.impl.TaskScheduler | No maintenance windows found at granite/operations/maintenance |
| 22.04.2026 | 00:07:16.509 | com.adobe.granite.maintenance.impl.TaskScheduler | No maintenance windows found at granite/operations/maintenance |
| 22.04.2026 | 00:07:56.308 | org.apache.jackrabbit.vault.fs.io.AutoSave | Error during auto save, retrying after refresh: javax.jcr.InvalidItemStateException: OakState0001: U |
| 22.04.2026 | 00:08:32.952 | GET | /content/dam/portals/realmadrid-com/hi-in/core-content/assemblies/footer/mobile-app-section/Google%2 |
| 22.04.2026 | 00:08:33.825 | GET | /content/dam/portals/realmadrid-com/hi-in/core-content/assemblies/footer/mobile-app-section/Google%2 |
| 22.04.2026 | 00:08:34.052 | GET | /content/dam/portals/realmadrid-com/hi-in/core-content/assemblies/footer/mobile-app-section/Google%2 |
| 22.04.2026 | 00:08:56.158 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 22.04.2026 | 00:08:56.293 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 22.04.2026 | 00:08:56.338 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 22.04.2026 | 00:11:22.878 | GET | /content/dam/portals/realmadrid-com/en-us/news/generic/2026/04/21/(fut)-rm-alaves-j33-liga/videos/21 |
| 22.04.2026 | 00:12:33.291 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 22.04.2026 | 00:12:33.331 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 22.04.2026 | 00:12:33.371 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 22.04.2026 | 00:15:16.300 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 22.04.2026 | 00:15:16.345 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 22.04.2026 | 00:15:16.389 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |

## Recent Warnings (sample)
| Date | Time | Class | Message |
|------|------|-------|--------|
| 22.04.2026 | 00:00:00.016 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1623ms to become available through index. |
| 22.04.2026 | 00:00:00.338 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1618ms to become available through index. |
| 22.04.2026 | 00:00:00.398 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1624ms to become available through index. |
| 22.04.2026 | 00:00:00.898 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 779ms to become available through index. |
| 22.04.2026 | 00:00:01.094 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1578ms to become available through index. |
| 22.04.2026 | 00:00:01.208 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 768ms to become available through index. |
| 22.04.2026 | 00:00:01.473 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.tagging.impl.JcrTagImpl |
| 22.04.2026 | 00:00:01.782 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1580ms to become available through index. |
| 22.04.2026 | 00:00:02.175 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1583ms to become available through index. |
| 22.04.2026 | 00:00:02.603 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1580ms to become available through index. |
| 22.04.2026 | 00:00:02.856 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1571ms to become available through index. |
| 22.04.2026 | 00:00:03.037 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 779ms to become available through index. |
| 22.04.2026 | 00:00:03.163 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1578ms to become available through index. |
| 22.04.2026 | 00:00:03.280 | GET | /graphql/execute.json/areavip/eventList%3bfromDate=2026-04-22T00:00%3btoDate=2027-04-22T00:00%3b.jso |
| 22.04.2026 | 00:00:03.489 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 829ms to become available through index. |
| 22.04.2026 | 00:00:03.658 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 768ms to become available through index. |
| 22.04.2026 | 00:00:04.706 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1588ms to become available through index. |
| 22.04.2026 | 00:00:04.908 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 4785ms to become available through index. |
| 22.04.2026 | 00:00:05.195 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1608ms to become available through index. |
| 22.04.2026 | 00:00:06.502 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1571ms to become available through index. |
| 22.04.2026 | 00:00:06.669 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 4800ms to become available through index. |
| 22.04.2026 | 00:00:06.822 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1582ms to become available through index. |
| 22.04.2026 | 00:00:07.871 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 775ms to become available through index. |
| 22.04.2026 | 00:00:08.007 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 4800ms to become available through index. |
| 22.04.2026 | 00:00:08.153 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1567ms to become available through index. |
| 22.04.2026 | 00:00:08.549 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1576ms to become available through index. |
| 22.04.2026 | 00:00:08.572 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 4804ms to become available through index. |
| 22.04.2026 | 00:00:09.308 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 22.04.2026 | 00:00:09.308 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 22.04.2026 | 00:00:09.317 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 22.04.2026 | 00:00:09.319 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 22.04.2026 | 00:00:09.324 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 22.04.2026 | 00:00:09.448 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 22.04.2026 | 00:00:09.513 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1576ms to become available through index. |
| 22.04.2026 | 00:00:09.643 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 4800ms to become available through index. |
| 22.04.2026 | 00:00:09.717 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1578ms to become available through index. |
| 22.04.2026 | 00:00:09.726 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 22.04.2026 | 00:00:09.726 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 22.04.2026 | 00:00:09.728 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 22.04.2026 | 00:00:09.728 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 22.04.2026 | 00:00:09.728 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 22.04.2026 | 00:00:09.769 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1574ms to become available through index. |
| 22.04.2026 | 00:00:09.791 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 22.04.2026 | 00:00:09.920 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.tagging.impl.JcrTagImpl |
| 22.04.2026 | 00:00:09.921 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.tagging.impl.JcrTagImpl |
| 22.04.2026 | 00:00:09.921 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.tagging.impl.JcrTagImpl |
| 22.04.2026 | 00:00:09.922 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.tagging.impl.JcrTagImpl |
| 22.04.2026 | 00:00:09.922 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.tagging.impl.JcrTagImpl |
| 22.04.2026 | 00:00:09.922 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.tagging.impl.JcrTagImpl |
| 22.04.2026 | 00:00:09.923 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.tagging.impl.JcrTagImpl |
