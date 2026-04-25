# AEM PROD Publish Error Report — 2026-04-24
Report date: 2026-04-24
Generated from aemerror.log — general error validation.
## Summary
- **ERROR**: 641
- **WARN**: 139438
## By Class
| Class | ERROR | WARN |
|-------|-------|------|
| org.apache.jackrabbit.vault.fs.io.ImportOptions | 0 | 73895 |
| com.adobe.cq.updateprocessor.impl.ProcessorUtils | 0 | 37442 |
| GET | 548 | 14575 |
| com.adobe.granite.workflow.core.WorkflowSessionImpl | 0 | 10303 |
| com.adobe.cq.dam.cfm.graphql.ModelManagerImpl | 0 | 2597 |
| org.apache.felix.webconsole | 0 | 224 |
| org.apache.felix.hc.core.impl.executor.HealthCheckExecutorImpl | 0 | 86 |
| org.apache.felix.configadmin.plugin.interpolation.InterpolationConfigurationPlugin | 0 | 63 |
| com.realmadridclubdefutbol.core.util.ResourceUtils | 30 | 0 |
| com.adobe.granite.ims.yamlloader.ImsYamlLoader | 0 | 28 |
| com.adobe.cq.dam.assethandler.internal.events.consumer.impl.AssetBatchDeliveryConsumerImpl | 0 | 21 |
| com.adobe.granite.repository.impl.SystemPrincipalsValidation | 0 | 21 |
| org.apache.jackrabbit.vault.fs.io.AutoSave | 20 | 0 |
| org.apache.jackrabbit.vault.fs.io.Importer | 0 | 20 |
| com.adobe.granite.probes.impl.K8SProbes | 0 | 14 |
| com.day.cq.commons.impl.PredicateProviderImpl | 0 | 14 |
| org.apache.sling.resourceresolver.impl.VanityPathConfigurer | 0 | 14 |
| com.day.cq.dam.handler.gibson.fontmanager.impl.FontManagerServiceImpl | 0 | 14 |
| com.adobe.cq.wcm.translation.impl.utils.I18nUtils | 0 | 14 |
| com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | 12 | 0 |
| com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | 12 | 0 |
| com.adobe.granite.maintenance.impl.MaintenanceTaskInfoImpl | 0 | 11 |
| io.prometheus.client.dropwizard.DropwizardExports | 0 | 9 |
| com.azure.core.http.netty.implementation.Utility | 0 | 7 |
| org.apache.jackrabbit.oak.plugins.index.elastic.query.inference.InferenceIndexConfig | 0 | 7 |
| com.adobe.granite.ims.client.config.ExpiryChecker | 0 | 7 |
| org.apache.jackrabbit.oak.jcr.lock.LockDeprecation | 0 | 7 |
| com.day.cq.commons.servlets.AbstractListServlet | 0 | 7 |
| com.adobe.granite.workflow.console.generate.WorkflowModelGeneratorImpl | 0 | 7 |
| com.day.crx.sling.server.impl.jmx.SecureContentRepositoryAccess | 0 | 7 |
| com.adobe.granite.workflow.core.job.JobHandler | 6 | 0 |
| org.apache.sling.event.impl.jobs.queues.JobQueueImpl.Granite | 0 | 6 |
| org.apache.sling.commons.scheduler.impl.QuartzScheduler | 4 | 0 |
| Events.Framework.com.adobe.cq.dam.cq-dam-processor-nui | 3 | 0 |
| org.apache.jackrabbit.oak.plugins.index.lucene.IndexCopier | 0 | 3 |
| org.apache.jackrabbit.oak.plugins.index.lucene.directory.CopyOnReadDirectory | 0 | 3 |
| Events.Framework.org.apache.felix.log | 2 | 0 |
| LogService.org.apache.felix.eventadmin | 1 | 0 |
| [2b41f1a3-ae5b-462c-b997-2feb1044f465] | 1 | 0 |
| ROOT | 1 | 0 |
| [b199a141-4fa0-46fa-b13c-2ac3f9c542c2] | 1 | 0 |
| [fffb9f05-c3e7-47e0-ab54-0b1ba93b3055] | 0 | 1 |
| [b6e59a2e-af10-4f35-8214-6b32c6200d02] | 0 | 1 |
| [9e184ae4-ea60-48ce-89b3-a44e40065d0b] | 0 | 1 |
| [c546f07e-de5b-4851-b450-c43a6d9f05e3] | 0 | 1 |
| [90ffc273-a6c8-44ba-a63c-ac657af0f99a] | 0 | 1 |
| com.adobe.cq.assetcompute.impl.smartcrop.CreateCropAssetComputeService | 0 | 1 |
| com.adobe.cq.assetcompute.impl.smartcrop.CreateCropAssetComputeEventHandler | 0 | 1 |
| com.adobe.cq.assetcompute.impl.connection.ConnectionServiceImpl | 0 | 1 |
| [dcbc1b02-5905-4fb5-85e3-58b2c336e700] | 0 | 1 |
| [edc3005a-879e-4768-9288-aa744a7df4de] | 0 | 1 |
| [f8d24d39-5b19-4f04-b676-996e0803f5a7] | 0 | 1 |
| [f7baf036-75c4-418e-a0b4-f570ce499a68] | 0 | 1 |

## Recent Errors (sample)
| Date | Time | Class | Message |
|------|------|-------|--------|
| 25.04.2026 | 00:00:00.059 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [672] |
| 25.04.2026 | 00:00:00.059 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 25.04.2026 | 00:00:00.092 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 25.04.2026 | 00:00:00.092 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [672] |
| 25.04.2026 | 00:00:00.105 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [672] |
| 25.04.2026 | 00:00:00.105 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 25.04.2026 | 00:00:00.123 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [672] |
| 25.04.2026 | 00:00:00.123 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 25.04.2026 | 00:00:00.125 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 25.04.2026 | 00:00:00.125 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [672] |
| 25.04.2026 | 00:00:00.191 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 25.04.2026 | 00:00:00.191 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [672] |
| 25.04.2026 | 00:00:44.573 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 25.04.2026 | 00:00:44.615 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 25.04.2026 | 00:00:44.657 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 25.04.2026 | 00:02:25.991 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 25.04.2026 | 00:02:26.032 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 25.04.2026 | 00:02:26.077 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 25.04.2026 | 00:03:32.261 | GET | /graphql/execute.json/realmadridmastersite/diaryV2;fromDate=2026-04-25T00:00:00.000Z;toDate=2027-04- |
| 25.04.2026 | 00:05:37.670 | GET | /graphql/execute.json/realmadridmastersite/trophyCategoriesAssemblyByPath%3bpath=/content/dam/portal |
| 25.04.2026 | 00:06:20.435 | GET | /graphql/execute.json/realmadridmastersite/diaryV2%3bfromDate=2026-04-24T23:00:00.000Z%3btoDate=2026 |
| 25.04.2026 | 00:06:55.921 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 25.04.2026 | 00:06:56.022 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 25.04.2026 | 00:06:56.052 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 25.04.2026 | 00:06:56.093 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 25.04.2026 | 00:06:56.156 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 25.04.2026 | 00:06:56.198 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 25.04.2026 | 00:07:37.124 | org.apache.jackrabbit.vault.fs.io.AutoSave | Error during auto save, retrying after refresh: javax.jcr.InvalidItemStateException: OakState0001: U |
| 25.04.2026 | 00:08:27.421 | GET | /content/dam/portals/realmadrid-com/en-us/news/generic/2026/03/10/videos/100326%20RMTV%20WEB%20TOTAL |
| 25.04.2026 | 00:09:15.608 | org.apache.sling.commons.scheduler.impl.QuartzScheduler | Exception during job execution of job 'org.apache.jackrabbit.oak.plugins.index.lucene.directory.Luce |
| 25.04.2026 | 00:10:20.541 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 25.04.2026 | 00:10:20.677 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 25.04.2026 | 00:10:20.720 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 25.04.2026 | 00:10:38.698 | org.apache.jackrabbit.vault.fs.io.AutoSave | Error during auto save, retrying after refresh: javax.jcr.InvalidItemStateException: OakState0001: U |
| 25.04.2026 | 00:10:38.708 | org.apache.jackrabbit.vault.fs.io.AutoSave | Error during auto save, retrying after refresh: javax.jcr.InvalidItemStateException: OakState0001: U |
| 25.04.2026 | 00:12:03.428 | GET | /graphql/execute.json/realmadridmastersite/diaryV2;fromDate=2026-04-25T00:00:00.000Z;toDate=2026-07- |
| 25.04.2026 | 00:13:06.572 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 25.04.2026 | 00:13:06.574 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 25.04.2026 | 00:13:06.619 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 25.04.2026 | 00:13:06.675 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 25.04.2026 | 00:13:06.705 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 25.04.2026 | 00:13:06.747 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 25.04.2026 | 00:13:13.231 | org.apache.jackrabbit.vault.fs.io.AutoSave | Error during auto save, retrying after refresh: javax.jcr.InvalidItemStateException: OakState0001: U |
| 25.04.2026 | 00:13:13.254 | org.apache.jackrabbit.vault.fs.io.AutoSave | Error during auto save, retrying after refresh: javax.jcr.InvalidItemStateException: OakState0001: U |
| 25.04.2026 | 00:13:13.273 | org.apache.jackrabbit.vault.fs.io.AutoSave | Error during auto save, retrying after refresh: javax.jcr.InvalidItemStateException: OakState0001: U |
| 25.04.2026 | 00:13:42.694 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 25.04.2026 | 00:13:42.736 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 25.04.2026 | 00:13:42.782 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 25.04.2026 | 00:14:30.173 | org.apache.sling.commons.scheduler.impl.QuartzScheduler | Exception during job execution of job 'org.apache.jackrabbit.oak.plugins.index.lucene.directory.Luce |
| 25.04.2026 | 00:18:09.238 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |

## Recent Warnings (sample)
| Date | Time | Class | Message |
|------|------|-------|--------|
| 25.04.2026 | 00:00:00.228 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 803ms to become available through index. |
| 25.04.2026 | 00:00:00.344 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 773ms to become available through index. |
| 25.04.2026 | 00:00:00.565 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1576ms to become available through index. |
| 25.04.2026 | 00:00:00.600 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 25.04.2026 | 00:00:00.601 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 25.04.2026 | 00:00:00.605 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 25.04.2026 | 00:00:00.606 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 25.04.2026 | 00:00:00.619 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 25.04.2026 | 00:00:00.636 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 25.04.2026 | 00:00:00.706 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1611ms to become available through index. |
| 25.04.2026 | 00:00:00.824 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1618ms to become available through index. |
| 25.04.2026 | 00:00:00.852 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1610ms to become available through index. |
| 25.04.2026 | 00:00:01.254 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 25.04.2026 | 00:00:01.255 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 25.04.2026 | 00:00:01.256 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 25.04.2026 | 00:00:01.257 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 25.04.2026 | 00:00:01.259 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 25.04.2026 | 00:00:01.262 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 25.04.2026 | 00:00:01.933 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1568ms to become available through index. |
| 25.04.2026 | 00:00:02.014 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 778ms to become available through index. |
| 25.04.2026 | 00:00:02.065 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1659ms to become available through index. |
| 25.04.2026 | 00:00:02.588 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1608ms to become available through index. |
| 25.04.2026 | 00:00:02.660 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1603ms to become available through index. |
| 25.04.2026 | 00:00:02.682 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.search.impl.builder.Roo |
| 25.04.2026 | 00:00:02.683 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.search.impl.builder.Roo |
| 25.04.2026 | 00:00:02.684 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.search.impl.builder.Roo |
| 25.04.2026 | 00:00:02.829 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1606ms to become available through index. |
| 25.04.2026 | 00:00:03.777 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1579ms to become available through index. |
| 25.04.2026 | 00:00:03.847 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1576ms to become available through index. |
| 25.04.2026 | 00:00:04.000 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1573ms to become available through index. |
| 25.04.2026 | 00:00:04.202 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1582ms to become available through index. |
| 25.04.2026 | 00:00:04.292 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1569ms to become available through index. |
| 25.04.2026 | 00:00:05.657 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1572ms to become available through index. |
| 25.04.2026 | 00:00:05.863 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1585ms to become available through index. |
| 25.04.2026 | 00:00:05.884 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1572ms to become available through index. |
| 25.04.2026 | 00:00:05.925 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1578ms to become available through index. |
| 25.04.2026 | 00:00:05.939 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1574ms to become available through index. |
| 25.04.2026 | 00:00:06.537 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 799ms to become available through index. |
| 25.04.2026 | 00:00:07.367 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 776ms to become available through index. |
| 25.04.2026 | 00:00:07.537 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1569ms to become available through index. |
| 25.04.2026 | 00:00:07.557 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1581ms to become available through index. |
| 25.04.2026 | 00:00:07.606 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1577ms to become available through index. |
| 25.04.2026 | 00:00:08.179 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 4796ms to become available through index. |
| 25.04.2026 | 00:00:08.333 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 770ms to become available through index. |
| 25.04.2026 | 00:00:08.488 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 837ms to become available through index. |
| 25.04.2026 | 00:00:09.035 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1576ms to become available through index. |
| 25.04.2026 | 00:00:09.241 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1571ms to become available through index. |
| 25.04.2026 | 00:00:09.491 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 775ms to become available through index. |
| 25.04.2026 | 00:00:09.942 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1578ms to become available through index. |
| 25.04.2026 | 00:00:09.950 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1572ms to become available through index. |
