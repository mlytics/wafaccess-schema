# wafaccess-schema

| Field | Type | Nullable | Description | Remark |
| - | - | - | - | - |
| @schema_ver | string | False | Schema version of this message |  |
| accept_encoding | string | False |  |  |
| body_bytes_sent | int | False |  |  |
| bytes_sent | int | False |  |  |
| cache_status | string | False |  |  |
| cdn_node_ip | string | False |  | "-"? |
| cdn_provider | string | False |  |  |
| content_encoding | string | False |  |  |
| customer_info | string | False |  |  |
| http_referer | string | False |  |  |
| http_user_agent | string | False |  |  |
| http_version | string | False |  |  |
| http_x_forwarded_for | string | False |  |  |
| mitigation_result | string | False |  |  |
| origin_content_encoding | string | False |  |  |
| query_string | string | False |  |  |
| realip_remote_addr | string | False |  |  |
| remote_addr | string | False |  |  |
| request_host | string | False |  |  |
| request_id | string | False |  |  |
| request_length | int | False |  |  |
| request_method | string | False |  |  |
| request_time | number | False |  | Seconds |
| scheme | string | False |  |  |
| sent_http_content_type | string | False |  |  |
| status | int | False |  |  |
| time | string | False |  |  |
| upstream_addr | string | False |  |  |
| upstream_connect_time | number | True |  |  |
| upstream_header_time | number | True |  |  |
| upstream_host | string | False |  |  |
| upstream_response_length | int | True |  |  |
| upstream_response_time | number | True |  |  |
| upstream_status | int | True |  |  |
| uri | string | False |  |  |
| zone_id | string | False |  |  |
