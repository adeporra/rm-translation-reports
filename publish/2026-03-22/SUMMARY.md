# AEM PROD Publish Error Report — 2026-03-22
Report date: 2026-03-22
Generated from aemerror.log — general error validation.
## Summary
- **ERROR**: 1139
- **WARN**: 169998
## By Class
| Class | ERROR | WARN |
|-------|-------|------|
| org.apache.jackrabbit.vault.fs.io.ImportOptions | 0 | 95161 |
| com.adobe.cq.updateprocessor.impl.ProcessorUtils | 0 | 43723 |
| GET | 1000 | 13057 |
| com.adobe.granite.workflow.core.WorkflowSessionImpl | 0 | 12655 |
| com.adobe.cq.dam.cfm.graphql.ModelManagerImpl | 0 | 4443 |
| org.apache.felix.webconsole | 0 | 329 |
| org.apache.felix.hc.core.impl.executor.HealthCheckExecutorImpl | 0 | 131 |
| org.apache.felix.configadmin.plugin.interpolation.InterpolationConfigurationPlugin | 0 | 75 |
| com.adobe.granite.ims.yamlloader.ImsYamlLoader | 0 | 48 |
| com.realmadridclubdefutbol.core.util.ResourceUtils | 38 | 0 |
| com.adobe.cq.dam.assethandler.internal.events.consumer.impl.AssetBatchDeliveryConsumerImpl | 0 | 36 |
| LogService.org.apache.felix.eventadmin | 33 | 1 |
| com.adobe.granite.repository.impl.SystemPrincipalsValidation | 0 | 24 |
| com.day.cq.commons.impl.PredicateProviderImpl | 0 | 24 |
| com.adobe.cq.wcm.translation.impl.utils.I18nUtils | 0 | 24 |
| com.adobe.granite.probes.impl.K8SProbes | 0 | 23 |
| org.apache.jackrabbit.vault.fs.io.AutoSave | 21 | 0 |
| org.apache.jackrabbit.vault.fs.io.Importer | 0 | 21 |
| org.apache.sling.resourceresolver.impl.VanityPathConfigurer | 0 | 18 |
| com.day.cq.dam.handler.gibson.fontmanager.impl.FontManagerServiceImpl | 0 | 18 |
| com.adobe.granite.maintenance.impl.MaintenanceTaskInfoImpl | 0 | 18 |
| com.day.crx.sling.server.impl.jmx.SecureContentRepositoryAccess | 0 | 14 |
| io.prometheus.client.dropwizard.DropwizardExports | 0 | 13 |
| org.apache.jackrabbit.oak.jcr.lock.LockDeprecation | 0 | 12 |
| com.day.cq.commons.servlets.AbstractListServlet | 0 | 12 |
| com.adobe.granite.workflow.console.generate.WorkflowModelGeneratorImpl | 0 | 12 |
| com.day.cq.dam.core.impl.malware.QuarantineServiceImpl | 0 | 12 |
| org.apache.sling.commons.scheduler.impl.QuartzScheduler | 9 | 0 |
| Events.Framework.com.adobe.cq.dam.cq-dam-processor-nui | 9 | 0 |
| com.adobe.granite.queries.impl.hc.QueryLimitsHealthCheck | 0 | 9 |
| com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | 8 | 0 |
| com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | 8 | 0 |
| com.adobe.granite.workflow.core.job.JobHandler | 8 | 0 |
| com.azure.core.http.netty.implementation.Utility | 0 | 8 |
| org.apache.jackrabbit.oak.plugins.index.elastic.query.inference.InferenceIndexConfig | 0 | 8 |
| org.apache.sling.event.impl.jobs.queues.JobQueueImpl.Granite | 0 | 8 |
| com.day.cq.audit.impl.AuditLogMaintenanceTask | 0 | 6 |
| org.apache.jackrabbit.oak.plugins.index.lucene.IndexCopier | 0 | 5 |
| org.apache.jackrabbit.oak.plugins.index.lucene.directory.CopyOnReadDirectory | 0 | 5 |
| com.adobe.cq.assetcompute.impl.connection.ConnectionServiceImpl | 0 | 5 |
| org.apache.jackrabbit.oak.plugins.index.AsyncCheckpointCreator | 0 | 4 |
| com.adobe.cq.assetcompute.impl.assetpreprocessor.malware.MalwareScanAssetComputeEventHandler | 1 | 1 |
| ROOT | 2 | 0 |
| [14cc3fba-fc5c-49d9-ab2e-c0ab96f199cf] | 0 | 2 |
| org.apache.jackrabbit.oak.plugins.index.lucene.directory.IndexSanityChecker | 0 | 2 |
| com.adobe.cq.assetcompute.impl.smartcrop.CreateCropAssetComputeService | 0 | 2 |
| com.adobe.cq.assetcompute.impl.smartcrop.CreateCropAssetComputeEventHandler | 0 | 2 |
| [1fda6fa7-3bf8-4455-ab58-6a569a99a5ae] | 0 | 2 |
| [e3ee1c34-9ca5-4b9c-967d-354bc8e835bb] | 0 | 2 |
| org.apache.sling.distribution.journal.impl.subscriber.DistributionSubscriber | 1 | 0 |
| [20c506e2-15b0-4a53-992a-304da9c77696] | 1 | 0 |
| [41e2d567-b8d3-48b9-883f-35f366f506aa] | 0 | 1 |
| [d17d4e4d-1fbd-455c-8ba3-e45d8b1a19d2] | 0 | 1 |
| [8c408953-40eb-4993-9b2e-eb1cf26c1981] | 0 | 1 |
| [0f031284-1fe6-4c20-9d61-3eca7f0b8bae] | 0 | 1 |
| [89c71054-d8d5-450f-93f7-ecb073c51319] | 0 | 1 |
| [f5d908fd-1e3e-4ca0-8113-362d7e50f639] | 0 | 1 |
| [792d0b34-24ae-4225-9073-78f4adbf63a3] | 0 | 1 |
| [bbc312d7-838a-48dc-834f-f0deff18e5d0] | 0 | 1 |
| [6ec46c62-4aaa-4b08-88df-d370f4b0067b] | 0 | 1 |
| [6dd197d3-b76b-4a67-acb8-6bb9c1de9daf] | 0 | 1 |
| [4e7dfe79-27db-4901-ac49-a91966a30e1b] | 0 | 1 |
| [b57661e4-3b48-48c6-ad54-54671f70d92f] | 0 | 1 |
| [0ea0ff86-4b7f-4c5f-b7b8-c20c245212c4] | 0 | 1 |
| [51c2ab6e-34ca-4b00-a0cb-44f39979d0ce] | 0 | 1 |
| [74606549-2bdb-4a00-936a-ee604ef1de4a] | 0 | 1 |
| [fe466893-9a50-40e1-96fd-e9749776235c] | 0 | 1 |
| [57d6638a-3786-4e02-9bcd-4e7ec6e65a74] | 0 | 1 |
| [d5a14e3b-9dee-4611-9bfa-bf37697147e5] | 0 | 1 |
| [b66e8a84-f09c-4188-9029-7358557eaed8] | 0 | 1 |
| [60f2b999-1dd1-4c92-abf7-73bc81b381f2] | 0 | 1 |
| [761f6d7d-6a56-46ac-ab90-d4f6214d08d3] | 0 | 1 |
| [e0275206-5f28-4d95-b71b-28447ed6614c] | 0 | 1 |
| [bed3170e-a315-43ff-af7e-bf35d0ed25c5] | 0 | 1 |

## Recent Errors (sample)
| Date | Time | Class | Message |
|------|------|-------|--------|
| 23.03.2026 | 00:00:00.088 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [670] |
| 23.03.2026 | 00:00:00.088 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 23.03.2026 | 00:00:00.105 | com.realmadridclubdefutbol.core.consumers.RMAPIMatchesImportConsumer | No Active squads found, check if squads are active and properly configured |
| 23.03.2026 | 00:00:00.105 | com.realmadridclubdefutbol.core.services.impl.ContentFragmentServiceImpl | Exception occurred: Cannot derive user name for bundle aem-realmadridclubdefutbol-project.core [670] |
| 23.03.2026 | 00:00:26.333 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 23.03.2026 | 00:00:26.396 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 23.03.2026 | 00:00:26.423 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 23.03.2026 | 00:00:53.774 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 23.03.2026 | 00:00:53.820 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 23.03.2026 | 00:00:53.861 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 23.03.2026 | 00:00:55.244 | GET | /graphql/execute.json/realmadridmastersite/diaryV2;fromDate=2026-03-23T00:00:00.000Z;toDate=2026-06- |
| 23.03.2026 | 00:03:10.829 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 23.03.2026 | 00:03:10.873 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 23.03.2026 | 00:03:10.916 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 23.03.2026 | 00:03:20.245 | org.apache.sling.commons.scheduler.impl.QuartzScheduler | Exception during job execution of job 'org.apache.jackrabbit.oak.plugins.index.lucene.directory.Luce |
| 23.03.2026 | 00:05:52.059 | GET | /graphql/execute.json/realmadridmastersite/news-section-detail-assembly%3bpath=%252Fcontent%252Fdam% |
| 23.03.2026 | 00:05:54.017 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 23.03.2026 | 00:05:54.062 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 23.03.2026 | 00:05:54.070 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 23.03.2026 | 00:05:54.105 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 23.03.2026 | 00:05:54.204 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 23.03.2026 | 00:05:54.247 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 23.03.2026 | 00:06:50.280 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 23.03.2026 | 00:06:50.285 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 23.03.2026 | 00:06:50.324 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 23.03.2026 | 00:06:50.327 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 23.03.2026 | 00:06:50.365 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 23.03.2026 | 00:06:50.370 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 23.03.2026 | 00:08:07.477 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 23.03.2026 | 00:08:07.483 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 23.03.2026 | 00:08:07.538 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 23.03.2026 | 00:08:07.583 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 23.03.2026 | 00:08:07.615 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 23.03.2026 | 00:08:07.655 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 23.03.2026 | 00:13:12.184 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 23.03.2026 | 00:13:12.249 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 23.03.2026 | 00:13:12.295 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 23.03.2026 | 00:14:00.044 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 23.03.2026 | 00:14:00.092 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 23.03.2026 | 00:14:00.140 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 23.03.2026 | 00:17:14.566 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 23.03.2026 | 00:17:14.609 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 23.03.2026 | 00:17:14.653 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 23.03.2026 | 00:18:30.468 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 23.03.2026 | 00:18:30.470 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 23.03.2026 | 00:18:30.598 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 23.03.2026 | 00:18:30.602 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 23.03.2026 | 00:18:30.643 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 23.03.2026 | 00:18:30.647 | GET | /content/dam/common/statics/public-content/internet/web/rm-spa-profile-area/images/home/home-hero-me |
| 23.03.2026 | 00:18:44.534 | LogService.org.apache.felix.eventadmin | Service [com.adobe.cq.updateprocessor.impl.ReplicationListener,6182, [org.osgi.service.event.EventHa |

## Recent Warnings (sample)
| Date | Time | Class | Message |
|------|------|-------|--------|
| 22.03.2026 | 23:59:11.379 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 767ms to become available through index. |
| 22.03.2026 | 23:59:11.381 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1582ms to become available through index. |
| 22.03.2026 | 23:59:11.550 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1574ms to become available through index. |
| 22.03.2026 | 23:59:11.570 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 768ms to become available through index. |
| 22.03.2026 | 23:59:11.861 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1578ms to become available through index. |
| 22.03.2026 | 23:59:12.024 | org.apache.jackrabbit.oak.plugins.index.AsyncCheckpointCreator | [elastic-pit] Unable to delete checkpoint 79e1cb0c-01c2-4e18-9590-e8301a622f5e. Removal will be atte |
| 22.03.2026 | 23:59:12.616 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 782ms to become available through index. |
| 22.03.2026 | 23:59:12.658 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1572ms to become available through index. |
| 22.03.2026 | 23:59:12.669 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 771ms to become available through index. |
| 22.03.2026 | 23:59:13.186 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1577ms to become available through index. |
| 22.03.2026 | 23:59:13.629 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1570ms to become available through index. |
| 22.03.2026 | 23:59:14.035 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1570ms to become available through index. |
| 22.03.2026 | 23:59:14.282 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1577ms to become available through index. |
| 22.03.2026 | 23:59:14.328 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1586ms to become available through index. |
| 22.03.2026 | 23:59:14.437 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1618ms to become available through index. |
| 22.03.2026 | 23:59:14.600 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 768ms to become available through index. |
| 22.03.2026 | 23:59:14.831 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1581ms to become available through index. |
| 22.03.2026 | 23:59:15.126 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 777ms to become available through index. |
| 22.03.2026 | 23:59:15.660 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1573ms to become available through index. |
| 22.03.2026 | 23:59:15.947 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1578ms to become available through index. |
| 22.03.2026 | 23:59:16.061 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1579ms to become available through index. |
| 22.03.2026 | 23:59:16.216 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1573ms to become available through index. |
| 22.03.2026 | 23:59:16.490 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1572ms to become available through index. |
| 22.03.2026 | 23:59:16.763 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 776ms to become available through index. |
| 22.03.2026 | 23:59:16.777 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1582ms to become available through index. |
| 22.03.2026 | 23:59:17.017 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 775ms to become available through index. |
| 22.03.2026 | 23:59:17.310 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1580ms to become available through index. |
| 22.03.2026 | 23:59:17.582 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 779ms to become available through index. |
| 22.03.2026 | 23:59:17.717 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1573ms to become available through index. |
| 22.03.2026 | 23:59:18.121 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1572ms to become available through index. |
| 22.03.2026 | 23:59:18.395 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1577ms to become available through index. |
| 22.03.2026 | 23:59:18.516 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 769ms to become available through index. |
| 22.03.2026 | 23:59:18.640 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1574ms to become available through index. |
| 22.03.2026 | 23:59:19.019 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1569ms to become available through index. |
| 22.03.2026 | 23:59:19.244 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1578ms to become available through index. |
| 22.03.2026 | 23:59:19.730 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1577ms to become available through index. |
| 22.03.2026 | 23:59:20.013 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1583ms to become available through index. |
| 22.03.2026 | 23:59:20.058 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 774ms to become available through index. |
| 22.03.2026 | 23:59:20.168 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1571ms to become available through index. |
| 22.03.2026 | 23:59:20.257 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1571ms to become available through index. |
| 22.03.2026 | 23:59:21.271 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1573ms to become available through index. |
| 22.03.2026 | 23:59:21.438 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1573ms to become available through index. |
| 22.03.2026 | 23:59:21.632 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1577ms to become available through index. |
| 22.03.2026 | 23:59:21.674 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1577ms to become available through index. |
| 22.03.2026 | 23:59:21.852 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1571ms to become available through index. |
| 22.03.2026 | 23:59:22.192 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 1574ms to become available through index. |
| 22.03.2026 | 23:59:22.237 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 775ms to become available through index. |
| 22.03.2026 | 23:59:22.288 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 769ms to become available through index. |
| 22.03.2026 | 23:59:22.477 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 773ms to become available through index. |
| 22.03.2026 | 23:59:22.530 | com.adobe.cq.updateprocessor.impl.ProcessorUtils | Deferred job availability; took 818ms to become available through index. |
