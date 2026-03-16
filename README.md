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

# Server Metrics 2026-03-16 15:23:57 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 6364.7 (1h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 72770
telemt_connections_bad_total 438
telemt_handshake_timeouts_total 2232
telemt_upstream_connect_attempt_total 1409
telemt_upstream_connect_success_total 1407
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 1409
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 668
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 739
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 1041
telemt_me_reconnect_success_total 1033
telemt_me_reader_eof_total 1024
telemt_me_idle_close_by_peer_total 1024
telemt_me_route_drop_no_conn_total 20796
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 67259
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 284
telemt_desync_full_logged_total 60
telemt_desync_suppressed_total 224
telemt_desync_frames_bucket_total{bucket="1_2"} 111
telemt_desync_frames_bucket_total{bucket="3_10"} 118
telemt_desync_frames_bucket_total{bucket="gt_10"} 55
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 1029
telemt_me_writer_restored_same_endpoint_total 1031
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 36
telemt_user_connections_total{user="hello"} 67188
telemt_user_connections_current{user="hello"} 667
telemt_user_octets_from_client{user="hello"} 1499384356 (1.40 GB)
telemt_user_octets_to_client{user="hello"} 39317626212 (36.62 GB)
telemt_user_unique_ips_current{user="hello"} 213
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 1143.2 (0h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10662
telemt_connections_bad_total 13
telemt_handshake_timeouts_total 200
telemt_upstream_connect_attempt_total 193
telemt_upstream_connect_success_total 190
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 193
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 85
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 83
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 84
telemt_me_reconnect_success_total 81
telemt_me_reader_eof_total 53
telemt_me_idle_close_by_peer_total 53
telemt_me_route_drop_no_conn_total 7274
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10111
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_writer_removed_unexpected_total 75
telemt_me_writer_restored_same_endpoint_total 76
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 343
telemt_user_connections_total{user="hello"} 10103
telemt_user_connections_current{user="hello"} 413
telemt_user_octets_from_client{user="hello"} 88200820 (84.11 MB)
telemt_user_octets_to_client{user="hello"} 1833696684 (1.71 GB)
telemt_user_unique_ips_current{user="hello"} 113
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 6477.4 (1h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 29455
telemt_connections_bad_total 15
telemt_handshake_timeouts_total 486
telemt_upstream_connect_attempt_total 2475
telemt_upstream_connect_success_total 2440
telemt_upstream_connect_fail_total 35
telemt_upstream_connect_attempts_per_request{bucket="1"} 2475
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1440
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 980
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 35
telemt_me_reconnect_attempts_total 35532
telemt_me_reconnect_success_total 1077
telemt_me_reader_eof_total 1235
telemt_me_idle_close_by_peer_total 1235
telemt_me_route_drop_no_conn_total 8158
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 26015
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 18
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 9
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 6
telemt_desync_frames_bucket_total{bucket="gt_10"} 6
telemt_me_writer_removed_unexpected_total 1258
telemt_me_refill_failed_total 1076
telemt_me_writer_restored_same_endpoint_total 1033
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 1272
telemt_me_writer_removed_unexpected_minus_restored_total 181
telemt_user_connections_total{user="hello"} 26964
telemt_user_connections_current{user="hello"} 267
telemt_user_octets_from_client{user="hello"} 318347134 (303.60 MB)
telemt_user_octets_to_client{user="hello"} 4508734914 (4.20 GB)
telemt_user_msgs_from_client{user="hello"} 4789
telemt_user_msgs_to_client{user="hello"} 14129
telemt_user_unique_ips_current{user="hello"} 82
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 6613.7 (1h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 52474
telemt_connections_bad_total 118
telemt_handshake_timeouts_total 846
telemt_upstream_connect_attempt_total 1360
telemt_upstream_connect_success_total 1352
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 1360
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 675
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 660
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 7260
telemt_me_reconnect_success_total 936
telemt_me_reader_eof_total 1109
telemt_me_idle_close_by_peer_total 1109
telemt_me_route_drop_no_conn_total 18047
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 49582
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 271
telemt_desync_full_logged_total 73
telemt_desync_suppressed_total 198
telemt_desync_frames_bucket_total{bucket="1_2"} 47
telemt_desync_frames_bucket_total{bucket="3_10"} 107
telemt_desync_frames_bucket_total{bucket="gt_10"} 117
telemt_me_writer_removed_unexpected_total 1133
telemt_me_refill_failed_total 197
telemt_me_writer_restored_same_endpoint_total 932
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 197
telemt_user_connections_total{user="hello"} 49563
telemt_user_connections_current{user="hello"} 474
telemt_user_octets_from_client{user="hello"} 858000892 (818.25 MB)
telemt_user_octets_to_client{user="hello"} 11479763476 (10.69 GB)
telemt_user_unique_ips_current{user="hello"} 141
telemt_user_unique_ips_recent_window{user="hello"} 62
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 4074.0 (1h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21557
telemt_connections_bad_total 7779
telemt_handshake_timeouts_total 126
telemt_upstream_connect_attempt_total 1106
telemt_upstream_connect_success_total 1092
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 1106
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 395
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 650
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 47
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_reconnect_attempts_total 1492
telemt_me_reconnect_success_total 841
telemt_me_reader_eof_total 854
telemt_me_idle_close_by_peer_total 854
telemt_me_route_drop_no_conn_total 4762
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12929
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
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
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 872
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 841
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 31
telemt_user_connections_total{user="hello"} 12913
telemt_user_connections_current{user="hello"} 139
telemt_user_octets_from_client{user="hello"} 278562672 (265.66 MB)
telemt_user_octets_to_client{user="hello"} 2235900040 (2.08 GB)
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 6181.6 (1h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 73587
telemt_connections_bad_total 1145
telemt_handshake_timeouts_total 1528
telemt_upstream_connect_attempt_total 1261
telemt_upstream_connect_success_total 1261
telemt_upstream_connect_attempts_per_request{bucket="1"} 1261
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 620
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 639
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 3290
telemt_me_reconnect_success_total 914
telemt_me_reader_eof_total 981
telemt_me_idle_close_by_peer_total 981
telemt_me_route_drop_no_conn_total 33204
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 68920
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 5
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9
telemt_desync_full_logged_total 4
telemt_desync_suppressed_total 5
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 7
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 993
telemt_me_refill_failed_total 74
telemt_me_writer_restored_same_endpoint_total 910
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 208
telemt_me_writer_removed_unexpected_minus_restored_total 79
telemt_user_connections_total{user="hello"} 68674
telemt_user_connections_current{user="hello"} 673
telemt_user_octets_from_client{user="hello"} 1484015160 (1.38 GB)
telemt_user_octets_to_client{user="hello"} 20550207616 (19.14 GB)
telemt_user_unique_ips_current{user="hello"} 253
telemt_user_unique_ips_recent_window{user="hello"} 100
```