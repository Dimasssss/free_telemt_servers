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

# Server Metrics 2026-03-13 01:55:40 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 66136.6 (18h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 267126
telemt_connections_bad_total 2804
telemt_handshake_timeouts_total 5634
telemt_upstream_connect_attempt_total 16758
telemt_upstream_connect_success_total 16687
telemt_upstream_connect_fail_total 71
telemt_upstream_connect_attempts_per_request{bucket="1"} 16758
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7383
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9258
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 71
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1513
telemt_me_reconnect_attempts_total 16826
telemt_me_reconnect_success_total 13348
telemt_me_reader_eof_total 14251
telemt_me_idle_close_by_peer_total 14250
telemt_me_route_drop_no_conn_total 82734
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 221813
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 734
telemt_desync_full_logged_total 277
telemt_desync_suppressed_total 457
telemt_desync_frames_bucket_total{bucket="1_2"} 132
telemt_desync_frames_bucket_total{bucket="3_10"} 272
telemt_desync_frames_bucket_total{bucket="gt_10"} 330
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 13600
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 13332
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 252
telemt_user_connections_total{user="hello"} 221580
telemt_user_connections_current{user="hello"} 215
telemt_user_octets_from_client{user="hello"} 3966295232 (3.69 GB)
telemt_user_octets_to_client{user="hello"} 110315776724 (102.74 GB)
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 66029.6 (18h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 124148
telemt_connections_bad_total 738
telemt_handshake_timeouts_total 975
telemt_upstream_connect_attempt_total 36773
telemt_upstream_connect_success_total 36323
telemt_upstream_connect_fail_total 450
telemt_upstream_connect_attempts_per_request{bucket="1"} 36773
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22639
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13183
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 501
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 450
telemt_me_keepalive_timeout_total 470
telemt_me_reconnect_attempts_total 60715
telemt_me_reconnect_success_total 16501
telemt_me_reader_eof_total 18344
telemt_me_idle_close_by_peer_total 18344
telemt_me_route_drop_no_conn_total 44387
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 101361
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 31
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 18004
telemt_me_refill_failed_total 1380
telemt_me_writer_restored_same_endpoint_total 16486
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1503
telemt_user_connections_total{user="hello"} 117861
telemt_user_connections_current{user="hello"} 60
telemt_user_octets_from_client{user="hello"} 1255484544 (1.17 GB)
telemt_user_octets_to_client{user="hello"} 35512699555 (33.07 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 65993.2 (18h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 149535
telemt_connections_bad_total 1730
telemt_handshake_timeouts_total 2363
telemt_upstream_connect_attempt_total 18212
telemt_upstream_connect_success_total 18210
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 18212
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8460
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9729
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 369
telemt_me_reconnect_attempts_total 16004
telemt_me_reconnect_success_total 14846
telemt_me_reader_eof_total 15880
telemt_me_idle_close_by_peer_total 15880
telemt_me_route_drop_no_conn_total 56912
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 139855
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 52
telemt_desync_full_logged_total 26
telemt_desync_suppressed_total 26
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 13
telemt_desync_frames_bucket_total{bucket="gt_10"} 36
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 15014
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 14826
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 168
telemt_user_connections_total{user="hello"} 139807
telemt_user_connections_current{user="hello"} 102
telemt_user_octets_from_client{user="hello"} 2703198264 (2.52 GB)
telemt_user_octets_to_client{user="hello"} 65697792232 (61.19 GB)
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 65968.8 (18h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 213502
telemt_connections_bad_total 13346
telemt_handshake_timeouts_total 1427
telemt_upstream_connect_attempt_total 30446
telemt_upstream_connect_success_total 20665
telemt_upstream_connect_fail_total 9781
telemt_upstream_connect_attempts_per_request{bucket="1"} 30446
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10530
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9971
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 156
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9781
telemt_me_keepalive_timeout_total 3222
telemt_me_reconnect_attempts_total 51376
telemt_me_reconnect_success_total 14476
telemt_me_reader_eof_total 16128
telemt_me_idle_close_by_peer_total 16121
telemt_me_route_drop_no_conn_total 77067
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 177038
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 499
telemt_desync_full_logged_total 143
telemt_desync_suppressed_total 356
telemt_desync_frames_bucket_total{bucket="1_2"} 124
telemt_desync_frames_bucket_total{bucket="3_10"} 186
telemt_desync_frames_bucket_total{bucket="gt_10"} 189
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 15836
telemt_me_refill_failed_total 1149
telemt_me_writer_restored_same_endpoint_total 14466
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1360
telemt_user_connections_total{user="hello"} 179790
telemt_user_connections_current{user="hello"} 120
telemt_user_octets_from_client{user="hello"} 3044463978 (2.84 GB)
telemt_user_octets_to_client{user="hello"} 73664631629 (68.61 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 16140.4 (4h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14380
telemt_connections_bad_total 3039
telemt_handshake_timeouts_total 26
telemt_upstream_connect_attempt_total 4982
telemt_upstream_connect_success_total 4939
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 4982
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2176
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2744
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_timeout_total 99
telemt_me_reconnect_attempts_total 4140
telemt_me_reconnect_success_total 4129
telemt_me_reader_eof_total 4411
telemt_me_idle_close_by_peer_total 4411
telemt_me_route_drop_no_conn_total 4400
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10868
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 4158
telemt_me_writer_restored_same_endpoint_total 4113
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 10868
telemt_user_connections_current{user="hello"} 39
telemt_user_octets_from_client{user="hello"} 55915232 (53.32 MB)
telemt_user_octets_to_client{user="hello"} 5257617852 (4.90 GB)
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 65925.3 (18h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 358665
telemt_connections_bad_total 6579
telemt_handshake_timeouts_total 2728
telemt_upstream_connect_attempt_total 14025
telemt_upstream_connect_success_total 13947
telemt_upstream_connect_fail_total 78
telemt_upstream_connect_attempts_per_request{bucket="1"} 14025
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6526
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7401
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 78
telemt_me_keepalive_timeout_total 1346
telemt_me_reconnect_attempts_total 14263
telemt_me_reconnect_success_total 10643
telemt_me_reader_eof_total 11425
telemt_me_idle_close_by_peer_total 11423
telemt_me_route_drop_no_conn_total 160568
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 350746
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 301
telemt_desync_full_logged_total 118
telemt_desync_suppressed_total 183
telemt_desync_frames_bucket_total{bucket="1_2"} 75
telemt_desync_frames_bucket_total{bucket="3_10"} 112
telemt_desync_frames_bucket_total{bucket="gt_10"} 114
telemt_pool_swap_total 59
telemt_me_writer_removed_unexpected_total 10885
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 10636
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 242
telemt_user_connections_total{user="hello"} 339045
telemt_user_connections_current{user="hello"} 216
telemt_user_octets_from_client{user="hello"} 5742871532 (5.35 GB)
telemt_user_octets_to_client{user="hello"} 189500618432 (176.49 GB)
telemt_user_unique_ips_current{user="hello"} 84
telemt_user_unique_ips_recent_window{user="hello"} 27
```