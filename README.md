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

# Server Metrics 2026-03-17 06:04:12 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 40730.1 (11h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 233691
telemt_connections_bad_total 3330
telemt_handshake_timeouts_total 7661
telemt_upstream_connect_attempt_total 8567
telemt_upstream_connect_success_total 8521
telemt_upstream_connect_fail_total 46
telemt_upstream_connect_attempts_per_request{bucket="1"} 8567
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3889
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4627
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 46
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 6504
telemt_me_reconnect_success_total 6480
telemt_me_reader_eof_total 6899
telemt_me_idle_close_by_peer_total 6899
telemt_me_route_drop_no_conn_total 72527
telemt_me_route_drop_channel_closed_total 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 211096
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1478
telemt_desync_full_logged_total 478
telemt_desync_suppressed_total 1000
telemt_desync_frames_bucket_total{bucket="1_2"} 347
telemt_desync_frames_bucket_total{bucket="3_10"} 761
telemt_desync_frames_bucket_total{bucket="gt_10"} 370
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 6544
telemt_me_writer_restored_same_endpoint_total 6459
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 210890
telemt_user_connections_current{user="hello"} 573
telemt_user_octets_from_client{user="hello"} 2871335940 (2.67 GB)
telemt_user_octets_to_client{user="hello"} 92968961692 (86.58 GB)
telemt_user_unique_ips_current{user="hello"} 227
telemt_user_unique_ips_recent_window{user="hello"} 80
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 40981.3 (11h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 133950
telemt_connections_bad_total 2207
telemt_handshake_timeouts_total 10467
telemt_upstream_connect_attempt_total 11302
telemt_upstream_connect_success_total 11156
telemt_upstream_connect_fail_total 146
telemt_upstream_connect_attempts_per_request{bucket="1"} 11302
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4663
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6417
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 76
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 146
telemt_me_reconnect_attempts_total 10300
telemt_me_reconnect_success_total 9125
telemt_me_reader_eof_total 9655
telemt_me_idle_close_by_peer_total 9655
telemt_me_route_drop_no_conn_total 50717
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 116391
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 314
telemt_desync_full_logged_total 114
telemt_desync_suppressed_total 200
telemt_desync_frames_bucket_total{bucket="1_2"} 79
telemt_desync_frames_bucket_total{bucket="3_10"} 152
telemt_desync_frames_bucket_total{bucket="gt_10"} 83
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 9244
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 9109
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 119
telemt_user_connections_total{user="hello"} 116402
telemt_user_connections_current{user="hello"} 340
telemt_user_octets_from_client{user="hello"} 1448028216 (1.35 GB)
telemt_user_octets_to_client{user="hello"} 49785406528 (46.37 GB)
telemt_user_unique_ips_current{user="hello"} 111
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 40757.8 (11h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 80125
telemt_connections_bad_total 1108
telemt_handshake_timeouts_total 2632
telemt_upstream_connect_attempt_total 10998
telemt_upstream_connect_success_total 10939
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 10997
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4841
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6036
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 8928
telemt_me_reconnect_success_total 8878
telemt_me_reader_eof_total 9505
telemt_me_idle_close_by_peer_total 9505
telemt_me_route_drop_no_conn_total 27012
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 68911
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 46
telemt_desync_full_logged_total 21
telemt_desync_suppressed_total 25
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 15
telemt_desync_frames_bucket_total{bucket="gt_10"} 18
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 8986
telemt_me_writer_restored_same_endpoint_total 8867
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 108
telemt_user_connections_total{user="hello"} 68894
telemt_user_connections_current{user="hello"} 202
telemt_user_octets_from_client{user="hello"} 6057528304 (5.64 GB)
telemt_user_octets_to_client{user="hello"} 22531414236 (20.98 GB)
telemt_user_unique_ips_current{user="hello"} 69
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 40817.0 (11h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 139364
telemt_connections_bad_total 3783
telemt_handshake_timeouts_total 5885
telemt_upstream_connect_attempt_total 9301
telemt_upstream_connect_success_total 9221
telemt_upstream_connect_fail_total 80
telemt_upstream_connect_attempts_per_request{bucket="1"} 9301
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4295
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4866
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 80
telemt_me_reconnect_attempts_total 7178
telemt_me_reconnect_success_total 7123
telemt_me_reader_eof_total 7585
telemt_me_idle_close_by_peer_total 7585
telemt_me_route_drop_no_conn_total 46472
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 125620
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 236
telemt_desync_full_logged_total 72
telemt_desync_suppressed_total 164
telemt_desync_frames_bucket_total{bucket="1_2"} 53
telemt_desync_frames_bucket_total{bucket="3_10"} 95
telemt_desync_frames_bucket_total{bucket="gt_10"} 88
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 7227
telemt_me_writer_restored_same_endpoint_total 7116
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 104
telemt_user_connections_total{user="hello"} 125637
telemt_user_connections_current{user="hello"} 377
telemt_user_octets_from_client{user="hello"} 1369580538 (1.28 GB)
telemt_user_octets_to_client{user="hello"} 60783171305 (56.61 GB)
telemt_user_msgs_from_client{user="hello"} 65
telemt_user_msgs_to_client{user="hello"} 189
telemt_user_unique_ips_current{user="hello"} 125
telemt_user_unique_ips_recent_window{user="hello"} 53
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 40788.9 (11h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 105651
telemt_connections_bad_total 30632
telemt_handshake_timeouts_total 2045
telemt_upstream_connect_attempt_total 12162
telemt_upstream_connect_success_total 11999
telemt_upstream_connect_fail_total 163
telemt_upstream_connect_attempts_per_request{bucket="1"} 12162
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5391
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6428
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 180
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 163
telemt_me_reconnect_attempts_total 12104
telemt_me_reconnect_success_total 9839
telemt_me_reader_eof_total 10394
telemt_me_idle_close_by_peer_total 10394
telemt_me_route_drop_no_conn_total 27292
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 70111
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 39
telemt_desync_full_logged_total 17
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 14
telemt_desync_frames_bucket_total{bucket="gt_10"} 12
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 10040
telemt_me_refill_failed_total 69
telemt_me_writer_restored_same_endpoint_total 9831
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 201
telemt_user_connections_total{user="hello"} 70208
telemt_user_connections_current{user="hello"} 171
telemt_user_octets_from_client{user="hello"} 760796867 (725.55 MB)
telemt_user_octets_to_client{user="hello"} 30375530586 (28.29 GB)
telemt_user_msgs_from_client{user="hello"} 265
telemt_user_msgs_to_client{user="hello"} 707
telemt_user_unique_ips_current{user="hello"} 74
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 40950.0 (11h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 251236
telemt_connections_bad_total 30380
telemt_handshake_timeouts_total 2079
telemt_upstream_connect_attempt_total 8406
telemt_upstream_connect_success_total 8361
telemt_upstream_connect_fail_total 45
telemt_upstream_connect_attempts_per_request{bucket="1"} 8406
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3997
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4354
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 45
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 6350
telemt_me_reconnect_success_total 6321
telemt_me_reader_eof_total 6775
telemt_me_idle_close_by_peer_total 6775
telemt_me_route_drop_no_conn_total 208349
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 287071
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 243
telemt_desync_full_logged_total 122
telemt_desync_suppressed_total 121
telemt_desync_frames_bucket_total{bucket="1_2"} 83
telemt_desync_frames_bucket_total{bucket="3_10"} 85
telemt_desync_frames_bucket_total{bucket="gt_10"} 75
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 6414
telemt_me_writer_restored_same_endpoint_total 6311
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 93
telemt_user_connections_total{user="hello"} 209323
telemt_user_connections_current{user="hello"} 655
telemt_user_octets_from_client{user="hello"} 3150578916 (2.93 GB)
telemt_user_octets_to_client{user="hello"} 150179083876 (139.87 GB)
telemt_user_unique_ips_current{user="hello"} 228
telemt_user_unique_ips_recent_window{user="hello"} 93
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 28956.3 (8h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 727
telemt_connections_bad_total 191
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 14301
telemt_upstream_connect_success_total 14301
telemt_upstream_connect_attempts_per_request{bucket="1"} 14301
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8191
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6103
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_reconnect_attempts_total 12845
telemt_me_reconnect_success_total 12774
telemt_me_reader_eof_total 14029
telemt_me_idle_close_by_peer_total 14029
telemt_me_route_drop_no_conn_total 77
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 528
telemt_me_writer_pick_total{mode="p2c",result="full"} 3
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 12890
telemt_me_writer_restored_same_endpoint_total 12774
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 116
telemt_user_connections_total{user="hello"} 528
telemt_user_connections_current{user="hello"} 17
telemt_user_octets_from_client{user="hello"} 182667184 (174.21 MB)
telemt_user_octets_to_client{user="hello"} 7168352776 (6.68 GB)
telemt_user_unique_ips_current{user="hello"} 5
telemt_user_unique_ips_recent_window{user="hello"} 1
```