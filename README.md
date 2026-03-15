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

# Server Metrics 2026-03-15 01:13:36 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 10748.9 (2h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 22402
telemt_connections_bad_total 366
telemt_handshake_timeouts_total 264
telemt_upstream_connect_attempt_total 2732
telemt_upstream_connect_success_total 2718
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 2732
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1251
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1463
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_reconnect_attempts_total 2181
telemt_me_reconnect_success_total 2170
telemt_me_reader_eof_total 2284
telemt_me_idle_close_by_peer_total 2284
telemt_me_route_drop_no_conn_total 6179
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 21065
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 128
telemt_desync_full_logged_total 56
telemt_desync_suppressed_total 72
telemt_desync_frames_bucket_total{bucket="1_2"} 22
telemt_desync_frames_bucket_total{bucket="3_10"} 42
telemt_desync_frames_bucket_total{bucket="gt_10"} 64
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 2173
telemt_me_writer_restored_same_endpoint_total 2139
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 21063
telemt_user_connections_current{user="hello"} 247
telemt_user_octets_from_client{user="hello"} 228225552 (217.65 MB)
telemt_user_octets_to_client{user="hello"} 7157860424 (6.67 GB)
telemt_user_unique_ips_current{user="hello"} 71
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 10755.4 (2h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10375
telemt_connections_bad_total 16
telemt_handshake_timeouts_total 30
telemt_upstream_connect_attempt_total 2980
telemt_upstream_connect_success_total 2980
telemt_upstream_connect_attempts_per_request{bucket="1"} 2980
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1312
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1668
telemt_me_reconnect_attempts_total 2437
telemt_me_reconnect_success_total 2430
telemt_me_reader_eof_total 2577
telemt_me_idle_close_by_peer_total 2577
telemt_me_route_drop_no_conn_total 3449
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9785
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 2441
telemt_me_writer_restored_same_endpoint_total 2414
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 9788
telemt_user_connections_current{user="hello"} 117
telemt_user_octets_from_client{user="hello"} 140092420 (133.60 MB)
telemt_user_octets_to_client{user="hello"} 1740809420 (1.62 GB)
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 10747.9 (2h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10590
telemt_connections_bad_total 84
telemt_handshake_timeouts_total 206
telemt_upstream_connect_attempt_total 2826
telemt_upstream_connect_success_total 2825
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 2826
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1254
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1567
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 2286
telemt_me_reconnect_success_total 2273
telemt_me_reader_eof_total 2437
telemt_me_idle_close_by_peer_total 2437
telemt_me_route_drop_no_conn_total 3584
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9979
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 2286
telemt_me_writer_restored_same_endpoint_total 2269
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 13
telemt_user_connections_total{user="hello"} 9951
telemt_user_connections_current{user="hello"} 67
telemt_user_octets_from_client{user="hello"} 2409144452 (2.24 GB)
telemt_user_octets_to_client{user="hello"} 10983586176 (10.23 GB)
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 10747.8 (2h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10869
telemt_connections_bad_total 74
telemt_handshake_timeouts_total 38
telemt_upstream_connect_attempt_total 2589
telemt_upstream_connect_success_total 2588
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 2589
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1173
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1409
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 2053
telemt_me_reconnect_success_total 2043
telemt_me_reader_eof_total 2161
telemt_me_idle_close_by_peer_total 2161
telemt_me_route_drop_no_conn_total 4286
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10484
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
telemt_me_writer_removed_unexpected_total 2057
telemt_me_writer_restored_same_endpoint_total 2032
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 10482
telemt_user_connections_current{user="hello"} 136
telemt_user_octets_from_client{user="hello"} 278790296 (265.88 MB)
telemt_user_octets_to_client{user="hello"} 8148186952 (7.59 GB)
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 10747.8 (2h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13582
telemt_connections_bad_total 2227
telemt_handshake_timeouts_total 381
telemt_upstream_connect_attempt_total 3403
telemt_upstream_connect_success_total 3360
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 3403
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1589
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1763
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_reconnect_attempts_total 2889
telemt_me_reconnect_success_total 2811
telemt_me_reader_eof_total 2946
telemt_me_idle_close_by_peer_total 2946
telemt_me_route_drop_no_conn_total 3574
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10712
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 2818
telemt_me_refill_failed_total 2
telemt_me_writer_restored_same_endpoint_total 2799
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 29
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 10700
telemt_user_connections_current{user="hello"} 86
telemt_user_octets_from_client{user="hello"} 168062152 (160.28 MB)
telemt_user_octets_to_client{user="hello"} 6228817508 (5.80 GB)
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 10746.9 (2h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 34573
telemt_connections_bad_total 987
telemt_handshake_timeouts_total 126
telemt_upstream_connect_attempt_total 2352
telemt_upstream_connect_success_total 2339
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 2352
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1174
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1165
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_reconnect_attempts_total 1799
telemt_me_reconnect_success_total 1793
telemt_me_reader_eof_total 1871
telemt_me_idle_close_by_peer_total 1871
telemt_me_route_drop_no_conn_total 19623
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 33986
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
telemt_me_writer_removed_unexpected_total 1783
telemt_me_writer_restored_same_endpoint_total 1766
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_user_connections_total{user="hello"} 32555
telemt_user_connections_current{user="hello"} 263
telemt_user_octets_from_client{user="hello"} 550257976 (524.77 MB)
telemt_user_octets_to_client{user="hello"} 23149932176 (21.56 GB)
telemt_user_unique_ips_current{user="hello"} 116
telemt_user_unique_ips_recent_window{user="hello"} 39
```