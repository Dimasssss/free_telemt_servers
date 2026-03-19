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

# Server Metrics 2026-03-19 14:04:20 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 40.0 (0h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3582
telemt_connections_current 100
telemt_connections_direct_current 100
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 480
telemt_upstream_connect_attempt_total 307
telemt_upstream_connect_success_total 307
telemt_upstream_connect_attempts_per_request{bucket="1"} 307
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 290
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 305
telemt_user_connections_current{user="hello"} 100
telemt_user_octets_from_client{user="hello"} 8002633 (7.63 MB)
telemt_user_octets_to_client{user="hello"} 27699588 (26.42 MB)
telemt_user_msgs_from_client{user="hello"} 3841
telemt_user_msgs_to_client{user="hello"} 3383
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 4860.8 (1h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 519006
telemt_connections_bad_total 16299
telemt_connections_current 3705
telemt_connections_me_current 3705
telemt_handshake_timeouts_total 8772
telemt_upstream_connect_attempt_total 2308
telemt_upstream_connect_success_total 2294
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 2308
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1792
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 492
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_reconnect_attempts_total 4975
telemt_me_reconnect_success_total 775
telemt_me_reader_eof_total 858
telemt_me_idle_close_by_peer_total 858
telemt_me_route_drop_no_conn_total 451403
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 462435
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1470
telemt_desync_full_logged_total 478
telemt_desync_suppressed_total 992
telemt_desync_frames_bucket_total{bucket="1_2"} 270
telemt_desync_frames_bucket_total{bucket="3_10"} 553
telemt_desync_frames_bucket_total{bucket="gt_10"} 647
telemt_me_writer_close_signal_drop_total 26
telemt_me_writer_removed_unexpected_total 888
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 720
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 113
telemt_user_connections_total{user="hello"} 463273
telemt_user_connections_current{user="hello"} 3705
telemt_user_octets_from_client{user="hello"} 6379690138 (5.94 GB)
telemt_user_octets_to_client{user="hello"} 115990308050 (108.02 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1325
telemt_user_unique_ips_recent_window{user="hello"} 709
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 4838.2 (1h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 569525
telemt_connections_bad_total 53701
telemt_connections_current 3044
telemt_connections_me_current 3044
telemt_handshake_timeouts_total 5713
telemt_upstream_connect_attempt_total 799
telemt_upstream_connect_success_total 790
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 799
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 474
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 316
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_reconnect_attempts_total 1397
telemt_me_reconnect_success_total 497
telemt_me_reader_eof_total 438
telemt_me_idle_close_by_peer_total 437
telemt_me_route_drop_no_conn_total 570108
telemt_me_route_drop_channel_closed_total 28
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 429154
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1521
telemt_desync_full_logged_total 389
telemt_desync_suppressed_total 1132
telemt_desync_frames_bucket_total{bucket="1_2"} 411
telemt_desync_frames_bucket_total{bucket="3_10"} 576
telemt_desync_frames_bucket_total{bucket="gt_10"} 534
telemt_pool_swap_total 3
telemt_me_writer_close_signal_drop_total 28
telemt_me_writer_removed_unexpected_total 452
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 496
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_user_connections_total{user="hello"} 426897
telemt_user_connections_current{user="hello"} 3044
telemt_user_octets_from_client{user="hello"} 3846259480 (3.58 GB)
telemt_user_octets_to_client{user="hello"} 103606305968 (96.49 GB)
telemt_user_unique_ips_current{user="hello"} 1110
telemt_user_unique_ips_recent_window{user="hello"} 603
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 4826.4 (1h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 422385
telemt_connections_bad_total 38579
telemt_connections_current 3186
telemt_connections_me_current 3186
telemt_handshake_timeouts_total 6797
telemt_upstream_connect_attempt_total 4334
telemt_upstream_connect_success_total 4165
telemt_upstream_connect_fail_total 169
telemt_upstream_connect_attempts_per_request{bucket="1"} 4334
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3627
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 488
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 169
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 579
telemt_me_reconnect_success_total 546
telemt_me_reader_eof_total 524
telemt_me_idle_close_by_peer_total 523
telemt_me_route_drop_no_conn_total 274679
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 341244
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1482
telemt_desync_full_logged_total 483
telemt_desync_suppressed_total 999
telemt_desync_frames_bucket_total{bucket="1_2"} 284
telemt_desync_frames_bucket_total{bucket="3_10"} 558
telemt_desync_frames_bucket_total{bucket="gt_10"} 640
telemt_pool_swap_total 2
telemt_me_writer_close_signal_drop_total 25
telemt_me_writer_removed_unexpected_total 548
telemt_me_writer_restored_same_endpoint_total 543
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 344169
telemt_user_connections_current{user="hello"} 3186
telemt_user_octets_from_client{user="hello"} 5723870531 (5.33 GB)
telemt_user_octets_to_client{user="hello"} 78977254682 (73.55 GB)
telemt_user_msgs_from_client{user="hello"} 5613
telemt_user_msgs_to_client{user="hello"} 6373
telemt_user_unique_ips_current{user="hello"} 1013
telemt_user_unique_ips_recent_window{user="hello"} 536
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 58549.3 (16h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4021343
telemt_connections_bad_total 764037
telemt_connections_current 3707
telemt_connections_me_current 3707
telemt_relay_adaptive_promotions_total 22
telemt_relay_adaptive_demotions_total 1819
telemt_relay_adaptive_hard_promotions_total 20
telemt_handshake_timeouts_total 78869
telemt_upstream_connect_attempt_total 62240
telemt_upstream_connect_success_total 59757
telemt_upstream_connect_fail_total 2483
telemt_upstream_connect_attempts_per_request{bucket="1"} 62240
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 51561
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7180
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1016
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2483
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 70707
telemt_me_reconnect_success_total 7647
telemt_me_reader_eof_total 7987
telemt_me_idle_close_by_peer_total 7984
telemt_me_route_drop_no_conn_total 1918352
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2746015
telemt_me_writer_pick_total{mode="p2c",result="full"} 8278
telemt_me_writer_pick_total{mode="p2c",result="closed"} 806
telemt_me_writer_pick_blocking_fallback_total 9050
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11856
telemt_desync_full_logged_total 3661
telemt_desync_suppressed_total 8195
telemt_desync_frames_bucket_total{bucket="1_2"} 2049
telemt_desync_frames_bucket_total{bucket="3_10"} 5105
telemt_desync_frames_bucket_total{bucket="gt_10"} 4702
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 7782
telemt_me_refill_failed_total 1967
telemt_me_writer_restored_same_endpoint_total 7623
telemt_me_writer_restored_fallback_total 24
telemt_me_no_writer_failfast_total 1478
telemt_me_async_recovery_trigger_total 7229
telemt_me_writer_removed_unexpected_minus_restored_total 135
telemt_user_connections_total{user="hello"} 2794721
telemt_user_connections_current{user="hello"} 3707
telemt_user_octets_from_client{user="hello"} 44979113551 (41.89 GB)
telemt_user_octets_to_client{user="hello"} 997920233952 (929.39 GB)
telemt_user_msgs_from_client{user="hello"} 549175
telemt_user_msgs_to_client{user="hello"} 1884577
telemt_user_unique_ips_current{user="hello"} 1179
telemt_user_unique_ips_recent_window{user="hello"} 612
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 4791.9 (1h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 117647
telemt_connections_bad_total 5383
telemt_connections_current 941
telemt_connections_me_current 941
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 4827
telemt_upstream_connect_attempt_total 3494
telemt_upstream_connect_success_total 3357
telemt_upstream_connect_fail_total 137
telemt_upstream_connect_attempts_per_request{bucket="1"} 3494
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1178
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2024
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 149
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 137
telemt_me_reconnect_attempts_total 553
telemt_me_reconnect_success_total 530
telemt_me_reader_eof_total 491
telemt_me_idle_close_by_peer_total 491
telemt_me_route_drop_no_conn_total 89938
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 99990
telemt_me_writer_pick_total{mode="p2c",result="success_fallback"} 464
telemt_me_writer_pick_total{mode="p2c",result="full"} 2833
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_writer_pick_blocking_fallback_total 3285
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 212
telemt_desync_full_logged_total 76
telemt_desync_suppressed_total 136
telemt_desync_frames_bucket_total{bucket="1_2"} 34
telemt_desync_frames_bucket_total{bucket="3_10"} 92
telemt_desync_frames_bucket_total{bucket="gt_10"} 86
telemt_pool_swap_total 4
telemt_me_writer_close_signal_drop_total 36
telemt_me_writer_removed_unexpected_total 492
telemt_me_writer_restored_same_endpoint_total 521
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 179
telemt_me_async_recovery_trigger_total 1239
telemt_user_connections_total{user="hello"} 102628
telemt_user_connections_current{user="hello"} 941
telemt_user_octets_from_client{user="hello"} 1420107748 (1.32 GB)
telemt_user_octets_to_client{user="hello"} 23881421338 (22.24 GB)
telemt_user_msgs_from_client{user="hello"} 7378
telemt_user_msgs_to_client{user="hello"} 12667
telemt_user_unique_ips_current{user="hello"} 334
telemt_user_unique_ips_recent_window{user="hello"} 162
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 4790.6 (1h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 332538
telemt_connections_bad_total 27193
telemt_connections_current 3042
telemt_connections_me_current 3042
telemt_handshake_timeouts_total 5937
telemt_upstream_connect_attempt_total 776
telemt_upstream_connect_success_total 770
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 775
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 418
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 352
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_reconnect_attempts_total 484
telemt_me_reconnect_success_total 475
telemt_me_reader_eof_total 484
telemt_me_idle_close_by_peer_total 484
telemt_me_route_drop_no_conn_total 105741
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 288654
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1417
telemt_desync_full_logged_total 426
telemt_desync_suppressed_total 991
telemt_desync_frames_bucket_total{bucket="1_2"} 231
telemt_desync_frames_bucket_total{bucket="3_10"} 478
telemt_desync_frames_bucket_total{bucket="gt_10"} 708
telemt_pool_swap_total 3
telemt_me_writer_close_signal_drop_total 23
telemt_me_writer_removed_unexpected_total 489
telemt_me_writer_restored_same_endpoint_total 458
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 288557
telemt_user_connections_current{user="hello"} 3042
telemt_user_octets_from_client{user="hello"} 3373954180 (3.14 GB)
telemt_user_octets_to_client{user="hello"} 119862634476 (111.63 GB)
telemt_user_unique_ips_current{user="hello"} 1068
telemt_user_unique_ips_recent_window{user="hello"} 530
```