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

# Server Metrics 2026-03-16 08:30:02 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 123332.7 (34h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 576184
telemt_connections_bad_total 6392
telemt_handshake_timeouts_total 20427
telemt_upstream_connect_attempt_total 28709
telemt_upstream_connect_success_total 28574
telemt_upstream_connect_fail_total 135
telemt_upstream_connect_attempts_per_request{bucket="1"} 28709
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12706
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15821
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 135
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 51
telemt_me_reconnect_attempts_total 25923
telemt_me_reconnect_success_total 22487
telemt_me_reader_eof_total 24059
telemt_me_idle_close_by_peer_total 24059
telemt_me_route_drop_no_conn_total 529072
telemt_me_route_drop_channel_closed_total 85
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 570951
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2750
telemt_desync_full_logged_total 1080
telemt_desync_suppressed_total 1670
telemt_desync_frames_bucket_total{bucket="1_2"} 603
telemt_desync_frames_bucket_total{bucket="3_10"} 1059
telemt_desync_frames_bucket_total{bucket="gt_10"} 1088
telemt_pool_swap_total 120
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 22844
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 22453
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 357
telemt_user_connections_total{user="hello"} 509769
telemt_user_connections_current{user="hello"} 505
telemt_user_octets_from_client{user="hello"} 9922160148 (9.24 GB)
telemt_user_octets_to_client{user="hello"} 322846998104 (300.67 GB)
telemt_user_unique_ips_current{user="hello"} 151
telemt_user_unique_ips_recent_window{user="hello"} 73
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 123339.1 (34h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 232667
telemt_connections_bad_total 3158
telemt_handshake_timeouts_total 15179
telemt_upstream_connect_attempt_total 33151
telemt_upstream_connect_success_total 33076
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 33151
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14264
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18164
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 648
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 1307
telemt_me_reconnect_attempts_total 35847
telemt_me_reconnect_success_total 26558
telemt_me_reader_eof_total 28483
telemt_me_idle_close_by_peer_total 28482
telemt_me_route_drop_no_conn_total 112854
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 206193
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 160
telemt_desync_full_logged_total 45
telemt_desync_suppressed_total 115
telemt_desync_frames_bucket_total{bucket="1_2"} 31
telemt_desync_frames_bucket_total{bucket="3_10"} 60
telemt_desync_frames_bucket_total{bucket="gt_10"} 69
telemt_pool_swap_total 106
telemt_me_writer_removed_unexpected_total 27211
telemt_me_refill_failed_total 282
telemt_me_writer_restored_same_endpoint_total 26542
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 653
telemt_user_connections_total{user="hello"} 205732
telemt_user_connections_current{user="hello"} 292
telemt_user_octets_from_client{user="hello"} 4639300573 (4.32 GB)
telemt_user_octets_to_client{user="hello"} 115814843504 (107.86 GB)
telemt_user_msgs_from_client{user="hello"} 721
telemt_user_msgs_to_client{user="hello"} 1482
telemt_user_unique_ips_current{user="hello"} 92
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 123331.7 (34h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 247397
telemt_connections_bad_total 5737
telemt_handshake_timeouts_total 4632
telemt_upstream_connect_attempt_total 34347
telemt_upstream_connect_success_total 34339
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 34347
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14875
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19410
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 41
telemt_me_reconnect_attempts_total 35580
telemt_me_reconnect_success_total 28172
telemt_me_reader_eof_total 30296
telemt_me_idle_close_by_peer_total 30295
telemt_me_route_drop_no_conn_total 86379
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 199018
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 100
telemt_desync_full_logged_total 39
telemt_desync_suppressed_total 61
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 45
telemt_desync_frames_bucket_total{bucket="gt_10"} 43
telemt_pool_swap_total 112
telemt_me_writer_removed_unexpected_total 28679
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 28164
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 507
telemt_user_connections_total{user="hello"} 198720
telemt_user_connections_current{user="hello"} 171
telemt_user_octets_from_client{user="hello"} 17543083657 (16.34 GB)
telemt_user_octets_to_client{user="hello"} 113820208940 (106.00 GB)
telemt_user_msgs_from_client{user="hello"} 7
telemt_user_msgs_to_client{user="hello"} 46
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 123330.9 (34h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 346704
telemt_connections_bad_total 1352
telemt_handshake_timeouts_total 3003
telemt_upstream_connect_attempt_total 28544
telemt_upstream_connect_success_total 28511
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 28544
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13663
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14691
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 15
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 142
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 22541
telemt_me_reconnect_success_total 22399
telemt_me_reader_eof_total 23915
telemt_me_idle_close_by_peer_total 23914
telemt_me_route_drop_no_conn_total 121329
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 319864
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1149
telemt_desync_full_logged_total 398
telemt_desync_suppressed_total 751
telemt_desync_frames_bucket_total{bucket="1_2"} 236
telemt_desync_frames_bucket_total{bucket="3_10"} 490
telemt_desync_frames_bucket_total{bucket="gt_10"} 423
telemt_pool_swap_total 118
telemt_me_writer_removed_unexpected_total 22693
telemt_me_writer_restored_same_endpoint_total 22388
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 294
telemt_user_connections_total{user="hello"} 319753
telemt_user_connections_current{user="hello"} 328
telemt_user_octets_from_client{user="hello"} 5020627370 (4.68 GB)
telemt_user_octets_to_client{user="hello"} 134516018780 (125.28 GB)
telemt_user_msgs_from_client{user="hello"} 25
telemt_user_msgs_to_client{user="hello"} 50
telemt_user_unique_ips_current{user="hello"} 107
telemt_user_unique_ips_recent_window{user="hello"} 51
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 98402.6 (27h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 225079
telemt_connections_bad_total 36460
telemt_handshake_timeouts_total 3734
telemt_upstream_connect_attempt_total 28102
telemt_upstream_connect_success_total 27949
telemt_upstream_connect_fail_total 152
telemt_upstream_connect_attempts_per_request{bucket="1"} 28101
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12383
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15421
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 145
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 152
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 117380
telemt_me_reconnect_success_total 22885
telemt_me_reader_eof_total 24318
telemt_me_idle_close_by_peer_total 24318
telemt_me_route_drop_no_conn_total 70271
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 178459
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 562
telemt_desync_full_logged_total 135
telemt_desync_suppressed_total 427
telemt_desync_frames_bucket_total{bucket="1_2"} 86
telemt_desync_frames_bucket_total{bucket="3_10"} 233
telemt_desync_frames_bucket_total{bucket="gt_10"} 243
telemt_pool_swap_total 85
telemt_me_writer_removed_unexpected_total 23075
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 22781
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 190
telemt_user_connections_total{user="hello"} 178078
telemt_user_connections_current{user="hello"} 138
telemt_user_octets_from_client{user="hello"} 2397687433 (2.23 GB)
telemt_user_octets_to_client{user="hello"} 73962636555 (68.88 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 123330.2 (34h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 818271
telemt_connections_bad_total 71706
telemt_handshake_timeouts_total 9106
telemt_upstream_connect_attempt_total 25819
telemt_upstream_connect_success_total 25683
telemt_upstream_connect_fail_total 136
telemt_upstream_connect_attempts_per_request{bucket="1"} 25819
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12288
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13353
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 136
telemt_me_keepalive_timeout_total 63
telemt_me_reconnect_attempts_total 20909
telemt_me_reconnect_success_total 19560
telemt_me_reader_eof_total 20889
telemt_me_idle_close_by_peer_total 20889
telemt_me_route_drop_no_conn_total 647993
telemt_me_route_drop_channel_closed_total 112
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 813534
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 336
telemt_desync_full_logged_total 96
telemt_desync_suppressed_total 240
telemt_desync_frames_bucket_total{bucket="1_2"} 171
telemt_desync_frames_bucket_total{bucket="3_10"} 98
telemt_desync_frames_bucket_total{bucket="gt_10"} 67
telemt_pool_swap_total 117
telemt_me_writer_removed_unexpected_total 19836
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 19533
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 276
telemt_user_connections_total{user="hello"} 672172
telemt_user_connections_current{user="hello"} 576
telemt_user_octets_from_client{user="hello"} 14670811140 (13.66 GB)
telemt_user_octets_to_client{user="hello"} 405292192100 (377.46 GB)
telemt_user_unique_ips_current{user="hello"} 216
telemt_user_unique_ips_recent_window{user="hello"} 96
```