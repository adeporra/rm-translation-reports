# AEM PROD Publish Error Report — 2026-04-26
Report date: 2026-04-26
Generated from aemerror.log — general error validation.
## Summary
- **ERROR**: 841
- **WARN**: 99799
## By Class
| Class | ERROR | WARN |
|-------|-------|------|
| org.apache.jackrabbit.vault.fs.io.ImportOptions | 0 | 43873 |
| com.adobe.cq.updateprocessor.impl.ProcessorUtils | 0 | 31851 |
| GET | 804 | 14785 |
| com.adobe.granite.workflow.core.WorkflowSessionImpl | 0 | 5616 |
| com.adobe.cq.dam.cfm.graphql.ModelManagerImpl | 0 | 2977 |
| org.apache.felix.webconsole | 0 | 256 |
| org.apache.felix.hc.core.impl.executor.HealthCheckExecutorImpl | 0 | 100 |
| org.apache.felix.configadmin.plugin.interpolation.InterpolationConfigurationPlugin | 0 | 72 |
| com.adobe.granite.ims.yamlloader.ImsYamlLoader | 0 | 32 |
| com.adobe.cq.dam.assethandler.internal.events.consumer.impl.AssetBatchDeliveryConsumerImpl | 0 | 24 |
| com.adobe.granite.repository.impl.SystemPrincipalsValidation | 0 | 24 |
| com.adobe.granite.probes.impl.K8SProbes | 0 | 16 |
| com.day.cq.commons.impl.PredicateProviderImpl | 0 | 16 |
| org.apache.sling.resourceresolver.impl.VanityPathConfigurer | 0 | 16 |
| com.day.cq.dam.handler.gibson.fontmanager.impl.FontManagerServiceImpl | 0 | 16 |
| com.adobe.cq.wcm.translation.impl.utils.I18nUtils | 0 | 16 |
| com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | 12 | 0 |
| com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | 12 | 0 |
| com.adobe.granite.maintenance.impl.MaintenanceTaskInfoImpl | 0 | 11 |
| com.azure.core.http.netty.implementation.Utility | 0 | 8 |
| org.apache.jackrabbit.oak.plugins.index.elastic.query.inference.InferenceIndexConfig | 0 | 8 |
| com.adobe.granite.ims.client.config.ExpiryChecker | 0 | 8 |
| org.apache.jackrabbit.oak.jcr.lock.LockDeprecation | 0 | 8 |
| com.day.cq.commons.servlets.AbstractListServlet | 0 | 8 |
| com.adobe.granite.workflow.console.generate.WorkflowModelGeneratorImpl | 0 | 8 |
| io.prometheus.client.dropwizard.DropwizardExports | 0 | 8 |
| com.day.crx.sling.server.impl.jmx.SecureContentRepositoryAccess | 0 | 7 |
| LogService.org.apache.felix.eventadmin | 4 | 2 |
| com.day.cq.audit.impl.AuditLogMaintenanceTask | 0 | 6 |
| org.apache.sling.commons.scheduler.impl.QuartzScheduler | 3 | 0 |
| Events.Framework.com.adobe.cq.dam.cq-dam-processor-nui | 3 | 0 |
| org.apache.jackrabbit.oak.plugins.index.lucene.directory.CopyOnReadDirectory | 0 | 2 |
| org.apache.jackrabbit.oak.plugins.index.lucene.IndexCopier | 0 | 2 |
| [430b79a2-5630-4d60-b8ba-e316c4b113e9] | 0 | 2 |
| [c898292e-7229-459e-9f98-d204ee6a570b] | 1 | 0 |
| Events.Framework.org.apache.felix.log | 1 | 0 |
| ROOT | 1 | 0 |
| [a5fd2c65-98d2-4047-a40f-c321e35b5328] | 0 | 1 |
| [0419bd70-9f38-42ba-963d-8e84ad879e50] | 0 | 1 |
| [634effee-ae38-414c-b725-5f0415799b92] | 0 | 1 |
| [df1b620f-4ccd-481b-9df8-04b938ad1fdf] | 0 | 1 |
| [9a7dd652-2fd6-4da8-9ba1-fcc046cc1bd4] | 0 | 1 |
| [d3b85db1-7511-43cc-8721-9db9a3b6e096] | 0 | 1 |
| [86042950-8814-40dd-8038-7424a86595ac] | 0 | 1 |
| com.adobe.cq.assetcompute.impl.smartcrop.CreateCropAssetComputeService | 0 | 1 |
| com.adobe.cq.assetcompute.impl.smartcrop.CreateCropAssetComputeEventHandler | 0 | 1 |
| com.adobe.cq.assetcompute.impl.connection.ConnectionServiceImpl | 0 | 1 |
| [091d3a85-640c-4929-8d34-2bf2a9dcc65c] | 0 | 1 |
| [644a816b-1a21-49ec-9845-7b108c8b432f] | 0 | 1 |
| [a8275afc-c5bc-4fe1-bb4e-fec015717f1e] | 0 | 1 |
| [fd256d97-4847-4a3d-b0c8-e5da4cd395db] | 0 | 1 |
| [c52b93ae-8011-4052-a198-84648dcbf2e6] | 0 | 1 |
| [3e793341-ce57-405a-8214-7743017ff070] | 0 | 1 |
| [8c7ccb3a-022f-407b-be24-4931a72cf5d4] | 0 | 1 |
| [687476bf-b0f9-4f42-85f9-5f6a2a2228b4] | 0 | 1 |
| [041f2a35-d793-4dc7-af1e-24ed17cc3aac] | 0 | 1 |
| [6e3c0064-4a40-4402-99c0-9a78508808be] | 0 | 1 |
| [b92d98ae-3720-43b3-bc4a-d1432f432127] | 0 | 1 |

## Recent Errors (sample)
| Date | Time | Class | Message |
|------|------|-------|--------|
| 27.04.2026 | 00:00:00.059 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [672] |
| 27.04.2026 | 00:00:00.059 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 27.04.2026 | 00:00:00.095 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [672] |
| 27.04.2026 | 00:00:00.095 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 27.04.2026 | 00:00:00.115 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 27.04.2026 | 00:00:00.115 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [672] |
| 27.04.2026 | 00:00:00.115 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 27.04.2026 | 00:00:00.115 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [672] |
| 27.04.2026 | 00:00:00.131 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 27.04.2026 | 00:00:00.131 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [672] |
| 27.04.2026 | 00:00:00.144 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [672] |
| 27.04.2026 | 00:00:00.144 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 27.04.2026 | 00:00:08.527 | GET | /graphql/execute.json/realmadridmastersite/diaryV2;fromDate=2026-04-27T00:00:00.000Z;toDate=2026-07- |
| 27.04.2026 | 00:01:06.328 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 27.04.2026 | 00:01:06.365 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 27.04.2026 | 00:01:06.408 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 27.04.2026 | 00:02:04.241 | GET | /graphql/execute.json/realmadridmastersite/diaryV2;fromDate=2026-04-27T00:00:00.000Z;toDate=2026-07- |
| 27.04.2026 | 00:02:30.779 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 27.04.2026 | 00:02:30.824 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 27.04.2026 | 00:02:30.868 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 27.04.2026 | 00:07:13.309 | GET | /content/dam/portals/realmadrid-com/ar-ae/news/generic/2026/03/27/videos/270326%20S7%20WEB%20TCHOUAM |
| 27.04.2026 | 00:08:39.743 | org.apache.sling.commons.scheduler.impl.QuartzScheduler | Exception during job execution of job 'org.apache.jackrabbit.oak.plugins.index.lucene.directory.Luce |
| 27.04.2026 | 00:15:58.621 | [c898292e-7229-459e-9f98-d204ee6a570b] | GET /adobe/dynamicmedia/deliver/dm-aid--16e9a501-8aa7-470f-9d4e-cbf6c8fdd95b/ND_ENTRENAMIENTO_03_AV2 |
| 27.04.2026 | 00:17:05.887 | GET | /content/sling/app-servlets/realmadrid/rssfeedv2.en-us.xml.xml HTTP/1.1] com.realmadridclubdefutbol. |
| 27.04.2026 | 00:20:30.600 | GET | /content/dam/portals/realmadrid-com/fr-fr/news/generic/2026/03/28/videos/240326%20S7%20WEB%20CALENDA |
| 27.04.2026 | 00:22:03.496 | GET | /graphql/execute.json/realmadridmastersite/diaryV2;fromDate=2026-04-27T00:00:00.000Z;toDate=2026-07- |
| 27.04.2026 | 00:30:16.281 | LogService.org.apache.felix.eventadmin | Service [com.adobe.cq.updateprocessor.impl.ReplicationListener,5014, [org.osgi.service.event.EventHa |
| 27.04.2026 | 00:30:16.282 | LogService.org.apache.felix.eventadmin | Service [com.adobe.cq.updateprocessor.impl.ReplicationListener,5014, [org.osgi.service.event.EventHa |
| 27.04.2026 | 00:30:16.282 | LogService.org.apache.felix.eventadmin | Service [com.adobe.cq.updateprocessor.impl.ReplicationListener,5014, [org.osgi.service.event.EventHa |
| 27.04.2026 | 00:30:58.827 | GET | /content/dam/portals/realmadrid-com/ja-jp/news/generic/2026/03/01/(cas)-castilla-ponferradina-j26-1r |
| 27.04.2026 | 00:37:29.243 | GET | /content/dam/portals/realmadrid-com/es-es/core-content/assemblies/pages/generic-pages/madridistas/ve |
| 27.04.2026 | 00:37:29.252 | GET | /content/dam/portals/realmadrid-com/es-es/core-content/assemblies/pages/generic-pages/madridistas/ve |
| 27.04.2026 | 00:37:29.256 | GET | /content/dam/portals/realmadrid-com/es-es/core-content/assemblies/pages/generic-pages/madridistas/ve |
| 27.04.2026 | 00:37:29.269 | GET | /content/dam/portals/realmadrid-com/es-es/core-content/assemblies/pages/generic-pages/madridistas/ve |
| 27.04.2026 | 00:37:29.278 | GET | /content/dam/portals/realmadrid-com/es-es/core-content/assemblies/pages/generic-pages/madridistas/ve |
| 27.04.2026 | 00:37:29.293 | GET | /content/dam/portals/realmadrid-com/es-es/core-content/assemblies/pages/generic-pages/madridistas/ve |
| 27.04.2026 | 00:37:29.296 | GET | /content/dam/portals/realmadrid-com/es-es/core-content/assemblies/pages/generic-pages/madridistas/ve |
| 27.04.2026 | 00:37:29.305 | GET | /content/dam/portals/realmadrid-com/es-es/core-content/assemblies/pages/generic-pages/madridistas/ve |
| 27.04.2026 | 00:37:29.317 | GET | /content/dam/portals/realmadrid-com/es-es/core-content/assemblies/pages/generic-pages/madridistas/ve |
| 27.04.2026 | 00:37:29.326 | GET | /content/dam/portals/realmadrid-com/es-es/core-content/assemblies/pages/generic-pages/madridistas/ve |
| 27.04.2026 | 00:37:29.346 | GET | /content/dam/portals/realmadrid-com/es-es/core-content/assemblies/pages/generic-pages/madridistas/ve |
| 27.04.2026 | 00:37:29.370 | GET | /content/dam/portals/realmadrid-com/es-es/core-content/assemblies/pages/generic-pages/madridistas/ve |
| 27.04.2026 | 00:37:47.650 | GET | /content/dam/portals/realmadrid-com/es-es/core-content/assemblies/pages/generic-pages/madridistas/ve |
| 27.04.2026 | 00:37:47.672 | GET | /content/dam/portals/realmadrid-com/es-es/core-content/assemblies/pages/generic-pages/madridistas/ve |
| 27.04.2026 | 00:37:47.674 | GET | /content/dam/portals/realmadrid-com/es-es/core-content/assemblies/pages/generic-pages/madridistas/ve |
| 27.04.2026 | 00:37:47.692 | GET | /content/dam/portals/realmadrid-com/es-es/core-content/assemblies/pages/generic-pages/madridistas/ve |
| 27.04.2026 | 00:37:47.694 | GET | /content/dam/portals/realmadrid-com/es-es/core-content/assemblies/pages/generic-pages/madridistas/ve |
| 27.04.2026 | 00:37:47.712 | GET | /content/dam/portals/realmadrid-com/es-es/core-content/assemblies/pages/generic-pages/madridistas/ve |
| 27.04.2026 | 00:37:47.731 | GET | /content/dam/portals/realmadrid-com/es-es/core-content/assemblies/pages/generic-pages/madridistas/ve |
| 27.04.2026 | 00:37:47.749 | GET | /content/dam/portals/realmadrid-com/es-es/core-content/assemblies/pages/generic-pages/madridistas/ve |

## Recent Warnings (sample)
| Date | Time | Class | Message |
|------|------|-------|--------|
| 27.04.2026 | 00:00:06.933 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 27.04.2026 | 00:00:06.936 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 27.04.2026 | 00:00:06.939 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 27.04.2026 | 00:00:06.939 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 27.04.2026 | 00:00:06.943 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 27.04.2026 | 00:00:06.945 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 27.04.2026 | 00:00:07.116 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 27.04.2026 | 00:00:07.121 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 27.04.2026 | 00:00:07.147 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 27.04.2026 | 00:00:07.148 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 27.04.2026 | 00:00:07.158 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 27.04.2026 | 00:00:07.161 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 27.04.2026 | 00:00:07.547 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 27.04.2026 | 00:00:07.547 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 27.04.2026 | 00:00:07.548 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 27.04.2026 | 00:00:07.548 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 27.04.2026 | 00:00:07.548 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 27.04.2026 | 00:00:07.549 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 27.04.2026 | 00:00:07.703 | GET | /graphql/execute.json/areavip/eventList%3bfromDate=2026-04-27T00:00%3btoDate=2027-04-27T00:00%3b.jso |
| 27.04.2026 | 00:00:07.713 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 27.04.2026 | 00:00:07.725 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 27.04.2026 | 00:00:07.740 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 27.04.2026 | 00:00:07.742 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 27.04.2026 | 00:00:07.747 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 27.04.2026 | 00:00:07.761 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 27.04.2026 | 00:00:07.881 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 27.04.2026 | 00:00:07.886 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 27.04.2026 | 00:00:07.903 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 27.04.2026 | 00:00:07.931 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 27.04.2026 | 00:00:07.933 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 27.04.2026 | 00:00:07.951 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 27.04.2026 | 00:00:08.101 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 27.04.2026 | 00:00:08.104 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 27.04.2026 | 00:00:08.104 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 27.04.2026 | 00:00:08.116 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 27.04.2026 | 00:00:08.124 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 27.04.2026 | 00:00:08.140 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 27.04.2026 | 00:00:08.301 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 27.04.2026 | 00:00:08.305 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 27.04.2026 | 00:00:08.306 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 27.04.2026 | 00:00:08.309 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 27.04.2026 | 00:00:08.319 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 27.04.2026 | 00:00:08.329 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 27.04.2026 | 00:00:08.576 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 27.04.2026 | 00:00:08.576 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 27.04.2026 | 00:00:08.577 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 27.04.2026 | 00:00:08.577 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 27.04.2026 | 00:00:08.578 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 27.04.2026 | 00:00:08.585 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 27.04.2026 | 00:00:08.780 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1569ms to become available through index. |
