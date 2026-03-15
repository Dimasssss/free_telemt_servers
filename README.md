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

# Server Metrics 2026-03-15 00:48:09 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 9222.1 (2h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19054
telemt_connections_bad_total 364
telemt_handshake_timeouts_total 261
telemt_upstream_connect_attempt_total 2375
telemt_upstream_connect_success_total 2363
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 2375
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1113
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1246
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_reconnect_attempts_total 1869
telemt_me_reconnect_success_total 1859
telemt_me_reader_eof_total 1956
telemt_me_idle_close_by_peer_total 1956
telemt_me_route_drop_no_conn_total 5184
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 17793
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 110
telemt_desync_full_logged_total 48
telemt_desync_suppressed_total 62
telemt_desync_frames_bucket_total{bucket="1_2"} 20
telemt_desync_frames_bucket_total{bucket="3_10"} 34
telemt_desync_frames_bucket_total{bucket="gt_10"} 56
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 1859
telemt_me_writer_restored_same_endpoint_total 1828
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_user_connections_total{user="hello"} 17792
telemt_user_connections_current{user="hello"} 233
telemt_user_octets_from_client{user="hello"} 202726928 (193.34 MB)
telemt_user_octets_to_client{user="hello"} 5267989760 (4.91 GB)
telemt_user_unique_ips_current{user="hello"} 76
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 9228.6 (2h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8724
telemt_connections_bad_total 16
telemt_handshake_timeouts_total 28
telemt_upstream_connect_attempt_total 2599
telemt_upstream_connect_success_total 2599
telemt_upstream_connect_attempts_per_request{bucket="1"} 2599
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1140
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1459
telemt_me_reconnect_attempts_total 2099
telemt_me_reconnect_success_total 2094
telemt_me_reader_eof_total 2225
telemt_me_idle_close_by_peer_total 2225
telemt_me_route_drop_no_conn_total 2701
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8235
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 2104
telemt_me_writer_restored_same_endpoint_total 2078
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 8237
telemt_user_connections_current{user="hello"} 106
telemt_user_octets_from_client{user="hello"} 81401876 (77.63 MB)
telemt_user_octets_to_client{user="hello"} 1522453784 (1.42 GB)
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 9221.1 (2h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9093
telemt_connections_bad_total 83
telemt_handshake_timeouts_total 179
telemt_upstream_connect_attempt_total 2465
telemt_upstream_connect_success_total 2464
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 2465
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1100
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1360
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 1968
telemt_me_reconnect_success_total 1956
telemt_me_reader_eof_total 2104
telemt_me_idle_close_by_peer_total 2104
telemt_me_route_drop_no_conn_total 2913
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8545
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 1966
telemt_me_writer_restored_same_endpoint_total 1952
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 8525
telemt_user_connections_current{user="hello"} 75
telemt_user_octets_from_client{user="hello"} 1190158192 (1.11 GB)
telemt_user_octets_to_client{user="hello"} 10912255900 (10.16 GB)
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 9220.9 (2h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9137
telemt_connections_bad_total 74
telemt_handshake_timeouts_total 35
telemt_upstream_connect_attempt_total 2286
telemt_upstream_connect_success_total 2285
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 2286
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1041
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1241
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 1793
telemt_me_reconnect_success_total 1784
telemt_me_reader_eof_total 1889
telemt_me_idle_close_by_peer_total 1889
telemt_me_route_drop_no_conn_total 3757
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8787
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 50
telemt_desync_full_logged_total 8
telemt_desync_suppressed_total 42
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 24
telemt_desync_frames_bucket_total{bucket="gt_10"} 22
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 1796
telemt_me_writer_restored_same_endpoint_total 1773
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 8787
telemt_user_connections_current{user="hello"} 145
telemt_user_octets_from_client{user="hello"} 211651904 (201.85 MB)
telemt_user_octets_to_client{user="hello"} 6467574460 (6.02 GB)
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 9221.0 (2h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11970
telemt_connections_bad_total 1953
telemt_handshake_timeouts_total 365
telemt_upstream_connect_attempt_total 3013
telemt_upstream_connect_success_total 2974
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 3013
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1440
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1528
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_reconnect_attempts_total 2546
telemt_me_reconnect_success_total 2470
telemt_me_reader_eof_total 2584
telemt_me_idle_close_by_peer_total 2584
telemt_me_route_drop_no_conn_total 2857
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9430
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 2472
telemt_me_refill_failed_total 2
telemt_me_writer_restored_same_endpoint_total 2458
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 29
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 9418
telemt_user_connections_current{user="hello"} 45
telemt_user_octets_from_client{user="hello"} 154805600 (147.63 MB)
telemt_user_octets_to_client{user="hello"} 5397922932 (5.03 GB)
telemt_user_unique_ips_current{user="hello"} 19
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 9220.1 (2h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 30014
telemt_connections_bad_total 616
telemt_handshake_timeouts_total 110
telemt_upstream_connect_attempt_total 2068
telemt_upstream_connect_success_total 2057
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 2068
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1033
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1024
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_reconnect_attempts_total 1560
telemt_me_reconnect_success_total 1555
telemt_me_reader_eof_total 1620
telemt_me_idle_close_by_peer_total 1620
telemt_me_route_drop_no_conn_total 17447
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 29869
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
telemt_me_writer_removed_unexpected_total 1541
telemt_me_writer_restored_same_endpoint_total 1528
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_user_connections_total{user="hello"} 28456
telemt_user_connections_current{user="hello"} 265
telemt_user_octets_from_client{user="hello"} 444687564 (424.09 MB)
telemt_user_octets_to_client{user="hello"} 20903777372 (19.47 GB)
telemt_user_unique_ips_current{user="hello"} 121
telemt_user_unique_ips_recent_window{user="hello"} 42
```