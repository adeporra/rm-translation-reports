# AEM PROD Publish Error Report — 2026-04-14
Report date: 2026-04-14
Generated from aemerror.log — general error validation.
## Summary
- **ERROR**: 712
- **WARN**: 93712
## By Class
| Class | ERROR | WARN |
|-------|-------|------|
| org.apache.jackrabbit.vault.fs.io.ImportOptions | 0 | 40397 |
| com.adobe.cq.updateprocessor.impl.ProcessorUtils | 0 | 30220 |
| GET | 681 | 14369 |
| com.adobe.granite.workflow.core.WorkflowSessionImpl | 0 | 5506 |
| com.adobe.cq.dam.cfm.graphql.ModelManagerImpl | 0 | 2591 |
| org.apache.felix.webconsole | 0 | 224 |
| org.apache.felix.hc.core.impl.executor.HealthCheckExecutorImpl | 0 | 109 |
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
| io.prometheus.client.dropwizard.DropwizardExports | 0 | 9 |
| com.adobe.granite.maintenance.impl.MaintenanceTaskInfoImpl | 0 | 9 |
| org.apache.jackrabbit.oak.plugins.index.lucene.IndexCopier | 0 | 8 |
| org.apache.jackrabbit.oak.plugins.index.lucene.directory.CopyOnReadDirectory | 0 | 8 |
| com.azure.core.http.netty.implementation.Utility | 0 | 7 |
| org.apache.jackrabbit.oak.plugins.index.elastic.query.inference.InferenceIndexConfig | 0 | 7 |
| com.adobe.granite.workflow.console.generate.WorkflowModelGeneratorImpl | 0 | 7 |
| org.apache.jackrabbit.oak.jcr.lock.LockDeprecation | 0 | 7 |
| com.day.cq.commons.servlets.AbstractListServlet | 0 | 7 |
| com.day.crx.sling.server.impl.jmx.SecureContentRepositoryAccess | 0 | 6 |
| Events.Framework.com.adobe.cq.dam.cq-dam-processor-nui | 3 | 0 |
| org.apache.sling.commons.scheduler.impl.QuartzScheduler | 3 | 0 |
| ROOT | 1 | 0 |
| org.apache.jackrabbit.oak.plugins.index.AsyncCheckpointCreator | 0 | 1 |
| com.adobe.granite.queries.impl.hc.QueryLimitsHealthCheck | 0 | 1 |
| com.adobe.cq.assetcompute.impl.smartcrop.CreateCropAssetComputeService | 0 | 1 |
| com.adobe.cq.assetcompute.impl.smartcrop.CreateCropAssetComputeEventHandler | 0 | 1 |
| com.adobe.cq.assetcompute.impl.connection.ConnectionServiceImpl | 0 | 1 |
| [c7b36968-8b7e-40ec-ab8f-01255b12b9c8] | 0 | 1 |
| [c59b0115-98da-4723-b5af-391642853771] | 0 | 1 |
| [4b90674c-c997-47cc-9b5f-fdd82245c36f] | 0 | 1 |
| [1d8808d9-494a-4c88-a986-1f5ae6cac13a] | 0 | 1 |
| [1476d722-afa6-4735-9dc0-4f24357c269d] | 0 | 1 |
| [c4d47471-eb92-4452-85c7-57056a7958db] | 0 | 1 |
| [d3de9d6a-b3a6-4368-95f0-1b3c059d8933] | 0 | 1 |
| [b9129cd2-3a01-4c22-ab43-c07f1a3430d7] | 0 | 1 |
| [d74a1981-32ef-481d-9fc8-5c5d0074f7e7] | 0 | 1 |
| [ded66a26-7133-40b1-81e6-a585b4e30e69] | 0 | 1 |
| [546eee98-b116-46ab-a333-7a681e3d25e0] | 0 | 1 |
| [1167fedb-8994-400d-aba3-9a200e0dd61f] | 0 | 1 |
| [cea0fe7a-6fc1-49b4-b783-1367d2e552ba] | 0 | 1 |

## Recent Errors (sample)
| Date | Time | Class | Message |
|------|------|-------|--------|
| 15.04.2026 | 00:00:00.065 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [672] |
| 15.04.2026 | 00:00:00.065 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 15.04.2026 | 00:00:00.098 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [672] |
| 15.04.2026 | 00:00:00.098 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 15.04.2026 | 00:00:00.099 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [672] |
| 15.04.2026 | 00:00:00.100 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 15.04.2026 | 00:00:00.120 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 15.04.2026 | 00:00:00.120 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [672] |
| 15.04.2026 | 00:00:00.124 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 15.04.2026 | 00:00:00.124 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [672] |
| 15.04.2026 | 00:00:00.153 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [672] |
| 15.04.2026 | 00:00:00.153 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 15.04.2026 | 00:00:19.158 | GET | /graphql/execute.json/realmadridmastersite/diaryV2;fromDate=2026-04-15T00:00:00.000Z;toDate=2026-06- |
| 15.04.2026 | 00:00:19.227 | GET | /graphql/execute.json/realmadridmastersite/news-section-detail-assembly%3bpath=%252Fcontent%252Fdam% |
| 15.04.2026 | 00:04:12.880 | GET | /content/dam/portals/realmadrid-com/es-es/projectfoundation/proyectosfundacion-espana/escuela-de-fut |
| 15.04.2026 | 00:04:13.820 | GET | /content/dam/portals/realmadrid-com/es-es/projectfoundation/proyectosfundacion-espana/escuela-de-fut |
| 15.04.2026 | 00:04:14.065 | GET | /content/dam/portals/realmadrid-com/es-es/projectfoundation/proyectosfundacion-espana/escuela-de-fut |
| 15.04.2026 | 00:09:28.327 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 15.04.2026 | 00:09:28.398 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 15.04.2026 | 00:09:28.467 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 15.04.2026 | 00:11:09.501 | GET | /graphql/execute.json/realmadridmastersite/diaryV2%3bfromDate=2026-04-14T23:00:00.000Z%3btoDate=2026 |
| 15.04.2026 | 00:11:41.738 | GET | /content/dam/portals/realmadrid-com/fr-fr/news/generic/2026/04/06/videos/060426%20RMTV%20WEB%20TOTAL |
| 15.04.2026 | 00:17:22.874 | GET | /graphql/execute.json/realmadridmastersite/news-section-detail-assembly%3bpath=%252Fcontent%252Fdam% |
| 15.04.2026 | 00:20:47.398 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 15.04.2026 | 00:20:47.399 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.servlets.re |
| 15.04.2026 | 00:20:47.400 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.servlets.re |
| 15.04.2026 | 00:20:47.400 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 15.04.2026 | 00:20:47.400 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 15.04.2026 | 00:20:47.683 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 15.04.2026 | 00:20:47.684 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.servlets.re |
| 15.04.2026 | 00:20:47.684 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.servlets.re |
| 15.04.2026 | 00:20:47.685 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 15.04.2026 | 00:20:47.685 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 15.04.2026 | 00:20:48.018 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 15.04.2026 | 00:20:48.020 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.servlets.re |
| 15.04.2026 | 00:20:48.020 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.servlets.re |
| 15.04.2026 | 00:20:48.021 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 15.04.2026 | 00:20:48.021 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 15.04.2026 | 00:22:30.281 | GET | /graphql/execute.json/realmadridmastersite/news-section-detail-assembly%3bpath=%252Fcontent%252Fdam% |
| 15.04.2026 | 00:23:43.048 | GET | /graphql/execute.json/realmadridmastersite/diaryV2;fromDate=2026-04-06T08:00:00.000Z;toDate=2026-06- |
| 15.04.2026 | 00:24:29.926 | GET | /graphql/execute.json/realmadridmastersite/diaryV2;fromDate=2026-04-15T00:00:00.000Z;toDate=2026-06- |
| 15.04.2026 | 00:26:47.360 | GET | /graphql/execute.json/realmadridmastersite/diaryV2;fromDate=2026-04-06T08:00:00.000Z;toDate=2026-06- |
| 15.04.2026 | 00:28:40.663 | GET | /content/dam/portals/realmadrid-com/en-us/news/generic/2026/03/28/videos/240326%20S7%20WEB%20CALENDA |
| 15.04.2026 | 00:31:41.907 | GET | /graphql/execute.json/realmadridmastersite/news-section-detail-assembly%3bpath=%252Fcontent%252Fdam% |
| 15.04.2026 | 00:33:16.349 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 15.04.2026 | 00:33:16.351 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 15.04.2026 | 00:33:16.351 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.servlets.re |
| 15.04.2026 | 00:33:16.351 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.servlets.re |
| 15.04.2026 | 00:33:16.352 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |
| 15.04.2026 | 00:33:17.791 | GET | /content/sling/app-servlets/realmadrid/legendary-players.json HTTP/1.1] org.apache.sling.engine.impl |

## Recent Warnings (sample)
| Date | Time | Class | Message |
|------|------|-------|--------|
| 15.04.2026 | 00:00:02.024 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.search.impl.builder.Roo |
| 15.04.2026 | 00:00:02.025 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.search.impl.builder.Roo |
| 15.04.2026 | 00:00:02.026 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.search.impl.builder.Roo |
| 15.04.2026 | 00:00:02.028 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.tagging.impl.JcrTagImpl |
| 15.04.2026 | 00:00:02.028 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.tagging.impl.JcrTagImpl |
| 15.04.2026 | 00:00:02.028 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.tagging.impl.JcrTagImpl |
| 15.04.2026 | 00:00:02.028 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.tagging.impl.JcrTagImpl |
| 15.04.2026 | 00:00:02.029 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.tagging.impl.JcrTagImpl |
| 15.04.2026 | 00:00:02.029 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.tagging.impl.JcrTagImpl |
| 15.04.2026 | 00:00:02.029 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.tagging.impl.JcrTagImpl |
| 15.04.2026 | 00:00:02.029 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.tagging.impl.JcrTagImpl |
| 15.04.2026 | 00:00:02.029 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.tagging.impl.JcrTagImpl |
| 15.04.2026 | 00:00:02.029 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.tagging.impl.JcrTagImpl |
| 15.04.2026 | 00:00:02.030 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.tagging.impl.JcrTagImpl |
| 15.04.2026 | 00:00:02.030 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.tagging.impl.JcrTagImpl |
| 15.04.2026 | 00:00:04.393 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 15.04.2026 | 00:00:04.405 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 15.04.2026 | 00:00:04.408 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 15.04.2026 | 00:00:04.418 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 15.04.2026 | 00:00:04.506 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 15.04.2026 | 00:00:04.532 | GET | /graphql/execute.json/areavip/eventList%3bfromDate=2026-04-15T00:00%3btoDate=2027-04-15T00:00%3b.jso |
| 15.04.2026 | 00:00:04.543 | GET | /graphql/execute.json/areavip/eventList%3bfromDate=2026-04-15T00:00%3btoDate=2027-04-15T00:00%3b.jso |
| 15.04.2026 | 00:00:04.599 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 15.04.2026 | 00:00:04.647 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 15.04.2026 | 00:00:04.703 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 15.04.2026 | 00:00:04.709 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 15.04.2026 | 00:00:04.710 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 15.04.2026 | 00:00:04.721 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 15.04.2026 | 00:00:04.732 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 15.04.2026 | 00:00:04.888 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 15.04.2026 | 00:00:04.898 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 15.04.2026 | 00:00:04.900 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 15.04.2026 | 00:00:04.926 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 15.04.2026 | 00:00:05.103 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 15.04.2026 | 00:00:05.104 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 15.04.2026 | 00:00:05.106 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 15.04.2026 | 00:00:05.108 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 15.04.2026 | 00:00:05.119 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 15.04.2026 | 00:00:05.174 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 15.04.2026 | 00:00:05.193 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 15.04.2026 | 00:00:05.278 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 15.04.2026 | 00:00:05.285 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.search.impl.builder.Roo |
| 15.04.2026 | 00:00:05.286 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.search.impl.builder.Roo |
| 15.04.2026 | 00:00:05.287 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.search.impl.builder.Roo |
| 15.04.2026 | 00:00:05.288 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.tagging.impl.JcrTagImpl |
| 15.04.2026 | 00:00:05.289 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.tagging.impl.JcrTagImpl |
| 15.04.2026 | 00:00:05.289 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.tagging.impl.JcrTagImpl |
| 15.04.2026 | 00:00:05.289 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.tagging.impl.JcrTagImpl |
| 15.04.2026 | 00:00:05.290 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.tagging.impl.JcrTagImpl |
| 15.04.2026 | 00:00:05.290 | GET | /content/sling/app-servlets/realmadrid/news-filter.json HTTP/1.1] com.day.cq.tagging.impl.JcrTagImpl |
