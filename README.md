# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt  
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

**Принимаю донаты криптой для добавления и продления серверов:**  
- TON: UQAyIvWts4-gC0b5ouoy_JNDfBEe337c7oOBqpGXFB8fJUzB

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-60
- Краткое описание тарифа: 4 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 19 апреля
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
Этот сервер пользуется большим спросом. Я арендовал еще один такой же, чтобы распределить нагрузку.

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

# Server Metrics 2026-03-20 07:53:09 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 52533.5 (14h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1123302
telemt_connections_bad_total 64600
telemt_connections_current 1667
telemt_connections_me_current 1667
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 29185
telemt_upstream_connect_attempt_total 10126
telemt_upstream_connect_success_total 10015
telemt_upstream_connect_fail_total 111
telemt_upstream_connect_attempts_per_request{bucket="1"} 10126
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5424
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4561
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 111
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 25
telemt_me_reconnect_attempts_total 6333
telemt_me_reconnect_success_total 6286
telemt_me_reader_eof_total 6657
telemt_me_idle_close_by_peer_total 6656
telemt_me_route_drop_no_conn_total 325655
telemt_me_route_drop_channel_closed_total 152
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 924816
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4685
telemt_desync_full_logged_total 1685
telemt_desync_suppressed_total 3000
telemt_desync_frames_bucket_total{bucket="1_2"} 944
telemt_desync_frames_bucket_total{bucket="3_10"} 1814
telemt_desync_frames_bucket_total{bucket="gt_10"} 1927
telemt_pool_swap_total 56
telemt_me_writer_close_signal_drop_total 78
telemt_me_writer_removed_unexpected_total 6356
telemt_me_writer_restored_same_endpoint_total 6273
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 447
telemt_me_writer_removed_unexpected_minus_restored_total 70
telemt_user_connections_total{user="hello"} 924294
telemt_user_connections_current{user="hello"} 1667
telemt_user_octets_from_client{user="hello"} 36876746108 (34.34 GB)
telemt_user_octets_to_client{user="hello"} 317449342741 (295.65 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 592
telemt_user_unique_ips_recent_window{user="hello"} 247
```

## psb.hosting №1

```
telemt 3.3.24

telemt_uptime_seconds 68989.1 (19h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5083818
telemt_connections_bad_total 449173
telemt_connections_current 3624
telemt_connections_me_current 3624
telemt_handshake_timeouts_total 108213
telemt_upstream_connect_attempt_total 12802
telemt_upstream_connect_success_total 12537
telemt_upstream_connect_fail_total 265
telemt_upstream_connect_attempts_per_request{bucket="1"} 12802
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7039
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5402
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 265
telemt_me_keepalive_timeout_total 119
telemt_me_reconnect_attempts_total 12163
telemt_me_reconnect_success_total 7886
telemt_me_reader_eof_total 8437
telemt_me_idle_close_by_peer_total 8436
telemt_me_route_drop_no_conn_total 3106987
telemt_me_route_drop_channel_closed_total 55
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4198722
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 15534
telemt_desync_full_logged_total 5133
telemt_desync_suppressed_total 10401
telemt_desync_frames_bucket_total{bucket="1_2"} 3053
telemt_desync_frames_bucket_total{bucket="3_10"} 6064
telemt_desync_frames_bucket_total{bucket="gt_10"} 6417
telemt_pool_swap_total 61
telemt_pool_stale_pick_total 8
telemt_me_writer_close_signal_drop_total 109
telemt_me_writer_removed_unexpected_total 8131
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 7831
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 245
telemt_user_connections_total{user="hello"} 4200794
telemt_user_connections_current{user="hello"} 3624
telemt_user_octets_from_client{user="hello"} 55964515162 (52.12 GB)
telemt_user_octets_to_client{user="hello"} 1397249019222 (1.27 TB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1275
telemt_user_unique_ips_recent_window{user="hello"} 440
```

## psb.hosting №2

```
telemt 3.3.24

telemt_uptime_seconds 2331.0 (0h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 95191
telemt_connections_bad_total 8361
telemt_connections_current 2185
telemt_connections_me_current 2185
telemt_handshake_timeouts_total 840
telemt_upstream_connect_attempt_total 513
telemt_upstream_connect_success_total 513
telemt_upstream_connect_attempts_per_request{bucket="1"} 513
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 314
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 198
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 312
telemt_me_reconnect_success_total 308
telemt_me_reader_eof_total 278
telemt_me_idle_close_by_peer_total 278
telemt_me_route_drop_no_conn_total 32148
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 81537
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 415
telemt_desync_full_logged_total 131
telemt_desync_suppressed_total 284
telemt_desync_frames_bucket_total{bucket="1_2"} 75
telemt_desync_frames_bucket_total{bucket="3_10"} 140
telemt_desync_frames_bucket_total{bucket="gt_10"} 200
telemt_pool_swap_total 2
telemt_me_writer_close_signal_drop_total 23
telemt_me_writer_removed_unexpected_total 288
telemt_me_writer_restored_same_endpoint_total 308
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 41
telemt_user_connections_total{user="hello"} 81607
telemt_user_connections_current{user="hello"} 2185
telemt_user_octets_from_client{user="hello"} 1839108240 (1.71 GB)
telemt_user_octets_to_client{user="hello"} 30309676451 (28.23 GB)
telemt_user_msgs_from_client{user="hello"} 145
telemt_user_msgs_to_client{user="hello"} 1210
telemt_user_unique_ips_current{user="hello"} 859
telemt_user_unique_ips_recent_window{user="hello"} 349
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 68967.6 (19h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4425490
telemt_connections_bad_total 553475
telemt_connections_current 4723
telemt_connections_me_current 4723
telemt_handshake_timeouts_total 67149
telemt_upstream_connect_attempt_total 12580
telemt_upstream_connect_success_total 12474
telemt_upstream_connect_fail_total 106
telemt_upstream_connect_attempts_per_request{bucket="1"} 12580
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6510
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5738
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 215
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 106
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 3086
telemt_me_reconnect_attempts_total 8546
telemt_me_reconnect_success_total 7582
telemt_me_reader_eof_total 7936
telemt_me_idle_close_by_peer_total 7931
telemt_me_route_drop_no_conn_total 2838118
telemt_me_route_drop_channel_closed_total 274
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3188429
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 179
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11291
telemt_desync_full_logged_total 3549
telemt_desync_suppressed_total 7742
telemt_desync_frames_bucket_total{bucket="1_2"} 2684
telemt_desync_frames_bucket_total{bucket="3_10"} 4301
telemt_desync_frames_bucket_total{bucket="gt_10"} 4306
telemt_pool_swap_total 68
telemt_me_writer_close_signal_drop_total 323
telemt_me_writer_removed_unexpected_total 7681
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 7581
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 99
telemt_user_connections_total{user="hello"} 3194812
telemt_user_connections_current{user="hello"} 4723
telemt_user_octets_from_client{user="hello"} 44658289030 (41.59 GB)
telemt_user_octets_to_client{user="hello"} 1194512379564 (1.09 TB)
telemt_user_msgs_from_client{user="hello"} 2664
telemt_user_msgs_to_client{user="hello"} 1842
telemt_user_unique_ips_current{user="hello"} 1515
telemt_user_unique_ips_recent_window{user="hello"} 597
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 68954.8 (19h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5323416
telemt_connections_bad_total 299459
telemt_connections_current 5734
telemt_connections_me_current 5734
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 73719
telemt_upstream_connect_attempt_total 82455
telemt_upstream_connect_success_total 70730
telemt_upstream_connect_fail_total 11725
telemt_upstream_connect_attempts_per_request{bucket="1"} 82455
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 57095
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11397
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2211
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11725
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 132
telemt_me_reconnect_attempts_total 11048
telemt_me_reconnect_success_total 7934
telemt_me_reader_eof_total 8261
telemt_me_idle_close_by_peer_total 8260
telemt_me_route_drop_no_conn_total 6785464
telemt_me_route_drop_channel_closed_total 82
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4503693
telemt_me_writer_pick_total{mode="p2c",result="full"} 4273
telemt_me_writer_pick_total{mode="p2c",result="closed"} 804
telemt_me_writer_pick_blocking_fallback_total 5052
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 13575
telemt_desync_full_logged_total 3921
telemt_desync_suppressed_total 9654
telemt_desync_frames_bucket_total{bucket="1_2"} 3031
telemt_desync_frames_bucket_total{bucket="3_10"} 5405
telemt_desync_frames_bucket_total{bucket="gt_10"} 5139
telemt_pool_swap_total 55
telemt_me_writer_close_signal_drop_total 824
telemt_me_writer_removed_unexpected_total 8759
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 7930
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 874
telemt_me_async_recovery_trigger_total 5091
telemt_me_writer_removed_unexpected_minus_restored_total 825
telemt_user_connections_total{user="hello"} 4562950
telemt_user_connections_current{user="hello"} 5734
telemt_user_octets_from_client{user="hello"} 48656457455 (45.31 GB)
telemt_user_octets_to_client{user="hello"} 874571202445 (814.51 GB)
telemt_user_msgs_from_client{user="hello"} 277683
telemt_user_msgs_to_client{user="hello"} 1826172
telemt_user_unique_ips_current{user="hello"} 1475
telemt_user_unique_ips_recent_window{user="hello"} 914
```

## rdp-onedash.ru

```
telemt 3.3.24

telemt_uptime_seconds 6537.8 (1h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1245550
telemt_connections_bad_total 97763
telemt_connections_current 5896
telemt_connections_me_current 5896
telemt_handshake_timeouts_total 18275
telemt_upstream_connect_attempt_total 1092
telemt_upstream_connect_success_total 1086
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 1092
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 571
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 513
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 709
telemt_me_reconnect_success_total 706
telemt_me_reader_eof_total 703
telemt_me_idle_close_by_peer_total 703
telemt_me_route_drop_no_conn_total 1805665
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1053994
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2389
telemt_desync_full_logged_total 716
telemt_desync_suppressed_total 1673
telemt_desync_frames_bucket_total{bucket="1_2"} 469
telemt_desync_frames_bucket_total{bucket="3_10"} 969
telemt_desync_frames_bucket_total{bucket="gt_10"} 951
telemt_pool_swap_total 4
telemt_me_writer_close_signal_drop_total 27
telemt_me_writer_removed_unexpected_total 704
telemt_me_writer_restored_same_endpoint_total 676
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 156
telemt_user_connections_total{user="hello"} 1053938
telemt_user_connections_current{user="hello"} 5896
telemt_user_octets_from_client{user="hello"} 11211409076 (10.44 GB)
telemt_user_octets_to_client{user="hello"} 161362615700 (150.28 GB)
telemt_user_unique_ips_current{user="hello"} 1757
telemt_user_unique_ips_recent_window{user="hello"} 889
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 6473.7 (1h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 101103
telemt_connections_bad_total 13976
telemt_connections_current 685
telemt_connections_me_current 685
telemt_handshake_timeouts_total 1197
telemt_upstream_connect_attempt_total 1194
telemt_upstream_connect_success_total 1184
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 1194
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 604
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 579
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 811
telemt_me_reconnect_success_total 806
telemt_me_reader_eof_total 830
telemt_me_idle_close_by_peer_total 830
telemt_me_route_drop_no_conn_total 51695
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 97430
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 310
telemt_desync_full_logged_total 102
telemt_desync_suppressed_total 208
telemt_desync_frames_bucket_total{bucket="1_2"} 39
telemt_desync_frames_bucket_total{bucket="3_10"} 136
telemt_desync_frames_bucket_total{bucket="gt_10"} 135
telemt_pool_swap_total 6
telemt_me_writer_close_signal_drop_total 28
telemt_me_writer_removed_unexpected_total 812
telemt_me_writer_restored_same_endpoint_total 798
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 198
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 81420
telemt_user_connections_current{user="hello"} 685
telemt_user_octets_from_client{user="hello"} 1243881700 (1.16 GB)
telemt_user_octets_to_client{user="hello"} 32782074928 (30.53 GB)
telemt_user_unique_ips_current{user="hello"} 237
telemt_user_unique_ips_recent_window{user="hello"} 102
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 68919.7 (19h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3189690
telemt_connections_bad_total 211472
telemt_connections_current 5283
telemt_connections_me_current 5283
telemt_handshake_timeouts_total 57901
telemt_upstream_connect_attempt_total 12057
telemt_upstream_connect_success_total 11982
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 12057
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6481
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5464
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 14
telemt_me_reconnect_attempts_total 8617
telemt_me_reconnect_success_total 8560
telemt_me_reader_eof_total 9052
telemt_me_idle_close_by_peer_total 9052
telemt_me_route_drop_no_conn_total 1085989
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2677471
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 13136
telemt_desync_full_logged_total 4289
telemt_desync_suppressed_total 8847
telemt_desync_frames_bucket_total{bucket="1_2"} 2615
telemt_desync_frames_bucket_total{bucket="3_10"} 4685
telemt_desync_frames_bucket_total{bucket="gt_10"} 5836
telemt_pool_swap_total 71
telemt_me_writer_close_signal_drop_total 49
telemt_me_writer_removed_unexpected_total 8683
telemt_me_writer_restored_same_endpoint_total 8543
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 123
telemt_user_connections_total{user="hello"} 2675406
telemt_user_connections_current{user="hello"} 5283
telemt_user_octets_from_client{user="hello"} 56407653380 (52.53 GB)
telemt_user_octets_to_client{user="hello"} 1395883318056 (1.27 TB)
telemt_user_unique_ips_current{user="hello"} 1651
telemt_user_unique_ips_recent_window{user="hello"} 664
```