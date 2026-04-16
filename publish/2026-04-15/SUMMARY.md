# AEM PROD Publish Error Report — 2026-04-15
Report date: 2026-04-15
Generated from aemerror.log — general error validation.
## Summary
- **ERROR**: 2076
- **WARN**: 209615
## By Class
| Class | ERROR | WARN |
|-------|-------|------|
| org.apache.jackrabbit.vault.fs.io.ImportOptions | 0 | 127277 |
| com.adobe.cq.updateprocessor.impl.ProcessorUtils | 0 | 41465 |
| GET | 1257 | 18353 |
| com.adobe.granite.workflow.core.WorkflowSessionImpl | 0 | 18081 |
| com.adobe.cq.dam.cfm.graphql.ModelManagerImpl | 0 | 3348 |
| com.realmadridclubdefutbol.core.util.ResourceUtils | 486 | 0 |
| org.apache.felix.webconsole | 0 | 288 |
| org.apache.jackrabbit.vault.fs.io.AutoSave | 172 | 0 |
| org.apache.jackrabbit.vault.fs.io.Importer | 0 | 172 |
| org.apache.felix.hc.core.impl.executor.HealthCheckExecutorImpl | 0 | 140 |
| com.adobe.granite.workflow.core.job.JobHandler | 97 | 0 |
| org.apache.sling.event.impl.jobs.queues.JobQueueImpl.Granite | 0 | 97 |
| org.apache.felix.configadmin.plugin.interpolation.InterpolationConfigurationPlugin | 0 | 81 |
| com.adobe.granite.ims.yamlloader.ImsYamlLoader | 0 | 36 |
| com.adobe.cq.dam.assethandler.internal.events.consumer.impl.AssetBatchDeliveryConsumerImpl | 0 | 27 |
| com.adobe.granite.repository.impl.SystemPrincipalsValidation | 0 | 27 |
| org.apache.jackrabbit.oak.plugins.index.lucene.IndexCopier | 0 | 22 |
| LogService.org.apache.felix.eventadmin | 20 | 0 |
| io.prometheus.client.dropwizard.DropwizardExports | 0 | 19 |
| com.adobe.granite.probes.impl.K8SProbes | 0 | 18 |
| com.day.cq.commons.impl.PredicateProviderImpl | 0 | 18 |
| org.apache.sling.resourceresolver.impl.VanityPathConfigurer | 0 | 18 |
| com.day.cq.dam.handler.gibson.fontmanager.impl.FontManagerServiceImpl | 0 | 18 |
| com.adobe.cq.wcm.translation.impl.utils.I18nUtils | 0 | 18 |
| org.apache.sling.commons.scheduler.impl.QuartzScheduler | 16 | 0 |
| com.adobe.granite.maintenance.impl.MaintenanceTaskInfoImpl | 0 | 13 |
| com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | 11 | 0 |
| com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | 11 | 0 |
| com.azure.core.http.netty.implementation.Utility | 0 | 9 |
| org.apache.jackrabbit.oak.plugins.index.elastic.query.inference.InferenceIndexConfig | 0 | 9 |
| com.adobe.granite.workflow.console.generate.WorkflowModelGeneratorImpl | 0 | 9 |
| org.apache.jackrabbit.oak.jcr.lock.LockDeprecation | 0 | 9 |
| com.day.cq.commons.servlets.AbstractListServlet | 0 | 9 |
| com.day.crx.sling.server.impl.jmx.SecureContentRepositoryAccess | 0 | 8 |
| org.apache.jackrabbit.oak.plugins.index.lucene.directory.CopyOnReadDirectory | 0 | 5 |
| com.adobe.granite.queries.impl.hc.QueryLimitsHealthCheck | 0 | 5 |
| Events.Framework.org.apache.felix.log | 2 | 0 |
| org.apache.sling.distribution.journal.impl.subscriber.DistributionSubscriber | 2 | 0 |
| org.apache.sling.event.impl.jobs.queues.JobQueueImpl.Reference | 1 | 1 |
| org.apache.jackrabbit.oak.plugins.index.AsyncCheckpointCreator | 0 | 2 |
| org.apache.sling.event.impl.jobs | 1 | 0 |
| [31c5d2cc-21b9-4173-b9aa-2072c7bf988e] | 0 | 1 |
| org.apache.sling.jcr.resource.internal.helper.jcr.JcrProviderStateFactory | 0 | 1 |
| [36dbdeaa-3a52-4913-8096-85d11a08215f] | 0 | 1 |
| [b31c5d84-8d7d-4cee-a3c5-337ebbe2a298] | 0 | 1 |
| [d3b0f765-75df-4a8b-8fde-e32c4b1c0778] | 0 | 1 |
| [b1ea92e9-3ead-4f81-b9f2-f06a6d9822cf] | 0 | 1 |
| [fb4b5d4c-bae8-401f-bbba-fa9113cb49fd] | 0 | 1 |
| com.adobe.granite.toggle.impl.ToggleRouterImpl | 0 | 1 |
| [802a6653-a081-4418-89db-289ad999813d] | 0 | 1 |
| [e3acff66-fbcc-46cd-b9f4-f6ecd0410180] | 0 | 1 |
| [ef921fd2-387f-4e70-a774-20fe96356a8f] | 0 | 1 |
| [665c7954-9063-4a50-a250-8d7ea476c192] | 0 | 1 |
| [299bc215-ddfa-4b23-a8bd-0b2c66c80e05] | 0 | 1 |

## Recent Errors (sample)
| Date | Time | Class | Message |
|------|------|-------|--------|
| 16.04.2026 | 00:00:00.057 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [672] |
| 16.04.2026 | 00:00:00.057 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 16.04.2026 | 00:00:00.071 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [672] |
| 16.04.2026 | 00:00:00.071 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 16.04.2026 | 00:00:00.075 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [672] |
| 16.04.2026 | 00:00:00.075 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 16.04.2026 | 00:00:00.080 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [672] |
| 16.04.2026 | 00:00:00.080 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 16.04.2026 | 00:00:00.085 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [672] |
| 16.04.2026 | 00:00:00.085 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 16.04.2026 | 00:00:00.098 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [672] |
| 16.04.2026 | 00:00:00.098 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 16.04.2026 | 00:03:30.699 | GET | /graphql/execute.json/realmadridmastersite/structurePageV2%3balang=/content/dam/portals/realmadrid-c |
| 16.04.2026 | 00:06:23.404 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 16.04.2026 | 00:06:23.405 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.servlets.re |
| 16.04.2026 | 00:06:23.406 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.servlets.re |
| 16.04.2026 | 00:06:23.406 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 16.04.2026 | 00:06:23.407 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 16.04.2026 | 00:06:23.468 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 16.04.2026 | 00:06:23.470 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.servlets.re |
| 16.04.2026 | 00:06:23.470 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.servlets.re |
| 16.04.2026 | 00:06:23.471 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 16.04.2026 | 00:06:23.471 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 16.04.2026 | 00:06:23.530 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 16.04.2026 | 00:06:23.531 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.servlets.re |
| 16.04.2026 | 00:06:23.532 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.servlets.re |
| 16.04.2026 | 00:06:23.532 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 16.04.2026 | 00:06:23.533 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 16.04.2026 | 00:06:45.447 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 16.04.2026 | 00:06:45.448 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.servlets.re |
| 16.04.2026 | 00:06:45.448 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.servlets.re |
| 16.04.2026 | 00:06:45.449 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 16.04.2026 | 00:06:45.449 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 16.04.2026 | 00:06:45.761 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 16.04.2026 | 00:06:45.763 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 16.04.2026 | 00:06:45.763 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.servlets.re |
| 16.04.2026 | 00:06:45.763 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.servlets.re |
| 16.04.2026 | 00:06:45.764 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 16.04.2026 | 00:06:45.867 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 16.04.2026 | 00:06:45.868 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.servlets.re |
| 16.04.2026 | 00:06:45.868 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.servlets.re |
| 16.04.2026 | 00:06:45.868 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 16.04.2026 | 00:06:45.869 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 16.04.2026 | 00:06:57.409 | GET | /graphql/execute.json/realmadridmastersite/news-section-detail-assembly%3bpath=%252Fcontent%252Fdam% |
| 16.04.2026 | 00:09:16.720 | GET | /graphql/execute.json/realmadridmastersite/news-section-detail-assembly%3bpath=%252Fcontent%252Fdam% |
| 16.04.2026 | 00:09:57.480 | GET | /content/dam/portals/realmadrid-com/en-us/news/generic/2026/04/04/(fut)-mallorca-rm-j30-liga/videos/ |
| 16.04.2026 | 00:11:05.541 | org.apache.sling.commons.scheduler.impl.QuartzScheduler | Exception during job execution of job 'org.apache.jackrabbit.oak.plugins.index.lucene.directory.Luce |
| 16.04.2026 | 00:11:16.253 | org.apache.sling.commons.scheduler.impl.QuartzScheduler | Exception during job execution of job 'org.apache.jackrabbit.oak.plugins.index.lucene.directory.Luce |
| 16.04.2026 | 00:12:17.797 | GET | /content/dam/portals/realmadrid-com/es-es/core-content/assemblies/pages/generic-pages/madridistas/ve |
| 16.04.2026 | 00:12:17.909 | GET | /content/dam/portals/realmadrid-com/es-es/core-content/assemblies/pages/generic-pages/madridistas/ve |

## Recent Warnings (sample)
| Date | Time | Class | Message |
|------|------|-------|--------|
| 16.04.2026 | 00:00:01.327 | GET | /graphql/execute.json/areavip/eventList%3bfromDate=2026-04-16T00:00%3btoDate=2027-04-16T00:00%3b.jso |
| 16.04.2026 | 00:00:01.338 | GET | /graphql/execute.json/areavip/eventList%3bfromDate=2026-04-16T00:00%3btoDate=2027-04-16T00:00%3b.jso |
| 16.04.2026 | 00:00:03.185 | GET | /graphql/execute.json/realmadridmastersite/newsBySlugV2%3balang=/content/dam/portals/realmadrid-com/ |
| 16.04.2026 | 00:00:04.923 | GET | /graphql/execute.json/realmadridmastersite/pageByPath%3bpath=/content/dam/portals/realmadrid-com/en- |
| 16.04.2026 | 00:00:09.747 | GET | /graphql/execute.json/realmadridmastersite/newsBySlugV2%3balang=/content/dam/portals/realmadrid-com/ |
| 16.04.2026 | 00:00:14.260 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.tagging.impl.JcrTagImpl |
| 16.04.2026 | 00:00:14.887 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 16.04.2026 | 00:00:14.888 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 16.04.2026 | 00:00:14.889 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 16.04.2026 | 00:00:14.902 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 16.04.2026 | 00:00:14.906 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 16.04.2026 | 00:00:14.908 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 16.04.2026 | 00:00:18.929 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 16.04.2026 | 00:00:18.929 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 16.04.2026 | 00:00:18.930 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 16.04.2026 | 00:00:18.932 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 16.04.2026 | 00:00:18.934 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 16.04.2026 | 00:00:18.935 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 16.04.2026 | 00:00:19.043 | GET | /graphql/execute.json/realmadridmastersite/pageByPath%3bpath=/content/dam/portals/realmadrid-com/fr- |
| 16.04.2026 | 00:00:22.355 | GET | /graphql/execute.json/realmadridmastersite/pageByPath%3bpath=/content/dam/portals/realmadrid-com/en- |
| 16.04.2026 | 00:00:23.112 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 16.04.2026 | 00:00:23.113 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 16.04.2026 | 00:00:23.113 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 16.04.2026 | 00:00:23.114 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 16.04.2026 | 00:00:23.115 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 16.04.2026 | 00:00:23.116 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 16.04.2026 | 00:00:23.486 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 16.04.2026 | 00:00:23.486 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 16.04.2026 | 00:00:23.487 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 16.04.2026 | 00:00:23.487 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 16.04.2026 | 00:00:23.487 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 16.04.2026 | 00:00:23.530 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 16.04.2026 | 00:00:24.355 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 802ms to become available through index. |
| 16.04.2026 | 00:00:24.360 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 800ms to become available through index. |
| 16.04.2026 | 00:00:24.372 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 797ms to become available through index. |
| 16.04.2026 | 00:00:24.382 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 819ms to become available through index. |
| 16.04.2026 | 00:00:24.385 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 773ms to become available through index. |
| 16.04.2026 | 00:00:27.970 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 16.04.2026 | 00:00:27.971 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 16.04.2026 | 00:00:27.972 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 16.04.2026 | 00:00:27.972 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 16.04.2026 | 00:00:27.973 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 16.04.2026 | 00:00:27.974 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 16.04.2026 | 00:00:27.986 | GET | /graphql/execute.json/realmadridmastersite/pageByPath%3bpath=/content/dam/portals/realmadrid-com/pt- |
| 16.04.2026 | 00:00:28.690 | GET | /graphql/execute.json/realmadridmastersite/pageByPath%3bpath=/content/dam/portals/realmadrid-com/en- |
| 16.04.2026 | 00:00:29.671 | GET | /graphql/execute.json/realmadridmastersite/newsBySlugV2%3balang=/content/dam/portals/realmadrid-com/ |
| 16.04.2026 | 00:00:32.404 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 16.04.2026 | 00:00:32.409 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 16.04.2026 | 00:00:32.411 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 16.04.2026 | 00:00:32.417 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
