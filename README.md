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

# Server Metrics 2026-03-19 10:13:59 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 44729.7 (12h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 986069
telemt_connections_bad_total 86621
telemt_connections_current 1559
telemt_connections_me_current 1559
telemt_handshake_timeouts_total 35979
telemt_upstream_connect_attempt_total 8485
telemt_upstream_connect_success_total 8337
telemt_upstream_connect_fail_total 148
telemt_upstream_connect_attempts_per_request{bucket="1"} 8485
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4027
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4307
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 148
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 89
telemt_me_reconnect_attempts_total 7254
telemt_me_reconnect_success_total 6094
telemt_me_reader_eof_total 6457
telemt_me_idle_close_by_peer_total 6456
telemt_me_seq_mismatch_total 10
telemt_me_route_drop_no_conn_total 335354
telemt_me_route_drop_channel_closed_total 144
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 757246
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 30
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4525
telemt_desync_full_logged_total 1382
telemt_desync_suppressed_total 3143
telemt_desync_frames_bucket_total{bucket="1_2"} 1514
telemt_desync_frames_bucket_total{bucket="3_10"} 1651
telemt_desync_frames_bucket_total{bucket="gt_10"} 1360
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 6206
telemt_me_refill_failed_total 35
telemt_me_writer_restored_same_endpoint_total 6074
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 112
telemt_user_connections_total{user="hello"} 751606
telemt_user_connections_current{user="hello"} 1559
telemt_user_octets_from_client{user="hello"} 11777356200 (10.97 GB)
telemt_user_octets_to_client{user="hello"} 240159429948 (223.67 GB)
telemt_user_unique_ips_current{user="hello"} 549
telemt_user_unique_ips_recent_window{user="hello"} 229
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 44735.0 (12h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2442411
telemt_connections_bad_total 154059
telemt_connections_current 4245
telemt_connections_me_current 4245
telemt_handshake_timeouts_total 53744
telemt_upstream_connect_attempt_total 8491
telemt_upstream_connect_success_total 8334
telemt_upstream_connect_fail_total 157
telemt_upstream_connect_attempts_per_request{bucket="1"} 8491
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4173
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4137
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 157
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 8425
telemt_me_reconnect_success_total 6072
telemt_me_reader_eof_total 6458
telemt_me_idle_close_by_peer_total 6458
telemt_me_seq_mismatch_total 13
telemt_me_route_drop_no_conn_total 1105253
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2018878
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 35
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9266
telemt_desync_full_logged_total 3071
telemt_desync_suppressed_total 6195
telemt_desync_frames_bucket_total{bucket="1_2"} 1704
telemt_desync_frames_bucket_total{bucket="3_10"} 3619
telemt_desync_frames_bucket_total{bucket="gt_10"} 3943
telemt_pool_swap_total 33
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 6256
telemt_me_refill_failed_total 73
telemt_me_writer_restored_same_endpoint_total 6050
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 184
telemt_user_connections_total{user="hello"} 2018574
telemt_user_connections_current{user="hello"} 4245
telemt_user_octets_from_client{user="hello"} 31738877660 (29.56 GB)
telemt_user_octets_to_client{user="hello"} 729416409720 (679.32 GB)
telemt_user_unique_ips_current{user="hello"} 1432
telemt_user_unique_ips_recent_window{user="hello"} 619
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 44732.2 (12h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2111477
telemt_connections_bad_total 249459
telemt_connections_current 2900
telemt_connections_me_current 2900
telemt_handshake_timeouts_total 47447
telemt_upstream_connect_attempt_total 7989
telemt_upstream_connect_success_total 7989
telemt_upstream_connect_attempts_per_request{bucket="1"} 7989
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4199
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3775
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 19
telemt_me_reconnect_attempts_total 5762
telemt_me_reconnect_success_total 5725
telemt_me_reader_eof_total 6057
telemt_me_idle_close_by_peer_total 6057
telemt_me_route_drop_no_conn_total 1302005
telemt_me_route_drop_channel_closed_total 64
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1656011
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7120
telemt_desync_full_logged_total 2280
telemt_desync_suppressed_total 4840
telemt_desync_frames_bucket_total{bucket="1_2"} 1575
telemt_desync_frames_bucket_total{bucket="3_10"} 2633
telemt_desync_frames_bucket_total{bucket="gt_10"} 2912
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 5827
telemt_me_writer_restored_same_endpoint_total 5709
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 102
telemt_user_connections_total{user="hello"} 1654429
telemt_user_connections_current{user="hello"} 2900
telemt_user_octets_from_client{user="hello"} 24021899020 (22.37 GB)
telemt_user_octets_to_client{user="hello"} 720306475796 (670.84 GB)
telemt_user_unique_ips_current{user="hello"} 1023
telemt_user_unique_ips_recent_window{user="hello"} 450
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 44785.2 (12h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2089985
telemt_connections_bad_total 116880
telemt_connections_current 2890
telemt_connections_me_current 2890
telemt_relay_adaptive_promotions_total 1
telemt_relay_adaptive_hard_promotions_total 1
telemt_handshake_timeouts_total 54393
telemt_upstream_connect_attempt_total 16237
telemt_upstream_connect_success_total 16108
telemt_upstream_connect_fail_total 129
telemt_upstream_connect_attempts_per_request{bucket="1"} 16237
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11389
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4566
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 151
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 129
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 8982
telemt_me_reconnect_success_total 5687
telemt_me_reader_eof_total 6065
telemt_me_idle_close_by_peer_total 6064
telemt_me_route_drop_no_conn_total 1067314
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1578093
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5761
telemt_desync_full_logged_total 1959
telemt_desync_suppressed_total 3802
telemt_desync_frames_bucket_total{bucket="1_2"} 1194
telemt_desync_frames_bucket_total{bucket="3_10"} 2256
telemt_desync_frames_bucket_total{bucket="gt_10"} 2311
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 6000
telemt_me_refill_failed_total 97
telemt_me_writer_restored_same_endpoint_total 5663
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 272
telemt_me_writer_removed_unexpected_minus_restored_total 313
telemt_user_connections_total{user="hello"} 1584736
telemt_user_connections_current{user="hello"} 2890
telemt_user_octets_from_client{user="hello"} 18406546208 (17.14 GB)
telemt_user_octets_to_client{user="hello"} 459202482622 (427.67 GB)
telemt_user_msgs_from_client{user="hello"} 28643
telemt_user_msgs_to_client{user="hello"} 76631
telemt_user_unique_ips_current{user="hello"} 1001
telemt_user_unique_ips_recent_window{user="hello"} 455
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 44728.4 (12h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2480637
telemt_connections_bad_total 569049
telemt_connections_current 3318
telemt_connections_me_current 3318
telemt_handshake_timeouts_total 50583
telemt_upstream_connect_attempt_total 7852
telemt_upstream_connect_success_total 7798
telemt_upstream_connect_fail_total 54
telemt_upstream_connect_attempts_per_request{bucket="1"} 7852
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3967
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3804
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 54
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 6746
telemt_me_reconnect_success_total 5548
telemt_me_reader_eof_total 5898
telemt_me_idle_close_by_peer_total 5898
telemt_me_route_drop_no_conn_total 922598
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1624820
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7289
telemt_desync_full_logged_total 2275
telemt_desync_suppressed_total 5014
telemt_desync_frames_bucket_total{bucket="1_2"} 1476
telemt_desync_frames_bucket_total{bucket="3_10"} 3154
telemt_desync_frames_bucket_total{bucket="gt_10"} 2659
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 5667
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 5524
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 119
telemt_user_connections_total{user="hello"} 1623937
telemt_user_connections_current{user="hello"} 3318
telemt_user_octets_from_client{user="hello"} 28917980116 (26.93 GB)
telemt_user_octets_to_client{user="hello"} 683386182212 (636.45 GB)
telemt_user_unique_ips_current{user="hello"} 1132
telemt_user_unique_ips_recent_window{user="hello"} 494
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 44741.7 (12h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 437630
telemt_connections_bad_total 18278
telemt_connections_current 884
telemt_connections_me_current 884
telemt_handshake_timeouts_total 3438
telemt_upstream_connect_attempt_total 11246
telemt_upstream_connect_success_total 10961
telemt_upstream_connect_fail_total 285
telemt_upstream_connect_attempts_per_request{bucket="1"} 11246
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5468
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5492
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 285
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 14100
telemt_me_reconnect_success_total 8710
telemt_me_reader_eof_total 9244
telemt_me_idle_close_by_peer_total 9244
telemt_me_route_drop_no_conn_total 223125
telemt_me_route_drop_channel_closed_total 25
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 393840
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 726
telemt_desync_full_logged_total 249
telemt_desync_suppressed_total 477
telemt_desync_frames_bucket_total{bucket="1_2"} 172
telemt_desync_frames_bucket_total{bucket="3_10"} 282
telemt_desync_frames_bucket_total{bucket="gt_10"} 272
telemt_pool_swap_total 22
telemt_pool_stale_pick_total 194
telemt_me_writer_removed_unexpected_total 8951
telemt_me_refill_failed_total 167
telemt_me_writer_restored_same_endpoint_total 8680
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 241
telemt_user_connections_total{user="hello"} 393808
telemt_user_connections_current{user="hello"} 884
telemt_user_octets_from_client{user="hello"} 6257829680 (5.83 GB)
telemt_user_octets_to_client{user="hello"} 153144310016 (142.63 GB)
telemt_user_unique_ips_current{user="hello"} 330
telemt_user_unique_ips_recent_window{user="hello"} 131
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 44730.9 (12h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1661615
telemt_connections_bad_total 135538
telemt_connections_current 3023
telemt_connections_me_current 3023
telemt_handshake_timeouts_total 68364
telemt_upstream_connect_attempt_total 9037
telemt_upstream_connect_success_total 9036
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 9037
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4879
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4154
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 50
telemt_me_reconnect_attempts_total 8129
telemt_me_reconnect_success_total 6775
telemt_me_reader_eof_total 7175
telemt_me_idle_close_by_peer_total 7174
telemt_me_route_drop_no_conn_total 660325
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1386606
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7800
telemt_desync_full_logged_total 2544
telemt_desync_suppressed_total 5256
telemt_desync_frames_bucket_total{bucket="1_2"} 1465
telemt_desync_frames_bucket_total{bucket="3_10"} 2930
telemt_desync_frames_bucket_total{bucket="gt_10"} 3405
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 6899
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 6760
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 124
telemt_user_connections_total{user="hello"} 1385423
telemt_user_connections_current{user="hello"} 3023
telemt_user_octets_from_client{user="hello"} 18973280604 (17.67 GB)
telemt_user_octets_to_client{user="hello"} 669319820508 (623.35 GB)
telemt_user_unique_ips_current{user="hello"} 1009
telemt_user_unique_ips_recent_window{user="hello"} 431
```