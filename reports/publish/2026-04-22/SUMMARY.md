# AEM PROD Publish Error Report — 2026-04-22
Report date: 2026-04-22
Generated from aemerror.log — general error validation.
## Summary
- **ERROR**: 729
- **WARN**: 90537
## By Class
| Class | ERROR | WARN |
|-------|-------|------|
| org.apache.jackrabbit.vault.fs.io.ImportOptions | 0 | 40276 |
| com.adobe.cq.updateprocessor.impl.ProcessorUtils | 0 | 27822 |
| GET | 677 | 13088 |
| com.adobe.granite.workflow.core.WorkflowSessionImpl | 0 | 5614 |
| com.adobe.cq.dam.cfm.graphql.ModelManagerImpl | 0 | 2977 |
| org.apache.felix.webconsole | 0 | 256 |
| org.apache.felix.hc.core.impl.executor.HealthCheckExecutorImpl | 0 | 127 |
| org.apache.felix.configadmin.plugin.interpolation.InterpolationConfigurationPlugin | 0 | 72 |
| com.adobe.granite.ims.yamlloader.ImsYamlLoader | 0 | 32 |
| com.adobe.cq.dam.assethandler.internal.events.consumer.impl.AssetBatchDeliveryConsumerImpl | 0 | 24 |
| com.adobe.granite.repository.impl.SystemPrincipalsValidation | 0 | 24 |
| io.prometheus.client.dropwizard.DropwizardExports | 0 | 23 |
| com.adobe.granite.probes.impl.K8SProbes | 0 | 16 |
| org.apache.sling.resourceresolver.impl.VanityPathConfigurer | 0 | 16 |
| com.day.cq.dam.handler.gibson.fontmanager.impl.FontManagerServiceImpl | 0 | 16 |
| com.day.cq.commons.impl.PredicateProviderImpl | 0 | 16 |
| com.adobe.cq.wcm.translation.impl.utils.I18nUtils | 0 | 16 |
| com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | 12 | 0 |
| com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | 12 | 0 |
| com.adobe.granite.maintenance.impl.MaintenanceTaskInfoImpl | 0 | 12 |
| LogService.org.apache.felix.eventadmin | 10 | 0 |
| org.apache.sling.commons.scheduler.impl.QuartzScheduler | 8 | 0 |
| com.azure.core.http.netty.implementation.Utility | 0 | 8 |
| org.apache.jackrabbit.oak.plugins.index.elastic.query.inference.InferenceIndexConfig | 0 | 8 |
| com.adobe.granite.ims.client.config.ExpiryChecker | 0 | 8 |
| org.apache.jackrabbit.oak.jcr.lock.LockDeprecation | 0 | 8 |
| com.adobe.granite.workflow.console.generate.WorkflowModelGeneratorImpl | 0 | 8 |
| com.day.cq.commons.servlets.AbstractListServlet | 0 | 8 |
| org.apache.jackrabbit.oak.plugins.index.lucene.IndexCopier | 0 | 7 |
| org.apache.jackrabbit.oak.plugins.index.lucene.directory.CopyOnReadDirectory | 0 | 7 |
| com.day.crx.sling.server.impl.jmx.SecureContentRepositoryAccess | 0 | 7 |
| Events.Framework.com.adobe.cq.dam.cq-dam-processor-nui | 6 | 0 |
| org.apache.jackrabbit.oak.plugins.index.lucene.directory.IndexSanityChecker | 0 | 4 |
| Events.Framework.org.apache.felix.log | 2 | 0 |
| ROOT | 2 | 0 |
| com.adobe.cq.assetcompute.impl.connection.ConnectionServiceImpl | 0 | 2 |
| [cfb41912-24e6-4438-8408-a82d3423c9cf] | 0 | 1 |
| [1097aa57-faa0-4000-af56-bb858cc1f9fa] | 0 | 1 |
| [cdf32c25-223c-4f0e-9e1b-5cdc29b9000a] | 0 | 1 |
| com.adobe.cq.assetcompute.impl.assetprocessor.AssetAiRenditionProcessingService | 0 | 1 |
| com.adobe.cq.assetcompute.impl.assetprocessor.AssetProcessorEventHandler | 0 | 1 |
| com.adobe.cq.assetcompute.impl.smartcrop.CreateCropAssetComputeService | 0 | 1 |
| com.adobe.cq.assetcompute.impl.smartcrop.CreateCropAssetComputeEventHandler | 0 | 1 |
| [e364c610-d889-4633-8c46-8f0702c5619c] | 0 | 1 |
| [b3fa2837-91fc-4ab2-849c-0876362722b5] | 0 | 1 |
| [6cf996a5-f6fa-4c35-a3c3-da2dd0a9e22b] | 0 | 1 |
| [8c3fca15-3bfe-4f29-a679-4794d1985bf6] | 0 | 1 |
| [6288d258-33c0-4f35-a3b3-5b52ab6d2fa0] | 0 | 1 |
| [bb2352bf-f80b-4656-b9a6-2eb7121efa84] | 0 | 1 |
| [65bd6ad2-53c5-40d4-8883-bd0546c68ef8] | 0 | 1 |
| [9808dd82-693c-49ec-bf39-2566ba74977f] | 0 | 1 |
| [02ac0f1a-ab12-45ab-9a3a-242eb82a212f] | 0 | 1 |
| [35c857db-5a87-4427-aad8-bdd9237cb254] | 0 | 1 |
| [511c9bc4-ddf4-47ce-842f-5b54befb718a] | 0 | 1 |
| [048053b3-24b3-4490-860f-4d0c922de32b] | 0 | 1 |
| [f0bb5ab5-76b8-4340-960e-9a0f8a14b9c1] | 0 | 1 |
| [e7e55686-d6b4-49f7-80af-e360396eaad1] | 0 | 1 |
| [b8f245d8-7cf4-4601-bc8c-84842091ae0f] | 0 | 1 |
| [0ee0d4f4-8bb0-482c-ba83-d90b952739f1] | 0 | 1 |
| [4d637b45-bd1b-46db-951d-73c6f03a2d2c] | 0 | 1 |
| [05095b23-feac-4e99-9787-5c63c225497e] | 0 | 1 |
| [7fce95eb-1fab-4ce7-9474-e748f16c2d91] | 0 | 1 |
| [ff52c8e0-cf90-47cf-8045-adb677be40b4] | 0 | 1 |
| [ce102493-0126-4643-ad75-b9a3366ed955] | 0 | 1 |
| [237fe10c-4d66-47a2-b330-809f0cdede29] | 0 | 1 |
| [48614488-40a4-43cf-af3b-a51bc46d18d6] | 0 | 1 |
| [0a642e31-0678-4586-9b16-4a61aefc47e9] | 0 | 1 |
| [793c161d-b6b8-4ce2-8fc4-0f4019a997c6] | 0 | 1 |
| [93675a3f-a002-4c8e-86a1-e472f2d1e7a1] | 0 | 1 |
| [b4e1df3e-a8d8-4183-8b7a-394bd05e37d4] | 0 | 1 |
| [eb238cd9-379d-4bc6-b395-4777ec5cf4d0] | 0 | 1 |

## Recent Errors (sample)
| Date | Time | Class | Message |
|------|------|-------|--------|
| 23.04.2026 | 00:00:00.079 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 23.04.2026 | 00:00:00.079 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [672] |
| 23.04.2026 | 00:00:00.097 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 23.04.2026 | 00:00:00.097 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [672] |
| 23.04.2026 | 00:00:00.098 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [672] |
| 23.04.2026 | 00:00:00.098 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 23.04.2026 | 00:00:00.105 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [672] |
| 23.04.2026 | 00:00:00.105 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 23.04.2026 | 00:00:00.113 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [672] |
| 23.04.2026 | 00:00:00.115 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 23.04.2026 | 00:00:00.120 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 23.04.2026 | 00:00:00.120 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [672] |
| 23.04.2026 | 00:01:09.030 | GET | /graphql/execute.json/realmadridmastersite/diaryV2;fromDate=2026-04-23T00:00:00.000Z;toDate=2026-07- |
| 23.04.2026 | 00:02:39.141 | GET | /content/dam/portals/realmadrid-com/fr-fr/news/generic/2026/04/21/(fut)-rm-alaves-j33-liga/videos/21 |
| 23.04.2026 | 00:03:49.064 | GET | /content/dam/portals/realmadrid-com/en-us/news/generic/2026/04/21/(fut)-rm-alaves-j33-liga/videos/21 |
| 23.04.2026 | 00:06:41.886 | GET | /graphql/execute.json/realmadridmastersite/news-section-detail-assembly%3bpath=%252Fcontent%252Fdam% |
| 23.04.2026 | 00:06:44.811 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 23.04.2026 | 00:06:44.812 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.servlets.re |
| 23.04.2026 | 00:06:44.812 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.servlets.re |
| 23.04.2026 | 00:06:44.813 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 23.04.2026 | 00:06:44.813 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 23.04.2026 | 00:06:44.939 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 23.04.2026 | 00:06:44.941 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.servlets.re |
| 23.04.2026 | 00:06:44.941 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.servlets.re |
| 23.04.2026 | 00:06:44.942 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 23.04.2026 | 00:06:44.943 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 23.04.2026 | 00:06:45.042 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 23.04.2026 | 00:06:45.044 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.servlets.re |
| 23.04.2026 | 00:06:45.044 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.servlets.re |
| 23.04.2026 | 00:06:45.045 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 23.04.2026 | 00:06:45.045 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 23.04.2026 | 00:07:15.131 | org.apache.sling.commons.scheduler.impl.QuartzScheduler | Exception during job execution of job 'org.apache.jackrabbit.oak.plugins.index.lucene.directory.Luce |
| 23.04.2026 | 00:08:04.431 | org.apache.sling.commons.scheduler.impl.QuartzScheduler | Exception during job execution of job 'org.apache.jackrabbit.oak.plugins.index.lucene.directory.Luce |
| 23.04.2026 | 00:12:15.135 | org.apache.sling.commons.scheduler.impl.QuartzScheduler | Exception during job execution of job 'org.apache.jackrabbit.oak.plugins.index.lucene.directory.Luce |
| 23.04.2026 | 00:13:04.428 | org.apache.sling.commons.scheduler.impl.QuartzScheduler | Exception during job execution of job 'org.apache.jackrabbit.oak.plugins.index.lucene.directory.Luce |
| 23.04.2026 | 00:14:39.009 | org.apache.sling.commons.scheduler.impl.QuartzScheduler | Exception during job execution of job 'org.apache.jackrabbit.oak.plugins.index.lucene.directory.Luce |
| 23.04.2026 | 00:14:47.235 | GET | /content/dam/portals/realmadrid-com/pt-pt/news/generic/2026/04/15/videos/TOTALES%20CAMPAZZO%20PREVIA |
| 23.04.2026 | 00:17:20.112 | GET | /content/dam/portals/realmadrid-com/en-us/news/generic/2026/04/21/(fut)-rm-alaves-j33-liga/videos/21 |
| 23.04.2026 | 00:20:09.037 | GET | /content/dam/portals/realmadrid-com/es-es/core-content/assemblies/pages/generic-pages/madridistas/ve |
| 23.04.2026 | 00:20:09.038 | GET | /content/dam/portals/realmadrid-com/es-es/core-content/assemblies/pages/generic-pages/madridistas/ve |
| 23.04.2026 | 00:20:09.368 | GET | /content/dam/portals/realmadrid-com/es-es/core-content/assemblies/pages/generic-pages/madridistas/ve |
| 23.04.2026 | 00:20:09.374 | GET | /content/dam/portals/realmadrid-com/es-es/core-content/assemblies/pages/generic-pages/madridistas/ve |
| 23.04.2026 | 00:20:09.463 | GET | /content/dam/portals/realmadrid-com/es-es/core-content/assemblies/pages/generic-pages/madridistas/ve |
| 23.04.2026 | 00:20:09.470 | GET | /content/dam/portals/realmadrid-com/es-es/core-content/assemblies/pages/generic-pages/madridistas/ve |
| 23.04.2026 | 00:21:16.946 | GET | /content/dam/portals/realmadrid-com/es-es/core-content/assemblies/pages/generic-pages/madridistas/ve |
| 23.04.2026 | 00:21:16.947 | GET | /content/dam/portals/realmadrid-com/es-es/core-content/assemblies/pages/generic-pages/madridistas/ve |
| 23.04.2026 | 00:21:17.047 | GET | /content/dam/portals/realmadrid-com/es-es/core-content/assemblies/pages/generic-pages/madridistas/ve |
| 23.04.2026 | 00:21:17.054 | GET | /content/dam/portals/realmadrid-com/es-es/core-content/assemblies/pages/generic-pages/madridistas/ve |
| 23.04.2026 | 00:21:17.147 | GET | /content/dam/portals/realmadrid-com/es-es/core-content/assemblies/pages/generic-pages/madridistas/ve |
| 23.04.2026 | 00:21:17.156 | GET | /content/dam/portals/realmadrid-com/es-es/core-content/assemblies/pages/generic-pages/madridistas/ve |

## Recent Warnings (sample)
| Date | Time | Class | Message |
|------|------|-------|--------|
| 23.04.2026 | 00:00:00.171 | GET | /content/dam/portals/realmadrid-com/es-es/news/generic/2025/06/13/galerias/galeria-mastantuono/Getty |
| 23.04.2026 | 00:00:01.280 | GET | /graphql/execute.json/areavip/eventList%3bfromDate=2026-04-23T00:00%3btoDate=2027-04-23T00:00%3b.jso |
| 23.04.2026 | 00:00:01.569 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.tagging.impl.JcrTagImpl |
| 23.04.2026 | 00:00:11.348 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 23.04.2026 | 00:00:11.350 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 23.04.2026 | 00:00:11.357 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 23.04.2026 | 00:00:11.360 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 23.04.2026 | 00:00:11.360 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 23.04.2026 | 00:00:11.364 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 23.04.2026 | 00:00:11.852 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 23.04.2026 | 00:00:11.856 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 23.04.2026 | 00:00:11.856 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 23.04.2026 | 00:00:11.857 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 23.04.2026 | 00:00:11.860 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 23.04.2026 | 00:00:11.861 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 23.04.2026 | 00:00:12.363 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 23.04.2026 | 00:00:12.365 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 23.04.2026 | 00:00:12.367 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 23.04.2026 | 00:00:12.369 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 23.04.2026 | 00:00:12.370 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 23.04.2026 | 00:00:12.382 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 23.04.2026 | 00:00:12.697 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 23.04.2026 | 00:00:12.699 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 23.04.2026 | 00:00:12.702 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 23.04.2026 | 00:00:12.704 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 23.04.2026 | 00:00:12.705 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 23.04.2026 | 00:00:12.705 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 23.04.2026 | 00:00:12.735 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 777ms to become available through index. |
| 23.04.2026 | 00:00:12.748 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 809ms to become available through index. |
| 23.04.2026 | 00:00:12.750 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 777ms to become available through index. |
| 23.04.2026 | 00:00:12.756 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 781ms to become available through index. |
| 23.04.2026 | 00:00:12.773 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 812ms to become available through index. |
| 23.04.2026 | 00:00:13.107 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 23.04.2026 | 00:00:13.111 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 23.04.2026 | 00:00:13.111 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 23.04.2026 | 00:00:13.111 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 23.04.2026 | 00:00:13.114 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 23.04.2026 | 00:00:13.118 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 23.04.2026 | 00:00:13.502 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1575ms to become available through index. |
| 23.04.2026 | 00:00:13.768 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 23.04.2026 | 00:00:13.771 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 23.04.2026 | 00:00:13.773 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 23.04.2026 | 00:00:13.775 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 23.04.2026 | 00:00:13.778 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 23.04.2026 | 00:00:13.779 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 23.04.2026 | 00:00:14.008 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 23.04.2026 | 00:00:14.012 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 23.04.2026 | 00:00:14.012 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 23.04.2026 | 00:00:14.012 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 23.04.2026 | 00:00:14.014 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
