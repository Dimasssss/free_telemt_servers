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

# Server Metrics 2026-03-13 14:44:38 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 112279.1 (31h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 464941
telemt_connections_bad_total 3219
telemt_handshake_timeouts_total 8623
telemt_upstream_connect_attempt_total 28208
telemt_upstream_connect_success_total 28074
telemt_upstream_connect_fail_total 134
telemt_upstream_connect_attempts_per_request{bucket="1"} 28208
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12666
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15345
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 134
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2428
telemt_me_reconnect_attempts_total 25994
telemt_me_reconnect_success_total 22462
telemt_me_reader_eof_total 23992
telemt_me_idle_close_by_peer_total 23991
telemt_me_route_drop_no_conn_total 151376
telemt_me_route_drop_channel_closed_total 28
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 407324
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1343
telemt_desync_full_logged_total 476
telemt_desync_suppressed_total 867
telemt_desync_frames_bucket_total{bucket="1_2"} 292
telemt_desync_frames_bucket_total{bucket="3_10"} 487
telemt_desync_frames_bucket_total{bucket="gt_10"} 564
telemt_pool_swap_total 101
telemt_me_writer_removed_unexpected_total 22806
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 22446
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 344
telemt_user_connections_total{user="hello"} 406901
telemt_user_connections_current{user="hello"} 387
telemt_user_octets_from_client{user="hello"} 7336562836 (6.83 GB)
telemt_user_octets_to_client{user="hello"} 187812967752 (174.91 GB)
telemt_user_unique_ips_current{user="hello"} 113
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 112172.2 (31h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 220820
telemt_connections_bad_total 1830
telemt_handshake_timeouts_total 1552
telemt_upstream_connect_attempt_total 78980
telemt_upstream_connect_success_total 78227
telemt_upstream_connect_fail_total 753
telemt_upstream_connect_attempts_per_request{bucket="1"} 78980
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 54442
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23021
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 764
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 753
telemt_me_keepalive_timeout_total 1399
telemt_me_reconnect_attempts_total 109426
telemt_me_reconnect_success_total 26022
telemt_me_reader_eof_total 29388
telemt_me_idle_close_by_peer_total 29388
telemt_me_route_drop_no_conn_total 80276
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 162283
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 26
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
telemt_me_writer_removed_unexpected_total 28852
telemt_me_refill_failed_total 2602
telemt_me_writer_restored_same_endpoint_total 26005
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 2830
telemt_user_connections_total{user="hello"} 208671
telemt_user_connections_current{user="hello"} 207
telemt_user_octets_from_client{user="hello"} 2101424558 (1.96 GB)
telemt_user_octets_to_client{user="hello"} 66609250851 (62.03 GB)
telemt_user_msgs_from_client{user="hello"} 684266
telemt_user_msgs_to_client{user="hello"} 4616895
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 112135.6 (31h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 267137
telemt_connections_bad_total 2212
telemt_handshake_timeouts_total 11621
telemt_upstream_connect_attempt_total 30211
telemt_upstream_connect_success_total 30207
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 30211
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13999
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16177
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2290
telemt_me_reconnect_attempts_total 25774
telemt_me_reconnect_success_total 24556
telemt_me_reader_eof_total 26308
telemt_me_idle_close_by_peer_total 26308
telemt_me_route_drop_no_conn_total 96748
telemt_me_route_drop_channel_closed_total 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 243743
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 96
telemt_desync_full_logged_total 45
telemt_desync_suppressed_total 51
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 32
telemt_desync_frames_bucket_total{bucket="gt_10"} 57
telemt_pool_swap_total 101
telemt_me_writer_removed_unexpected_total 24824
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 24536
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 268
telemt_user_connections_total{user="hello"} 243658
telemt_user_connections_current{user="hello"} 137
telemt_user_octets_from_client{user="hello"} 9521066892 (8.87 GB)
telemt_user_octets_to_client{user="hello"} 105142105004 (97.92 GB)
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 112111.2 (31h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 366389
telemt_connections_bad_total 15044
telemt_handshake_timeouts_total 3639
telemt_upstream_connect_attempt_total 42226
telemt_upstream_connect_success_total 32084
telemt_upstream_connect_fail_total 10142
telemt_upstream_connect_attempts_per_request{bucket="1"} 42226
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16201
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15663
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 211
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10142
telemt_me_keepalive_timeout_total 4145
telemt_me_reconnect_attempts_total 98219
telemt_me_reconnect_success_total 23429
telemt_me_reader_eof_total 26468
telemt_me_idle_close_by_peer_total 26461
telemt_me_route_drop_no_conn_total 131239
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 316715
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1228
telemt_desync_full_logged_total 363
telemt_desync_suppressed_total 865
telemt_desync_frames_bucket_total{bucket="1_2"} 303
telemt_desync_frames_bucket_total{bucket="3_10"} 460
telemt_desync_frames_bucket_total{bucket="gt_10"} 465
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 26066
telemt_me_refill_failed_total 2332
telemt_me_writer_restored_same_endpoint_total 23419
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 2637
telemt_user_connections_total{user="hello"} 319625
telemt_user_connections_current{user="hello"} 203
telemt_user_octets_from_client{user="hello"} 6844053318 (6.37 GB)
telemt_user_octets_to_client{user="hello"} 120446775761 (112.17 GB)
telemt_user_msgs_from_client{user="hello"} 68310
telemt_user_msgs_to_client{user="hello"} 114408
telemt_user_unique_ips_current{user="hello"} 65
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 62282.7 (17h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 95712
telemt_connections_bad_total 12514
telemt_handshake_timeouts_total 1217
telemt_upstream_connect_attempt_total 25579
telemt_upstream_connect_success_total 25364
telemt_upstream_connect_fail_total 215
telemt_upstream_connect_attempts_per_request{bucket="1"} 25579
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13276
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12018
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 70
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 215
telemt_me_keepalive_timeout_total 1033
telemt_me_reconnect_attempts_total 27242
telemt_me_reconnect_success_total 17319
telemt_me_reader_eof_total 18575
telemt_me_idle_close_by_peer_total 18575
telemt_me_route_drop_no_conn_total 28523
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 74027
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 318
telemt_desync_full_logged_total 65
telemt_desync_suppressed_total 253
telemt_desync_frames_bucket_total{bucket="1_2"} 41
telemt_desync_frames_bucket_total{bucket="3_10"} 161
telemt_desync_frames_bucket_total{bucket="gt_10"} 116
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 17779
telemt_me_refill_failed_total 308
telemt_me_writer_restored_same_endpoint_total 17301
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 460
telemt_user_connections_total{user="hello"} 78927
telemt_user_connections_current{user="hello"} 123
telemt_user_octets_from_client{user="hello"} 925458073 (882.59 MB)
telemt_user_octets_to_client{user="hello"} 23048715947 (21.47 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 112067.8 (31h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 663497
telemt_connections_bad_total 18506
telemt_handshake_timeouts_total 20847
telemt_upstream_connect_attempt_total 23584
telemt_upstream_connect_success_total 23466
telemt_upstream_connect_fail_total 118
telemt_upstream_connect_attempts_per_request{bucket="1"} 23584
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10997
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12444
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 118
telemt_me_keepalive_timeout_total 2532
telemt_me_reconnect_attempts_total 22518
telemt_me_reconnect_success_total 17893
telemt_me_reader_eof_total 19202
telemt_me_idle_close_by_peer_total 19199
telemt_me_route_drop_no_conn_total 319196
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 628927
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 481
telemt_desync_full_logged_total 182
telemt_desync_suppressed_total 299
telemt_desync_frames_bucket_total{bucket="1_2"} 114
telemt_desync_frames_bucket_total{bucket="3_10"} 178
telemt_desync_frames_bucket_total{bucket="gt_10"} 189
telemt_pool_swap_total 103
telemt_me_writer_removed_unexpected_total 18268
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 17886
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 375
telemt_user_connections_total{user="hello"} 601876
telemt_user_connections_current{user="hello"} 534
telemt_user_octets_from_client{user="hello"} 10382336080 (9.67 GB)
telemt_user_octets_to_client{user="hello"} 313400845236 (291.88 GB)
telemt_user_unique_ips_current{user="hello"} 183
telemt_user_unique_ips_recent_window{user="hello"} 77
```