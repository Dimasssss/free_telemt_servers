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

# Server Metrics 2026-03-12 10:20:02 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 9999.5 (2h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 52491
telemt_connections_bad_total 41
telemt_handshake_timeouts_total 2360
telemt_upstream_connect_attempt_total 2423
telemt_upstream_connect_success_total 2412
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 2423
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1090
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1320
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 61
telemt_me_reconnect_attempts_total 1868
telemt_me_reconnect_success_total 1855
telemt_me_reader_eof_total 1921
telemt_me_idle_close_by_peer_total 1921
telemt_me_route_drop_no_conn_total 13984
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 47366
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 173
telemt_desync_full_logged_total 68
telemt_desync_suppressed_total 105
telemt_desync_frames_bucket_total{bucket="1_2"} 38
telemt_desync_frames_bucket_total{bucket="3_10"} 63
telemt_desync_frames_bucket_total{bucket="gt_10"} 72
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 1863
telemt_me_writer_restored_same_endpoint_total 1839
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 8
telemt_user_connections_total{user="hello"} 47339
telemt_user_connections_current{user="hello"} 316
telemt_user_octets_from_client{user="hello"} 704512252 (671.88 MB)
telemt_user_octets_to_client{user="hello"} 13489338480 (12.56 GB)
telemt_user_unique_ips_current{user="hello"} 89
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 9892.5 (2h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21541
telemt_connections_bad_total 129
telemt_handshake_timeouts_total 180
telemt_upstream_connect_attempt_total 3631
telemt_upstream_connect_success_total 3562
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 3631
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1297
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2263
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_keepalive_timeout_total 72
telemt_me_reconnect_attempts_total 5849
telemt_me_reconnect_success_total 3054
telemt_me_reader_eof_total 3177
telemt_me_idle_close_by_peer_total 3177
telemt_me_route_drop_no_conn_total 7991
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 20556
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 30
telemt_desync_full_logged_total 8
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 11
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 3147
telemt_me_refill_failed_total 87
telemt_me_writer_restored_same_endpoint_total 3039
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 93
telemt_user_connections_total{user="hello"} 20554
telemt_user_connections_current{user="hello"} 129
telemt_user_octets_from_client{user="hello"} 219026252 (208.88 MB)
telemt_user_octets_to_client{user="hello"} 4121915068 (3.84 GB)
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 9856.3 (2h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 30222
telemt_connections_bad_total 80
telemt_handshake_timeouts_total 224
telemt_upstream_connect_attempt_total 2681
telemt_upstream_connect_success_total 2681
telemt_upstream_connect_attempts_per_request{bucket="1"} 2681
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1329
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1348
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 49
telemt_me_reconnect_attempts_total 2178
telemt_me_reconnect_success_total 2164
telemt_me_reader_eof_total 2240
telemt_me_idle_close_by_peer_total 2240
telemt_me_route_drop_no_conn_total 9855
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 28126
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9
telemt_desync_full_logged_total 5
telemt_desync_suppressed_total 4
telemt_desync_frames_bucket_total{bucket="3_10"} 5
telemt_desync_frames_bucket_total{bucket="gt_10"} 4
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 2163
telemt_me_writer_restored_same_endpoint_total 2144
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_user_connections_total{user="hello"} 28119
telemt_user_connections_current{user="hello"} 203
telemt_user_octets_from_client{user="hello"} 310667232 (296.28 MB)
telemt_user_octets_to_client{user="hello"} 26534987292 (24.71 GB)
telemt_user_unique_ips_current{user="hello"} 72
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 9832.1 (2h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 35203
telemt_connections_bad_total 1031
telemt_handshake_timeouts_total 193
telemt_upstream_connect_attempt_total 2789
telemt_upstream_connect_success_total 2722
telemt_upstream_connect_fail_total 67
telemt_upstream_connect_attempts_per_request{bucket="1"} 2789
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1169
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1544
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 67
telemt_me_keepalive_timeout_total 133
telemt_me_reconnect_attempts_total 2241
telemt_me_reconnect_success_total 2205
telemt_me_reader_eof_total 2290
telemt_me_idle_close_by_peer_total 2290
telemt_me_route_drop_no_conn_total 10150
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 31545
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 131
telemt_desync_full_logged_total 46
telemt_desync_suppressed_total 85
telemt_desync_frames_bucket_total{bucket="1_2"} 55
telemt_desync_frames_bucket_total{bucket="3_10"} 41
telemt_desync_frames_bucket_total{bucket="gt_10"} 35
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 2239
telemt_me_writer_restored_same_endpoint_total 2197
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 121
telemt_me_writer_removed_unexpected_minus_restored_total 34
telemt_user_connections_total{user="hello"} 31544
telemt_user_connections_current{user="hello"} 213
telemt_user_octets_from_client{user="hello"} 836040132 (797.31 MB)
telemt_user_octets_to_client{user="hello"} 14585416176 (13.58 GB)
telemt_user_unique_ips_current{user="hello"} 70
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 9801.4 (2h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19179
telemt_connections_bad_total 1902
telemt_handshake_timeouts_total 321
telemt_upstream_connect_attempt_total 3011
telemt_upstream_connect_success_total 2904
telemt_upstream_connect_fail_total 107
telemt_upstream_connect_attempts_per_request{bucket="1"} 3011
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1062
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1836
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 107
telemt_me_keepalive_timeout_total 62
telemt_me_reconnect_attempts_total 8805
telemt_me_reconnect_success_total 2390
telemt_me_reader_eof_total 2579
telemt_me_idle_close_by_peer_total 2579
telemt_me_seq_mismatch_total 5
telemt_me_route_drop_no_conn_total 5519
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16482
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 281
telemt_desync_full_logged_total 77
telemt_desync_suppressed_total 204
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 243
telemt_desync_frames_bucket_total{bucket="gt_10"} 34
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 2600
telemt_me_refill_failed_total 200
telemt_me_writer_restored_same_endpoint_total 2374
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 210
telemt_user_connections_total{user="hello"} 16479
telemt_user_connections_current{user="hello"} 83
telemt_user_octets_from_client{user="hello"} 79611520 (75.92 MB)
telemt_user_octets_to_client{user="hello"} 4346584048 (4.05 GB)
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 9788.2 (2h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 48100
telemt_connections_bad_total 557
telemt_handshake_timeouts_total 647
telemt_upstream_connect_attempt_total 1823
telemt_upstream_connect_success_total 1812
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 1823
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 884
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 926
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 60
telemt_me_reconnect_attempts_total 1318
telemt_me_reconnect_success_total 1307
telemt_me_reader_eof_total 1369
telemt_me_idle_close_by_peer_total 1369
telemt_me_route_drop_no_conn_total 21227
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 45105
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 114
telemt_desync_full_logged_total 36
telemt_desync_suppressed_total 78
telemt_desync_frames_bucket_total{bucket="1_2"} 35
telemt_desync_frames_bucket_total{bucket="3_10"} 45
telemt_desync_frames_bucket_total{bucket="gt_10"} 34
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 1325
telemt_me_writer_restored_same_endpoint_total 1300
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 18
telemt_user_connections_total{user="hello"} 45068
telemt_user_connections_current{user="hello"} 372
telemt_user_octets_from_client{user="hello"} 1773887212 (1.65 GB)
telemt_user_octets_to_client{user="hello"} 26998385216 (25.14 GB)
telemt_user_unique_ips_current{user="hello"} 124
telemt_user_unique_ips_recent_window{user="hello"} 48
```