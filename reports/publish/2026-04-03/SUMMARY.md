# AEM PROD Publish Error Report — 2026-04-03
Report date: 2026-04-03
Generated from aemerror.log — general error validation.
## Summary
- **ERROR**: 805
- **WARN**: 87853
## By Class
| Class | ERROR | WARN |
|-------|-------|------|
| org.apache.jackrabbit.vault.fs.io.ImportOptions | 0 | 39729 |
| com.adobe.cq.updateprocessor.impl.ProcessorUtils | 0 | 26770 |
| GET | 716 | 13211 |
| com.adobe.granite.workflow.core.WorkflowSessionImpl | 0 | 5396 |
| com.adobe.cq.dam.cfm.graphql.ModelManagerImpl | 0 | 2219 |
| org.apache.felix.webconsole | 0 | 192 |
| org.apache.felix.hc.core.impl.executor.HealthCheckExecutorImpl | 0 | 86 |
| org.apache.felix.configadmin.plugin.interpolation.InterpolationConfigurationPlugin | 0 | 54 |
| LogService.org.apache.felix.eventadmin | 39 | 0 |
| com.adobe.granite.ims.yamlloader.ImsYamlLoader | 0 | 24 |
| com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | 18 | 0 |
| com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | 18 | 0 |
| com.adobe.cq.dam.assethandler.internal.events.consumer.impl.AssetBatchDeliveryConsumerImpl | 0 | 18 |
| com.day.cq.commons.impl.PredicateProviderImpl | 0 | 12 |
| org.apache.sling.resourceresolver.impl.VanityPathConfigurer | 0 | 12 |
| com.day.cq.dam.handler.gibson.fontmanager.impl.FontManagerServiceImpl | 0 | 12 |
| com.adobe.granite.repository.impl.SystemPrincipalsValidation | 0 | 12 |
| com.adobe.cq.wcm.translation.impl.utils.I18nUtils | 0 | 12 |
| com.adobe.granite.probes.impl.K8SProbes | 0 | 11 |
| com.adobe.granite.maintenance.impl.MaintenanceTaskInfoImpl | 0 | 8 |
| com.day.crx.sling.server.impl.jmx.SecureContentRepositoryAccess | 0 | 7 |
| com.azure.core.http.netty.implementation.Utility | 0 | 6 |
| org.apache.jackrabbit.oak.plugins.index.elastic.query.inference.InferenceIndexConfig | 0 | 6 |
| com.adobe.granite.workflow.console.generate.WorkflowModelGeneratorImpl | 0 | 6 |
| org.apache.jackrabbit.oak.jcr.lock.LockDeprecation | 0 | 6 |
| com.day.cq.commons.servlets.AbstractListServlet | 0 | 6 |
| com.day.cq.dam.core.impl.malware.QuarantineServiceImpl | 0 | 6 |
| com.adobe.granite.queries.impl.hc.QueryLimitsHealthCheck | 0 | 5 |
| io.prometheus.client.dropwizard.DropwizardExports | 0 | 5 |
| Events.Framework.org.apache.felix.log | 4 | 0 |
| org.apache.jackrabbit.oak.plugins.index.lucene.IndexCopier | 0 | 4 |
| org.apache.jackrabbit.oak.plugins.index.lucene.directory.CopyOnReadDirectory | 0 | 4 |
| Events.Framework.com.adobe.cq.dam.cq-dam-processor-nui | 3 | 0 |
| org.apache.sling.distribution.journal.impl.subscriber.DistributionSubscriber | 2 | 0 |
| org.apache.sling.event.impl.jobs.queues.JobQueueImpl.Reference | 2 | 0 |
| org.apache.sling.commons.scheduler.impl.QuartzScheduler | 2 | 0 |
| ROOT | 1 | 0 |
| [2080aa42-cb0c-4998-b545-07d7b86ca0de] | 0 | 1 |
| [78b940ce-3ff5-45dc-b0fe-b4e6970f8e10] | 0 | 1 |
| org.apache.sling.servlets.resolver.internal.resource.ServletMounter | 0 | 1 |
| com.adobe.cq.assetcompute.impl.smartcrop.CreateCropAssetComputeService | 0 | 1 |
| com.adobe.cq.assetcompute.impl.smartcrop.CreateCropAssetComputeEventHandler | 0 | 1 |
| com.adobe.cq.assetcompute.impl.connection.ConnectionServiceImpl | 0 | 1 |
| [0a1152e6-7ac4-42c7-afdd-9de4a8cdc342] | 0 | 1 |
| [0bb17afb-c71d-4586-988b-f3fac934c943] | 0 | 1 |
| [82193e27-2bfe-4f31-acca-ca78f799e5e8] | 0 | 1 |
| [6194d457-09d4-4c56-a0b9-1432e09413b2] | 0 | 1 |
| [8f702806-5ce6-407e-936c-0cbbcad3593e] | 0 | 1 |
| POST | 0 | 1 |
| org.apache.jackrabbit.oak.plugins.index.AsyncCheckpointCreator | 0 | 1 |
| [9d492f4f-40d3-4fe6-8251-1f0c1e8f406f] | 0 | 1 |

## Recent Errors (sample)
| Date | Time | Class | Message |
|------|------|-------|--------|
| 04.04.2026 | 00:00:00.075 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 04.04.2026 | 00:00:00.075 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [654] |
| 04.04.2026 | 00:00:00.124 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [654] |
| 04.04.2026 | 00:00:00.124 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 04.04.2026 | 00:00:00.130 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 04.04.2026 | 00:00:00.130 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [654] |
| 04.04.2026 | 00:00:00.182 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [654] |
| 04.04.2026 | 00:00:00.182 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 04.04.2026 | 00:00:00.291 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [654] |
| 04.04.2026 | 00:00:00.293 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 04.04.2026 | 00:00:00.309 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [654] |
| 04.04.2026 | 00:00:00.309 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 04.04.2026 | 00:00:28.875 | org.apache.sling.distribution.journal.impl.subscriber.DistributionSubscriber | Error processing queue item |
| 04.04.2026 | 00:00:50.299 | LogService.org.apache.felix.eventadmin | Service [com.adobe.cq.updateprocessor.impl.ReplicationListener,6543, [org.osgi.service.event.EventHa |
| 04.04.2026 | 00:00:50.300 | LogService.org.apache.felix.eventadmin | Service [com.adobe.cq.updateprocessor.impl.ReplicationListener,6543, [org.osgi.service.event.EventHa |
| 04.04.2026 | 00:00:50.300 | LogService.org.apache.felix.eventadmin | Service [com.adobe.cq.updateprocessor.impl.ReplicationListener,6543, [org.osgi.service.event.EventHa |
| 04.04.2026 | 00:00:50.300 | LogService.org.apache.felix.eventadmin | Service [com.adobe.cq.updateprocessor.impl.ReplicationListener,6543, [org.osgi.service.event.EventHa |
| 04.04.2026 | 00:00:50.300 | org.apache.sling.event.impl.jobs.queues.JobQueueImpl.Reference | Update Processing Queue Unhandled error occured in job processor Cannot invoke "com.adobe.cq.updatep |
| 04.04.2026 | 00:00:50.300 | LogService.org.apache.felix.eventadmin | Service [com.adobe.cq.updateprocessor.impl.ReplicationListener,6543, [org.osgi.service.event.EventHa |
| 04.04.2026 | 00:00:50.300 | LogService.org.apache.felix.eventadmin | Service [com.adobe.cq.updateprocessor.impl.ReplicationListener,6543, [org.osgi.service.event.EventHa |
| 04.04.2026 | 00:00:50.301 | LogService.org.apache.felix.eventadmin | Service [com.adobe.cq.updateprocessor.impl.ReplicationListener,6543, [org.osgi.service.event.EventHa |
| 04.04.2026 | 00:00:50.301 | LogService.org.apache.felix.eventadmin | Service [com.adobe.cq.updateprocessor.impl.ReplicationListener,6543, [org.osgi.service.event.EventHa |
| 04.04.2026 | 00:00:50.301 | LogService.org.apache.felix.eventadmin | Service [com.adobe.cq.updateprocessor.impl.ReplicationListener,6543, [org.osgi.service.event.EventHa |
| 04.04.2026 | 00:00:50.301 | LogService.org.apache.felix.eventadmin | Service [com.adobe.cq.updateprocessor.impl.ReplicationListener,6543, [org.osgi.service.event.EventHa |
| 04.04.2026 | 00:00:51.046 | Events.Framework.org.apache.felix.log | FrameworkEvent ERROR (java.lang.NullPointerException: Cannot invoke "org.osgi.framework.Bundle.getSy |
| 04.04.2026 | 00:01:10.558 | GET | /graphql/execute.json/realmadridmastersite/diaryV2;fromDate=2026-04-04T00:00:00.000Z;toDate=2026-06- |
| 04.04.2026 | 00:01:32.357 | GET | /graphql/execute.json/realmadridmastersite/news-section-detail-assembly%3bpath=%252Fcontent%252Fdam% |
| 04.04.2026 | 00:02:31.083 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [654] |
| 04.04.2026 | 00:02:31.086 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 04.04.2026 | 00:04:28.494 | org.apache.sling.distribution.journal.impl.subscriber.DistributionSubscriber | Error processing queue item |
| 04.04.2026 | 00:04:47.241 | org.apache.sling.event.impl.jobs.queues.JobQueueImpl.Reference | Update Processing Queue Unhandled error occured in job processor Cannot invoke "org.apache.sling.api |
| 04.04.2026 | 00:04:47.241 | LogService.org.apache.felix.eventadmin | Service [com.adobe.cq.updateprocessor.impl.ReplicationListener,5914, [org.osgi.service.event.EventHa |
| 04.04.2026 | 00:04:47.241 | LogService.org.apache.felix.eventadmin | Service [com.adobe.cq.updateprocessor.impl.ReplicationListener,5914, [org.osgi.service.event.EventHa |
| 04.04.2026 | 00:04:47.241 | LogService.org.apache.felix.eventadmin | Service [com.adobe.cq.updateprocessor.impl.ReplicationListener,5914, [org.osgi.service.event.EventHa |
| 04.04.2026 | 00:04:47.241 | LogService.org.apache.felix.eventadmin | Service [com.adobe.cq.updateprocessor.impl.ReplicationListener,5914, [org.osgi.service.event.EventHa |
| 04.04.2026 | 00:04:47.241 | LogService.org.apache.felix.eventadmin | Service [com.adobe.cq.updateprocessor.impl.ReplicationListener,5914, [org.osgi.service.event.EventHa |
| 04.04.2026 | 00:04:47.242 | LogService.org.apache.felix.eventadmin | Service [com.adobe.cq.updateprocessor.impl.ReplicationListener,5914, [org.osgi.service.event.EventHa |
| 04.04.2026 | 00:04:47.242 | LogService.org.apache.felix.eventadmin | Service [com.adobe.cq.updateprocessor.impl.ReplicationListener,5914, [org.osgi.service.event.EventHa |
| 04.04.2026 | 00:04:47.242 | LogService.org.apache.felix.eventadmin | Service [com.adobe.cq.updateprocessor.impl.ReplicationListener,5914, [org.osgi.service.event.EventHa |
| 04.04.2026 | 00:04:47.242 | LogService.org.apache.felix.eventadmin | Service [com.adobe.cq.updateprocessor.impl.ReplicationListener,5914, [org.osgi.service.event.EventHa |
| 04.04.2026 | 00:04:47.242 | LogService.org.apache.felix.eventadmin | Service [com.adobe.cq.updateprocessor.impl.ReplicationListener,5914, [org.osgi.service.event.EventHa |
| 04.04.2026 | 00:04:49.260 | Events.Framework.org.apache.felix.log | FrameworkEvent ERROR (java.lang.NullPointerException: Cannot invoke "org.osgi.framework.Bundle.getSy |
| 04.04.2026 | 00:05:22.668 | GET | /graphql/execute.json/realmadridmastersite/news-section-detail-assembly%3bpath=%252Fcontent%252Fdam% |
| 04.04.2026 | 00:05:32.319 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 04.04.2026 | 00:05:32.320 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.servlets.re |
| 04.04.2026 | 00:05:32.321 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 04.04.2026 | 00:05:32.321 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.servlets.re |
| 04.04.2026 | 00:05:32.322 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 04.04.2026 | 00:05:36.628 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 04.04.2026 | 00:05:36.630 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.servlets.re |

## Recent Warnings (sample)
| Date | Time | Class | Message |
|------|------|-------|--------|
| 04.04.2026 | 00:00:01.911 | GET | /content/dam/portals/realmadrid-com/es-es/news/generic/2026/04/03/fotos/ND-MILITAO_HE15520.jpg HTTP/ |
| 04.04.2026 | 00:00:03.985 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.tagging.impl.JcrTagImpl |
| 04.04.2026 | 00:00:04.828 | GET | /content/dam/portals/realmadrid-com/es-es/news/generic/2024/07/02/fotos/ND-ARDA-GULER_GettyImages-21 |
| 04.04.2026 | 00:00:05.021 | GET | /content/dam/portals/realmadrid-com/es-es/news/generic/2024/05/24/fotos/ND-ARDA-GULER-TURQUIA_GettyI |
| 04.04.2026 | 00:00:05.511 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 04.04.2026 | 00:00:05.522 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 04.04.2026 | 00:00:05.524 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 04.04.2026 | 00:00:05.527 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 04.04.2026 | 00:00:05.540 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 04.04.2026 | 00:00:05.609 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 04.04.2026 | 00:00:05.840 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 04.04.2026 | 00:00:05.841 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 04.04.2026 | 00:00:05.854 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 04.04.2026 | 00:00:05.880 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 04.04.2026 | 00:00:05.912 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 04.04.2026 | 00:00:05.920 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 04.04.2026 | 00:00:06.010 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 04.04.2026 | 00:00:06.039 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 04.04.2026 | 00:00:06.054 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 04.04.2026 | 00:00:06.063 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 04.04.2026 | 00:00:06.321 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 04.04.2026 | 00:00:06.354 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 04.04.2026 | 00:00:06.366 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 04.04.2026 | 00:00:06.412 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 04.04.2026 | 00:00:06.416 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 04.04.2026 | 00:00:06.422 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 04.04.2026 | 00:00:06.439 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 04.04.2026 | 00:00:06.666 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 806ms to become available through index. |
| 04.04.2026 | 00:00:06.770 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 04.04.2026 | 00:00:06.927 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 04.04.2026 | 00:00:06.927 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 04.04.2026 | 00:00:06.927 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 04.04.2026 | 00:00:06.927 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 04.04.2026 | 00:00:06.928 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 04.04.2026 | 00:00:06.951 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 04.04.2026 | 00:00:06.974 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 779ms to become available through index. |
| 04.04.2026 | 00:00:07.129 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 04.04.2026 | 00:00:07.138 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 04.04.2026 | 00:00:07.154 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 04.04.2026 | 00:00:07.191 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 04.04.2026 | 00:00:07.194 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 04.04.2026 | 00:00:07.520 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 04.04.2026 | 00:00:07.525 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 04.04.2026 | 00:00:07.549 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1609ms to become available through index. |
| 04.04.2026 | 00:00:07.563 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 04.04.2026 | 00:00:07.568 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 04.04.2026 | 00:00:07.569 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 04.04.2026 | 00:00:07.639 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 04.04.2026 | 00:00:07.643 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1615ms to become available through index. |
| 04.04.2026 | 00:00:07.708 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
