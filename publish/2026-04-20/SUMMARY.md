# AEM PROD Publish Error Report — 2026-04-20
Report date: 2026-04-20
Generated from aemerror.log — general error validation.
## Summary
- **ERROR**: 1849
- **WARN**: 92583
## By Class
| Class | ERROR | WARN |
|-------|-------|------|
| org.apache.jackrabbit.vault.fs.io.ImportOptions | 0 | 39329 |
| com.adobe.cq.updateprocessor.impl.ProcessorUtils | 0 | 28545 |
| GET | 1821 | 15410 |
| com.adobe.granite.workflow.core.WorkflowSessionImpl | 0 | 5619 |
| com.adobe.cq.dam.cfm.graphql.ModelManagerImpl | 0 | 2968 |
| org.apache.felix.webconsole | 0 | 256 |
| org.apache.felix.hc.core.impl.executor.HealthCheckExecutorImpl | 0 | 126 |
| org.apache.felix.configadmin.plugin.interpolation.InterpolationConfigurationPlugin | 0 | 72 |
| com.adobe.granite.ims.yamlloader.ImsYamlLoader | 0 | 32 |
| com.adobe.cq.dam.assethandler.internal.events.consumer.impl.AssetBatchDeliveryConsumerImpl | 0 | 24 |
| com.adobe.granite.repository.impl.SystemPrincipalsValidation | 0 | 24 |
| com.adobe.granite.probes.impl.K8SProbes | 0 | 16 |
| com.day.cq.commons.impl.PredicateProviderImpl | 0 | 16 |
| org.apache.sling.resourceresolver.impl.VanityPathConfigurer | 0 | 16 |
| com.day.cq.dam.handler.gibson.fontmanager.impl.FontManagerServiceImpl | 0 | 16 |
| com.adobe.cq.wcm.translation.impl.utils.I18nUtils | 0 | 16 |
| com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | 12 | 0 |
| com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | 12 | 0 |
| io.prometheus.client.dropwizard.DropwizardExports | 0 | 12 |
| com.adobe.granite.maintenance.impl.MaintenanceTaskInfoImpl | 0 | 12 |
| com.azure.core.http.netty.implementation.Utility | 0 | 8 |
| org.apache.jackrabbit.oak.plugins.index.elastic.query.inference.InferenceIndexConfig | 0 | 8 |
| com.adobe.granite.ims.client.config.ExpiryChecker | 0 | 8 |
| org.apache.jackrabbit.oak.jcr.lock.LockDeprecation | 0 | 8 |
| com.day.cq.commons.servlets.AbstractListServlet | 0 | 8 |
| com.adobe.granite.workflow.console.generate.WorkflowModelGeneratorImpl | 0 | 8 |
| com.day.crx.sling.server.impl.jmx.SecureContentRepositoryAccess | 0 | 6 |
| org.apache.sling.commons.scheduler.impl.QuartzScheduler | 4 | 0 |
| org.apache.jackrabbit.oak.plugins.index.lucene.IndexCopier | 0 | 4 |
| org.apache.jackrabbit.oak.plugins.index.lucene.directory.CopyOnReadDirectory | 0 | 1 |
| [07e93274-0e2d-44cb-bb1b-dae525632cdf] | 0 | 1 |
| org.apache.sling.servlets.resolver.internal.resource.ServletMounter | 0 | 1 |
| [74b4da02-d6c9-4d12-9340-7f2b6f2402d3] | 0 | 1 |
| [411324df-1644-42ea-8200-6ddbe1e64e2e] | 0 | 1 |
| [22f76168-d0f5-4b2f-abc9-4cde602f8d62] | 0 | 1 |
| [7e5ba412-3b5c-421d-a31a-f6cb011b6ce2] | 0 | 1 |
| [8769cf2f-c1bd-4193-b721-19c3d09d7fec] | 0 | 1 |
| [8e8e43df-1d39-4cd0-b890-2ef49e5ee063] | 0 | 1 |
| com.adobe.granite.queries.impl.hc.QueryLimitsHealthCheck | 0 | 1 |
| org.apache.jackrabbit.oak.plugins.index.AsyncCheckpointCreator | 0 | 1 |
| [33bd14db-c53e-44e1-a6ee-1deba2552539] | 0 | 1 |
| [43881b9b-c55b-45ae-ac33-e402bacdab5a] | 0 | 1 |
| [fbe9010e-460c-41e7-8045-286169dd25e2] | 0 | 1 |
| [6c341d39-d553-4271-b2e1-37d7d715ed6c] | 0 | 1 |
| [cb126e79-885a-4d01-ae38-d856dc0ee657] | 0 | 1 |

## Recent Errors (sample)
| Date | Time | Class | Message |
|------|------|-------|--------|
| 21.04.2026 | 00:00:00.065 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 21.04.2026 | 00:00:00.065 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [672] |
| 21.04.2026 | 00:00:00.084 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [672] |
| 21.04.2026 | 00:00:00.084 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 21.04.2026 | 00:00:00.092 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 21.04.2026 | 00:00:00.092 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [672] |
| 21.04.2026 | 00:00:00.095 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [672] |
| 21.04.2026 | 00:00:00.095 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 21.04.2026 | 00:00:00.117 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 21.04.2026 | 00:00:00.117 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [672] |
| 21.04.2026 | 00:00:00.133 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 21.04.2026 | 00:00:00.133 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [672] |
| 21.04.2026 | 00:00:16.989 | GET | /graphql/execute.json/realmadridmastersite/news-section-detail-assembly%3bpath=%252Fcontent%252Fdam% |
| 21.04.2026 | 00:01:03.748 | GET | /graphql/execute.json/realmadridmastersite/diaryV2;fromDate=2026-04-21T00:00:00.000Z;toDate=2026-07- |
| 21.04.2026 | 00:01:14.403 | GET | /content/dam/portals/realmadrid-com/pt-pt/news/generic/2026/03/28/videos/240326%20S7%20WEB%20CALENDA |
| 21.04.2026 | 00:03:09.465 | GET | /content/dam/portals/realmadrid-com/en-us/news/generic/2026/03/28/videos/240326%20S7%20WEB%20CALENDA |
| 21.04.2026 | 00:03:11.548 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 21.04.2026 | 00:03:11.707 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 21.04.2026 | 00:03:11.751 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 21.04.2026 | 00:04:06.921 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 21.04.2026 | 00:04:06.970 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 21.04.2026 | 00:04:07.015 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 21.04.2026 | 00:04:07.028 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 21.04.2026 | 00:04:07.073 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 21.04.2026 | 00:04:07.118 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 21.04.2026 | 00:04:32.057 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 21.04.2026 | 00:04:32.106 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 21.04.2026 | 00:04:32.155 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 21.04.2026 | 00:04:47.903 | org.apache.sling.commons.scheduler.impl.QuartzScheduler | Exception during job execution of job 'org.apache.jackrabbit.oak.plugins.index.lucene.directory.Luce |
| 21.04.2026 | 00:05:05.740 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 21.04.2026 | 00:05:05.890 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 21.04.2026 | 00:05:05.935 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 21.04.2026 | 00:05:27.105 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 21.04.2026 | 00:05:27.155 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 21.04.2026 | 00:05:27.208 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 21.04.2026 | 00:06:29.589 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 21.04.2026 | 00:06:29.637 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 21.04.2026 | 00:06:29.682 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 21.04.2026 | 00:06:29.693 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 21.04.2026 | 00:06:29.741 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 21.04.2026 | 00:06:29.788 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 21.04.2026 | 00:07:14.690 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 21.04.2026 | 00:07:14.737 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 21.04.2026 | 00:07:14.781 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 21.04.2026 | 00:09:47.908 | org.apache.sling.commons.scheduler.impl.QuartzScheduler | Exception during job execution of job 'org.apache.jackrabbit.oak.plugins.index.lucene.directory.Luce |
| 21.04.2026 | 00:10:25.674 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 21.04.2026 | 00:10:25.819 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 21.04.2026 | 00:10:25.865 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 21.04.2026 | 00:14:13.713 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 21.04.2026 | 00:14:13.860 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |

## Recent Warnings (sample)
| Date | Time | Class | Message |
|------|------|-------|--------|
| 21.04.2026 | 00:00:01.615 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.tagging.impl.JcrTagImpl |
| 21.04.2026 | 00:00:03.497 | GET | /content/dam/portals/realmadrid-com/es-es/news/generic/2026/04/20/fotos/01_ND_PREVIA_RM_ALAVES_ALEGR |
| 21.04.2026 | 00:00:03.785 | GET | /content/sling/app-servlets/realmadrid/ical.undefined.en-us.ics HTTP/1.1] com.day.cq.search.impl.bui |
| 21.04.2026 | 00:00:03.785 | GET | /content/sling/app-servlets/realmadrid/ical.undefined.en-us.ics HTTP/1.1] com.day.cq.search.impl.bui |
| 21.04.2026 | 00:00:05.799 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.tagging.impl.JcrTagImpl |
| 21.04.2026 | 00:00:09.126 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 21.04.2026 | 00:00:09.129 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 21.04.2026 | 00:00:09.130 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 21.04.2026 | 00:00:09.132 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 21.04.2026 | 00:00:09.134 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 21.04.2026 | 00:00:09.135 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 21.04.2026 | 00:00:09.217 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 21.04.2026 | 00:00:09.230 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 21.04.2026 | 00:00:09.231 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 21.04.2026 | 00:00:09.233 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 21.04.2026 | 00:00:09.242 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 21.04.2026 | 00:00:09.256 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 21.04.2026 | 00:00:09.743 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 21.04.2026 | 00:00:09.743 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 21.04.2026 | 00:00:09.744 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 21.04.2026 | 00:00:09.746 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 21.04.2026 | 00:00:09.747 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 21.04.2026 | 00:00:09.748 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 21.04.2026 | 00:00:10.587 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 21.04.2026 | 00:00:10.587 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 21.04.2026 | 00:00:10.588 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 21.04.2026 | 00:00:10.589 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 21.04.2026 | 00:00:10.590 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 21.04.2026 | 00:00:10.609 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 21.04.2026 | 00:00:10.692 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 21.04.2026 | 00:00:10.693 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 21.04.2026 | 00:00:10.755 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 21.04.2026 | 00:00:10.758 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 21.04.2026 | 00:00:10.760 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 21.04.2026 | 00:00:10.782 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 21.04.2026 | 00:00:11.040 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1604ms to become available through index. |
| 21.04.2026 | 00:00:11.059 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1599ms to become available through index. |
| 21.04.2026 | 00:00:11.098 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1608ms to become available through index. |
| 21.04.2026 | 00:00:11.107 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1612ms to become available through index. |
| 21.04.2026 | 00:00:11.127 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1610ms to become available through index. |
| 21.04.2026 | 00:00:11.195 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1623ms to become available through index. |
| 21.04.2026 | 00:00:11.196 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 21.04.2026 | 00:00:11.197 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 21.04.2026 | 00:00:11.200 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 21.04.2026 | 00:00:11.201 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 21.04.2026 | 00:00:11.202 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 21.04.2026 | 00:00:11.204 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 21.04.2026 | 00:00:11.513 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 21.04.2026 | 00:00:11.514 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 21.04.2026 | 00:00:11.515 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
