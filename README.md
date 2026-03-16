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

# Server Metrics 2026-03-16 12:14:41 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 136810.9 (38h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 754168
telemt_connections_bad_total 54144
telemt_handshake_timeouts_total 24184
telemt_upstream_connect_attempt_total 31508
telemt_upstream_connect_success_total 31357
telemt_upstream_connect_fail_total 151
telemt_upstream_connect_attempts_per_request{bucket="1"} 31508
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13985
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17325
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 151
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 56
telemt_me_reconnect_attempts_total 38811
telemt_me_reconnect_success_total 24582
telemt_me_reader_eof_total 26525
telemt_me_idle_close_by_peer_total 26525
telemt_me_route_drop_no_conn_total 608180
telemt_me_route_drop_channel_closed_total 95
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 694717
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3308
telemt_desync_full_logged_total 1249
telemt_desync_suppressed_total 2059
telemt_desync_frames_bucket_total{bucket="1_2"} 700
telemt_desync_frames_bucket_total{bucket="3_10"} 1363
telemt_desync_frames_bucket_total{bucket="gt_10"} 1245
telemt_pool_swap_total 124
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 25293
telemt_me_refill_failed_total 440
telemt_me_writer_restored_same_endpoint_total 24547
telemt_me_writer_restored_fallback_total 35
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 711
telemt_user_connections_total{user="hello"} 631215
telemt_user_connections_current{user="hello"} 661
telemt_user_octets_from_client{user="hello"} 12198543824 (11.36 GB)
telemt_user_octets_to_client{user="hello"} 366025691404 (340.89 GB)
telemt_user_unique_ips_current{user="hello"} 204
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 136818.3 (38h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 312000
telemt_connections_bad_total 3926
telemt_handshake_timeouts_total 20610
telemt_upstream_connect_attempt_total 36571
telemt_upstream_connect_success_total 36464
telemt_upstream_connect_fail_total 107
telemt_upstream_connect_attempts_per_request{bucket="1"} 36571
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15754
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19870
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 834
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 107
telemt_me_keepalive_timeout_total 1697
telemt_me_reconnect_attempts_total 42997
telemt_me_reconnect_success_total 29058
telemt_me_reader_eof_total 31221
telemt_me_idle_close_by_peer_total 31220
telemt_me_route_drop_no_conn_total 148008
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 275898
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 225
telemt_desync_full_logged_total 73
telemt_desync_suppressed_total 152
telemt_desync_frames_bucket_total{bucket="1_2"} 46
telemt_desync_frames_bucket_total{bucket="3_10"} 85
telemt_desync_frames_bucket_total{bucket="gt_10"} 94
telemt_pool_swap_total 112
telemt_me_writer_removed_unexpected_total 29908
telemt_me_refill_failed_total 426
telemt_me_writer_restored_same_endpoint_total 29042
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 850
telemt_user_connections_total{user="hello"} 275595
telemt_user_connections_current{user="hello"} 412
telemt_user_octets_from_client{user="hello"} 5531259409 (5.15 GB)
telemt_user_octets_to_client{user="hello"} 136731605288 (127.34 GB)
telemt_user_msgs_from_client{user="hello"} 994
telemt_user_msgs_to_client{user="hello"} 1709
telemt_user_unique_ips_current{user="hello"} 106
telemt_user_unique_ips_recent_window{user="hello"} 51
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 136810.7 (38h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 301599
telemt_connections_bad_total 5951
telemt_handshake_timeouts_total 8934
telemt_upstream_connect_attempt_total 37869
telemt_upstream_connect_success_total 37861
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 37869
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16351
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21449
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 71
telemt_me_reconnect_attempts_total 38442
telemt_me_reconnect_success_total 31002
telemt_me_reader_eof_total 33277
telemt_me_idle_close_by_peer_total 33276
telemt_me_route_drop_no_conn_total 102569
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 246798
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 119
telemt_desync_full_logged_total 46
telemt_desync_suppressed_total 73
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 52
telemt_desync_frames_bucket_total{bucket="gt_10"} 52
telemt_pool_swap_total 120
telemt_me_writer_removed_unexpected_total 31550
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 30994
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 548
telemt_user_connections_total{user="hello"} 246397
telemt_user_connections_current{user="hello"} 254
telemt_user_octets_from_client{user="hello"} 18912784009 (17.61 GB)
telemt_user_octets_to_client{user="hello"} 129662195088 (120.76 GB)
telemt_user_msgs_from_client{user="hello"} 7
telemt_user_msgs_to_client{user="hello"} 46
telemt_user_unique_ips_current{user="hello"} 93
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 136810.6 (38h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 454681
telemt_connections_bad_total 1486
telemt_handshake_timeouts_total 5173
telemt_upstream_connect_attempt_total 31628
telemt_upstream_connect_success_total 31583
telemt_upstream_connect_fail_total 45
telemt_upstream_connect_attempts_per_request{bucket="1"} 31628
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15261
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16134
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 16
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 172
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 45
telemt_me_keepalive_timeout_total 127
telemt_me_reconnect_attempts_total 29786
telemt_me_reconnect_success_total 24782
telemt_me_reader_eof_total 26542
telemt_me_idle_close_by_peer_total 26541
telemt_me_route_drop_no_conn_total 154497
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 419828
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1530
telemt_desync_full_logged_total 511
telemt_desync_suppressed_total 1019
telemt_desync_frames_bucket_total{bucket="1_2"} 307
telemt_desync_frames_bucket_total{bucket="3_10"} 657
telemt_desync_frames_bucket_total{bucket="gt_10"} 566
telemt_pool_swap_total 123
telemt_me_writer_removed_unexpected_total 25272
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 24771
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 490
telemt_user_connections_total{user="hello"} 419660
telemt_user_connections_current{user="hello"} 491
telemt_user_octets_from_client{user="hello"} 6566486174 (6.12 GB)
telemt_user_octets_to_client{user="hello"} 160305719544 (149.30 GB)
telemt_user_msgs_from_client{user="hello"} 25
telemt_user_msgs_to_client{user="hello"} 50
telemt_user_unique_ips_current{user="hello"} 140
telemt_user_unique_ips_recent_window{user="hello"} 80
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 111881.9 (31h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 284486
telemt_connections_bad_total 51392
telemt_handshake_timeouts_total 4513
telemt_upstream_connect_attempt_total 31876
telemt_upstream_connect_success_total 31705
telemt_upstream_connect_fail_total 171
telemt_upstream_connect_attempts_per_request{bucket="1"} 31876
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13977
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17557
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 171
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 171
telemt_me_keepalive_timeout_total 52
telemt_me_reconnect_attempts_total 121557
telemt_me_reconnect_success_total 25947
telemt_me_reader_eof_total 27559
telemt_me_idle_close_by_peer_total 27559
telemt_me_route_drop_no_conn_total 85687
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 219789
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 701
telemt_desync_full_logged_total 171
telemt_desync_suppressed_total 530
telemt_desync_frames_bucket_total{bucket="1_2"} 102
telemt_desync_frames_bucket_total{bucket="3_10"} 288
telemt_desync_frames_bucket_total{bucket="gt_10"} 311
telemt_pool_swap_total 93
telemt_me_writer_removed_unexpected_total 26208
telemt_me_refill_failed_total 3067
telemt_me_writer_restored_same_endpoint_total 25843
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 261
telemt_user_connections_total{user="hello"} 219408
telemt_user_connections_current{user="hello"} 141
telemt_user_octets_from_client{user="hello"} 2861896441 (2.67 GB)
telemt_user_octets_to_client{user="hello"} 98428177903 (91.67 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 136809.9 (38h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 981121
telemt_connections_bad_total 77481
telemt_handshake_timeouts_total 12162
telemt_upstream_connect_attempt_total 28882
telemt_upstream_connect_success_total 28731
telemt_upstream_connect_fail_total 151
telemt_upstream_connect_attempts_per_request{bucket="1"} 28882
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13535
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15149
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 151
telemt_me_keepalive_timeout_total 168
telemt_me_reconnect_attempts_total 24537
telemt_me_reconnect_success_total 21915
telemt_me_reader_eof_total 23382
telemt_me_idle_close_by_peer_total 23381
telemt_me_route_drop_no_conn_total 709054
telemt_me_route_drop_channel_closed_total 135
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 956371
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 647
telemt_desync_full_logged_total 195
telemt_desync_suppressed_total 452
telemt_desync_frames_bucket_total{bucket="1_2"} 185
telemt_desync_frames_bucket_total{bucket="3_10"} 227
telemt_desync_frames_bucket_total{bucket="gt_10"} 235
telemt_pool_swap_total 123
telemt_me_writer_removed_unexpected_total 22264
telemt_me_refill_failed_total 77
telemt_me_writer_restored_same_endpoint_total 21888
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 349
telemt_user_connections_total{user="hello"} 814965
telemt_user_connections_current{user="hello"} 782
telemt_user_octets_from_client{user="hello"} 17557019716 (16.35 GB)
telemt_user_octets_to_client{user="hello"} 464256173848 (432.37 GB)
telemt_user_unique_ips_current{user="hello"} 263
telemt_user_unique_ips_recent_window{user="hello"} 102
```