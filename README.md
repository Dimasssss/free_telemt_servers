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

# Server Metrics 2026-03-16 09:36:23 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 127313.1 (35h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 613492
telemt_connections_bad_total 10281
telemt_handshake_timeouts_total 21586
telemt_upstream_connect_attempt_total 29910
telemt_upstream_connect_success_total 29768
telemt_upstream_connect_fail_total 142
telemt_upstream_connect_attempts_per_request{bucket="1"} 29910
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13257
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16464
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 142
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 51
telemt_me_reconnect_attempts_total 29459
telemt_me_reconnect_success_total 23457
telemt_me_reader_eof_total 25118
telemt_me_idle_close_by_peer_total 25118
telemt_me_route_drop_no_conn_total 583898
telemt_me_route_drop_channel_closed_total 86
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 604063
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2872
telemt_desync_full_logged_total 1110
telemt_desync_suppressed_total 1762
telemt_desync_frames_bucket_total{bucket="1_2"} 631
telemt_desync_frames_bucket_total{bucket="3_10"} 1100
telemt_desync_frames_bucket_total{bucket="gt_10"} 1141
telemt_pool_swap_total 121
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 23901
telemt_me_refill_failed_total 184
telemt_me_writer_restored_same_endpoint_total 23423
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 444
telemt_user_connections_total{user="hello"} 540634
telemt_user_connections_current{user="hello"} 523
telemt_user_octets_from_client{user="hello"} 10590584604 (9.86 GB)
telemt_user_octets_to_client{user="hello"} 338102422200 (314.88 GB)
telemt_user_unique_ips_current{user="hello"} 170
telemt_user_unique_ips_recent_window{user="hello"} 83
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 127320.2 (35h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 252330
telemt_connections_bad_total 3291
telemt_handshake_timeouts_total 15481
telemt_upstream_connect_attempt_total 34168
telemt_upstream_connect_success_total 34093
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 34168
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14704
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18700
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 689
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 1307
telemt_me_reconnect_attempts_total 37677
telemt_me_reconnect_success_total 27361
telemt_me_reader_eof_total 29348
telemt_me_idle_close_by_peer_total 29347
telemt_me_route_drop_no_conn_total 120541
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 224787
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 194
telemt_desync_full_logged_total 61
telemt_desync_suppressed_total 133
telemt_desync_frames_bucket_total{bucket="1_2"} 37
telemt_desync_frames_bucket_total{bucket="3_10"} 71
telemt_desync_frames_bucket_total{bucket="gt_10"} 86
telemt_pool_swap_total 108
telemt_me_writer_removed_unexpected_total 28062
telemt_me_refill_failed_total 314
telemt_me_writer_restored_same_endpoint_total 27345
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 701
telemt_user_connections_total{user="hello"} 224327
telemt_user_connections_current{user="hello"} 256
telemt_user_octets_from_client{user="hello"} 4943560633 (4.60 GB)
telemt_user_octets_to_client{user="hello"} 122466260232 (114.06 GB)
telemt_user_msgs_from_client{user="hello"} 721
telemt_user_msgs_to_client{user="hello"} 1482
telemt_user_unique_ips_current{user="hello"} 88
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 127313.1 (35h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 261812
telemt_connections_bad_total 5757
telemt_handshake_timeouts_total 5736
telemt_upstream_connect_attempt_total 35417
telemt_upstream_connect_success_total 35409
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 35417
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15297
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20058
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 41
telemt_me_reconnect_attempts_total 36437
telemt_me_reconnect_success_total 29017
telemt_me_reader_eof_total 31201
telemt_me_idle_close_by_peer_total 31200
telemt_me_route_drop_no_conn_total 90681
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 211841
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
telemt_pool_swap_total 115
telemt_me_writer_removed_unexpected_total 29536
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 29009
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 519
telemt_user_connections_total{user="hello"} 211539
telemt_user_connections_current{user="hello"} 182
telemt_user_octets_from_client{user="hello"} 17672387577 (16.46 GB)
telemt_user_octets_to_client{user="hello"} 117956386448 (109.86 GB)
telemt_user_msgs_from_client{user="hello"} 7
telemt_user_msgs_to_client{user="hello"} 46
telemt_user_unique_ips_current{user="hello"} 76
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 127312.5 (35h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 375450
telemt_connections_bad_total 1381
telemt_handshake_timeouts_total 3377
telemt_upstream_connect_attempt_total 29486
telemt_upstream_connect_success_total 29447
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 29486
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14132
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15152
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 16
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 147
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 24164
telemt_me_reconnect_success_total 23113
telemt_me_reader_eof_total 24685
telemt_me_idle_close_by_peer_total 24684
telemt_me_route_drop_no_conn_total 130231
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 347133
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1293
telemt_desync_full_logged_total 444
telemt_desync_suppressed_total 849
telemt_desync_frames_bucket_total{bucket="1_2"} 259
telemt_desync_frames_bucket_total{bucket="3_10"} 550
telemt_desync_frames_bucket_total{bucket="gt_10"} 484
telemt_pool_swap_total 120
telemt_me_writer_removed_unexpected_total 23452
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 23102
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 339
telemt_user_connections_total{user="hello"} 347009
telemt_user_connections_current{user="hello"} 356
telemt_user_octets_from_client{user="hello"} 5881243010 (5.48 GB)
telemt_user_octets_to_client{user="hello"} 140925357808 (131.25 GB)
telemt_user_msgs_from_client{user="hello"} 25
telemt_user_msgs_to_client{user="hello"} 50
telemt_user_unique_ips_current{user="hello"} 110
telemt_user_unique_ips_recent_window{user="hello"} 55
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 102383.8 (28h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 236706
telemt_connections_bad_total 37266
telemt_handshake_timeouts_total 4245
telemt_upstream_connect_attempt_total 29242
telemt_upstream_connect_success_total 29083
telemt_upstream_connect_fail_total 159
telemt_upstream_connect_attempts_per_request{bucket="1"} 29242
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12883
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16052
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 148
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 159
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 118337
telemt_me_reconnect_success_total 23835
telemt_me_reader_eof_total 25313
telemt_me_idle_close_by_peer_total 25313
telemt_me_route_drop_no_conn_total 74085
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 188431
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 612
telemt_desync_full_logged_total 140
telemt_desync_suppressed_total 472
telemt_desync_frames_bucket_total{bucket="1_2"} 95
telemt_desync_frames_bucket_total{bucket="3_10"} 244
telemt_desync_frames_bucket_total{bucket="gt_10"} 273
telemt_pool_swap_total 87
telemt_me_writer_removed_unexpected_total 24039
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 23731
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 204
telemt_user_connections_total{user="hello"} 188046
telemt_user_connections_current{user="hello"} 149
telemt_user_octets_from_client{user="hello"} 2474579917 (2.30 GB)
telemt_user_octets_to_client{user="hello"} 81428569415 (75.84 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 127311.8 (35h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 862185
telemt_connections_bad_total 72594
telemt_handshake_timeouts_total 10045
telemt_upstream_connect_attempt_total 26747
telemt_upstream_connect_success_total 26606
telemt_upstream_connect_fail_total 141
telemt_upstream_connect_attempts_per_request{bucket="1"} 26747
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12639
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13925
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 141
telemt_me_keepalive_timeout_total 63
telemt_me_reconnect_attempts_total 22864
telemt_me_reconnect_success_total 20263
telemt_me_reader_eof_total 21651
telemt_me_idle_close_by_peer_total 21651
telemt_me_route_drop_no_conn_total 664116
telemt_me_route_drop_channel_closed_total 117
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 851987
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
telemt_pool_swap_total 119
telemt_me_writer_removed_unexpected_total 20584
telemt_me_refill_failed_total 77
telemt_me_writer_restored_same_endpoint_total 20236
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 321
telemt_user_connections_total{user="hello"} 710644
telemt_user_connections_current{user="hello"} 647
telemt_user_octets_from_client{user="hello"} 15255828400 (14.21 GB)
telemt_user_octets_to_client{user="hello"} 429870420792 (400.35 GB)
telemt_user_unique_ips_current{user="hello"} 238
telemt_user_unique_ips_recent_window{user="hello"} 92
```