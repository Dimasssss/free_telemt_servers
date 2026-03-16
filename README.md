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

# Server Metrics 2026-03-16 22:26:01 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 13239.7 (3h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 82274
telemt_connections_bad_total 874
telemt_handshake_timeouts_total 3857
telemt_upstream_connect_attempt_total 2508
telemt_upstream_connect_success_total 2489
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 2508
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1127
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1360
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1818
telemt_me_reconnect_success_total 1809
telemt_me_reader_eof_total 1893
telemt_me_idle_close_by_peer_total 1893
telemt_me_route_drop_no_conn_total 27546
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 73713
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 401
telemt_desync_full_logged_total 106
telemt_desync_suppressed_total 295
telemt_desync_frames_bucket_total{bucket="1_2"} 114
telemt_desync_frames_bucket_total{bucket="3_10"} 165
telemt_desync_frames_bucket_total{bucket="gt_10"} 122
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 1816
telemt_me_writer_restored_same_endpoint_total 1788
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 73669
telemt_user_connections_current{user="hello"} 337
telemt_user_octets_from_client{user="hello"} 1384784068 (1.29 GB)
telemt_user_octets_to_client{user="hello"} 46310361476 (43.13 GB)
telemt_user_unique_ips_current{user="hello"} 122
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 13491.0 (3h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 60449
telemt_connections_bad_total 505
telemt_handshake_timeouts_total 2733
telemt_upstream_connect_attempt_total 2938
telemt_upstream_connect_success_total 2902
telemt_upstream_connect_fail_total 36
telemt_upstream_connect_attempts_per_request{bucket="1"} 2938
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1262
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1578
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 36
telemt_me_reconnect_attempts_total 2233
telemt_me_reconnect_success_total 2227
telemt_me_reader_eof_total 2334
telemt_me_idle_close_by_peer_total 2334
telemt_me_route_drop_no_conn_total 24029
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 54835
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 114
telemt_desync_full_logged_total 32
telemt_desync_suppressed_total 82
telemt_desync_frames_bucket_total{bucket="1_2"} 28
telemt_desync_frames_bucket_total{bucket="3_10"} 48
telemt_desync_frames_bucket_total{bucket="gt_10"} 38
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 2254
telemt_me_writer_restored_same_endpoint_total 2211
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 54817
telemt_user_connections_current{user="hello"} 180
telemt_user_octets_from_client{user="hello"} 822167744 (784.08 MB)
telemt_user_octets_to_client{user="hello"} 24515153716 (22.83 GB)
telemt_user_unique_ips_current{user="hello"} 64
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 13267.3 (3h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 31719
telemt_connections_bad_total 397
telemt_handshake_timeouts_total 241
telemt_upstream_connect_attempt_total 3324
telemt_upstream_connect_success_total 3305
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 3324
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1390
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1904
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_reconnect_attempts_total 2640
telemt_me_reconnect_success_total 2618
telemt_me_reader_eof_total 2768
telemt_me_idle_close_by_peer_total 2768
telemt_me_route_drop_no_conn_total 10981
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 30288
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
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 2645
telemt_me_writer_restored_same_endpoint_total 2607
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 30284
telemt_user_connections_current{user="hello"} 127
telemt_user_octets_from_client{user="hello"} 609498892 (581.26 MB)
telemt_user_octets_to_client{user="hello"} 11923453656 (11.10 GB)
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 13326.6 (3h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 61247
telemt_connections_bad_total 2984
telemt_handshake_timeouts_total 440
telemt_upstream_connect_attempt_total 2823
telemt_upstream_connect_success_total 2788
telemt_upstream_connect_fail_total 35
telemt_upstream_connect_attempts_per_request{bucket="1"} 2823
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1310
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1460
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 35
telemt_me_reconnect_attempts_total 2122
telemt_me_reconnect_success_total 2101
telemt_me_reader_eof_total 2198
telemt_me_idle_close_by_peer_total 2198
telemt_me_route_drop_no_conn_total 19595
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 56061
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 141
telemt_desync_full_logged_total 38
telemt_desync_suppressed_total 103
telemt_desync_frames_bucket_total{bucket="1_2"} 29
telemt_desync_frames_bucket_total{bucket="3_10"} 54
telemt_desync_frames_bucket_total{bucket="gt_10"} 58
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 2128
telemt_me_writer_restored_same_endpoint_total 2094
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 56047
telemt_user_connections_current{user="hello"} 203
telemt_user_octets_from_client{user="hello"} 752923356 (718.04 MB)
telemt_user_octets_to_client{user="hello"} 24552863284 (22.87 GB)
telemt_user_unique_ips_current{user="hello"} 69
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 13298.6 (3h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 42968
telemt_connections_bad_total 12932
telemt_handshake_timeouts_total 196
telemt_upstream_connect_attempt_total 3647
telemt_upstream_connect_success_total 3587
telemt_upstream_connect_fail_total 60
telemt_upstream_connect_attempts_per_request{bucket="1"} 3647
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1593
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1903
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 60
telemt_me_reconnect_attempts_total 4019
telemt_me_reconnect_success_total 2909
telemt_me_reader_eof_total 3017
telemt_me_idle_close_by_peer_total 3017
telemt_me_route_drop_no_conn_total 11479
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 28471
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
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 3012
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 2901
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 103
telemt_user_connections_total{user="hello"} 28467
telemt_user_connections_current{user="hello"} 134
telemt_user_octets_from_client{user="hello"} 238513592 (227.46 MB)
telemt_user_octets_to_client{user="hello"} 9095266804 (8.47 GB)
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 13459.4 (3h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 92564
telemt_connections_bad_total 1154
telemt_handshake_timeouts_total 790
telemt_upstream_connect_attempt_total 2578
telemt_upstream_connect_success_total 2561
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 2578
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1221
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1336
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_reconnect_attempts_total 1892
telemt_me_reconnect_success_total 1889
telemt_me_reader_eof_total 1997
telemt_me_idle_close_by_peer_total 1997
telemt_me_route_drop_no_conn_total 59794
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 99791
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 60
telemt_desync_full_logged_total 29
telemt_desync_suppressed_total 31
telemt_desync_frames_bucket_total{bucket="1_2"} 14
telemt_desync_frames_bucket_total{bucket="3_10"} 22
telemt_desync_frames_bucket_total{bucket="gt_10"} 24
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 1917
telemt_me_writer_restored_same_endpoint_total 1879
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 28
telemt_user_connections_total{user="hello"} 87506
telemt_user_connections_current{user="hello"} 397
telemt_user_octets_from_client{user="hello"} 1746734996 (1.63 GB)
telemt_user_octets_to_client{user="hello"} 51322621636 (47.80 GB)
telemt_user_unique_ips_current{user="hello"} 148
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 1466.1 (0h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 40
telemt_connections_bad_total 4
telemt_upstream_connect_attempt_total 382
telemt_upstream_connect_success_total 382
telemt_upstream_connect_attempts_per_request{bucket="1"} 382
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 211
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 171
telemt_me_reconnect_attempts_total 271
telemt_me_reconnect_success_total 267
telemt_me_reader_eof_total 265
telemt_me_idle_close_by_peer_total 265
telemt_me_route_drop_no_conn_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 36
telemt_me_writer_pick_total{mode="p2c",result="full"} 3
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 265
telemt_me_writer_restored_same_endpoint_total 267
telemt_me_async_recovery_trigger_total 18
telemt_user_connections_total{user="hello"} 36
telemt_user_octets_from_client{user="hello"} 157473040 (150.18 MB)
telemt_user_octets_to_client{user="hello"} 23027108 (21.96 MB)
```