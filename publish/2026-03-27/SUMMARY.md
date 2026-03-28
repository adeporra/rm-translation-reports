# AEM PROD Publish Error Report — 2026-03-27
Report date: 2026-03-27
Generated from aemerror.log — general error validation.
## Summary
- **ERROR**: 569
- **WARN**: 86724
## By Class
| Class | ERROR | WARN |
|-------|-------|------|
| org.apache.jackrabbit.vault.fs.io.ImportOptions | 0 | 39536 |
| com.adobe.cq.updateprocessor.impl.ProcessorUtils | 0 | 29303 |
| GET | 539 | 9167 |
| com.adobe.granite.workflow.core.WorkflowSessionImpl | 0 | 5508 |
| com.adobe.cq.dam.cfm.graphql.ModelManagerImpl | 0 | 2624 |
| org.apache.felix.webconsole | 0 | 210 |
| org.apache.felix.hc.core.impl.executor.HealthCheckExecutorImpl | 0 | 82 |
| org.apache.felix.configadmin.plugin.interpolation.InterpolationConfigurationPlugin | 0 | 60 |
| com.adobe.granite.ims.yamlloader.ImsYamlLoader | 0 | 28 |
| com.adobe.cq.dam.assethandler.internal.events.consumer.impl.AssetBatchDeliveryConsumerImpl | 0 | 21 |
| com.adobe.granite.maintenance.impl.MaintenanceTaskInfoImpl | 0 | 15 |
| com.adobe.granite.probes.impl.K8SProbes | 0 | 14 |
| com.day.cq.commons.impl.PredicateProviderImpl | 0 | 14 |
| com.adobe.granite.repository.impl.SystemPrincipalsValidation | 0 | 14 |
| com.adobe.cq.wcm.translation.impl.utils.I18nUtils | 0 | 14 |
| com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | 12 | 0 |
| com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | 12 | 0 |
| org.apache.sling.resourceresolver.impl.VanityPathConfigurer | 0 | 12 |
| com.day.cq.dam.handler.gibson.fontmanager.impl.FontManagerServiceImpl | 0 | 12 |
| com.day.crx.sling.server.impl.jmx.SecureContentRepositoryAccess | 0 | 8 |
| com.azure.core.http.netty.implementation.Utility | 0 | 7 |
| com.adobe.granite.workflow.console.generate.WorkflowModelGeneratorImpl | 0 | 7 |
| org.apache.jackrabbit.oak.jcr.lock.LockDeprecation | 0 | 7 |
| com.day.cq.commons.servlets.AbstractListServlet | 0 | 7 |
| com.day.cq.dam.core.impl.malware.QuarantineServiceImpl | 0 | 7 |
| com.day.cq.wcm.workflow.impl.WcmWorkflowServiceImpl | 0 | 6 |
| org.apache.jackrabbit.oak.plugins.index.elastic.query.inference.InferenceIndexConfig | 0 | 6 |
| com.adobe.granite.queries.impl.hc.QueryLimitsHealthCheck | 0 | 6 |
| org.apache.jackrabbit.oak.plugins.index.lucene.directory.CopyOnReadDirectory | 0 | 5 |
| org.apache.jackrabbit.oak.plugins.index.lucene.IndexCopier | 0 | 5 |
| [0779eb6f-0f6c-482a-92fd-e5075babf82f] | 0 | 4 |
| Events.Framework.com.adobe.cq.dam.cq-dam-processor-nui | 3 | 0 |
| org.apache.jackrabbit.oak.plugins.index.AsyncCheckpointCreator | 0 | 3 |
| io.prometheus.client.dropwizard.DropwizardExports | 0 | 2 |
| Events.Framework.org.apache.felix.log | 1 | 0 |
| ROOT | 1 | 0 |
| org.apache.sling.commons.scheduler.impl.QuartzScheduler | 1 | 0 |
| [fa3e138f-3f36-4b7d-a85d-b723ad261bd6] | 0 | 1 |
| com.adobe.cq.assetcompute.impl.smartcrop.CreateCropAssetComputeService | 0 | 1 |
| com.adobe.cq.assetcompute.impl.smartcrop.CreateCropAssetComputeEventHandler | 0 | 1 |
| com.adobe.cq.assetcompute.impl.connection.ConnectionServiceImpl | 0 | 1 |
| [f05970bb-f931-46cc-8913-fe5d5ad6bee4] | 0 | 1 |
| [471a8b87-e8c9-409d-b8b6-5658b948dc84] | 0 | 1 |
| [f7afc3f8-d1cb-4139-8643-ac7656096cca] | 0 | 1 |
| [79f7946e-11d7-4469-91bb-8eefbdcd620e] | 0 | 1 |
| [b2eb4801-aa21-4acc-a48b-990483e8843c] | 0 | 1 |
| [a693efe3-e075-4743-b436-ae1dd45866a8] | 0 | 1 |

## Recent Errors (sample)
| Date | Time | Class | Message |
|------|------|-------|--------|
| 28.03.2026 | 00:00:00.085 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [654] |
| 28.03.2026 | 00:00:00.086 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 28.03.2026 | 00:00:00.100 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [654] |
| 28.03.2026 | 00:00:00.100 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 28.03.2026 | 00:00:00.114 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 28.03.2026 | 00:00:00.114 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [654] |
| 28.03.2026 | 00:00:00.127 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [654] |
| 28.03.2026 | 00:00:00.127 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 28.03.2026 | 00:00:00.164 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 28.03.2026 | 00:00:00.164 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [654] |
| 28.03.2026 | 00:00:00.206 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [654] |
| 28.03.2026 | 00:00:00.206 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 28.03.2026 | 00:01:38.075 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 28.03.2026 | 00:01:38.111 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 28.03.2026 | 00:01:38.157 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 28.03.2026 | 00:01:55.200 | GET | /graphql/execute.json/realmadridmastersite/news-section-detail-assembly%3bpath=%252Fcontent%252Fdam% |
| 28.03.2026 | 00:04:45.917 | GET | /content/dam/portals/realmadrid-com/en-us/news/generic/2026/03/27/(cas)-barakaldo-castilla-j30-1rfef |
| 28.03.2026 | 00:05:09.512 | GET | /content/dam/portals/realmadrid-com/en-us/news/generic/2026/03/27/(cas)-barakaldo-castilla-j30-1rfef |
| 28.03.2026 | 00:05:09.977 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 28.03.2026 | 00:05:10.020 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 28.03.2026 | 00:05:10.066 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 28.03.2026 | 00:06:02.193 | GET | /graphql/execute.json/realmadridmastersite/news-section-detail-assembly%3bpath=/content/dam/portals/ |
| 28.03.2026 | 00:06:02.502 | GET | /graphql/execute.json/realmadridmastersite/news-section-detail-assembly%3bpath=/content/dam/portals/ |
| 28.03.2026 | 00:08:38.334 | GET | /graphql/execute.json/realmadridmastersite/news-section-detail-assembly%3bpath=/content/dam/portals/ |
| 28.03.2026 | 00:09:44.214 | GET | /content/dam/portals/realmadrid-com/en-us/news/generic/2026/03/27/(cas)-barakaldo-castilla-j30-1rfef |
| 28.03.2026 | 00:10:11.474 | GET | /graphql/execute.json/realmadridmastersite/news-section-detail-assembly%3bpath=%252Fcontent%252Fdam% |
| 28.03.2026 | 00:11:08.840 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 28.03.2026 | 00:11:08.842 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.servlets.re |
| 28.03.2026 | 00:11:08.842 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.servlets.re |
| 28.03.2026 | 00:11:08.843 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 28.03.2026 | 00:11:08.843 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 28.03.2026 | 00:11:08.995 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 28.03.2026 | 00:11:08.996 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.servlets.re |
| 28.03.2026 | 00:11:08.996 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.servlets.re |
| 28.03.2026 | 00:11:08.997 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 28.03.2026 | 00:11:08.997 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 28.03.2026 | 00:11:09.128 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 28.03.2026 | 00:11:09.129 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.servlets.re |
| 28.03.2026 | 00:11:09.130 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.servlets.re |
| 28.03.2026 | 00:11:09.130 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 28.03.2026 | 00:11:09.131 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 28.03.2026 | 00:11:21.274 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 28.03.2026 | 00:11:21.276 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.servlets.re |
| 28.03.2026 | 00:11:21.276 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.servlets.re |
| 28.03.2026 | 00:11:21.277 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 28.03.2026 | 00:11:21.277 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 28.03.2026 | 00:11:22.184 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 28.03.2026 | 00:11:22.186 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.servlets.re |
| 28.03.2026 | 00:11:22.186 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.servlets.re |
| 28.03.2026 | 00:11:22.187 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |

## Recent Warnings (sample)
| Date | Time | Class | Message |
|------|------|-------|--------|
| 28.03.2026 | 00:00:05.067 | GET | /content/sling/app-servlets/realmadrid/ical.vaikl8nl7hdr4y9jj4jyb9ey.en-us.ics HTTP/1.1] com.day.cq. |
| 28.03.2026 | 00:00:05.067 | GET | /content/sling/app-servlets/realmadrid/ical.vaikl8nl7hdr4y9jj4jyb9ey.en-us.ics HTTP/1.1] com.day.cq. |
| 28.03.2026 | 00:00:06.939 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 28.03.2026 | 00:00:06.942 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 28.03.2026 | 00:00:06.944 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 28.03.2026 | 00:00:06.945 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 28.03.2026 | 00:00:06.947 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 28.03.2026 | 00:00:06.948 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 28.03.2026 | 00:00:07.137 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 28.03.2026 | 00:00:07.143 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 28.03.2026 | 00:00:07.152 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 28.03.2026 | 00:00:07.161 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 28.03.2026 | 00:00:07.239 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 28.03.2026 | 00:00:07.474 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 28.03.2026 | 00:00:07.802 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 28.03.2026 | 00:00:07.803 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 28.03.2026 | 00:00:07.806 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 28.03.2026 | 00:00:07.806 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 28.03.2026 | 00:00:07.807 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 28.03.2026 | 00:00:07.936 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 28.03.2026 | 00:00:08.104 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 800ms to become available through index. |
| 28.03.2026 | 00:00:08.291 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 28.03.2026 | 00:00:08.293 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 28.03.2026 | 00:00:08.296 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 28.03.2026 | 00:00:08.304 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 28.03.2026 | 00:00:08.306 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 28.03.2026 | 00:00:08.311 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 28.03.2026 | 00:00:08.461 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 784ms to become available through index. |
| 28.03.2026 | 00:00:08.611 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 28.03.2026 | 00:00:08.614 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 28.03.2026 | 00:00:08.616 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 28.03.2026 | 00:00:08.617 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 28.03.2026 | 00:00:08.617 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 28.03.2026 | 00:00:08.617 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 28.03.2026 | 00:00:08.932 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1601ms to become available through index. |
| 28.03.2026 | 00:00:08.939 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1612ms to become available through index. |
| 28.03.2026 | 00:00:08.947 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 28.03.2026 | 00:00:08.950 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 28.03.2026 | 00:00:08.985 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1620ms to become available through index. |
| 28.03.2026 | 00:00:09.030 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 28.03.2026 | 00:00:09.035 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 28.03.2026 | 00:00:09.054 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 28.03.2026 | 00:00:09.055 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1578ms to become available through index. |
| 28.03.2026 | 00:00:09.055 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 28.03.2026 | 00:00:09.326 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 28.03.2026 | 00:00:09.330 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 28.03.2026 | 00:00:09.332 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 28.03.2026 | 00:00:09.332 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 28.03.2026 | 00:00:09.333 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 28.03.2026 | 00:00:09.334 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
