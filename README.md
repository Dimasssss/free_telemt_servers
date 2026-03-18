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

# Server Metrics 2026-03-18 09:30:55 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.20

telemt_uptime_seconds 2993.7 (0h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 128109
telemt_connections_bad_total 325
telemt_handshake_timeouts_total 2499
telemt_upstream_connect_attempt_total 63502
telemt_upstream_connect_success_total 62589
telemt_upstream_connect_fail_total 913
telemt_upstream_connect_attempts_per_request{bucket="1"} 63502
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 59200
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2807
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 582
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 913
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 505962
telemt_me_reconnect_success_total 445
telemt_me_reader_eof_total 351
telemt_me_idle_close_by_peer_total 349
telemt_me_route_drop_no_conn_total 18623
telemt_me_route_drop_channel_closed_total 16
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 48877
telemt_me_writer_pick_total{mode="p2c",result="full"} 21
telemt_me_writer_pick_total{mode="p2c",result="closed"} 54
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 211
telemt_desync_full_logged_total 63
telemt_desync_suppressed_total 148
telemt_desync_frames_bucket_total{bucket="1_2"} 77
telemt_desync_frames_bucket_total{bucket="3_10"} 72
telemt_desync_frames_bucket_total{bucket="gt_10"} 62
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 392
telemt_me_refill_failed_total 16481
telemt_me_writer_restored_same_endpoint_total 340
telemt_me_writer_restored_fallback_total 105
telemt_me_async_recovery_trigger_total 11769
telemt_user_connections_total{user="hello"} 110757
telemt_user_connections_current{user="hello"} 1469
telemt_user_octets_from_client{user="hello"} 1405589008 (1.31 GB)
telemt_user_octets_to_client{user="hello"} 22533852169 (20.99 GB)
telemt_user_msgs_from_client{user="hello"} 846607
telemt_user_msgs_to_client{user="hello"} 1165163
telemt_user_unique_ips_current{user="hello"} 461
telemt_user_unique_ips_recent_window{user="hello"} 245
```

## psb.hosting

```
telemt 3.3.20

telemt_uptime_seconds 3024.4 (0h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 278889
telemt_connections_bad_total 35122
telemt_handshake_timeouts_total 6585
telemt_upstream_connect_attempt_total 562
telemt_upstream_connect_success_total 562
telemt_upstream_connect_attempts_per_request{bucket="1"} 562
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 353
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 204
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_failed_total 1
telemt_me_reconnect_attempts_total 360
telemt_me_reconnect_success_total 350
telemt_me_reader_eof_total 310
telemt_me_idle_close_by_peer_total 310
telemt_me_route_drop_no_conn_total 87254
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 215476
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1062
telemt_desync_full_logged_total 258
telemt_desync_suppressed_total 804
telemt_desync_frames_bucket_total{bucket="1_2"} 211
telemt_desync_frames_bucket_total{bucket="3_10"} 425
telemt_desync_frames_bucket_total{bucket="gt_10"} 426
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 323
telemt_me_writer_restored_same_endpoint_total 349
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 1068
telemt_user_connections_total{user="hello"} 214757
telemt_user_connections_current{user="hello"} 3863
telemt_user_octets_from_client{user="hello"} 6413408700 (5.97 GB)
telemt_user_octets_to_client{user="hello"} 73827482080 (68.76 GB)
telemt_user_unique_ips_current{user="hello"} 1107
telemt_user_unique_ips_recent_window{user="hello"} 547
```

## koara.io

```
telemt 3.3.20

telemt_uptime_seconds 2939.4 (0h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 238578
telemt_connections_bad_total 12282
telemt_handshake_timeouts_total 5420
telemt_upstream_connect_attempt_total 8843
telemt_upstream_connect_success_total 8843
telemt_upstream_connect_attempts_per_request{bucket="1"} 8843
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7297
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1540
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 40
telemt_me_reconnect_attempts_total 606107
telemt_me_reconnect_success_total 439
telemt_me_reader_eof_total 400
telemt_me_idle_close_by_peer_total 399
telemt_me_route_drop_no_conn_total 137875
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 167488
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 392
telemt_desync_full_logged_total 131
telemt_desync_suppressed_total 261
telemt_desync_frames_bucket_total{bucket="1_2"} 79
telemt_desync_frames_bucket_total{bucket="3_10"} 180
telemt_desync_frames_bucket_total{bucket="gt_10"} 133
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 425
telemt_me_refill_failed_total 19672
telemt_me_writer_restored_same_endpoint_total 404
telemt_me_writer_restored_fallback_total 35
telemt_me_async_recovery_trigger_total 14895
telemt_user_connections_total{user="hello"} 175561
telemt_user_connections_current{user="hello"} 2596
telemt_user_octets_from_client{user="hello"} 1455939815 (1.36 GB)
telemt_user_octets_to_client{user="hello"} 46341890804 (43.16 GB)
telemt_user_msgs_from_client{user="hello"} 68547
telemt_user_msgs_to_client{user="hello"} 285346
telemt_user_unique_ips_current{user="hello"} 722
telemt_user_unique_ips_recent_window{user="hello"} 339
```

## landvps.ru

```
telemt 3.3.20

telemt_uptime_seconds 2972.8 (0h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 356922
telemt_connections_bad_total 5820
telemt_handshake_timeouts_total 43667
telemt_upstream_connect_attempt_total 11303
telemt_upstream_connect_success_total 11208
telemt_upstream_connect_fail_total 95
telemt_upstream_connect_attempts_per_request{bucket="1"} 11303
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10224
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 952
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 95
telemt_me_keepalive_timeout_total 126
telemt_me_reconnect_attempts_total 2811834
telemt_me_reconnect_success_total 725
telemt_me_reader_eof_total 731
telemt_me_idle_close_by_peer_total 731
telemt_me_route_drop_no_conn_total 203298
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 268206
telemt_me_writer_pick_total{mode="p2c",result="success_fallback"} 2495
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_writer_pick_blocking_fallback_total 2495
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 395
telemt_desync_full_logged_total 124
telemt_desync_suppressed_total 271
telemt_desync_frames_bucket_total{bucket="1_2"} 93
telemt_desync_frames_bucket_total{bucket="3_10"} 161
telemt_desync_frames_bucket_total{bucket="gt_10"} 141
telemt_me_writer_removed_unexpected_total 754
telemt_me_refill_failed_total 99585
telemt_me_writer_restored_same_endpoint_total 630
telemt_me_writer_restored_fallback_total 95
telemt_me_async_recovery_trigger_total 365465
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 280866
telemt_user_connections_current{user="hello"} 4478
telemt_user_octets_from_client{user="hello"} 2195226542 (2.04 GB)
telemt_user_octets_to_client{user="hello"} 43356982473 (40.38 GB)
telemt_user_msgs_from_client{user="hello"} 80007
telemt_user_msgs_to_client{user="hello"} 158054
telemt_user_unique_ips_current{user="hello"} 923
telemt_user_unique_ips_recent_window{user="hello"} 711
```

## rdp-onedash.ru

```
telemt 3.3.20

telemt_uptime_seconds 2864.5 (0h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 197802
telemt_connections_bad_total 7098
telemt_handshake_timeouts_total 2231
telemt_upstream_connect_attempt_total 10252
telemt_upstream_connect_success_total 10251
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 10252
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9377
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 668
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 206
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 2982493
telemt_me_reconnect_success_total 545
telemt_me_reader_eof_total 480
telemt_me_idle_close_by_peer_total 480
telemt_me_route_drop_no_conn_total 56265
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 156917
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 415
telemt_desync_full_logged_total 160
telemt_desync_suppressed_total 255
telemt_desync_frames_bucket_total{bucket="1_2"} 60
telemt_desync_frames_bucket_total{bucket="3_10"} 151
telemt_desync_frames_bucket_total{bucket="gt_10"} 204
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 491
telemt_me_refill_failed_total 107153
telemt_me_writer_restored_same_endpoint_total 430
telemt_me_writer_restored_fallback_total 115
telemt_me_async_recovery_trigger_total 267383
telemt_user_connections_total{user="hello"} 166292
telemt_user_connections_current{user="hello"} 3049
telemt_user_octets_from_client{user="hello"} 3245982021 (3.02 GB)
telemt_user_octets_to_client{user="hello"} 66575884853 (62.00 GB)
telemt_user_msgs_from_client{user="hello"} 86293
telemt_user_msgs_to_client{user="hello"} 266108
telemt_user_unique_ips_current{user="hello"} 895
telemt_user_unique_ips_recent_window{user="hello"} 415
```

## hostvds.com

```
telemt 3.3.20

telemt_uptime_seconds 2749.6 (0h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 59271
telemt_connections_bad_total 9498
telemt_handshake_timeouts_total 321
telemt_upstream_connect_attempt_total 444
telemt_upstream_connect_success_total 444
telemt_upstream_connect_attempts_per_request{bucket="1"} 444
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 262
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 182
telemt_me_reconnect_attempts_total 264
telemt_me_reconnect_success_total 261
telemt_me_reader_eof_total 236
telemt_me_idle_close_by_peer_total 236
telemt_me_route_drop_no_conn_total 19467
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 47429
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 78
telemt_desync_full_logged_total 35
telemt_desync_suppressed_total 43
telemt_desync_frames_bucket_total{bucket="1_2"} 11
telemt_desync_frames_bucket_total{bucket="3_10"} 40
telemt_desync_frames_bucket_total{bucket="gt_10"} 27
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 250
telemt_me_writer_restored_same_endpoint_total 253
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 130
telemt_user_connections_total{user="hello"} 45056
telemt_user_connections_current{user="hello"} 828
telemt_user_octets_from_client{user="hello"} 962699176 (918.10 MB)
telemt_user_octets_to_client{user="hello"} 11197146020 (10.43 GB)
telemt_user_unique_ips_current{user="hello"} 317
telemt_user_unique_ips_recent_window{user="hello"} 129
```

## 4vps.su

```
telemt 3.3.20

telemt_uptime_seconds 2820.5 (0h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 142352
telemt_connections_bad_total 2408
telemt_handshake_timeouts_total 2186
telemt_upstream_connect_attempt_total 466
telemt_upstream_connect_success_total 450
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 465
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 265
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 178
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_reconnect_attempts_total 255
telemt_me_reconnect_success_total 246
telemt_me_reader_eof_total 210
telemt_me_idle_close_by_peer_total 210
telemt_me_route_drop_no_conn_total 109283
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 128459
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 350
telemt_desync_full_logged_total 114
telemt_desync_suppressed_total 236
telemt_desync_frames_bucket_total{bucket="1_2"} 61
telemt_desync_frames_bucket_total{bucket="3_10"} 141
telemt_desync_frames_bucket_total{bucket="gt_10"} 148
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 232
telemt_me_writer_restored_same_endpoint_total 236
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 2494
telemt_user_connections_total{user="hello"} 128363
telemt_user_connections_current{user="hello"} 2393
telemt_user_octets_from_client{user="hello"} 1670238996 (1.56 GB)
telemt_user_octets_to_client{user="hello"} 51729125204 (48.18 GB)
telemt_user_unique_ips_current{user="hello"} 659
telemt_user_unique_ips_recent_window{user="hello"} 312
```