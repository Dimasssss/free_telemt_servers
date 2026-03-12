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

# Server Metrics 2026-03-12 13:59:49 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 23186.2 (6h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 122796
telemt_connections_bad_total 1360
telemt_handshake_timeouts_total 4355
telemt_upstream_connect_attempt_total 5677
telemt_upstream_connect_success_total 5653
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 5677
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2513
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3134
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_keepalive_timeout_total 249
telemt_me_reconnect_attempts_total 4488
telemt_me_reconnect_success_total 4459
telemt_me_reader_eof_total 4669
telemt_me_idle_close_by_peer_total 4668
telemt_me_route_drop_no_conn_total 34379
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 107758
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 524
telemt_desync_full_logged_total 192
telemt_desync_suppressed_total 332
telemt_desync_frames_bucket_total{bucket="1_2"} 97
telemt_desync_frames_bucket_total{bucket="3_10"} 203
telemt_desync_frames_bucket_total{bucket="gt_10"} 224
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 4496
telemt_me_writer_restored_same_endpoint_total 4443
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 107720
telemt_user_connections_current{user="hello"} 350
telemt_user_octets_from_client{user="hello"} 1721599972 (1.60 GB)
telemt_user_octets_to_client{user="hello"} 40942003240 (38.13 GB)
telemt_user_unique_ips_current{user="hello"} 109
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 23079.4 (6h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 49865
telemt_connections_bad_total 380
telemt_handshake_timeouts_total 352
telemt_upstream_connect_attempt_total 6789
telemt_upstream_connect_success_total 6629
telemt_upstream_connect_fail_total 160
telemt_upstream_connect_attempts_per_request{bucket="1"} 6789
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2762
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3847
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 160
telemt_me_keepalive_timeout_total 156
telemt_me_reconnect_attempts_total 21287
telemt_me_reconnect_success_total 5455
telemt_me_reader_eof_total 6060
telemt_me_idle_close_by_peer_total 6060
telemt_me_route_drop_no_conn_total 22445
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 47602
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 5
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
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 5981
telemt_me_refill_failed_total 494
telemt_me_writer_restored_same_endpoint_total 5440
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 526
telemt_user_connections_total{user="hello"} 47596
telemt_user_connections_current{user="hello"} 134
telemt_user_octets_from_client{user="hello"} 572501680 (545.98 MB)
telemt_user_octets_to_client{user="hello"} 13546028064 (12.62 GB)
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 23043.0 (6h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 67702
telemt_connections_bad_total 341
telemt_handshake_timeouts_total 817
telemt_upstream_connect_attempt_total 6243
telemt_upstream_connect_success_total 6243
telemt_upstream_connect_attempts_per_request{bucket="1"} 6243
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3032
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3202
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 111
telemt_me_reconnect_attempts_total 5074
telemt_me_reconnect_success_total 5036
telemt_me_reader_eof_total 5324
telemt_me_idle_close_by_peer_total 5324
telemt_me_route_drop_no_conn_total 23810
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 63547
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
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 5072
telemt_me_writer_restored_same_endpoint_total 5016
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 36
telemt_user_connections_total{user="hello"} 63529
telemt_user_connections_current{user="hello"} 171
telemt_user_octets_from_client{user="hello"} 1836841312 (1.71 GB)
telemt_user_octets_to_client{user="hello"} 36008346276 (33.54 GB)
telemt_user_unique_ips_current{user="hello"} 75
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 23018.6 (6h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 87302
telemt_connections_bad_total 1510
telemt_handshake_timeouts_total 413
telemt_upstream_connect_attempt_total 6191
telemt_upstream_connect_success_total 6033
telemt_upstream_connect_fail_total 158
telemt_upstream_connect_attempts_per_request{bucket="1"} 6191
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2665
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3347
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 158
telemt_me_keepalive_timeout_total 237
telemt_me_reconnect_attempts_total 16635
telemt_me_reconnect_success_total 4839
telemt_me_reader_eof_total 5337
telemt_me_idle_close_by_peer_total 5337
telemt_me_route_drop_no_conn_total 32714
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 80255
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 252
telemt_desync_full_logged_total 85
telemt_desync_suppressed_total 167
telemt_desync_frames_bucket_total{bucket="1_2"} 89
telemt_desync_frames_bucket_total{bucket="3_10"} 84
telemt_desync_frames_bucket_total{bucket="gt_10"} 79
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 5262
telemt_me_refill_failed_total 367
telemt_me_writer_restored_same_endpoint_total 4831
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 121
telemt_me_writer_removed_unexpected_minus_restored_total 423
telemt_user_connections_total{user="hello"} 80138
telemt_user_connections_current{user="hello"} 199
telemt_user_octets_from_client{user="hello"} 1302521552 (1.21 GB)
telemt_user_octets_to_client{user="hello"} 34897327324 (32.50 GB)
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 22988.1 (6h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 51007
telemt_connections_bad_total 4362
telemt_handshake_timeouts_total 684
telemt_upstream_connect_attempt_total 17537
telemt_upstream_connect_success_total 17249
telemt_upstream_connect_fail_total 288
telemt_upstream_connect_attempts_per_request{bucket="1"} 17537
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13390
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3832
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 288
telemt_me_keepalive_timeout_total 105
telemt_me_reconnect_attempts_total 30071
telemt_me_reconnect_success_total 3676
telemt_me_reader_eof_total 4497
telemt_me_idle_close_by_peer_total 4497
telemt_me_seq_mismatch_total 8
telemt_me_route_drop_no_conn_total 12099
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 32352
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 439
telemt_desync_full_logged_total 121
telemt_desync_suppressed_total 318
telemt_desync_frames_bucket_total{bucket="1_2"} 16
telemt_desync_frames_bucket_total{bucket="3_10"} 365
telemt_desync_frames_bucket_total{bucket="gt_10"} 58
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 4522
telemt_me_refill_failed_total 826
telemt_me_writer_restored_same_endpoint_total 3659
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 846
telemt_user_connections_total{user="hello"} 44733
telemt_user_connections_current{user="hello"} 123
telemt_user_octets_from_client{user="hello"} 368702883 (351.62 MB)
telemt_user_octets_to_client{user="hello"} 11556797135 (10.76 GB)
telemt_user_msgs_from_client{user="hello"} 177288
telemt_user_msgs_to_client{user="hello"} 493767
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 22975.0 (6h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 137066
telemt_connections_bad_total 775
telemt_handshake_timeouts_total 1011
telemt_upstream_connect_attempt_total 4751
telemt_upstream_connect_success_total 4728
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 4751
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2249
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2477
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_timeout_total 112
telemt_me_reconnect_attempts_total 3576
telemt_me_reconnect_success_total 3547
telemt_me_reader_eof_total 3731
telemt_me_idle_close_by_peer_total 3731
telemt_me_route_drop_no_conn_total 54456
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 130926
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 222
telemt_desync_full_logged_total 78
telemt_desync_suppressed_total 144
telemt_desync_frames_bucket_total{bucket="1_2"} 53
telemt_desync_frames_bucket_total{bucket="3_10"} 87
telemt_desync_frames_bucket_total{bucket="gt_10"} 82
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 3589
telemt_me_writer_restored_same_endpoint_total 3540
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 42
telemt_user_connections_total{user="hello"} 130893
telemt_user_connections_current{user="hello"} 453
telemt_user_octets_from_client{user="hello"} 2786056800 (2.59 GB)
telemt_user_octets_to_client{user="hello"} 54284292188 (50.56 GB)
telemt_user_unique_ips_current{user="hello"} 137
telemt_user_unique_ips_recent_window{user="hello"} 65
```