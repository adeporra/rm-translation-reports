# AEM PROD Publish Error Report — 2026-05-03
Report date: 2026-05-03
Generated from aemerror.log — general error validation.
## Summary
- **ERROR**: 1233
- **WARN**: 105289
## By Class
| Class | ERROR | WARN |
|-------|-------|------|
| org.apache.jackrabbit.vault.fs.io.ImportOptions | 0 | 44774 |
| com.adobe.cq.updateprocessor.impl.ProcessorUtils | 0 | 36519 |
| GET | 1196 | 15024 |
| com.adobe.granite.workflow.core.WorkflowSessionImpl | 0 | 5651 |
| com.adobe.cq.dam.cfm.graphql.ModelManagerImpl | 0 | 2647 |
| org.apache.felix.webconsole | 0 | 224 |
| org.apache.felix.hc.core.impl.executor.HealthCheckExecutorImpl | 0 | 100 |
| org.apache.felix.configadmin.plugin.interpolation.InterpolationConfigurationPlugin | 0 | 63 |
| com.adobe.granite.ims.yamlloader.ImsYamlLoader | 0 | 28 |
| com.adobe.cq.dam.assethandler.internal.events.consumer.impl.AssetBatchDeliveryConsumerImpl | 0 | 21 |
| com.adobe.granite.repository.impl.SystemPrincipalsValidation | 0 | 21 |
| io.prometheus.client.dropwizard.DropwizardExports | 0 | 20 |
| org.apache.jackrabbit.oak.plugins.index.lucene.IndexCopier | 0 | 20 |
| org.apache.jackrabbit.oak.plugins.index.lucene.directory.CopyOnReadDirectory | 0 | 15 |
| com.adobe.granite.probes.impl.K8SProbes | 0 | 14 |
| org.apache.sling.resourceresolver.impl.VanityPathConfigurer | 0 | 14 |
| com.day.cq.dam.handler.gibson.fontmanager.impl.FontManagerServiceImpl | 0 | 14 |
| com.day.cq.commons.impl.PredicateProviderImpl | 0 | 14 |
| com.adobe.cq.wcm.translation.impl.utils.I18nUtils | 0 | 14 |
| com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | 12 | 0 |
| com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | 12 | 0 |
| com.adobe.granite.maintenance.impl.MaintenanceTaskInfoImpl | 0 | 10 |
| org.apache.sling.commons.scheduler.impl.QuartzScheduler | 8 | 0 |
| com.azure.core.http.netty.implementation.Utility | 0 | 7 |
| org.apache.jackrabbit.oak.plugins.index.elastic.query.inference.InferenceIndexConfig | 0 | 7 |
| com.adobe.granite.ims.client.config.ExpiryChecker | 0 | 7 |
| com.adobe.granite.workflow.console.generate.WorkflowModelGeneratorImpl | 0 | 7 |
| org.apache.jackrabbit.oak.jcr.lock.LockDeprecation | 0 | 7 |
| com.day.cq.commons.servlets.AbstractListServlet | 0 | 7 |
| com.day.crx.sling.server.impl.jmx.SecureContentRepositoryAccess | 0 | 6 |
| com.day.cq.audit.impl.AuditLogMaintenanceTask | 0 | 6 |
| Events.Framework.org.apache.felix.log | 2 | 0 |
| com.adobe.granite.maintenance.impl.TaskScheduler | 2 | 0 |
| org.apache.jackrabbit.oak.plugins.index.AsyncCheckpointCreator | 0 | 2 |
| [7585c860-eca5-4340-a217-3fc9cd585f62] | 0 | 2 |
| [a44c051d-0e8b-4ce3-9e54-929e4a913e35] | 0 | 2 |
| [d33f4e08-c1b5-4403-b0ee-fb8f8aaf3848] | 1 | 0 |
| [4abbe623-93cb-4b03-9db0-0c579f33b9a6] | 0 | 1 |
| [59e6e16a-3e94-472d-93ce-b50f92f254bc] | 0 | 1 |
| [24936d6d-0570-49f6-b07e-759743bccc91] | 0 | 1 |
| [4c0c5a8e-b81f-437b-9f59-4084a93533bc] | 0 | 1 |
| [68740712-49f4-4335-8997-515d8d6a0c3b] | 0 | 1 |
| [57ec9187-786c-468b-bade-9b7fb045ea4d] | 0 | 1 |
| [064db716-38b5-49f0-bf6f-ab5ce22bf9f5] | 0 | 1 |
| [cb2a7a83-4ee6-4e92-8b97-15dbc2b87e0d] | 0 | 1 |
| LogService.org.apache.felix.eventadmin | 0 | 1 |
| [492769c3-e2e8-4b49-9a32-6dffd855f19f] | 0 | 1 |
| [185f9e1e-746d-4899-9068-6a33e381c747] | 0 | 1 |
| [7c3e5ad5-1a2d-4d4d-b932-62daf54bf43b] | 0 | 1 |
| [5f658b3e-d836-411b-b80c-28623f4301e9] | 0 | 1 |
| [c55e6314-6096-4f6e-99b7-38476fda7600] | 0 | 1 |
| [970f2abf-7511-49ce-878f-7ed8c16f3ce3] | 0 | 1 |
| [a46477f7-b5b2-47c6-ab36-4b5b54888188] | 0 | 1 |
| [7e6aceed-f82d-44e8-b2b0-447e3e4c073a] | 0 | 1 |
| [b1326804-77d0-4822-a120-f0a8d08db3d5] | 0 | 1 |
| [ea207a3f-648f-4f24-a7cb-24c7a06201e4] | 0 | 1 |
| [563fba66-e0a4-4407-8c3c-bf9d8b883ad0] | 0 | 1 |
| [fcc7a5cd-25f1-461c-9c47-22e98b741515] | 0 | 1 |
| POST | 0 | 1 |

## Recent Errors (sample)
| Date | Time | Class | Message |
|------|------|-------|--------|
| 04.05.2026 | 00:00:00.081 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [657] |
| 04.05.2026 | 00:00:00.082 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 04.05.2026 | 00:00:00.107 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [657] |
| 04.05.2026 | 00:00:00.108 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 04.05.2026 | 00:00:00.110 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 04.05.2026 | 00:00:00.110 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [657] |
| 04.05.2026 | 00:00:00.112 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 04.05.2026 | 00:00:00.112 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [657] |
| 04.05.2026 | 00:00:00.113 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [657] |
| 04.05.2026 | 00:00:00.114 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 04.05.2026 | 00:00:00.130 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 04.05.2026 | 00:00:00.130 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [657] |
| 04.05.2026 | 00:00:18.418 | GET | /graphql/execute.json/madridistas/madridistasLandingPlatinumByPath%3bpath=/content/dam/portals/madri |
| 04.05.2026 | 00:00:49.969 | GET | /graphql/execute.json/realmadridmastersite/diaryV2;fromDate=2026-05-04T00:00:00.000Z;toDate=2026-07- |
| 04.05.2026 | 00:03:19.648 | GET | /graphql/execute.json/madridistas/madridistasLandingPlatinumByPath%3bpath=/content/dam/portals/madri |
| 04.05.2026 | 00:04:19.888 | GET | /graphql/execute.json/madridistas/madridistasLandingPlatinumByPath%3bpath=/content/dam/portals/madri |
| 04.05.2026 | 00:04:39.410 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 04.05.2026 | 00:04:39.412 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.servlets.re |
| 04.05.2026 | 00:04:39.412 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.servlets.re |
| 04.05.2026 | 00:04:39.412 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 04.05.2026 | 00:04:39.413 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 04.05.2026 | 00:04:40.814 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 04.05.2026 | 00:04:40.816 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.servlets.re |
| 04.05.2026 | 00:04:40.816 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.servlets.re |
| 04.05.2026 | 00:04:40.817 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 04.05.2026 | 00:04:40.817 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 04.05.2026 | 00:04:42.010 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 04.05.2026 | 00:04:42.012 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.servlets.re |
| 04.05.2026 | 00:04:42.012 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.servlets.re |
| 04.05.2026 | 00:04:42.013 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 04.05.2026 | 00:04:42.013 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 04.05.2026 | 00:06:57.642 | GET | /graphql/execute.json/madridistas/madridistasLandingPlatinumByPath%3bpath=/content/dam/portals/madri |
| 04.05.2026 | 00:07:47.403 | GET | /content/dam/portals/realmadrid-com/es-es/core-content/assemblies/pages/generic-pages/madridistas/ve |
| 04.05.2026 | 00:07:47.540 | GET | /content/dam/portals/realmadrid-com/es-es/core-content/assemblies/pages/generic-pages/madridistas/ve |
| 04.05.2026 | 00:07:47.584 | GET | /content/dam/portals/realmadrid-com/es-es/core-content/assemblies/pages/generic-pages/madridistas/ve |
| 04.05.2026 | 00:07:47.587 | org.apache.sling.commons.scheduler.impl.QuartzScheduler | Exception during job execution of job 'org.apache.jackrabbit.oak.plugins.index.lucene.directory.Luce |
| 04.05.2026 | 00:07:51.926 | GET | /content/dam/portals/realmadrid-com/es-es/core-content/assemblies/pages/generic-pages/madridistas/ve |
| 04.05.2026 | 00:07:51.970 | GET | /content/dam/portals/realmadrid-com/es-es/core-content/assemblies/pages/generic-pages/madridistas/ve |
| 04.05.2026 | 00:07:52.014 | GET | /content/dam/portals/realmadrid-com/es-es/core-content/assemblies/pages/generic-pages/madridistas/ve |
| 04.05.2026 | 00:09:19.465 | GET | /graphql/execute.json/madridistas/madridistasLandingPlatinumByPath%3bpath=/content/dam/portals/madri |
| 04.05.2026 | 00:09:33.082 | GET | /graphql/execute.json/madridistas/madridistasLandingPlatinumByPath%3bpath=/content/dam/portals/madri |
| 04.05.2026 | 00:10:07.560 | org.apache.sling.commons.scheduler.impl.QuartzScheduler | Exception during job execution of job 'org.apache.jackrabbit.oak.plugins.index.lucene.directory.Luce |
| 04.05.2026 | 00:10:19.039 | GET | /graphql/execute.json/madridistas/madridistasLandingPlatinumByPath%3bpath=/content/dam/portals/madri |
| 04.05.2026 | 00:10:26.701 | GET | /content/dam/portals/realmadrid-com/es-es/core-content/assemblies/pages/generic-pages/madridistas/ve |
| 04.05.2026 | 00:10:26.937 | GET | /content/dam/portals/realmadrid-com/es-es/core-content/assemblies/pages/generic-pages/madridistas/ve |
| 04.05.2026 | 00:10:27.067 | GET | /content/dam/portals/realmadrid-com/es-es/core-content/assemblies/pages/generic-pages/madridistas/ve |
| 04.05.2026 | 00:10:27.192 | GET | /content/dam/portals/realmadrid-com/es-es/core-content/assemblies/pages/generic-pages/madridistas/ve |
| 04.05.2026 | 00:10:27.326 | GET | /content/dam/portals/realmadrid-com/es-es/core-content/assemblies/pages/generic-pages/madridistas/ve |
| 04.05.2026 | 00:10:27.417 | GET | /content/dam/portals/realmadrid-com/es-es/core-content/assemblies/pages/generic-pages/madridistas/ve |
| 04.05.2026 | 00:10:27.552 | GET | /content/dam/portals/realmadrid-com/es-es/core-content/assemblies/pages/generic-pages/madridistas/ve |

## Recent Warnings (sample)
| Date | Time | Class | Message |
|------|------|-------|--------|
| 04.05.2026 | 00:00:00.238 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1578ms to become available through index. |
| 04.05.2026 | 00:00:01.060 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 778ms to become available through index. |
| 04.05.2026 | 00:00:01.060 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1581ms to become available through index. |
| 04.05.2026 | 00:00:01.085 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1572ms to become available through index. |
| 04.05.2026 | 00:00:01.126 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1575ms to become available through index. |
| 04.05.2026 | 00:00:01.261 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1571ms to become available through index. |
| 04.05.2026 | 00:00:01.878 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 777ms to become available through index. |
| 04.05.2026 | 00:00:01.942 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 770ms to become available through index. |
| 04.05.2026 | 00:00:02.066 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 767ms to become available through index. |
| 04.05.2026 | 00:00:02.711 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1584ms to become available through index. |
| 04.05.2026 | 00:00:02.743 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 777ms to become available through index. |
| 04.05.2026 | 00:00:02.869 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 778ms to become available through index. |
| 04.05.2026 | 00:00:03.062 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1578ms to become available through index. |
| 04.05.2026 | 00:00:03.503 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1597ms to become available through index. |
| 04.05.2026 | 00:00:03.548 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 801ms to become available through index. |
| 04.05.2026 | 00:00:04.350 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1576ms to become available through index. |
| 04.05.2026 | 00:00:04.458 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1572ms to become available through index. |
| 04.05.2026 | 00:00:04.667 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1579ms to become available through index. |
| 04.05.2026 | 00:00:05.165 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1628ms to become available through index. |
| 04.05.2026 | 00:00:05.167 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1578ms to become available through index. |
| 04.05.2026 | 00:00:05.950 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1576ms to become available through index. |
| 04.05.2026 | 00:00:06.060 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1571ms to become available through index. |
| 04.05.2026 | 00:00:06.276 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1584ms to become available through index. |
| 04.05.2026 | 00:00:06.770 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1582ms to become available through index. |
| 04.05.2026 | 00:00:06.786 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1588ms to become available through index. |
| 04.05.2026 | 00:00:06.845 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 769ms to become available through index. |
| 04.05.2026 | 00:00:07.558 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1581ms to become available through index. |
| 04.05.2026 | 00:00:07.886 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1583ms to become available through index. |
| 04.05.2026 | 00:00:08.367 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 04.05.2026 | 00:00:08.377 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 04.05.2026 | 00:00:08.377 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 04.05.2026 | 00:00:08.378 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 04.05.2026 | 00:00:08.383 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 04.05.2026 | 00:00:08.386 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 04.05.2026 | 00:00:08.390 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1589ms to become available through index. |
| 04.05.2026 | 00:00:08.419 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1598ms to become available through index. |
| 04.05.2026 | 00:00:08.439 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1578ms to become available through index. |
| 04.05.2026 | 00:00:08.749 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 04.05.2026 | 00:00:08.750 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 04.05.2026 | 00:00:08.752 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 04.05.2026 | 00:00:08.760 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 04.05.2026 | 00:00:08.765 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 04.05.2026 | 00:00:08.819 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 04.05.2026 | 00:00:09.028 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 04.05.2026 | 00:00:09.031 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 04.05.2026 | 00:00:09.033 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 04.05.2026 | 00:00:09.036 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 04.05.2026 | 00:00:09.041 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 04.05.2026 | 00:00:09.052 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 04.05.2026 | 00:00:09.199 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1575ms to become available through index. |
