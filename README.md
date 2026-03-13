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

# Server Metrics 2026-03-13 01:45:26 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 65522.8 (18h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 265785
telemt_connections_bad_total 2804
telemt_handshake_timeouts_total 5619
telemt_upstream_connect_attempt_total 16568
telemt_upstream_connect_success_total 16497
telemt_upstream_connect_fail_total 71
telemt_upstream_connect_attempts_per_request{bucket="1"} 16568
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7293
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9158
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 71
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1512
telemt_me_reconnect_attempts_total 16679
telemt_me_reconnect_success_total 13202
telemt_me_reader_eof_total 14089
telemt_me_idle_close_by_peer_total 14088
telemt_me_route_drop_no_conn_total 82495
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 220567
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 729
telemt_desync_full_logged_total 275
telemt_desync_suppressed_total 454
telemt_desync_frames_bucket_total{bucket="1_2"} 130
telemt_desync_frames_bucket_total{bucket="3_10"} 271
telemt_desync_frames_bucket_total{bucket="gt_10"} 328
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 13452
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 13186
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 250
telemt_user_connections_total{user="hello"} 220335
telemt_user_connections_current{user="hello"} 201
telemt_user_octets_from_client{user="hello"} 3959775564 (3.69 GB)
telemt_user_octets_to_client{user="hello"} 110149980896 (102.59 GB)
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 65415.8 (18h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 123511
telemt_connections_bad_total 737
telemt_handshake_timeouts_total 975
telemt_upstream_connect_attempt_total 36496
telemt_upstream_connect_success_total 36050
telemt_upstream_connect_fail_total 446
telemt_upstream_connect_attempts_per_request{bucket="1"} 36496
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22524
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13025
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 501
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 446
telemt_me_keepalive_timeout_total 466
telemt_me_reconnect_attempts_total 60485
telemt_me_reconnect_success_total 16272
telemt_me_reader_eof_total 18078
telemt_me_idle_close_by_peer_total 18078
telemt_me_route_drop_no_conn_total 44129
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 100739
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
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 17770
telemt_me_refill_failed_total 1380
telemt_me_writer_restored_same_endpoint_total 16257
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1498
telemt_user_connections_total{user="hello"} 117239
telemt_user_connections_current{user="hello"} 63
telemt_user_octets_from_client{user="hello"} 1253180168 (1.17 GB)
telemt_user_octets_to_client{user="hello"} 35450619227 (33.02 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 20
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 65379.3 (18h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 148876
telemt_connections_bad_total 1705
telemt_handshake_timeouts_total 2350
telemt_upstream_connect_attempt_total 18030
telemt_upstream_connect_success_total 18028
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 18030
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8375
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9632
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 368
telemt_me_reconnect_attempts_total 15865
telemt_me_reconnect_success_total 14708
telemt_me_reader_eof_total 15724
telemt_me_idle_close_by_peer_total 15724
telemt_me_route_drop_no_conn_total 56623
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 139246
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
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 14873
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 14688
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 165
telemt_user_connections_total{user="hello"} 139199
telemt_user_connections_current{user="hello"} 78
telemt_user_octets_from_client{user="hello"} 2696944432 (2.51 GB)
telemt_user_octets_to_client{user="hello"} 64015195956 (59.62 GB)
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 65355.2 (18h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 212690
telemt_connections_bad_total 13305
telemt_handshake_timeouts_total 1427
telemt_upstream_connect_attempt_total 30176
telemt_upstream_connect_success_total 20403
telemt_upstream_connect_fail_total 9773
telemt_upstream_connect_attempts_per_request{bucket="1"} 30176
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10402
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9838
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 155
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9773
telemt_me_keepalive_timeout_total 3218
telemt_me_reconnect_attempts_total 51157
telemt_me_reconnect_success_total 14258
telemt_me_reader_eof_total 15908
telemt_me_idle_close_by_peer_total 15901
telemt_me_route_drop_no_conn_total 76684
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 176351
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
telemt_me_writer_removed_unexpected_total 15616
telemt_me_refill_failed_total 1149
telemt_me_writer_restored_same_endpoint_total 14248
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1358
telemt_user_connections_total{user="hello"} 179103
telemt_user_connections_current{user="hello"} 112
telemt_user_octets_from_client{user="hello"} 3040787150 (2.83 GB)
telemt_user_octets_to_client{user="hello"} 73287549201 (68.25 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 15526.8 (4h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13748
telemt_connections_bad_total 2929
telemt_handshake_timeouts_total 25
telemt_upstream_connect_attempt_total 4836
telemt_upstream_connect_success_total 4793
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 4836
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2130
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2644
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_timeout_total 94
telemt_me_reconnect_attempts_total 3994
telemt_me_reconnect_success_total 3984
telemt_me_reader_eof_total 4264
telemt_me_idle_close_by_peer_total 4264
telemt_me_route_drop_no_conn_total 4257
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10374
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 4011
telemt_me_writer_restored_same_endpoint_total 3968
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 10374
telemt_user_connections_current{user="hello"} 44
telemt_user_octets_from_client{user="hello"} 49527996 (47.23 MB)
telemt_user_octets_to_client{user="hello"} 3512435736 (3.27 GB)
telemt_user_unique_ips_current{user="hello"} 21
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 65311.5 (18h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 356954
telemt_connections_bad_total 6579
telemt_handshake_timeouts_total 2616
telemt_upstream_connect_attempt_total 13869
telemt_upstream_connect_success_total 13793
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 13869
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6447
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7326
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_keepalive_timeout_total 1343
telemt_me_reconnect_attempts_total 14152
telemt_me_reconnect_success_total 10534
telemt_me_reader_eof_total 11303
telemt_me_idle_close_by_peer_total 11301
telemt_me_route_drop_no_conn_total 159812
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 349177
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
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 10774
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 10527
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 240
telemt_user_connections_total{user="hello"} 337477
telemt_user_connections_current{user="hello"} 224
telemt_user_octets_from_client{user="hello"} 5720931216 (5.33 GB)
telemt_user_octets_to_client{user="hello"} 185529531264 (172.79 GB)
telemt_user_unique_ips_current{user="hello"} 92
telemt_user_unique_ips_recent_window{user="hello"} 21
```