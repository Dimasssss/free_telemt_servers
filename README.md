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

# Server Metrics 2026-03-13 04:49:39 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 76575.1 (21h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 291733
telemt_connections_bad_total 3032
telemt_handshake_timeouts_total 5779
telemt_upstream_connect_attempt_total 19342
telemt_upstream_connect_success_total 19251
telemt_upstream_connect_fail_total 91
telemt_upstream_connect_attempts_per_request{bucket="1"} 19342
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8603
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10600
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 91
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1556
telemt_me_reconnect_attempts_total 18890
telemt_me_reconnect_success_total 15394
telemt_me_reader_eof_total 16452
telemt_me_idle_close_by_peer_total 16451
telemt_me_route_drop_no_conn_total 91010
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 244993
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 834
telemt_desync_full_logged_total 311
telemt_desync_suppressed_total 523
telemt_desync_frames_bucket_total{bucket="1_2"} 164
telemt_desync_frames_bucket_total{bucket="3_10"} 306
telemt_desync_frames_bucket_total{bucket="gt_10"} 364
telemt_pool_swap_total 68
telemt_me_writer_removed_unexpected_total 15669
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 15378
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 275
telemt_user_connections_total{user="hello"} 244931
telemt_user_connections_current{user="hello"} 227
telemt_user_octets_from_client{user="hello"} 4241946016 (3.95 GB)
telemt_user_octets_to_client{user="hello"} 120683119356 (112.39 GB)
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 76468.0 (21h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 133945
telemt_connections_bad_total 752
telemt_handshake_timeouts_total 1004
telemt_upstream_connect_attempt_total 40934
telemt_upstream_connect_success_total 40425
telemt_upstream_connect_fail_total 509
telemt_upstream_connect_attempts_per_request{bucket="1"} 40934
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24246
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15673
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 506
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 509
telemt_me_keepalive_timeout_total 560
telemt_me_reconnect_attempts_total 66678
telemt_me_reconnect_success_total 20116
telemt_me_reader_eof_total 22178
telemt_me_idle_close_by_peer_total 22178
telemt_me_route_drop_no_conn_total 49456
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 110761
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
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 21724
telemt_me_refill_failed_total 1453
telemt_me_writer_restored_same_endpoint_total 20101
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1608
telemt_user_connections_total{user="hello"} 127261
telemt_user_connections_current{user="hello"} 112
telemt_user_octets_from_client{user="hello"} 1311985392 (1.22 GB)
telemt_user_octets_to_client{user="hello"} 38205573955 (35.58 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 76431.6 (21h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 161558
telemt_connections_bad_total 1846
telemt_handshake_timeouts_total 2609
telemt_upstream_connect_attempt_total 21080
telemt_upstream_connect_success_total 21078
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 21080
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9713
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11342
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 446
telemt_me_reconnect_attempts_total 18393
telemt_me_reconnect_success_total 17229
telemt_me_reader_eof_total 18448
telemt_me_idle_close_by_peer_total 18448
telemt_me_route_drop_no_conn_total 62372
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 151121
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
telemt_pool_swap_total 68
telemt_me_writer_removed_unexpected_total 17419
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 17209
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 190
telemt_user_connections_total{user="hello"} 151048
telemt_user_connections_current{user="hello"} 97
telemt_user_octets_from_client{user="hello"} 2853599208 (2.66 GB)
telemt_user_octets_to_client{user="hello"} 70525157420 (65.68 GB)
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 76407.3 (21h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 232906
telemt_connections_bad_total 13530
telemt_handshake_timeouts_total 1466
telemt_upstream_connect_attempt_total 33527
telemt_upstream_connect_success_total 23653
telemt_upstream_connect_fail_total 9874
telemt_upstream_connect_attempts_per_request{bucket="1"} 33527
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11913
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11566
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9874
telemt_me_keepalive_timeout_total 3310
telemt_me_reconnect_attempts_total 64386
telemt_me_reconnect_success_total 16984
telemt_me_reader_eof_total 18988
telemt_me_idle_close_by_peer_total 18981
telemt_me_route_drop_no_conn_total 85021
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 194986
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 506
telemt_desync_full_logged_total 146
telemt_desync_suppressed_total 360
telemt_desync_frames_bucket_total{bucket="1_2"} 128
telemt_desync_frames_bucket_total{bucket="3_10"} 188
telemt_desync_frames_bucket_total{bucket="gt_10"} 190
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 18689
telemt_me_refill_failed_total 1477
telemt_me_writer_restored_same_endpoint_total 16974
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1705
telemt_user_connections_total{user="hello"} 197734
telemt_user_connections_current{user="hello"} 126
telemt_user_octets_from_client{user="hello"} 3246631798 (3.02 GB)
telemt_user_octets_to_client{user="hello"} 79325131109 (73.88 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 26578.9 (7h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 27259
telemt_connections_bad_total 4964
telemt_handshake_timeouts_total 102
telemt_upstream_connect_attempt_total 8392
telemt_upstream_connect_success_total 8310
telemt_upstream_connect_fail_total 82
telemt_upstream_connect_attempts_per_request{bucket="1"} 8392
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3651
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4629
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 82
telemt_me_keepalive_timeout_total 200
telemt_me_reconnect_attempts_total 6995
telemt_me_reconnect_success_total 6969
telemt_me_reader_eof_total 7451
telemt_me_idle_close_by_peer_total 7451
telemt_me_route_drop_no_conn_total 7510
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 21435
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 7032
telemt_me_writer_restored_same_endpoint_total 6951
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 63
telemt_user_connections_total{user="hello"} 21435
telemt_user_connections_current{user="hello"} 52
telemt_user_octets_from_client{user="hello"} 151030496 (144.03 MB)
telemt_user_octets_to_client{user="hello"} 9129606200 (8.50 GB)
telemt_user_unique_ips_current{user="hello"} 23
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 76363.8 (21h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 392407
telemt_connections_bad_total 7710
telemt_handshake_timeouts_total 2956
telemt_upstream_connect_attempt_total 16250
telemt_upstream_connect_success_total 16159
telemt_upstream_connect_fail_total 91
telemt_upstream_connect_attempts_per_request{bucket="1"} 16250
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7514
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8620
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 91
telemt_me_keepalive_timeout_total 1433
telemt_me_reconnect_attempts_total 16000
telemt_me_reconnect_success_total 12371
telemt_me_reader_eof_total 13282
telemt_me_idle_close_by_peer_total 13279
telemt_me_route_drop_no_conn_total 175314
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 382537
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
telemt_pool_swap_total 70
telemt_me_writer_removed_unexpected_total 12641
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 12364
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 270
telemt_user_connections_total{user="hello"} 370781
telemt_user_connections_current{user="hello"} 308
telemt_user_octets_from_client{user="hello"} 6154142428 (5.73 GB)
telemt_user_octets_to_client{user="hello"} 219177712592 (204.13 GB)
telemt_user_unique_ips_current{user="hello"} 122
telemt_user_unique_ips_recent_window{user="hello"} 48
```