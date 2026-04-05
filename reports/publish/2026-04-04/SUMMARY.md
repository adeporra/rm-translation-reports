# AEM PROD Publish Error Report — 2026-04-04
Report date: 2026-04-04
Generated from aemerror.log — general error validation.
## Summary
- **ERROR**: 1283
- **WARN**: 89115
## By Class
| Class | ERROR | WARN |
|-------|-------|------|
| org.apache.jackrabbit.vault.fs.io.ImportOptions | 0 | 41281 |
| com.adobe.cq.updateprocessor.impl.ProcessorUtils | 0 | 27287 |
| GET | 1214 | 13108 |
| com.adobe.granite.workflow.core.WorkflowSessionImpl | 0 | 5460 |
| com.adobe.cq.dam.cfm.graphql.ModelManagerImpl | 0 | 1502 |
| org.apache.felix.webconsole | 0 | 177 |
| org.apache.felix.hc.core.impl.executor.HealthCheckExecutorImpl | 0 | 71 |
| org.apache.felix.configadmin.plugin.interpolation.InterpolationConfigurationPlugin | 0 | 54 |
| LogService.org.apache.felix.eventadmin | 34 | 0 |
| com.adobe.granite.ims.yamlloader.ImsYamlLoader | 0 | 20 |
| org.apache.sling.resourceresolver.impl.VanityPathConfigurer | 0 | 12 |
| com.day.cq.dam.handler.gibson.fontmanager.impl.FontManagerServiceImpl | 0 | 12 |
| com.adobe.cq.dam.assethandler.internal.events.consumer.impl.AssetBatchDeliveryConsumerImpl | 0 | 12 |
| com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | 11 | 0 |
| com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | 11 | 0 |
| io.prometheus.client.dropwizard.DropwizardExports | 0 | 11 |
| com.adobe.granite.repository.impl.SystemPrincipalsValidation | 0 | 10 |
| com.adobe.cq.wcm.translation.impl.utils.I18nUtils | 0 | 10 |
| com.adobe.granite.probes.impl.K8SProbes | 0 | 10 |
| com.adobe.granite.maintenance.impl.MaintenanceTaskInfoImpl | 0 | 9 |
| com.day.cq.commons.impl.PredicateProviderImpl | 0 | 9 |
| com.day.crx.sling.server.impl.jmx.SecureContentRepositoryAccess | 0 | 7 |
| com.azure.core.http.netty.implementation.Utility | 0 | 6 |
| org.apache.jackrabbit.oak.plugins.index.elastic.query.inference.InferenceIndexConfig | 0 | 6 |
| com.adobe.granite.queries.impl.hc.QueryLimitsHealthCheck | 0 | 6 |
| org.apache.sling.commons.scheduler.impl.QuartzScheduler | 5 | 0 |
| org.apache.jackrabbit.oak.plugins.index.lucene.IndexCopier | 0 | 5 |
| com.adobe.granite.workflow.console.generate.WorkflowModelGeneratorImpl | 0 | 5 |
| org.apache.jackrabbit.oak.jcr.lock.LockDeprecation | 0 | 5 |
| com.day.cq.dam.core.impl.malware.QuarantineServiceImpl | 0 | 5 |
| com.day.cq.commons.servlets.AbstractListServlet | 0 | 5 |
| org.apache.sling.distribution.journal.impl.subscriber.DistributionSubscriber | 3 | 0 |
| org.apache.sling.event.impl.jobs.queues.JobQueueImpl.Reference | 2 | 0 |
| org.apache.jackrabbit.oak.plugins.index.AsyncCheckpointCreator | 0 | 2 |
| Events.Framework.org.apache.felix.log | 1 | 0 |
| com.adobe.granite.repository.impl.SlingRepositoryManager | 1 | 0 |
| com.adobe.granite.panic.impl.PanicLoggerDetail | 1 | 0 |
| [a8e2087e-5797-4b14-b684-58b2686e5f31] | 0 | 1 |
| [e77486f9-d472-4299-9072-bce385f82fe3] | 0 | 1 |
| [a88ba413-867a-4eef-9c40-c9983cf3c0bb] | 0 | 1 |
| [070e857f-d148-4d30-a56a-784040103745] | 0 | 1 |
| [4fc3828f-ef29-45a9-99f5-d3c53b3cfabf] | 0 | 1 |
| [2b4e1907-d562-477a-b8e4-ad1749f7693a] | 0 | 1 |
| [87820abe-5388-46f2-8439-04539f795627] | 0 | 1 |
| [e46f8653-ae09-426c-a200-d2b836cfc80f] | 0 | 1 |

## Recent Errors (sample)
| Date | Time | Class | Message |
|------|------|-------|--------|
| 05.04.2026 | 00:00:00.109 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [654] |
| 05.04.2026 | 00:00:00.110 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 05.04.2026 | 00:00:00.111 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [654] |
| 05.04.2026 | 00:00:00.111 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 05.04.2026 | 00:00:00.114 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 05.04.2026 | 00:00:00.114 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [654] |
| 05.04.2026 | 00:00:00.170 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 05.04.2026 | 00:00:00.170 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [654] |
| 05.04.2026 | 00:00:00.299 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [654] |
| 05.04.2026 | 00:00:00.299 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 05.04.2026 | 00:00:46.709 | GET | /content/dam/portals/realmadrid-com/en-us/news/generic/2026/04/04/(fut)-mallorca-rm-j30-liga/videos/ |
| 05.04.2026 | 00:00:55.788 | GET | /content/dam/portals/realmadrid-com/fr-fr/news/generic/2026/04/04/(fut)-mallorca-rm-j30-liga/videos/ |
| 05.04.2026 | 00:01:11.278 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 05.04.2026 | 00:01:11.289 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 05.04.2026 | 00:01:11.417 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 05.04.2026 | 00:01:11.423 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 05.04.2026 | 00:01:11.461 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 05.04.2026 | 00:01:11.468 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 05.04.2026 | 00:01:46.035 | GET | /content/dam/portals/realmadrid-com/en-us/news/generic/2026/04/04/(fut)-mallorca-rm-j30-liga/videos/ |
| 05.04.2026 | 00:02:27.769 | GET | /content/dam/portals/realmadrid-com/en-us/news/generic/2026/03/27/(cas)-barakaldo-castilla-j30-1rfef |
| 05.04.2026 | 00:03:31.268 | org.apache.sling.distribution.journal.impl.subscriber.DistributionSubscriber | Error processing queue item |
| 05.04.2026 | 00:03:43.505 | GET | /content/dam/portals/realmadrid-com/en-us/news/generic/2026/04/04/(fut)-mallorca-rm-j30-liga/videos/ |
| 05.04.2026 | 00:03:49.002 | LogService.org.apache.felix.eventadmin | Service [com.adobe.cq.updateprocessor.impl.ReplicationListener,5184, [org.osgi.service.event.EventHa |
| 05.04.2026 | 00:03:49.003 | LogService.org.apache.felix.eventadmin | Service [com.adobe.cq.updateprocessor.impl.ReplicationListener,5184, [org.osgi.service.event.EventHa |
| 05.04.2026 | 00:03:49.003 | LogService.org.apache.felix.eventadmin | Service [com.adobe.cq.updateprocessor.impl.ReplicationListener,5184, [org.osgi.service.event.EventHa |
| 05.04.2026 | 00:03:49.003 | LogService.org.apache.felix.eventadmin | Service [com.adobe.cq.updateprocessor.impl.ReplicationListener,5184, [org.osgi.service.event.EventHa |
| 05.04.2026 | 00:03:49.003 | LogService.org.apache.felix.eventadmin | Service [com.adobe.cq.updateprocessor.impl.ReplicationListener,5184, [org.osgi.service.event.EventHa |
| 05.04.2026 | 00:03:49.004 | LogService.org.apache.felix.eventadmin | Service [com.adobe.cq.updateprocessor.impl.ReplicationListener,5184, [org.osgi.service.event.EventHa |
| 05.04.2026 | 00:03:49.004 | LogService.org.apache.felix.eventadmin | Service [com.adobe.cq.updateprocessor.impl.ReplicationListener,5184, [org.osgi.service.event.EventHa |
| 05.04.2026 | 00:03:49.004 | LogService.org.apache.felix.eventadmin | Service [com.adobe.cq.updateprocessor.impl.ReplicationListener,5184, [org.osgi.service.event.EventHa |
| 05.04.2026 | 00:03:49.004 | LogService.org.apache.felix.eventadmin | Service [com.adobe.cq.updateprocessor.impl.ReplicationListener,5184, [org.osgi.service.event.EventHa |
| 05.04.2026 | 00:03:49.005 | LogService.org.apache.felix.eventadmin | Service [com.adobe.cq.updateprocessor.impl.ReplicationListener,5184, [org.osgi.service.event.EventHa |
| 05.04.2026 | 00:03:52.426 | GET | /content/dam/portals/realmadrid-com/es-es/core-content/assemblies/pages/generic-pages/madridistas/ve |
| 05.04.2026 | 00:03:52.583 | GET | /content/dam/portals/realmadrid-com/es-es/core-content/assemblies/pages/generic-pages/madridistas/ve |
| 05.04.2026 | 00:03:52.585 | GET | /content/dam/portals/realmadrid-com/es-es/core-content/assemblies/pages/generic-pages/madridistas/ve |
| 05.04.2026 | 00:03:52.597 | GET | /content/dam/portals/realmadrid-com/es-es/core-content/assemblies/pages/generic-pages/madridistas/ve |
| 05.04.2026 | 00:03:52.621 | GET | /content/dam/portals/realmadrid-com/es-es/core-content/assemblies/pages/generic-pages/madridistas/ve |
| 05.04.2026 | 00:03:52.625 | GET | /content/dam/portals/realmadrid-com/es-es/core-content/assemblies/pages/generic-pages/madridistas/ve |
| 05.04.2026 | 00:03:52.635 | GET | /content/dam/portals/realmadrid-com/es-es/core-content/assemblies/pages/generic-pages/madridistas/ve |
| 05.04.2026 | 00:03:52.658 | GET | /content/dam/portals/realmadrid-com/es-es/core-content/assemblies/pages/generic-pages/madridistas/ve |
| 05.04.2026 | 00:03:52.730 | GET | /content/dam/portals/realmadrid-com/es-es/core-content/assemblies/pages/generic-pages/madridistas/ve |
| 05.04.2026 | 00:03:52.770 | GET | /content/dam/portals/realmadrid-com/es-es/core-content/assemblies/pages/generic-pages/madridistas/ve |
| 05.04.2026 | 00:03:52.805 | GET | /content/dam/portals/realmadrid-com/es-es/core-content/assemblies/pages/generic-pages/madridistas/ve |
| 05.04.2026 | 00:03:52.844 | GET | /content/dam/portals/realmadrid-com/es-es/core-content/assemblies/pages/generic-pages/madridistas/ve |
| 05.04.2026 | 00:04:25.513 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 05.04.2026 | 00:04:25.555 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 05.04.2026 | 00:04:25.603 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 05.04.2026 | 00:04:38.684 | GET | /content/dam/portals/realmadrid-com/fr-fr/news/generic/2026/04/04/(fut)-mallorca-rm-j30-liga/videos/ |
| 05.04.2026 | 00:04:42.309 | GET | /content/dam/portals/realmadrid-com/en-us/news/generic/2026/03/28/videos/240326%20S7%20WEB%20CALENDA |
| 05.04.2026 | 00:05:12.356 | GET | /content/dam/portals/realmadrid-com/en-us/news/generic/2026/04/04/(fut)-mallorca-rm-j30-liga/videos/ |

## Recent Warnings (sample)
| Date | Time | Class | Message |
|------|------|-------|--------|
| 05.04.2026 | 00:00:06.605 | org.apache.felix.webconsole | Legacy webconsole plugin found. Update this to the Jakarta Servlet API: Service 22([org.apache.felix |
| 05.04.2026 | 00:00:07.462 | org.apache.felix.webconsole | Legacy webconsole plugin found. Update this to the Jakarta Servlet API: Service 212([javax.servlet.S |
| 05.04.2026 | 00:00:07.770 | org.apache.felix.webconsole | Legacy webconsole plugin found. Update this to the Jakarta Servlet API: Service 686([javax.servlet.S |
| 05.04.2026 | 00:00:08.129 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 05.04.2026 | 00:00:08.145 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 05.04.2026 | 00:00:08.256 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 05.04.2026 | 00:00:08.625 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 05.04.2026 | 00:00:08.647 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 05.04.2026 | 00:00:08.655 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 05.04.2026 | 00:00:08.657 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 05.04.2026 | 00:00:08.658 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 05.04.2026 | 00:00:08.870 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 05.04.2026 | 00:00:08.907 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 05.04.2026 | 00:00:09.037 | org.apache.felix.configadmin.plugin.interpolation.InterpolationConfigurationPlugin | Cannot replace variable. Configured paths are not regular files: [/mnt/osgisecrets/azure/clientId] |
| 05.04.2026 | 00:00:09.037 | org.apache.felix.configadmin.plugin.interpolation.InterpolationConfigurationPlugin | Cannot replace variable. Configured paths are not regular files: [/mnt/osgisecrets/azure/clientSecre |
| 05.04.2026 | 00:00:09.038 | org.apache.felix.configadmin.plugin.interpolation.InterpolationConfigurationPlugin | Cannot replace variable. Configured paths are not regular files: [/mnt/osgisecrets/azure/tenantId] |
| 05.04.2026 | 00:00:09.196 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 05.04.2026 | 00:00:09.197 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 05.04.2026 | 00:00:09.214 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 05.04.2026 | 00:00:09.222 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 05.04.2026 | 00:00:09.282 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 05.04.2026 | 00:00:09.812 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 05.04.2026 | 00:00:09.814 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 05.04.2026 | 00:00:09.834 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 05.04.2026 | 00:00:09.852 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 05.04.2026 | 00:00:09.880 | org.apache.felix.configadmin.plugin.interpolation.InterpolationConfigurationPlugin | Cannot replace variable. Configured paths are not regular files: [/mnt/osgisecrets/segmentAzure/clie |
| 05.04.2026 | 00:00:09.880 | org.apache.felix.configadmin.plugin.interpolation.InterpolationConfigurationPlugin | Cannot replace variable. Configured paths are not regular files: [/mnt/osgisecrets/segmentAzure/tena |
| 05.04.2026 | 00:00:09.880 | org.apache.felix.configadmin.plugin.interpolation.InterpolationConfigurationPlugin | Cannot replace variable. Configured paths are not regular files: [/mnt/osgisecrets/segmentAzure/clie |
| 05.04.2026 | 00:00:10.039 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 05.04.2026 | 00:00:10.097 | com.azure.core.http.netty.implementation.Utility | The following Netty dependencies have versions that do not match the versions specified in the azure |
| 05.04.2026 | 00:00:10.295 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 05.04.2026 | 00:00:10.312 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 05.04.2026 | 00:00:10.321 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1586ms to become available through index. |
| 05.04.2026 | 00:00:10.337 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 05.04.2026 | 00:00:10.337 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 05.04.2026 | 00:00:10.361 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 05.04.2026 | 00:00:10.470 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 05.04.2026 | 00:00:10.489 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 05.04.2026 | 00:00:10.491 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 05.04.2026 | 00:00:10.507 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 05.04.2026 | 00:00:10.602 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 05.04.2026 | 00:00:10.630 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1605ms to become available through index. |
| 05.04.2026 | 00:00:10.638 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1614ms to become available through index. |
| 05.04.2026 | 00:00:10.699 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 05.04.2026 | 00:00:10.753 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 05.04.2026 | 00:00:10.769 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 05.04.2026 | 00:00:10.776 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 05.04.2026 | 00:00:10.858 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 05.04.2026 | 00:00:11.293 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 05.04.2026 | 00:00:11.311 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
