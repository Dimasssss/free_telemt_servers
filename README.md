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

# Server Metrics 2026-03-15 01:39:03 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 12275.4 (3h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 25633
telemt_connections_bad_total 366
telemt_handshake_timeouts_total 270
telemt_upstream_connect_attempt_total 3145
telemt_upstream_connect_success_total 3126
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 3145
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1425
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1697
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_reconnect_attempts_total 2502
telemt_me_reconnect_success_total 2490
telemt_me_reader_eof_total 2633
telemt_me_idle_close_by_peer_total 2633
telemt_me_route_drop_no_conn_total 7406
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 24213
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 134
telemt_desync_full_logged_total 62
telemt_desync_suppressed_total 72
telemt_desync_frames_bucket_total{bucket="1_2"} 23
telemt_desync_frames_bucket_total{bucket="3_10"} 46
telemt_desync_frames_bucket_total{bucket="gt_10"} 65
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 2495
telemt_me_writer_restored_same_endpoint_total 2459
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 24211
telemt_user_connections_current{user="hello"} 232
telemt_user_octets_from_client{user="hello"} 265245540 (252.96 MB)
telemt_user_octets_to_client{user="hello"} 9933548752 (9.25 GB)
telemt_user_unique_ips_current{user="hello"} 75
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 12281.7 (3h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11692
telemt_connections_bad_total 17
telemt_handshake_timeouts_total 32
telemt_upstream_connect_attempt_total 3409
telemt_upstream_connect_success_total 3409
telemt_upstream_connect_attempts_per_request{bucket="1"} 3409
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1502
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1906
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 2780
telemt_me_reconnect_success_total 2770
telemt_me_reader_eof_total 2947
telemt_me_idle_close_by_peer_total 2947
telemt_me_route_drop_no_conn_total 4058
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 11047
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 2787
telemt_me_writer_restored_same_endpoint_total 2754
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 11051
telemt_user_connections_current{user="hello"} 124
telemt_user_octets_from_client{user="hello"} 265921496 (253.60 MB)
telemt_user_octets_to_client{user="hello"} 1936377480 (1.80 GB)
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 12274.3 (3h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12026
telemt_connections_bad_total 108
telemt_handshake_timeouts_total 223
telemt_upstream_connect_attempt_total 3265
telemt_upstream_connect_success_total 3264
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 3265
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1445
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1815
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 2639
telemt_me_reconnect_success_total 2624
telemt_me_reader_eof_total 2823
telemt_me_idle_close_by_peer_total 2823
telemt_me_route_drop_no_conn_total 4123
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 11335
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 2641
telemt_me_writer_restored_same_endpoint_total 2620
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 11294
telemt_user_connections_current{user="hello"} 84
telemt_user_octets_from_client{user="hello"} 7350501944 (6.85 GB)
telemt_user_octets_to_client{user="hello"} 12624495504 (11.76 GB)
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 12274.1 (3h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12504
telemt_connections_bad_total 77
telemt_handshake_timeouts_total 40
telemt_upstream_connect_attempt_total 2979
telemt_upstream_connect_success_total 2978
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 2979
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1361
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1609
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 2357
telemt_me_reconnect_success_total 2346
telemt_me_reader_eof_total 2489
telemt_me_idle_close_by_peer_total 2489
telemt_me_route_drop_no_conn_total 4948
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 11975
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 54
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 44
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 25
telemt_desync_frames_bucket_total{bucket="gt_10"} 23
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 2365
telemt_me_writer_restored_same_endpoint_total 2335
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 11973
telemt_user_connections_current{user="hello"} 122
telemt_user_octets_from_client{user="hello"} 337213728 (321.59 MB)
telemt_user_octets_to_client{user="hello"} 9083576464 (8.46 GB)
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 12274.1 (3h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15422
telemt_connections_bad_total 2498
telemt_handshake_timeouts_total 385
telemt_upstream_connect_attempt_total 3998
telemt_upstream_connect_success_total 3945
telemt_upstream_connect_fail_total 53
telemt_upstream_connect_attempts_per_request{bucket="1"} 3998
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1824
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2110
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 53
telemt_me_reconnect_attempts_total 3388
telemt_me_reconnect_success_total 3309
telemt_me_reader_eof_total 3476
telemt_me_idle_close_by_peer_total 3476
telemt_me_route_drop_no_conn_total 4329
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12245
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 3320
telemt_me_refill_failed_total 2
telemt_me_writer_restored_same_endpoint_total 3297
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 29
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 12233
telemt_user_connections_current{user="hello"} 47
telemt_user_octets_from_client{user="hello"} 180846844 (172.47 MB)
telemt_user_octets_to_client{user="hello"} 6549958248 (6.10 GB)
telemt_user_unique_ips_current{user="hello"} 21
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 12273.1 (3h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 38993
telemt_connections_bad_total 1012
telemt_handshake_timeouts_total 153
telemt_upstream_connect_attempt_total 2703
telemt_upstream_connect_success_total 2685
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 2703
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1340
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1344
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_reconnect_attempts_total 2059
telemt_me_reconnect_success_total 2052
telemt_me_reader_eof_total 2153
telemt_me_idle_close_by_peer_total 2153
telemt_me_route_drop_no_conn_total 21899
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 38229
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
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 2043
telemt_me_writer_restored_same_endpoint_total 2025
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_user_connections_total{user="hello"} 36798
telemt_user_connections_current{user="hello"} 250
telemt_user_octets_from_client{user="hello"} 1222827100 (1.14 GB)
telemt_user_octets_to_client{user="hello"} 24734429620 (23.04 GB)
telemt_user_unique_ips_current{user="hello"} 114
telemt_user_unique_ips_recent_window{user="hello"} 39
```