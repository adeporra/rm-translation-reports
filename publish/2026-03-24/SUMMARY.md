# AEM PROD Publish Error Report — 2026-03-24
Report date: 2026-03-24
Generated from aemerror.log — general error validation.
## Summary
- **ERROR**: 581
- **WARN**: 88672
## By Class
| Class | ERROR | WARN |
|-------|-------|------|
| org.apache.jackrabbit.vault.fs.io.ImportOptions | 0 | 40114 |
| com.adobe.cq.updateprocessor.impl.ProcessorUtils | 0 | 30508 |
| GET | 542 | 9327 |
| com.adobe.granite.workflow.core.WorkflowSessionImpl | 0 | 5508 |
| com.adobe.cq.dam.cfm.graphql.ModelManagerImpl | 0 | 2578 |
| org.apache.felix.webconsole | 0 | 224 |
| org.apache.felix.hc.core.impl.executor.HealthCheckExecutorImpl | 0 | 67 |
| org.apache.felix.configadmin.plugin.interpolation.InterpolationConfigurationPlugin | 0 | 63 |
| com.adobe.granite.ims.yamlloader.ImsYamlLoader | 0 | 28 |
| com.adobe.cq.dam.assethandler.internal.events.consumer.impl.AssetBatchDeliveryConsumerImpl | 0 | 21 |
| com.adobe.granite.probes.impl.K8SProbes | 0 | 14 |
| com.day.cq.commons.impl.PredicateProviderImpl | 0 | 14 |
| org.apache.sling.resourceresolver.impl.VanityPathConfigurer | 0 | 14 |
| com.day.cq.dam.handler.gibson.fontmanager.impl.FontManagerServiceImpl | 0 | 14 |
| com.adobe.granite.repository.impl.SystemPrincipalsValidation | 0 | 14 |
| com.adobe.cq.wcm.translation.impl.utils.I18nUtils | 0 | 14 |
| com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | 12 | 0 |
| com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | 12 | 0 |
| io.prometheus.client.dropwizard.DropwizardExports | 0 | 12 |
| com.adobe.granite.maintenance.impl.MaintenanceTaskInfoImpl | 0 | 9 |
| Events.Framework.com.adobe.cq.dam.cq-dam-processor-nui | 7 | 0 |
| com.azure.core.http.netty.implementation.Utility | 0 | 7 |
| org.apache.jackrabbit.oak.plugins.index.elastic.query.inference.InferenceIndexConfig | 0 | 7 |
| com.adobe.granite.queries.impl.hc.QueryLimitsHealthCheck | 0 | 7 |
| com.adobe.granite.workflow.console.generate.WorkflowModelGeneratorImpl | 0 | 7 |
| org.apache.jackrabbit.oak.jcr.lock.LockDeprecation | 0 | 7 |
| com.day.cq.commons.servlets.AbstractListServlet | 0 | 7 |
| com.day.cq.dam.core.impl.malware.QuarantineServiceImpl | 0 | 7 |
| com.day.crx.sling.server.impl.jmx.SecureContentRepositoryAccess | 0 | 7 |
| org.apache.sling.commons.scheduler.impl.QuartzScheduler | 6 | 0 |
| com.day.cq.wcm.workflow.impl.WcmWorkflowServiceImpl | 0 | 6 |
| org.apache.jackrabbit.oak.plugins.index.lucene.IndexCopier | 0 | 4 |
| org.apache.jackrabbit.oak.plugins.index.lucene.directory.CopyOnReadDirectory | 0 | 4 |
| org.apache.jackrabbit.oak.plugins.index.AsyncCheckpointCreator | 0 | 2 |
| com.adobe.cq.assetcompute.impl.connection.ConnectionServiceImpl | 0 | 2 |
| Events.Framework.org.apache.felix.log | 1 | 0 |
| ROOT | 1 | 0 |
| [67a54ea3-f3c4-4b1a-a72c-7d24f942e58a] | 0 | 1 |
| [521ff24f-998d-46ae-b6bf-51e38060c55f] | 0 | 1 |
| [2f4b9eec-c639-4e10-b7d8-c94e826532ae] | 0 | 1 |
| [7d3d4bf4-bcbd-43c0-87a3-0cb74ef257ee] | 0 | 1 |
| [7a014a9e-6104-476a-997a-b1ccc59f66a3] | 0 | 1 |
| [631c3236-6718-4808-b4eb-49a5600d8c5a] | 0 | 1 |
| [7c7cdda1-c9ee-43f8-a92c-3a3f7ad74cd9] | 0 | 1 |
| com.adobe.cq.assetcompute.impl.assetprocessor.AssetProcessorInitService | 0 | 1 |
| com.adobe.cq.assetcompute.impl.assetprocessor.AssetRetryRenditionProcessingService | 0 | 1 |
| com.adobe.cq.assetcompute.impl.assetprocessor.AssetProcessorEventHandler | 0 | 1 |
| com.adobe.cq.assetcompute.impl.smartcrop.CreateCropAssetComputeService | 0 | 1 |
| com.adobe.cq.assetcompute.impl.smartcrop.CreateCropAssetComputeEventHandler | 0 | 1 |
| [f3475ea9-8950-4eed-a1f6-7cf84d804dd8] | 0 | 1 |
| [ed8c2d5f-89bb-4e8b-ba88-97b155901bd9] | 0 | 1 |
| reactor.netty.http.client.HttpClientConnect | 0 | 1 |
| [ebea3210-f456-4ead-8adf-5bc134768b56] | 0 | 1 |
| [a5997eff-1e28-4410-8ce2-4cac4f40e18d] | 0 | 1 |
| [3e841c12-29b6-460c-8d04-df5cb6f652fb] | 0 | 1 |
| [65388c0b-38ce-4db1-a4ca-3aeb80cdfbe0] | 0 | 1 |
| [5901f48a-cac6-4c08-8535-7af2d7e388d9] | 0 | 1 |
| [380ccde2-2c54-41d8-8063-4a64e2341258] | 0 | 1 |
| [a05dc3dc-b345-43e5-8feb-e7abfbd3c905] | 0 | 1 |
| [ddd36f8a-df7e-4378-8dd1-1a29e6ff8a47] | 0 | 1 |
| [7beac5c2-de16-4550-b009-4ac7ea4c7a89] | 0 | 1 |
| [0c131690-bf8d-4ae6-9e4f-1efb1e5e281d] | 0 | 1 |
| [f3ec445e-5d65-4246-a309-48d741a2bd20] | 0 | 1 |
| [5dec6a08-15b3-4e51-a232-cb1c9c438d02] | 0 | 1 |
| [7a1eba3d-8fee-4638-bbd1-71b5042c5942] | 0 | 1 |
| [f6dab500-b250-4fe7-8d94-4edee2fad012] | 0 | 1 |
| [0414c50b-8a6d-4d58-babe-c06987babc95] | 0 | 1 |
| [959d8fe0-3757-4a39-ba91-a2b87d772f41] | 0 | 1 |
| [54610648-da46-4711-bfc9-bdc38f44e5a9] | 0 | 1 |
| [e33a8575-b59f-47e5-9563-38d8d92d9f82] | 0 | 1 |
| [3509ef0d-4fb7-4cec-83ee-565e8b11d872] | 0 | 1 |
| [1ff79125-9c65-4eb9-9d1c-daf54505b66b] | 0 | 1 |
| [ab094c57-f841-44cf-819f-f77cc755f5a8] | 0 | 1 |
| [f86fa03b-6daa-4787-b3fd-966844673a3e] | 0 | 1 |
| [7854a553-9356-41b2-a411-91d4e5c04174] | 0 | 1 |
| [f4c09a9f-3ec4-4598-af60-9b9844aff1de] | 0 | 1 |
| [07048bf1-055b-4067-983e-853170e38e60] | 0 | 1 |
| [585331b1-1f35-47b6-8d59-8495b39fafdd] | 0 | 1 |
| [696a210d-a85b-425d-9a14-5ad64688c233] | 0 | 1 |
| [c3436201-0b5b-41bd-b051-0d33c0b1d339] | 0 | 1 |
| [560a0e24-dd38-464c-a90d-32d059129032] | 0 | 1 |
| [9af310c2-bd49-4b26-b980-700c7260d432] | 0 | 1 |
| [248afae1-f553-4ea3-af3c-fa4017e3efe5] | 0 | 1 |
| [063bb95f-aae5-4328-a19c-17a07e756a2a] | 0 | 1 |
| [8b11df0f-41e7-452d-9a20-267d099ea1af] | 0 | 1 |
| [aafd99b8-89ec-46c9-a791-a2a3c5118d66] | 0 | 1 |
| [3c551ea9-d638-4366-88d3-6f525fd01e2d] | 0 | 1 |
| [778a5849-403b-4782-ba3e-8d761d875344] | 0 | 1 |
| [50a65e95-df1d-4fd5-aa00-4662a4536198] | 0 | 1 |
| org.apache.sling.servlets.resolver.internal.resource.ServletMounter | 0 | 1 |
| [a11c2eeb-3dfd-4ee7-a134-acb1ec606f28] | 0 | 1 |
| [fc5064e7-c482-47eb-9e46-3c450711da1f] | 0 | 1 |

## Recent Errors (sample)
| Date | Time | Class | Message |
|------|------|-------|--------|
| 25.03.2026 | 00:00:00.050 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [654] |
| 25.03.2026 | 00:00:00.050 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 25.03.2026 | 00:00:00.069 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [654] |
| 25.03.2026 | 00:00:00.069 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 25.03.2026 | 00:00:00.098 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [654] |
| 25.03.2026 | 00:00:00.098 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 25.03.2026 | 00:00:00.099 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [654] |
| 25.03.2026 | 00:00:00.100 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 25.03.2026 | 00:00:00.113 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 25.03.2026 | 00:00:00.113 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [654] |
| 25.03.2026 | 00:00:00.154 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [654] |
| 25.03.2026 | 00:00:00.154 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 25.03.2026 | 00:04:51.335 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 25.03.2026 | 00:04:51.350 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 25.03.2026 | 00:04:51.379 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 25.03.2026 | 00:04:51.422 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 25.03.2026 | 00:04:51.476 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 25.03.2026 | 00:04:51.518 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 25.03.2026 | 00:05:36.903 | GET | /graphql/execute.json/estadio/newsListByTagV2;alang=/content/dam/portals/estadio/en-us/;tag=%7b%22_e |
| 25.03.2026 | 00:05:52.447 | GET | /content/dam/portals/realmadrid-com/es-es/core-content/assemblies/pages/generic-pages/madridistas/ve |
| 25.03.2026 | 00:05:52.463 | GET | /content/dam/portals/realmadrid-com/es-es/core-content/assemblies/pages/generic-pages/madridistas/ve |
| 25.03.2026 | 00:05:52.466 | GET | /content/dam/portals/realmadrid-com/es-es/core-content/assemblies/pages/generic-pages/madridistas/ve |
| 25.03.2026 | 00:05:52.587 | GET | /content/dam/portals/realmadrid-com/es-es/core-content/assemblies/pages/generic-pages/madridistas/ve |
| 25.03.2026 | 00:05:52.852 | GET | /content/dam/portals/realmadrid-com/es-es/core-content/assemblies/pages/generic-pages/madridistas/ve |
| 25.03.2026 | 00:05:52.876 | GET | /content/dam/portals/realmadrid-com/es-es/core-content/assemblies/pages/generic-pages/madridistas/ve |
| 25.03.2026 | 00:05:52.966 | GET | /content/dam/portals/realmadrid-com/es-es/core-content/assemblies/pages/generic-pages/madridistas/ve |
| 25.03.2026 | 00:05:52.988 | GET | /content/dam/portals/realmadrid-com/es-es/core-content/assemblies/pages/generic-pages/madridistas/ve |
| 25.03.2026 | 00:05:52.992 | GET | /content/dam/portals/realmadrid-com/es-es/core-content/assemblies/pages/generic-pages/madridistas/ve |
| 25.03.2026 | 00:05:53.103 | GET | /content/dam/portals/realmadrid-com/es-es/core-content/assemblies/pages/generic-pages/madridistas/ve |
| 25.03.2026 | 00:05:53.218 | GET | /content/dam/portals/realmadrid-com/es-es/core-content/assemblies/pages/generic-pages/madridistas/ve |
| 25.03.2026 | 00:05:53.333 | GET | /content/dam/portals/realmadrid-com/es-es/core-content/assemblies/pages/generic-pages/madridistas/ve |
| 25.03.2026 | 00:06:45.620 | org.apache.sling.commons.scheduler.impl.QuartzScheduler | Exception during job execution of job 'org.apache.jackrabbit.oak.plugins.index.lucene.directory.Luce |
| 25.03.2026 | 00:09:19.470 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 25.03.2026 | 00:09:19.502 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 25.03.2026 | 00:09:19.544 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 25.03.2026 | 00:11:50.088 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 25.03.2026 | 00:11:50.094 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 25.03.2026 | 00:11:50.129 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 25.03.2026 | 00:11:50.171 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 25.03.2026 | 00:11:50.224 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 25.03.2026 | 00:11:50.269 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 25.03.2026 | 00:13:29.818 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 25.03.2026 | 00:13:29.958 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 25.03.2026 | 00:13:29.998 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 25.03.2026 | 00:15:04.031 | GET | /content/dam/portals/realmadrid-com/es-es/core-content/assemblies/pages/generic-pages/madridistas/ve |
| 25.03.2026 | 00:15:04.076 | GET | /content/dam/portals/realmadrid-com/es-es/core-content/assemblies/pages/generic-pages/madridistas/ve |
| 25.03.2026 | 00:15:04.076 | GET | /content/dam/portals/realmadrid-com/es-es/core-content/assemblies/pages/generic-pages/madridistas/ve |
| 25.03.2026 | 00:15:04.104 | GET | /content/dam/portals/realmadrid-com/es-es/core-content/assemblies/pages/generic-pages/madridistas/ve |
| 25.03.2026 | 00:15:04.104 | GET | /content/dam/portals/realmadrid-com/es-es/core-content/assemblies/pages/generic-pages/madridistas/ve |
| 25.03.2026 | 00:15:04.125 | GET | /content/dam/portals/realmadrid-com/es-es/core-content/assemblies/pages/generic-pages/madridistas/ve |

## Recent Warnings (sample)
| Date | Time | Class | Message |
|------|------|-------|--------|
| 25.03.2026 | 00:00:05.342 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 25.03.2026 | 00:00:05.359 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 25.03.2026 | 00:00:05.367 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 25.03.2026 | 00:00:05.374 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 25.03.2026 | 00:00:05.397 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 25.03.2026 | 00:00:05.399 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 25.03.2026 | 00:00:05.672 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 25.03.2026 | 00:00:05.677 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 25.03.2026 | 00:00:05.683 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 25.03.2026 | 00:00:05.694 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 25.03.2026 | 00:00:05.777 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 25.03.2026 | 00:00:05.785 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 25.03.2026 | 00:00:05.860 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 25.03.2026 | 00:00:05.895 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 25.03.2026 | 00:00:05.896 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 25.03.2026 | 00:00:05.966 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 25.03.2026 | 00:00:05.997 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 25.03.2026 | 00:00:06.005 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 25.03.2026 | 00:00:06.007 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 25.03.2026 | 00:00:06.007 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 25.03.2026 | 00:00:06.008 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 25.03.2026 | 00:00:06.074 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 25.03.2026 | 00:00:06.098 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 25.03.2026 | 00:00:06.115 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 25.03.2026 | 00:00:06.275 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 25.03.2026 | 00:00:06.312 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 25.03.2026 | 00:00:06.317 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 25.03.2026 | 00:00:06.323 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 25.03.2026 | 00:00:06.399 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 25.03.2026 | 00:00:06.424 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 25.03.2026 | 00:00:06.432 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 25.03.2026 | 00:00:06.437 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 25.03.2026 | 00:00:06.466 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 25.03.2026 | 00:00:06.544 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 25.03.2026 | 00:00:06.558 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 25.03.2026 | 00:00:06.566 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 774ms to become available through index. |
| 25.03.2026 | 00:00:06.590 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 25.03.2026 | 00:00:06.723 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 25.03.2026 | 00:00:06.736 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 25.03.2026 | 00:00:06.739 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 770ms to become available through index. |
| 25.03.2026 | 00:00:06.751 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 25.03.2026 | 00:00:06.752 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 25.03.2026 | 00:00:06.778 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 779ms to become available through index. |
| 25.03.2026 | 00:00:06.845 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 25.03.2026 | 00:00:06.942 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 25.03.2026 | 00:00:06.957 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 25.03.2026 | 00:00:06.984 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 25.03.2026 | 00:00:07.006 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 25.03.2026 | 00:00:07.014 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
| 25.03.2026 | 00:00:07.029 | org.apache.jackrabbit.vault.fs.io.ImportOptions | Patch files are no longer supported for security reasons. Ignoring setPatchKeepInRepo(false) |
