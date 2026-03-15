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

# Server Metrics 2026-03-15 19:44:11 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 77382.9 (21h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 363927
telemt_connections_bad_total 4431
telemt_handshake_timeouts_total 13573
telemt_upstream_connect_attempt_total 18555
telemt_upstream_connect_success_total 18462
telemt_upstream_connect_fail_total 93
telemt_upstream_connect_attempts_per_request{bucket="1"} 18555
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8178
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10241
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 93
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 32
telemt_me_reconnect_attempts_total 18021
telemt_me_reconnect_success_total 14620
telemt_me_reader_eof_total 15585
telemt_me_idle_close_by_peer_total 15585
telemt_me_route_drop_no_conn_total 474711
telemt_me_route_drop_channel_closed_total 77
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 393128
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1936
telemt_desync_full_logged_total 761
telemt_desync_suppressed_total 1175
telemt_desync_frames_bucket_total{bucket="1_2"} 367
telemt_desync_frames_bucket_total{bucket="3_10"} 751
telemt_desync_frames_bucket_total{bucket="gt_10"} 818
telemt_pool_swap_total 69
telemt_me_writer_removed_unexpected_total 14887
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 14586
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 267
telemt_user_connections_total{user="hello"} 332192
telemt_user_connections_current{user="hello"} 313
telemt_user_octets_from_client{user="hello"} 7512580328 (7.00 GB)
telemt_user_octets_to_client{user="hello"} 255821250416 (238.25 GB)
telemt_user_unique_ips_current{user="hello"} 98
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 77390.4 (21h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 148652
telemt_connections_bad_total 2845
telemt_handshake_timeouts_total 12854
telemt_upstream_connect_attempt_total 21098
telemt_upstream_connect_success_total 21069
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 21098
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9118
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11468
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 483
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 954
telemt_me_reconnect_attempts_total 19286
telemt_me_reconnect_success_total 16860
telemt_me_reader_eof_total 18000
telemt_me_idle_close_by_peer_total 17999
telemt_me_route_drop_no_conn_total 62388
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 126757
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3
telemt_desync_full_logged_total 3
telemt_desync_frames_bucket_total{bucket="1_2"} 1
telemt_desync_frames_bucket_total{bucket="3_10"} 2
telemt_pool_swap_total 66
telemt_me_writer_removed_unexpected_total 17180
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 16844
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 320
telemt_user_connections_total{user="hello"} 127029
telemt_user_connections_current{user="hello"} 184
telemt_user_octets_from_client{user="hello"} 2372030609 (2.21 GB)
telemt_user_octets_to_client{user="hello"} 62437915080 (58.15 GB)
telemt_user_msgs_from_client{user="hello"} 721
telemt_user_msgs_to_client{user="hello"} 1482
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 77382.9 (21h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 150033
telemt_connections_bad_total 1722
telemt_handshake_timeouts_total 3361
telemt_upstream_connect_attempt_total 22288
telemt_upstream_connect_success_total 22280
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 22288
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9688
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12546
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 25746
telemt_me_reconnect_success_total 18381
telemt_me_reader_eof_total 19732
telemt_me_idle_close_by_peer_total 19732
telemt_me_route_drop_no_conn_total 59018
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 132719
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 60
telemt_desync_full_logged_total 24
telemt_desync_suppressed_total 36
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 30
telemt_desync_frames_bucket_total{bucket="gt_10"} 25
telemt_pool_swap_total 64
telemt_me_writer_removed_unexpected_total 18794
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 18373
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 413
telemt_user_connections_total{user="hello"} 132606
telemt_user_connections_current{user="hello"} 147
telemt_user_octets_from_client{user="hello"} 10843073656 (10.10 GB)
telemt_user_octets_to_client{user="hello"} 73011085816 (68.00 GB)
telemt_user_unique_ips_current{user="hello"} 64
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 77382.6 (21h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 213809
telemt_connections_bad_total 1148
telemt_handshake_timeouts_total 1562
telemt_upstream_connect_attempt_total 18135
telemt_upstream_connect_success_total 18120
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 18135
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8691
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9354
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 14369
telemt_me_reconnect_success_total 14281
telemt_me_reader_eof_total 15205
telemt_me_idle_close_by_peer_total 15205
telemt_me_route_drop_no_conn_total 79069
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 196892
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 712
telemt_desync_full_logged_total 263
telemt_desync_suppressed_total 449
telemt_desync_frames_bucket_total{bucket="1_2"} 144
telemt_desync_frames_bucket_total{bucket="3_10"} 326
telemt_desync_frames_bucket_total{bucket="gt_10"} 242
telemt_pool_swap_total 71
telemt_me_writer_removed_unexpected_total 14450
telemt_me_writer_restored_same_endpoint_total 14270
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 169
telemt_user_connections_total{user="hello"} 196810
telemt_user_connections_current{user="hello"} 225
telemt_user_octets_from_client{user="hello"} 3698428576 (3.44 GB)
telemt_user_octets_to_client{user="hello"} 90336124400 (84.13 GB)
telemt_user_unique_ips_current{user="hello"} 71
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 52454.2 (14h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 128270
telemt_connections_bad_total 25477
telemt_handshake_timeouts_total 2501
telemt_upstream_connect_attempt_total 15449
telemt_upstream_connect_success_total 15355
telemt_upstream_connect_fail_total 94
telemt_upstream_connect_attempts_per_request{bucket="1"} 15449
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7002
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8261
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 92
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 94
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 106991
telemt_me_reconnect_success_total 12542
telemt_me_reader_eof_total 13190
telemt_me_idle_close_by_peer_total 13190
telemt_me_route_drop_no_conn_total 43871
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 96747
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 307
telemt_desync_full_logged_total 66
telemt_desync_suppressed_total 241
telemt_desync_frames_bucket_total{bucket="1_2"} 46
telemt_desync_frames_bucket_total{bucket="3_10"} 113
telemt_desync_frames_bucket_total{bucket="gt_10"} 148
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 12625
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 12438
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 83
telemt_user_connections_total{user="hello"} 96877
telemt_user_connections_current{user="hello"} 92
telemt_user_octets_from_client{user="hello"} 1572163053 (1.46 GB)
telemt_user_octets_to_client{user="hello"} 37063084367 (34.52 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 77382.4 (21h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 524428
telemt_connections_bad_total 58014
telemt_handshake_timeouts_total 4266
telemt_upstream_connect_attempt_total 16460
telemt_upstream_connect_success_total 16367
telemt_upstream_connect_fail_total 93
telemt_upstream_connect_attempts_per_request{bucket="1"} 16460
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7858
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8470
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 93
telemt_me_keepalive_timeout_total 62
telemt_me_reconnect_attempts_total 13808
telemt_me_reconnect_success_total 12499
telemt_me_reader_eof_total 13283
telemt_me_idle_close_by_peer_total 13283
telemt_me_route_drop_no_conn_total 357120
telemt_me_route_drop_channel_closed_total 91
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 498115
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 322
telemt_desync_full_logged_total 89
telemt_desync_suppressed_total 233
telemt_desync_frames_bucket_total{bucket="1_2"} 169
telemt_desync_frames_bucket_total{bucket="3_10"} 95
telemt_desync_frames_bucket_total{bucket="gt_10"} 58
telemt_pool_swap_total 66
telemt_me_writer_removed_unexpected_total 12675
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 12472
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 176
telemt_user_connections_total{user="hello"} 442675
telemt_user_connections_current{user="hello"} 611
telemt_user_octets_from_client{user="hello"} 11236770068 (10.47 GB)
telemt_user_octets_to_client{user="hello"} 249251158432 (232.13 GB)
telemt_user_unique_ips_current{user="hello"} 190
telemt_user_unique_ips_recent_window{user="hello"} 68
```