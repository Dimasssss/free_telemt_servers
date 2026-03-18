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

# Server Metrics 2026-03-18 09:51:17 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.20

telemt_uptime_seconds 4216.9 (1h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 166431
telemt_connections_bad_total 828
telemt_handshake_timeouts_total 3028
telemt_upstream_connect_attempt_total 63788
telemt_upstream_connect_success_total 62873
telemt_upstream_connect_fail_total 915
telemt_upstream_connect_attempts_per_request{bucket="1"} 63788
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 59348
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2943
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 582
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 915
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 506202
telemt_me_reconnect_success_total 684
telemt_me_reader_eof_total 591
telemt_me_idle_close_by_peer_total 589
telemt_me_route_drop_no_conn_total 30464
telemt_me_route_drop_channel_closed_total 24
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 81473
telemt_me_writer_pick_total{mode="p2c",result="full"} 21
telemt_me_writer_pick_total{mode="p2c",result="closed"} 54
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 438
telemt_desync_full_logged_total 129
telemt_desync_suppressed_total 309
telemt_desync_frames_bucket_total{bucket="1_2"} 133
telemt_desync_frames_bucket_total{bucket="3_10"} 149
telemt_desync_frames_bucket_total{bucket="gt_10"} 156
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 632
telemt_me_refill_failed_total 16481
telemt_me_writer_restored_same_endpoint_total 579
telemt_me_writer_restored_fallback_total 105
telemt_me_async_recovery_trigger_total 11769
telemt_user_connections_total{user="hello"} 143335
telemt_user_connections_current{user="hello"} 1466
telemt_user_octets_from_client{user="hello"} 1713493856 (1.60 GB)
telemt_user_octets_to_client{user="hello"} 32039255685 (29.84 GB)
telemt_user_msgs_from_client{user="hello"} 846607
telemt_user_msgs_to_client{user="hello"} 1165163
telemt_user_unique_ips_current{user="hello"} 470
telemt_user_unique_ips_recent_window{user="hello"} 218
```

## psb.hosting

```
telemt 3.3.20

telemt_uptime_seconds 4248.3 (1h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 373583
telemt_connections_bad_total 39621
telemt_handshake_timeouts_total 9412
telemt_upstream_connect_attempt_total 710
telemt_upstream_connect_success_total 710
telemt_upstream_connect_attempts_per_request{bucket="1"} 710
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 431
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 273
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_failed_total 1
telemt_me_reconnect_attempts_total 465
telemt_me_reconnect_success_total 454
telemt_me_reader_eof_total 421
telemt_me_idle_close_by_peer_total 421
telemt_me_route_drop_no_conn_total 121196
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 299815
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1432
telemt_desync_full_logged_total 370
telemt_desync_suppressed_total 1062
telemt_desync_frames_bucket_total{bucket="1_2"} 272
telemt_desync_frames_bucket_total{bucket="3_10"} 572
telemt_desync_frames_bucket_total{bucket="gt_10"} 588
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 430
telemt_me_writer_restored_same_endpoint_total 453
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 1068
telemt_user_connections_total{user="hello"} 299070
telemt_user_connections_current{user="hello"} 3788
telemt_user_octets_from_client{user="hello"} 7631898744 (7.11 GB)
telemt_user_octets_to_client{user="hello"} 109174920232 (101.68 GB)
telemt_user_unique_ips_current{user="hello"} 1124
telemt_user_unique_ips_recent_window{user="hello"} 561
```

## koara.io

```
telemt 3.3.20

telemt_uptime_seconds 4163.4 (1h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 308324
telemt_connections_bad_total 16305
telemt_handshake_timeouts_total 7781
telemt_upstream_connect_attempt_total 9047
telemt_upstream_connect_success_total 9047
telemt_upstream_connect_attempts_per_request{bucket="1"} 9047
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7401
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1638
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 40
telemt_me_reconnect_attempts_total 606266
telemt_me_reconnect_success_total 595
telemt_me_reader_eof_total 560
telemt_me_idle_close_by_peer_total 559
telemt_me_route_drop_no_conn_total 157516
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 224035
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 550
telemt_desync_full_logged_total 187
telemt_desync_suppressed_total 363
telemt_desync_frames_bucket_total{bucket="1_2"} 130
telemt_desync_frames_bucket_total{bucket="3_10"} 238
telemt_desync_frames_bucket_total{bucket="gt_10"} 182
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 585
telemt_me_refill_failed_total 19672
telemt_me_writer_restored_same_endpoint_total 560
telemt_me_writer_restored_fallback_total 35
telemt_me_async_recovery_trigger_total 14895
telemt_user_connections_total{user="hello"} 232080
telemt_user_connections_current{user="hello"} 2670
telemt_user_octets_from_client{user="hello"} 2295500371 (2.14 GB)
telemt_user_octets_to_client{user="hello"} 78931084492 (73.51 GB)
telemt_user_msgs_from_client{user="hello"} 68547
telemt_user_msgs_to_client{user="hello"} 285346
telemt_user_unique_ips_current{user="hello"} 786
telemt_user_unique_ips_recent_window{user="hello"} 387
```

## landvps.ru

```
telemt 3.3.20

telemt_uptime_seconds 4193.4 (1h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 634952
telemt_connections_bad_total 7171
telemt_handshake_timeouts_total 67803
telemt_upstream_connect_attempt_total 11473
telemt_upstream_connect_success_total 11372
telemt_upstream_connect_fail_total 101
telemt_upstream_connect_attempts_per_request{bucket="1"} 11473
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10327
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1010
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 101
telemt_me_keepalive_timeout_total 699
telemt_me_reconnect_attempts_total 2813200
telemt_me_reconnect_success_total 843
telemt_me_reader_eof_total 891
telemt_me_idle_close_by_peer_total 891
telemt_me_route_drop_no_conn_total 1299626
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 497617
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
telemt_desync_total 594
telemt_desync_full_logged_total 173
telemt_desync_suppressed_total 421
telemt_desync_frames_bucket_total{bucket="1_2"} 131
telemt_desync_frames_bucket_total{bucket="3_10"} 259
telemt_desync_frames_bucket_total{bucket="gt_10"} 204
telemt_me_writer_removed_unexpected_total 915
telemt_me_refill_failed_total 99624
telemt_me_writer_restored_same_endpoint_total 748
telemt_me_writer_restored_fallback_total 95
telemt_me_async_recovery_trigger_total 365465
telemt_me_writer_removed_unexpected_minus_restored_total 72
telemt_user_connections_total{user="hello"} 516603
telemt_user_connections_current{user="hello"} 2893
telemt_user_octets_from_client{user="hello"} 3278303382 (3.05 GB)
telemt_user_octets_to_client{user="hello"} 53033151701 (49.39 GB)
telemt_user_msgs_from_client{user="hello"} 80007
telemt_user_msgs_to_client{user="hello"} 158054
telemt_user_unique_ips_current{user="hello"} 816
telemt_user_unique_ips_recent_window{user="hello"} 394
```

## rdp-onedash.ru

```
telemt 3.3.20

telemt_uptime_seconds 4088.1 (1h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 290387
telemt_connections_bad_total 9424
telemt_handshake_timeouts_total 3927
telemt_upstream_connect_attempt_total 10393
telemt_upstream_connect_success_total 10392
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 10393
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9437
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 748
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 207
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 37
telemt_me_reconnect_attempts_total 2982591
telemt_me_reconnect_success_total 643
telemt_me_reader_eof_total 585
telemt_me_idle_close_by_peer_total 585
telemt_me_route_drop_no_conn_total 101402
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 231675
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 692
telemt_desync_full_logged_total 249
telemt_desync_suppressed_total 443
telemt_desync_frames_bucket_total{bucket="1_2"} 107
telemt_desync_frames_bucket_total{bucket="3_10"} 268
telemt_desync_frames_bucket_total{bucket="gt_10"} 317
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 592
telemt_me_refill_failed_total 107153
telemt_me_writer_restored_same_endpoint_total 528
telemt_me_writer_restored_fallback_total 115
telemt_me_async_recovery_trigger_total 267383
telemt_user_connections_total{user="hello"} 241032
telemt_user_connections_current{user="hello"} 3362
telemt_user_octets_from_client{user="hello"} 4499422149 (4.19 GB)
telemt_user_octets_to_client{user="hello"} 95024246829 (88.50 GB)
telemt_user_msgs_from_client{user="hello"} 86293
telemt_user_msgs_to_client{user="hello"} 266108
telemt_user_unique_ips_current{user="hello"} 973
telemt_user_unique_ips_recent_window{user="hello"} 468
```

## hostvds.com

```
telemt 3.3.20

telemt_uptime_seconds 3973.1 (1h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 80349
telemt_connections_bad_total 10688
telemt_handshake_timeouts_total 409
telemt_upstream_connect_attempt_total 687
telemt_upstream_connect_success_total 687
telemt_upstream_connect_attempts_per_request{bucket="1"} 687
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 377
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 310
telemt_me_reconnect_attempts_total 434
telemt_me_reconnect_success_total 432
telemt_me_reader_eof_total 417
telemt_me_idle_close_by_peer_total 417
telemt_me_route_drop_no_conn_total 27792
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 66377
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 133
telemt_desync_full_logged_total 53
telemt_desync_suppressed_total 80
telemt_desync_frames_bucket_total{bucket="1_2"} 23
telemt_desync_frames_bucket_total{bucket="3_10"} 59
telemt_desync_frames_bucket_total{bucket="gt_10"} 51
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 424
telemt_me_writer_restored_same_endpoint_total 424
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 130
telemt_user_connections_total{user="hello"} 63994
telemt_user_connections_current{user="hello"} 929
telemt_user_octets_from_client{user="hello"} 1252818784 (1.17 GB)
telemt_user_octets_to_client{user="hello"} 14987698396 (13.96 GB)
telemt_user_unique_ips_current{user="hello"} 312
telemt_user_unique_ips_recent_window{user="hello"} 125
```

## 4vps.su

```
telemt 3.3.20

telemt_uptime_seconds 4044.3 (1h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 204387
telemt_connections_bad_total 5522
telemt_handshake_timeouts_total 3117
telemt_upstream_connect_attempt_total 698
telemt_upstream_connect_success_total 681
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 698
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 392
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 282
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_reconnect_attempts_total 435
telemt_me_reconnect_success_total 425
telemt_me_reader_eof_total 397
telemt_me_idle_close_by_peer_total 397
telemt_me_route_drop_no_conn_total 127076
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 181098
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 537
telemt_desync_full_logged_total 182
telemt_desync_suppressed_total 355
telemt_desync_frames_bucket_total{bucket="1_2"} 102
telemt_desync_frames_bucket_total{bucket="3_10"} 211
telemt_desync_frames_bucket_total{bucket="gt_10"} 224
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 414
telemt_me_writer_restored_same_endpoint_total 415
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 2494
telemt_user_connections_total{user="hello"} 180974
telemt_user_connections_current{user="hello"} 2477
telemt_user_octets_from_client{user="hello"} 2749378732 (2.56 GB)
telemt_user_octets_to_client{user="hello"} 81897506172 (76.27 GB)
telemt_user_unique_ips_current{user="hello"} 703
telemt_user_unique_ips_recent_window{user="hello"} 344
```