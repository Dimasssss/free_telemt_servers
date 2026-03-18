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

# Server Metrics 2026-03-18 15:38:27 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 784.4 (0h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 27507
telemt_connections_bad_total 1456
telemt_handshake_timeouts_total 770
telemt_upstream_connect_attempt_total 91
telemt_upstream_connect_success_total 91
telemt_upstream_connect_attempts_per_request{bucket="1"} 91
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39
telemt_me_reconnect_attempts_total 21
telemt_me_reconnect_success_total 21
telemt_me_reader_eof_total 2
telemt_me_idle_close_by_peer_total 2
telemt_me_route_drop_no_conn_total 10398
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 23071
telemt_me_writer_pick_total{mode="p2c",result="full"} 116
telemt_me_writer_pick_total{mode="p2c",result="closed"} 293
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 112
telemt_desync_full_logged_total 31
telemt_desync_suppressed_total 81
telemt_desync_frames_bucket_total{bucket="1_2"} 28
telemt_desync_frames_bucket_total{bucket="3_10"} 35
telemt_desync_frames_bucket_total{bucket="gt_10"} 49
telemt_me_writer_removed_unexpected_total 24
telemt_me_writer_restored_same_endpoint_total 10
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 75
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 23061
telemt_user_connections_current{user="hello"} 1543
telemt_user_octets_from_client{user="hello"} 251525660 (239.87 MB)
telemt_user_octets_to_client{user="hello"} 5285220200 (4.92 GB)
telemt_user_unique_ips_current{user="hello"} 509
telemt_user_unique_ips_recent_window{user="hello"} 208
```

## psb.hosting

```
telemt 3.3.22

telemt_uptime_seconds 5612.5 (1h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 619010
telemt_connections_bad_total 33999
telemt_connections_current 3452
telemt_connections_me_current 3452
telemt_handshake_timeouts_total 11764
telemt_upstream_connect_attempt_total 1022
telemt_upstream_connect_success_total 1016
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 1022
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 617
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 396
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_reconnect_attempts_total 685
telemt_me_reconnect_success_total 677
telemt_me_reader_eof_total 599
telemt_me_idle_close_by_peer_total 598
telemt_me_route_drop_no_conn_total 628730
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 543502
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1389
telemt_desync_full_logged_total 420
telemt_desync_suppressed_total 969
telemt_desync_frames_bucket_total{bucket="1_2"} 305
telemt_desync_frames_bucket_total{bucket="3_10"} 554
telemt_desync_frames_bucket_total{bucket="gt_10"} 530
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 603
telemt_me_writer_restored_same_endpoint_total 675
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 2874
telemt_user_connections_total{user="hello"} 542723
telemt_user_connections_current{user="hello"} 3452
telemt_user_octets_from_client{user="hello"} 5100660412 (4.75 GB)
telemt_user_octets_to_client{user="hello"} 144224549920 (134.32 GB)
telemt_user_unique_ips_current{user="hello"} 1122
telemt_user_unique_ips_recent_window{user="hello"} 470
```

## koara.io

```
telemt 3.3.22

telemt_uptime_seconds 5541.1 (1h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 404914
telemt_connections_bad_total 24548
telemt_connections_current 3114
telemt_connections_me_current 3114
telemt_handshake_timeouts_total 7531
telemt_upstream_connect_attempt_total 764
telemt_upstream_connect_success_total 759
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 764
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 404
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 354
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_reconnect_attempts_total 431
telemt_me_reconnect_success_total 427
telemt_me_reader_eof_total 433
telemt_me_idle_close_by_peer_total 433
telemt_me_route_drop_no_conn_total 232019
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 349759
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1112
telemt_desync_full_logged_total 318
telemt_desync_suppressed_total 794
telemt_desync_frames_bucket_total{bucket="1_2"} 243
telemt_desync_frames_bucket_total{bucket="3_10"} 415
telemt_desync_frames_bucket_total{bucket="gt_10"} 454
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 440
telemt_me_writer_restored_same_endpoint_total 410
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 652
telemt_me_writer_removed_unexpected_minus_restored_total 13
telemt_user_connections_total{user="hello"} 349715
telemt_user_connections_current{user="hello"} 3114
telemt_user_octets_from_client{user="hello"} 6906919132 (6.43 GB)
telemt_user_octets_to_client{user="hello"} 131200506384 (122.19 GB)
telemt_user_unique_ips_current{user="hello"} 972
telemt_user_unique_ips_recent_window{user="hello"} 448
```

## landvps.ru

```
telemt 3.3.22

telemt_uptime_seconds 6255.5 (1h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 601054
telemt_connections_bad_total 6264
telemt_connections_current 2518
telemt_connections_me_current 2518
telemt_handshake_timeouts_total 8189
telemt_upstream_connect_attempt_total 1007
telemt_upstream_connect_success_total 999
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 1007
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 529
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 465
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 663
telemt_me_reconnect_success_total 655
telemt_me_reader_eof_total 631
telemt_me_idle_close_by_peer_total 630
telemt_me_route_drop_no_conn_total 1055083
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 547622
telemt_me_writer_pick_total{mode="p2c",result="full"} 30
telemt_me_writer_pick_total{mode="p2c",result="closed"} 61
telemt_me_endpoint_quarantine_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1940
telemt_desync_full_logged_total 472
telemt_desync_suppressed_total 1468
telemt_desync_frames_bucket_total{bucket="1_2"} 418
telemt_desync_frames_bucket_total{bucket="3_10"} 901
telemt_desync_frames_bucket_total{bucket="gt_10"} 621
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 638
telemt_me_writer_restored_same_endpoint_total 644
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 1000
telemt_user_connections_total{user="hello"} 547622
telemt_user_connections_current{user="hello"} 2518
telemt_user_octets_from_client{user="hello"} 3736382080 (3.48 GB)
telemt_user_octets_to_client{user="hello"} 93762749316 (87.32 GB)
telemt_user_unique_ips_current{user="hello"} 820
telemt_user_unique_ips_recent_window{user="hello"} 358
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 769.9 (0h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 62241
telemt_connections_bad_total 10186
telemt_handshake_timeouts_total 938
telemt_upstream_connect_attempt_total 141
telemt_upstream_connect_success_total 138
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 141
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 97
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 70
telemt_me_reconnect_success_total 70
telemt_me_reader_eof_total 35
telemt_me_idle_close_by_peer_total 35
telemt_me_route_drop_no_conn_total 20406
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 46786
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 97
telemt_desync_full_logged_total 43
telemt_desync_suppressed_total 54
telemt_desync_frames_bucket_total{bucket="1_2"} 25
telemt_desync_frames_bucket_total{bucket="3_10"} 28
telemt_desync_frames_bucket_total{bucket="gt_10"} 44
telemt_me_writer_removed_unexpected_total 57
telemt_me_writer_restored_same_endpoint_total 44
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 786
telemt_user_connections_total{user="hello"} 46672
telemt_user_connections_current{user="hello"} 3004
telemt_user_octets_from_client{user="hello"} 500464968 (477.28 MB)
telemt_user_octets_to_client{user="hello"} 16312899736 (15.19 GB)
telemt_user_unique_ips_current{user="hello"} 970
telemt_user_unique_ips_recent_window{user="hello"} 436
```

## hostvds.com

```
telemt 3.3.22

telemt_uptime_seconds 5706.7 (1h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 116026
telemt_connections_bad_total 5675
telemt_connections_current 855
telemt_connections_me_current 855
telemt_relay_adaptive_promotions_total 18
telemt_relay_adaptive_hard_promotions_total 18
telemt_handshake_timeouts_total 1039
telemt_upstream_connect_attempt_total 5109
telemt_upstream_connect_success_total 5102
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 5109
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2920
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2151
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 22
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_reconnect_attempts_total 330402
telemt_me_reconnect_success_total 945
telemt_me_reader_eof_total 875
telemt_me_idle_close_by_peer_total 875
telemt_me_route_drop_no_conn_total 65639
telemt_me_route_drop_channel_closed_total 17
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 100300
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 9
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 199
telemt_desync_full_logged_total 81
telemt_desync_suppressed_total 118
telemt_desync_frames_bucket_total{bucket="1_2"} 34
telemt_desync_frames_bucket_total{bucket="3_10"} 85
telemt_desync_frames_bucket_total{bucket="gt_10"} 80
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 870
telemt_me_refill_failed_total 10448
telemt_me_writer_restored_same_endpoint_total 934
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 40876
telemt_user_connections_total{user="hello"} 104055
telemt_user_connections_current{user="hello"} 855
telemt_user_octets_from_client{user="hello"} 1681246169 (1.57 GB)
telemt_user_octets_to_client{user="hello"} 20685170241 (19.26 GB)
telemt_user_msgs_from_client{user="hello"} 38712
telemt_user_msgs_to_client{user="hello"} 31668
telemt_user_unique_ips_current{user="hello"} 287
telemt_user_unique_ips_recent_window{user="hello"} 95
```

## 4vps.su

```
telemt 3.3.22

telemt_uptime_seconds 4774.5 (1h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 313312
telemt_connections_bad_total 12945
telemt_connections_current 2642
telemt_connections_me_current 2642
telemt_handshake_timeouts_total 2953
telemt_upstream_connect_attempt_total 880
telemt_upstream_connect_success_total 880
telemt_upstream_connect_attempts_per_request{bucket="1"} 880
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 482
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 397
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 14878
telemt_me_reconnect_success_total 588
telemt_me_reader_eof_total 491
telemt_me_idle_close_by_peer_total 491
telemt_me_route_drop_no_conn_total 221895
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="base"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 271121
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 647
telemt_desync_full_logged_total 243
telemt_desync_suppressed_total 404
telemt_desync_frames_bucket_total{bucket="1_2"} 136
telemt_desync_frames_bucket_total{bucket="3_10"} 224
telemt_desync_frames_bucket_total{bucket="gt_10"} 287
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 500
telemt_me_refill_failed_total 703
telemt_me_writer_restored_same_endpoint_total 527
telemt_me_writer_restored_fallback_total 61
telemt_me_async_recovery_trigger_total 9552
telemt_user_connections_total{user="hello"} 271547
telemt_user_connections_current{user="hello"} 2642
telemt_user_octets_from_client{user="hello"} 3666840104 (3.42 GB)
telemt_user_octets_to_client{user="hello"} 110333982748 (102.76 GB)
telemt_user_unique_ips_current{user="hello"} 787
telemt_user_unique_ips_recent_window{user="hello"} 346
```