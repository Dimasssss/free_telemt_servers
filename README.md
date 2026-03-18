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

# Server Metrics 2026-03-18 09:46:12 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.20

telemt_uptime_seconds 3911.6 (1h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 157786
telemt_connections_bad_total 754
telemt_handshake_timeouts_total 2950
telemt_upstream_connect_attempt_total 63729
telemt_upstream_connect_success_total 62814
telemt_upstream_connect_fail_total 915
telemt_upstream_connect_attempts_per_request{bucket="1"} 63729
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 59321
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2911
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 582
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 915
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 506143
telemt_me_reconnect_success_total 624
telemt_me_reader_eof_total 532
telemt_me_idle_close_by_peer_total 530
telemt_me_route_drop_no_conn_total 27717
telemt_me_route_drop_channel_closed_total 22
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 73412
telemt_me_writer_pick_total{mode="p2c",result="full"} 21
telemt_me_writer_pick_total{mode="p2c",result="closed"} 54
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 376
telemt_desync_full_logged_total 111
telemt_desync_suppressed_total 265
telemt_desync_frames_bucket_total{bucket="1_2"} 119
telemt_desync_frames_bucket_total{bucket="3_10"} 123
telemt_desync_frames_bucket_total{bucket="gt_10"} 134
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 573
telemt_me_refill_failed_total 16481
telemt_me_writer_restored_same_endpoint_total 519
telemt_me_writer_restored_fallback_total 105
telemt_me_async_recovery_trigger_total 11769
telemt_user_connections_total{user="hello"} 135278
telemt_user_connections_current{user="hello"} 1581
telemt_user_octets_from_client{user="hello"} 1620964836 (1.51 GB)
telemt_user_octets_to_client{user="hello"} 29905358133 (27.85 GB)
telemt_user_msgs_from_client{user="hello"} 846607
telemt_user_msgs_to_client{user="hello"} 1165163
telemt_user_unique_ips_current{user="hello"} 470
telemt_user_unique_ips_recent_window{user="hello"} 222
```

## psb.hosting

```
telemt 3.3.20

telemt_uptime_seconds 3942.9 (1h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 351076
telemt_connections_bad_total 38781
telemt_handshake_timeouts_total 8807
telemt_upstream_connect_attempt_total 685
telemt_upstream_connect_success_total 685
telemt_upstream_connect_attempts_per_request{bucket="1"} 685
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 423
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 257
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_failed_total 1
telemt_me_reconnect_attempts_total 440
telemt_me_reconnect_success_total 429
telemt_me_reader_eof_total 396
telemt_me_idle_close_by_peer_total 396
telemt_me_route_drop_no_conn_total 110275
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 279371
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1329
telemt_desync_full_logged_total 339
telemt_desync_suppressed_total 990
telemt_desync_frames_bucket_total{bucket="1_2"} 263
telemt_desync_frames_bucket_total{bucket="3_10"} 522
telemt_desync_frames_bucket_total{bucket="gt_10"} 544
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 405
telemt_me_writer_restored_same_endpoint_total 428
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 1068
telemt_user_connections_total{user="hello"} 278638
telemt_user_connections_current{user="hello"} 3979
telemt_user_octets_from_client{user="hello"} 7348423684 (6.84 GB)
telemt_user_octets_to_client{user="hello"} 101215114352 (94.26 GB)
telemt_user_unique_ips_current{user="hello"} 1118
telemt_user_unique_ips_recent_window{user="hello"} 546
```

## koara.io

```
telemt 3.3.20

telemt_uptime_seconds 3858.2 (1h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 291758
telemt_connections_bad_total 15305
telemt_handshake_timeouts_total 7282
telemt_upstream_connect_attempt_total 9010
telemt_upstream_connect_success_total 9010
telemt_upstream_connect_attempts_per_request{bucket="1"} 9010
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7382
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1621
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 40
telemt_me_reconnect_attempts_total 606229
telemt_me_reconnect_success_total 558
telemt_me_reader_eof_total 523
telemt_me_idle_close_by_peer_total 522
telemt_me_route_drop_no_conn_total 152414
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 210212
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 483
telemt_desync_full_logged_total 172
telemt_desync_suppressed_total 311
telemt_desync_frames_bucket_total{bucket="1_2"} 99
telemt_desync_frames_bucket_total{bucket="3_10"} 219
telemt_desync_frames_bucket_total{bucket="gt_10"} 165
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 548
telemt_me_refill_failed_total 19672
telemt_me_writer_restored_same_endpoint_total 523
telemt_me_writer_restored_fallback_total 35
telemt_me_async_recovery_trigger_total 14895
telemt_user_connections_total{user="hello"} 218262
telemt_user_connections_current{user="hello"} 2605
telemt_user_octets_from_client{user="hello"} 2101842263 (1.96 GB)
telemt_user_octets_to_client{user="hello"} 70677853636 (65.82 GB)
telemt_user_msgs_from_client{user="hello"} 68547
telemt_user_msgs_to_client{user="hello"} 285346
telemt_user_unique_ips_current{user="hello"} 787
telemt_user_unique_ips_recent_window{user="hello"} 351
```

## landvps.ru

```
telemt 3.3.20

telemt_uptime_seconds 3887.8 (1h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 609824
telemt_connections_bad_total 6719
telemt_handshake_timeouts_total 63438
telemt_upstream_connect_attempt_total 11442
telemt_upstream_connect_success_total 11341
telemt_upstream_connect_fail_total 101
telemt_upstream_connect_attempts_per_request{bucket="1"} 11442
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10306
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1000
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 101
telemt_me_keepalive_timeout_total 699
telemt_me_reconnect_attempts_total 2813169
telemt_me_reconnect_success_total 812
telemt_me_reader_eof_total 860
telemt_me_idle_close_by_peer_total 860
telemt_me_route_drop_no_conn_total 1288253
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 479547
telemt_me_writer_pick_total{mode="p2c",result="success_fallback"} 8840
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_writer_pick_blocking_fallback_total 8840
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 536
telemt_desync_full_logged_total 158
telemt_desync_suppressed_total 378
telemt_desync_frames_bucket_total{bucket="1_2"} 111
telemt_desync_frames_bucket_total{bucket="3_10"} 240
telemt_desync_frames_bucket_total{bucket="gt_10"} 185
telemt_me_writer_removed_unexpected_total 884
telemt_me_refill_failed_total 99624
telemt_me_writer_restored_same_endpoint_total 717
telemt_me_writer_restored_fallback_total 95
telemt_me_async_recovery_trigger_total 365465
telemt_me_writer_removed_unexpected_minus_restored_total 72
telemt_user_connections_total{user="hello"} 498541
telemt_user_connections_current{user="hello"} 3182
telemt_user_octets_from_client{user="hello"} 3059653806 (2.85 GB)
telemt_user_octets_to_client{user="hello"} 47826226009 (44.54 GB)
telemt_user_msgs_from_client{user="hello"} 80007
telemt_user_msgs_to_client{user="hello"} 158054
telemt_user_unique_ips_current{user="hello"} 833
telemt_user_unique_ips_recent_window{user="hello"} 415
```

## rdp-onedash.ru

```
telemt 3.3.20

telemt_uptime_seconds 3784.3 (1h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 268494
telemt_connections_bad_total 8727
telemt_handshake_timeouts_total 3514
telemt_upstream_connect_attempt_total 10368
telemt_upstream_connect_success_total 10367
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 10368
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9427
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 733
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 207
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 2982566
telemt_me_reconnect_success_total 617
telemt_me_reader_eof_total 559
telemt_me_idle_close_by_peer_total 559
telemt_me_route_drop_no_conn_total 80536
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 212325
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 602
telemt_desync_full_logged_total 222
telemt_desync_suppressed_total 380
telemt_desync_frames_bucket_total{bucket="1_2"} 89
telemt_desync_frames_bucket_total{bucket="3_10"} 230
telemt_desync_frames_bucket_total{bucket="gt_10"} 283
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 566
telemt_me_refill_failed_total 107153
telemt_me_writer_restored_same_endpoint_total 502
telemt_me_writer_restored_fallback_total 115
telemt_me_async_recovery_trigger_total 267383
telemt_user_connections_total{user="hello"} 221669
telemt_user_connections_current{user="hello"} 3375
telemt_user_octets_from_client{user="hello"} 4151070505 (3.87 GB)
telemt_user_octets_to_client{user="hello"} 88226820805 (82.17 GB)
telemt_user_msgs_from_client{user="hello"} 86293
telemt_user_msgs_to_client{user="hello"} 266108
telemt_user_unique_ips_current{user="hello"} 949
telemt_user_unique_ips_recent_window{user="hello"} 545
```

## hostvds.com

```
telemt 3.3.20

telemt_uptime_seconds 3667.6 (1h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 75376
telemt_connections_bad_total 10637
telemt_handshake_timeouts_total 403
telemt_upstream_connect_attempt_total 572
telemt_upstream_connect_success_total 572
telemt_upstream_connect_attempts_per_request{bucket="1"} 572
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 321
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 251
telemt_me_reconnect_attempts_total 347
telemt_me_reconnect_success_total 345
telemt_me_reader_eof_total 328
telemt_me_idle_close_by_peer_total 328
telemt_me_route_drop_no_conn_total 25528
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 61655
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 128
telemt_desync_full_logged_total 50
telemt_desync_suppressed_total 78
telemt_desync_frames_bucket_total{bucket="1_2"} 23
telemt_desync_frames_bucket_total{bucket="3_10"} 56
telemt_desync_frames_bucket_total{bucket="gt_10"} 49
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 335
telemt_me_writer_restored_same_endpoint_total 337
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 130
telemt_user_connections_total{user="hello"} 59276
telemt_user_connections_current{user="hello"} 824
telemt_user_octets_from_client{user="hello"} 1143163452 (1.06 GB)
telemt_user_octets_to_client{user="hello"} 13823214924 (12.87 GB)
telemt_user_unique_ips_current{user="hello"} 304
telemt_user_unique_ips_recent_window{user="hello"} 129
```

## 4vps.su

```
telemt 3.3.20

telemt_uptime_seconds 3738.8 (1h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 190112
telemt_connections_bad_total 5270
telemt_handshake_timeouts_total 2866
telemt_upstream_connect_attempt_total 609
telemt_upstream_connect_success_total 592
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 609
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 341
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 244
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_reconnect_attempts_total 349
telemt_me_reconnect_success_total 340
telemt_me_reader_eof_total 311
telemt_me_idle_close_by_peer_total 311
telemt_me_route_drop_no_conn_total 121978
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 168395
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 491
telemt_desync_full_logged_total 161
telemt_desync_suppressed_total 330
telemt_desync_frames_bucket_total{bucket="1_2"} 93
telemt_desync_frames_bucket_total{bucket="3_10"} 191
telemt_desync_frames_bucket_total{bucket="gt_10"} 207
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 328
telemt_me_writer_restored_same_endpoint_total 330
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 2494
telemt_user_connections_total{user="hello"} 168264
telemt_user_connections_current{user="hello"} 2535
telemt_user_octets_from_client{user="hello"} 2504309604 (2.33 GB)
telemt_user_octets_to_client{user="hello"} 73554838288 (68.50 GB)
telemt_user_unique_ips_current{user="hello"} 706
telemt_user_unique_ips_recent_window{user="hello"} 326
```