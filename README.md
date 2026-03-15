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

# Server Metrics 2026-03-15 01:03:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 10137.9 (2h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21080
telemt_connections_bad_total 366
telemt_handshake_timeouts_total 262
telemt_upstream_connect_attempt_total 2606
telemt_upstream_connect_success_total 2592
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 2606
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1213
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1375
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_reconnect_attempts_total 2055
telemt_me_reconnect_success_total 2044
telemt_me_reader_eof_total 2157
telemt_me_idle_close_by_peer_total 2157
telemt_me_route_drop_no_conn_total 5878
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 19772
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 127
telemt_desync_full_logged_total 55
telemt_desync_suppressed_total 72
telemt_desync_frames_bucket_total{bucket="1_2"} 22
telemt_desync_frames_bucket_total{bucket="3_10"} 41
telemt_desync_frames_bucket_total{bucket="gt_10"} 64
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 2046
telemt_me_writer_restored_same_endpoint_total 2013
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 19770
telemt_user_connections_current{user="hello"} 272
telemt_user_octets_from_client{user="hello"} 219711420 (209.53 MB)
telemt_user_octets_to_client{user="hello"} 6850891460 (6.38 GB)
telemt_user_unique_ips_current{user="hello"} 77
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 10144.5 (2h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9778
telemt_connections_bad_total 16
telemt_handshake_timeouts_total 30
telemt_upstream_connect_attempt_total 2856
telemt_upstream_connect_success_total 2856
telemt_upstream_connect_attempts_per_request{bucket="1"} 2856
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1260
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1596
telemt_me_reconnect_attempts_total 2313
telemt_me_reconnect_success_total 2307
telemt_me_reader_eof_total 2454
telemt_me_idle_close_by_peer_total 2454
telemt_me_route_drop_no_conn_total 3121
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9218
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 2318
telemt_me_writer_restored_same_endpoint_total 2291
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 9221
telemt_user_connections_current{user="hello"} 114
telemt_user_octets_from_client{user="hello"} 117010208 (111.59 MB)
telemt_user_octets_to_client{user="hello"} 1625685504 (1.51 GB)
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 10137.0 (2h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10003
telemt_connections_bad_total 84
telemt_handshake_timeouts_total 201
telemt_upstream_connect_attempt_total 2703
telemt_upstream_connect_success_total 2702
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 2703
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1215
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1483
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 2163
telemt_me_reconnect_success_total 2151
telemt_me_reader_eof_total 2313
telemt_me_idle_close_by_peer_total 2313
telemt_me_route_drop_no_conn_total 3353
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9414
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 2162
telemt_me_writer_restored_same_endpoint_total 2147
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 9386
telemt_user_connections_current{user="hello"} 83
telemt_user_octets_from_client{user="hello"} 1556113540 (1.45 GB)
telemt_user_octets_to_client{user="hello"} 10934450752 (10.18 GB)
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 10136.7 (2h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10271
telemt_connections_bad_total 74
telemt_handshake_timeouts_total 38
telemt_upstream_connect_attempt_total 2494
telemt_upstream_connect_success_total 2493
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 2494
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1138
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1351
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 1958
telemt_me_reconnect_success_total 1949
telemt_me_reader_eof_total 2065
telemt_me_idle_close_by_peer_total 2065
telemt_me_route_drop_no_conn_total 4069
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9893
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
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 1961
telemt_me_writer_restored_same_endpoint_total 1938
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 9893
telemt_user_connections_current{user="hello"} 160
telemt_user_octets_from_client{user="hello"} 247866348 (236.38 MB)
telemt_user_octets_to_client{user="hello"} 6994846960 (6.51 GB)
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 10136.9 (2h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12882
telemt_connections_bad_total 2117
telemt_handshake_timeouts_total 372
telemt_upstream_connect_attempt_total 3281
telemt_upstream_connect_success_total 3238
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 3281
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1549
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1681
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_reconnect_attempts_total 2767
telemt_me_reconnect_success_total 2690
telemt_me_reader_eof_total 2822
telemt_me_idle_close_by_peer_total 2822
telemt_me_route_drop_no_conn_total 3211
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10147
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 2694
telemt_me_refill_failed_total 2
telemt_me_writer_restored_same_endpoint_total 2678
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 29
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 10135
telemt_user_connections_current{user="hello"} 75
telemt_user_octets_from_client{user="hello"} 161436728 (153.96 MB)
telemt_user_octets_to_client{user="hello"} 5668065724 (5.28 GB)
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 10136.0 (2h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 32833
telemt_connections_bad_total 903
telemt_handshake_timeouts_total 123
telemt_upstream_connect_attempt_total 2256
telemt_upstream_connect_success_total 2243
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 2256
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1130
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1113
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_reconnect_attempts_total 1703
telemt_me_reconnect_success_total 1697
telemt_me_reader_eof_total 1773
telemt_me_idle_close_by_peer_total 1773
telemt_me_route_drop_no_conn_total 18821
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 32358
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
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 1685
telemt_me_writer_restored_same_endpoint_total 1670
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_user_connections_total{user="hello"} 30927
telemt_user_connections_current{user="hello"} 254
telemt_user_octets_from_client{user="hello"} 475646736 (453.61 MB)
telemt_user_octets_to_client{user="hello"} 22387719060 (20.85 GB)
telemt_user_unique_ips_current{user="hello"} 123
telemt_user_unique_ips_recent_window{user="hello"} 40
```