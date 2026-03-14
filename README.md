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

# Server Metrics 2026-03-14 23:31:50 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 4643.1 (1h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9118
telemt_connections_bad_total 240
telemt_handshake_timeouts_total 180
telemt_upstream_connect_attempt_total 1220
telemt_upstream_connect_success_total 1213
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 1220
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 588
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 621
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_reconnect_attempts_total 934
telemt_me_reconnect_success_total 929
telemt_me_reader_eof_total 952
telemt_me_idle_close_by_peer_total 952
telemt_me_route_drop_no_conn_total 2538
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8309
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 43
telemt_desync_full_logged_total 17
telemt_desync_suppressed_total 26
telemt_desync_frames_bucket_total{bucket="1_2"} 9
telemt_desync_frames_bucket_total{bucket="3_10"} 14
telemt_desync_frames_bucket_total{bucket="gt_10"} 20
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 921
telemt_me_writer_restored_same_endpoint_total 898
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_user_connections_total{user="hello"} 8308
telemt_user_connections_current{user="hello"} 217
telemt_user_octets_from_client{user="hello"} 81164236 (77.40 MB)
telemt_user_octets_to_client{user="hello"} 2364170916 (2.20 GB)
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 4649.7 (1h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3890
telemt_connections_bad_total 9
telemt_handshake_timeouts_total 14
telemt_upstream_connect_attempt_total 1336
telemt_upstream_connect_success_total 1336
telemt_upstream_connect_attempts_per_request{bucket="1"} 1336
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 596
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 740
telemt_me_reconnect_attempts_total 1051
telemt_me_reconnect_success_total 1049
telemt_me_reader_eof_total 1090
telemt_me_idle_close_by_peer_total 1090
telemt_me_route_drop_no_conn_total 1452
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3652
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 1050
telemt_me_writer_restored_same_endpoint_total 1033
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 3653
telemt_user_connections_current{user="hello"} 112
telemt_user_octets_from_client{user="hello"} 36411944 (34.73 MB)
telemt_user_octets_to_client{user="hello"} 611335808 (583.02 MB)
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 4642.3 (1h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4600
telemt_connections_bad_total 20
telemt_handshake_timeouts_total 66
telemt_upstream_connect_attempt_total 1241
telemt_upstream_connect_success_total 1240
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 1241
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 560
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 676
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 959
telemt_me_reconnect_success_total 950
telemt_me_reader_eof_total 1003
telemt_me_idle_close_by_peer_total 1003
telemt_me_route_drop_no_conn_total 1424
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4361
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 947
telemt_me_writer_restored_same_endpoint_total 946
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 14
telemt_user_connections_total{user="hello"} 4352
telemt_user_connections_current{user="hello"} 69
telemt_user_octets_from_client{user="hello"} 1020011152 (972.76 MB)
telemt_user_octets_to_client{user="hello"} 8770328436 (8.17 GB)
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 4642.2 (1h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4196
telemt_connections_bad_total 11
telemt_handshake_timeouts_total 14
telemt_upstream_connect_attempt_total 1154
telemt_upstream_connect_success_total 1153
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 1154
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 532
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 619
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 876
telemt_me_reconnect_success_total 871
telemt_me_reader_eof_total 899
telemt_me_idle_close_by_peer_total 899
telemt_me_route_drop_no_conn_total 2011
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4051
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 12
telemt_desync_full_logged_total 2
telemt_desync_suppressed_total 10
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 5
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 869
telemt_me_writer_restored_same_endpoint_total 860
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_user_connections_total{user="hello"} 4051
telemt_user_connections_current{user="hello"} 120
telemt_user_octets_from_client{user="hello"} 87807008 (83.74 MB)
telemt_user_octets_to_client{user="hello"} 4664708024 (4.34 GB)
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 4642.1 (1h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5915
telemt_connections_bad_total 1095
telemt_handshake_timeouts_total 327
telemt_upstream_connect_attempt_total 1740
telemt_upstream_connect_success_total 1718
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 1740
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 880
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 835
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_reconnect_attempts_total 1505
telemt_me_reconnect_success_total 1436
telemt_me_reader_eof_total 1459
telemt_me_idle_close_by_peer_total 1459
telemt_me_route_drop_no_conn_total 1219
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4382
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 1429
telemt_me_refill_failed_total 2
telemt_me_writer_restored_same_endpoint_total 1424
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 29
telemt_user_connections_total{user="hello"} 4377
telemt_user_connections_current{user="hello"} 45
telemt_user_octets_from_client{user="hello"} 45922316 (43.79 MB)
telemt_user_octets_to_client{user="hello"} 3566349316 (3.32 GB)
telemt_user_unique_ips_current{user="hello"} 15
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 4641.2 (1h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15206
telemt_connections_bad_total 370
telemt_handshake_timeouts_total 58
telemt_upstream_connect_attempt_total 1110
telemt_upstream_connect_success_total 1105
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 1110
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 537
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 568
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_reconnect_attempts_total 824
telemt_me_reconnect_success_total 822
telemt_me_reader_eof_total 823
telemt_me_idle_close_by_peer_total 823
telemt_me_route_drop_no_conn_total 7374
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 14319
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 15
telemt_desync_full_logged_total 4
telemt_desync_suppressed_total 11
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 4
telemt_desync_frames_bucket_total{bucket="gt_10"} 6
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 801
telemt_me_writer_restored_same_endpoint_total 795
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_user_connections_total{user="hello"} 14318
telemt_user_connections_current{user="hello"} 290
telemt_user_octets_from_client{user="hello"} 276727048 (263.91 MB)
telemt_user_octets_to_client{user="hello"} 12242203592 (11.40 GB)
telemt_user_unique_ips_current{user="hello"} 119
telemt_user_unique_ips_recent_window{user="hello"} 30
```