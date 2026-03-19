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

# Server Metrics 2026-03-19 00:31:09 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 9762.2 (2h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 112498
telemt_connections_bad_total 12762
telemt_connections_current 658
telemt_connections_me_current 658
telemt_handshake_timeouts_total 1133
telemt_upstream_connect_attempt_total 1894
telemt_upstream_connect_success_total 1864
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 1894
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 868
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 994
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1371
telemt_me_reconnect_success_total 1367
telemt_me_reader_eof_total 1411
telemt_me_idle_close_by_peer_total 1411
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 35099
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 93662
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 560
telemt_desync_full_logged_total 160
telemt_desync_suppressed_total 400
telemt_desync_frames_bucket_total{bucket="1_2"} 182
telemt_desync_frames_bucket_total{bucket="3_10"} 243
telemt_desync_frames_bucket_total{bucket="gt_10"} 135
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 1368
telemt_me_writer_restored_same_endpoint_total 1355
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 90894
telemt_user_connections_current{user="hello"} 658
telemt_user_octets_from_client{user="hello"} 866237356 (826.11 MB)
telemt_user_octets_to_client{user="hello"} 34881057956 (32.49 GB)
telemt_user_unique_ips_current{user="hello"} 282
telemt_user_unique_ips_recent_window{user="hello"} 78
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 9766.0 (2h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 238236
telemt_connections_bad_total 19115
telemt_connections_current 1476
telemt_connections_me_current 1476
telemt_handshake_timeouts_total 2390
telemt_upstream_connect_attempt_total 1816
telemt_upstream_connect_success_total 1777
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 1816
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 836
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 935
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_reconnect_attempts_total 1278
telemt_me_reconnect_success_total 1276
telemt_me_reader_eof_total 1334
telemt_me_idle_close_by_peer_total 1334
telemt_me_seq_mismatch_total 3
telemt_me_route_drop_no_conn_total 72523
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 203292
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 804
telemt_desync_full_logged_total 275
telemt_desync_suppressed_total 529
telemt_desync_frames_bucket_total{bucket="1_2"} 178
telemt_desync_frames_bucket_total{bucket="3_10"} 280
telemt_desync_frames_bucket_total{bucket="gt_10"} 346
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 1298
telemt_me_writer_restored_same_endpoint_total 1263
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 203349
telemt_user_connections_current{user="hello"} 1476
telemt_user_octets_from_client{user="hello"} 10643472268 (9.91 GB)
telemt_user_octets_to_client{user="hello"} 76225900060 (70.99 GB)
telemt_user_unique_ips_current{user="hello"} 594
telemt_user_unique_ips_recent_window{user="hello"} 135
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 9763.2 (2h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 187094
telemt_connections_bad_total 29656
telemt_connections_current 1124
telemt_connections_me_current 1124
telemt_handshake_timeouts_total 5146
telemt_upstream_connect_attempt_total 1893
telemt_upstream_connect_success_total 1893
telemt_upstream_connect_attempts_per_request{bucket="1"} 1893
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 950
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 939
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 1394
telemt_me_reconnect_success_total 1390
telemt_me_reader_eof_total 1448
telemt_me_idle_close_by_peer_total 1448
telemt_me_route_drop_no_conn_total 61223
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 146522
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 673
telemt_desync_full_logged_total 253
telemt_desync_suppressed_total 420
telemt_desync_frames_bucket_total{bucket="1_2"} 138
telemt_desync_frames_bucket_total{bucket="3_10"} 268
telemt_desync_frames_bucket_total{bucket="gt_10"} 267
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 1408
telemt_me_writer_restored_same_endpoint_total 1374
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 18
telemt_user_connections_total{user="hello"} 146525
telemt_user_connections_current{user="hello"} 1124
telemt_user_octets_from_client{user="hello"} 1931119928 (1.80 GB)
telemt_user_octets_to_client{user="hello"} 85004470724 (79.17 GB)
telemt_user_unique_ips_current{user="hello"} 495
telemt_user_unique_ips_recent_window{user="hello"} 102
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 9816.6 (2h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 194028
telemt_connections_bad_total 26296
telemt_connections_current 901
telemt_connections_me_current 901
telemt_handshake_timeouts_total 3510
telemt_upstream_connect_attempt_total 1790
telemt_upstream_connect_success_total 1790
telemt_upstream_connect_attempts_per_request{bucket="1"} 1790
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 937
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 846
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_reconnect_attempts_total 1293
telemt_me_reconnect_success_total 1287
telemt_me_reader_eof_total 1338
telemt_me_idle_close_by_peer_total 1338
telemt_me_route_drop_no_conn_total 70739
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 150642
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 403
telemt_desync_full_logged_total 143
telemt_desync_suppressed_total 260
telemt_desync_frames_bucket_total{bucket="1_2"} 75
telemt_desync_frames_bucket_total{bucket="3_10"} 162
telemt_desync_frames_bucket_total{bucket="gt_10"} 166
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 1303
telemt_me_writer_restored_same_endpoint_total 1263
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 268
telemt_me_writer_removed_unexpected_minus_restored_total 16
telemt_user_connections_total{user="hello"} 150566
telemt_user_connections_current{user="hello"} 901
telemt_user_octets_from_client{user="hello"} 1587657116 (1.48 GB)
telemt_user_octets_to_client{user="hello"} 53836453484 (50.14 GB)
telemt_user_unique_ips_current{user="hello"} 383
telemt_user_unique_ips_recent_window{user="hello"} 89
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 9760.1 (2h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 203192
telemt_connections_bad_total 9063
telemt_connections_current 1131
telemt_connections_me_current 1131
telemt_handshake_timeouts_total 6917
telemt_upstream_connect_attempt_total 1805
telemt_upstream_connect_success_total 1794
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 1805
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 869
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 919
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_reconnect_attempts_total 1295
telemt_me_reconnect_success_total 1288
telemt_me_reader_eof_total 1339
telemt_me_idle_close_by_peer_total 1339
telemt_me_route_drop_no_conn_total 65546
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 158065
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 629
telemt_desync_full_logged_total 250
telemt_desync_suppressed_total 379
telemt_desync_frames_bucket_total{bucket="1_2"} 153
telemt_desync_frames_bucket_total{bucket="3_10"} 217
telemt_desync_frames_bucket_total{bucket="gt_10"} 259
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 1294
telemt_me_writer_restored_same_endpoint_total 1264
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 157995
telemt_user_connections_current{user="hello"} 1131
telemt_user_octets_from_client{user="hello"} 2067233152 (1.93 GB)
telemt_user_octets_to_client{user="hello"} 98253006688 (91.51 GB)
telemt_user_unique_ips_current{user="hello"} 511
telemt_user_unique_ips_recent_window{user="hello"} 109
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 9771.6 (2h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 51127
telemt_connections_bad_total 8754
telemt_connections_current 335
telemt_connections_me_current 335
telemt_handshake_timeouts_total 152
telemt_upstream_connect_attempt_total 2915
telemt_upstream_connect_success_total 2825
telemt_upstream_connect_fail_total 90
telemt_upstream_connect_attempts_per_request{bucket="1"} 2915
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1380
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1445
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 90
telemt_me_reconnect_attempts_total 4155
telemt_me_reconnect_success_total 2328
telemt_me_reader_eof_total 2409
telemt_me_idle_close_by_peer_total 2409
telemt_me_route_drop_no_conn_total 18759
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 41041
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 27
telemt_desync_full_logged_total 7
telemt_desync_suppressed_total 20
telemt_desync_frames_bucket_total{bucket="1_2"} 16
telemt_desync_frames_bucket_total{bucket="3_10"} 10
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 2368
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 2298
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 40
telemt_user_connections_total{user="hello"} 41041
telemt_user_connections_current{user="hello"} 335
telemt_user_octets_from_client{user="hello"} 467791144 (446.12 MB)
telemt_user_octets_to_client{user="hello"} 26891774924 (25.04 GB)
telemt_user_unique_ips_current{user="hello"} 144
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 9762.4 (2h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 148726
telemt_connections_bad_total 18425
telemt_connections_current 1059
telemt_connections_me_current 1059
telemt_handshake_timeouts_total 5663
telemt_upstream_connect_attempt_total 1999
telemt_upstream_connect_success_total 1999
telemt_upstream_connect_attempts_per_request{bucket="1"} 1999
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1027
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 971
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 1500
telemt_me_reconnect_success_total 1495
telemt_me_reader_eof_total 1557
telemt_me_idle_close_by_peer_total 1557
telemt_me_route_drop_no_conn_total 44537
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 121784
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 837
telemt_desync_full_logged_total 334
telemt_desync_suppressed_total 503
telemt_desync_frames_bucket_total{bucket="1_2"} 135
telemt_desync_frames_bucket_total{bucket="3_10"} 348
telemt_desync_frames_bucket_total{bucket="gt_10"} 354
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 1512
telemt_me_writer_restored_same_endpoint_total 1480
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 121808
telemt_user_connections_current{user="hello"} 1059
telemt_user_octets_from_client{user="hello"} 1164596504 (1.08 GB)
telemt_user_octets_to_client{user="hello"} 64809090296 (60.36 GB)
telemt_user_unique_ips_current{user="hello"} 450
telemt_user_unique_ips_recent_window{user="hello"} 87
```