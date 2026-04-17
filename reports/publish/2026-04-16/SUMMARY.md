# AEM PROD Publish Error Report — 2026-04-16
Report date: 2026-04-16
Generated from aemerror.log — general error validation.
## Summary
- **ERROR**: 1129
- **WARN**: 94593
## By Class
| Class | ERROR | WARN |
|-------|-------|------|
| org.apache.jackrabbit.vault.fs.io.ImportOptions | 0 | 40217 |
| com.adobe.cq.updateprocessor.impl.ProcessorUtils | 0 | 29617 |
| GET | 1099 | 15097 |
| com.adobe.granite.workflow.core.WorkflowSessionImpl | 0 | 5508 |
| com.adobe.cq.dam.cfm.graphql.ModelManagerImpl | 0 | 3357 |
| org.apache.felix.webconsole | 0 | 288 |
| org.apache.felix.hc.core.impl.executor.HealthCheckExecutorImpl | 0 | 123 |
| org.apache.felix.configadmin.plugin.interpolation.InterpolationConfigurationPlugin | 0 | 81 |
| com.adobe.granite.ims.yamlloader.ImsYamlLoader | 0 | 36 |
| com.adobe.cq.dam.assethandler.internal.events.consumer.impl.AssetBatchDeliveryConsumerImpl | 0 | 27 |
| com.adobe.granite.repository.impl.SystemPrincipalsValidation | 0 | 27 |
| com.adobe.granite.probes.impl.K8SProbes | 0 | 18 |
| com.day.cq.commons.impl.PredicateProviderImpl | 0 | 18 |
| org.apache.sling.resourceresolver.impl.VanityPathConfigurer | 0 | 18 |
| com.day.cq.dam.handler.gibson.fontmanager.impl.FontManagerServiceImpl | 0 | 18 |
| com.adobe.cq.wcm.translation.impl.utils.I18nUtils | 0 | 18 |
| org.apache.jackrabbit.oak.plugins.index.lucene.IndexCopier | 0 | 16 |
| com.adobe.granite.maintenance.impl.MaintenanceTaskInfoImpl | 0 | 16 |
| com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | 12 | 0 |
| com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | 12 | 0 |
| com.azure.core.http.netty.implementation.Utility | 0 | 9 |
| org.apache.jackrabbit.oak.plugins.index.elastic.query.inference.InferenceIndexConfig | 0 | 9 |
| org.apache.jackrabbit.oak.jcr.lock.LockDeprecation | 0 | 9 |
| com.day.cq.commons.servlets.AbstractListServlet | 0 | 9 |
| com.adobe.granite.workflow.console.generate.WorkflowModelGeneratorImpl | 0 | 9 |
| com.day.crx.sling.server.impl.jmx.SecureContentRepositoryAccess | 0 | 7 |
| io.prometheus.client.dropwizard.DropwizardExports | 0 | 6 |
| org.apache.jackrabbit.oak.plugins.index.lucene.directory.CopyOnReadDirectory | 0 | 5 |
| Events.Framework.com.adobe.cq.dam.cq-dam-processor-nui | 3 | 0 |
| org.apache.sling.commons.scheduler.impl.QuartzScheduler | 2 | 0 |
| org.apache.jackrabbit.oak.plugins.index.AsyncCheckpointCreator | 0 | 2 |
| org.apache.jackrabbit.oak.plugins.index.lucene.directory.IndexSanityChecker | 0 | 2 |
| ROOT | 1 | 0 |
| [5f859aca-58c1-4f41-bb07-298dd3741ae4] | 0 | 1 |
| [12fbfddb-cdba-49dd-b99f-a41d61beeaca] | 0 | 1 |
| com.adobe.granite.queries.impl.hc.QueryLimitsHealthCheck | 0 | 1 |
| com.adobe.cq.assetcompute.impl.smartcrop.CreateCropAssetComputeService | 0 | 1 |
| com.adobe.cq.assetcompute.impl.smartcrop.CreateCropAssetComputeEventHandler | 0 | 1 |
| com.adobe.cq.assetcompute.impl.connection.ConnectionServiceImpl | 0 | 1 |
| [2ffe37ce-98b3-4fc9-ac4f-5bb8b6b1a5f4] | 0 | 1 |
| [7210e19f-2576-48d1-87c9-fe00db5742e0] | 0 | 1 |
| LogService.org.apache.felix.eventadmin | 0 | 1 |
| [4f32e3d4-77e5-4206-b25b-850096a32e99] | 0 | 1 |
| [c127ff31-7eea-4458-baf2-896079221b75] | 0 | 1 |
| [c6f82823-3bef-460d-968e-498920e2eef0] | 0 | 1 |
| [066609a9-cb3c-4848-8544-7839487e1360] | 0 | 1 |
| [0ae8b6e8-76d5-46cd-b2a6-695a90b6a17f] | 0 | 1 |
| [6f98e61f-014c-470a-a7cc-8dce6a9cc686] | 0 | 1 |
| [17dcefa1-123d-4627-879d-d8d28c69d616] | 0 | 1 |
| [28fc54a0-1126-4583-86a1-d49721723560] | 0 | 1 |
| [c0ea5a64-378e-4654-a6d5-8025ad5dc3a1] | 0 | 1 |
| [40b557d2-f816-4764-8203-06d2c3fcc6d2] | 0 | 1 |
| [ea7773b9-621d-4654-9c23-94180e44cd12] | 0 | 1 |
| [297ee30e-c179-40e8-ae5f-bea19b914aa7] | 0 | 1 |
| [b445b2df-a993-4175-ac45-e1d9d7ac809a] | 0 | 1 |
| [ca0f1d87-44b0-422b-9749-91338479ace7] | 0 | 1 |
| [f5f9f0c6-a7b1-48ba-b1f5-68cb5fbf311a] | 0 | 1 |
| [04fb2b90-e41e-4dae-a17e-1730fa4cced1] | 0 | 1 |
| [6b1a064f-2432-4d73-88d0-6272539d478e] | 0 | 1 |

## Recent Errors (sample)
| Date | Time | Class | Message |
|------|------|-------|--------|
| 17.04.2026 | 00:00:00.075 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [672] |
| 17.04.2026 | 00:00:00.075 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 17.04.2026 | 00:00:00.090 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 17.04.2026 | 00:00:00.090 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [672] |
| 17.04.2026 | 00:00:00.106 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [672] |
| 17.04.2026 | 00:00:00.108 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 17.04.2026 | 00:00:00.108 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [672] |
| 17.04.2026 | 00:00:00.108 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 17.04.2026 | 00:00:00.118 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 17.04.2026 | 00:00:00.118 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [672] |
| 17.04.2026 | 00:00:00.131 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [672] |
| 17.04.2026 | 00:00:00.132 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 17.04.2026 | 00:00:31.921 | GET | /graphql/execute.json/realmadridmastersite/news-section-detail-assembly%3bpath=%252Fcontent%252Fdam% |
| 17.04.2026 | 00:00:53.666 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 17.04.2026 | 00:00:53.705 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 17.04.2026 | 00:00:53.747 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 17.04.2026 | 00:01:40.835 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 17.04.2026 | 00:01:40.848 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 17.04.2026 | 00:01:40.971 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 17.04.2026 | 00:01:40.988 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 17.04.2026 | 00:01:41.014 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 17.04.2026 | 00:01:41.033 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 17.04.2026 | 00:02:23.269 | GET | /content/dam/portals/realmadrid-com/ar-ae/core-content/assemblies/pages/generic-pages/el-club/junta- |
| 17.04.2026 | 00:02:23.332 | GET | /content/dam/portals/realmadrid-com/ar-ae/core-content/assemblies/pages/generic-pages/el-club/junta- |
| 17.04.2026 | 00:02:23.361 | GET | /content/dam/portals/realmadrid-com/ar-ae/core-content/assemblies/pages/generic-pages/el-club/junta- |
| 17.04.2026 | 00:02:41.840 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 17.04.2026 | 00:02:41.880 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 17.04.2026 | 00:02:41.924 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 17.04.2026 | 00:03:45.124 | GET | /graphql/execute.json/realmadridmastersite/news-section-detail-assembly%3bpath=%252Fcontent%252Fdam% |
| 17.04.2026 | 00:06:03.063 | GET | /content/dam/portals/realmadrid-com/fr-fr/news/generic/2026/01/27/videos/230126%20S7%20WEB%20ESTADIO |
| 17.04.2026 | 00:08:29.870 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 17.04.2026 | 00:08:29.907 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 17.04.2026 | 00:08:29.949 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 17.04.2026 | 00:10:14.147 | GET | /graphql/execute.json/realmadridmastersite/news-section-detail-assembly%3bpath=%252Fcontent%252Fdam% |
| 17.04.2026 | 00:10:36.840 | org.apache.sling.commons.scheduler.impl.QuartzScheduler | Exception during job execution of job 'org.apache.jackrabbit.oak.plugins.index.lucene.directory.Luce |
| 17.04.2026 | 00:11:54.741 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 17.04.2026 | 00:11:54.754 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 17.04.2026 | 00:11:54.889 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 17.04.2026 | 00:11:54.901 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 17.04.2026 | 00:11:54.931 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 17.04.2026 | 00:11:54.941 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 17.04.2026 | 00:12:54.885 | GET | /graphql/execute.json/realmadridmastersite/news-section-detail-assembly%3bpath=/content/dam/portals/ |
| 17.04.2026 | 00:13:07.809 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 17.04.2026 | 00:13:07.819 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 17.04.2026 | 00:13:07.855 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 17.04.2026 | 00:13:07.864 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 17.04.2026 | 00:13:07.897 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 17.04.2026 | 00:13:07.907 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 17.04.2026 | 00:14:57.223 | GET | /graphql/execute.json/realmadridmastersite/news-section-detail-assembly%3bpath=%252Fcontent%252Fdam% |
| 17.04.2026 | 00:22:05.480 | GET | /graphql/execute.json/realmadridmastersite/news-section-detail-assembly%3bpath=%252Fcontent%252Fdam% |

## Recent Warnings (sample)
| Date | Time | Class | Message |
|------|------|-------|--------|
| 17.04.2026 | 00:00:01.883 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.search.impl.builder.Roo |
| 17.04.2026 | 00:00:01.884 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.search.impl.builder.Roo |
| 17.04.2026 | 00:00:01.885 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.search.impl.builder.Roo |
| 17.04.2026 | 00:00:02.102 | GET | /graphql/execute.json/areavip/eventList%3bfromDate=2026-04-17T00:00%3btoDate=2027-04-17T00:00%3b.jso |
| 17.04.2026 | 00:00:02.118 | GET | /graphql/execute.json/areavip/eventList%3bfromDate=2026-04-17T00:00%3btoDate=2027-04-17T00:00%3b.jso |
| 17.04.2026 | 00:00:05.360 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.tagging.impl.JcrTagImpl |
| 17.04.2026 | 00:00:05.360 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.tagging.impl.JcrTagImpl |
| 17.04.2026 | 00:00:05.360 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.tagging.impl.JcrTagImpl |
| 17.04.2026 | 00:00:05.361 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.tagging.impl.JcrTagImpl |
| 17.04.2026 | 00:00:05.361 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.tagging.impl.JcrTagImpl |
| 17.04.2026 | 00:00:05.361 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.tagging.impl.JcrTagImpl |
| 17.04.2026 | 00:00:05.362 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.tagging.impl.JcrTagImpl |
| 17.04.2026 | 00:00:05.362 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.tagging.impl.JcrTagImpl |
| 17.04.2026 | 00:00:05.362 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.tagging.impl.JcrTagImpl |
| 17.04.2026 | 00:00:05.363 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.tagging.impl.JcrTagImpl |
| 17.04.2026 | 00:00:05.363 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.tagging.impl.JcrTagImpl |
| 17.04.2026 | 00:00:05.363 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.tagging.impl.JcrTagImpl |
| 17.04.2026 | 00:00:07.080 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 17.04.2026 | 00:00:07.084 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 17.04.2026 | 00:00:07.086 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 17.04.2026 | 00:00:07.091 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 17.04.2026 | 00:00:07.109 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 17.04.2026 | 00:00:07.252 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 17.04.2026 | 00:00:07.739 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 17.04.2026 | 00:00:07.742 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 17.04.2026 | 00:00:07.745 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 17.04.2026 | 00:00:07.747 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 17.04.2026 | 00:00:07.749 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 17.04.2026 | 00:00:07.838 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 17.04.2026 | 00:00:08.242 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 17.04.2026 | 00:00:08.246 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 17.04.2026 | 00:00:08.252 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 17.04.2026 | 00:00:08.340 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 17.04.2026 | 00:00:08.345 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 17.04.2026 | 00:00:08.459 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 17.04.2026 | 00:00:08.615 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 796ms to become available through index. |
| 17.04.2026 | 00:00:08.654 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 784ms to become available through index. |
| 17.04.2026 | 00:00:08.663 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 808ms to become available through index. |
| 17.04.2026 | 00:00:08.676 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 817ms to become available through index. |
| 17.04.2026 | 00:00:08.686 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 816ms to become available through index. |
| 17.04.2026 | 00:00:08.724 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 802ms to become available through index. |
| 17.04.2026 | 00:00:08.967 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 17.04.2026 | 00:00:08.972 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 17.04.2026 | 00:00:08.974 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 17.04.2026 | 00:00:08.975 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 17.04.2026 | 00:00:08.975 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 17.04.2026 | 00:00:09.007 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 17.04.2026 | 00:00:09.234 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 17.04.2026 | 00:00:09.234 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 17.04.2026 | 00:00:09.237 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
