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

# Server Metrics 2026-03-18 09:41:06 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.20

telemt_uptime_seconds 3606.0 (1h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 149685
telemt_connections_bad_total 673
telemt_handshake_timeouts_total 2844
telemt_upstream_connect_attempt_total 63583
telemt_upstream_connect_success_total 62670
telemt_upstream_connect_fail_total 913
telemt_upstream_connect_attempts_per_request{bucket="1"} 63583
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 59238
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2850
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 582
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 913
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 506043
telemt_me_reconnect_success_total 525
telemt_me_reader_eof_total 432
telemt_me_idle_close_by_peer_total 430
telemt_me_route_drop_no_conn_total 25134
telemt_me_route_drop_channel_closed_total 20
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 65805
telemt_me_writer_pick_total{mode="p2c",result="full"} 21
telemt_me_writer_pick_total{mode="p2c",result="closed"} 54
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 339
telemt_desync_full_logged_total 97
telemt_desync_suppressed_total 242
telemt_desync_frames_bucket_total{bucket="1_2"} 107
telemt_desync_frames_bucket_total{bucket="3_10"} 112
telemt_desync_frames_bucket_total{bucket="gt_10"} 120
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 473
telemt_me_refill_failed_total 16481
telemt_me_writer_restored_same_endpoint_total 420
telemt_me_writer_restored_fallback_total 105
telemt_me_async_recovery_trigger_total 11769
telemt_user_connections_total{user="hello"} 127674
telemt_user_connections_current{user="hello"} 1436
telemt_user_octets_from_client{user="hello"} 1568028104 (1.46 GB)
telemt_user_octets_to_client{user="hello"} 27859279541 (25.95 GB)
telemt_user_msgs_from_client{user="hello"} 846607
telemt_user_msgs_to_client{user="hello"} 1165163
telemt_user_unique_ips_current{user="hello"} 469
telemt_user_unique_ips_recent_window{user="hello"} 216
```

## psb.hosting

```
telemt 3.3.20

telemt_uptime_seconds 3637.1 (1h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 329529
telemt_connections_bad_total 38051
telemt_handshake_timeouts_total 8224
telemt_upstream_connect_attempt_total 602
telemt_upstream_connect_success_total 602
telemt_upstream_connect_attempts_per_request{bucket="1"} 602
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 377
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 220
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_failed_total 1
telemt_me_reconnect_attempts_total 389
telemt_me_reconnect_success_total 379
telemt_me_reader_eof_total 341
telemt_me_idle_close_by_peer_total 341
telemt_me_route_drop_no_conn_total 102174
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 259631
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1232
telemt_desync_full_logged_total 309
telemt_desync_suppressed_total 923
telemt_desync_frames_bucket_total{bucket="1_2"} 241
telemt_desync_frames_bucket_total{bucket="3_10"} 492
telemt_desync_frames_bucket_total{bucket="gt_10"} 499
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 354
telemt_me_writer_restored_same_endpoint_total 378
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 1068
telemt_user_connections_total{user="hello"} 258893
telemt_user_connections_current{user="hello"} 4110
telemt_user_octets_from_client{user="hello"} 6966326136 (6.49 GB)
telemt_user_octets_to_client{user="hello"} 92225267564 (85.89 GB)
telemt_user_unique_ips_current{user="hello"} 1169
telemt_user_unique_ips_recent_window{user="hello"} 558
```

## koara.io

```
telemt 3.3.20

telemt_uptime_seconds 3552.2 (0h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 275418
telemt_connections_bad_total 14248
telemt_handshake_timeouts_total 6751
telemt_upstream_connect_attempt_total 8896
telemt_upstream_connect_success_total 8896
telemt_upstream_connect_attempts_per_request{bucket="1"} 8896
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7318
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1572
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 40
telemt_me_reconnect_attempts_total 606160
telemt_me_reconnect_success_total 491
telemt_me_reader_eof_total 453
telemt_me_idle_close_by_peer_total 452
telemt_me_route_drop_no_conn_total 147125
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 196323
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 455
telemt_desync_full_logged_total 159
telemt_desync_suppressed_total 296
telemt_desync_frames_bucket_total{bucket="1_2"} 90
telemt_desync_frames_bucket_total{bucket="3_10"} 208
telemt_desync_frames_bucket_total{bucket="gt_10"} 157
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 478
telemt_me_refill_failed_total 19672
telemt_me_writer_restored_same_endpoint_total 456
telemt_me_writer_restored_fallback_total 35
telemt_me_async_recovery_trigger_total 14895
telemt_user_connections_total{user="hello"} 204382
telemt_user_connections_current{user="hello"} 2699
telemt_user_octets_from_client{user="hello"} 1948460947 (1.81 GB)
telemt_user_octets_to_client{user="hello"} 62515266480 (58.22 GB)
telemt_user_msgs_from_client{user="hello"} 68547
telemt_user_msgs_to_client{user="hello"} 285346
telemt_user_unique_ips_current{user="hello"} 772
telemt_user_unique_ips_recent_window{user="hello"} 371
```

## landvps.ru

```
telemt 3.3.20

telemt_uptime_seconds 3582.0 (0h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 571589
telemt_connections_bad_total 6405
telemt_handshake_timeouts_total 61073
telemt_upstream_connect_attempt_total 11363
telemt_upstream_connect_success_total 11268
telemt_upstream_connect_fail_total 95
telemt_upstream_connect_attempts_per_request{bucket="1"} 11363
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10261
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 973
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 95
telemt_me_keepalive_timeout_total 652
telemt_me_reconnect_attempts_total 2811894
telemt_me_reconnect_success_total 785
telemt_me_reader_eof_total 793
telemt_me_idle_close_by_peer_total 793
telemt_me_route_drop_no_conn_total 1062989
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 447244
telemt_me_writer_pick_total{mode="p2c",result="success_fallback"} 8840
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_writer_pick_blocking_fallback_total 8840
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 491
telemt_desync_full_logged_total 146
telemt_desync_suppressed_total 345
telemt_desync_frames_bucket_total{bucket="1_2"} 103
telemt_desync_frames_bucket_total{bucket="3_10"} 215
telemt_desync_frames_bucket_total{bucket="gt_10"} 173
telemt_me_writer_removed_unexpected_total 816
telemt_me_refill_failed_total 99585
telemt_me_writer_restored_same_endpoint_total 690
telemt_me_writer_restored_fallback_total 95
telemt_me_async_recovery_trigger_total 365465
telemt_me_writer_removed_unexpected_minus_restored_total 31
telemt_user_connections_total{user="hello"} 466241
telemt_user_connections_current{user="hello"} 3411
telemt_user_octets_from_client{user="hello"} 2807472882 (2.61 GB)
telemt_user_octets_to_client{user="hello"} 44031869341 (41.01 GB)
telemt_user_msgs_from_client{user="hello"} 80007
telemt_user_msgs_to_client{user="hello"} 158054
telemt_user_unique_ips_current{user="hello"} 838
telemt_user_unique_ips_recent_window{user="hello"} 560
```

## rdp-onedash.ru

```
telemt 3.3.20

telemt_uptime_seconds 3476.9 (0h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 245604
telemt_connections_bad_total 8251
telemt_handshake_timeouts_total 2978
telemt_upstream_connect_attempt_total 10296
telemt_upstream_connect_success_total 10295
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 10296
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9392
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 697
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 206
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 2982537
telemt_me_reconnect_success_total 589
telemt_me_reader_eof_total 526
telemt_me_idle_close_by_peer_total 526
telemt_me_route_drop_no_conn_total 68855
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 192702
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 535
telemt_desync_full_logged_total 198
telemt_desync_suppressed_total 337
telemt_desync_frames_bucket_total{bucket="1_2"} 81
telemt_desync_frames_bucket_total{bucket="3_10"} 199
telemt_desync_frames_bucket_total{bucket="gt_10"} 255
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 537
telemt_me_refill_failed_total 107153
telemt_me_writer_restored_same_endpoint_total 474
telemt_me_writer_restored_fallback_total 115
telemt_me_async_recovery_trigger_total 267383
telemt_user_connections_total{user="hello"} 202058
telemt_user_connections_current{user="hello"} 3121
telemt_user_octets_from_client{user="hello"} 3909004881 (3.64 GB)
telemt_user_octets_to_client{user="hello"} 81723847837 (76.11 GB)
telemt_user_msgs_from_client{user="hello"} 86293
telemt_user_msgs_to_client{user="hello"} 266108
telemt_user_unique_ips_current{user="hello"} 930
telemt_user_unique_ips_recent_window{user="hello"} 433
```

## hostvds.com

```
telemt 3.3.20

telemt_uptime_seconds 3361.7 (0h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 70393
telemt_connections_bad_total 10363
telemt_handshake_timeouts_total 379
telemt_upstream_connect_attempt_total 542
telemt_upstream_connect_success_total 542
telemt_upstream_connect_attempts_per_request{bucket="1"} 542
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 304
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 238
telemt_me_reconnect_attempts_total 334
telemt_me_reconnect_success_total 332
telemt_me_reader_eof_total 315
telemt_me_idle_close_by_peer_total 315
telemt_me_route_drop_no_conn_total 23557
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 57135
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 116
telemt_desync_full_logged_total 46
telemt_desync_suppressed_total 70
telemt_desync_frames_bucket_total{bucket="1_2"} 20
telemt_desync_frames_bucket_total{bucket="3_10"} 54
telemt_desync_frames_bucket_total{bucket="gt_10"} 42
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 322
telemt_me_writer_restored_same_endpoint_total 324
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 130
telemt_user_connections_total{user="hello"} 54757
telemt_user_connections_current{user="hello"} 890
telemt_user_octets_from_client{user="hello"} 1078840344 (1.00 GB)
telemt_user_octets_to_client{user="hello"} 12919372000 (12.03 GB)
telemt_user_unique_ips_current{user="hello"} 307
telemt_user_unique_ips_recent_window{user="hello"} 142
```

## 4vps.su

```
telemt 3.3.20

telemt_uptime_seconds 3432.9 (0h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 175123
telemt_connections_bad_total 5079
telemt_handshake_timeouts_total 2605
telemt_upstream_connect_attempt_total 556
telemt_upstream_connect_success_total 539
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 556
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 306
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 226
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_reconnect_attempts_total 337
telemt_me_reconnect_success_total 328
telemt_me_reader_eof_total 297
telemt_me_idle_close_by_peer_total 297
telemt_me_route_drop_no_conn_total 117874
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 155836
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 452
telemt_desync_full_logged_total 147
telemt_desync_suppressed_total 305
telemt_desync_frames_bucket_total{bucket="1_2"} 84
telemt_desync_frames_bucket_total{bucket="3_10"} 179
telemt_desync_frames_bucket_total{bucket="gt_10"} 189
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 314
telemt_me_writer_restored_same_endpoint_total 318
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 2494
telemt_user_connections_total{user="hello"} 155712
telemt_user_connections_current{user="hello"} 2565
telemt_user_octets_from_client{user="hello"} 2306992056 (2.15 GB)
telemt_user_octets_to_client{user="hello"} 66161737212 (61.62 GB)
telemt_user_unique_ips_current{user="hello"} 715
telemt_user_unique_ips_recent_window{user="hello"} 331
```