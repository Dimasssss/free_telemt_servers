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

# Server Metrics 2026-03-18 15:53:47 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 1705.8 (0h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 57941
telemt_connections_bad_total 5920
telemt_handshake_timeouts_total 2954
telemt_upstream_connect_attempt_total 216
telemt_upstream_connect_success_total 216
telemt_upstream_connect_attempts_per_request{bucket="1"} 216
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 105
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 110
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 103
telemt_me_reconnect_success_total 102
telemt_me_reader_eof_total 83
telemt_me_idle_close_by_peer_total 83
telemt_me_route_drop_no_conn_total 19121
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 45458
telemt_me_writer_pick_total{mode="p2c",result="full"} 116
telemt_me_writer_pick_total{mode="p2c",result="closed"} 293
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 306
telemt_desync_full_logged_total 65
telemt_desync_suppressed_total 241
telemt_desync_frames_bucket_total{bucket="1_2"} 89
telemt_desync_frames_bucket_total{bucket="3_10"} 79
telemt_desync_frames_bucket_total{bucket="gt_10"} 138
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 105
telemt_me_writer_restored_same_endpoint_total 91
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 75
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 45442
telemt_user_connections_current{user="hello"} 1520
telemt_user_octets_from_client{user="hello"} 719478612 (686.15 MB)
telemt_user_octets_to_client{user="hello"} 13622308192 (12.69 GB)
telemt_user_unique_ips_current{user="hello"} 516
telemt_user_unique_ips_recent_window{user="hello"} 198
```

## psb.hosting

```
telemt 3.3.22

telemt_uptime_seconds 6534.6 (1h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 709912
telemt_connections_bad_total 46421
telemt_connections_current 3496
telemt_connections_me_current 3496
telemt_handshake_timeouts_total 12848
telemt_upstream_connect_attempt_total 1163
telemt_upstream_connect_success_total 1155
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 1163
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 684
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 465
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 780
telemt_me_reconnect_success_total 772
telemt_me_reader_eof_total 695
telemt_me_idle_close_by_peer_total 694
telemt_me_route_drop_no_conn_total 716275
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 616819
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1589
telemt_desync_full_logged_total 493
telemt_desync_suppressed_total 1096
telemt_desync_frames_bucket_total{bucket="1_2"} 332
telemt_desync_frames_bucket_total{bucket="3_10"} 643
telemt_desync_frames_bucket_total{bucket="gt_10"} 614
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 701
telemt_me_writer_restored_same_endpoint_total 770
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 2874
telemt_user_connections_total{user="hello"} 616023
telemt_user_connections_current{user="hello"} 3496
telemt_user_octets_from_client{user="hello"} 5804555328 (5.41 GB)
telemt_user_octets_to_client{user="hello"} 166761306492 (155.31 GB)
telemt_user_unique_ips_current{user="hello"} 1147
telemt_user_unique_ips_recent_window{user="hello"} 498
```

## koara.io

```
telemt 3.3.22

telemt_uptime_seconds 6463.9 (1h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 471285
telemt_connections_bad_total 29947
telemt_connections_current 2834
telemt_connections_me_current 2834
telemt_handshake_timeouts_total 9465
telemt_upstream_connect_attempt_total 913
telemt_upstream_connect_success_total 908
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 913
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 467
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 438
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_reconnect_attempts_total 537
telemt_me_reconnect_success_total 531
telemt_me_reader_eof_total 549
telemt_me_idle_close_by_peer_total 549
telemt_me_route_drop_no_conn_total 261533
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 398900
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1385
telemt_desync_full_logged_total 395
telemt_desync_suppressed_total 990
telemt_desync_frames_bucket_total{bucket="1_2"} 326
telemt_desync_frames_bucket_total{bucket="3_10"} 516
telemt_desync_frames_bucket_total{bucket="gt_10"} 543
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 545
telemt_me_writer_restored_same_endpoint_total 514
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 652
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 398652
telemt_user_connections_current{user="hello"} 2834
telemt_user_octets_from_client{user="hello"} 8015426756 (7.46 GB)
telemt_user_octets_to_client{user="hello"} 150563448324 (140.22 GB)
telemt_user_unique_ips_current{user="hello"} 926
telemt_user_unique_ips_recent_window{user="hello"} 387
```

## landvps.ru

```
telemt 3.3.22

telemt_uptime_seconds 7177.5 (1h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 653361
telemt_connections_bad_total 8081
telemt_connections_current 2521
telemt_connections_me_current 2521
telemt_handshake_timeouts_total 8944
telemt_upstream_connect_attempt_total 1136
telemt_upstream_connect_success_total 1127
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 1136
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 595
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 526
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 748
telemt_me_reconnect_success_total 740
telemt_me_reader_eof_total 728
telemt_me_idle_close_by_peer_total 727
telemt_me_route_drop_no_conn_total 1085530
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 594136
telemt_me_writer_pick_total{mode="p2c",result="full"} 30
telemt_me_writer_pick_total{mode="p2c",result="closed"} 61
telemt_me_endpoint_quarantine_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2230
telemt_desync_full_logged_total 549
telemt_desync_suppressed_total 1681
telemt_desync_frames_bucket_total{bucket="1_2"} 487
telemt_desync_frames_bucket_total{bucket="3_10"} 1024
telemt_desync_frames_bucket_total{bucket="gt_10"} 719
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 726
telemt_me_writer_restored_same_endpoint_total 729
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 1000
telemt_user_connections_total{user="hello"} 594135
telemt_user_connections_current{user="hello"} 2521
telemt_user_octets_from_client{user="hello"} 4286837704 (3.99 GB)
telemt_user_octets_to_client{user="hello"} 109230135760 (101.73 GB)
telemt_user_unique_ips_current{user="hello"} 806
telemt_user_unique_ips_recent_window{user="hello"} 361
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 1692.2 (0h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 128954
telemt_connections_bad_total 22758
telemt_handshake_timeouts_total 1739
telemt_upstream_connect_attempt_total 254
telemt_upstream_connect_success_total 248
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 254
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 155
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 93
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 137
telemt_me_reconnect_success_total 135
telemt_me_reader_eof_total 104
telemt_me_idle_close_by_peer_total 104
telemt_me_route_drop_no_conn_total 47530
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 95507
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 263
telemt_desync_full_logged_total 90
telemt_desync_suppressed_total 173
telemt_desync_frames_bucket_total{bucket="1_2"} 56
telemt_desync_frames_bucket_total{bucket="3_10"} 75
telemt_desync_frames_bucket_total{bucket="gt_10"} 132
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 125
telemt_me_writer_restored_same_endpoint_total 109
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 786
telemt_user_connections_total{user="hello"} 95303
telemt_user_connections_current{user="hello"} 2967
telemt_user_octets_from_client{user="hello"} 1709461424 (1.59 GB)
telemt_user_octets_to_client{user="hello"} 34548963884 (32.18 GB)
telemt_user_unique_ips_current{user="hello"} 965
telemt_user_unique_ips_recent_window{user="hello"} 405
```

## hostvds.com

```
telemt 3.3.22

telemt_uptime_seconds 6626.2 (1h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 131943
telemt_connections_bad_total 5706
telemt_connections_current 904
telemt_connections_me_current 904
telemt_relay_adaptive_promotions_total 18
telemt_relay_adaptive_hard_promotions_total 18
telemt_handshake_timeouts_total 1212
telemt_upstream_connect_attempt_total 5271
telemt_upstream_connect_success_total 5262
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 5271
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3006
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2225
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 22
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_reconnect_attempts_total 330515
telemt_me_reconnect_success_total 1058
telemt_me_reader_eof_total 987
telemt_me_idle_close_by_peer_total 987
telemt_me_route_drop_no_conn_total 74007
telemt_me_route_drop_channel_closed_total 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 115077
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 9
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 233
telemt_desync_full_logged_total 94
telemt_desync_suppressed_total 139
telemt_desync_frames_bucket_total{bucket="1_2"} 36
telemt_desync_frames_bucket_total{bucket="3_10"} 99
telemt_desync_frames_bucket_total{bucket="gt_10"} 98
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 983
telemt_me_refill_failed_total 10448
telemt_me_writer_restored_same_endpoint_total 1047
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 40876
telemt_user_connections_total{user="hello"} 118826
telemt_user_connections_current{user="hello"} 904
telemt_user_octets_from_client{user="hello"} 1857129057 (1.73 GB)
telemt_user_octets_to_client{user="hello"} 24958402605 (23.24 GB)
telemt_user_msgs_from_client{user="hello"} 38712
telemt_user_msgs_to_client{user="hello"} 31668
telemt_user_unique_ips_current{user="hello"} 327
telemt_user_unique_ips_recent_window{user="hello"} 151
```

## 4vps.su

```
telemt 3.3.22

telemt_uptime_seconds 5696.7 (1h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 362789
telemt_connections_bad_total 14113
telemt_connections_current 2533
telemt_connections_me_current 2533
telemt_handshake_timeouts_total 3932
telemt_upstream_connect_attempt_total 1084
telemt_upstream_connect_success_total 1084
telemt_upstream_connect_attempts_per_request{bucket="1"} 1084
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 592
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 491
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 15037
telemt_me_reconnect_success_total 745
telemt_me_reader_eof_total 650
telemt_me_idle_close_by_peer_total 650
telemt_me_route_drop_no_conn_total 240129
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="base"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 312232
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 776
telemt_desync_full_logged_total 294
telemt_desync_suppressed_total 482
telemt_desync_frames_bucket_total{bucket="1_2"} 163
telemt_desync_frames_bucket_total{bucket="3_10"} 272
telemt_desync_frames_bucket_total{bucket="gt_10"} 341
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 660
telemt_me_refill_failed_total 703
telemt_me_writer_restored_same_endpoint_total 684
telemt_me_writer_restored_fallback_total 61
telemt_me_async_recovery_trigger_total 9552
telemt_user_connections_total{user="hello"} 312525
telemt_user_connections_current{user="hello"} 2533
telemt_user_octets_from_client{user="hello"} 4372749616 (4.07 GB)
telemt_user_octets_to_client{user="hello"} 127901785120 (119.12 GB)
telemt_user_unique_ips_current{user="hello"} 792
telemt_user_unique_ips_recent_window{user="hello"} 319
```