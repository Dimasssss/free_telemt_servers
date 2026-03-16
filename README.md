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

## 4vps.su
- Локация: Польша, Варшава
- Тариф: PL-cx21
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 2 Gbit/s
- Цена в месяц: 770 RUB
- Оплачен до: 16 апреля
- Ссылка:
```bash
tg://proxy?server=s7.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-16 22:15:50 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 12629.3 (3h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 79656
telemt_connections_bad_total 718
telemt_handshake_timeouts_total 3587
telemt_upstream_connect_attempt_total 2355
telemt_upstream_connect_success_total 2338
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 2355
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1061
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1275
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1704
telemt_me_reconnect_success_total 1696
telemt_me_reader_eof_total 1770
telemt_me_idle_close_by_peer_total 1770
telemt_me_route_drop_no_conn_total 26992
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 71593
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 365
telemt_desync_full_logged_total 98
telemt_desync_suppressed_total 267
telemt_desync_frames_bucket_total{bucket="1_2"} 113
telemt_desync_frames_bucket_total{bucket="3_10"} 145
telemt_desync_frames_bucket_total{bucket="gt_10"} 107
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 1702
telemt_me_writer_restored_same_endpoint_total 1675
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 71547
telemt_user_connections_current{user="hello"} 386
telemt_user_octets_from_client{user="hello"} 1354568128 (1.26 GB)
telemt_user_octets_to_client{user="hello"} 45857535476 (42.71 GB)
telemt_user_unique_ips_current{user="hello"} 128
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 12880.9 (3h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 59444
telemt_connections_bad_total 505
telemt_handshake_timeouts_total 2728
telemt_upstream_connect_attempt_total 2847
telemt_upstream_connect_success_total 2811
telemt_upstream_connect_fail_total 36
telemt_upstream_connect_attempts_per_request{bucket="1"} 2847
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1230
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1519
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 36
telemt_me_reconnect_attempts_total 2142
telemt_me_reconnect_success_total 2137
telemt_me_reader_eof_total 2244
telemt_me_idle_close_by_peer_total 2244
telemt_me_route_drop_no_conn_total 23247
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 53879
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 113
telemt_desync_full_logged_total 31
telemt_desync_suppressed_total 82
telemt_desync_frames_bucket_total{bucket="1_2"} 28
telemt_desync_frames_bucket_total{bucket="3_10"} 47
telemt_desync_frames_bucket_total{bucket="gt_10"} 38
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 2164
telemt_me_writer_restored_same_endpoint_total 2121
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 53861
telemt_user_connections_current{user="hello"} 196
telemt_user_octets_from_client{user="hello"} 815769012 (777.98 MB)
telemt_user_octets_to_client{user="hello"} 24237781224 (22.57 GB)
telemt_user_unique_ips_current{user="hello"} 64
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 12657.3 (3h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 30962
telemt_connections_bad_total 384
telemt_handshake_timeouts_total 238
telemt_upstream_connect_attempt_total 3156
telemt_upstream_connect_success_total 3137
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 3156
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1311
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1815
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_reconnect_attempts_total 2493
telemt_me_reconnect_success_total 2472
telemt_me_reader_eof_total 2606
telemt_me_idle_close_by_peer_total 2606
telemt_me_route_drop_no_conn_total 10485
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 29559
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
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 2498
telemt_me_writer_restored_same_endpoint_total 2461
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 26
telemt_user_connections_total{user="hello"} 29555
telemt_user_connections_current{user="hello"} 127
telemt_user_octets_from_client{user="hello"} 604212052 (576.22 MB)
telemt_user_octets_to_client{user="hello"} 11425484952 (10.64 GB)
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 12716.8 (3h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 60099
telemt_connections_bad_total 2983
telemt_handshake_timeouts_total 440
telemt_upstream_connect_attempt_total 2692
telemt_upstream_connect_success_total 2658
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 2692
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1253
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1387
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_reconnect_attempts_total 1991
telemt_me_reconnect_success_total 1971
telemt_me_reader_eof_total 2054
telemt_me_idle_close_by_peer_total 2054
telemt_me_route_drop_no_conn_total 19231
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 54943
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 140
telemt_desync_full_logged_total 37
telemt_desync_suppressed_total 103
telemt_desync_frames_bucket_total{bucket="1_2"} 29
telemt_desync_frames_bucket_total{bucket="3_10"} 54
telemt_desync_frames_bucket_total{bucket="gt_10"} 57
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 1997
telemt_me_writer_restored_same_endpoint_total 1964
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 26
telemt_user_connections_total{user="hello"} 54929
telemt_user_connections_current{user="hello"} 207
telemt_user_octets_from_client{user="hello"} 745612248 (711.07 MB)
telemt_user_octets_to_client{user="hello"} 24004485960 (22.36 GB)
telemt_user_unique_ips_current{user="hello"} 74
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 12688.8 (3h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 42072
telemt_connections_bad_total 12823
telemt_handshake_timeouts_total 196
telemt_upstream_connect_attempt_total 3489
telemt_upstream_connect_success_total 3430
telemt_upstream_connect_fail_total 59
telemt_upstream_connect_attempts_per_request{bucket="1"} 3489
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1516
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1823
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 59
telemt_me_reconnect_attempts_total 3872
telemt_me_reconnect_success_total 2763
telemt_me_reader_eof_total 2841
telemt_me_idle_close_by_peer_total 2841
telemt_me_route_drop_no_conn_total 11128
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 27705
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
telemt_me_writer_removed_unexpected_total 2864
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 2755
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 101
telemt_user_connections_total{user="hello"} 27701
telemt_user_connections_current{user="hello"} 111
telemt_user_octets_from_client{user="hello"} 233185280 (222.38 MB)
telemt_user_octets_to_client{user="hello"} 8324528236 (7.75 GB)
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 12850.0 (3h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 89384
telemt_connections_bad_total 1100
telemt_handshake_timeouts_total 757
telemt_upstream_connect_attempt_total 2490
telemt_upstream_connect_success_total 2473
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 2490
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1187
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1282
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_reconnect_attempts_total 1804
telemt_me_reconnect_success_total 1801
telemt_me_reader_eof_total 1907
telemt_me_idle_close_by_peer_total 1907
telemt_me_route_drop_no_conn_total 54088
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 93027
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 54
telemt_desync_full_logged_total 26
telemt_desync_suppressed_total 28
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 22
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 1827
telemt_me_writer_restored_same_endpoint_total 1791
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 26
telemt_user_connections_total{user="hello"} 84588
telemt_user_connections_current{user="hello"} 409
telemt_user_octets_from_client{user="hello"} 1713619872 (1.60 GB)
telemt_user_octets_to_client{user="hello"} 48635129444 (45.29 GB)
telemt_user_unique_ips_current{user="hello"} 157
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 856.3 (0h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 37
telemt_connections_bad_total 1
telemt_upstream_connect_attempt_total 108
telemt_upstream_connect_success_total 108
telemt_upstream_connect_attempts_per_request{bucket="1"} 108
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 55
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 53
telemt_me_reconnect_attempts_total 40
telemt_me_reconnect_success_total 37
telemt_me_reader_eof_total 27
telemt_me_idle_close_by_peer_total 27
telemt_me_route_drop_no_conn_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 36
telemt_me_writer_pick_total{mode="p2c",result="full"} 3
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_writer_removed_unexpected_total 34
telemt_me_writer_restored_same_endpoint_total 37
telemt_me_async_recovery_trigger_total 18
telemt_user_connections_total{user="hello"} 36
telemt_user_octets_from_client{user="hello"} 157473040 (150.18 MB)
telemt_user_octets_to_client{user="hello"} 23027108 (21.96 MB)
```