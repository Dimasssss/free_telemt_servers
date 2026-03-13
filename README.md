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

# Server Metrics 2026-03-13 04:44:32 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 76268.5 (21h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 290929
telemt_connections_bad_total 3032
telemt_handshake_timeouts_total 5777
telemt_upstream_connect_attempt_total 19268
telemt_upstream_connect_success_total 19178
telemt_upstream_connect_fail_total 90
telemt_upstream_connect_attempts_per_request{bucket="1"} 19268
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8568
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10562
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 90
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1556
telemt_me_reconnect_attempts_total 18846
telemt_me_reconnect_success_total 15350
telemt_me_reader_eof_total 16408
telemt_me_idle_close_by_peer_total 16407
telemt_me_route_drop_no_conn_total 90666
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 244220
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 821
telemt_desync_full_logged_total 308
telemt_desync_suppressed_total 513
telemt_desync_frames_bucket_total{bucket="1_2"} 157
telemt_desync_frames_bucket_total{bucket="3_10"} 301
telemt_desync_frames_bucket_total{bucket="gt_10"} 363
telemt_pool_swap_total 68
telemt_me_writer_removed_unexpected_total 15625
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 15334
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 275
telemt_user_connections_total{user="hello"} 244158
telemt_user_connections_current{user="hello"} 260
telemt_user_octets_from_client{user="hello"} 4236235460 (3.95 GB)
telemt_user_octets_to_client{user="hello"} 120065894192 (111.82 GB)
telemt_user_unique_ips_current{user="hello"} 77
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 76161.3 (21h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 133589
telemt_connections_bad_total 752
telemt_handshake_timeouts_total 1003
telemt_upstream_connect_attempt_total 40842
telemt_upstream_connect_success_total 40333
telemt_upstream_connect_fail_total 509
telemt_upstream_connect_attempts_per_request{bucket="1"} 40842
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24220
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15608
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 505
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 509
telemt_me_keepalive_timeout_total 557
telemt_me_reconnect_attempts_total 66586
telemt_me_reconnect_success_total 20024
telemt_me_reader_eof_total 22086
telemt_me_idle_close_by_peer_total 22086
telemt_me_route_drop_no_conn_total 49172
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 110420
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 31
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 21632
telemt_me_refill_failed_total 1453
telemt_me_writer_restored_same_endpoint_total 20009
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1608
telemt_user_connections_total{user="hello"} 126920
telemt_user_connections_current{user="hello"} 101
telemt_user_octets_from_client{user="hello"} 1309864740 (1.22 GB)
telemt_user_octets_to_client{user="hello"} 38070561983 (35.46 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 76124.7 (21h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 161173
telemt_connections_bad_total 1845
telemt_handshake_timeouts_total 2604
telemt_upstream_connect_attempt_total 21031
telemt_upstream_connect_success_total 21029
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 21031
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9689
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11317
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 446
telemt_me_reconnect_attempts_total 18344
telemt_me_reconnect_success_total 17180
telemt_me_reader_eof_total 18399
telemt_me_idle_close_by_peer_total 18399
telemt_me_route_drop_no_conn_total 62199
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 150749
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 62
telemt_desync_full_logged_total 30
telemt_desync_suppressed_total 32
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 20
telemt_desync_frames_bucket_total{bucket="gt_10"} 39
telemt_pool_swap_total 68
telemt_me_writer_removed_unexpected_total 17370
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 17160
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 190
telemt_user_connections_total{user="hello"} 150676
telemt_user_connections_current{user="hello"} 113
telemt_user_octets_from_client{user="hello"} 2850567388 (2.65 GB)
telemt_user_octets_to_client{user="hello"} 70367561916 (65.53 GB)
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 76100.5 (21h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 232223
telemt_connections_bad_total 13507
telemt_handshake_timeouts_total 1466
telemt_upstream_connect_attempt_total 33481
telemt_upstream_connect_success_total 23607
telemt_upstream_connect_fail_total 9874
telemt_upstream_connect_attempts_per_request{bucket="1"} 33481
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11890
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11543
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9874
telemt_me_keepalive_timeout_total 3310
telemt_me_reconnect_attempts_total 64340
telemt_me_reconnect_success_total 16938
telemt_me_reader_eof_total 18942
telemt_me_idle_close_by_peer_total 18935
telemt_me_route_drop_no_conn_total 84772
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 194342
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 506
telemt_desync_full_logged_total 146
telemt_desync_suppressed_total 360
telemt_desync_frames_bucket_total{bucket="1_2"} 128
telemt_desync_frames_bucket_total{bucket="3_10"} 188
telemt_desync_frames_bucket_total{bucket="gt_10"} 190
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 18643
telemt_me_refill_failed_total 1477
telemt_me_writer_restored_same_endpoint_total 16928
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1705
telemt_user_connections_total{user="hello"} 197090
telemt_user_connections_current{user="hello"} 143
telemt_user_octets_from_client{user="hello"} 3236021302 (3.01 GB)
telemt_user_octets_to_client{user="hello"} 79269775425 (73.83 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 26272.1 (7h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 26895
telemt_connections_bad_total 4909
telemt_handshake_timeouts_total 102
telemt_upstream_connect_attempt_total 8257
telemt_upstream_connect_success_total 8175
telemt_upstream_connect_fail_total 82
telemt_upstream_connect_attempts_per_request{bucket="1"} 8257
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3589
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4556
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 82
telemt_me_keepalive_timeout_total 194
telemt_me_reconnect_attempts_total 6860
telemt_me_reconnect_success_total 6834
telemt_me_reader_eof_total 7316
telemt_me_idle_close_by_peer_total 7316
telemt_me_route_drop_no_conn_total 7376
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 21127
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 6897
telemt_me_writer_restored_same_endpoint_total 6816
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 63
telemt_user_connections_total{user="hello"} 21127
telemt_user_connections_current{user="hello"} 62
telemt_user_octets_from_client{user="hello"} 150010400 (143.06 MB)
telemt_user_octets_to_client{user="hello"} 9109959352 (8.48 GB)
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 76057.0 (21h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 391262
telemt_connections_bad_total 7710
telemt_handshake_timeouts_total 2944
telemt_upstream_connect_attempt_total 16203
telemt_upstream_connect_success_total 16112
telemt_upstream_connect_fail_total 91
telemt_upstream_connect_attempts_per_request{bucket="1"} 16203
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7496
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8591
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 91
telemt_me_keepalive_timeout_total 1433
telemt_me_reconnect_attempts_total 15953
telemt_me_reconnect_success_total 12324
telemt_me_reader_eof_total 13235
telemt_me_idle_close_by_peer_total 13232
telemt_me_route_drop_no_conn_total 174898
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 381435
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 314
telemt_desync_full_logged_total 123
telemt_desync_suppressed_total 191
telemt_desync_frames_bucket_total{bucket="1_2"} 75
telemt_desync_frames_bucket_total{bucket="3_10"} 116
telemt_desync_frames_bucket_total{bucket="gt_10"} 123
telemt_pool_swap_total 70
telemt_me_writer_removed_unexpected_total 12594
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 12317
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 270
telemt_user_connections_total{user="hello"} 369679
telemt_user_connections_current{user="hello"} 326
telemt_user_octets_from_client{user="hello"} 6138538312 (5.72 GB)
telemt_user_octets_to_client{user="hello"} 219008728164 (203.97 GB)
telemt_user_unique_ips_current{user="hello"} 118
telemt_user_unique_ips_recent_window{user="hello"} 49
```