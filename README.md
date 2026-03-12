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

# Server Metrics 2026-03-12 08:17:22 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 2640.1 (0h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16139
telemt_connections_bad_total 3
telemt_handshake_timeouts_total 1886
telemt_upstream_connect_attempt_total 537
telemt_upstream_connect_success_total 535
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 537
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 244
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 290
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 384
telemt_me_reconnect_success_total 383
telemt_me_reader_eof_total 365
telemt_me_idle_close_by_peer_total 365
telemt_me_route_drop_no_conn_total 3894
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13267
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 56
telemt_desync_full_logged_total 17
telemt_desync_suppressed_total 39
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 26
telemt_desync_frames_bucket_total{bucket="gt_10"} 24
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 375
telemt_me_writer_restored_same_endpoint_total 367
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_user_connections_total{user="hello"} 13264
telemt_user_connections_current{user="hello"} 327
telemt_user_octets_from_client{user="hello"} 113605628 (108.34 MB)
telemt_user_octets_to_client{user="hello"} 5149057684 (4.80 GB)
telemt_user_unique_ips_current{user="hello"} 93
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 2532.8 (0h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5300
telemt_connections_bad_total 8
telemt_handshake_timeouts_total 25
telemt_upstream_connect_attempt_total 950
telemt_upstream_connect_success_total 930
telemt_upstream_connect_fail_total 20
telemt_upstream_connect_attempts_per_request{bucket="1"} 950
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 282
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 648
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 20
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 1067
telemt_me_reconnect_success_total 777
telemt_me_reader_eof_total 745
telemt_me_idle_close_by_peer_total 745
telemt_me_route_drop_no_conn_total 1630
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5053
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_writer_removed_unexpected_total 768
telemt_me_refill_failed_total 9
telemt_me_writer_restored_same_endpoint_total 762
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_user_connections_total{user="hello"} 5051
telemt_user_connections_current{user="hello"} 132
telemt_user_octets_from_client{user="hello"} 32881452 (31.36 MB)
telemt_user_octets_to_client{user="hello"} 1247450956 (1.16 GB)
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 2496.5 (0h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7780
telemt_connections_bad_total 7
telemt_handshake_timeouts_total 57
telemt_upstream_connect_attempt_total 554
telemt_upstream_connect_success_total 554
telemt_upstream_connect_attempts_per_request{bucket="1"} 554
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 287
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 266
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 6
telemt_me_reconnect_attempts_total 404
telemt_me_reconnect_success_total 402
telemt_me_reader_eof_total 379
telemt_me_idle_close_by_peer_total 379
telemt_me_route_drop_no_conn_total 2322
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7381
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8
telemt_desync_full_logged_total 4
telemt_desync_suppressed_total 4
telemt_desync_frames_bucket_total{bucket="3_10"} 4
telemt_desync_frames_bucket_total{bucket="gt_10"} 4
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 380
telemt_me_writer_restored_same_endpoint_total 382
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_user_connections_total{user="hello"} 7380
telemt_user_connections_current{user="hello"} 208
telemt_user_octets_from_client{user="hello"} 87575628 (83.52 MB)
telemt_user_octets_to_client{user="hello"} 10529285292 (9.81 GB)
telemt_user_unique_ips_current{user="hello"} 70
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 2472.2 (0h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9468
telemt_connections_bad_total 1012
telemt_handshake_timeouts_total 33
telemt_upstream_connect_attempt_total 589
telemt_upstream_connect_success_total 556
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 589
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 243
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 312
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 419
telemt_me_reconnect_success_total 399
telemt_me_reader_eof_total 388
telemt_me_idle_close_by_peer_total 388
telemt_me_route_drop_no_conn_total 2403
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7786
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 17
telemt_desync_full_logged_total 7
telemt_desync_suppressed_total 10
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 5
telemt_desync_frames_bucket_total{bucket="gt_10"} 6
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 407
telemt_me_writer_restored_same_endpoint_total 391
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 121
telemt_me_writer_removed_unexpected_minus_restored_total 8
telemt_user_connections_total{user="hello"} 7786
telemt_user_connections_current{user="hello"} 207
telemt_user_octets_from_client{user="hello"} 96355424 (91.89 MB)
telemt_user_octets_to_client{user="hello"} 1878359356 (1.75 GB)
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 2441.6 (0h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4603
telemt_connections_bad_total 518
telemt_handshake_timeouts_total 84
telemt_upstream_connect_attempt_total 775
telemt_upstream_connect_success_total 741
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 775
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 310
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 429
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 591
telemt_me_reconnect_success_total 590
telemt_me_reader_eof_total 561
telemt_me_idle_close_by_peer_total 561
telemt_me_seq_mismatch_total 1
telemt_me_route_drop_no_conn_total 1307
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3885
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 58
telemt_desync_full_logged_total 20
telemt_desync_suppressed_total 38
telemt_desync_frames_bucket_total{bucket="1_2"} 1
telemt_desync_frames_bucket_total{bucket="3_10"} 47
telemt_desync_frames_bucket_total{bucket="gt_10"} 10
telemt_me_writer_removed_unexpected_total 580
telemt_me_writer_restored_same_endpoint_total 578
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 18
telemt_user_connections_total{user="hello"} 3885
telemt_user_connections_current{user="hello"} 100
telemt_user_octets_from_client{user="hello"} 12791992 (12.20 MB)
telemt_user_octets_to_client{user="hello"} 598782184 (571.04 MB)
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 2428.6 (0h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11603
telemt_connections_bad_total 491
telemt_handshake_timeouts_total 120
telemt_upstream_connect_attempt_total 378
telemt_upstream_connect_success_total 375
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 378
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 199
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 176
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 226
telemt_me_reconnect_success_total 225
telemt_me_reader_eof_total 215
telemt_me_idle_close_by_peer_total 215
telemt_me_route_drop_no_conn_total 5140
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10468
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4
telemt_desync_full_logged_total 2
telemt_desync_suppressed_total 2
telemt_desync_frames_bucket_total{bucket="3_10"} 4
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 229
telemt_me_writer_restored_same_endpoint_total 218
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 10442
telemt_user_connections_current{user="hello"} 304
telemt_user_octets_from_client{user="hello"} 292877936 (279.31 MB)
telemt_user_octets_to_client{user="hello"} 7854568208 (7.32 GB)
telemt_user_unique_ips_current{user="hello"} 103
telemt_user_unique_ips_recent_window{user="hello"} 40
```