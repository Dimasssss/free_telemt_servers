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

# Server Metrics 2026-03-19 00:20:56 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 9149.0 (2h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 105831
telemt_connections_bad_total 11841
telemt_connections_current 697
telemt_connections_me_current 697
telemt_handshake_timeouts_total 1120
telemt_upstream_connect_attempt_total 1831
telemt_upstream_connect_success_total 1801
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 1831
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 829
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 970
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1308
telemt_me_reconnect_success_total 1304
telemt_me_reader_eof_total 1344
telemt_me_idle_close_by_peer_total 1344
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 33618
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 88197
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 509
telemt_desync_full_logged_total 151
telemt_desync_suppressed_total 358
telemt_desync_frames_bucket_total{bucket="1_2"} 160
telemt_desync_frames_bucket_total{bucket="3_10"} 220
telemt_desync_frames_bucket_total{bucket="gt_10"} 129
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 1304
telemt_me_writer_restored_same_endpoint_total 1292
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 136
telemt_user_connections_total{user="hello"} 85432
telemt_user_connections_current{user="hello"} 697
telemt_user_octets_from_client{user="hello"} 786704360 (750.26 MB)
telemt_user_octets_to_client{user="hello"} 33323228988 (31.03 GB)
telemt_user_unique_ips_current{user="hello"} 275
telemt_user_unique_ips_recent_window{user="hello"} 84
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 9152.6 (2h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 226680
telemt_connections_bad_total 17347
telemt_connections_current 1523
telemt_connections_me_current 1523
telemt_handshake_timeouts_total 2047
telemt_upstream_connect_attempt_total 1745
telemt_upstream_connect_success_total 1706
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 1745
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 808
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 892
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_reconnect_attempts_total 1207
telemt_me_reconnect_success_total 1206
telemt_me_reader_eof_total 1261
telemt_me_idle_close_by_peer_total 1261
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 69858
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 194494
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 784
telemt_desync_full_logged_total 263
telemt_desync_suppressed_total 521
telemt_desync_frames_bucket_total{bucket="1_2"} 177
telemt_desync_frames_bucket_total{bucket="3_10"} 269
telemt_desync_frames_bucket_total{bucket="gt_10"} 338
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 1226
telemt_me_writer_restored_same_endpoint_total 1195
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 194551
telemt_user_connections_current{user="hello"} 1523
telemt_user_octets_from_client{user="hello"} 10592614216 (9.87 GB)
telemt_user_octets_to_client{user="hello"} 72489103108 (67.51 GB)
telemt_user_unique_ips_current{user="hello"} 619
telemt_user_unique_ips_recent_window{user="hello"} 144
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 9149.8 (2h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 177451
telemt_connections_bad_total 27666
telemt_connections_current 1194
telemt_connections_me_current 1194
telemt_handshake_timeouts_total 4783
telemt_upstream_connect_attempt_total 1795
telemt_upstream_connect_success_total 1795
telemt_upstream_connect_attempts_per_request{bucket="1"} 1795
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 904
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 887
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 1296
telemt_me_reconnect_success_total 1292
telemt_me_reader_eof_total 1349
telemt_me_idle_close_by_peer_total 1349
telemt_me_route_drop_no_conn_total 58810
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 139550
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 617
telemt_desync_full_logged_total 240
telemt_desync_suppressed_total 377
telemt_desync_frames_bucket_total{bucket="1_2"} 116
telemt_desync_frames_bucket_total{bucket="3_10"} 251
telemt_desync_frames_bucket_total{bucket="gt_10"} 250
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 1310
telemt_me_writer_restored_same_endpoint_total 1276
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 18
telemt_user_connections_total{user="hello"} 139551
telemt_user_connections_current{user="hello"} 1194
telemt_user_octets_from_client{user="hello"} 1861719476 (1.73 GB)
telemt_user_octets_to_client{user="hello"} 81923967312 (76.30 GB)
telemt_user_unique_ips_current{user="hello"} 499
telemt_user_unique_ips_recent_window{user="hello"} 104
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 9203.2 (2h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 186534
telemt_connections_bad_total 25438
telemt_connections_current 962
telemt_connections_me_current 962
telemt_handshake_timeouts_total 3436
telemt_upstream_connect_attempt_total 1720
telemt_upstream_connect_success_total 1720
telemt_upstream_connect_attempts_per_request{bucket="1"} 1720
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 897
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 817
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_reconnect_attempts_total 1223
telemt_me_reconnect_success_total 1218
telemt_me_reader_eof_total 1267
telemt_me_idle_close_by_peer_total 1267
telemt_me_route_drop_no_conn_total 68880
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 144337
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 376
telemt_desync_full_logged_total 138
telemt_desync_suppressed_total 238
telemt_desync_frames_bucket_total{bucket="1_2"} 67
telemt_desync_frames_bucket_total{bucket="3_10"} 153
telemt_desync_frames_bucket_total{bucket="gt_10"} 156
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 1232
telemt_me_writer_restored_same_endpoint_total 1194
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 268
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 144262
telemt_user_connections_current{user="hello"} 962
telemt_user_octets_from_client{user="hello"} 1560434300 (1.45 GB)
telemt_user_octets_to_client{user="hello"} 52587702544 (48.98 GB)
telemt_user_unique_ips_current{user="hello"} 412
telemt_user_unique_ips_recent_window{user="hello"} 100
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 9146.5 (2h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 193746
telemt_connections_bad_total 8459
telemt_connections_current 1157
telemt_connections_me_current 1157
telemt_handshake_timeouts_total 6773
telemt_upstream_connect_attempt_total 1722
telemt_upstream_connect_success_total 1711
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 1722
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 832
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 874
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_reconnect_attempts_total 1212
telemt_me_reconnect_success_total 1206
telemt_me_reader_eof_total 1250
telemt_me_idle_close_by_peer_total 1250
telemt_me_route_drop_no_conn_total 62641
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 151039
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 607
telemt_desync_full_logged_total 245
telemt_desync_suppressed_total 362
telemt_desync_frames_bucket_total{bucket="1_2"} 143
telemt_desync_frames_bucket_total{bucket="3_10"} 210
telemt_desync_frames_bucket_total{bucket="gt_10"} 254
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 1210
telemt_me_writer_restored_same_endpoint_total 1182
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 150969
telemt_user_connections_current{user="hello"} 1157
telemt_user_octets_from_client{user="hello"} 1996250196 (1.86 GB)
telemt_user_octets_to_client{user="hello"} 94555828300 (88.06 GB)
telemt_user_unique_ips_current{user="hello"} 529
telemt_user_unique_ips_recent_window{user="hello"} 121
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 9158.0 (2h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 48605
telemt_connections_bad_total 8573
telemt_connections_current 352
telemt_connections_me_current 352
telemt_handshake_timeouts_total 137
telemt_upstream_connect_attempt_total 2762
telemt_upstream_connect_success_total 2672
telemt_upstream_connect_fail_total 90
telemt_upstream_connect_attempts_per_request{bucket="1"} 2762
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1320
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1352
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 90
telemt_me_reconnect_attempts_total 4002
telemt_me_reconnect_success_total 2176
telemt_me_reader_eof_total 2254
telemt_me_idle_close_by_peer_total 2254
telemt_me_route_drop_no_conn_total 17564
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 38759
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 24
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 18
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 10
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 2213
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 2146
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 38760
telemt_user_connections_current{user="hello"} 352
telemt_user_octets_from_client{user="hello"} 444996932 (424.38 MB)
telemt_user_octets_to_client{user="hello"} 26195806168 (24.40 GB)
telemt_user_unique_ips_current{user="hello"} 155
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 9148.9 (2h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 142706
telemt_connections_bad_total 18055
telemt_connections_current 1045
telemt_connections_me_current 1045
telemt_handshake_timeouts_total 5274
telemt_upstream_connect_attempt_total 1869
telemt_upstream_connect_success_total 1869
telemt_upstream_connect_attempts_per_request{bucket="1"} 1869
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 972
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 896
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 1370
telemt_me_reconnect_success_total 1366
telemt_me_reader_eof_total 1423
telemt_me_idle_close_by_peer_total 1423
telemt_me_route_drop_no_conn_total 42917
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 116655
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 809
telemt_desync_full_logged_total 317
telemt_desync_suppressed_total 492
telemt_desync_frames_bucket_total{bucket="1_2"} 131
telemt_desync_frames_bucket_total{bucket="3_10"} 336
telemt_desync_frames_bucket_total{bucket="gt_10"} 342
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 1382
telemt_me_writer_restored_same_endpoint_total 1351
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 16
telemt_user_connections_total{user="hello"} 116681
telemt_user_connections_current{user="hello"} 1045
telemt_user_octets_from_client{user="hello"} 1128577988 (1.05 GB)
telemt_user_octets_to_client{user="hello"} 62328445620 (58.05 GB)
telemt_user_unique_ips_current{user="hello"} 431
telemt_user_unique_ips_recent_window{user="hello"} 90
```