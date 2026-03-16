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

# Server Metrics 2026-03-16 17:41:43 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 14630.0 (4h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 150192
telemt_connections_bad_total 664
telemt_handshake_timeouts_total 3954
telemt_upstream_connect_attempt_total 3158
telemt_upstream_connect_success_total 3146
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 3158
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1496
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1647
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 3515
telemt_me_reconnect_success_total 2345
telemt_me_reader_eof_total 2431
telemt_me_idle_close_by_peer_total 2430
telemt_me_route_drop_no_conn_total 45386
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 140649
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 5
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 709
telemt_desync_full_logged_total 166
telemt_desync_suppressed_total 543
telemt_desync_frames_bucket_total{bucket="1_2"} 263
telemt_desync_frames_bucket_total{bucket="3_10"} 254
telemt_desync_frames_bucket_total{bucket="gt_10"} 192
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 2395
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 2343
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 50
telemt_user_connections_total{user="hello"} 140567
telemt_user_connections_current{user="hello"} 656
telemt_user_octets_from_client{user="hello"} 2554351900 (2.38 GB)
telemt_user_octets_to_client{user="hello"} 81219088984 (75.64 GB)
telemt_user_unique_ips_current{user="hello"} 196
telemt_user_unique_ips_recent_window{user="hello"} 66
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 9409.0 (2h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 67419
telemt_connections_bad_total 577
telemt_handshake_timeouts_total 3128
telemt_upstream_connect_attempt_total 2063
telemt_upstream_connect_success_total 2051
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 2063
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 735
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1139
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 177
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_reconnect_attempts_total 5031
telemt_me_reconnect_success_total 1524
telemt_me_reader_eof_total 1660
telemt_me_idle_close_by_peer_total 1660
telemt_me_route_drop_no_conn_total 39292
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 61284
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 113
telemt_desync_full_logged_total 27
telemt_desync_suppressed_total 86
telemt_desync_frames_bucket_total{bucket="1_2"} 32
telemt_desync_frames_bucket_total{bucket="3_10"} 48
telemt_desync_frames_bucket_total{bucket="gt_10"} 33
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 1660
telemt_me_refill_failed_total 109
telemt_me_writer_restored_same_endpoint_total 1519
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 343
telemt_me_writer_removed_unexpected_minus_restored_total 136
telemt_user_connections_total{user="hello"} 61225
telemt_user_connections_current{user="hello"} 391
telemt_user_octets_from_client{user="hello"} 736471384 (702.35 MB)
telemt_user_octets_to_client{user="hello"} 18063879140 (16.82 GB)
telemt_user_unique_ips_current{user="hello"} 116
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 14743.3 (4h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 59342
telemt_connections_bad_total 77
telemt_handshake_timeouts_total 868
telemt_upstream_connect_attempt_total 4405
telemt_upstream_connect_success_total 4358
telemt_upstream_connect_fail_total 47
telemt_upstream_connect_attempts_per_request{bucket="1"} 4405
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2329
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2006
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 47
telemt_me_reconnect_attempts_total 41458
telemt_me_reconnect_success_total 2573
telemt_me_reader_eof_total 2901
telemt_me_idle_close_by_peer_total 2901
telemt_me_route_drop_no_conn_total 20814
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 54504
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 149
telemt_desync_full_logged_total 54
telemt_desync_suppressed_total 95
telemt_desync_frames_bucket_total{bucket="1_2"} 33
telemt_desync_frames_bucket_total{bucket="3_10"} 65
telemt_desync_frames_bucket_total{bucket="gt_10"} 51
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 2907
telemt_me_refill_failed_total 1214
telemt_me_writer_restored_same_endpoint_total 2529
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 1272
telemt_me_writer_removed_unexpected_minus_restored_total 334
telemt_user_connections_total{user="hello"} 55445
telemt_user_connections_current{user="hello"} 258
telemt_user_octets_from_client{user="hello"} 680258982 (648.75 MB)
telemt_user_octets_to_client{user="hello"} 15282477518 (14.23 GB)
telemt_user_msgs_from_client{user="hello"} 4789
telemt_user_msgs_to_client{user="hello"} 14129
telemt_user_unique_ips_current{user="hello"} 76
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 14879.4 (4h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 116589
telemt_connections_bad_total 221
telemt_handshake_timeouts_total 1738
telemt_upstream_connect_attempt_total 3235
telemt_upstream_connect_success_total 3209
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 3235
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1532
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1646
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 8734
telemt_me_reconnect_success_total 2378
telemt_me_reader_eof_total 2624
telemt_me_idle_close_by_peer_total 2623
telemt_me_route_drop_no_conn_total 42993
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 110548
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 610
telemt_desync_full_logged_total 171
telemt_desync_suppressed_total 439
telemt_desync_frames_bucket_total{bucket="1_2"} 104
telemt_desync_frames_bucket_total{bucket="3_10"} 261
telemt_desync_frames_bucket_total{bucket="gt_10"} 245
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 2608
telemt_me_refill_failed_total 197
telemt_me_writer_restored_same_endpoint_total 2374
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 230
telemt_user_connections_total{user="hello"} 110521
telemt_user_connections_current{user="hello"} 422
telemt_user_octets_from_client{user="hello"} 1524274452 (1.42 GB)
telemt_user_octets_to_client{user="hello"} 27932716056 (26.01 GB)
telemt_user_unique_ips_current{user="hello"} 128
telemt_user_unique_ips_recent_window{user="hello"} 55
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 12340.1 (3h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 67671
telemt_connections_bad_total 20178
telemt_handshake_timeouts_total 548
telemt_upstream_connect_attempt_total 3144
telemt_upstream_connect_success_total 3104
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 3144
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1260
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1779
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 65
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_reconnect_attempts_total 4102
telemt_me_reconnect_success_total 2448
telemt_me_reader_eof_total 2556
telemt_me_idle_close_by_peer_total 2556
telemt_me_route_drop_no_conn_total 50141
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 63463
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 63
telemt_desync_full_logged_total 23
telemt_desync_suppressed_total 40
telemt_desync_frames_bucket_total{bucket="1_2"} 28
telemt_desync_frames_bucket_total{bucket="3_10"} 23
telemt_desync_frames_bucket_total{bucket="gt_10"} 12
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 2537
telemt_me_refill_failed_total 51
telemt_me_writer_restored_same_endpoint_total 2448
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 89
telemt_user_connections_total{user="hello"} 44515
telemt_user_connections_current{user="hello"} 171
telemt_user_octets_from_client{user="hello"} 2048387608 (1.91 GB)
telemt_user_octets_to_client{user="hello"} 31432566088 (29.27 GB)
telemt_user_unique_ips_current{user="hello"} 69
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 14447.5 (4h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 168857
telemt_connections_bad_total 2076
telemt_handshake_timeouts_total 3348
telemt_upstream_connect_attempt_total 3000
telemt_upstream_connect_success_total 3000
telemt_upstream_connect_attempts_per_request{bucket="1"} 3000
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1453
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1543
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 7261
telemt_me_reconnect_success_total 2234
telemt_me_reader_eof_total 2434
telemt_me_idle_close_by_peer_total 2433
telemt_me_route_drop_no_conn_total 75713
telemt_me_route_drop_channel_closed_total 20
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 156606
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 49
telemt_desync_full_logged_total 20
telemt_desync_suppressed_total 29
telemt_desync_frames_bucket_total{bucket="1_2"} 17
telemt_desync_frames_bucket_total{bucket="3_10"} 23
telemt_desync_frames_bucket_total{bucket="gt_10"} 9
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 2410
telemt_me_refill_failed_total 156
telemt_me_writer_restored_same_endpoint_total 2228
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 208
telemt_me_writer_removed_unexpected_minus_restored_total 176
telemt_user_connections_total{user="hello"} 156323
telemt_user_connections_current{user="hello"} 774
telemt_user_octets_from_client{user="hello"} 3104531436 (2.89 GB)
telemt_user_octets_to_client{user="hello"} 59181376904 (55.12 GB)
telemt_user_unique_ips_current{user="hello"} 258
telemt_user_unique_ips_recent_window{user="hello"} 87
```