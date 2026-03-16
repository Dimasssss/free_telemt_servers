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

# Server Metrics 2026-03-16 21:41:24 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 10563.1 (2h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 68418
telemt_connections_bad_total 700
telemt_handshake_timeouts_total 3203
telemt_upstream_connect_attempt_total 1960
telemt_upstream_connect_success_total 1946
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 1960
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 872
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1072
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_reconnect_attempts_total 1404
telemt_me_reconnect_success_total 1398
telemt_me_reader_eof_total 1454
telemt_me_idle_close_by_peer_total 1454
telemt_me_route_drop_no_conn_total 23716
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 61567
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 323
telemt_desync_full_logged_total 89
telemt_desync_suppressed_total 234
telemt_desync_frames_bucket_total{bucket="1_2"} 107
telemt_desync_frames_bucket_total{bucket="3_10"} 129
telemt_desync_frames_bucket_total{bucket="gt_10"} 87
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 1401
telemt_me_writer_restored_same_endpoint_total 1377
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 61522
telemt_user_connections_current{user="hello"} 432
telemt_user_octets_from_client{user="hello"} 1173721000 (1.09 GB)
telemt_user_octets_to_client{user="hello"} 40886289232 (38.08 GB)
telemt_user_unique_ips_current{user="hello"} 139
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 10814.5 (3h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 53897
telemt_connections_bad_total 94
telemt_handshake_timeouts_total 2691
telemt_upstream_connect_attempt_total 2298
telemt_upstream_connect_success_total 2270
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 2298
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 985
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1223
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_reconnect_attempts_total 1730
telemt_me_reconnect_success_total 1726
telemt_me_reader_eof_total 1798
telemt_me_idle_close_by_peer_total 1798
telemt_me_route_drop_no_conn_total 21176
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 48934
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 112
telemt_desync_full_logged_total 30
telemt_desync_suppressed_total 82
telemt_desync_frames_bucket_total{bucket="1_2"} 28
telemt_desync_frames_bucket_total{bucket="3_10"} 46
telemt_desync_frames_bucket_total{bucket="gt_10"} 38
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 1751
telemt_me_writer_restored_same_endpoint_total 1710
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 25
telemt_user_connections_total{user="hello"} 48916
telemt_user_connections_current{user="hello"} 259
telemt_user_octets_from_client{user="hello"} 750495532 (715.73 MB)
telemt_user_octets_to_client{user="hello"} 20436353016 (19.03 GB)
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 10590.6 (2h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 28113
telemt_connections_bad_total 370
telemt_handshake_timeouts_total 182
telemt_upstream_connect_attempt_total 2605
telemt_upstream_connect_success_total 2587
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 2605
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1085
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1491
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_reconnect_attempts_total 2053
telemt_me_reconnect_success_total 2034
telemt_me_reader_eof_total 2138
telemt_me_idle_close_by_peer_total 2138
telemt_me_route_drop_no_conn_total 9514
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 26858
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16
telemt_desync_full_logged_total 7
telemt_desync_suppressed_total 9
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 6
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 2055
telemt_me_writer_restored_same_endpoint_total 2023
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 21
telemt_user_connections_total{user="hello"} 26854
telemt_user_connections_current{user="hello"} 126
telemt_user_octets_from_client{user="hello"} 586811564 (559.63 MB)
telemt_user_octets_to_client{user="hello"} 9688453392 (9.02 GB)
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 10649.9 (2h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 55240
telemt_connections_bad_total 2959
telemt_handshake_timeouts_total 375
telemt_upstream_connect_attempt_total 2221
telemt_upstream_connect_success_total 2192
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 2221
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1025
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1149
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_reconnect_attempts_total 1655
telemt_me_reconnect_success_total 1636
telemt_me_reader_eof_total 1700
telemt_me_idle_close_by_peer_total 1700
telemt_me_route_drop_no_conn_total 17840
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 50404
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 135
telemt_desync_full_logged_total 33
telemt_desync_suppressed_total 102
telemt_desync_frames_bucket_total{bucket="1_2"} 28
telemt_desync_frames_bucket_total{bucket="3_10"} 54
telemt_desync_frames_bucket_total{bucket="gt_10"} 53
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 1657
telemt_me_writer_restored_same_endpoint_total 1629
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 21
telemt_user_connections_total{user="hello"} 50391
telemt_user_connections_current{user="hello"} 218
telemt_user_octets_from_client{user="hello"} 719793432 (686.45 MB)
telemt_user_octets_to_client{user="hello"} 21982035392 (20.47 GB)
telemt_user_unique_ips_current{user="hello"} 73
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 10622.0 (2h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 38016
telemt_connections_bad_total 11795
telemt_handshake_timeouts_total 190
telemt_upstream_connect_attempt_total 2664
telemt_upstream_connect_success_total 2617
telemt_upstream_connect_fail_total 47
telemt_upstream_connect_attempts_per_request{bucket="1"} 2664
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1160
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1368
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 47
telemt_me_reconnect_attempts_total 3178
telemt_me_reconnect_success_total 2070
telemt_me_reader_eof_total 2140
telemt_me_idle_close_by_peer_total 2140
telemt_me_route_drop_no_conn_total 10092
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 24840
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 31
telemt_desync_full_logged_total 12
telemt_desync_suppressed_total 19
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 13
telemt_desync_frames_bucket_total{bucket="gt_10"} 12
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 2163
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 2062
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 93
telemt_user_connections_total{user="hello"} 24836
telemt_user_connections_current{user="hello"} 108
telemt_user_octets_from_client{user="hello"} 217691644 (207.61 MB)
telemt_user_octets_to_client{user="hello"} 7208823756 (6.71 GB)
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 10782.9 (2h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 79982
telemt_connections_bad_total 959
telemt_handshake_timeouts_total 734
telemt_upstream_connect_attempt_total 2035
telemt_upstream_connect_success_total 2021
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 2035
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 981
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1036
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_reconnect_attempts_total 1481
telemt_me_reconnect_success_total 1478
telemt_me_reader_eof_total 1551
telemt_me_idle_close_by_peer_total 1551
telemt_me_route_drop_no_conn_total 42243
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 77888
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 49
telemt_desync_full_logged_total 25
telemt_desync_suppressed_total 24
telemt_desync_frames_bucket_total{bucket="1_2"} 11
telemt_desync_frames_bucket_total{bucket="3_10"} 19
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 1498
telemt_me_writer_restored_same_endpoint_total 1468
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 75674
telemt_user_connections_current{user="hello"} 410
telemt_user_octets_from_client{user="hello"} 1593015572 (1.48 GB)
telemt_user_octets_to_client{user="hello"} 40890799568 (38.08 GB)
telemt_user_unique_ips_current{user="hello"} 161
telemt_user_unique_ips_recent_window{user="hello"} 39
```