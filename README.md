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

# Server Metrics 2026-03-12 23:58:00 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 59076.7 (16h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 253412
telemt_connections_bad_total 2745
telemt_handshake_timeouts_total 5273
telemt_upstream_connect_attempt_total 14865
telemt_upstream_connect_success_total 14800
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 14865
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6541
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8213
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1490
telemt_me_reconnect_attempts_total 15286
telemt_me_reconnect_success_total 11815
telemt_me_reader_eof_total 12596
telemt_me_idle_close_by_peer_total 12595
telemt_me_route_drop_no_conn_total 78874
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 209596
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 700
telemt_desync_full_logged_total 259
telemt_desync_suppressed_total 441
telemt_desync_frames_bucket_total{bucket="1_2"} 125
telemt_desync_frames_bucket_total{bucket="3_10"} 259
telemt_desync_frames_bucket_total{bucket="gt_10"} 316
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 12058
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 11799
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 243
telemt_user_connections_total{user="hello"} 209364
telemt_user_connections_current{user="hello"} 204
telemt_user_octets_from_client{user="hello"} 3864605808 (3.60 GB)
telemt_user_octets_to_client{user="hello"} 107230256036 (99.87 GB)
telemt_user_unique_ips_current{user="hello"} 64
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 58969.7 (16h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 115930
telemt_connections_bad_total 647
telemt_handshake_timeouts_total 905
telemt_upstream_connect_attempt_total 33736
telemt_upstream_connect_success_total 33352
telemt_upstream_connect_fail_total 384
telemt_upstream_connect_attempts_per_request{bucket="1"} 33736
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21570
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11282
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 500
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 384
telemt_me_keepalive_timeout_total 417
telemt_me_reconnect_attempts_total 55752
telemt_me_reconnect_success_total 13880
telemt_me_reader_eof_total 15562
telemt_me_idle_close_by_peer_total 15562
telemt_me_route_drop_no_conn_total 41995
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 93597
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 14
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
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 15287
telemt_me_refill_failed_total 1307
telemt_me_writer_restored_same_endpoint_total 13865
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1407
telemt_user_connections_total{user="hello"} 110099
telemt_user_connections_current{user="hello"} 108
telemt_user_octets_from_client{user="hello"} 1210569964 (1.13 GB)
telemt_user_octets_to_client{user="hello"} 34111109823 (31.77 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 58933.3 (16h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 141846
telemt_connections_bad_total 1663
telemt_handshake_timeouts_total 2245
telemt_upstream_connect_attempt_total 16195
telemt_upstream_connect_success_total 16194
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 16195
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7592
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8582
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 344
telemt_me_reconnect_attempts_total 14332
telemt_me_reconnect_success_total 13182
telemt_me_reader_eof_total 14080
telemt_me_idle_close_by_peer_total 14080
telemt_me_route_drop_no_conn_total 53599
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 132624
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 52
telemt_desync_full_logged_total 26
telemt_desync_suppressed_total 26
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 13
telemt_desync_frames_bucket_total{bucket="gt_10"} 36
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 13347
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 13162
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 165
telemt_user_connections_total{user="hello"} 132590
telemt_user_connections_current{user="hello"} 137
telemt_user_octets_from_client{user="hello"} 2611590292 (2.43 GB)
telemt_user_octets_to_client{user="hello"} 60894212988 (56.71 GB)
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 58909.1 (16h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 204955
telemt_connections_bad_total 13279
telemt_handshake_timeouts_total 1382
telemt_upstream_connect_attempt_total 27894
telemt_upstream_connect_success_total 18172
telemt_upstream_connect_fail_total 9722
telemt_upstream_connect_attempts_per_request{bucket="1"} 27894
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9540
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8488
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 136
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9722
telemt_me_keepalive_timeout_total 3090
telemt_me_reconnect_attempts_total 44587
telemt_me_reconnect_success_total 12335
telemt_me_reader_eof_total 13791
telemt_me_idle_close_by_peer_total 13784
telemt_me_route_drop_no_conn_total 72950
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 168907
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 499
telemt_desync_full_logged_total 143
telemt_desync_suppressed_total 356
telemt_desync_frames_bucket_total{bucket="1_2"} 124
telemt_desync_frames_bucket_total{bucket="3_10"} 186
telemt_desync_frames_bucket_total{bucket="gt_10"} 189
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 13530
telemt_me_refill_failed_total 1004
telemt_me_writer_restored_same_endpoint_total 12325
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1195
telemt_user_connections_total{user="hello"} 171661
telemt_user_connections_current{user="hello"} 98
telemt_user_octets_from_client{user="hello"} 2992852738 (2.79 GB)
telemt_user_octets_to_client{user="hello"} 69910817225 (65.11 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 9080.6 (2h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7933
telemt_connections_bad_total 1684
telemt_handshake_timeouts_total 9
telemt_upstream_connect_attempt_total 2907
telemt_upstream_connect_success_total 2878
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 2907
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1278
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1592
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 55
telemt_me_reconnect_attempts_total 2392
telemt_me_reconnect_success_total 2388
telemt_me_reader_eof_total 2524
telemt_me_idle_close_by_peer_total 2524
telemt_me_route_drop_no_conn_total 2396
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5977
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 2400
telemt_me_writer_restored_same_endpoint_total 2372
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 5977
telemt_user_connections_current{user="hello"} 44
telemt_user_octets_from_client{user="hello"} 20501656 (19.55 MB)
telemt_user_octets_to_client{user="hello"} 2027388860 (1.89 GB)
telemt_user_unique_ips_current{user="hello"} 23
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 58865.4 (16h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 338557
telemt_connections_bad_total 5150
telemt_handshake_timeouts_total 2539
telemt_upstream_connect_attempt_total 12409
telemt_upstream_connect_success_total 12340
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 12409
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5790
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6530
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_keepalive_timeout_total 632
telemt_me_reconnect_attempts_total 13002
telemt_me_reconnect_success_total 9386
telemt_me_reader_eof_total 10070
telemt_me_idle_close_by_peer_total 10068
telemt_me_route_drop_no_conn_total 151478
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 332771
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 293
telemt_desync_full_logged_total 110
telemt_desync_suppressed_total 183
telemt_desync_frames_bucket_total{bucket="1_2"} 74
telemt_desync_frames_bucket_total{bucket="3_10"} 110
telemt_desync_frames_bucket_total{bucket="gt_10"} 109
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 9613
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 9379
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 227
telemt_user_connections_total{user="hello"} 321074
telemt_user_connections_current{user="hello"} 216
telemt_user_octets_from_client{user="hello"} 5533240668 (5.15 GB)
telemt_user_octets_to_client{user="hello"} 172650484564 (160.79 GB)
telemt_user_unique_ips_current{user="hello"} 85
telemt_user_unique_ips_recent_window{user="hello"} 24
```