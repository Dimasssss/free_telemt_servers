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

# Server Metrics 2026-03-15 00:53:15 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 9527.3 (2h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19699
telemt_connections_bad_total 366
telemt_handshake_timeouts_total 261
telemt_upstream_connect_attempt_total 2441
telemt_upstream_connect_success_total 2429
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 2441
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1143
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1282
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_reconnect_attempts_total 1935
telemt_me_reconnect_success_total 1924
telemt_me_reader_eof_total 2022
telemt_me_idle_close_by_peer_total 2022
telemt_me_route_drop_no_conn_total 5416
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 18427
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 114
telemt_desync_full_logged_total 50
telemt_desync_suppressed_total 64
telemt_desync_frames_bucket_total{bucket="1_2"} 20
telemt_desync_frames_bucket_total{bucket="3_10"} 35
telemt_desync_frames_bucket_total{bucket="gt_10"} 59
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 1925
telemt_me_writer_restored_same_endpoint_total 1893
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 18425
telemt_user_connections_current{user="hello"} 239
telemt_user_octets_from_client{user="hello"} 209681100 (199.97 MB)
telemt_user_octets_to_client{user="hello"} 5947446096 (5.54 GB)
telemt_user_unique_ips_current{user="hello"} 75
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 9534.0 (2h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9106
telemt_connections_bad_total 16
telemt_handshake_timeouts_total 30
telemt_upstream_connect_attempt_total 2676
telemt_upstream_connect_success_total 2676
telemt_upstream_connect_attempts_per_request{bucket="1"} 2676
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1174
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1502
telemt_me_reconnect_attempts_total 2176
telemt_me_reconnect_success_total 2171
telemt_me_reader_eof_total 2302
telemt_me_idle_close_by_peer_total 2302
telemt_me_route_drop_no_conn_total 2814
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8584
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 2181
telemt_me_writer_restored_same_endpoint_total 2155
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 8586
telemt_user_connections_current{user="hello"} 109
telemt_user_octets_from_client{user="hello"} 89478600 (85.33 MB)
telemt_user_octets_to_client{user="hello"} 1551043480 (1.44 GB)
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 9526.5 (2h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9357
telemt_connections_bad_total 84
telemt_handshake_timeouts_total 188
telemt_upstream_connect_attempt_total 2536
telemt_upstream_connect_success_total 2535
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 2536
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1134
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1397
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 2039
telemt_me_reconnect_success_total 2027
telemt_me_reader_eof_total 2175
telemt_me_idle_close_by_peer_total 2175
telemt_me_route_drop_no_conn_total 3017
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8795
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 2037
telemt_me_writer_restored_same_endpoint_total 2023
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 8773
telemt_user_connections_current{user="hello"} 85
telemt_user_octets_from_client{user="hello"} 1300416600 (1.21 GB)
telemt_user_octets_to_client{user="hello"} 10916276408 (10.17 GB)
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 9526.3 (2h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9483
telemt_connections_bad_total 74
telemt_handshake_timeouts_total 37
telemt_upstream_connect_attempt_total 2337
telemt_upstream_connect_success_total 2336
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 2337
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1059
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1273
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 1844
telemt_me_reconnect_success_total 1835
telemt_me_reader_eof_total 1940
telemt_me_idle_close_by_peer_total 1940
telemt_me_route_drop_no_conn_total 3847
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9122
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 52
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 43
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 24
telemt_desync_frames_bucket_total{bucket="gt_10"} 23
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 1847
telemt_me_writer_restored_same_endpoint_total 1824
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 9122
telemt_user_connections_current{user="hello"} 115
telemt_user_octets_from_client{user="hello"} 224189140 (213.80 MB)
telemt_user_octets_to_client{user="hello"} 6518871732 (6.07 GB)
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 9526.4 (2h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12206
telemt_connections_bad_total 2008
telemt_handshake_timeouts_total 371
telemt_upstream_connect_attempt_total 3096
telemt_upstream_connect_success_total 3057
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 3096
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1468
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1583
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_reconnect_attempts_total 2629
telemt_me_reconnect_success_total 2553
telemt_me_reader_eof_total 2667
telemt_me_idle_close_by_peer_total 2667
telemt_me_route_drop_no_conn_total 2936
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9596
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 2555
telemt_me_refill_failed_total 2
telemt_me_writer_restored_same_endpoint_total 2541
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 29
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 9584
telemt_user_connections_current{user="hello"} 47
telemt_user_octets_from_client{user="hello"} 155864624 (148.64 MB)
telemt_user_octets_to_client{user="hello"} 5416677892 (5.04 GB)
telemt_user_unique_ips_current{user="hello"} 17
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 9525.3 (2h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 30852
telemt_connections_bad_total 658
telemt_handshake_timeouts_total 110
telemt_upstream_connect_attempt_total 2110
telemt_upstream_connect_success_total 2099
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 2110
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1052
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1047
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_reconnect_attempts_total 1602
telemt_me_reconnect_success_total 1597
telemt_me_reader_eof_total 1662
telemt_me_idle_close_by_peer_total 1662
telemt_me_route_drop_no_conn_total 17913
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 30673
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16
telemt_desync_full_logged_total 5
telemt_desync_suppressed_total 11
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 4
telemt_desync_frames_bucket_total{bucket="gt_10"} 6
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 1583
telemt_me_writer_restored_same_endpoint_total 1570
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_user_connections_total{user="hello"} 29242
telemt_user_connections_current{user="hello"} 244
telemt_user_octets_from_client{user="hello"} 451428156 (430.52 MB)
telemt_user_octets_to_client{user="hello"} 21298148796 (19.84 GB)
telemt_user_unique_ips_current{user="hello"} 116
telemt_user_unique_ips_recent_window{user="hello"} 25
```