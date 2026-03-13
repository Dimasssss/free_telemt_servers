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

# Server Metrics 2026-03-13 12:22:08 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 103729.1 (28h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 422512
telemt_connections_bad_total 3210
telemt_handshake_timeouts_total 8362
telemt_upstream_connect_attempt_total 26398
telemt_upstream_connect_success_total 26273
telemt_upstream_connect_fail_total 125
telemt_upstream_connect_attempts_per_request{bucket="1"} 26398
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11855
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14370
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 125
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2395
telemt_me_reconnect_attempts_total 24580
telemt_me_reconnect_success_total 21055
telemt_me_reader_eof_total 22480
telemt_me_idle_close_by_peer_total 22479
telemt_me_route_drop_no_conn_total 134017
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 366861
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1239
telemt_desync_full_logged_total 438
telemt_desync_suppressed_total 801
telemt_desync_frames_bucket_total{bucket="1_2"} 250
telemt_desync_frames_bucket_total{bucket="3_10"} 459
telemt_desync_frames_bucket_total{bucket="gt_10"} 530
telemt_pool_swap_total 92
telemt_me_writer_removed_unexpected_total 21382
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 21039
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 327
telemt_user_connections_total{user="hello"} 366454
telemt_user_connections_current{user="hello"} 360
telemt_user_octets_from_client{user="hello"} 6542743764 (6.09 GB)
telemt_user_octets_to_client{user="hello"} 157081740972 (146.29 GB)
telemt_user_unique_ips_current{user="hello"} 110
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 103622.3 (28h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 195291
telemt_connections_bad_total 1657
telemt_handshake_timeouts_total 1477
telemt_upstream_connect_attempt_total 57304
telemt_upstream_connect_success_total 56603
telemt_upstream_connect_fail_total 701
telemt_upstream_connect_attempts_per_request{bucket="1"} 57304
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35308
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20732
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 563
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 701
telemt_me_keepalive_timeout_total 1351
telemt_me_reconnect_attempts_total 95684
telemt_me_reconnect_success_total 25948
telemt_me_reader_eof_total 28887
telemt_me_idle_close_by_peer_total 28887
telemt_me_route_drop_no_conn_total 79057
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 158934
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 23
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
telemt_me_writer_removed_unexpected_total 28351
telemt_me_refill_failed_total 2175
telemt_me_writer_restored_same_endpoint_total 25931
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 2403
telemt_user_connections_total{user="hello"} 184166
telemt_user_connections_current{user="hello"} 159
telemt_user_octets_from_client{user="hello"} 1872112353 (1.74 GB)
telemt_user_octets_to_client{user="hello"} 60672270550 (56.51 GB)
telemt_user_msgs_from_client{user="hello"} 375876
telemt_user_msgs_to_client{user="hello"} 2794227
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 57
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 103585.8 (28h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 236919
telemt_connections_bad_total 2065
telemt_handshake_timeouts_total 7430
telemt_upstream_connect_attempt_total 28132
telemt_upstream_connect_success_total 28128
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 28132
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13026
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15075
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2175
telemt_me_reconnect_attempts_total 24088
telemt_me_reconnect_success_total 22877
telemt_me_reader_eof_total 24502
telemt_me_idle_close_by_peer_total 24502
telemt_me_route_drop_no_conn_total 87862
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 218815
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 92
telemt_desync_full_logged_total 43
telemt_desync_suppressed_total 49
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 32
telemt_desync_frames_bucket_total{bucket="gt_10"} 54
telemt_pool_swap_total 92
telemt_me_writer_removed_unexpected_total 23129
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 22857
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 252
telemt_user_connections_total{user="hello"} 218729
telemt_user_connections_current{user="hello"} 148
telemt_user_octets_from_client{user="hello"} 9347638228 (8.71 GB)
telemt_user_octets_to_client{user="hello"} 97740761124 (91.03 GB)
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 103561.2 (28h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 330331
telemt_connections_bad_total 13771
telemt_handshake_timeouts_total 2427
telemt_upstream_connect_attempt_total 39935
telemt_upstream_connect_success_total 29860
telemt_upstream_connect_fail_total 10075
telemt_upstream_connect_attempts_per_request{bucket="1"} 39935
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15098
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14551
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 202
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10075
telemt_me_keepalive_timeout_total 4048
telemt_me_reconnect_attempts_total 93176
telemt_me_reconnect_success_total 21624
telemt_me_reader_eof_total 24506
telemt_me_idle_close_by_peer_total 24499
telemt_me_route_drop_no_conn_total 119540
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 285132
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 987
telemt_desync_full_logged_total 293
telemt_desync_suppressed_total 694
telemt_desync_frames_bucket_total{bucket="1_2"} 248
telemt_desync_frames_bucket_total{bucket="3_10"} 362
telemt_desync_frames_bucket_total{bucket="gt_10"} 377
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 24128
telemt_me_refill_failed_total 2231
telemt_me_writer_restored_same_endpoint_total 21614
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 2504
telemt_user_connections_total{user="hello"} 288044
telemt_user_connections_current{user="hello"} 239
telemt_user_octets_from_client{user="hello"} 5942749078 (5.53 GB)
telemt_user_octets_to_client{user="hello"} 108620689125 (101.16 GB)
telemt_user_msgs_from_client{user="hello"} 68310
telemt_user_msgs_to_client{user="hello"} 114408
telemt_user_unique_ips_current{user="hello"} 68
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 53732.8 (14h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 78144
telemt_connections_bad_total 10624
telemt_handshake_timeouts_total 925
telemt_upstream_connect_attempt_total 23303
telemt_upstream_connect_success_total 23122
telemt_upstream_connect_fail_total 181
telemt_upstream_connect_attempts_per_request{bucket="1"} 23303
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12315
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10745
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 181
telemt_me_keepalive_timeout_total 943
telemt_me_reconnect_attempts_total 25432
telemt_me_reconnect_success_total 15515
telemt_me_reader_eof_total 16654
telemt_me_idle_close_by_peer_total 16654
telemt_me_route_drop_no_conn_total 23113
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 59173
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 120
telemt_desync_full_logged_total 20
telemt_desync_suppressed_total 100
telemt_desync_frames_bucket_total{bucket="1_2"} 17
telemt_desync_frames_bucket_total{bucket="3_10"} 49
telemt_desync_frames_bucket_total{bucket="gt_10"} 54
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 15960
telemt_me_refill_failed_total 308
telemt_me_writer_restored_same_endpoint_total 15497
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 445
telemt_user_connections_total{user="hello"} 64084
telemt_user_connections_current{user="hello"} 99
telemt_user_octets_from_client{user="hello"} 559213093 (533.31 MB)
telemt_user_octets_to_client{user="hello"} 18047109747 (16.81 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 103517.8 (28h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 591208
telemt_connections_bad_total 17509
telemt_handshake_timeouts_total 14026
telemt_upstream_connect_attempt_total 21937
telemt_upstream_connect_success_total 21823
telemt_upstream_connect_fail_total 114
telemt_upstream_connect_attempts_per_request{bucket="1"} 21937
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10238
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11560
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 114
telemt_me_keepalive_timeout_total 2486
telemt_me_reconnect_attempts_total 21307
telemt_me_reconnect_success_total 16686
telemt_me_reader_eof_total 17907
telemt_me_idle_close_by_peer_total 17904
telemt_me_route_drop_no_conn_total 291449
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 566410
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 461
telemt_desync_full_logged_total 174
telemt_desync_suppressed_total 287
telemt_desync_frames_bucket_total{bucket="1_2"} 109
telemt_desync_frames_bucket_total{bucket="3_10"} 175
telemt_desync_frames_bucket_total{bucket="gt_10"} 177
telemt_pool_swap_total 94
telemt_me_writer_removed_unexpected_total 17048
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 16679
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 362
telemt_user_connections_total{user="hello"} 539473
telemt_user_connections_current{user="hello"} 405
telemt_user_octets_from_client{user="hello"} 9579632756 (8.92 GB)
telemt_user_octets_to_client{user="hello"} 288742812144 (268.91 GB)
telemt_user_unique_ips_current{user="hello"} 162
telemt_user_unique_ips_recent_window{user="hello"} 57
```