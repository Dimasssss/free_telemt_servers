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

# Server Metrics 2026-03-13 17:17:43 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 121463.6 (33h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 511172
telemt_connections_bad_total 6636
telemt_handshake_timeouts_total 11651
telemt_upstream_connect_attempt_total 30170
telemt_upstream_connect_success_total 30021
telemt_upstream_connect_fail_total 149
telemt_upstream_connect_attempts_per_request{bucket="1"} 30170
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13589
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16361
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 149
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3369
telemt_me_reconnect_attempts_total 27509
telemt_me_reconnect_success_total 23959
telemt_me_reader_eof_total 25583
telemt_me_idle_close_by_peer_total 25582
telemt_me_route_drop_no_conn_total 166122
telemt_me_route_drop_channel_closed_total 28
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 445215
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1434
telemt_desync_full_logged_total 501
telemt_desync_suppressed_total 933
telemt_desync_frames_bucket_total{bucket="1_2"} 318
telemt_desync_frames_bucket_total{bucket="3_10"} 518
telemt_desync_frames_bucket_total{bucket="gt_10"} 598
telemt_pool_swap_total 110
telemt_me_writer_removed_unexpected_total 24330
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 23943
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 371
telemt_user_connections_total{user="hello"} 444784
telemt_user_connections_current{user="hello"} 356
telemt_user_octets_from_client{user="hello"} 8137046624 (7.58 GB)
telemt_user_octets_to_client{user="hello"} 207220743600 (192.99 GB)
telemt_user_unique_ips_current{user="hello"} 99
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 121357.6 (33h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 250654
telemt_connections_bad_total 1942
telemt_handshake_timeouts_total 1807
telemt_upstream_connect_attempt_total 105216
telemt_upstream_connect_success_total 104391
telemt_upstream_connect_fail_total 825
telemt_upstream_connect_attempts_per_request{bucket="1"} 105216
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 77041
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25885
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1465
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 825
telemt_me_keepalive_timeout_total 1490
telemt_me_reconnect_attempts_total 123200
telemt_me_reconnect_success_total 26033
telemt_me_reader_eof_total 29823
telemt_me_idle_close_by_peer_total 29823
telemt_me_route_drop_no_conn_total 82309
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 165170
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 29
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 32
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 18
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 29293
telemt_me_refill_failed_total 3032
telemt_me_writer_restored_same_endpoint_total 26016
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 3260
telemt_user_connections_total{user="hello"} 237265
telemt_user_connections_current{user="hello"} 207
telemt_user_octets_from_client{user="hello"} 2480183856 (2.31 GB)
telemt_user_octets_to_client{user="hello"} 73421550760 (68.38 GB)
telemt_user_msgs_from_client{user="hello"} 1136646
telemt_user_msgs_to_client{user="hello"} 6638669
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 121321.3 (33h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 296837
telemt_connections_bad_total 2474
telemt_handshake_timeouts_total 16043
telemt_upstream_connect_attempt_total 32411
telemt_upstream_connect_success_total 32407
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 32411
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15035
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17340
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2545
telemt_me_reconnect_attempts_total 27537
telemt_me_reconnect_success_total 26311
telemt_me_reader_eof_total 28203
telemt_me_idle_close_by_peer_total 28203
telemt_me_route_drop_no_conn_total 106359
telemt_me_route_drop_channel_closed_total 16
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 267833
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 104
telemt_desync_full_logged_total 48
telemt_desync_suppressed_total 56
telemt_desync_frames_bucket_total{bucket="1_2"} 9
telemt_desync_frames_bucket_total{bucket="3_10"} 34
telemt_desync_frames_bucket_total{bucket="gt_10"} 61
telemt_pool_swap_total 110
telemt_me_writer_removed_unexpected_total 26605
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 26291
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 294
telemt_user_connections_total{user="hello"} 267742
telemt_user_connections_current{user="hello"} 148
telemt_user_octets_from_client{user="hello"} 10135926100 (9.44 GB)
telemt_user_octets_to_client{user="hello"} 111540737296 (103.88 GB)
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 121296.8 (33h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 402572
telemt_connections_bad_total 15106
telemt_handshake_timeouts_total 3851
telemt_upstream_connect_attempt_total 55866
telemt_upstream_connect_success_total 45642
telemt_upstream_connect_fail_total 10224
telemt_upstream_connect_attempts_per_request{bucket="1"} 55866
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27960
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17424
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 249
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10224
telemt_me_keepalive_timeout_total 4386
telemt_me_reconnect_attempts_total 112754
telemt_me_reconnect_success_total 24481
telemt_me_reader_eof_total 27937
telemt_me_idle_close_by_peer_total 27930
telemt_me_route_drop_no_conn_total 140026
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 338938
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1350
telemt_desync_full_logged_total 402
telemt_desync_suppressed_total 948
telemt_desync_frames_bucket_total{bucket="1_2"} 331
telemt_desync_frames_bucket_total{bucket="3_10"} 520
telemt_desync_frames_bucket_total{bucket="gt_10"} 499
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 27548
telemt_me_refill_failed_total 2753
telemt_me_writer_restored_same_endpoint_total 24471
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3067
telemt_user_connections_total{user="hello"} 353911
telemt_user_connections_current{user="hello"} 197
telemt_user_octets_from_client{user="hello"} 8309140784 (7.74 GB)
telemt_user_octets_to_client{user="hello"} 128313038168 (119.50 GB)
telemt_user_msgs_from_client{user="hello"} 412626
telemt_user_msgs_to_client{user="hello"} 737182
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 71468.3 (19h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 115844
telemt_connections_bad_total 14801
telemt_handshake_timeouts_total 1386
telemt_upstream_connect_attempt_total 28506
telemt_upstream_connect_success_total 28246
telemt_upstream_connect_fail_total 260
telemt_upstream_connect_attempts_per_request{bucket="1"} 28506
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14637
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13523
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 86
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 260
telemt_me_keepalive_timeout_total 1138
telemt_me_reconnect_attempts_total 33142
telemt_me_reconnect_success_total 19756
telemt_me_reader_eof_total 21197
telemt_me_idle_close_by_peer_total 21197
telemt_me_route_drop_no_conn_total 36028
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 91021
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 390
telemt_desync_full_logged_total 76
telemt_desync_suppressed_total 314
telemt_desync_frames_bucket_total{bucket="1_2"} 52
telemt_desync_frames_bucket_total{bucket="3_10"} 214
telemt_desync_frames_bucket_total{bucket="gt_10"} 124
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 20353
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 19738
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 597
telemt_user_connections_total{user="hello"} 95919
telemt_user_connections_current{user="hello"} 100
telemt_user_octets_from_client{user="hello"} 1149387841 (1.07 GB)
telemt_user_octets_to_client{user="hello"} 29914207491 (27.86 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 121253.6 (33h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 740139
telemt_connections_bad_total 24645
telemt_handshake_timeouts_total 24385
telemt_upstream_connect_attempt_total 25335
telemt_upstream_connect_success_total 25205
telemt_upstream_connect_fail_total 130
telemt_upstream_connect_attempts_per_request{bucket="1"} 25335
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11830
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13346
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 130
telemt_me_keepalive_timeout_total 2805
telemt_me_reconnect_attempts_total 23825
telemt_me_reconnect_success_total 19185
telemt_me_reader_eof_total 20585
telemt_me_idle_close_by_peer_total 20582
telemt_me_route_drop_no_conn_total 349521
telemt_me_route_drop_channel_closed_total 15
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 694072
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 668
telemt_desync_full_logged_total 218
telemt_desync_suppressed_total 450
telemt_desync_frames_bucket_total{bucket="1_2"} 236
telemt_desync_frames_bucket_total{bucket="3_10"} 221
telemt_desync_frames_bucket_total{bucket="gt_10"} 211
telemt_pool_swap_total 111
telemt_me_writer_removed_unexpected_total 19577
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 19178
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 392
telemt_user_connections_total{user="hello"} 666957
telemt_user_connections_current{user="hello"} 445
telemt_user_octets_from_client{user="hello"} 11553595120 (10.76 GB)
telemt_user_octets_to_client{user="hello"} 336634188504 (313.52 GB)
telemt_user_unique_ips_current{user="hello"} 155
telemt_user_unique_ips_recent_window{user="hello"} 54
```