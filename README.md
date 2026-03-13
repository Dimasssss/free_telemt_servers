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

# Server Metrics 2026-03-13 03:38:00 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 72276.3 (20h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 280441
telemt_connections_bad_total 2966
telemt_handshake_timeouts_total 5742
telemt_upstream_connect_attempt_total 18295
telemt_upstream_connect_success_total 18213
telemt_upstream_connect_fail_total 82
telemt_upstream_connect_attempts_per_request{bucket="1"} 18295
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8111
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10056
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 82
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1530
telemt_me_reconnect_attempts_total 18051
telemt_me_reconnect_success_total 14564
telemt_me_reader_eof_total 15570
telemt_me_idle_close_by_peer_total 15569
telemt_me_route_drop_no_conn_total 87278
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 234130
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 782
telemt_desync_full_logged_total 289
telemt_desync_suppressed_total 493
telemt_desync_frames_bucket_total{bucket="1_2"} 147
telemt_desync_frames_bucket_total{bucket="3_10"} 282
telemt_desync_frames_bucket_total{bucket="gt_10"} 353
telemt_pool_swap_total 64
telemt_me_writer_removed_unexpected_total 14832
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 14548
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 268
telemt_user_connections_total{user="hello"} 234070
telemt_user_connections_current{user="hello"} 209
telemt_user_octets_from_client{user="hello"} 4116593784 (3.83 GB)
telemt_user_octets_to_client{user="hello"} 115320715132 (107.40 GB)
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 72169.3 (20h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 129261
telemt_connections_bad_total 745
telemt_handshake_timeouts_total 983
telemt_upstream_connect_attempt_total 39536
telemt_upstream_connect_success_total 39057
telemt_upstream_connect_fail_total 479
telemt_upstream_connect_attempts_per_request{bucket="1"} 39536
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23702
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14852
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 503
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 479
telemt_me_keepalive_timeout_total 526
telemt_me_reconnect_attempts_total 65482
telemt_me_reconnect_success_total 18924
telemt_me_reader_eof_total 20923
telemt_me_idle_close_by_peer_total 20923
telemt_me_route_drop_no_conn_total 46441
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 106292
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 16
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
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 20521
telemt_me_refill_failed_total 1453
telemt_me_writer_restored_same_endpoint_total 18909
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1597
telemt_user_connections_total{user="hello"} 122792
telemt_user_connections_current{user="hello"} 102
telemt_user_octets_from_client{user="hello"} 1281942984 (1.19 GB)
telemt_user_octets_to_client{user="hello"} 36327474447 (33.83 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 72132.9 (20h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 155408
telemt_connections_bad_total 1826
telemt_handshake_timeouts_total 2437
telemt_upstream_connect_attempt_total 20023
telemt_upstream_connect_success_total 20021
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 20023
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9262
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10736
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 395
telemt_me_reconnect_attempts_total 17508
telemt_me_reconnect_success_total 16345
telemt_me_reader_eof_total 17484
telemt_me_idle_close_by_peer_total 17484
telemt_me_route_drop_no_conn_total 59805
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 145392
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
telemt_pool_swap_total 64
telemt_me_writer_removed_unexpected_total 16524
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 16325
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 179
telemt_user_connections_total{user="hello"} 145317
telemt_user_connections_current{user="hello"} 108
telemt_user_octets_from_client{user="hello"} 2752883140 (2.56 GB)
telemt_user_octets_to_client{user="hello"} 69121709636 (64.37 GB)
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 72108.7 (20h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 223075
telemt_connections_bad_total 13467
telemt_handshake_timeouts_total 1441
telemt_upstream_connect_attempt_total 32256
telemt_upstream_connect_success_total 22417
telemt_upstream_connect_fail_total 9839
telemt_upstream_connect_attempts_per_request{bucket="1"} 32256
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11261
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10987
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 161
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9839
telemt_me_keepalive_timeout_total 3300
telemt_me_reconnect_attempts_total 59455
telemt_me_reconnect_success_total 15928
telemt_me_reader_eof_total 17804
telemt_me_idle_close_by_peer_total 17797
telemt_me_route_drop_no_conn_total 81177
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 186070
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 505
telemt_desync_full_logged_total 145
telemt_desync_suppressed_total 360
telemt_desync_frames_bucket_total{bucket="1_2"} 127
telemt_desync_frames_bucket_total{bucket="3_10"} 188
telemt_desync_frames_bucket_total{bucket="gt_10"} 190
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 17505
telemt_me_refill_failed_total 1356
telemt_me_writer_restored_same_endpoint_total 15918
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1577
telemt_user_connections_total{user="hello"} 188820
telemt_user_connections_current{user="hello"} 134
telemt_user_octets_from_client{user="hello"} 3152107286 (2.94 GB)
telemt_user_octets_to_client{user="hello"} 77023369929 (71.73 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 22280.1 (6h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21553
telemt_connections_bad_total 4182
telemt_handshake_timeouts_total 47
telemt_upstream_connect_attempt_total 6984
telemt_upstream_connect_success_total 6920
telemt_upstream_connect_fail_total 64
telemt_upstream_connect_attempts_per_request{bucket="1"} 6984
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3020
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3872
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 64
telemt_me_keepalive_timeout_total 158
telemt_me_reconnect_attempts_total 5821
telemt_me_reconnect_success_total 5802
telemt_me_reader_eof_total 6214
telemt_me_idle_close_by_peer_total 6214
telemt_me_route_drop_no_conn_total 6269
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16717
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 5849
telemt_me_writer_restored_same_endpoint_total 5784
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 47
telemt_user_connections_total{user="hello"} 16717
telemt_user_connections_current{user="hello"} 36
telemt_user_octets_from_client{user="hello"} 126281072 (120.43 MB)
telemt_user_octets_to_client{user="hello"} 7032617532 (6.55 GB)
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 72065.0 (20h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 376050
telemt_connections_bad_total 6674
telemt_handshake_timeouts_total 2874
telemt_upstream_connect_attempt_total 15360
telemt_upstream_connect_success_total 15274
telemt_upstream_connect_fail_total 86
telemt_upstream_connect_attempts_per_request{bucket="1"} 15360
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7107
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8142
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 86
telemt_me_keepalive_timeout_total 1423
telemt_me_reconnect_attempts_total 15302
telemt_me_reconnect_success_total 11677
telemt_me_reader_eof_total 12538
telemt_me_idle_close_by_peer_total 12535
telemt_me_route_drop_no_conn_total 168693
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 367625
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 314
telemt_desync_full_logged_total 123
telemt_desync_suppressed_total 191
telemt_desync_frames_bucket_total{bucket="1_2"} 75
telemt_desync_frames_bucket_total{bucket="3_10"} 116
telemt_desync_frames_bucket_total{bucket="gt_10"} 123
telemt_pool_swap_total 65
telemt_me_writer_removed_unexpected_total 11938
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 11670
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 261
telemt_user_connections_total{user="hello"} 355871
telemt_user_connections_current{user="hello"} 259
telemt_user_octets_from_client{user="hello"} 5980014000 (5.57 GB)
telemt_user_octets_to_client{user="hello"} 214176885972 (199.47 GB)
telemt_user_unique_ips_current{user="hello"} 99
telemt_user_unique_ips_recent_window{user="hello"} 31
```