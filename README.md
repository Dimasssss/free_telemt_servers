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

# Server Metrics 2026-03-19 02:49:11 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 18043.4 (5h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 219890
telemt_connections_bad_total 26485
telemt_connections_current 693
telemt_connections_me_current 693
telemt_handshake_timeouts_total 13466
telemt_upstream_connect_attempt_total 3566
telemt_upstream_connect_success_total 3509
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 3566
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1684
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1822
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 2620
telemt_me_reconnect_success_total 2607
telemt_me_reader_eof_total 2726
telemt_me_idle_close_by_peer_total 2726
telemt_me_seq_mismatch_total 5
telemt_me_route_drop_no_conn_total 60277
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 170141
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1169
telemt_desync_full_logged_total 309
telemt_desync_suppressed_total 860
telemt_desync_frames_bucket_total{bucket="1_2"} 433
telemt_desync_frames_bucket_total{bucket="3_10"} 501
telemt_desync_frames_bucket_total{bucket="gt_10"} 235
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 2621
telemt_me_writer_restored_same_endpoint_total 2592
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 167369
telemt_user_connections_current{user="hello"} 693
telemt_user_octets_from_client{user="hello"} 1800664772 (1.68 GB)
telemt_user_octets_to_client{user="hello"} 52937894564 (49.30 GB)
telemt_user_unique_ips_current{user="hello"} 293
telemt_user_unique_ips_recent_window{user="hello"} 63
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 18047.2 (5h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 395252
telemt_connections_bad_total 24497
telemt_connections_current 1699
telemt_connections_me_current 1699
telemt_handshake_timeouts_total 9392
telemt_upstream_connect_attempt_total 3506
telemt_upstream_connect_success_total 3444
telemt_upstream_connect_fail_total 62
telemt_upstream_connect_attempts_per_request{bucket="1"} 3506
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1612
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1824
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 62
telemt_me_reconnect_attempts_total 2541
telemt_me_reconnect_success_total 2530
telemt_me_reader_eof_total 2655
telemt_me_idle_close_by_peer_total 2655
telemt_me_seq_mismatch_total 5
telemt_me_route_drop_no_conn_total 121347
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 336346
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1228
telemt_desync_full_logged_total 420
telemt_desync_suppressed_total 808
telemt_desync_frames_bucket_total{bucket="1_2"} 280
telemt_desync_frames_bucket_total{bucket="3_10"} 470
telemt_desync_frames_bucket_total{bucket="gt_10"} 478
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 2569
telemt_me_writer_restored_same_endpoint_total 2515
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 336320
telemt_user_connections_current{user="hello"} 1699
telemt_user_octets_from_client{user="hello"} 12002574168 (11.18 GB)
telemt_user_octets_to_client{user="hello"} 130345503568 (121.39 GB)
telemt_user_unique_ips_current{user="hello"} 648
telemt_user_unique_ips_recent_window{user="hello"} 172
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 18044.6 (5h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 322534
telemt_connections_bad_total 62961
telemt_connections_current 1222
telemt_connections_me_current 1222
telemt_handshake_timeouts_total 7814
telemt_upstream_connect_attempt_total 3429
telemt_upstream_connect_success_total 3429
telemt_upstream_connect_attempts_per_request{bucket="1"} 3429
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1727
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1697
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 2523
telemt_me_reconnect_success_total 2513
telemt_me_reader_eof_total 2656
telemt_me_idle_close_by_peer_total 2656
telemt_me_route_drop_no_conn_total 95722
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 242776
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1235
telemt_desync_full_logged_total 457
telemt_desync_suppressed_total 778
telemt_desync_frames_bucket_total{bucket="1_2"} 210
telemt_desync_frames_bucket_total{bucket="3_10"} 503
telemt_desync_frames_bucket_total{bucket="gt_10"} 522
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 2553
telemt_me_writer_restored_same_endpoint_total 2497
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 40
telemt_user_connections_total{user="hello"} 242774
telemt_user_connections_current{user="hello"} 1222
telemt_user_octets_from_client{user="hello"} 4639310212 (4.32 GB)
telemt_user_octets_to_client{user="hello"} 144150669896 (134.25 GB)
telemt_user_unique_ips_current{user="hello"} 520
telemt_user_unique_ips_recent_window{user="hello"} 121
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 18097.7 (5h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 383015
telemt_connections_bad_total 35636
telemt_connections_current 1013
telemt_connections_me_current 1013
telemt_handshake_timeouts_total 5790
telemt_upstream_connect_attempt_total 3345
telemt_upstream_connect_success_total 3345
telemt_upstream_connect_attempts_per_request{bucket="1"} 3345
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1712
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1625
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 2415
telemt_me_reconnect_success_total 2404
telemt_me_reader_eof_total 2524
telemt_me_idle_close_by_peer_total 2523
telemt_me_route_drop_no_conn_total 106918
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 243575
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 627
telemt_desync_full_logged_total 231
telemt_desync_suppressed_total 396
telemt_desync_frames_bucket_total{bucket="1_2"} 123
telemt_desync_frames_bucket_total{bucket="3_10"} 265
telemt_desync_frames_bucket_total{bucket="gt_10"} 239
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 2430
telemt_me_writer_restored_same_endpoint_total 2380
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 272
telemt_me_writer_removed_unexpected_minus_restored_total 26
telemt_user_connections_total{user="hello"} 243483
telemt_user_connections_current{user="hello"} 1013
telemt_user_octets_from_client{user="hello"} 2166916592 (2.02 GB)
telemt_user_octets_to_client{user="hello"} 82423419152 (76.76 GB)
telemt_user_unique_ips_current{user="hello"} 432
telemt_user_unique_ips_recent_window{user="hello"} 112
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 18041.1 (5h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 345299
telemt_connections_bad_total 21257
telemt_connections_current 1233
telemt_connections_me_current 1233
telemt_handshake_timeouts_total 12031
telemt_upstream_connect_attempt_total 3396
telemt_upstream_connect_success_total 3378
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 3396
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1637
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1730
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_reconnect_attempts_total 2484
telemt_me_reconnect_success_total 2470
telemt_me_reader_eof_total 2604
telemt_me_idle_close_by_peer_total 2604
telemt_me_route_drop_no_conn_total 104830
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 264384
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1159
telemt_desync_full_logged_total 436
telemt_desync_suppressed_total 723
telemt_desync_frames_bucket_total{bucket="1_2"} 310
telemt_desync_frames_bucket_total{bucket="3_10"} 443
telemt_desync_frames_bucket_total{bucket="gt_10"} 406
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 2485
telemt_me_writer_restored_same_endpoint_total 2446
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 15
telemt_user_connections_total{user="hello"} 264305
telemt_user_connections_current{user="hello"} 1233
telemt_user_octets_from_client{user="hello"} 8463937304 (7.88 GB)
telemt_user_octets_to_client{user="hello"} 147578242844 (137.44 GB)
telemt_user_unique_ips_current{user="hello"} 544
telemt_user_unique_ips_recent_window{user="hello"} 129
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 18052.5 (5h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 85193
telemt_connections_bad_total 9362
telemt_connections_current 337
telemt_connections_me_current 337
telemt_handshake_timeouts_total 372
telemt_upstream_connect_attempt_total 5255
telemt_upstream_connect_success_total 5104
telemt_upstream_connect_fail_total 150
telemt_upstream_connect_attempts_per_request{bucket="1"} 5254
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2431
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2673
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 150
telemt_me_reconnect_attempts_total 6031
telemt_me_reconnect_success_total 4196
telemt_me_reader_eof_total 4385
telemt_me_idle_close_by_peer_total 4385
telemt_me_route_drop_no_conn_total 34106
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 72716
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 34
telemt_desync_full_logged_total 12
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 20
telemt_desync_frames_bucket_total{bucket="3_10"} 13
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 4256
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 4166
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 60
telemt_user_connections_total{user="hello"} 72714
telemt_user_connections_current{user="hello"} 337
telemt_user_octets_from_client{user="hello"} 1574761332 (1.47 GB)
telemt_user_octets_to_client{user="hello"} 52741571740 (49.12 GB)
telemt_user_unique_ips_current{user="hello"} 157
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 18043.5 (5h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 243885
telemt_connections_bad_total 24801
telemt_connections_current 1250
telemt_connections_me_current 1250
telemt_handshake_timeouts_total 12098
telemt_upstream_connect_attempt_total 3841
telemt_upstream_connect_success_total 3841
telemt_upstream_connect_attempts_per_request{bucket="1"} 3841
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2017
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1822
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 2938
telemt_me_reconnect_success_total 2929
telemt_me_reader_eof_total 3080
telemt_me_idle_close_by_peer_total 3080
telemt_me_route_drop_no_conn_total 71282
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 200633
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1087
telemt_desync_full_logged_total 425
telemt_desync_suppressed_total 662
telemt_desync_frames_bucket_total{bucket="1_2"} 202
telemt_desync_frames_bucket_total{bucket="3_10"} 438
telemt_desync_frames_bucket_total{bucket="gt_10"} 447
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 2962
telemt_me_writer_restored_same_endpoint_total 2914
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 200658
telemt_user_connections_current{user="hello"} 1250
telemt_user_octets_from_client{user="hello"} 2099464816 (1.96 GB)
telemt_user_octets_to_client{user="hello"} 103564642280 (96.45 GB)
telemt_user_unique_ips_current{user="hello"} 462
telemt_user_unique_ips_recent_window{user="hello"} 113
```