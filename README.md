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

# Server Metrics 2026-03-18 15:33:09 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 468.2 (0h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17663
telemt_connections_bad_total 822
telemt_handshake_timeouts_total 472
telemt_upstream_connect_attempt_total 91
telemt_upstream_connect_success_total 91
telemt_upstream_connect_attempts_per_request{bucket="1"} 91
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39
telemt_me_reconnect_attempts_total 21
telemt_me_reconnect_success_total 21
telemt_me_reader_eof_total 2
telemt_me_idle_close_by_peer_total 2
telemt_me_route_drop_no_conn_total 6907
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 14694
telemt_me_writer_pick_total{mode="p2c",result="full"} 116
telemt_me_writer_pick_total{mode="p2c",result="closed"} 293
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 63
telemt_desync_full_logged_total 18
telemt_desync_suppressed_total 45
telemt_desync_frames_bucket_total{bucket="1_2"} 16
telemt_desync_frames_bucket_total{bucket="3_10"} 21
telemt_desync_frames_bucket_total{bucket="gt_10"} 26
telemt_me_writer_removed_unexpected_total 24
telemt_me_writer_restored_same_endpoint_total 10
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 75
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 14690
telemt_user_connections_current{user="hello"} 1582
telemt_user_octets_from_client{user="hello"} 140350572 (133.85 MB)
telemt_user_octets_to_client{user="hello"} 3215396052 (2.99 GB)
telemt_user_unique_ips_current{user="hello"} 505
telemt_user_unique_ips_recent_window{user="hello"} 221
```

## psb.hosting

```
telemt 3.3.22

telemt_uptime_seconds 5296.4 (1h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 594740
telemt_connections_bad_total 32544
telemt_connections_current 3428
telemt_connections_me_current 3428
telemt_handshake_timeouts_total 11354
telemt_upstream_connect_attempt_total 924
telemt_upstream_connect_success_total 918
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 924
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 560
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 355
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_reconnect_attempts_total 630
telemt_me_reconnect_success_total 622
telemt_me_reader_eof_total 531
telemt_me_idle_close_by_peer_total 530
telemt_me_route_drop_no_conn_total 614394
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 522459
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1303
telemt_desync_full_logged_total 396
telemt_desync_suppressed_total 907
telemt_desync_frames_bucket_total{bucket="1_2"} 287
telemt_desync_frames_bucket_total{bucket="3_10"} 521
telemt_desync_frames_bucket_total{bucket="gt_10"} 495
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 548
telemt_me_writer_restored_same_endpoint_total 620
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 2874
telemt_user_connections_total{user="hello"} 521684
telemt_user_connections_current{user="hello"} 3428
telemt_user_octets_from_client{user="hello"} 4866318368 (4.53 GB)
telemt_user_octets_to_client{user="hello"} 135520796808 (126.21 GB)
telemt_user_unique_ips_current{user="hello"} 1115
telemt_user_unique_ips_recent_window{user="hello"} 508
```

## koara.io

```
telemt 3.3.22

telemt_uptime_seconds 5225.1 (1h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 383352
telemt_connections_bad_total 23488
telemt_connections_current 2995
telemt_connections_me_current 2995
telemt_handshake_timeouts_total 7111
telemt_upstream_connect_attempt_total 689
telemt_upstream_connect_success_total 685
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 689
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 362
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 322
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 400
telemt_me_reconnect_success_total 396
telemt_me_reader_eof_total 402
telemt_me_idle_close_by_peer_total 402
telemt_me_route_drop_no_conn_total 223142
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 331556
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1059
telemt_desync_full_logged_total 304
telemt_desync_suppressed_total 755
telemt_desync_frames_bucket_total{bucket="1_2"} 233
telemt_desync_frames_bucket_total{bucket="3_10"} 392
telemt_desync_frames_bucket_total{bucket="gt_10"} 434
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 409
telemt_me_writer_restored_same_endpoint_total 379
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 652
telemt_me_writer_removed_unexpected_minus_restored_total 13
telemt_user_connections_total{user="hello"} 331519
telemt_user_connections_current{user="hello"} 2995
telemt_user_octets_from_client{user="hello"} 6463199332 (6.02 GB)
telemt_user_octets_to_client{user="hello"} 123863755724 (115.36 GB)
telemt_user_unique_ips_current{user="hello"} 969
telemt_user_unique_ips_recent_window{user="hello"} 445
```

## landvps.ru

```
telemt 3.3.22

telemt_uptime_seconds 5939.2 (1h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 582602
telemt_connections_bad_total 6049
telemt_connections_current 2710
telemt_connections_me_current 2710
telemt_handshake_timeouts_total 8051
telemt_upstream_connect_attempt_total 978
telemt_upstream_connect_success_total 970
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 978
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 512
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 453
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 634
telemt_me_reconnect_success_total 626
telemt_me_reader_eof_total 601
telemt_me_idle_close_by_peer_total 600
telemt_me_route_drop_no_conn_total 1038224
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 530756
telemt_me_writer_pick_total{mode="p2c",result="full"} 30
telemt_me_writer_pick_total{mode="p2c",result="closed"} 61
telemt_me_endpoint_quarantine_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1757
telemt_desync_full_logged_total 433
telemt_desync_suppressed_total 1324
telemt_desync_frames_bucket_total{bucket="1_2"} 376
telemt_desync_frames_bucket_total{bucket="3_10"} 824
telemt_desync_frames_bucket_total{bucket="gt_10"} 557
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 608
telemt_me_writer_restored_same_endpoint_total 615
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 1000
telemt_user_connections_total{user="hello"} 530747
telemt_user_connections_current{user="hello"} 2710
telemt_user_octets_from_client{user="hello"} 3604309036 (3.36 GB)
telemt_user_octets_to_client{user="hello"} 88273144788 (82.21 GB)
telemt_user_unique_ips_current{user="hello"} 843
telemt_user_unique_ips_recent_window{user="hello"} 383
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 454.1 (0h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 36735
telemt_connections_bad_total 3827
telemt_handshake_timeouts_total 471
telemt_upstream_connect_attempt_total 131
telemt_upstream_connect_success_total 128
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 131
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 87
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 60
telemt_me_reconnect_success_total 60
telemt_me_reader_eof_total 22
telemt_me_idle_close_by_peer_total 22
telemt_me_route_drop_no_conn_total 13496
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 29414
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 40
telemt_desync_full_logged_total 25
telemt_desync_suppressed_total 15
telemt_desync_frames_bucket_total{bucket="1_2"} 14
telemt_desync_frames_bucket_total{bucket="3_10"} 6
telemt_desync_frames_bucket_total{bucket="gt_10"} 20
telemt_me_writer_removed_unexpected_total 44
telemt_me_writer_restored_same_endpoint_total 34
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 786
telemt_user_connections_total{user="hello"} 29310
telemt_user_connections_current{user="hello"} 2843
telemt_user_octets_from_client{user="hello"} 270931596 (258.38 MB)
telemt_user_octets_to_client{user="hello"} 9487734740 (8.84 GB)
telemt_user_unique_ips_current{user="hello"} 910
telemt_user_unique_ips_recent_window{user="hello"} 491
```

## hostvds.com

```
telemt 3.3.22

telemt_uptime_seconds 5389.0 (1h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 111402
telemt_connections_bad_total 5671
telemt_connections_current 908
telemt_connections_me_current 908
telemt_relay_adaptive_promotions_total 18
telemt_relay_adaptive_hard_promotions_total 18
telemt_handshake_timeouts_total 988
telemt_upstream_connect_attempt_total 5019
telemt_upstream_connect_success_total 5011
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 5018
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2880
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2101
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 22
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_reconnect_attempts_total 330355
telemt_me_reconnect_success_total 897
telemt_me_reader_eof_total 819
telemt_me_idle_close_by_peer_total 819
telemt_me_route_drop_no_conn_total 63383
telemt_me_route_drop_channel_closed_total 16
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 96002
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 9
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 193
telemt_desync_full_logged_total 78
telemt_desync_suppressed_total 115
telemt_desync_frames_bucket_total{bucket="1_2"} 34
telemt_desync_frames_bucket_total{bucket="3_10"} 82
telemt_desync_frames_bucket_total{bucket="gt_10"} 77
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 821
telemt_me_refill_failed_total 10448
telemt_me_writer_restored_same_endpoint_total 886
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 40876
telemt_user_connections_total{user="hello"} 99758
telemt_user_connections_current{user="hello"} 908
telemt_user_octets_from_client{user="hello"} 1635290333 (1.52 GB)
telemt_user_octets_to_client{user="hello"} 19559242137 (18.22 GB)
telemt_user_msgs_from_client{user="hello"} 38712
telemt_user_msgs_to_client{user="hello"} 31668
telemt_user_unique_ips_current{user="hello"} 300
telemt_user_unique_ips_recent_window{user="hello"} 135
```

## 4vps.su

```
telemt 3.3.22

telemt_uptime_seconds 4458.5 (1h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 295368
telemt_connections_bad_total 12033
telemt_connections_current 2635
telemt_connections_me_current 2635
telemt_handshake_timeouts_total 2652
telemt_upstream_connect_attempt_total 761
telemt_upstream_connect_success_total 761
telemt_upstream_connect_attempts_per_request{bucket="1"} 761
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 416
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 344
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 14805
telemt_me_reconnect_success_total 515
telemt_me_reader_eof_total 418
telemt_me_idle_close_by_peer_total 418
telemt_me_route_drop_no_conn_total 205377
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="base"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 254974
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 600
telemt_desync_full_logged_total 224
telemt_desync_suppressed_total 376
telemt_desync_frames_bucket_total{bucket="1_2"} 120
telemt_desync_frames_bucket_total{bucket="3_10"} 212
telemt_desync_frames_bucket_total{bucket="gt_10"} 268
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 427
telemt_me_refill_failed_total 703
telemt_me_writer_restored_same_endpoint_total 454
telemt_me_writer_restored_fallback_total 61
telemt_me_async_recovery_trigger_total 9552
telemt_user_connections_total{user="hello"} 255403
telemt_user_connections_current{user="hello"} 2635
telemt_user_octets_from_client{user="hello"} 3262717996 (3.04 GB)
telemt_user_octets_to_client{user="hello"} 103887431020 (96.75 GB)
telemt_user_unique_ips_current{user="hello"} 820
telemt_user_unique_ips_recent_window{user="hello"} 381
```