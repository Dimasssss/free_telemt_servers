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

# Server Metrics 2026-03-16 15:34:09 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 6976.4 (1h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 78965
telemt_connections_bad_total 472
telemt_handshake_timeouts_total 2623
telemt_upstream_connect_attempt_total 1516
telemt_upstream_connect_success_total 1514
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 1516
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 720
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 793
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1131
telemt_me_reconnect_success_total 1122
telemt_me_reader_eof_total 1131
telemt_me_idle_close_by_peer_total 1131
telemt_me_route_drop_no_conn_total 22481
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 72981
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 294
telemt_desync_full_logged_total 63
telemt_desync_suppressed_total 231
telemt_desync_frames_bucket_total{bucket="1_2"} 117
telemt_desync_frames_bucket_total{bucket="3_10"} 120
telemt_desync_frames_bucket_total{bucket="gt_10"} 57
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 1119
telemt_me_writer_restored_same_endpoint_total 1120
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 36
telemt_user_connections_total{user="hello"} 72909
telemt_user_connections_current{user="hello"} 678
telemt_user_octets_from_client{user="hello"} 1557999372 (1.45 GB)
telemt_user_octets_to_client{user="hello"} 43408582880 (40.43 GB)
telemt_user_unique_ips_current{user="hello"} 207
telemt_user_unique_ips_recent_window{user="hello"} 71
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 1755.6 (0h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14410
telemt_connections_bad_total 15
telemt_handshake_timeouts_total 239
telemt_upstream_connect_attempt_total 286
telemt_upstream_connect_success_total 283
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 286
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 101
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 156
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 177
telemt_me_reconnect_success_total 173
telemt_me_reader_eof_total 149
telemt_me_idle_close_by_peer_total 149
telemt_me_route_drop_no_conn_total 8793
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13710
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_writer_removed_unexpected_total 171
telemt_me_writer_restored_same_endpoint_total 168
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 343
telemt_user_connections_total{user="hello"} 13700
telemt_user_connections_current{user="hello"} 403
telemt_user_octets_from_client{user="hello"} 119449020 (113.92 MB)
telemt_user_octets_to_client{user="hello"} 2527649732 (2.35 GB)
telemt_user_unique_ips_current{user="hello"} 113
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 7089.4 (1h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 31501
telemt_connections_bad_total 18
telemt_handshake_timeouts_total 561
telemt_upstream_connect_attempt_total 2483
telemt_upstream_connect_success_total 2448
telemt_upstream_connect_fail_total 35
telemt_upstream_connect_attempts_per_request{bucket="1"} 2483
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1440
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 988
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 35
telemt_me_reconnect_attempts_total 36148
telemt_me_reconnect_success_total 1084
telemt_me_reader_eof_total 1261
telemt_me_idle_close_by_peer_total 1261
telemt_me_route_drop_no_conn_total 9199
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 27899
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 25
telemt_desync_full_logged_total 11
telemt_desync_suppressed_total 14
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 8
telemt_desync_frames_bucket_total{bucket="gt_10"} 10
telemt_me_writer_removed_unexpected_total 1284
telemt_me_refill_failed_total 1095
telemt_me_writer_restored_same_endpoint_total 1040
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 1272
telemt_me_writer_removed_unexpected_minus_restored_total 200
telemt_user_connections_total{user="hello"} 28848
telemt_user_connections_current{user="hello"} 220
telemt_user_octets_from_client{user="hello"} 332837474 (317.42 MB)
telemt_user_octets_to_client{user="hello"} 4764542350 (4.44 GB)
telemt_user_msgs_from_client{user="hello"} 4789
telemt_user_msgs_to_client{user="hello"} 14129
telemt_user_unique_ips_current{user="hello"} 84
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 7225.4 (2h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 56679
telemt_connections_bad_total 118
telemt_handshake_timeouts_total 856
telemt_upstream_connect_attempt_total 1410
telemt_upstream_connect_success_total 1402
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 1410
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 689
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 696
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 7310
telemt_me_reconnect_success_total 985
telemt_me_reader_eof_total 1158
telemt_me_idle_close_by_peer_total 1158
telemt_me_route_drop_no_conn_total 19293
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 53698
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 287
telemt_desync_full_logged_total 78
telemt_desync_suppressed_total 209
telemt_desync_frames_bucket_total{bucket="1_2"} 47
telemt_desync_frames_bucket_total{bucket="3_10"} 115
telemt_desync_frames_bucket_total{bucket="gt_10"} 125
telemt_me_writer_removed_unexpected_total 1182
telemt_me_refill_failed_total 197
telemt_me_writer_restored_same_endpoint_total 981
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 197
telemt_user_connections_total{user="hello"} 53679
telemt_user_connections_current{user="hello"} 421
telemt_user_octets_from_client{user="hello"} 904665756 (862.76 MB)
telemt_user_octets_to_client{user="hello"} 12593941404 (11.73 GB)
telemt_user_unique_ips_current{user="hello"} 131
telemt_user_unique_ips_recent_window{user="hello"} 63
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 4686.0 (1h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 24869
telemt_connections_bad_total 8944
telemt_handshake_timeouts_total 180
telemt_upstream_connect_attempt_total 1262
telemt_upstream_connect_success_total 1244
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 1262
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 444
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 751
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_reconnect_attempts_total 1601
telemt_me_reconnect_success_total 949
telemt_me_reader_eof_total 971
telemt_me_idle_close_by_peer_total 971
telemt_me_route_drop_no_conn_total 5712
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 14909
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 17
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 11
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 6
telemt_desync_frames_bucket_total{bucket="gt_10"} 6
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 981
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 949
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 14893
telemt_user_connections_current{user="hello"} 171
telemt_user_octets_from_client{user="hello"} 290159040 (276.72 MB)
telemt_user_octets_to_client{user="hello"} 2520653608 (2.35 GB)
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 6794.2 (1h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 79755
telemt_connections_bad_total 1146
telemt_handshake_timeouts_total 1656
telemt_upstream_connect_attempt_total 1444
telemt_upstream_connect_success_total 1444
telemt_upstream_connect_attempts_per_request{bucket="1"} 1444
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 704
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 738
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 3428
telemt_me_reconnect_success_total 1051
telemt_me_reader_eof_total 1121
telemt_me_idle_close_by_peer_total 1121
telemt_me_route_drop_no_conn_total 36313
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 74658
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 5
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16
telemt_desync_full_logged_total 5
telemt_desync_suppressed_total 11
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 10
telemt_desync_frames_bucket_total{bucket="gt_10"} 3
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 1133
telemt_me_refill_failed_total 74
telemt_me_writer_restored_same_endpoint_total 1047
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 208
telemt_me_writer_removed_unexpected_minus_restored_total 82
telemt_user_connections_total{user="hello"} 74411
telemt_user_connections_current{user="hello"} 687
telemt_user_octets_from_client{user="hello"} 1534922696 (1.43 GB)
telemt_user_octets_to_client{user="hello"} 22598861136 (21.05 GB)
telemt_user_unique_ips_current{user="hello"} 256
telemt_user_unique_ips_recent_window{user="hello"} 97
```