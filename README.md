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

# Server Metrics 2026-03-16 15:59:44 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 8510.7 (2h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 93250
telemt_connections_bad_total 591
telemt_handshake_timeouts_total 2821
telemt_upstream_connect_attempt_total 1948
telemt_upstream_connect_success_total 1943
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 1948
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 946
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 996
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1469
telemt_me_reconnect_success_total 1457
telemt_me_reader_eof_total 1466
telemt_me_idle_close_by_peer_total 1466
telemt_me_route_drop_no_conn_total 26827
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 86537
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 443
telemt_desync_full_logged_total 85
telemt_desync_suppressed_total 358
telemt_desync_frames_bucket_total{bucket="1_2"} 196
telemt_desync_frames_bucket_total{bucket="3_10"} 160
telemt_desync_frames_bucket_total{bucket="gt_10"} 87
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 1456
telemt_me_writer_restored_same_endpoint_total 1455
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 36
telemt_user_connections_total{user="hello"} 86462
telemt_user_connections_current{user="hello"} 704
telemt_user_octets_from_client{user="hello"} 1695444796 (1.58 GB)
telemt_user_octets_to_client{user="hello"} 49782147868 (46.36 GB)
telemt_user_unique_ips_current{user="hello"} 200
telemt_user_unique_ips_recent_window{user="hello"} 83
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 3288.8 (0h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 23912
telemt_connections_bad_total 28
telemt_handshake_timeouts_total 521
telemt_upstream_connect_attempt_total 639
telemt_upstream_connect_success_total 633
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 639
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 222
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 356
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 55
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_reconnect_attempts_total 437
telemt_me_reconnect_success_total 429
telemt_me_reader_eof_total 419
telemt_me_idle_close_by_peer_total 419
telemt_me_route_drop_no_conn_total 13289
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 22475
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11
telemt_desync_full_logged_total 2
telemt_desync_suppressed_total 9
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 4
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 434
telemt_me_writer_restored_same_endpoint_total 424
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 343
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 22450
telemt_user_connections_current{user="hello"} 410
telemt_user_octets_from_client{user="hello"} 168522552 (160.72 MB)
telemt_user_octets_to_client{user="hello"} 6266128492 (5.84 GB)
telemt_user_unique_ips_current{user="hello"} 113
telemt_user_unique_ips_recent_window{user="hello"} 53
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 8623.6 (2h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 37301
telemt_connections_bad_total 33
telemt_handshake_timeouts_total 610
telemt_upstream_connect_attempt_total 2597
telemt_upstream_connect_success_total 2559
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 2597
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1498
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1039
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_reconnect_attempts_total 38852
telemt_me_reconnect_success_total 1100
telemt_me_reader_eof_total 1361
telemt_me_idle_close_by_peer_total 1361
telemt_me_route_drop_no_conn_total 11986
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 33450
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 40
telemt_desync_full_logged_total 18
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 11
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_me_writer_removed_unexpected_total 1385
telemt_me_refill_failed_total 1179
telemt_me_writer_restored_same_endpoint_total 1056
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 1272
telemt_me_writer_removed_unexpected_minus_restored_total 285
telemt_user_connections_total{user="hello"} 34399
telemt_user_connections_current{user="hello"} 250
telemt_user_octets_from_client{user="hello"} 359579810 (342.92 MB)
telemt_user_octets_to_client{user="hello"} 5552559194 (5.17 GB)
telemt_user_msgs_from_client{user="hello"} 4789
telemt_user_msgs_to_client{user="hello"} 14129
telemt_user_unique_ips_current{user="hello"} 83
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 8759.7 (2h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 67231
telemt_connections_bad_total 137
telemt_handshake_timeouts_total 930
telemt_upstream_connect_attempt_total 1780
telemt_upstream_connect_success_total 1770
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 1780
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 853
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 895
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 7592
telemt_me_reconnect_success_total 1261
telemt_me_reader_eof_total 1450
telemt_me_idle_close_by_peer_total 1450
telemt_me_route_drop_no_conn_total 22646
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 63801
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 354
telemt_desync_full_logged_total 95
telemt_desync_suppressed_total 259
telemt_desync_frames_bucket_total{bucket="1_2"} 59
telemt_desync_frames_bucket_total{bucket="3_10"} 146
telemt_desync_frames_bucket_total{bucket="gt_10"} 149
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 1468
telemt_me_refill_failed_total 197
telemt_me_writer_restored_same_endpoint_total 1257
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 207
telemt_user_connections_total{user="hello"} 63780
telemt_user_connections_current{user="hello"} 425
telemt_user_octets_from_client{user="hello"} 1025975044 (978.45 MB)
telemt_user_octets_to_client{user="hello"} 15535036696 (14.47 GB)
telemt_user_unique_ips_current{user="hello"} 134
telemt_user_unique_ips_recent_window{user="hello"} 58
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 6220.2 (1h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 34106
telemt_connections_bad_total 12325
telemt_handshake_timeouts_total 250
telemt_upstream_connect_attempt_total 1521
telemt_upstream_connect_success_total 1501
telemt_upstream_connect_fail_total 20
telemt_upstream_connect_attempts_per_request{bucket="1"} 1521
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 553
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 899
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 20
telemt_me_reconnect_attempts_total 1815
telemt_me_reconnect_success_total 1161
telemt_me_reader_eof_total 1198
telemt_me_idle_close_by_peer_total 1198
telemt_me_route_drop_no_conn_total 8230
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 20472
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 19
telemt_desync_full_logged_total 7
telemt_desync_suppressed_total 12
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 8
telemt_desync_frames_bucket_total{bucket="gt_10"} 6
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 1196
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 1161
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 20451
telemt_user_connections_current{user="hello"} 204
telemt_user_octets_from_client{user="hello"} 423477580 (403.86 MB)
telemt_user_octets_to_client{user="hello"} 6846926896 (6.38 GB)
telemt_user_unique_ips_current{user="hello"} 70
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 8327.5 (2h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 96530
telemt_connections_bad_total 1196
telemt_handshake_timeouts_total 1900
telemt_upstream_connect_attempt_total 1740
telemt_upstream_connect_success_total 1740
telemt_upstream_connect_attempts_per_request{bucket="1"} 1740
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 852
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 886
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 3634
telemt_me_reconnect_success_total 1253
telemt_me_reader_eof_total 1341
telemt_me_idle_close_by_peer_total 1341
telemt_me_route_drop_no_conn_total 44586
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 90427
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
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 1340
telemt_me_refill_failed_total 74
telemt_me_writer_restored_same_endpoint_total 1249
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 208
telemt_me_writer_removed_unexpected_minus_restored_total 87
telemt_user_connections_total{user="hello"} 90160
telemt_user_connections_current{user="hello"} 744
telemt_user_octets_from_client{user="hello"} 1918542620 (1.79 GB)
telemt_user_octets_to_client{user="hello"} 28594953504 (26.63 GB)
telemt_user_unique_ips_current{user="hello"} 279
telemt_user_unique_ips_recent_window{user="hello"} 116
```