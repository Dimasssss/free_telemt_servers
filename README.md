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

# Server Metrics 2026-03-19 03:35:10 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 20802.6 (5h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 265243
telemt_connections_bad_total 30546
telemt_connections_current 800
telemt_connections_me_current 800
telemt_handshake_timeouts_total 17581
telemt_upstream_connect_attempt_total 4114
telemt_upstream_connect_success_total 4049
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 4114
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1959
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2087
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 3000
telemt_me_reconnect_success_total 2985
telemt_me_reader_eof_total 3126
telemt_me_idle_close_by_peer_total 3126
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 69518
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 200367
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1419
telemt_desync_full_logged_total 379
telemt_desync_suppressed_total 1040
telemt_desync_frames_bucket_total{bucket="1_2"} 524
telemt_desync_frames_bucket_total{bucket="3_10"} 592
telemt_desync_frames_bucket_total{bucket="gt_10"} 303
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 3003
telemt_me_writer_restored_same_endpoint_total 2968
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 18
telemt_user_connections_total{user="hello"} 197592
telemt_user_connections_current{user="hello"} 800
telemt_user_octets_from_client{user="hello"} 2124969248 (1.98 GB)
telemt_user_octets_to_client{user="hello"} 59453820312 (55.37 GB)
telemt_user_unique_ips_current{user="hello"} 326
telemt_user_unique_ips_recent_window{user="hello"} 89
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 20806.9 (5h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 480266
telemt_connections_bad_total 38164
telemt_connections_current 1905
telemt_connections_me_current 1905
telemt_handshake_timeouts_total 12734
telemt_upstream_connect_attempt_total 3969
telemt_upstream_connect_success_total 3898
telemt_upstream_connect_fail_total 71
telemt_upstream_connect_attempts_per_request{bucket="1"} 3969
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1843
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2047
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 71
telemt_me_reconnect_attempts_total 2837
telemt_me_reconnect_success_total 2824
telemt_me_reader_eof_total 2975
telemt_me_idle_close_by_peer_total 2975
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 143339
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 398431
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 29
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1481
telemt_desync_full_logged_total 508
telemt_desync_suppressed_total 973
telemt_desync_frames_bucket_total{bucket="1_2"} 325
telemt_desync_frames_bucket_total{bucket="3_10"} 556
telemt_desync_frames_bucket_total{bucket="gt_10"} 600
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 2868
telemt_me_writer_restored_same_endpoint_total 2807
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 44
telemt_user_connections_total{user="hello"} 398405
telemt_user_connections_current{user="hello"} 1905
telemt_user_octets_from_client{user="hello"} 12612790900 (11.75 GB)
telemt_user_octets_to_client{user="hello"} 165460091236 (154.10 GB)
telemt_user_unique_ips_current{user="hello"} 756
telemt_user_unique_ips_recent_window{user="hello"} 197
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 20803.9 (5h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 393407
telemt_connections_bad_total 83892
telemt_connections_current 1492
telemt_connections_me_current 1492
telemt_handshake_timeouts_total 9689
telemt_upstream_connect_attempt_total 3930
telemt_upstream_connect_success_total 3930
telemt_upstream_connect_attempts_per_request{bucket="1"} 3930
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1985
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1938
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 2867
telemt_me_reconnect_success_total 2857
telemt_me_reader_eof_total 3021
telemt_me_idle_close_by_peer_total 3021
telemt_me_route_drop_no_conn_total 116290
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 287814
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1366
telemt_desync_full_logged_total 515
telemt_desync_suppressed_total 851
telemt_desync_frames_bucket_total{bucket="1_2"} 237
telemt_desync_frames_bucket_total{bucket="3_10"} 560
telemt_desync_frames_bucket_total{bucket="gt_10"} 569
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 2902
telemt_me_writer_restored_same_endpoint_total 2841
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 45
telemt_user_connections_total{user="hello"} 287807
telemt_user_connections_current{user="hello"} 1492
telemt_user_octets_from_client{user="hello"} 6083765216 (5.67 GB)
telemt_user_octets_to_client{user="hello"} 178065387852 (165.84 GB)
telemt_user_unique_ips_current{user="hello"} 591
telemt_user_unique_ips_recent_window{user="hello"} 156
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 20857.3 (5h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 473840
telemt_connections_bad_total 52283
telemt_connections_current 1265
telemt_connections_me_current 1265
telemt_handshake_timeouts_total 8884
telemt_upstream_connect_attempt_total 3827
telemt_upstream_connect_success_total 3827
telemt_upstream_connect_attempts_per_request{bucket="1"} 3827
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1930
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1889
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 2767
telemt_me_reconnect_success_total 2756
telemt_me_reader_eof_total 2904
telemt_me_idle_close_by_peer_total 2903
telemt_me_route_drop_no_conn_total 121290
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 288576
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 808
telemt_desync_full_logged_total 288
telemt_desync_suppressed_total 520
telemt_desync_frames_bucket_total{bucket="1_2"} 175
telemt_desync_frames_bucket_total{bucket="3_10"} 354
telemt_desync_frames_bucket_total{bucket="gt_10"} 279
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 2788
telemt_me_writer_restored_same_endpoint_total 2732
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 272
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 288309
telemt_user_connections_current{user="hello"} 1265
telemt_user_octets_from_client{user="hello"} 2570837660 (2.39 GB)
telemt_user_octets_to_client{user="hello"} 103625517368 (96.51 GB)
telemt_user_unique_ips_current{user="hello"} 511
telemt_user_unique_ips_recent_window{user="hello"} 156
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 20800.6 (5h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 449671
telemt_connections_bad_total 64491
telemt_connections_current 1518
telemt_connections_me_current 1518
telemt_handshake_timeouts_total 15075
telemt_upstream_connect_attempt_total 3966
telemt_upstream_connect_success_total 3941
telemt_upstream_connect_fail_total 25
telemt_upstream_connect_attempts_per_request{bucket="1"} 3966
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1957
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1973
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 25
telemt_me_reconnect_attempts_total 2880
telemt_me_reconnect_success_total 2864
telemt_me_reader_eof_total 3019
telemt_me_idle_close_by_peer_total 3019
telemt_me_route_drop_no_conn_total 123034
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 311944
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1391
telemt_desync_full_logged_total 534
telemt_desync_suppressed_total 857
telemt_desync_frames_bucket_total{bucket="1_2"} 370
telemt_desync_frames_bucket_total{bucket="3_10"} 556
telemt_desync_frames_bucket_total{bucket="gt_10"} 465
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 2886
telemt_me_writer_restored_same_endpoint_total 2840
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 311862
telemt_user_connections_current{user="hello"} 1518
telemt_user_octets_from_client{user="hello"} 10439528716 (9.72 GB)
telemt_user_octets_to_client{user="hello"} 183238557100 (170.65 GB)
telemt_user_unique_ips_current{user="hello"} 651
telemt_user_unique_ips_recent_window{user="hello"} 182
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 20812.0 (5h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 98615
telemt_connections_bad_total 10089
telemt_connections_current 405
telemt_connections_me_current 405
telemt_handshake_timeouts_total 432
telemt_upstream_connect_attempt_total 5884
telemt_upstream_connect_success_total 5718
telemt_upstream_connect_fail_total 166
telemt_upstream_connect_attempts_per_request{bucket="1"} 5884
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2725
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2993
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 166
telemt_me_reconnect_attempts_total 6488
telemt_me_reconnect_success_total 4650
telemt_me_reader_eof_total 4879
telemt_me_idle_close_by_peer_total 4879
telemt_me_route_drop_no_conn_total 40723
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 84782
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 42
telemt_desync_full_logged_total 14
telemt_desync_suppressed_total 28
telemt_desync_frames_bucket_total{bucket="1_2"} 24
telemt_desync_frames_bucket_total{bucket="3_10"} 15
telemt_desync_frames_bucket_total{bucket="gt_10"} 3
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 4714
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 4620
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 84776
telemt_user_connections_current{user="hello"} 405
telemt_user_octets_from_client{user="hello"} 1664856140 (1.55 GB)
telemt_user_octets_to_client{user="hello"} 56759122040 (52.86 GB)
telemt_user_unique_ips_current{user="hello"} 167
telemt_user_unique_ips_recent_window{user="hello"} 51
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 20803.1 (5h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 294467
telemt_connections_bad_total 29168
telemt_connections_current 1485
telemt_connections_me_current 1485
telemt_handshake_timeouts_total 15780
telemt_upstream_connect_attempt_total 4434
telemt_upstream_connect_success_total 4434
telemt_upstream_connect_attempts_per_request{bucket="1"} 4434
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2329
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2102
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 3373
telemt_me_reconnect_success_total 3364
telemt_me_reader_eof_total 3542
telemt_me_idle_close_by_peer_total 3542
telemt_me_route_drop_no_conn_total 84098
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 242130
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1246
telemt_desync_full_logged_total 478
telemt_desync_suppressed_total 768
telemt_desync_frames_bucket_total{bucket="1_2"} 232
telemt_desync_frames_bucket_total{bucket="3_10"} 489
telemt_desync_frames_bucket_total{bucket="gt_10"} 525
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 3401
telemt_me_writer_restored_same_endpoint_total 3349
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 242151
telemt_user_connections_current{user="hello"} 1485
telemt_user_octets_from_client{user="hello"} 2613204480 (2.43 GB)
telemt_user_octets_to_client{user="hello"} 130151599744 (121.21 GB)
telemt_user_unique_ips_current{user="hello"} 569
telemt_user_unique_ips_recent_window{user="hello"} 152
```