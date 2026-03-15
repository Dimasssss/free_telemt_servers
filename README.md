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

# Server Metrics 2026-03-15 01:18:41 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 11054.1 (3h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 23016
telemt_connections_bad_total 366
telemt_handshake_timeouts_total 265
telemt_upstream_connect_attempt_total 2848
telemt_upstream_connect_success_total 2832
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 2848
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1303
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1525
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_reconnect_attempts_total 2252
telemt_me_reconnect_success_total 2241
telemt_me_reader_eof_total 2370
telemt_me_idle_close_by_peer_total 2370
telemt_me_route_drop_no_conn_total 6329
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 21668
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 129
telemt_desync_full_logged_total 57
telemt_desync_suppressed_total 72
telemt_desync_frames_bucket_total{bucket="1_2"} 22
telemt_desync_frames_bucket_total{bucket="3_10"} 42
telemt_desync_frames_bucket_total{bucket="gt_10"} 65
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 2244
telemt_me_writer_restored_same_endpoint_total 2210
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 21666
telemt_user_connections_current{user="hello"} 226
telemt_user_octets_from_client{user="hello"} 232177524 (221.42 MB)
telemt_user_octets_to_client{user="hello"} 7565910620 (7.05 GB)
telemt_user_unique_ips_current{user="hello"} 72
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 11060.8 (3h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10639
telemt_connections_bad_total 16
telemt_handshake_timeouts_total 31
telemt_upstream_connect_attempt_total 3100
telemt_upstream_connect_success_total 3100
telemt_upstream_connect_attempts_per_request{bucket="1"} 3100
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1372
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1728
telemt_me_reconnect_attempts_total 2514
telemt_me_reconnect_success_total 2506
telemt_me_reader_eof_total 2667
telemt_me_idle_close_by_peer_total 2667
telemt_me_route_drop_no_conn_total 3505
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10040
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 2519
telemt_me_writer_restored_same_endpoint_total 2490
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 13
telemt_user_connections_total{user="hello"} 10043
telemt_user_connections_current{user="hello"} 98
telemt_user_octets_from_client{user="hello"} 141768460 (135.20 MB)
telemt_user_octets_to_client{user="hello"} 1761337896 (1.64 GB)
telemt_user_unique_ips_current{user="hello"} 20
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 11053.4 (3h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10947
telemt_connections_bad_total 84
telemt_handshake_timeouts_total 210
telemt_upstream_connect_attempt_total 2954
telemt_upstream_connect_success_total 2953
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 2954
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1314
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1635
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 2371
telemt_me_reconnect_success_total 2358
telemt_me_reader_eof_total 2539
telemt_me_idle_close_by_peer_total 2539
telemt_me_route_drop_no_conn_total 3701
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10327
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 2372
telemt_me_writer_restored_same_endpoint_total 2354
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 10291
telemt_user_connections_current{user="hello"} 76
telemt_user_octets_from_client{user="hello"} 3319558996 (3.09 GB)
telemt_user_octets_to_client{user="hello"} 11261567348 (10.49 GB)
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 11053.0 (3h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11192
telemt_connections_bad_total 74
telemt_handshake_timeouts_total 39
telemt_upstream_connect_attempt_total 2699
telemt_upstream_connect_success_total 2698
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 2699
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1234
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1456
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 2120
telemt_me_reconnect_success_total 2109
telemt_me_reader_eof_total 2238
telemt_me_idle_close_by_peer_total 2238
telemt_me_route_drop_no_conn_total 4458
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10798
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
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 2124
telemt_me_writer_restored_same_endpoint_total 2098
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 15
telemt_user_connections_total{user="hello"} 10796
telemt_user_connections_current{user="hello"} 132
telemt_user_octets_from_client{user="hello"} 292049464 (278.52 MB)
telemt_user_octets_to_client{user="hello"} 8496228608 (7.91 GB)
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 11053.3 (3h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14009
telemt_connections_bad_total 2281
telemt_handshake_timeouts_total 381
telemt_upstream_connect_attempt_total 3559
telemt_upstream_connect_success_total 3511
telemt_upstream_connect_fail_total 48
telemt_upstream_connect_attempts_per_request{bucket="1"} 3559
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1665
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1838
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 48
telemt_me_reconnect_attempts_total 2997
telemt_me_reconnect_success_total 2918
telemt_me_reader_eof_total 3053
telemt_me_idle_close_by_peer_total 3053
telemt_me_route_drop_no_conn_total 3739
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 11074
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 2926
telemt_me_refill_failed_total 2
telemt_me_writer_restored_same_endpoint_total 2906
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 29
telemt_me_writer_removed_unexpected_minus_restored_total 8
telemt_user_connections_total{user="hello"} 11062
telemt_user_connections_current{user="hello"} 61
telemt_user_octets_from_client{user="hello"} 170054564 (162.18 MB)
telemt_user_octets_to_client{user="hello"} 6280738632 (5.85 GB)
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 11052.2 (3h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 35555
telemt_connections_bad_total 988
telemt_handshake_timeouts_total 126
telemt_upstream_connect_attempt_total 2456
telemt_upstream_connect_success_total 2439
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 2456
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1229
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1210
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_reconnect_attempts_total 1856
telemt_me_reconnect_success_total 1850
telemt_me_reader_eof_total 1938
telemt_me_idle_close_by_peer_total 1938
telemt_me_route_drop_no_conn_total 20003
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 34928
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
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 1840
telemt_me_writer_restored_same_endpoint_total 1823
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_user_connections_total{user="hello"} 33497
telemt_user_connections_current{user="hello"} 235
telemt_user_octets_from_client{user="hello"} 606847592 (578.73 MB)
telemt_user_octets_to_client{user="hello"} 23279422304 (21.68 GB)
telemt_user_unique_ips_current{user="hello"} 106
telemt_user_unique_ips_recent_window{user="hello"} 28
```