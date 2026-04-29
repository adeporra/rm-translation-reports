# AEM PROD Publish Error Report — 2026-04-28
Report date: 2026-04-28
Generated from aemerror.log — general error validation.
## Summary
- **ERROR**: 1103
- **WARN**: 91482
## By Class
| Class | ERROR | WARN |
|-------|-------|------|
| org.apache.jackrabbit.vault.fs.io.ImportOptions | 0 | 39375 |
| com.adobe.cq.updateprocessor.impl.ProcessorUtils | 0 | 28761 |
| GET | 1067 | 14357 |
| com.adobe.granite.workflow.core.WorkflowSessionImpl | 0 | 5615 |
| com.adobe.cq.dam.cfm.graphql.ModelManagerImpl | 0 | 2623 |
| org.apache.felix.webconsole | 0 | 224 |
| org.apache.jackrabbit.oak.plugins.index.lucene.IndexCopier | 0 | 125 |
| org.apache.felix.hc.core.impl.executor.HealthCheckExecutorImpl | 0 | 111 |
| org.apache.felix.configadmin.plugin.interpolation.InterpolationConfigurationPlugin | 0 | 63 |
| com.adobe.granite.ims.yamlloader.ImsYamlLoader | 0 | 28 |
| com.adobe.cq.dam.assethandler.internal.events.consumer.impl.AssetBatchDeliveryConsumerImpl | 0 | 21 |
| com.adobe.granite.repository.impl.SystemPrincipalsValidation | 0 | 21 |
| com.adobe.granite.probes.impl.K8SProbes | 0 | 14 |
| com.day.cq.commons.impl.PredicateProviderImpl | 0 | 14 |
| org.apache.sling.resourceresolver.impl.VanityPathConfigurer | 0 | 14 |
| com.day.cq.dam.handler.gibson.fontmanager.impl.FontManagerServiceImpl | 0 | 14 |
| com.adobe.cq.wcm.translation.impl.utils.I18nUtils | 0 | 14 |
| com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | 12 | 0 |
| com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | 12 | 0 |
| com.adobe.granite.maintenance.impl.MaintenanceTaskInfoImpl | 0 | 11 |
| io.prometheus.client.dropwizard.DropwizardExports | 0 | 8 |
| com.azure.core.http.netty.implementation.Utility | 0 | 7 |
| org.apache.jackrabbit.oak.plugins.index.elastic.query.inference.InferenceIndexConfig | 0 | 7 |
| com.adobe.granite.ims.client.config.ExpiryChecker | 0 | 7 |
| org.apache.jackrabbit.oak.jcr.lock.LockDeprecation | 0 | 7 |
| com.day.cq.commons.servlets.AbstractListServlet | 0 | 7 |
| com.adobe.granite.workflow.console.generate.WorkflowModelGeneratorImpl | 0 | 7 |
| org.apache.sling.commons.scheduler.impl.QuartzScheduler | 6 | 0 |
| com.day.crx.sling.server.impl.jmx.SecureContentRepositoryAccess | 0 | 6 |
| LogService.org.apache.felix.eventadmin | 4 | 0 |
| org.apache.jackrabbit.oak.plugins.index.lucene.directory.CopyOnReadDirectory | 0 | 3 |
| [36499ae8-b6df-48d0-988a-f02293286ea2] | 0 | 2 |
| org.apache.sling.distribution.journal.impl.subscriber.DistributionSubscriber | 1 | 0 |
| Events.Framework.org.apache.felix.log | 1 | 0 |
| [49fb54a3-c26e-4e30-9b91-83cc5e0f7880] | 0 | 1 |
| [ca9ba0ea-419c-47b1-ac0f-6e403549887a] | 0 | 1 |
| [7a78e8b9-0a2b-4017-a895-d1656209d166] | 0 | 1 |
| [752915f4-08d5-447e-9a31-d0f2a4909f1d] | 0 | 1 |
| [4ee86262-1b8a-4719-ac9f-a68d4e770698] | 0 | 1 |
| [d51faed9-bf22-4641-bca4-a44161291a7e] | 0 | 1 |
| com.adobe.granite.workflow.core.launcher.WorkflowLauncherListener | 0 | 1 |
| [6a0814ac-ba90-4420-81f2-02f3aaa057fa] | 0 | 1 |
| [b184a9e6-3ccf-4545-900f-6410a88f9e4f] | 0 | 1 |
| [5d94b32b-f847-4fd6-b9ca-83e5f7ef20a2] | 0 | 1 |
| [73e98e21-b99f-4037-bda8-991e2fa29285] | 0 | 1 |
| [2ec3389a-2eb6-4d6e-9626-952e2d063f38] | 0 | 1 |
| [0382afd1-8ebb-4981-824b-eb4df6431fb6] | 0 | 1 |
| [c503ee4b-2f03-4eed-bce2-a8a096936bd7] | 0 | 1 |
| [5f7db420-c076-4fc9-ba13-3b6d8c70cdd2] | 0 | 1 |
| [56340ebd-b31b-4e92-b103-abd48111b178] | 0 | 1 |

## Recent Errors (sample)
| Date | Time | Class | Message |
|------|------|-------|--------|
| 29.04.2026 | 00:00:00.072 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [657] |
| 29.04.2026 | 00:00:00.072 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 29.04.2026 | 00:00:00.083 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 29.04.2026 | 00:00:00.083 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [657] |
| 29.04.2026 | 00:00:00.091 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 29.04.2026 | 00:00:00.091 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [657] |
| 29.04.2026 | 00:00:00.093 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [657] |
| 29.04.2026 | 00:00:00.093 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 29.04.2026 | 00:00:00.105 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [657] |
| 29.04.2026 | 00:00:00.105 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 29.04.2026 | 00:00:00.109 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [657] |
| 29.04.2026 | 00:00:00.110 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 29.04.2026 | 00:00:50.022 | GET | /graphql/execute.json/madridistas/madridistasLandingPlatinumByPath%3bpath=/content/dam/portals/madri |
| 29.04.2026 | 00:02:19.026 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 29.04.2026 | 00:02:19.070 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 29.04.2026 | 00:02:19.112 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 29.04.2026 | 00:02:19.493 | GET | /graphql/execute.json/madridistas/madridistasLandingPlatinumByPath%3bpath=/content/dam/portals/madri |
| 29.04.2026 | 00:03:25.984 | org.apache.sling.commons.scheduler.impl.QuartzScheduler | Exception during job execution of job 'org.apache.jackrabbit.oak.plugins.index.lucene.directory.Luce |
| 29.04.2026 | 00:03:36.279 | GET | /graphql/execute.json/madridistas/madridistasLandingPlatinumByPath%3bpath=/content/dam/portals/madri |
| 29.04.2026 | 00:03:53.636 | GET | /graphql/execute.json/madridistas/madridistasLandingPlatinumByPath%3bpath=/content/dam/portals/madri |
| 29.04.2026 | 00:03:57.312 | org.apache.sling.commons.scheduler.impl.QuartzScheduler | Exception during job execution of job 'org.apache.jackrabbit.oak.plugins.index.lucene.directory.Luce |
| 29.04.2026 | 00:07:15.778 | GET | /graphql/execute.json/realmadridmastersite/news-section-detail-assembly%3bpath=%252Fcontent%252Fdam% |
| 29.04.2026 | 00:07:20.794 | GET | /graphql/execute.json/madridistas/madridistasLandingPlatinumByPath%3bpath=/content/dam/portals/madri |
| 29.04.2026 | 00:08:21.734 | GET | /graphql/execute.json/madridistas/madridistasLandingPlatinumByPath%3bpath=/content/dam/portals/madri |
| 29.04.2026 | 00:08:26.054 | org.apache.sling.commons.scheduler.impl.QuartzScheduler | Exception during job execution of job 'org.apache.jackrabbit.oak.plugins.index.lucene.directory.Luce |
| 29.04.2026 | 00:08:57.319 | org.apache.sling.commons.scheduler.impl.QuartzScheduler | Exception during job execution of job 'org.apache.jackrabbit.oak.plugins.index.lucene.directory.Luce |
| 29.04.2026 | 00:10:06.323 | org.apache.sling.commons.scheduler.impl.QuartzScheduler | Exception during job execution of job 'org.apache.jackrabbit.oak.plugins.index.lucene.directory.Luce |
| 29.04.2026 | 00:10:22.111 | GET | /graphql/execute.json/madridistas/madridistasLandingPlatinumByPath%3bpath=/content/dam/portals/madri |
| 29.04.2026 | 00:10:47.781 | GET | /graphql/execute.json/madridistas/madridistasLandingPlatinumByPath%3bpath=/content/dam/portals/madri |
| 29.04.2026 | 00:11:03.322 | GET | /graphql/execute.json/realmadridmastersite/news-section-detail-assembly%3bpath=/content/dam/portals/ |
| 29.04.2026 | 00:11:03.747 | GET | /graphql/execute.json/realmadridmastersite/news-section-detail-assembly%3bpath=/content/dam/portals/ |
| 29.04.2026 | 00:12:34.064 | GET | /graphql/execute.json/realmadridmastersite/news-section-detail-assembly%3bpath=%252Fcontent%252Fdam% |
| 29.04.2026 | 00:16:27.096 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 29.04.2026 | 00:16:27.098 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 29.04.2026 | 00:16:27.098 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.servlets.re |
| 29.04.2026 | 00:16:27.098 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.servlets.re |
| 29.04.2026 | 00:16:27.099 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 29.04.2026 | 00:16:27.357 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 29.04.2026 | 00:16:27.359 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 29.04.2026 | 00:16:27.359 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.servlets.re |
| 29.04.2026 | 00:16:27.359 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.servlets.re |
| 29.04.2026 | 00:16:27.360 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 29.04.2026 | 00:16:27.574 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 29.04.2026 | 00:16:27.575 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.servlets.re |
| 29.04.2026 | 00:16:27.575 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.servlets.re |
| 29.04.2026 | 00:16:27.576 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 29.04.2026 | 00:16:27.576 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 29.04.2026 | 00:17:19.509 | GET | /graphql/execute.json/madridistas/madridistasLandingPlatinumByPath%3bpath=/content/dam/portals/madri |
| 29.04.2026 | 00:19:19.169 | GET | /graphql/execute.json/madridistas/madridistasLandingPlatinumByPath%3bpath=/content/dam/portals/madri |
| 29.04.2026 | 00:21:09.971 | GET | /graphql/execute.json/madridistas/madridistasLandingPlatinumByPath%3bpath=/content/dam/portals/madri |

## Recent Warnings (sample)
| Date | Time | Class | Message |
|------|------|-------|--------|
| 29.04.2026 | 00:00:00.199 | GET | /graphql/execute.json/realmadridmastersite/newsBySlugV2%3balang=/content/dam/portals/realmadrid-com/ |
| 29.04.2026 | 00:00:00.200 | GET | /graphql/execute.json/realmadridmastersite/newsBySlugV2%3balang=/content/dam/portals/realmadrid-com/ |
| 29.04.2026 | 00:00:00.832 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.tagging.impl.JcrTagImpl |
| 29.04.2026 | 00:00:09.647 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 29.04.2026 | 00:00:09.649 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 29.04.2026 | 00:00:09.654 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 29.04.2026 | 00:00:09.672 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 29.04.2026 | 00:00:09.679 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 29.04.2026 | 00:00:09.682 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 29.04.2026 | 00:00:10.039 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 29.04.2026 | 00:00:10.040 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 29.04.2026 | 00:00:10.041 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 29.04.2026 | 00:00:10.041 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 29.04.2026 | 00:00:10.043 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 29.04.2026 | 00:00:10.047 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 29.04.2026 | 00:00:10.422 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 29.04.2026 | 00:00:10.423 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 29.04.2026 | 00:00:10.424 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 29.04.2026 | 00:00:10.426 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 29.04.2026 | 00:00:10.428 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 29.04.2026 | 00:00:10.430 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 29.04.2026 | 00:00:10.941 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 29.04.2026 | 00:00:10.942 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 29.04.2026 | 00:00:10.942 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 29.04.2026 | 00:00:10.943 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 29.04.2026 | 00:00:10.943 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 29.04.2026 | 00:00:10.947 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 29.04.2026 | 00:00:10.962 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 811ms to become available through index. |
| 29.04.2026 | 00:00:11.175 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 29.04.2026 | 00:00:11.187 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 29.04.2026 | 00:00:11.188 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 29.04.2026 | 00:00:11.194 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 29.04.2026 | 00:00:11.202 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 29.04.2026 | 00:00:11.203 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 29.04.2026 | 00:00:11.541 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 29.04.2026 | 00:00:11.542 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 29.04.2026 | 00:00:11.542 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 29.04.2026 | 00:00:11.542 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 29.04.2026 | 00:00:11.544 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 29.04.2026 | 00:00:11.553 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 29.04.2026 | 00:00:11.705 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1599ms to become available through index. |
| 29.04.2026 | 00:00:11.711 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1601ms to become available through index. |
| 29.04.2026 | 00:00:11.715 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1607ms to become available through index. |
| 29.04.2026 | 00:00:11.725 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 29.04.2026 | 00:00:11.733 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 29.04.2026 | 00:00:11.734 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1604ms to become available through index. |
| 29.04.2026 | 00:00:11.738 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 29.04.2026 | 00:00:11.739 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 29.04.2026 | 00:00:11.751 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 29.04.2026 | 00:00:11.757 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
