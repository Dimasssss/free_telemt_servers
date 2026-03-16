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

# Server Metrics 2026-03-16 04:55:31 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 110462.4 (30h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 472590
telemt_connections_bad_total 5425
telemt_handshake_timeouts_total 15993
telemt_upstream_connect_attempt_total 26337
telemt_upstream_connect_success_total 26217
telemt_upstream_connect_fail_total 120
telemt_upstream_connect_attempts_per_request{bucket="1"} 26337
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11608
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14562
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 120
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 24180
telemt_me_reconnect_success_total 20754
telemt_me_reader_eof_total 22200
telemt_me_idle_close_by_peer_total 22200
telemt_me_route_drop_no_conn_total 505922
telemt_me_route_drop_channel_closed_total 82
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 493216
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2422
telemt_desync_full_logged_total 962
telemt_desync_suppressed_total 1460
telemt_desync_frames_bucket_total{bucket="1_2"} 489
telemt_desync_frames_bucket_total{bucket="3_10"} 950
telemt_desync_frames_bucket_total{bucket="gt_10"} 983
telemt_pool_swap_total 106
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 21085
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 20720
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 331
telemt_user_connections_total{user="hello"} 432067
telemt_user_connections_current{user="hello"} 326
telemt_user_octets_from_client{user="hello"} 8677176000 (8.08 GB)
telemt_user_octets_to_client{user="hello"} 299352104260 (278.79 GB)
telemt_user_unique_ips_current{user="hello"} 121
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 110468.7 (30h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 190858
telemt_connections_bad_total 2993
telemt_handshake_timeouts_total 14750
telemt_upstream_connect_attempt_total 29947
telemt_upstream_connect_success_total 29872
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 29947
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12994
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16269
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 609
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 1307
telemt_me_reconnect_attempts_total 30905
telemt_me_reconnect_success_total 23996
telemt_me_reader_eof_total 25718
telemt_me_idle_close_by_peer_total 25717
telemt_me_route_drop_no_conn_total 96515
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 166179
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 25
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 16
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 9
telemt_pool_swap_total 97
telemt_me_writer_removed_unexpected_total 24546
telemt_me_refill_failed_total 208
telemt_me_writer_restored_same_endpoint_total 23980
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 550
telemt_user_connections_total{user="hello"} 165722
telemt_user_connections_current{user="hello"} 104
telemt_user_octets_from_client{user="hello"} 3556881333 (3.31 GB)
telemt_user_octets_to_client{user="hello"} 87244489204 (81.25 GB)
telemt_user_msgs_from_client{user="hello"} 721
telemt_user_msgs_to_client{user="hello"} 1482
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 110461.3 (30h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 212600
telemt_connections_bad_total 3738
telemt_handshake_timeouts_total 4162
telemt_upstream_connect_attempt_total 31078
telemt_upstream_connect_success_total 31070
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 31078
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13431
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17586
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 32935
telemt_me_reconnect_success_total 25542
telemt_me_reader_eof_total 27514
telemt_me_idle_close_by_peer_total 27513
telemt_me_route_drop_no_conn_total 75272
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 167689
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 65
telemt_desync_full_logged_total 26
telemt_desync_suppressed_total 39
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 32
telemt_desync_frames_bucket_total{bucket="gt_10"} 27
telemt_pool_swap_total 101
telemt_me_writer_removed_unexpected_total 26025
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 25534
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 483
telemt_user_connections_total{user="hello"} 167422
telemt_user_connections_current{user="hello"} 120
telemt_user_octets_from_client{user="hello"} 16493768085 (15.36 GB)
telemt_user_octets_to_client{user="hello"} 103996063704 (96.85 GB)
telemt_user_msgs_from_client{user="hello"} 7
telemt_user_msgs_to_client{user="hello"} 46
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 110461.0 (30h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 278752
telemt_connections_bad_total 1249
telemt_handshake_timeouts_total 2327
telemt_upstream_connect_attempt_total 25815
telemt_upstream_connect_success_total 25789
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 25815
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12336
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13318
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 122
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 20446
telemt_me_reconnect_success_total 20322
telemt_me_reader_eof_total 21704
telemt_me_idle_close_by_peer_total 21703
telemt_me_route_drop_no_conn_total 102220
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 257163
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 886
telemt_desync_full_logged_total 316
telemt_desync_suppressed_total 570
telemt_desync_frames_bucket_total{bucket="1_2"} 175
telemt_desync_frames_bucket_total{bucket="3_10"} 386
telemt_desync_frames_bucket_total{bucket="gt_10"} 325
telemt_pool_swap_total 108
telemt_me_writer_removed_unexpected_total 20576
telemt_me_writer_restored_same_endpoint_total 20311
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 254
telemt_user_connections_total{user="hello"} 257051
telemt_user_connections_current{user="hello"} 187
telemt_user_octets_from_client{user="hello"} 4326665848 (4.03 GB)
telemt_user_octets_to_client{user="hello"} 114945332344 (107.05 GB)
telemt_user_unique_ips_current{user="hello"} 70
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 85532.6 (23h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 186481
telemt_connections_bad_total 32252
telemt_handshake_timeouts_total 3370
telemt_upstream_connect_attempt_total 24594
telemt_upstream_connect_success_total 24460
telemt_upstream_connect_fail_total 134
telemt_upstream_connect_attempts_per_request{bucket="1"} 24594
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10873
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13451
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 136
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 134
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 114532
telemt_me_reconnect_success_total 20057
telemt_me_reader_eof_total 21291
telemt_me_idle_close_by_peer_total 21291
telemt_me_route_drop_no_conn_total 59291
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 146188
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 349
telemt_desync_full_logged_total 84
telemt_desync_suppressed_total 265
telemt_desync_frames_bucket_total{bucket="1_2"} 52
telemt_desync_frames_bucket_total{bucket="3_10"} 133
telemt_desync_frames_bucket_total{bucket="gt_10"} 164
telemt_pool_swap_total 73
telemt_me_writer_removed_unexpected_total 20217
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 19953
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 160
telemt_user_connections_total{user="hello"} 145823
telemt_user_connections_current{user="hello"} 129
telemt_user_octets_from_client{user="hello"} 2014300089 (1.88 GB)
telemt_user_octets_to_client{user="hello"} 62390380951 (58.11 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 110460.2 (30h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 706448
telemt_connections_bad_total 59414
telemt_handshake_timeouts_total 5307
telemt_upstream_connect_attempt_total 23447
telemt_upstream_connect_success_total 23321
telemt_upstream_connect_fail_total 126
telemt_upstream_connect_attempts_per_request{bucket="1"} 23447
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11116
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12163
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 126
telemt_me_keepalive_timeout_total 62
telemt_me_reconnect_attempts_total 19164
telemt_me_reconnect_success_total 17829
telemt_me_reader_eof_total 19038
telemt_me_idle_close_by_peer_total 19038
telemt_me_route_drop_no_conn_total 605335
telemt_me_route_drop_channel_closed_total 96
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 724660
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
telemt_pool_swap_total 103
telemt_me_writer_removed_unexpected_total 18078
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 17802
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 249
telemt_user_connections_total{user="hello"} 583332
telemt_user_connections_current{user="hello"} 393
telemt_user_octets_from_client{user="hello"} 13392734424 (12.47 GB)
telemt_user_octets_to_client{user="hello"} 360855154712 (336.07 GB)
telemt_user_unique_ips_current{user="hello"} 156
telemt_user_unique_ips_recent_window{user="hello"} 59
```