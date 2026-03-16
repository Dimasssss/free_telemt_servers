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

# Server Metrics 2026-03-16 23:16:55 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 16293.4 (4h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 99368
telemt_connections_bad_total 1513
telemt_handshake_timeouts_total 4460
telemt_upstream_connect_attempt_total 3297
telemt_upstream_connect_success_total 3275
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 3297
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1468
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1802
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 2429
telemt_me_reconnect_success_total 2420
telemt_me_reader_eof_total 2533
telemt_me_idle_close_by_peer_total 2533
telemt_me_route_drop_no_conn_total 31991
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 89132
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 513
telemt_desync_full_logged_total 144
telemt_desync_suppressed_total 369
telemt_desync_frames_bucket_total{bucket="1_2"} 121
telemt_desync_frames_bucket_total{bucket="3_10"} 233
telemt_desync_frames_bucket_total{bucket="gt_10"} 159
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 2435
telemt_me_writer_restored_same_endpoint_total 2399
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 15
telemt_user_connections_total{user="hello"} 89088
telemt_user_connections_current{user="hello"} 382
telemt_user_octets_from_client{user="hello"} 1496286636 (1.39 GB)
telemt_user_octets_to_client{user="hello"} 49971760912 (46.54 GB)
telemt_user_unique_ips_current{user="hello"} 133
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 16544.8 (4h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 66456
telemt_connections_bad_total 840
telemt_handshake_timeouts_total 2764
telemt_upstream_connect_attempt_total 3788
telemt_upstream_connect_success_total 3739
telemt_upstream_connect_fail_total 49
telemt_upstream_connect_attempts_per_request{bucket="1"} 3788
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1641
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2023
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 49
telemt_me_reconnect_attempts_total 2897
telemt_me_reconnect_success_total 2891
telemt_me_reader_eof_total 3043
telemt_me_idle_close_by_peer_total 3043
telemt_me_route_drop_no_conn_total 26681
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 60031
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
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 2928
telemt_me_writer_restored_same_endpoint_total 2875
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 59980
telemt_user_connections_current{user="hello"} 210
telemt_user_octets_from_client{user="hello"} 855921416 (816.27 MB)
telemt_user_octets_to_client{user="hello"} 27489107904 (25.60 GB)
telemt_user_unique_ips_current{user="hello"} 72
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 16320.7 (4h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 35990
telemt_connections_bad_total 421
telemt_handshake_timeouts_total 739
telemt_upstream_connect_attempt_total 4166
telemt_upstream_connect_success_total 4137
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 4165
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1756
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2359
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_reconnect_attempts_total 3301
telemt_me_reconnect_success_total 3277
telemt_me_reader_eof_total 3484
telemt_me_idle_close_by_peer_total 3484
telemt_me_route_drop_no_conn_total 12527
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 33936
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
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 3311
telemt_me_writer_restored_same_endpoint_total 3266
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 34
telemt_user_connections_total{user="hello"} 33932
telemt_user_connections_current{user="hello"} 99
telemt_user_octets_from_client{user="hello"} 632234348 (602.95 MB)
telemt_user_octets_to_client{user="hello"} 13787485252 (12.84 GB)
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 16380.1 (4h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 66480
telemt_connections_bad_total 2991
telemt_handshake_timeouts_total 446
telemt_upstream_connect_attempt_total 3595
telemt_upstream_connect_success_total 3553
telemt_upstream_connect_fail_total 42
telemt_upstream_connect_attempts_per_request{bucket="1"} 3595
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1678
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1853
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 42
telemt_me_reconnect_attempts_total 2717
telemt_me_reconnect_success_total 2691
telemt_me_reader_eof_total 2834
telemt_me_idle_close_by_peer_total 2834
telemt_me_route_drop_no_conn_total 21557
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 61186
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 143
telemt_desync_full_logged_total 40
telemt_desync_suppressed_total 103
telemt_desync_frames_bucket_total{bucket="1_2"} 29
telemt_desync_frames_bucket_total{bucket="3_10"} 55
telemt_desync_frames_bucket_total{bucket="gt_10"} 59
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 2724
telemt_me_writer_restored_same_endpoint_total 2684
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 61171
telemt_user_connections_current{user="hello"} 175
telemt_user_octets_from_client{user="hello"} 786905856 (750.45 MB)
telemt_user_octets_to_client{user="hello"} 27284738552 (25.41 GB)
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 16352.1 (4h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 47662
telemt_connections_bad_total 13487
telemt_handshake_timeouts_total 202
telemt_upstream_connect_attempt_total 4463
telemt_upstream_connect_success_total 4393
telemt_upstream_connect_fail_total 70
telemt_upstream_connect_attempts_per_request{bucket="1"} 4463
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1979
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2320
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 94
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 70
telemt_me_reconnect_attempts_total 4653
telemt_me_reconnect_success_total 3541
telemt_me_reader_eof_total 3698
telemt_me_idle_close_by_peer_total 3698
telemt_me_route_drop_no_conn_total 12686
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 32502
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
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 3645
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 3533
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 104
telemt_user_connections_total{user="hello"} 32498
telemt_user_connections_current{user="hello"} 77
telemt_user_octets_from_client{user="hello"} 262222148 (250.07 MB)
telemt_user_octets_to_client{user="hello"} 12736765056 (11.86 GB)
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 16513.0 (4h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 107806
telemt_connections_bad_total 1169
telemt_handshake_timeouts_total 886
telemt_upstream_connect_attempt_total 3265
telemt_upstream_connect_success_total 3244
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 3265
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1564
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1676
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_reconnect_attempts_total 2403
telemt_me_reconnect_success_total 2399
telemt_me_reader_eof_total 2551
telemt_me_idle_close_by_peer_total 2551
telemt_me_route_drop_no_conn_total 103605
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 143838
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 95
telemt_desync_full_logged_total 44
telemt_desync_suppressed_total 51
telemt_desync_frames_bucket_total{bucket="1_2"} 20
telemt_desync_frames_bucket_total{bucket="3_10"} 35
telemt_desync_frames_bucket_total{bucket="gt_10"} 40
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 2434
telemt_me_writer_restored_same_endpoint_total 2389
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 101997
telemt_user_connections_current{user="hello"} 373
telemt_user_octets_from_client{user="hello"} 1908005764 (1.78 GB)
telemt_user_octets_to_client{user="hello"} 69207325068 (64.45 GB)
telemt_user_unique_ips_current{user="hello"} 158
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 4519.5 (1h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 92
telemt_connections_bad_total 55
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 1926
telemt_upstream_connect_success_total 1926
telemt_upstream_connect_attempts_per_request{bucket="1"} 1926
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1131
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 792
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 1684
telemt_me_reconnect_success_total 1675
telemt_me_reader_eof_total 1803
telemt_me_idle_close_by_peer_total 1803
telemt_me_route_drop_no_conn_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 36
telemt_me_writer_pick_total{mode="p2c",result="full"} 3
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 1688
telemt_me_writer_restored_same_endpoint_total 1675
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 13
telemt_user_connections_total{user="hello"} 36
telemt_user_octets_from_client{user="hello"} 157473040 (150.18 MB)
telemt_user_octets_to_client{user="hello"} 23027108 (21.96 MB)
```