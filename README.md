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

# Server Metrics 2026-03-16 01:00:37 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 96368.6 (26h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 418999
telemt_connections_bad_total 5358
telemt_handshake_timeouts_total 14253
telemt_upstream_connect_attempt_total 23047
telemt_upstream_connect_success_total 22937
telemt_upstream_connect_fail_total 110
telemt_upstream_connect_attempts_per_request{bucket="1"} 23047
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10157
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12733
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 110
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 33
telemt_me_reconnect_attempts_total 21563
telemt_me_reconnect_success_total 18152
telemt_me_reader_eof_total 19393
telemt_me_idle_close_by_peer_total 19393
telemt_me_route_drop_no_conn_total 492594
telemt_me_route_drop_channel_closed_total 79
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 444708
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2193
telemt_desync_full_logged_total 880
telemt_desync_suppressed_total 1313
telemt_desync_frames_bucket_total{bucket="1_2"} 427
telemt_desync_frames_bucket_total{bucket="3_10"} 849
telemt_desync_frames_bucket_total{bucket="gt_10"} 917
telemt_pool_swap_total 90
telemt_me_writer_removed_unexpected_total 18459
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 18118
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 307
telemt_user_connections_total{user="hello"} 383779
telemt_user_connections_current{user="hello"} 251
telemt_user_octets_from_client{user="hello"} 8248093752 (7.68 GB)
telemt_user_octets_to_client{user="hello"} 282174260676 (262.80 GB)
telemt_user_unique_ips_current{user="hello"} 82
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 96374.9 (26h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 174039
telemt_connections_bad_total 2914
telemt_handshake_timeouts_total 14539
telemt_upstream_connect_attempt_total 26288
telemt_upstream_connect_success_total 26213
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 26288
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11396
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14208
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 609
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 1305
telemt_me_reconnect_attempts_total 27902
telemt_me_reconnect_success_total 21001
telemt_me_reader_eof_total 22474
telemt_me_idle_close_by_peer_total 22473
telemt_me_route_drop_no_conn_total 70232
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 149545
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 24
telemt_desync_full_logged_total 8
telemt_desync_suppressed_total 16
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 9
telemt_pool_swap_total 81
telemt_me_writer_removed_unexpected_total 21520
telemt_me_refill_failed_total 208
telemt_me_writer_restored_same_endpoint_total 20985
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 519
telemt_user_connections_total{user="hello"} 149806
telemt_user_connections_current{user="hello"} 98
telemt_user_octets_from_client{user="hello"} 3393927813 (3.16 GB)
telemt_user_octets_to_client{user="hello"} 77925189692 (72.57 GB)
telemt_user_msgs_from_client{user="hello"} 721
telemt_user_msgs_to_client{user="hello"} 1482
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 96367.6 (26h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 184119
telemt_connections_bad_total 2093
telemt_handshake_timeouts_total 3567
telemt_upstream_connect_attempt_total 27378
telemt_upstream_connect_success_total 27370
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 27378
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11870
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15447
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 29900
telemt_me_reconnect_success_total 22518
telemt_me_reader_eof_total 24220
telemt_me_idle_close_by_peer_total 24219
telemt_me_route_drop_no_conn_total 67874
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 153547
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 60
telemt_desync_full_logged_total 24
telemt_desync_suppressed_total 36
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 30
telemt_desync_frames_bucket_total{bucket="gt_10"} 25
telemt_pool_swap_total 85
telemt_me_writer_removed_unexpected_total 22968
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 22510
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 450
telemt_user_connections_total{user="hello"} 153422
telemt_user_connections_current{user="hello"} 81
telemt_user_octets_from_client{user="hello"} 13111710208 (12.21 GB)
telemt_user_octets_to_client{user="hello"} 98794818688 (92.01 GB)
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 96367.2 (26h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 254923
telemt_connections_bad_total 1214
telemt_handshake_timeouts_total 1648
telemt_upstream_connect_attempt_total 22544
telemt_upstream_connect_success_total 22523
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 22544
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10794
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11615
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 103
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 17838
telemt_me_reconnect_success_total 17731
telemt_me_reader_eof_total 18907
telemt_me_idle_close_by_peer_total 18907
telemt_me_route_drop_no_conn_total 91786
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 235439
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 875
telemt_desync_full_logged_total 306
telemt_desync_suppressed_total 569
telemt_desync_frames_bucket_total{bucket="1_2"} 175
telemt_desync_frames_bucket_total{bucket="3_10"} 376
telemt_desync_frames_bucket_total{bucket="gt_10"} 324
telemt_pool_swap_total 92
telemt_me_writer_removed_unexpected_total 17946
telemt_me_writer_restored_same_endpoint_total 17720
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 215
telemt_user_connections_total{user="hello"} 235351
telemt_user_connections_current{user="hello"} 96
telemt_user_octets_from_client{user="hello"} 4121695204 (3.84 GB)
telemt_user_octets_to_client{user="hello"} 107515375064 (100.13 GB)
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 71438.7 (19h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 163615
telemt_connections_bad_total 29571
telemt_handshake_timeouts_total 2829
telemt_upstream_connect_attempt_total 20475
telemt_upstream_connect_success_total 20356
telemt_upstream_connect_fail_total 119
telemt_upstream_connect_attempts_per_request{bucket="1"} 20475
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9124
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11111
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 121
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 119
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 111085
telemt_me_reconnect_success_total 16624
telemt_me_reader_eof_total 17614
telemt_me_idle_close_by_peer_total 17614
telemt_me_route_drop_no_conn_total 51707
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 126648
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 339
telemt_desync_full_logged_total 80
telemt_desync_suppressed_total 259
telemt_desync_frames_bucket_total{bucket="1_2"} 51
telemt_desync_frames_bucket_total{bucket="3_10"} 129
telemt_desync_frames_bucket_total{bucket="gt_10"} 159
telemt_pool_swap_total 60
telemt_me_writer_removed_unexpected_total 16750
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 16520
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 126
telemt_user_connections_total{user="hello"} 126769
telemt_user_connections_current{user="hello"} 49
telemt_user_octets_from_client{user="hello"} 1831489357 (1.71 GB)
telemt_user_octets_to_client{user="hello"} 44529183615 (41.47 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 22
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 96366.4 (26h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 635771
telemt_connections_bad_total 58662
telemt_handshake_timeouts_total 4880
telemt_upstream_connect_attempt_total 20364
telemt_upstream_connect_success_total 20249
telemt_upstream_connect_fail_total 115
telemt_upstream_connect_attempts_per_request{bucket="1"} 20364
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9660
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10547
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 115
telemt_me_keepalive_timeout_total 62
telemt_me_reconnect_attempts_total 16759
telemt_me_reconnect_success_total 15439
telemt_me_reader_eof_total 16456
telemt_me_idle_close_by_peer_total 16456
telemt_me_route_drop_no_conn_total 578365
telemt_me_route_drop_channel_closed_total 96
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 672942
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
telemt_pool_swap_total 87
telemt_me_writer_removed_unexpected_total 15660
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 15412
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 221
telemt_user_connections_total{user="hello"} 531627
telemt_user_connections_current{user="hello"} 299
telemt_user_octets_from_client{user="hello"} 12666654040 (11.80 GB)
telemt_user_octets_to_client{user="hello"} 327728694808 (305.22 GB)
telemt_user_unique_ips_current{user="hello"} 133
telemt_user_unique_ips_recent_window{user="hello"} 36
```