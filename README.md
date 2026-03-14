# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt  
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-40
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 марта
- Ссылка:
```bash
tg://proxy?server=s1.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## psb.hosting
- Локация: Finland
- Тариф: FI-200
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 12$
- Оплачен до: 25 марта
- Ссылка:
```bash
tg://proxy?server=s2.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## koara.io
- Локация: Германия, Франкфурт-на-Майне
- Тариф: DE-2
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 639 RUB
- Оплачен до: 25 марта
- Ссылка:
```bash
tg://proxy?server=s3.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## landvps.ru
- Локация: Финляндия
- Тариф: FL-2
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 200 Mbps/s
- Цена в месяц: 800 RUB
- Оплачен до: 26 марта
- Ссылка:
```bash
tg://proxy?server=s4.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## rdp-onedash.ru
- Локация: Нидерланды
- Тариф: Mini
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 844 RUB
- Оплачен до: 14 апреля
- Ссылка:
```bash
tg://proxy?server=s5.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## hostvds.com
- Локация: Нидерланды, Амстердам
- Тариф: Burstable
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 10 Gbit/s
- Цена в месяц: €7.98
- Оплачен до: 13 апреля
- Ссылка:
```bash
tg://proxy?server=s6.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-14 20:48:42 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.17

telemt_uptime_seconds 27141.5 (7h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 137280
telemt_connections_bad_total 16158
telemt_handshake_timeouts_total 1470
telemt_upstream_connect_attempt_total 6083
telemt_upstream_connect_success_total 6081
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 6083
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2883
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3115
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 83
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 216
telemt_me_reconnect_attempts_total 4705
telemt_me_reconnect_success_total 4669
telemt_me_reader_eof_total 4951
telemt_me_idle_close_by_peer_total 4951
telemt_me_route_drop_no_conn_total 49826
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 113482
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 516
telemt_desync_full_logged_total 184
telemt_desync_suppressed_total 332
telemt_desync_frames_bucket_total{bucket="1_2"} 119
telemt_desync_frames_bucket_total{bucket="3_10"} 189
telemt_desync_frames_bucket_total{bucket="gt_10"} 208
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 4749
telemt_me_writer_restored_same_endpoint_total 4651
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 72
telemt_me_writer_removed_unexpected_minus_restored_total 80
telemt_user_connections_total{user="hello"} 113402
telemt_user_connections_current{user="hello"} 292
telemt_user_octets_from_client{user="hello"} 2428644300 (2.26 GB)
telemt_user_octets_to_client{user="hello"} 68095520632 (63.42 GB)
telemt_user_unique_ips_current{user="hello"} 83
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## psb.hosting

```
telemt 3.3.17

telemt_uptime_seconds 27139.8 (7h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 56241
telemt_connections_bad_total 729
telemt_handshake_timeouts_total 984
telemt_upstream_connect_attempt_total 7074
telemt_upstream_connect_success_total 7029
telemt_upstream_connect_fail_total 45
telemt_upstream_connect_attempts_per_request{bucket="1"} 7074
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2887
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4009
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 133
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 45
telemt_me_keepalive_timeout_total 130
telemt_me_reconnect_attempts_total 8194
telemt_me_reconnect_success_total 5615
telemt_me_reader_eof_total 5963
telemt_me_idle_close_by_peer_total 5963
telemt_me_route_drop_no_conn_total 29126
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 52343
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 11
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 5772
telemt_me_refill_failed_total 79
telemt_me_writer_restored_same_endpoint_total 5610
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 120
telemt_me_writer_removed_unexpected_minus_restored_total 157
telemt_user_connections_total{user="hello"} 52331
telemt_user_connections_current{user="hello"} 172
telemt_user_octets_from_client{user="hello"} 1338766244 (1.25 GB)
telemt_user_octets_to_client{user="hello"} 23310724800 (21.71 GB)
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## koara.io

```
telemt 3.3.17

telemt_uptime_seconds 27143.9 (7h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 63061
telemt_connections_bad_total 391
telemt_handshake_timeouts_total 1888
telemt_upstream_connect_attempt_total 8953
telemt_upstream_connect_success_total 8862
telemt_upstream_connect_fail_total 91
telemt_upstream_connect_attempts_per_request{bucket="1"} 8953
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4154
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4698
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 91
telemt_me_keepalive_timeout_total 250
telemt_me_reconnect_attempts_total 104995
telemt_me_reconnect_success_total 7131
telemt_me_reader_eof_total 7614
telemt_me_idle_close_by_peer_total 7614
telemt_me_route_drop_no_conn_total 23825
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 57515
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 11
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 15
telemt_desync_full_logged_total 4
telemt_desync_suppressed_total 11
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 5
telemt_desync_frames_bucket_total{bucket="gt_10"} 6
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 7409
telemt_me_refill_failed_total 3169
telemt_me_writer_restored_same_endpoint_total 7085
telemt_me_writer_restored_fallback_total 46
telemt_me_async_recovery_trigger_total 1685
telemt_me_writer_removed_unexpected_minus_restored_total 278
telemt_user_connections_total{user="hello"} 57581
telemt_user_connections_current{user="hello"} 112
telemt_user_octets_from_client{user="hello"} 3854162041 (3.59 GB)
telemt_user_octets_to_client{user="hello"} 41130624826 (38.31 GB)
telemt_user_msgs_from_client{user="hello"} 3762
telemt_user_msgs_to_client{user="hello"} 18362
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## landvps.ru

```
telemt 3.3.17

telemt_uptime_seconds 27148.8 (7h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 80561
telemt_connections_bad_total 206
telemt_handshake_timeouts_total 598
telemt_upstream_connect_attempt_total 6698
telemt_upstream_connect_success_total 6657
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 6698
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3114
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3515
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_keepalive_timeout_total 191
telemt_me_reconnect_attempts_total 5107
telemt_me_reconnect_success_total 5080
telemt_me_reader_eof_total 5351
telemt_me_idle_close_by_peer_total 5351
telemt_me_route_drop_no_conn_total 34755
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 76307
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 609
telemt_desync_full_logged_total 154
telemt_desync_suppressed_total 455
telemt_desync_frames_bucket_total{bucket="1_2"} 106
telemt_desync_frames_bucket_total{bucket="3_10"} 258
telemt_desync_frames_bucket_total{bucket="gt_10"} 245
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 5138
telemt_me_writer_restored_same_endpoint_total 5078
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 60
telemt_me_writer_removed_unexpected_minus_restored_total 58
telemt_user_connections_total{user="hello"} 76353
telemt_user_connections_current{user="hello"} 151
telemt_user_octets_from_client{user="hello"} 1243630772 (1.16 GB)
telemt_user_octets_to_client{user="hello"} 26415645042 (24.60 GB)
telemt_user_msgs_from_client{user="hello"} 473
telemt_user_msgs_to_client{user="hello"} 2783
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## rdp-onedash.ru

```
telemt 3.3.17

telemt_uptime_seconds 27142.0 (7h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 59067
telemt_connections_bad_total 5233
telemt_handshake_timeouts_total 3333
telemt_upstream_connect_attempt_total 6478
telemt_upstream_connect_success_total 6402
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 6478
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2880
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3482
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_keepalive_timeout_total 194
telemt_me_reconnect_attempts_total 11521
telemt_me_reconnect_success_total 4985
telemt_me_reader_eof_total 5410
telemt_me_idle_close_by_peer_total 5410
telemt_me_route_drop_no_conn_total 19502
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 47697
telemt_me_writer_pick_total{mode="p2c",result="full"} 2
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 262
telemt_desync_full_logged_total 39
telemt_desync_suppressed_total 223
telemt_desync_frames_bucket_total{bucket="1_2"} 37
telemt_desync_frames_bucket_total{bucket="3_10"} 92
telemt_desync_frames_bucket_total{bucket="gt_10"} 133
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 5236
telemt_me_refill_failed_total 203
telemt_me_writer_restored_same_endpoint_total 4981
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 251
telemt_user_connections_total{user="hello"} 47684
telemt_user_connections_current{user="hello"} 62
telemt_user_octets_from_client{user="hello"} 1379087544 (1.28 GB)
telemt_user_octets_to_client{user="hello"} 29133651280 (27.13 GB)
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## hostvds.com

```
telemt 3.3.17

telemt_uptime_seconds 27141.4 (7h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 203202
telemt_connections_bad_total 7303
telemt_handshake_timeouts_total 2662
telemt_upstream_connect_attempt_total 5317
telemt_upstream_connect_success_total 5218
telemt_upstream_connect_fail_total 99
telemt_upstream_connect_attempts_per_request{bucket="1"} 5317
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2548
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2665
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 99
telemt_me_keepalive_timeout_total 252
telemt_me_reconnect_attempts_total 8812
telemt_me_reconnect_success_total 3805
telemt_me_reader_eof_total 4126
telemt_me_idle_close_by_peer_total 4126
telemt_me_route_drop_no_conn_total 113872
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 187269
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 4
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 55
telemt_desync_full_logged_total 20
telemt_desync_suppressed_total 35
telemt_desync_frames_bucket_total{bucket="1_2"} 20
telemt_desync_frames_bucket_total{bucket="3_10"} 15
telemt_desync_frames_bucket_total{bucket="gt_10"} 20
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 4007
telemt_me_refill_failed_total 155
telemt_me_writer_restored_same_endpoint_total 3801
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 202
telemt_user_connections_total{user="hello"} 183756
telemt_user_connections_current{user="hello"} 407
telemt_user_octets_from_client{user="hello"} 3966263292 (3.69 GB)
telemt_user_octets_to_client{user="hello"} 97663629180 (90.96 GB)
telemt_user_unique_ips_current{user="hello"} 154
telemt_user_unique_ips_recent_window{user="hello"} 53
```