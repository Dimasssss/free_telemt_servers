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

# Server Metrics 2026-03-15 02:14:41 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 14413.0 (4h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 30735
telemt_connections_bad_total 368
telemt_handshake_timeouts_total 277
telemt_upstream_connect_attempt_total 3654
telemt_upstream_connect_success_total 3632
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 3654
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1641
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1987
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 2921
telemt_me_reconnect_success_total 2908
telemt_me_reader_eof_total 3079
telemt_me_idle_close_by_peer_total 3079
telemt_me_route_drop_no_conn_total 9006
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 29172
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 143
telemt_desync_full_logged_total 67
telemt_desync_suppressed_total 76
telemt_desync_frames_bucket_total{bucket="1_2"} 27
telemt_desync_frames_bucket_total{bucket="3_10"} 49
telemt_desync_frames_bucket_total{bucket="gt_10"} 67
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 2918
telemt_me_writer_restored_same_endpoint_total 2877
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 29170
telemt_user_connections_current{user="hello"} 246
telemt_user_octets_from_client{user="hello"} 324693288 (309.65 MB)
telemt_user_octets_to_client{user="hello"} 11525966812 (10.73 GB)
telemt_user_unique_ips_current{user="hello"} 71
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 14419.6 (4h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13731
telemt_connections_bad_total 22
telemt_handshake_timeouts_total 37
telemt_upstream_connect_attempt_total 3991
telemt_upstream_connect_success_total 3991
telemt_upstream_connect_attempts_per_request{bucket="1"} 3991
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1744
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2244
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 3275
telemt_me_reconnect_success_total 3261
telemt_me_reader_eof_total 3474
telemt_me_idle_close_by_peer_total 3474
telemt_me_route_drop_no_conn_total 5928
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12980
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 3283
telemt_me_writer_restored_same_endpoint_total 3245
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 12984
telemt_user_connections_current{user="hello"} 129
telemt_user_octets_from_client{user="hello"} 522804668 (498.59 MB)
telemt_user_octets_to_client{user="hello"} 2408527640 (2.24 GB)
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 14412.1 (4h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13707
telemt_connections_bad_total 208
telemt_handshake_timeouts_total 245
telemt_upstream_connect_attempt_total 3837
telemt_upstream_connect_success_total 3836
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 3837
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1693
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2137
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 3125
telemt_me_reconnect_success_total 3109
telemt_me_reader_eof_total 3344
telemt_me_idle_close_by_peer_total 3344
telemt_me_route_drop_no_conn_total 4860
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12822
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 3133
telemt_me_writer_restored_same_endpoint_total 3105
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 24
telemt_user_connections_total{user="hello"} 12781
telemt_user_connections_current{user="hello"} 43
telemt_user_octets_from_client{user="hello"} 8616905836 (8.03 GB)
telemt_user_octets_to_client{user="hello"} 13697828980 (12.76 GB)
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 14411.8 (4h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15208
telemt_connections_bad_total 82
telemt_handshake_timeouts_total 55
telemt_upstream_connect_attempt_total 3441
telemt_upstream_connect_success_total 3440
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 3441
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1593
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1838
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 2733
telemt_me_reconnect_success_total 2721
telemt_me_reader_eof_total 2888
telemt_me_idle_close_by_peer_total 2888
telemt_me_route_drop_no_conn_total 5815
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 14445
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 55
telemt_desync_full_logged_total 11
telemt_desync_suppressed_total 44
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 25
telemt_desync_frames_bucket_total{bucket="gt_10"} 23
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 2744
telemt_me_writer_restored_same_endpoint_total 2710
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 14443
telemt_user_connections_current{user="hello"} 154
telemt_user_octets_from_client{user="hello"} 417957736 (398.60 MB)
telemt_user_octets_to_client{user="hello"} 11787468064 (10.98 GB)
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 14412.0 (4h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17510
telemt_connections_bad_total 2884
telemt_handshake_timeouts_total 388
telemt_upstream_connect_attempt_total 4577
telemt_upstream_connect_success_total 4519
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 4577
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2068
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2440
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_reconnect_attempts_total 3876
telemt_me_reconnect_success_total 3796
telemt_me_reader_eof_total 4000
telemt_me_idle_close_by_peer_total 4000
telemt_me_route_drop_no_conn_total 5143
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13902
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 3809
telemt_me_refill_failed_total 2
telemt_me_writer_restored_same_endpoint_total 3784
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 29
telemt_me_writer_removed_unexpected_minus_restored_total 13
telemt_user_connections_total{user="hello"} 13888
telemt_user_connections_current{user="hello"} 36
telemt_user_octets_from_client{user="hello"} 190337064 (181.52 MB)
telemt_user_octets_to_client{user="hello"} 7166203604 (6.67 GB)
telemt_user_unique_ips_current{user="hello"} 19
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 14411.0 (4h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 45343
telemt_connections_bad_total 1158
telemt_handshake_timeouts_total 176
telemt_upstream_connect_attempt_total 3206
telemt_upstream_connect_success_total 3187
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 3206
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1614
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1572
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_reconnect_attempts_total 2473
telemt_me_reconnect_success_total 2465
telemt_me_reader_eof_total 2577
telemt_me_idle_close_by_peer_total 2577
telemt_me_route_drop_no_conn_total 24985
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 44296
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
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 2459
telemt_me_writer_restored_same_endpoint_total 2438
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_user_connections_total{user="hello"} 42865
telemt_user_connections_current{user="hello"} 239
telemt_user_octets_from_client{user="hello"} 1529045888 (1.42 GB)
telemt_user_octets_to_client{user="hello"} 27470161716 (25.58 GB)
telemt_user_unique_ips_current{user="hello"} 109
telemt_user_unique_ips_recent_window{user="hello"} 40
```