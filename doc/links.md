{% include variables.md %}


<!--== Features and components ==-->
{% capture kaa_features_url %}{{root_url}}Features/{% endcapture %}
[kaa features]: {{kaa_features_url}}


<!-- Device management -->
{% capture feature_device_mgmt_url %}{{kaa_features_url}}Device-management/{% endcapture %}
[identity]: {{feature_device_mgmt_url}}
[device management]: {{feature_device_mgmt_url}}

{% capture epr_url %}{{feature_device_mgmt_url}}EPR/{% endcapture %}
[EPR]:                          {{epr_url}}
[EPR REST API]:                 {{epr_url}}REST-API/
[EPR endpoint POST REST API]:   {{epr_url}}REST-API/#endpoints_post

{% capture epmx_url %}{{feature_device_mgmt_url}}EPMX/{% endcapture %}
[EPMX]: {{epmx_url}}

{% capture cm_url %}{{feature_device_mgmt_url}}CM/{% endcapture %}
[CM]: {{cm_url}}
[CM REST API]:                  {{cm_url}}REST-API/
[CM clients REST API]:          {{cm_url}}REST-API/#clients
[CM certificate POST REST API]: {{cm_url}}REST-API/#clients_certificates_post

{% capture ccm_url %}{{feature_device_mgmt_url}}CCM/{% endcapture %}
[CCM]: {{ccm_url}}


<!-- Communication -->
{% capture feature_communication_url %}{{kaa_features_url}}Communication/{% endcapture %}
[communication]: {{feature_communication_url}}
[1/KP over MQTT topic structure]: {{feature_communication_url}}#mqtt-topic-structure-for-the-kaa-protocol-v1

{% capture kpc_url %}{{feature_communication_url}}KPC/{% endcapture %}
[KPC]: {{kpc_url}}

{% capture epl_url %}{{feature_communication_url}}EPL/{% endcapture %}
[EPL]: {{epl_url}}


<!-- Data collection -->
{% capture feature_data_collection_url %}{{kaa_features_url}}Data-collection/{% endcapture %}
[data collection]: {{feature_data_collection_url}}

{% capture dcx_url %}{{feature_data_collection_url}}DCX/{% endcapture %}
[DCX]: {{dcx_url}}
[DCX metadata enrichment]: {{dcx_url}}Overview/#enriching-data-samples-with-endpoint-metadata

{% capture bcx_url %}{{feature_data_collection_url}}BCX/{% endcapture %}
[BCX]: {{bcx_url}}

{% capture epts_url %}{{feature_data_collection_url}}EPTS/{% endcapture %}
[EPTS]:                                             {{epts_url}}
[EPTS REST API]:                                    {{epts_url}}REST-API/
[EPTS time series PUT REST API]:                    {{epts_url}}REST-API/#applications__applicationname__time_series_data_put
[EPTS time series PUT via app version REST API]:    {{epts_url}}REST-API/#app_versions__appversionname__time_series_data_put
[EPTS time series last REST API]:                   {{epts_url}}REST-API/#applications__applicationname__time_series_last_get
[EPTS time series data REST API]:                   {{epts_url}}REST-API/#applications__applicationname__time_series_data_get
[EPTS time series extraction]:                      {{epts_url}}Configuration/#time-series-extraction
[EPTS time series auto extraction]:                 {{epts_url}}Configuration/#time-series-auto-extraction

{% capture kdca_url %}{{feature_data_collection_url}}KDCA/{% endcapture %}
[KDCA]: {{kdca_url}}

{% capture mdca_url %}{{feature_data_collection_url}}MDCA/{% endcapture %}
[MDCA]: {{mdca_url}}


<!-- Configuration management -->
{% capture feature_config_mgmt_url %}{{kaa_features_url}}Configuration-management/{% endcapture %}
[configuration]: {{feature_config_mgmt_url}}

{% capture cmx_url %}{{feature_config_mgmt_url}}CMX/{% endcapture %}
[CMX]: {{cmx_url}}

{% capture ecr_url %}{{feature_config_mgmt_url}}ECR/{% endcapture %}
[ECR]: {{ecr_url}}
[ECR REST API]: {{ecr_url}}REST-API/


<!-- Commands -->
{% capture feature_commands_url %}{{kaa_features_url}}Command-invocation/{% endcapture %}
[commands]: {{feature_commands_url}}

{% capture cex_url %}{{feature_commands_url}}CEX/{% endcapture %}
[CEX]: {{cex_url}}
[CEX REST API]: {{cex_url}}REST-API/
[CEX REST API POST command]: {{cex_url}}REST-API/#endpoints__endpointid__commands__commandtype__post

{% capture rci_url %}{{feature_commands_url}}RCI/{% endcapture %}
[RCI]: {{rci_url}}
[RCI REST API]: {{rci_url}}REST-API/


<!-- Software updates -->
{% capture feature_ota_url %}{{kaa_features_url}}Software-updates/{% endcapture %}
[ota]: {{feature_ota_url}}

{% capture otao_url %}{{feature_ota_url}}OTAO/{% endcapture %}
[OTAO]: {{otao_url}}
[OTAO REST API]: {{otao_url}}REST-API/


<!-- Visualization -->
{% capture feature_visualization_url %}{{kaa_features_url}}Visualization/{% endcapture %}
[visualization]: {{feature_visualization_url}}

{% capture wd_url %}{{feature_visualization_url}}WD/{% endcapture %}
[WD]: {{wd_url}}


<!-- Infrastructure -->
{% capture feature_infrastructure_url %}{{kaa_features_url}}Infrastructure/{% endcapture %}
[infrastructure]: {{feature_infrastructure_url}}

{% capture tekton_url %}{{feature_infrastructure_url}}TEKTON/{% endcapture %}
[TEKTON]:                               {{tekton_url}}
[TEKTON REST API]:                      {{tekton_url}}REST-API/
[TEKTON applications REST API]:         {{tekton_url}}REST-API/#applications
[TEKTON application create REST API]:   {{tekton_url}}REST-API/#applications_post
[TEKTON app version create REST API]:   {{tekton_url}}REST-API/#applications__appname__app_versions_post
[TEKTON bulk config load REST API]:     {{tekton_url}}REST-API/#app_configs_post


<!-- Multi-tenancy -->
{% capture feature_multi_tenancy_url %}{{kaa_features_url}}Multi-tenancy/{% endcapture %}
[multi-tenancy]: {{feature_multi_tenancy_url}}

{% capture tenant_manager_url %}{{feature_multi_tenancy_url}}TENANT-MANAGER/{% endcapture %}
[Tenant Manager]:          {{tenant_manager_url}}
[Tenant Manager REST API]: {{tenant_manager_url}}REST-API/


<!-- Miscellaneous -->
{% capture feature_miscellaneous_url %}{{kaa_features_url}}Miscellaneous/{% endcapture %}
[misc]: {{feature_miscellaneous_url}}

{% capture tsx_url %}{{feature_miscellaneous_url}}TSX/{% endcapture %}
[TSX]: {{tsx_url}}


<!--== Kaa RFCs ==-->
[RFCs]:     {{rfc_url}}#kaa-rfcs
[1/KP]:     {{rfc_url}}blob/master/0001/README.md
[2/DCP]:    {{rfc_url}}blob/master/0002/README.md
[3/ISM]:    {{rfc_url}}blob/master/0003/README.md
[4/ESP]:    {{rfc_url}}blob/master/0004/README.md
[6/CDTP]:   {{rfc_url}}blob/master/0006/README.md
[7/CMP]:    {{rfc_url}}blob/master/0007/README.md
[8/KPSR]:   {{rfc_url}}blob/master/0008/README.md
[9/ELCE]:   {{rfc_url}}blob/master/0009/README.md
[10/EPMP]:  {{rfc_url}}blob/master/0010/README.md
[11/CEP]:   {{rfc_url}}blob/master/0011/README.md
[12/CIP]:   {{rfc_url}}blob/master/0012/README.md
[13/DSTP]:  {{rfc_url}}blob/master/0013/README.md
[14/TSTP]:  {{rfc_url}}blob/master/0014/README.md
[15/EME]:   {{rfc_url}}blob/master/0015/README.md
[16/ECAP]:  {{rfc_url}}blob/master/0016/README.md
[17/SCMP]:  {{rfc_url}}blob/master/0017/README.md
[18/EFE]:   {{rfc_url}}blob/master/0018/README.md
[19/EPMMP]: {{rfc_url}}blob/master/0019/README.md
[20/EFMP]:  {{rfc_url}}blob/master/0020/README.md

<!--== Kaa terminology ==-->
[architecture overview]:    {{root_url}}Architecture-overview/
[scalability]:              {{root_url}}Architecture-overview/#scalability
[service configuration]:    {{root_url}}Architecture-overview/#configuration

{% capture kaa_concepts %}{{root_url}}Kaa-concepts/{% endcapture %}
[kaa concepts]:         {{kaa_concepts}}
[endpoint]:             {{kaa_concepts}}#endpoints
[endpoint-id]:          {{kaa_concepts}}#endpoint-id
[endpoint-token]:       {{kaa_concepts}}#endpoint-token
[endpoint-metadata]:    {{kaa_concepts}}#endpoint-metadata
[data-sample]:          {{kaa_concepts}}#data-sample
[endpoint-filter]:      {{epr_url}}Key-service-features/Ep-filters/
[client]:               {{kaa_concepts}}#kaa-client
[application]:          {{kaa_concepts}}#applications-and-application-versions
[service]:              {{kaa_concepts}}#kaa-services
[solution]:             {{kaa_concepts}}#solutions
[blueprint]:            {{kaa_concepts}}#blueprint
[extension]:            {{kaa_concepts}}#extension-services
[dashboard]:            {{wd_url}}Overview/#dashboards
[widget]:               {{wd_url}}Overview/#widgets
[tenant]:               {{kaa_concepts}}#tenant

<!--== Tutorials ==-->
{% capture tutorials_url %}{{root_url}}Tutorials/{% endcapture %}
[tutorials]:                        {{tutorials_url}}
[how to connect device]:            {{tutorials_url}}connect-device-to-iot-platform/
[connect BlitzWolf smart socket]:   {{tutorials_url}}connect-blitzwolf-smart-socket/
[how to connect an ESP8266]:        {{tutorials_url}}connect-esp8266-to-kaa-platform/
[data collection tutorial]:         {{tutorials_url}}iot-data-collection/
[custom web dashboard]:             {{tutorials_url}}build-iot-dashboard/
[iot notification tutorial]:        {{tutorials_url}}iot-notification/
[kaa cloud getting started]:        {{tutorials_url}}getting-started-kaa-cloud/

<!-- Administration -->
{% capture administration_url %}{{root_url}}Administration/{% endcapture %}
[administration]:               {{administration_url}}
[local installation]:           {{administration_url}}Local-installation/
[k8s installation]:             {{administration_url}}Installation-to-kubernetes-cluster/
[api security]:                 {{administration_url}}API-security/
[endpoint resource type]:       {{administration_url}}API-security/#endpoint-resource-type
[application resource type]:    {{administration_url}}API-security/#application-resource-type
[dashboard resource type]:      {{administration_url}}API-security/#dashboard-resource-type
[kaa resource type]:            {{administration_url}}API-security/#kaa-resource-type

<!-- Webinars -->
[webinars]: {{root_url}}Webinars/
[webinar Kaa IoT Cloud and Kaa 1.1]:        {{root_url}}Webinars/2019-12-11-Kaa-IoT-Cloud-and-Kaa-1.1/
[webinar Data Analytics and Notifications]: {{root_url}}Webinars/2020-04-02-Data-Analytics-and-Notifications/

<!-- What's new -->
[whats new]: {{root_url}}Whats-new/
[whats new in 1.1]: {{root_url}}Whats-new/#kaa-11-november-8-th-2019

<!--== 3-rd party components ==-->
[docker]: https://www.docker.com/
[k8s]: https://kubernetes.io/
[helm]: https://helm.sh/
[prometheus]: https://prometheus.io/
[nginx]: https://www.nginx.com/
[fluentd]: https://www.fluentd.org/
[grafana]: https://grafana.com/
[nats]: https://www.nats.io/
[keycloak]: https://www.keycloak.org/
[influxdb]: https://docs.influxdata.com/influxdb/
[mongo]: https://www.mongodb.com/what-is-mongodb
[maria]: https://mariadb.org/
[redis]: https://redis.io
[postgresql]: https://www.postgresql.org/
[elastic stack]: https://www.elastic.co/elastic-stack
[kibana]: https://www.elastic.co/kibana

<!--== Technologies ==-->
[mqtt]: http://mqtt.org/
[coap]: http://coap.technology/
[json]: https://www.json.org/
[avro]: https://avro.apache.org/
[oauth2]: https://tools.ietf.org/html/rfc6749
[resource server]: https://www.oauth.com/oauth2-servers/the-resource-server/
[access token]: https://www.oauth.com/oauth2-servers/access-tokens/
[oauth scope]: https://www.oauth.com/oauth2-servers/scope/
[openid]: https://openid.net/connect/
[uma]: https://en.wikipedia.org/wiki/User-Managed_Access

<!--== General ==-->
[digital twin]: https://en.wikipedia.org/wiki/Digital_twin
[over-the-air]: https://en.wikipedia.org/wiki/Over-the-air_programming
[openid]: https://openid.net/connect/


<!--== KaaIoT sites ==-->
[Kaa cloud]: https://cloud.kaaiot.com
[Kaa user chat]: https://gitter.im/KaaIoT/community
