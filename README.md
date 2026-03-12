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

# Server Metrics 2026-03-12 10:55:50 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 12147.6 (3h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 63252
telemt_connections_bad_total 493
telemt_handshake_timeouts_total 2582
telemt_upstream_connect_attempt_total 3010
telemt_upstream_connect_success_total 2998
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 3010
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1358
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1638
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 81
telemt_me_reconnect_attempts_total 2366
telemt_me_reconnect_success_total 2352
telemt_me_reader_eof_total 2440
telemt_me_idle_close_by_peer_total 2439
telemt_me_route_drop_no_conn_total 17113
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 56959
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 224
telemt_desync_full_logged_total 86
telemt_desync_suppressed_total 138
telemt_desync_frames_bucket_total{bucket="1_2"} 51
telemt_desync_frames_bucket_total{bucket="3_10"} 81
telemt_desync_frames_bucket_total{bucket="gt_10"} 92
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 2364
telemt_me_writer_restored_same_endpoint_total 2336
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 56935
telemt_user_connections_current{user="hello"} 310
telemt_user_octets_from_client{user="hello"} 785385712 (749.00 MB)
telemt_user_octets_to_client{user="hello"} 17110964920 (15.94 GB)
telemt_user_unique_ips_current{user="hello"} 95
telemt_user_unique_ips_recent_window{user="hello"} 53
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 12041.0 (3h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 25656
telemt_connections_bad_total 218
telemt_handshake_timeouts_total 192
telemt_upstream_connect_attempt_total 4370
telemt_upstream_connect_success_total 4281
telemt_upstream_connect_fail_total 89
telemt_upstream_connect_attempts_per_request{bucket="1"} 4370
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1626
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2652
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 89
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 9893
telemt_me_reconnect_success_total 3640
telemt_me_reader_eof_total 3879
telemt_me_idle_close_by_peer_total 3879
telemt_me_route_drop_no_conn_total 9892
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 24401
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 2
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
telemt_me_writer_removed_unexpected_total 3849
telemt_me_refill_failed_total 195
telemt_me_writer_restored_same_endpoint_total 3625
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 209
telemt_user_connections_total{user="hello"} 24399
telemt_user_connections_current{user="hello"} 117
telemt_user_octets_from_client{user="hello"} 258113972 (246.16 MB)
telemt_user_octets_to_client{user="hello"} 5302242564 (4.94 GB)
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 12004.5 (3h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 36274
telemt_connections_bad_total 102
telemt_handshake_timeouts_total 277
telemt_upstream_connect_attempt_total 3371
telemt_upstream_connect_success_total 3371
telemt_upstream_connect_attempts_per_request{bucket="1"} 3371
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1679
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1688
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 55
telemt_me_reconnect_attempts_total 2735
telemt_me_reconnect_success_total 2718
telemt_me_reader_eof_total 2842
telemt_me_idle_close_by_peer_total 2842
telemt_me_route_drop_no_conn_total 11698
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 33942
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 4
telemt_desync_frames_bucket_total{bucket="3_10"} 6
telemt_desync_frames_bucket_total{bucket="gt_10"} 4
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 2720
telemt_me_writer_restored_same_endpoint_total 2698
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 33931
telemt_user_connections_current{user="hello"} 158
telemt_user_octets_from_client{user="hello"} 461897932 (440.50 MB)
telemt_user_octets_to_client{user="hello"} 28910879544 (26.93 GB)
telemt_user_unique_ips_current{user="hello"} 68
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 11980.0 (3h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 43906
telemt_connections_bad_total 1034
telemt_handshake_timeouts_total 227
telemt_upstream_connect_attempt_total 3493
telemt_upstream_connect_success_total 3411
telemt_upstream_connect_fail_total 82
telemt_upstream_connect_attempts_per_request{bucket="1"} 3493
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1447
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1955
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 82
telemt_me_keepalive_timeout_total 158
telemt_me_reconnect_attempts_total 2799
telemt_me_reconnect_success_total 2761
telemt_me_reader_eof_total 2869
telemt_me_idle_close_by_peer_total 2869
telemt_me_route_drop_no_conn_total 13446
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 39806
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 160
telemt_desync_full_logged_total 56
telemt_desync_suppressed_total 104
telemt_desync_frames_bucket_total{bucket="1_2"} 64
telemt_desync_frames_bucket_total{bucket="3_10"} 54
telemt_desync_frames_bucket_total{bucket="gt_10"} 42
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 2800
telemt_me_writer_restored_same_endpoint_total 2753
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 121
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 39805
telemt_user_connections_current{user="hello"} 227
telemt_user_octets_from_client{user="hello"} 911504460 (869.28 MB)
telemt_user_octets_to_client{user="hello"} 25359371656 (23.62 GB)
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 11949.5 (3h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 22981
telemt_connections_bad_total 2295
telemt_handshake_timeouts_total 385
telemt_upstream_connect_attempt_total 3861
telemt_upstream_connect_success_total 3716
telemt_upstream_connect_fail_total 145
telemt_upstream_connect_attempts_per_request{bucket="1"} 3861
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1328
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2377
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 145
telemt_me_keepalive_timeout_total 78
telemt_me_reconnect_attempts_total 13199
telemt_me_reconnect_success_total 3070
telemt_me_reader_eof_total 3379
telemt_me_idle_close_by_peer_total 3379
telemt_me_seq_mismatch_total 5
telemt_me_route_drop_no_conn_total 6864
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 19629
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 312
telemt_desync_full_logged_total 90
telemt_desync_suppressed_total 222
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 263
telemt_desync_frames_bucket_total{bucket="gt_10"} 42
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 3401
telemt_me_refill_failed_total 316
telemt_me_writer_restored_same_endpoint_total 3054
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 331
telemt_user_connections_total{user="hello"} 19626
telemt_user_connections_current{user="hello"} 122
telemt_user_octets_from_client{user="hello"} 93358492 (89.03 MB)
telemt_user_octets_to_client{user="hello"} 5319469324 (4.95 GB)
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 11936.3 (3h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 60288
telemt_connections_bad_total 577
telemt_handshake_timeouts_total 700
telemt_upstream_connect_attempt_total 2380
telemt_upstream_connect_success_total 2368
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 2380
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1152
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1214
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 63
telemt_me_reconnect_attempts_total 1744
telemt_me_reconnect_success_total 1730
telemt_me_reader_eof_total 1819
telemt_me_idle_close_by_peer_total 1819
telemt_me_route_drop_no_conn_total 26423
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 56834
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 142
telemt_desync_full_logged_total 49
telemt_desync_suppressed_total 93
telemt_desync_frames_bucket_total{bucket="1_2"} 39
telemt_desync_frames_bucket_total{bucket="3_10"} 49
telemt_desync_frames_bucket_total{bucket="gt_10"} 54
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 1751
telemt_me_writer_restored_same_endpoint_total 1723
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 21
telemt_user_connections_total{user="hello"} 56797
telemt_user_connections_current{user="hello"} 321
telemt_user_octets_from_client{user="hello"} 1911627376 (1.78 GB)
telemt_user_octets_to_client{user="hello"} 32420601064 (30.19 GB)
telemt_user_unique_ips_current{user="hello"} 107
telemt_user_unique_ips_recent_window{user="hello"} 46
```