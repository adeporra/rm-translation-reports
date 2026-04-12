# AEM PROD Publish Error Report — 2026-04-11
Report date: 2026-04-11
Generated from aemerror.log — general error validation.
## Summary
- **ERROR**: 936
- **WARN**: 94525
## By Class
| Class | ERROR | WARN |
|-------|-------|------|
| org.apache.jackrabbit.vault.fs.io.ImportOptions | 0 | 40990 |
| com.adobe.cq.updateprocessor.impl.ProcessorUtils | 0 | 30039 |
| GET | 905 | 14732 |
| com.adobe.granite.workflow.core.WorkflowSessionImpl | 0 | 5508 |
| com.adobe.cq.dam.cfm.graphql.ModelManagerImpl | 0 | 2569 |
| org.apache.felix.webconsole | 0 | 224 |
| org.apache.felix.hc.core.impl.executor.HealthCheckExecutorImpl | 0 | 117 |
| org.apache.felix.configadmin.plugin.interpolation.InterpolationConfigurationPlugin | 0 | 63 |
| org.apache.jackrabbit.oak.plugins.index.lucene.IndexCopier | 0 | 42 |
| com.adobe.granite.ims.yamlloader.ImsYamlLoader | 0 | 28 |
| com.adobe.cq.dam.assethandler.internal.events.consumer.impl.AssetBatchDeliveryConsumerImpl | 0 | 21 |
| com.adobe.granite.probes.impl.K8SProbes | 0 | 14 |
| com.day.cq.commons.impl.PredicateProviderImpl | 0 | 14 |
| org.apache.sling.resourceresolver.impl.VanityPathConfigurer | 0 | 14 |
| com.day.cq.dam.handler.gibson.fontmanager.impl.FontManagerServiceImpl | 0 | 14 |
| com.adobe.granite.repository.impl.SystemPrincipalsValidation | 0 | 14 |
| com.adobe.cq.wcm.translation.impl.utils.I18nUtils | 0 | 14 |
| org.apache.jackrabbit.oak.plugins.index.lucene.directory.CopyOnReadDirectory | 0 | 13 |
| com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | 12 | 0 |
| com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | 12 | 0 |
| io.prometheus.client.dropwizard.DropwizardExports | 0 | 10 |
| com.adobe.granite.maintenance.impl.MaintenanceTaskInfoImpl | 0 | 10 |
| com.azure.core.http.netty.implementation.Utility | 0 | 7 |
| org.apache.jackrabbit.oak.plugins.index.elastic.query.inference.InferenceIndexConfig | 0 | 7 |
| com.adobe.granite.workflow.console.generate.WorkflowModelGeneratorImpl | 0 | 7 |
| org.apache.jackrabbit.oak.jcr.lock.LockDeprecation | 0 | 7 |
| com.day.cq.commons.servlets.AbstractListServlet | 0 | 7 |
| com.day.crx.sling.server.impl.jmx.SecureContentRepositoryAccess | 0 | 7 |
| org.apache.sling.commons.scheduler.impl.QuartzScheduler | 6 | 0 |
| com.adobe.granite.queries.impl.hc.QueryLimitsHealthCheck | 0 | 4 |
| org.apache.jackrabbit.oak.plugins.index.AsyncCheckpointCreator | 0 | 3 |
| Events.Framework.org.apache.felix.log | 1 | 0 |
| [fa3ad049-0c6f-42a1-8375-6560fa565fbf] | 0 | 1 |
| [c39cdffd-93ea-4537-becc-09e73460dd18] | 0 | 1 |
| [e98a3249-ca4a-4301-80bb-33f2477dfde8] | 0 | 1 |
| [efda3bc2-368f-4d98-9d0c-d3e9e7bb50d5] | 0 | 1 |
| [01753b2a-5a71-433d-b524-f37e04aa2f30] | 0 | 1 |
| [57ee0ddb-e6e4-423a-86fa-9179df3905d5] | 0 | 1 |
| [ddaf8c3d-3893-43c3-bd29-50243160e59d] | 0 | 1 |
| [77b8be31-6efd-42d7-ad32-98cd8406e07b] | 0 | 1 |
| [7745e7ee-1840-47c7-abb8-67be06351322] | 0 | 1 |
| [a628b7fc-8189-4b89-abbc-bb0a17e864b2] | 0 | 1 |
| [6b878109-0b7f-4768-8313-5742291b8fb7] | 0 | 1 |
| [9cd24c28-ebaa-4e75-8318-2f270946641c] | 0 | 1 |
| [420dff7d-d674-4904-bb83-4b0f2d1ba0ee] | 0 | 1 |
| [119894f6-3213-4aa7-b850-c8f629ed6ece] | 0 | 1 |
| [0a60c8c6-d67a-4731-9a39-77c04ee33da5] | 0 | 1 |
| [cdfb2ce9-11c7-4827-b40f-de254067da99] | 0 | 1 |
| [b56055d7-fc11-4c0a-9023-38967161d807] | 0 | 1 |
| [715a1252-35fb-4037-95c9-3af399cd15a3] | 0 | 1 |
| [b705cb0f-36dc-44ca-96c7-31215272c7f6] | 0 | 1 |
| [f43596f6-82d1-4fc2-be7a-53da4e08780c] | 0 | 1 |
| [098d1110-c8e6-4bb5-8424-0798f8affd5a] | 0 | 1 |
| [c2967a23-a515-4f7e-ada7-e735e19ed189] | 0 | 1 |
| [0cdd39b3-114a-4da4-bb85-8ef0a35c72a8] | 0 | 1 |
| [31076caa-980f-4e4c-ab97-8c966ed4cdc9] | 0 | 1 |
| [b53d4e70-7c91-48e7-95ca-c912e0292c0e] | 0 | 1 |
| [5945a2b6-11e9-4b74-9417-6c82fa56d99a] | 0 | 1 |

## Recent Errors (sample)
| Date | Time | Class | Message |
|------|------|-------|--------|
| 12.04.2026 | 00:00:00.071 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [656] |
| 12.04.2026 | 00:00:00.071 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 12.04.2026 | 00:00:00.075 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [656] |
| 12.04.2026 | 00:00:00.075 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 12.04.2026 | 00:00:00.098 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [656] |
| 12.04.2026 | 00:00:00.099 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 12.04.2026 | 00:00:00.110 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [656] |
| 12.04.2026 | 00:00:00.110 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 12.04.2026 | 00:00:00.155 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 12.04.2026 | 00:00:00.155 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [656] |
| 12.04.2026 | 00:00:00.175 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [656] |
| 12.04.2026 | 00:00:00.175 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 12.04.2026 | 00:00:53.118 | GET | /graphql/execute.json/realmadridmastersite/diaryV2;fromDate=2026-04-06T08:00:00.000Z;toDate=2026-06- |
| 12.04.2026 | 00:01:26.601 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 12.04.2026 | 00:01:26.734 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 12.04.2026 | 00:01:26.779 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 12.04.2026 | 00:01:47.082 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 12.04.2026 | 00:01:47.179 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 12.04.2026 | 00:01:47.330 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 12.04.2026 | 00:01:56.537 | org.apache.sling.commons.scheduler.impl.QuartzScheduler | Exception during job execution of job 'org.apache.jackrabbit.oak.plugins.index.lucene.directory.Luce |
| 12.04.2026 | 00:04:15.887 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 12.04.2026 | 00:04:15.892 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 12.04.2026 | 00:04:15.930 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 12.04.2026 | 00:04:15.973 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 12.04.2026 | 00:04:16.022 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 12.04.2026 | 00:04:16.065 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 12.04.2026 | 00:04:38.187 | org.apache.sling.commons.scheduler.impl.QuartzScheduler | Exception during job execution of job 'org.apache.jackrabbit.oak.plugins.index.lucene.directory.Luce |
| 12.04.2026 | 00:05:15.896 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 12.04.2026 | 00:05:15.943 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 12.04.2026 | 00:05:15.987 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 12.04.2026 | 00:05:16.026 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 12.04.2026 | 00:05:16.069 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 12.04.2026 | 00:05:21.602 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 12.04.2026 | 00:05:21.613 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 12.04.2026 | 00:05:21.664 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 12.04.2026 | 00:05:21.704 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 12.04.2026 | 00:05:21.774 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 12.04.2026 | 00:05:21.820 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 12.04.2026 | 00:05:41.735 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 12.04.2026 | 00:05:41.779 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 12.04.2026 | 00:05:41.825 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 12.04.2026 | 00:05:46.242 | org.apache.sling.commons.scheduler.impl.QuartzScheduler | Exception during job execution of job 'org.apache.jackrabbit.oak.plugins.index.lucene.directory.Luce |
| 12.04.2026 | 00:05:48.873 | GET | /content/dam/portals/realmadrid-com/pt-pt/news/generic/2026/02/09/videos/090226%20RMTV%20WEB%20LINDA |
| 12.04.2026 | 00:06:04.964 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 12.04.2026 | 00:06:04.964 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 12.04.2026 | 00:06:05.008 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 12.04.2026 | 00:06:05.011 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 12.04.2026 | 00:06:05.052 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 12.04.2026 | 00:06:05.054 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 12.04.2026 | 00:07:03.187 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |

## Recent Warnings (sample)
| Date | Time | Class | Message |
|------|------|-------|--------|
| 12.04.2026 | 00:00:00.179 | GET | /content/dam/portals/realmadrid-com/es-es/news/generic/2026/04/07/fotos/ND-MIRCEA-LUCESCU-01-GettyIm |
| 12.04.2026 | 00:00:01.733 | GET | /content/dam/portals/realmadrid-com/es-es/news/generic/2026/04/07/fotos/ND-MIRCEA-LUCESCU-01-GettyIm |
| 12.04.2026 | 00:00:06.162 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 12.04.2026 | 00:00:06.234 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 12.04.2026 | 00:00:06.251 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 12.04.2026 | 00:00:06.253 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 12.04.2026 | 00:00:06.257 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 12.04.2026 | 00:00:06.262 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 12.04.2026 | 00:00:06.292 | GET | /content/sling/app-servlets/realmadrid/ical.3kq9cckrnlogidldtdie2fkbl.ar-ae.ics HTTP/1.1] com.day.cq |
| 12.04.2026 | 00:00:06.292 | GET | /content/sling/app-servlets/realmadrid/ical.3kq9cckrnlogidldtdie2fkbl.ar-ae.ics HTTP/1.1] com.day.cq |
| 12.04.2026 | 00:00:06.719 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 12.04.2026 | 00:00:06.720 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 12.04.2026 | 00:00:06.721 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 12.04.2026 | 00:00:06.724 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 12.04.2026 | 00:00:06.732 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 12.04.2026 | 00:00:06.735 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 12.04.2026 | 00:00:07.189 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 12.04.2026 | 00:00:07.190 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 12.04.2026 | 00:00:07.192 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 12.04.2026 | 00:00:07.194 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 12.04.2026 | 00:00:07.195 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 12.04.2026 | 00:00:07.295 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 12.04.2026 | 00:00:07.570 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 772ms to become available through index. |
| 12.04.2026 | 00:00:07.585 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 797ms to become available through index. |
| 12.04.2026 | 00:00:07.604 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 816ms to become available through index. |
| 12.04.2026 | 00:00:07.630 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 782ms to become available through index. |
| 12.04.2026 | 00:00:07.638 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 815ms to become available through index. |
| 12.04.2026 | 00:00:07.652 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 823ms to become available through index. |
| 12.04.2026 | 00:00:07.964 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 12.04.2026 | 00:00:07.966 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 12.04.2026 | 00:00:07.968 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 12.04.2026 | 00:00:07.968 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 12.04.2026 | 00:00:07.969 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 12.04.2026 | 00:00:07.982 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 12.04.2026 | 00:00:08.140 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 12.04.2026 | 00:00:08.144 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 12.04.2026 | 00:00:08.145 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 12.04.2026 | 00:00:08.145 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 12.04.2026 | 00:00:08.158 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 12.04.2026 | 00:00:08.174 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 12.04.2026 | 00:00:08.447 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 12.04.2026 | 00:00:08.448 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 12.04.2026 | 00:00:08.450 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 12.04.2026 | 00:00:08.454 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 12.04.2026 | 00:00:08.469 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 12.04.2026 | 00:00:08.515 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 12.04.2026 | 00:00:08.826 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 12.04.2026 | 00:00:08.827 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 12.04.2026 | 00:00:08.829 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 12.04.2026 | 00:00:08.830 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
