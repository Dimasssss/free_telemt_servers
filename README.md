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

# Server Metrics 2026-03-20 06:40:03 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 48147.0 (13h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 969231
telemt_connections_bad_total 59727
telemt_connections_current 1590
telemt_connections_me_current 1590
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 25688
telemt_upstream_connect_attempt_total 9326
telemt_upstream_connect_success_total 9220
telemt_upstream_connect_fail_total 106
telemt_upstream_connect_attempts_per_request{bucket="1"} 9326
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5039
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4151
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 106
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 5755
telemt_me_reconnect_success_total 5711
telemt_me_reader_eof_total 6050
telemt_me_idle_close_by_peer_total 6049
telemt_me_route_drop_no_conn_total 278159
telemt_me_route_drop_channel_closed_total 98
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 789309
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4126
telemt_desync_full_logged_total 1493
telemt_desync_suppressed_total 2633
telemt_desync_frames_bucket_total{bucket="1_2"} 810
telemt_desync_frames_bucket_total{bucket="3_10"} 1600
telemt_desync_frames_bucket_total{bucket="gt_10"} 1716
telemt_pool_swap_total 52
telemt_me_writer_close_signal_drop_total 50
telemt_me_writer_removed_unexpected_total 5772
telemt_me_writer_restored_same_endpoint_total 5698
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 447
telemt_me_writer_removed_unexpected_minus_restored_total 61
telemt_user_connections_total{user="hello"} 788701
telemt_user_connections_current{user="hello"} 1590
telemt_user_octets_from_client{user="hello"} 34152839544 (31.81 GB)
telemt_user_octets_to_client{user="hello"} 272020208373 (253.34 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 572
telemt_user_unique_ips_recent_window{user="hello"} 217
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 64602.9 (17h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4289241
telemt_connections_bad_total 406489
telemt_connections_current 5478
telemt_connections_me_current 5478
telemt_handshake_timeouts_total 98079
telemt_upstream_connect_attempt_total 12118
telemt_upstream_connect_success_total 11894
telemt_upstream_connect_fail_total 224
telemt_upstream_connect_attempts_per_request{bucket="1"} 12118
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6697
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5134
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 224
telemt_me_keepalive_timeout_total 56
telemt_me_reconnect_attempts_total 11725
telemt_me_reconnect_success_total 7469
telemt_me_reader_eof_total 7990
telemt_me_idle_close_by_peer_total 7989
telemt_me_route_drop_no_conn_total 2011577
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3499928
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 13869
telemt_desync_full_logged_total 4599
telemt_desync_suppressed_total 9270
telemt_desync_frames_bucket_total{bucket="1_2"} 2723
telemt_desync_frames_bucket_total{bucket="3_10"} 5407
telemt_desync_frames_bucket_total{bucket="gt_10"} 5739
telemt_pool_swap_total 57
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 68
telemt_me_writer_removed_unexpected_total 7700
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 7414
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 231
telemt_user_connections_total{user="hello"} 3499571
telemt_user_connections_current{user="hello"} 5478
telemt_user_octets_from_client{user="hello"} 50778121526 (47.29 GB)
telemt_user_octets_to_client{user="hello"} 1295887156186 (1.18 TB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1732
telemt_user_unique_ips_recent_window{user="hello"} 719
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 64581.7 (17h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3935574
telemt_connections_bad_total 511389
telemt_connections_current 3166
telemt_connections_me_current 3166
telemt_handshake_timeouts_total 62086
telemt_upstream_connect_attempt_total 11902
telemt_upstream_connect_success_total 11807
telemt_upstream_connect_fail_total 95
telemt_upstream_connect_attempts_per_request{bucket="1"} 11902
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6119
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5471
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 206
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 95
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 3049
telemt_me_reconnect_attempts_total 8098
telemt_me_reconnect_success_total 7140
telemt_me_reader_eof_total 7479
telemt_me_idle_close_by_peer_total 7475
telemt_me_route_drop_no_conn_total 2653700
telemt_me_route_drop_channel_closed_total 241
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2819880
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 179
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9636
telemt_desync_full_logged_total 3028
telemt_desync_suppressed_total 6608
telemt_desync_frames_bucket_total{bucket="1_2"} 2408
telemt_desync_frames_bucket_total{bucket="3_10"} 3686
telemt_desync_frames_bucket_total{bucket="gt_10"} 3542
telemt_pool_swap_total 64
telemt_me_writer_close_signal_drop_total 287
telemt_me_writer_removed_unexpected_total 7227
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 7139
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 87
telemt_user_connections_total{user="hello"} 2826268
telemt_user_connections_current{user="hello"} 3166
telemt_user_octets_from_client{user="hello"} 39647709042 (36.92 GB)
telemt_user_octets_to_client{user="hello"} 1063882728332 (990.82 GB)
telemt_user_msgs_from_client{user="hello"} 2664
telemt_user_msgs_to_client{user="hello"} 1842
telemt_user_unique_ips_current{user="hello"} 1085
telemt_user_unique_ips_recent_window{user="hello"} 449
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 64568.5 (17h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3944328
telemt_connections_bad_total 271750
telemt_connections_current 4766
telemt_connections_me_current 4766
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 57069
telemt_upstream_connect_attempt_total 67739
telemt_upstream_connect_success_total 63009
telemt_upstream_connect_fail_total 4730
telemt_upstream_connect_attempts_per_request{bucket="1"} 67739
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52544
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9728
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 712
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4730
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 10390
telemt_me_reconnect_success_total 7408
telemt_me_reader_eof_total 7737
telemt_me_idle_close_by_peer_total 7736
telemt_me_route_drop_no_conn_total 3754615
telemt_me_route_drop_channel_closed_total 74
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3257310
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11460
telemt_desync_full_logged_total 3461
telemt_desync_suppressed_total 7999
telemt_desync_frames_bucket_total{bucket="1_2"} 2662
telemt_desync_frames_bucket_total{bucket="3_10"} 4409
telemt_desync_frames_bucket_total{bucket="gt_10"} 4389
telemt_pool_swap_total 52
telemt_me_writer_close_signal_drop_total 676
telemt_me_writer_removed_unexpected_total 8133
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 7404
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 410
telemt_me_writer_removed_unexpected_minus_restored_total 725
telemt_user_connections_total{user="hello"} 3308248
telemt_user_connections_current{user="hello"} 4766
telemt_user_octets_from_client{user="hello"} 44090007040 (41.06 GB)
telemt_user_octets_to_client{user="hello"} 827551434099 (770.72 GB)
telemt_user_msgs_from_client{user="hello"} 260491
telemt_user_msgs_to_client{user="hello"} 1782062
telemt_user_unique_ips_current{user="hello"} 1371
telemt_user_unique_ips_recent_window{user="hello"} 731
```

## rdp-onedash.ru

```
telemt 3.3.24

telemt_uptime_seconds 2151.6 (0h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 266836
telemt_connections_bad_total 30028
telemt_connections_current 4725
telemt_connections_me_current 4725
telemt_handshake_timeouts_total 5233
telemt_upstream_connect_attempt_total 395
telemt_upstream_connect_success_total 394
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 395
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 220
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 173
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 236
telemt_me_reconnect_success_total 234
telemt_me_reader_eof_total 206
telemt_me_idle_close_by_peer_total 206
telemt_me_route_drop_no_conn_total 200633
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 212307
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 602
telemt_desync_full_logged_total 202
telemt_desync_suppressed_total 400
telemt_desync_frames_bucket_total{bucket="1_2"} 105
telemt_desync_frames_bucket_total{bucket="3_10"} 266
telemt_desync_frames_bucket_total{bucket="gt_10"} 231
telemt_pool_swap_total 1
telemt_me_writer_close_signal_drop_total 22
telemt_me_writer_removed_unexpected_total 223
telemt_me_writer_restored_same_endpoint_total 204
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 156
telemt_user_connections_total{user="hello"} 212190
telemt_user_connections_current{user="hello"} 4725
telemt_user_octets_from_client{user="hello"} 3126036512 (2.91 GB)
telemt_user_octets_to_client{user="hello"} 56508822572 (52.63 GB)
telemt_user_unique_ips_current{user="hello"} 1435
telemt_user_unique_ips_recent_window{user="hello"} 655
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 2087.1 (0h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 32210
telemt_connections_bad_total 5682
telemt_connections_current 561
telemt_connections_me_current 561
telemt_handshake_timeouts_total 418
telemt_upstream_connect_attempt_total 373
telemt_upstream_connect_success_total 368
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 373
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 197
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 170
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_reconnect_attempts_total 212
telemt_me_reconnect_success_total 210
telemt_me_reader_eof_total 188
telemt_me_idle_close_by_peer_total 188
telemt_me_route_drop_no_conn_total 19415
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 33666
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 128
telemt_desync_full_logged_total 37
telemt_desync_suppressed_total 91
telemt_desync_frames_bucket_total{bucket="1_2"} 18
telemt_desync_frames_bucket_total{bucket="3_10"} 56
telemt_desync_frames_bucket_total{bucket="gt_10"} 54
telemt_pool_swap_total 1
telemt_me_writer_close_signal_drop_total 23
telemt_me_writer_removed_unexpected_total 210
telemt_me_writer_restored_same_endpoint_total 202
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 198
telemt_user_connections_total{user="hello"} 24823
telemt_user_connections_current{user="hello"} 561
telemt_user_octets_from_client{user="hello"} 215534916 (205.55 MB)
telemt_user_octets_to_client{user="hello"} 9192529124 (8.56 GB)
telemt_user_unique_ips_current{user="hello"} 213
telemt_user_unique_ips_recent_window{user="hello"} 81
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 64533.2 (17h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2767190
telemt_connections_bad_total 180051
telemt_connections_current 4048
telemt_connections_me_current 4048
telemt_handshake_timeouts_total 48870
telemt_upstream_connect_attempt_total 11434
telemt_upstream_connect_success_total 11363
telemt_upstream_connect_fail_total 71
telemt_upstream_connect_attempts_per_request{bucket="1"} 11434
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6148
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5178
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 71
telemt_me_keepalive_timeout_total 14
telemt_me_reconnect_attempts_total 8216
telemt_me_reconnect_success_total 8163
telemt_me_reader_eof_total 8632
telemt_me_idle_close_by_peer_total 8632
telemt_me_route_drop_no_conn_total 946605
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2315337
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11626
telemt_desync_full_logged_total 3807
telemt_desync_suppressed_total 7819
telemt_desync_frames_bucket_total{bucket="1_2"} 2324
telemt_desync_frames_bucket_total{bucket="3_10"} 4085
telemt_desync_frames_bucket_total{bucket="gt_10"} 5217
telemt_pool_swap_total 66
telemt_me_writer_close_signal_drop_total 44
telemt_me_writer_removed_unexpected_total 8276
telemt_me_writer_restored_same_endpoint_total 8146
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 113
telemt_user_connections_total{user="hello"} 2314189
telemt_user_connections_current{user="hello"} 4048
telemt_user_octets_from_client{user="hello"} 50528634264 (47.06 GB)
telemt_user_octets_to_client{user="hello"} 1215417857432 (1.11 TB)
telemt_user_unique_ips_current{user="hello"} 1308
telemt_user_unique_ips_recent_window{user="hello"} 507
```