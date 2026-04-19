# AEM PROD Publish Error Report — 2026-04-18
Report date: 2026-04-18
Generated from aemerror.log — general error validation.
## Summary
- **ERROR**: 631
- **WARN**: 91534
## By Class
| Class | ERROR | WARN |
|-------|-------|------|
| org.apache.jackrabbit.vault.fs.io.ImportOptions | 0 | 40331 |
| com.adobe.cq.updateprocessor.impl.ProcessorUtils | 0 | 29419 |
| GET | 603 | 12924 |
| com.adobe.granite.workflow.core.WorkflowSessionImpl | 0 | 5615 |
| com.adobe.cq.dam.cfm.graphql.ModelManagerImpl | 0 | 2606 |
| org.apache.felix.webconsole | 0 | 224 |
| org.apache.felix.hc.core.impl.executor.HealthCheckExecutorImpl | 0 | 115 |
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
| org.apache.jackrabbit.oak.plugins.index.lucene.IndexCopier | 0 | 10 |
| org.apache.jackrabbit.oak.plugins.index.lucene.directory.CopyOnReadDirectory | 0 | 9 |
| com.azure.core.http.netty.implementation.Utility | 0 | 7 |
| org.apache.jackrabbit.oak.plugins.index.elastic.query.inference.InferenceIndexConfig | 0 | 7 |
| com.adobe.granite.ims.client.config.ExpiryChecker | 0 | 7 |
| com.adobe.granite.workflow.console.generate.WorkflowModelGeneratorImpl | 0 | 7 |
| org.apache.jackrabbit.oak.jcr.lock.LockDeprecation | 0 | 7 |
| com.day.cq.commons.servlets.AbstractListServlet | 0 | 7 |
| com.day.crx.sling.server.impl.jmx.SecureContentRepositoryAccess | 0 | 6 |
| io.prometheus.client.dropwizard.DropwizardExports | 0 | 5 |
| org.apache.sling.commons.scheduler.impl.QuartzScheduler | 4 | 0 |
| org.apache.jackrabbit.oak.plugins.index.AsyncCheckpointCreator | 0 | 4 |
| [7410aa20-b8e9-4e8e-a5d2-3bd64066a9fa] | 0 | 1 |
| [08781571-7d5f-4128-b0db-aba6613e247c] | 0 | 1 |
| [c7a7ae74-02f1-4275-b512-8e7d52a7530e] | 0 | 1 |
| [62f5c396-747d-44ae-ae36-77a099f1e1c3] | 0 | 1 |
| [f3468871-9f43-4c06-ac8f-baf4599dcdc9] | 0 | 1 |
| [5fdfc824-1a2e-4f06-a700-9514ad5dba12] | 0 | 1 |
| [510ddd6a-4a0f-4c89-adb0-f63cd51f1e32] | 0 | 1 |
| [c63c6151-9b0e-43e2-8cd9-4df6d3d78da5] | 0 | 1 |
| [216100d6-0480-4f7a-bd71-2a5f479a4a03] | 0 | 1 |
| [5cb3ee9b-8610-49f3-88de-751ed77a64b3] | 0 | 1 |

## Recent Errors (sample)
| Date | Time | Class | Message |
|------|------|-------|--------|
| 19.04.2026 | 00:00:00.082 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [672] |
| 19.04.2026 | 00:00:00.082 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 19.04.2026 | 00:00:00.099 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [672] |
| 19.04.2026 | 00:00:00.099 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 19.04.2026 | 00:00:00.110 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [672] |
| 19.04.2026 | 00:00:00.110 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 19.04.2026 | 00:00:00.112 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 19.04.2026 | 00:00:00.112 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [672] |
| 19.04.2026 | 00:00:00.113 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 19.04.2026 | 00:00:00.113 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [672] |
| 19.04.2026 | 00:00:00.129 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [672] |
| 19.04.2026 | 00:00:00.130 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 19.04.2026 | 00:00:33.871 | GET | /graphql/execute.json/realmadridmastersite/bannerByPath%3bpath=/content/dam/portals/mobile-app/ja-jp |
| 19.04.2026 | 00:01:08.670 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 19.04.2026 | 00:01:08.807 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 19.04.2026 | 00:01:08.849 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 19.04.2026 | 00:02:10.163 | GET | /graphql/execute.json/realmadridmastersite/diaryV2;fromDate=2026-04-19T00:00:00.000Z;toDate=2026-07- |
| 19.04.2026 | 00:02:58.231 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 19.04.2026 | 00:02:58.252 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 19.04.2026 | 00:02:58.367 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 19.04.2026 | 00:02:58.386 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 19.04.2026 | 00:02:58.409 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 19.04.2026 | 00:02:58.432 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 19.04.2026 | 00:03:50.403 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 19.04.2026 | 00:03:50.533 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 19.04.2026 | 00:03:50.576 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 19.04.2026 | 00:04:00.124 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 19.04.2026 | 00:04:00.126 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 19.04.2026 | 00:04:00.254 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 19.04.2026 | 00:04:00.260 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 19.04.2026 | 00:04:00.301 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 19.04.2026 | 00:04:00.302 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 19.04.2026 | 00:04:06.942 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 19.04.2026 | 00:04:06.982 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 19.04.2026 | 00:04:07.028 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 19.04.2026 | 00:05:06.692 | org.apache.sling.commons.scheduler.impl.QuartzScheduler | Exception during job execution of job 'org.apache.jackrabbit.oak.plugins.index.lucene.directory.Luce |
| 19.04.2026 | 00:06:10.124 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 19.04.2026 | 00:06:10.129 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 19.04.2026 | 00:06:10.170 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 19.04.2026 | 00:06:10.217 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 19.04.2026 | 00:06:10.233 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 19.04.2026 | 00:06:10.279 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 19.04.2026 | 00:08:16.109 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 19.04.2026 | 00:08:16.247 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 19.04.2026 | 00:08:16.293 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 19.04.2026 | 00:09:11.665 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 19.04.2026 | 00:09:11.671 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 19.04.2026 | 00:09:11.711 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 19.04.2026 | 00:09:11.756 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 19.04.2026 | 00:09:11.810 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |

## Recent Warnings (sample)
| Date | Time | Class | Message |
|------|------|-------|--------|
| 19.04.2026 | 00:00:07.159 | GET | /graphql/execute.json/areavip/eventList%3bfromDate=2026-04-19T00:00%3btoDate=2027-04-19T00:00%3b.jso |
| 19.04.2026 | 00:00:07.169 | GET | /graphql/execute.json/areavip/eventList%3bfromDate=2026-04-19T00:00%3btoDate=2027-04-19T00:00%3b.jso |
| 19.04.2026 | 00:00:07.786 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 19.04.2026 | 00:00:07.788 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 19.04.2026 | 00:00:07.801 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 19.04.2026 | 00:00:07.802 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 19.04.2026 | 00:00:07.923 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 19.04.2026 | 00:00:07.926 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 19.04.2026 | 00:00:08.030 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.tagging.impl.JcrTagImpl |
| 19.04.2026 | 00:00:08.210 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 19.04.2026 | 00:00:08.211 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 19.04.2026 | 00:00:08.212 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 19.04.2026 | 00:00:08.214 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 19.04.2026 | 00:00:08.214 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 19.04.2026 | 00:00:08.277 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 19.04.2026 | 00:00:08.719 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 19.04.2026 | 00:00:08.723 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 19.04.2026 | 00:00:08.723 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 19.04.2026 | 00:00:08.724 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 19.04.2026 | 00:00:08.745 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 19.04.2026 | 00:00:08.872 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 19.04.2026 | 00:00:09.294 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 19.04.2026 | 00:00:09.294 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 19.04.2026 | 00:00:09.295 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 19.04.2026 | 00:00:09.296 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 19.04.2026 | 00:00:09.298 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 19.04.2026 | 00:00:09.298 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 19.04.2026 | 00:00:09.839 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 19.04.2026 | 00:00:09.840 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 19.04.2026 | 00:00:09.841 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 19.04.2026 | 00:00:09.842 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 19.04.2026 | 00:00:09.843 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 19.04.2026 | 00:00:09.845 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 19.04.2026 | 00:00:09.892 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1607ms to become available through index. |
| 19.04.2026 | 00:00:09.915 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1604ms to become available through index. |
| 19.04.2026 | 00:00:09.932 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1574ms to become available through index. |
| 19.04.2026 | 00:00:09.932 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1617ms to become available through index. |
| 19.04.2026 | 00:00:09.953 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1625ms to become available through index. |
| 19.04.2026 | 00:00:09.961 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1610ms to become available through index. |
| 19.04.2026 | 00:00:10.142 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 19.04.2026 | 00:00:10.143 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 19.04.2026 | 00:00:10.143 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 19.04.2026 | 00:00:10.163 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 19.04.2026 | 00:00:10.225 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 19.04.2026 | 00:00:10.227 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 19.04.2026 | 00:00:10.457 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 19.04.2026 | 00:00:10.460 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 19.04.2026 | 00:00:10.460 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 19.04.2026 | 00:00:10.463 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 19.04.2026 | 00:00:10.464 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
