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

# Server Metrics 2026-03-13 02:36:36 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 68592.5 (19h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 272014
telemt_connections_bad_total 2812
telemt_handshake_timeouts_total 5646
telemt_upstream_connect_attempt_total 17400
telemt_upstream_connect_success_total 17323
telemt_upstream_connect_fail_total 77
telemt_upstream_connect_attempts_per_request{bucket="1"} 17400
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7666
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9611
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 77
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1521
telemt_me_reconnect_attempts_total 17333
telemt_me_reconnect_success_total 13851
telemt_me_reader_eof_total 14799
telemt_me_idle_close_by_peer_total 14798
telemt_me_route_drop_no_conn_total 84610
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 226494
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 747
telemt_desync_full_logged_total 280
telemt_desync_suppressed_total 467
telemt_desync_frames_bucket_total{bucket="1_2"} 138
telemt_desync_frames_bucket_total{bucket="3_10"} 276
telemt_desync_frames_bucket_total{bucket="gt_10"} 333
telemt_pool_swap_total 60
telemt_me_writer_removed_unexpected_total 14108
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 13835
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 257
telemt_user_connections_total{user="hello"} 226260
telemt_user_connections_current{user="hello"} 231
telemt_user_octets_from_client{user="hello"} 4009905816 (3.73 GB)
telemt_user_octets_to_client{user="hello"} 111097402400 (103.47 GB)
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 68485.5 (19h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 125966
telemt_connections_bad_total 742
telemt_handshake_timeouts_total 982
telemt_upstream_connect_attempt_total 37646
telemt_upstream_connect_success_total 37187
telemt_upstream_connect_fail_total 458
telemt_upstream_connect_attempts_per_request{bucket="1"} 37645
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22985
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13700
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 502
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 458
telemt_me_keepalive_timeout_total 485
telemt_me_reconnect_attempts_total 61460
telemt_me_reconnect_success_total 17242
telemt_me_reader_eof_total 19109
telemt_me_idle_close_by_peer_total 19109
telemt_me_route_drop_no_conn_total 45351
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 103112
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
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 18754
telemt_me_refill_failed_total 1380
telemt_me_writer_restored_same_endpoint_total 17227
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1512
telemt_user_connections_total{user="hello"} 119612
telemt_user_connections_current{user="hello"} 56
telemt_user_octets_from_client{user="hello"} 1262474904 (1.18 GB)
telemt_user_octets_to_client{user="hello"} 35592929347 (33.15 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 21
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 68449.1 (19h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 151796
telemt_connections_bad_total 1822
telemt_handshake_timeouts_total 2423
telemt_upstream_connect_attempt_total 19020
telemt_upstream_connect_success_total 19018
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 19020
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8794
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10202
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 380
telemt_me_reconnect_attempts_total 16703
telemt_me_reconnect_success_total 15543
telemt_me_reader_eof_total 16612
telemt_me_idle_close_by_peer_total 16612
telemt_me_route_drop_no_conn_total 58027
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 141912
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
telemt_pool_swap_total 59
telemt_me_writer_removed_unexpected_total 15713
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 15523
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 170
telemt_user_connections_total{user="hello"} 141847
telemt_user_connections_current{user="hello"} 71
telemt_user_octets_from_client{user="hello"} 2719229344 (2.53 GB)
telemt_user_octets_to_client{user="hello"} 67119133732 (62.51 GB)
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 68425.0 (19h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 217119
telemt_connections_bad_total 13412
telemt_handshake_timeouts_total 1429
telemt_upstream_connect_attempt_total 31334
telemt_upstream_connect_success_total 21534
telemt_upstream_connect_fail_total 9800
telemt_upstream_connect_attempts_per_request{bucket="1"} 31334
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10874
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10492
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 160
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9800
telemt_me_keepalive_timeout_total 3272
telemt_me_reconnect_attempts_total 54751
telemt_me_reconnect_success_total 15259
telemt_me_reader_eof_total 16993
telemt_me_idle_close_by_peer_total 16986
telemt_me_route_drop_no_conn_total 78868
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 180402
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 14
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
telemt_me_writer_removed_unexpected_total 16705
telemt_me_refill_failed_total 1230
telemt_me_writer_restored_same_endpoint_total 15249
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1446
telemt_user_connections_total{user="hello"} 183153
telemt_user_connections_current{user="hello"} 120
telemt_user_octets_from_client{user="hello"} 3060403290 (2.85 GB)
telemt_user_octets_to_client{user="hello"} 75662045229 (70.47 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 18596.4 (5h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17227
telemt_connections_bad_total 3499
telemt_handshake_timeouts_total 27
telemt_upstream_connect_attempt_total 5708
telemt_upstream_connect_success_total 5654
telemt_upstream_connect_fail_total 54
telemt_upstream_connect_attempts_per_request{bucket="1"} 5708
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2485
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3145
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 54
telemt_me_keepalive_timeout_total 113
telemt_me_reconnect_attempts_total 4727
telemt_me_reconnect_success_total 4710
telemt_me_reader_eof_total 5049
telemt_me_idle_close_by_peer_total 5049
telemt_me_route_drop_no_conn_total 5049
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13210
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 4749
telemt_me_writer_restored_same_endpoint_total 4694
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 13210
telemt_user_connections_current{user="hello"} 52
telemt_user_octets_from_client{user="hello"} 85370492 (81.42 MB)
telemt_user_octets_to_client{user="hello"} 6362937436 (5.93 GB)
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 68381.2 (18h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 365553
telemt_connections_bad_total 6623
telemt_handshake_timeouts_total 2848
telemt_upstream_connect_attempt_total 14557
telemt_upstream_connect_success_total 14475
telemt_upstream_connect_fail_total 82
telemt_upstream_connect_attempts_per_request{bucket="1"} 14557
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6765
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7687
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 82
telemt_me_keepalive_timeout_total 1352
telemt_me_reconnect_attempts_total 14705
telemt_me_reconnect_success_total 11084
telemt_me_reader_eof_total 11897
telemt_me_idle_close_by_peer_total 11895
telemt_me_route_drop_no_conn_total 163800
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 357399
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 304
telemt_desync_full_logged_total 119
telemt_desync_suppressed_total 185
telemt_desync_frames_bucket_total{bucket="1_2"} 75
telemt_desync_frames_bucket_total{bucket="3_10"} 113
telemt_desync_frames_bucket_total{bucket="gt_10"} 116
telemt_pool_swap_total 61
telemt_me_writer_removed_unexpected_total 11332
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 11077
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 248
telemt_user_connections_total{user="hello"} 345657
telemt_user_connections_current{user="hello"} 228
telemt_user_octets_from_client{user="hello"} 5852056672 (5.45 GB)
telemt_user_octets_to_client{user="hello"} 205596716088 (191.48 GB)
telemt_user_unique_ips_current{user="hello"} 81
telemt_user_unique_ips_recent_window{user="hello"} 30
```