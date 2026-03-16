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

# Server Metrics 2026-03-16 06:58:04 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 117814.5 (32h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 534528
telemt_connections_bad_total 5700
telemt_handshake_timeouts_total 18867
telemt_upstream_connect_attempt_total 27744
telemt_upstream_connect_success_total 27614
telemt_upstream_connect_fail_total 130
telemt_upstream_connect_attempts_per_request{bucket="1"} 27744
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12252
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15315
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 130
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 51
telemt_me_reconnect_attempts_total 25232
telemt_me_reconnect_success_total 21800
telemt_me_reader_eof_total 23322
telemt_me_idle_close_by_peer_total 23322
telemt_me_route_drop_no_conn_total 518414
telemt_me_route_drop_channel_closed_total 83
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 532943
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2597
telemt_desync_full_logged_total 1033
telemt_desync_suppressed_total 1564
telemt_desync_frames_bucket_total{bucket="1_2"} 527
telemt_desync_frames_bucket_total{bucket="3_10"} 1004
telemt_desync_frames_bucket_total{bucket="gt_10"} 1066
telemt_pool_swap_total 114
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 22145
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 21766
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 345
telemt_user_connections_total{user="hello"} 471772
telemt_user_connections_current{user="hello"} 420
telemt_user_octets_from_client{user="hello"} 9295412236 (8.66 GB)
telemt_user_octets_to_client{user="hello"} 312888643892 (291.40 GB)
telemt_user_unique_ips_current{user="hello"} 143
telemt_user_unique_ips_recent_window{user="hello"} 60
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 117820.8 (32h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 211273
telemt_connections_bad_total 3150
telemt_handshake_timeouts_total 15012
telemt_upstream_connect_attempt_total 31619
telemt_upstream_connect_success_total 31544
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 31619
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13689
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17244
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 611
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 1307
telemt_me_reconnect_attempts_total 32228
telemt_me_reconnect_success_total 25311
telemt_me_reader_eof_total 27130
telemt_me_idle_close_by_peer_total 27129
telemt_me_route_drop_no_conn_total 104771
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 185522
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 79
telemt_desync_full_logged_total 24
telemt_desync_suppressed_total 55
telemt_desync_frames_bucket_total{bucket="1_2"} 11
telemt_desync_frames_bucket_total{bucket="3_10"} 32
telemt_desync_frames_bucket_total{bucket="gt_10"} 36
telemt_pool_swap_total 105
telemt_me_writer_removed_unexpected_total 25871
telemt_me_refill_failed_total 208
telemt_me_writer_restored_same_endpoint_total 25295
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 560
telemt_user_connections_total{user="hello"} 185054
telemt_user_connections_current{user="hello"} 323
telemt_user_octets_from_client{user="hello"} 4073676285 (3.79 GB)
telemt_user_octets_to_client{user="hello"} 100158987116 (93.28 GB)
telemt_user_msgs_from_client{user="hello"} 721
telemt_user_msgs_to_client{user="hello"} 1482
telemt_user_unique_ips_current{user="hello"} 81
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 117813.8 (32h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 231389
telemt_connections_bad_total 5717
telemt_handshake_timeouts_total 4590
telemt_upstream_connect_attempt_total 32894
telemt_upstream_connect_success_total 32886
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 32894
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14270
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18562
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 34403
telemt_me_reconnect_success_total 27006
telemt_me_reader_eof_total 29073
telemt_me_idle_close_by_peer_total 29072
telemt_me_route_drop_no_conn_total 81076
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 183434
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 78
telemt_desync_full_logged_total 29
telemt_desync_suppressed_total 49
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 36
telemt_desync_frames_bucket_total{bucket="gt_10"} 35
telemt_pool_swap_total 108
telemt_me_writer_removed_unexpected_total 27497
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 26998
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 491
telemt_user_connections_total{user="hello"} 183149
telemt_user_connections_current{user="hello"} 213
telemt_user_octets_from_client{user="hello"} 17261432161 (16.08 GB)
telemt_user_octets_to_client{user="hello"} 109173119272 (101.68 GB)
telemt_user_msgs_from_client{user="hello"} 7
telemt_user_msgs_to_client{user="hello"} 46
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 117812.9 (32h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 309897
telemt_connections_bad_total 1320
telemt_handshake_timeouts_total 2853
telemt_upstream_connect_attempt_total 27347
telemt_upstream_connect_success_total 27318
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 27347
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13074
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14098
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 133
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 21616
telemt_me_reconnect_success_total 21484
telemt_me_reader_eof_total 22949
telemt_me_idle_close_by_peer_total 22948
telemt_me_route_drop_no_conn_total 110643
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 285005
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 987
telemt_desync_full_logged_total 345
telemt_desync_suppressed_total 642
telemt_desync_frames_bucket_total{bucket="1_2"} 198
telemt_desync_frames_bucket_total{bucket="3_10"} 428
telemt_desync_frames_bucket_total{bucket="gt_10"} 361
telemt_pool_swap_total 115
telemt_me_writer_removed_unexpected_total 21759
telemt_me_writer_restored_same_endpoint_total 21473
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 275
telemt_user_connections_total{user="hello"} 284904
telemt_user_connections_current{user="hello"} 290
telemt_user_octets_from_client{user="hello"} 4690408022 (4.37 GB)
telemt_user_octets_to_client{user="hello"} 124564083180 (116.01 GB)
telemt_user_msgs_from_client{user="hello"} 25
telemt_user_msgs_to_client{user="hello"} 50
telemt_user_unique_ips_current{user="hello"} 93
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 92884.4 (25h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 207830
telemt_connections_bad_total 35404
telemt_handshake_timeouts_total 3597
telemt_upstream_connect_attempt_total 26521
telemt_upstream_connect_success_total 26375
telemt_upstream_connect_fail_total 146
telemt_upstream_connect_attempts_per_request{bucket="1"} 26521
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11698
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14538
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 139
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 146
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 116066
telemt_me_reconnect_success_total 21578
telemt_me_reader_eof_total 22931
telemt_me_idle_close_by_peer_total 22931
telemt_me_route_drop_no_conn_total 65177
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 163449
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 467
telemt_desync_full_logged_total 115
telemt_desync_suppressed_total 352
telemt_desync_frames_bucket_total{bucket="1_2"} 62
telemt_desync_frames_bucket_total{bucket="3_10"} 194
telemt_desync_frames_bucket_total{bucket="gt_10"} 211
telemt_pool_swap_total 81
telemt_me_writer_removed_unexpected_total 21751
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 21474
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 173
telemt_user_connections_total{user="hello"} 163080
telemt_user_connections_current{user="hello"} 141
telemt_user_octets_from_client{user="hello"} 2280118061 (2.12 GB)
telemt_user_octets_to_client{user="hello"} 70806544055 (65.94 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 117812.2 (32h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 764818
telemt_connections_bad_total 65870
telemt_handshake_timeouts_total 5708
telemt_upstream_connect_attempt_total 24805
telemt_upstream_connect_success_total 24673
telemt_upstream_connect_fail_total 132
telemt_upstream_connect_attempts_per_request{bucket="1"} 24805
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11777
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12854
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 132
telemt_me_keepalive_timeout_total 62
telemt_me_reconnect_attempts_total 20168
telemt_me_reconnect_success_total 18826
telemt_me_reader_eof_total 20104
telemt_me_idle_close_by_peer_total 20104
telemt_me_route_drop_no_conn_total 627390
telemt_me_route_drop_channel_closed_total 101
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 770618
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
telemt_pool_swap_total 111
telemt_me_writer_removed_unexpected_total 19089
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 18799
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 263
telemt_user_connections_total{user="hello"} 629267
telemt_user_connections_current{user="hello"} 533
telemt_user_octets_from_client{user="hello"} 14071070604 (13.10 GB)
telemt_user_octets_to_client{user="hello"} 380412375204 (354.29 GB)
telemt_user_unique_ips_current{user="hello"} 206
telemt_user_unique_ips_recent_window{user="hello"} 78
```