# AEM PROD Publish Error Report — 2026-04-13
Report date: 2026-04-13
Generated from aemerror.log — general error validation.
## Summary
- **ERROR**: 1493
- **WARN**: 92926
## By Class
| Class | ERROR | WARN |
|-------|-------|------|
| org.apache.jackrabbit.vault.fs.io.ImportOptions | 0 | 39099 |
| com.adobe.cq.updateprocessor.impl.ProcessorUtils | 0 | 29037 |
| GET | 1467 | 16039 |
| com.adobe.granite.workflow.core.WorkflowSessionImpl | 0 | 5508 |
| com.adobe.cq.dam.cfm.graphql.ModelManagerImpl | 0 | 2615 |
| org.apache.felix.webconsole | 0 | 224 |
| org.apache.felix.hc.core.impl.executor.HealthCheckExecutorImpl | 0 | 110 |
| org.apache.felix.configadmin.plugin.interpolation.InterpolationConfigurationPlugin | 0 | 63 |
| com.adobe.granite.ims.yamlloader.ImsYamlLoader | 0 | 28 |
| com.adobe.cq.dam.assethandler.internal.events.consumer.impl.AssetBatchDeliveryConsumerImpl | 0 | 21 |
| io.prometheus.client.dropwizard.DropwizardExports | 0 | 17 |
| com.adobe.granite.probes.impl.K8SProbes | 0 | 14 |
| com.day.cq.commons.impl.PredicateProviderImpl | 0 | 14 |
| org.apache.sling.resourceresolver.impl.VanityPathConfigurer | 0 | 14 |
| com.day.cq.dam.handler.gibson.fontmanager.impl.FontManagerServiceImpl | 0 | 14 |
| com.adobe.granite.repository.impl.SystemPrincipalsValidation | 0 | 14 |
| com.adobe.cq.wcm.translation.impl.utils.I18nUtils | 0 | 14 |
| com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | 12 | 0 |
| com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | 12 | 0 |
| com.adobe.granite.maintenance.impl.MaintenanceTaskInfoImpl | 0 | 10 |
| com.day.crx.sling.server.impl.jmx.SecureContentRepositoryAccess | 0 | 7 |
| com.azure.core.http.netty.implementation.Utility | 0 | 7 |
| org.apache.jackrabbit.oak.plugins.index.elastic.query.inference.InferenceIndexConfig | 0 | 7 |
| org.apache.jackrabbit.oak.jcr.lock.LockDeprecation | 0 | 7 |
| com.adobe.granite.workflow.console.generate.WorkflowModelGeneratorImpl | 0 | 7 |
| com.day.cq.commons.servlets.AbstractListServlet | 0 | 7 |
| org.apache.jackrabbit.oak.plugins.index.AsyncCheckpointCreator | 0 | 5 |
| org.apache.jackrabbit.oak.plugins.index.lucene.IndexCopier | 0 | 2 |
| org.apache.jackrabbit.oak.plugins.index.lucene.directory.CopyOnReadDirectory | 0 | 2 |
| [468c789b-f0f3-46af-9f49-2bed5a5077f9] | 0 | 2 |
| [c6e52036-e7b8-43a0-8f66-5951cc7302c0] | 0 | 2 |
| [f90b4240-1480-4cd6-9d8e-645a9e1b536d] | 0 | 2 |
| Events.Framework.org.apache.felix.log | 1 | 0 |
| org.apache.sling.commons.scheduler.impl.QuartzScheduler | 1 | 0 |
| [94cc69c1-c337-4d96-ac68-dd6ffefa9fd0] | 0 | 1 |
| [40b9338d-557c-4f6f-ac4a-57321993c934] | 0 | 1 |
| [176dbd14-1552-4db5-93c9-490b01e73992] | 0 | 1 |
| [effa921b-a4fb-4321-9a5d-7c98ebb7fa0a] | 0 | 1 |
| [5ea7300c-dc17-45d2-a8a6-ebe58d15dceb] | 0 | 1 |
| [beb9a39c-3cb2-4e6c-a782-259817ac812e] | 0 | 1 |
| [db0a84c3-2c41-4639-bf68-3c8f1d88343a] | 0 | 1 |
| [044f014d-5fa3-4e64-a92f-b64672ef4272] | 0 | 1 |
| [e043f0c5-1664-47af-be82-5cb1da13fdc9] | 0 | 1 |
| [394eda9d-9006-4fc3-804d-2acce8128e94] | 0 | 1 |
| [2e435178-5d4c-4f6b-8033-0d7c083999ff] | 0 | 1 |
| [5094c0d5-18fe-4b6c-8876-3b5bfd247451] | 0 | 1 |
| [e059386b-066f-4873-b8d3-b81e45362858] | 0 | 1 |
| [c5542985-e6cb-4cb4-9c7a-c1cb20fc796f] | 0 | 1 |

## Recent Errors (sample)
| Date | Time | Class | Message |
|------|------|-------|--------|
| 14.04.2026 | 00:00:00.070 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [656] |
| 14.04.2026 | 00:00:00.070 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 14.04.2026 | 00:00:00.120 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [656] |
| 14.04.2026 | 00:00:00.121 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 14.04.2026 | 00:00:00.127 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 14.04.2026 | 00:00:00.127 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [656] |
| 14.04.2026 | 00:00:00.138 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [656] |
| 14.04.2026 | 00:00:00.138 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 14.04.2026 | 00:00:00.150 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 14.04.2026 | 00:00:00.150 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [656] |
| 14.04.2026 | 00:00:00.281 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [656] |
| 14.04.2026 | 00:00:00.282 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 14.04.2026 | 00:00:07.475 | GET | /graphql/execute.json/realmadridmastersite/diaryV2;fromDate=2026-04-14T00:00:00.000Z;toDate=2026-07- |
| 14.04.2026 | 00:00:23.968 | GET | /content/dam/portals/realmadrid-com/hi-in/core-content/assemblies/footer/mobile-app-section/App%20St |
| 14.04.2026 | 00:00:24.710 | GET | /content/dam/portals/realmadrid-com/hi-in/core-content/assemblies/footer/mobile-app-section/App%20St |
| 14.04.2026 | 00:00:24.904 | GET | /content/dam/portals/realmadrid-com/hi-in/core-content/assemblies/footer/mobile-app-section/App%20St |
| 14.04.2026 | 00:00:57.724 | GET | /content/dam/portals/realmadrid-com/en-us/news/generic/2026/04/14/(cas)-castilla-ourense-j33-1rfef/v |
| 14.04.2026 | 00:01:04.779 | GET | /graphql/execute.json/realmadridmastersite/news-section-detail-assembly%3bpath=%252Fcontent%252Fdam% |
| 14.04.2026 | 00:01:12.170 | GET | /graphql/execute.json/realmadridmastersite/news-section-detail-assembly%3bpath=%252Fcontent%252Fdam% |
| 14.04.2026 | 00:01:26.445 | GET | /content/dam/portals/realmadrid-com/pt-pt/news/generic/2026/02/09/videos/090226%20RMTV%20WEB%20LINDA |
| 14.04.2026 | 00:04:37.384 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 14.04.2026 | 00:04:37.387 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.servlets.re |
| 14.04.2026 | 00:04:37.387 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.servlets.re |
| 14.04.2026 | 00:04:37.388 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 14.04.2026 | 00:04:37.388 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 14.04.2026 | 00:04:37.901 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 14.04.2026 | 00:04:37.903 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.servlets.re |
| 14.04.2026 | 00:04:37.904 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.servlets.re |
| 14.04.2026 | 00:04:37.904 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 14.04.2026 | 00:04:37.905 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 14.04.2026 | 00:04:38.292 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 14.04.2026 | 00:04:38.294 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.servlets.re |
| 14.04.2026 | 00:04:38.294 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.servlets.re |
| 14.04.2026 | 00:04:38.295 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 14.04.2026 | 00:04:38.296 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 14.04.2026 | 00:04:49.257 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 14.04.2026 | 00:04:49.259 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.servlets.re |
| 14.04.2026 | 00:04:49.259 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.servlets.re |
| 14.04.2026 | 00:04:49.260 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 14.04.2026 | 00:04:49.261 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 14.04.2026 | 00:04:49.566 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 14.04.2026 | 00:04:49.568 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.servlets.re |
| 14.04.2026 | 00:04:49.569 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.servlets.re |
| 14.04.2026 | 00:04:49.569 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 14.04.2026 | 00:04:49.570 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 14.04.2026 | 00:04:49.836 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 14.04.2026 | 00:04:49.838 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 14.04.2026 | 00:04:49.838 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.servlets.re |
| 14.04.2026 | 00:04:49.838 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.servlets.re |
| 14.04.2026 | 00:04:49.839 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |

## Recent Warnings (sample)
| Date | Time | Class | Message |
|------|------|-------|--------|
| 14.04.2026 | 00:00:01.590 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.tagging.impl.JcrTagImpl |
| 14.04.2026 | 00:00:07.079 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 14.04.2026 | 00:00:07.080 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 14.04.2026 | 00:00:07.082 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 14.04.2026 | 00:00:07.098 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 14.04.2026 | 00:00:07.102 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 14.04.2026 | 00:00:07.142 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 14.04.2026 | 00:00:07.530 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 14.04.2026 | 00:00:07.565 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 14.04.2026 | 00:00:07.568 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 14.04.2026 | 00:00:07.568 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 14.04.2026 | 00:00:07.578 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 14.04.2026 | 00:00:07.715 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 14.04.2026 | 00:00:08.153 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 14.04.2026 | 00:00:08.156 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 14.04.2026 | 00:00:08.156 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 14.04.2026 | 00:00:08.156 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 14.04.2026 | 00:00:08.159 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 14.04.2026 | 00:00:08.167 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 14.04.2026 | 00:00:08.411 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 769ms to become available through index. |
| 14.04.2026 | 00:00:08.417 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 771ms to become available through index. |
| 14.04.2026 | 00:00:08.423 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 821ms to become available through index. |
| 14.04.2026 | 00:00:08.445 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 775ms to become available through index. |
| 14.04.2026 | 00:00:08.704 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 14.04.2026 | 00:00:08.705 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 14.04.2026 | 00:00:08.705 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 14.04.2026 | 00:00:08.706 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 14.04.2026 | 00:00:08.707 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 14.04.2026 | 00:00:08.865 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 14.04.2026 | 00:00:09.117 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 14.04.2026 | 00:00:09.119 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 14.04.2026 | 00:00:09.156 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 14.04.2026 | 00:00:09.156 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 14.04.2026 | 00:00:09.159 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 14.04.2026 | 00:00:09.202 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 14.04.2026 | 00:00:09.216 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1573ms to become available through index. |
| 14.04.2026 | 00:00:09.277 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 14.04.2026 | 00:00:09.288 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 14.04.2026 | 00:00:09.304 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 14.04.2026 | 00:00:09.330 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 14.04.2026 | 00:00:09.422 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 14.04.2026 | 00:00:09.425 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 14.04.2026 | 00:00:09.490 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 14.04.2026 | 00:00:09.491 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 14.04.2026 | 00:00:09.503 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 14.04.2026 | 00:00:09.509 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 14.04.2026 | 00:00:09.518 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 14.04.2026 | 00:00:09.568 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 14.04.2026 | 00:00:09.761 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 14.04.2026 | 00:00:09.762 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
