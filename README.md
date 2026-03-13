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

# Server Metrics 2026-03-13 14:29:22 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 111362.9 (30h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 460519
telemt_connections_bad_total 3217
telemt_handshake_timeouts_total 8593
telemt_upstream_connect_attempt_total 28008
telemt_upstream_connect_success_total 27877
telemt_upstream_connect_fail_total 130
telemt_upstream_connect_attempts_per_request{bucket="1"} 28007
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12583
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15231
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 130
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2428
telemt_me_reconnect_attempts_total 25841
telemt_me_reconnect_success_total 22310
telemt_me_reader_eof_total 23831
telemt_me_idle_close_by_peer_total 23830
telemt_me_route_drop_no_conn_total 149405
telemt_me_route_drop_channel_closed_total 28
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 403077
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1342
telemt_desync_full_logged_total 475
telemt_desync_suppressed_total 867
telemt_desync_frames_bucket_total{bucket="1_2"} 291
telemt_desync_frames_bucket_total{bucket="3_10"} 487
telemt_desync_frames_bucket_total{bucket="gt_10"} 564
telemt_pool_swap_total 100
telemt_me_writer_removed_unexpected_total 22654
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 22294
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 344
telemt_user_connections_total{user="hello"} 402655
telemt_user_connections_current{user="hello"} 391
telemt_user_octets_from_client{user="hello"} 7276553208 (6.78 GB)
telemt_user_octets_to_client{user="hello"} 186213328908 (173.42 GB)
telemt_user_unique_ips_current{user="hello"} 109
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 111255.7 (30h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 218037
telemt_connections_bad_total 1820
telemt_handshake_timeouts_total 1549
telemt_upstream_connect_attempt_total 76649
telemt_upstream_connect_success_total 75902
telemt_upstream_connect_fail_total 747
telemt_upstream_connect_attempts_per_request{bucket="1"} 76649
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52348
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22820
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 734
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 747
telemt_me_keepalive_timeout_total 1397
telemt_me_reconnect_attempts_total 108050
telemt_me_reconnect_success_total 26022
telemt_me_reader_eof_total 29345
telemt_me_idle_close_by_peer_total 29345
telemt_me_route_drop_no_conn_total 80109
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 161921
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 26
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
telemt_me_writer_removed_unexpected_total 28809
telemt_me_refill_failed_total 2559
telemt_me_writer_restored_same_endpoint_total 26005
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 2787
telemt_user_connections_total{user="hello"} 206027
telemt_user_connections_current{user="hello"} 203
telemt_user_octets_from_client{user="hello"} 2074984748 (1.93 GB)
telemt_user_octets_to_client{user="hello"} 66142980542 (61.60 GB)
telemt_user_msgs_from_client{user="hello"} 652376
telemt_user_msgs_to_client{user="hello"} 4456211
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 111219.6 (30h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 264136
telemt_connections_bad_total 2190
telemt_handshake_timeouts_total 11204
telemt_upstream_connect_attempt_total 29921
telemt_upstream_connect_success_total 29917
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 29921
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13881
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16008
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2287
telemt_me_reconnect_attempts_total 25527
telemt_me_reconnect_success_total 24311
telemt_me_reader_eof_total 26036
telemt_me_idle_close_by_peer_total 26036
telemt_me_route_drop_no_conn_total 95846
telemt_me_route_drop_channel_closed_total 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 241288
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 96
telemt_desync_full_logged_total 45
telemt_desync_suppressed_total 51
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 32
telemt_desync_frames_bucket_total{bucket="gt_10"} 57
telemt_pool_swap_total 100
telemt_me_writer_removed_unexpected_total 24577
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 24291
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 266
telemt_user_connections_total{user="hello"} 241203
telemt_user_connections_current{user="hello"} 152
telemt_user_octets_from_client{user="hello"} 9504610852 (8.85 GB)
telemt_user_octets_to_client{user="hello"} 102895132400 (95.83 GB)
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 111194.8 (30h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 362918
telemt_connections_bad_total 15043
telemt_handshake_timeouts_total 3624
telemt_upstream_connect_attempt_total 41916
telemt_upstream_connect_success_total 31784
telemt_upstream_connect_fail_total 10132
telemt_upstream_connect_attempts_per_request{bucket="1"} 41916
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16057
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15508
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 210
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10132
telemt_me_keepalive_timeout_total 4140
telemt_me_reconnect_attempts_total 97003
telemt_me_reconnect_success_total 23173
telemt_me_reader_eof_total 26182
telemt_me_idle_close_by_peer_total 26175
telemt_me_route_drop_no_conn_total 130086
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 313433
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1208
telemt_desync_full_logged_total 358
telemt_desync_suppressed_total 850
telemt_desync_frames_bucket_total{bucket="1_2"} 301
telemt_desync_frames_bucket_total{bucket="3_10"} 451
telemt_desync_frames_bucket_total{bucket="gt_10"} 456
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 25780
telemt_me_refill_failed_total 2302
telemt_me_writer_restored_same_endpoint_total 23163
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 2607
telemt_user_connections_total{user="hello"} 316343
telemt_user_connections_current{user="hello"} 238
telemt_user_octets_from_client{user="hello"} 6821371574 (6.35 GB)
telemt_user_octets_to_client{user="hello"} 119155675861 (110.97 GB)
telemt_user_msgs_from_client{user="hello"} 68310
telemt_user_msgs_to_client{user="hello"} 114408
telemt_user_unique_ips_current{user="hello"} 75
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 61366.5 (17h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 93924
telemt_connections_bad_total 12348
telemt_handshake_timeouts_total 1209
telemt_upstream_connect_attempt_total 25358
telemt_upstream_connect_success_total 25150
telemt_upstream_connect_fail_total 208
telemt_upstream_connect_attempts_per_request{bucket="1"} 25358
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13174
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11906
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 70
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 208
telemt_me_keepalive_timeout_total 1029
telemt_me_reconnect_attempts_total 27071
telemt_me_reconnect_success_total 17149
telemt_me_reader_eof_total 18402
telemt_me_idle_close_by_peer_total 18402
telemt_me_route_drop_no_conn_total 27913
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 72469
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 284
telemt_desync_full_logged_total 57
telemt_desync_suppressed_total 227
telemt_desync_frames_bucket_total{bucket="1_2"} 40
telemt_desync_frames_bucket_total{bucket="3_10"} 135
telemt_desync_frames_bucket_total{bucket="gt_10"} 109
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 17608
telemt_me_refill_failed_total 308
telemt_me_writer_restored_same_endpoint_total 17131
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 459
telemt_user_connections_total{user="hello"} 77369
telemt_user_connections_current{user="hello"} 111
telemt_user_octets_from_client{user="hello"} 914128757 (871.78 MB)
telemt_user_octets_to_client{user="hello"} 22429362903 (20.89 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 111151.9 (30h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 654851
telemt_connections_bad_total 18070
telemt_handshake_timeouts_total 20028
telemt_upstream_connect_attempt_total 23387
telemt_upstream_connect_success_total 23269
telemt_upstream_connect_fail_total 118
telemt_upstream_connect_attempts_per_request{bucket="1"} 23387
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10901
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12343
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 118
telemt_me_keepalive_timeout_total 2529
telemt_me_reconnect_attempts_total 22365
telemt_me_reconnect_success_total 17740
telemt_me_reader_eof_total 19049
telemt_me_idle_close_by_peer_total 19046
telemt_me_route_drop_no_conn_total 315946
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 621905
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 475
telemt_desync_full_logged_total 178
telemt_desync_suppressed_total 297
telemt_desync_frames_bucket_total{bucket="1_2"} 114
telemt_desync_frames_bucket_total{bucket="3_10"} 177
telemt_desync_frames_bucket_total{bucket="gt_10"} 184
telemt_pool_swap_total 103
telemt_me_writer_removed_unexpected_total 18115
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 17733
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 375
telemt_user_connections_total{user="hello"} 594853
telemt_user_connections_current{user="hello"} 523
telemt_user_octets_from_client{user="hello"} 10305919176 (9.60 GB)
telemt_user_octets_to_client{user="hello"} 311563316760 (290.17 GB)
telemt_user_unique_ips_current{user="hello"} 185
telemt_user_unique_ips_recent_window{user="hello"} 82
```