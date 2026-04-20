# AEM PROD Publish Error Report — 2026-04-19
Report date: 2026-04-19
Generated from aemerror.log — general error validation.
## Summary
- **ERROR**: 1805
- **WARN**: 97722
## By Class
| Class | ERROR | WARN |
|-------|-------|------|
| org.apache.jackrabbit.vault.fs.io.ImportOptions | 0 | 42569 |
| com.adobe.cq.updateprocessor.impl.ProcessorUtils | 0 | 31416 |
| GET | 1768 | 15292 |
| com.adobe.granite.workflow.core.WorkflowSessionImpl | 0 | 5615 |
| com.adobe.cq.dam.cfm.graphql.ModelManagerImpl | 0 | 2235 |
| org.apache.felix.webconsole | 0 | 192 |
| org.apache.felix.hc.core.impl.executor.HealthCheckExecutorImpl | 0 | 84 |
| org.apache.felix.configadmin.plugin.interpolation.InterpolationConfigurationPlugin | 0 | 54 |
| org.apache.jackrabbit.oak.plugins.index.lucene.IndexCopier | 0 | 48 |
| com.adobe.granite.ims.yamlloader.ImsYamlLoader | 0 | 24 |
| com.adobe.cq.dam.assethandler.internal.events.consumer.impl.AssetBatchDeliveryConsumerImpl | 0 | 18 |
| com.adobe.granite.repository.impl.SystemPrincipalsValidation | 0 | 18 |
| io.prometheus.client.dropwizard.DropwizardExports | 0 | 13 |
| com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | 12 | 0 |
| com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | 12 | 0 |
| com.adobe.granite.probes.impl.K8SProbes | 0 | 12 |
| com.day.cq.commons.impl.PredicateProviderImpl | 0 | 12 |
| org.apache.sling.resourceresolver.impl.VanityPathConfigurer | 0 | 12 |
| com.day.cq.dam.handler.gibson.fontmanager.impl.FontManagerServiceImpl | 0 | 12 |
| com.adobe.cq.wcm.translation.impl.utils.I18nUtils | 0 | 12 |
| com.adobe.granite.maintenance.impl.MaintenanceTaskInfoImpl | 0 | 11 |
| org.apache.jackrabbit.oak.plugins.index.lucene.directory.CopyOnReadDirectory | 0 | 7 |
| org.apache.sling.commons.scheduler.impl.QuartzScheduler | 6 | 0 |
| com.azure.core.http.netty.implementation.Utility | 0 | 6 |
| org.apache.jackrabbit.oak.plugins.index.elastic.query.inference.InferenceIndexConfig | 0 | 6 |
| com.adobe.granite.ims.client.config.ExpiryChecker | 0 | 6 |
| org.apache.jackrabbit.oak.jcr.lock.LockDeprecation | 0 | 6 |
| com.adobe.granite.workflow.console.generate.WorkflowModelGeneratorImpl | 0 | 6 |
| com.day.cq.commons.servlets.AbstractListServlet | 0 | 6 |
| com.day.crx.sling.server.impl.jmx.SecureContentRepositoryAccess | 0 | 6 |
| com.day.cq.audit.impl.AuditLogMaintenanceTask | 0 | 6 |
| Events.Framework.com.adobe.cq.dam.cq-dam-processor-nui | 3 | 0 |
| Events.Framework.org.apache.felix.log | 2 | 0 |
| ROOT | 1 | 0 |
| [42046041-1753-4bf6-b0c7-4dee62311e83] | 1 | 0 |
| [cbf16743-91d9-4367-9ffd-70f65d3bcd69] | 0 | 1 |
| [b7db9f5b-a867-4439-9dad-36af2828090e] | 0 | 1 |
| org.apache.sling.event.impl.jobs | 0 | 1 |
| com.adobe.cq.assetcompute.impl.smartcrop.CreateCropAssetComputeService | 0 | 1 |
| com.adobe.cq.assetcompute.impl.smartcrop.CreateCropAssetComputeEventHandler | 0 | 1 |
| com.adobe.cq.assetcompute.impl.connection.ConnectionServiceImpl | 0 | 1 |
| [9bc57ab7-c047-41a2-8b1e-2621a31227ff] | 0 | 1 |
| [5a5a8b17-9b4f-408e-b5d8-4db9fce297b9] | 0 | 1 |
| com.adobe.granite.toggle.impl.ToggleRouterImpl | 0 | 1 |
| [3b41b888-5b4f-483c-8355-e928ba616d5a] | 0 | 1 |
| [fb466f8c-17a7-442b-b012-5c97a25b6ae2] | 0 | 1 |
| [c44490f0-bd0f-4087-bb01-9619ae9c9c95] | 0 | 1 |
| [c6341817-d7f5-44be-a288-ebe270ee1b2c] | 0 | 1 |
| [5eecea2f-44bf-498b-a9e6-21948fecf5b3] | 0 | 1 |
| [6c9ea78f-f5ac-4d5c-99fe-f555a027629d] | 0 | 1 |
| [2e3895bb-49a4-492a-909d-01bff7cc737b] | 0 | 1 |
| [d97617c2-85b3-4f83-87a2-17243443614e] | 0 | 1 |
| [be473f2a-571f-4a8a-9828-d79d91bd741a] | 0 | 1 |

## Recent Errors (sample)
| Date | Time | Class | Message |
|------|------|-------|--------|
| 20.04.2026 | 00:00:00.067 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 20.04.2026 | 00:00:00.067 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [672] |
| 20.04.2026 | 00:00:00.102 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [672] |
| 20.04.2026 | 00:00:00.102 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 20.04.2026 | 00:00:00.103 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [672] |
| 20.04.2026 | 00:00:00.103 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 20.04.2026 | 00:00:00.146 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [672] |
| 20.04.2026 | 00:00:00.146 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 20.04.2026 | 00:00:00.153 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 20.04.2026 | 00:00:00.153 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [672] |
| 20.04.2026 | 00:00:00.159 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 20.04.2026 | 00:00:00.159 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [672] |
| 20.04.2026 | 00:01:34.112 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 20.04.2026 | 00:01:34.154 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 20.04.2026 | 00:01:34.195 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 20.04.2026 | 00:01:42.263 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 20.04.2026 | 00:01:42.264 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 20.04.2026 | 00:01:42.400 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 20.04.2026 | 00:01:42.443 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 20.04.2026 | 00:01:42.624 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 20.04.2026 | 00:01:42.669 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 20.04.2026 | 00:04:34.067 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 20.04.2026 | 00:04:34.112 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 20.04.2026 | 00:04:34.158 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 20.04.2026 | 00:05:16.062 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 20.04.2026 | 00:05:16.106 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 20.04.2026 | 00:05:16.154 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 20.04.2026 | 00:05:58.337 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 20.04.2026 | 00:05:58.358 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 20.04.2026 | 00:05:58.464 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 20.04.2026 | 00:05:58.471 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 20.04.2026 | 00:05:58.509 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 20.04.2026 | 00:05:58.514 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 20.04.2026 | 00:06:54.112 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 20.04.2026 | 00:06:54.128 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 20.04.2026 | 00:06:54.159 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 20.04.2026 | 00:06:54.203 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 20.04.2026 | 00:06:54.253 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 20.04.2026 | 00:06:54.296 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 20.04.2026 | 00:12:28.728 | GET | /graphql/execute.json/realmadridmastersite/news-section-detail-assembly%3bpath=%252Fcontent%252Fdam% |
| 20.04.2026 | 00:12:31.804 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 20.04.2026 | 00:12:31.845 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 20.04.2026 | 00:12:31.885 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 20.04.2026 | 00:12:48.231 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 20.04.2026 | 00:12:48.331 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 20.04.2026 | 00:12:48.364 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 20.04.2026 | 00:12:48.410 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 20.04.2026 | 00:12:48.470 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 20.04.2026 | 00:12:48.511 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 20.04.2026 | 00:13:14.963 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |

## Recent Warnings (sample)
| Date | Time | Class | Message |
|------|------|-------|--------|
| 20.04.2026 | 00:00:01.482 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.tagging.impl.JcrTagImpl |
| 20.04.2026 | 00:00:01.544 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.tagging.impl.JcrTagImpl |
| 20.04.2026 | 00:00:02.390 | GET | /graphql/execute.json/areavip/eventList%3bfromDate=2026-04-20T00:00%3btoDate=2027-04-20T00:00%3b.jso |
| 20.04.2026 | 00:00:02.403 | GET | /graphql/execute.json/areavip/eventList%3bfromDate=2026-04-20T00:00%3btoDate=2027-04-20T00:00%3b.jso |
| 20.04.2026 | 00:00:02.562 | GET | /content/dam/portals/realmadrid-com/es-es/news/generic/2026/01/18/fotos/ND-BRAHIM-MARRUECOS-GettyIma |
| 20.04.2026 | 00:00:07.677 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.tagging.impl.JcrTagImpl |
| 20.04.2026 | 00:00:08.464 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 20.04.2026 | 00:00:08.470 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 20.04.2026 | 00:00:08.471 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 20.04.2026 | 00:00:08.472 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 20.04.2026 | 00:00:08.474 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 20.04.2026 | 00:00:08.474 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 20.04.2026 | 00:00:08.696 | GET | /content/dam/portals/realmadrid-com/es-es/news/generic/2026/03/13/fotos/1ND_PREVIA_ALEGRIA-VINICIUS- |
| 20.04.2026 | 00:00:08.920 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 20.04.2026 | 00:00:08.920 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 20.04.2026 | 00:00:08.921 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 20.04.2026 | 00:00:08.921 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 20.04.2026 | 00:00:08.921 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 20.04.2026 | 00:00:09.012 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 20.04.2026 | 00:00:09.318 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 20.04.2026 | 00:00:09.318 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 20.04.2026 | 00:00:09.321 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 20.04.2026 | 00:00:09.321 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 20.04.2026 | 00:00:09.321 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 20.04.2026 | 00:00:09.322 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 20.04.2026 | 00:00:09.719 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 20.04.2026 | 00:00:09.719 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 20.04.2026 | 00:00:09.719 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 20.04.2026 | 00:00:09.720 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 20.04.2026 | 00:00:09.728 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 20.04.2026 | 00:00:09.729 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 20.04.2026 | 00:00:09.793 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 774ms to become available through index. |
| 20.04.2026 | 00:00:09.811 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 781ms to become available through index. |
| 20.04.2026 | 00:00:09.825 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 790ms to become available through index. |
| 20.04.2026 | 00:00:09.828 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 794ms to become available through index. |
| 20.04.2026 | 00:00:09.928 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 20.04.2026 | 00:00:09.929 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 20.04.2026 | 00:00:09.931 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 20.04.2026 | 00:00:09.931 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 20.04.2026 | 00:00:09.939 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 20.04.2026 | 00:00:09.944 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 20.04.2026 | 00:00:10.238 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 20.04.2026 | 00:00:10.238 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 20.04.2026 | 00:00:10.238 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 20.04.2026 | 00:00:10.238 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 20.04.2026 | 00:00:10.239 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 20.04.2026 | 00:00:10.240 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 20.04.2026 | 00:00:10.586 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1579ms to become available through index. |
| 20.04.2026 | 00:00:10.618 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 20.04.2026 | 00:00:10.619 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
