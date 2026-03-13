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

# Server Metrics 2026-03-13 06:21:47 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 82103.4 (22h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 310770
telemt_connections_bad_total 3086
telemt_handshake_timeouts_total 6499
telemt_upstream_connect_attempt_total 20730
telemt_upstream_connect_success_total 20632
telemt_upstream_connect_fail_total 98
telemt_upstream_connect_attempts_per_request{bucket="1"} 20730
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9292
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11292
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 98
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1616
telemt_me_reconnect_attempts_total 19994
telemt_me_reconnect_success_total 16493
telemt_me_reader_eof_total 17638
telemt_me_idle_close_by_peer_total 17637
telemt_me_route_drop_no_conn_total 96752
telemt_me_route_drop_channel_closed_total 16
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 262552
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 915
telemt_desync_full_logged_total 340
telemt_desync_suppressed_total 575
telemt_desync_frames_bucket_total{bucket="1_2"} 182
telemt_desync_frames_bucket_total{bucket="3_10"} 334
telemt_desync_frames_bucket_total{bucket="gt_10"} 399
telemt_pool_swap_total 74
telemt_me_writer_removed_unexpected_total 16780
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 16477
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 287
telemt_user_connections_total{user="hello"} 262483
telemt_user_connections_current{user="hello"} 285
telemt_user_octets_from_client{user="hello"} 4465610612 (4.16 GB)
telemt_user_octets_to_client{user="hello"} 125551744444 (116.93 GB)
telemt_user_unique_ips_current{user="hello"} 95
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 81996.3 (22h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 142506
telemt_connections_bad_total 1421
telemt_handshake_timeouts_total 1062
telemt_upstream_connect_attempt_total 42991
telemt_upstream_connect_success_total 42433
telemt_upstream_connect_fail_total 558
telemt_upstream_connect_attempts_per_request{bucket="1"} 42991
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25131
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16793
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 509
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 558
telemt_me_keepalive_timeout_total 624
telemt_me_reconnect_attempts_total 71008
telemt_me_reconnect_success_total 21818
telemt_me_reader_eof_total 24008
telemt_me_idle_close_by_peer_total 24008
telemt_me_route_drop_no_conn_total 53624
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 118358
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 17
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
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 23523
telemt_me_refill_failed_total 1535
telemt_me_writer_restored_same_endpoint_total 21803
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1705
telemt_user_connections_total{user="hello"} 134853
telemt_user_connections_current{user="hello"} 122
telemt_user_octets_from_client{user="hello"} 1396102924 (1.30 GB)
telemt_user_octets_to_client{user="hello"} 42092313283 (39.20 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 81959.8 (22h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 172415
telemt_connections_bad_total 1910
telemt_handshake_timeouts_total 2828
telemt_upstream_connect_attempt_total 22477
telemt_upstream_connect_success_total 22475
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 22477
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10346
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12106
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 499
telemt_me_reconnect_attempts_total 19509
telemt_me_reconnect_success_total 18338
telemt_me_reader_eof_total 19654
telemt_me_idle_close_by_peer_total 19654
telemt_me_route_drop_no_conn_total 66677
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 161252
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 62
telemt_desync_full_logged_total 30
telemt_desync_suppressed_total 32
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 20
telemt_desync_frames_bucket_total{bucket="gt_10"} 39
telemt_pool_swap_total 74
telemt_me_writer_removed_unexpected_total 18537
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 18318
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 199
telemt_user_connections_total{user="hello"} 161180
telemt_user_connections_current{user="hello"} 119
telemt_user_octets_from_client{user="hello"} 2952015612 (2.75 GB)
telemt_user_octets_to_client{user="hello"} 72783490528 (67.78 GB)
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 81935.5 (22h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 248853
telemt_connections_bad_total 13611
telemt_handshake_timeouts_total 1833
telemt_upstream_connect_attempt_total 34895
telemt_upstream_connect_success_total 24974
telemt_upstream_connect_fail_total 9920
telemt_upstream_connect_attempts_per_request{bucket="1"} 34894
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12545
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12246
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 175
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9920
telemt_me_keepalive_timeout_total 3347
telemt_me_reconnect_attempts_total 69572
telemt_me_reconnect_success_total 18037
telemt_me_reader_eof_total 20185
telemt_me_idle_close_by_peer_total 20178
telemt_me_route_drop_no_conn_total 90428
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 209534
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 629
telemt_desync_full_logged_total 184
telemt_desync_suppressed_total 445
telemt_desync_frames_bucket_total{bucket="1_2"} 158
telemt_desync_frames_bucket_total{bucket="3_10"} 240
telemt_desync_frames_bucket_total{bucket="gt_10"} 231
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 19878
telemt_me_refill_failed_total 1606
telemt_me_writer_restored_same_endpoint_total 18027
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1841
telemt_user_connections_total{user="hello"} 212274
telemt_user_connections_current{user="hello"} 156
telemt_user_octets_from_client{user="hello"} 3329791846 (3.10 GB)
telemt_user_octets_to_client{user="hello"} 82244114617 (76.60 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 32107.1 (8h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 36336
telemt_connections_bad_total 6682
telemt_handshake_timeouts_total 155
telemt_upstream_connect_attempt_total 11132
telemt_upstream_connect_success_total 11026
telemt_upstream_connect_fail_total 106
telemt_upstream_connect_attempts_per_request{bucket="1"} 11132
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4789
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6197
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 106
telemt_me_keepalive_timeout_total 267
telemt_me_reconnect_attempts_total 10377
telemt_me_reconnect_success_total 9413
telemt_me_reader_eof_total 10034
telemt_me_idle_close_by_peer_total 10034
telemt_me_route_drop_no_conn_total 9963
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 28548
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 9526
telemt_me_refill_failed_total 29
telemt_me_writer_restored_same_endpoint_total 9395
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 113
telemt_user_connections_total{user="hello"} 28548
telemt_user_connections_current{user="hello"} 56
telemt_user_octets_from_client{user="hello"} 214694956 (204.75 MB)
telemt_user_octets_to_client{user="hello"} 9974170232 (9.29 GB)
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 81892.0 (22h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 419586
telemt_connections_bad_total 8056
telemt_handshake_timeouts_total 3192
telemt_upstream_connect_attempt_total 17438
telemt_upstream_connect_success_total 17342
telemt_upstream_connect_fail_total 96
telemt_upstream_connect_attempts_per_request{bucket="1"} 17438
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8071
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9246
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 96
telemt_me_keepalive_timeout_total 1454
telemt_me_reconnect_attempts_total 16922
telemt_me_reconnect_success_total 13289
telemt_me_reader_eof_total 14270
telemt_me_idle_close_by_peer_total 14267
telemt_me_route_drop_no_conn_total 186513
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 406983
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 360
telemt_desync_full_logged_total 137
telemt_desync_suppressed_total 223
telemt_desync_frames_bucket_total{bucket="1_2"} 86
telemt_desync_frames_bucket_total{bucket="3_10"} 128
telemt_desync_frames_bucket_total{bucket="gt_10"} 146
telemt_pool_swap_total 76
telemt_me_writer_removed_unexpected_total 13568
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 13282
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 279
telemt_user_connections_total{user="hello"} 395218
telemt_user_connections_current{user="hello"} 375
telemt_user_octets_from_client{user="hello"} 6470338180 (6.03 GB)
telemt_user_octets_to_client{user="hello"} 232334291396 (216.38 GB)
telemt_user_unique_ips_current{user="hello"} 142
telemt_user_unique_ips_recent_window{user="hello"} 53
```