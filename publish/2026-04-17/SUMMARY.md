# AEM PROD Publish Error Report — 2026-04-17
Report date: 2026-04-17
Generated from aemerror.log — general error validation.
## Summary
- **ERROR**: 956
- **WARN**: 93041
## By Class
| Class | ERROR | WARN |
|-------|-------|------|
| org.apache.jackrabbit.vault.fs.io.ImportOptions | 0 | 40086 |
| com.adobe.cq.updateprocessor.impl.ProcessorUtils | 0 | 29373 |
| GET | 926 | 14284 |
| com.adobe.granite.workflow.core.WorkflowSessionImpl | 0 | 5632 |
| com.adobe.cq.dam.cfm.graphql.ModelManagerImpl | 0 | 2986 |
| org.apache.felix.webconsole | 0 | 256 |
| org.apache.felix.hc.core.impl.executor.HealthCheckExecutorImpl | 0 | 106 |
| org.apache.felix.configadmin.plugin.interpolation.InterpolationConfigurationPlugin | 0 | 72 |
| com.adobe.granite.ims.yamlloader.ImsYamlLoader | 0 | 32 |
| com.adobe.cq.dam.assethandler.internal.events.consumer.impl.AssetBatchDeliveryConsumerImpl | 0 | 24 |
| com.adobe.granite.repository.impl.SystemPrincipalsValidation | 0 | 24 |
| com.adobe.granite.probes.impl.K8SProbes | 0 | 16 |
| com.day.cq.commons.impl.PredicateProviderImpl | 0 | 16 |
| org.apache.sling.resourceresolver.impl.VanityPathConfigurer | 0 | 16 |
| com.day.cq.dam.handler.gibson.fontmanager.impl.FontManagerServiceImpl | 0 | 16 |
| com.adobe.cq.wcm.translation.impl.utils.I18nUtils | 0 | 16 |
| com.adobe.granite.maintenance.impl.MaintenanceTaskInfoImpl | 0 | 13 |
| com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | 12 | 0 |
| com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | 12 | 0 |
| io.prometheus.client.dropwizard.DropwizardExports | 0 | 10 |
| com.azure.core.http.netty.implementation.Utility | 0 | 8 |
| org.apache.jackrabbit.oak.plugins.index.elastic.query.inference.InferenceIndexConfig | 0 | 8 |
| org.apache.jackrabbit.oak.jcr.lock.LockDeprecation | 0 | 8 |
| com.day.cq.commons.servlets.AbstractListServlet | 0 | 8 |
| com.adobe.granite.workflow.console.generate.WorkflowModelGeneratorImpl | 0 | 8 |
| com.day.crx.sling.server.impl.jmx.SecureContentRepositoryAccess | 0 | 7 |
| org.apache.sling.commons.scheduler.impl.QuartzScheduler | 5 | 0 |
| [d809aee8-1607-4852-9b81-f5c16fae212e] | 0 | 2 |
| com.adobe.granite.queries.impl.hc.QueryLimitsHealthCheck | 0 | 2 |
| [4959884a-6c37-487e-8969-905f8ebc17ad] | 0 | 2 |
| Events.Framework.org.apache.felix.log | 1 | 0 |
| [97ed108e-e04d-43fb-a897-4fc302c449c2] | 0 | 1 |
| [851e20d8-481d-4fa1-aeae-ed369fbd3919] | 0 | 1 |
| [7a8c0cba-1a8f-4401-9572-4213466fd976] | 0 | 1 |
| [342336b5-af68-4915-9124-2853265394b8] | 0 | 1 |
| [66f756a9-aebf-4045-a953-fc333d3a554d] | 0 | 1 |
| [a08f907c-8c1c-4d88-b542-d83974626e56] | 0 | 1 |
| [8a5098c9-e546-49ee-9cc8-fd410beab1a7] | 0 | 1 |
| [f6749c5f-00f2-4f3d-9512-955f0dd7939c] | 0 | 1 |
| [17b3911f-a40d-4dc8-b126-1a48c6c3a5c2] | 0 | 1 |
| [5a62afb5-23c9-407a-a3d0-fd6797e31055] | 0 | 1 |

## Recent Errors (sample)
| Date | Time | Class | Message |
|------|------|-------|--------|
| 18.04.2026 | 00:00:00.092 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [672] |
| 18.04.2026 | 00:00:00.092 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 18.04.2026 | 00:00:00.094 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 18.04.2026 | 00:00:00.094 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [672] |
| 18.04.2026 | 00:00:00.113 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [672] |
| 18.04.2026 | 00:00:00.113 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 18.04.2026 | 00:00:00.117 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 18.04.2026 | 00:00:00.117 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [672] |
| 18.04.2026 | 00:00:00.123 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [672] |
| 18.04.2026 | 00:00:00.123 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 18.04.2026 | 00:00:00.127 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 18.04.2026 | 00:00:00.127 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [672] |
| 18.04.2026 | 00:01:25.745 | GET | /graphql/execute.json/estadio/newsListByTagV2;alang=/content/dam/portals/estadio/es-es/;tag=%7b%22_e |
| 18.04.2026 | 00:02:34.177 | GET | /graphql/execute.json/realmadridmastersite/diaryV2;fromDate=2026-04-18T00:00:00.000Z;toDate=2026-07- |
| 18.04.2026 | 00:04:47.932 | GET | /content/dam/portals/realmadrid-com/en-us/news/generic/2026/04/14/(cas)-castilla-ourense-j33-1rfef/v |
| 18.04.2026 | 00:06:44.819 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 18.04.2026 | 00:06:45.625 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 18.04.2026 | 00:06:45.835 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 18.04.2026 | 00:08:45.853 | org.apache.sling.commons.scheduler.impl.QuartzScheduler | Exception during job execution of job 'org.apache.jackrabbit.oak.plugins.index.lucene.directory.Luce |
| 18.04.2026 | 00:10:46.088 | GET | /graphql/execute.json/realmadridmastersite/diaryV2;fromDate=2026-04-18T00:00:00.000Z;toDate=2026-07- |
| 18.04.2026 | 00:11:09.698 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 18.04.2026 | 00:11:09.932 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 18.04.2026 | 00:11:10.147 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 18.04.2026 | 00:11:53.999 | GET | /graphql/execute.json/realmadridmastersite/news-section-detail-assembly%3bpath=%252Fcontent%252Fdam% |
| 18.04.2026 | 00:12:16.918 | GET | /graphql/execute.json/realmadridmastersite/diaryV2;fromDate=2026-04-18T00:00:00.000Z;toDate=2026-07- |
| 18.04.2026 | 00:12:19.391 | GET | /graphql/execute.json/realmadridmastersite/news-section-detail-assembly%3bpath=%252Fcontent%252Fdam% |
| 18.04.2026 | 00:12:53.669 | GET | /content/dam/portals/realmadrid-com/en-us/news/generic/2026/03/28/videos/240326%20S7%20WEB%20CALENDA |
| 18.04.2026 | 00:14:25.650 | GET | /graphql/execute.json/realmadridmastersite/diaryV2;fromDate=2026-04-18T00:00:00.000Z;toDate=2026-07- |
| 18.04.2026 | 00:15:34.915 | GET | /content/dam/portals/realmadrid-com/en-us/news/generic/2026/02/17/videos/TOTALES%20PAU%20QUESADA%20Y |
| 18.04.2026 | 00:15:44.391 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 18.04.2026 | 00:15:44.434 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 18.04.2026 | 00:15:44.466 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 18.04.2026 | 00:15:44.480 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 18.04.2026 | 00:15:44.605 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 18.04.2026 | 00:15:44.649 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 18.04.2026 | 00:15:53.754 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 18.04.2026 | 00:15:53.804 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 18.04.2026 | 00:15:53.851 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 18.04.2026 | 00:15:59.107 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 18.04.2026 | 00:15:59.238 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 18.04.2026 | 00:15:59.279 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 18.04.2026 | 00:17:05.081 | GET | /content/dam/portals/realmadrid-com/de-de/news/generic/2026/04/04/(fut)-mallorca-rm-j30-liga/videos/ |
| 18.04.2026 | 00:18:20.335 | GET | /content/dam/portals/realmadrid-com/en-us/news/generic/2026/04/17/videos/170426%20RMTV%20WEB%20RESUM |
| 18.04.2026 | 00:18:20.355 | GET | /graphql/execute.json/realmadridmastersite/diaryV2;fromDate=2026-04-18T00:00:00.000Z;toDate=2026-05- |
| 18.04.2026 | 00:18:33.813 | GET | /graphql/execute.json/realmadridmastersite/news-section-detail-assembly%3bpath=%252Fcontent%252Fdam% |
| 18.04.2026 | 00:19:02.454 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 18.04.2026 | 00:19:02.500 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 18.04.2026 | 00:19:02.542 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 18.04.2026 | 00:20:44.544 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 18.04.2026 | 00:20:44.668 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |

## Recent Warnings (sample)
| Date | Time | Class | Message |
|------|------|-------|--------|
| 18.04.2026 | 00:00:01.326 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.search.impl.builder.Roo |
| 18.04.2026 | 00:00:01.327 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.search.impl.builder.Roo |
| 18.04.2026 | 00:00:01.328 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.search.impl.builder.Roo |
| 18.04.2026 | 00:00:01.328 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.search.impl.builder.Roo |
| 18.04.2026 | 00:00:01.329 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.tagging.impl.JcrTagImpl |
| 18.04.2026 | 00:00:01.329 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.tagging.impl.JcrTagImpl |
| 18.04.2026 | 00:00:01.330 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.tagging.impl.JcrTagImpl |
| 18.04.2026 | 00:00:01.330 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.tagging.impl.JcrTagImpl |
| 18.04.2026 | 00:00:01.330 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.tagging.impl.JcrTagImpl |
| 18.04.2026 | 00:00:01.330 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.tagging.impl.JcrTagImpl |
| 18.04.2026 | 00:00:01.330 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.tagging.impl.JcrTagImpl |
| 18.04.2026 | 00:00:01.330 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.tagging.impl.JcrTagImpl |
| 18.04.2026 | 00:00:01.331 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.tagging.impl.JcrTagImpl |
| 18.04.2026 | 00:00:01.331 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.tagging.impl.JcrTagImpl |
| 18.04.2026 | 00:00:01.331 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.tagging.impl.JcrTagImpl |
| 18.04.2026 | 00:00:01.331 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.tagging.impl.JcrTagImpl |
| 18.04.2026 | 00:00:02.388 | GET | /graphql/execute.json/areavip/eventList%3bfromDate=2026-04-18T00:00%3btoDate=2027-04-18T00:00%3b.jso |
| 18.04.2026 | 00:00:02.404 | GET | /graphql/execute.json/areavip/eventList%3bfromDate=2026-04-18T00:00%3btoDate=2027-04-18T00:00%3b.jso |
| 18.04.2026 | 00:00:06.287 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 18.04.2026 | 00:00:06.288 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 18.04.2026 | 00:00:06.310 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.search.impl.builder.Roo |
| 18.04.2026 | 00:00:06.311 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.search.impl.builder.Roo |
| 18.04.2026 | 00:00:06.312 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.tagging.impl.JcrTagImpl |
| 18.04.2026 | 00:00:06.313 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 18.04.2026 | 00:00:06.313 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.tagging.impl.JcrTagImpl |
| 18.04.2026 | 00:00:06.313 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.tagging.impl.JcrTagImpl |
| 18.04.2026 | 00:00:06.313 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.tagging.impl.JcrTagImpl |
| 18.04.2026 | 00:00:06.314 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.tagging.impl.JcrTagImpl |
| 18.04.2026 | 00:00:06.314 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.tagging.impl.JcrTagImpl |
| 18.04.2026 | 00:00:06.314 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.tagging.impl.JcrTagImpl |
| 18.04.2026 | 00:00:06.315 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.tagging.impl.JcrTagImpl |
| 18.04.2026 | 00:00:06.315 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.tagging.impl.JcrTagImpl |
| 18.04.2026 | 00:00:06.315 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.tagging.impl.JcrTagImpl |
| 18.04.2026 | 00:00:06.316 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.tagging.impl.JcrTagImpl |
| 18.04.2026 | 00:00:06.316 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.tagging.impl.JcrTagImpl |
| 18.04.2026 | 00:00:06.388 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 18.04.2026 | 00:00:06.388 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 18.04.2026 | 00:00:06.390 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 18.04.2026 | 00:00:06.578 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 18.04.2026 | 00:00:06.604 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 18.04.2026 | 00:00:06.621 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 18.04.2026 | 00:00:06.626 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 18.04.2026 | 00:00:06.636 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 18.04.2026 | 00:00:06.669 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 18.04.2026 | 00:00:06.920 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 18.04.2026 | 00:00:06.920 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 18.04.2026 | 00:00:06.925 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 18.04.2026 | 00:00:06.992 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 18.04.2026 | 00:00:07.015 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 18.04.2026 | 00:00:07.025 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
