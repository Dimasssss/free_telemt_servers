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

# Server Metrics 2026-03-13 04:03:35 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 73811.5 (20h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 284335
telemt_connections_bad_total 3006
telemt_handshake_timeouts_total 5759
telemt_upstream_connect_attempt_total 18628
telemt_upstream_connect_success_total 18545
telemt_upstream_connect_fail_total 83
telemt_upstream_connect_attempts_per_request{bucket="1"} 18628
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8273
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10226
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 83
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1534
telemt_me_reconnect_attempts_total 18340
telemt_me_reconnect_success_total 14852
telemt_me_reader_eof_total 15872
telemt_me_idle_close_by_peer_total 15871
telemt_me_route_drop_no_conn_total 88423
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 237879
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 789
telemt_desync_full_logged_total 293
telemt_desync_suppressed_total 496
telemt_desync_frames_bucket_total{bucket="1_2"} 149
telemt_desync_frames_bucket_total{bucket="3_10"} 286
telemt_desync_frames_bucket_total{bucket="gt_10"} 354
telemt_pool_swap_total 65
telemt_me_writer_removed_unexpected_total 15123
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 14836
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 271
telemt_user_connections_total{user="hello"} 237819
telemt_user_connections_current{user="hello"} 234
telemt_user_octets_from_client{user="hello"} 4149535920 (3.86 GB)
telemt_user_octets_to_client{user="hello"} 116539493936 (108.54 GB)
telemt_user_unique_ips_current{user="hello"} 78
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 73704.2 (20h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 130894
telemt_connections_bad_total 746
telemt_handshake_timeouts_total 983
telemt_upstream_connect_attempt_total 39918
telemt_upstream_connect_success_total 39435
telemt_upstream_connect_fail_total 483
telemt_upstream_connect_attempts_per_request{bucket="1"} 39918
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23866
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15066
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 503
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 483
telemt_me_keepalive_timeout_total 536
telemt_me_reconnect_attempts_total 65817
telemt_me_reconnect_success_total 19257
telemt_me_reader_eof_total 21283
telemt_me_idle_close_by_peer_total 21283
telemt_me_route_drop_no_conn_total 47611
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 107871
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
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 20858
telemt_me_refill_failed_total 1453
telemt_me_writer_restored_same_endpoint_total 19242
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1601
telemt_user_connections_total{user="hello"} 124371
telemt_user_connections_current{user="hello"} 109
telemt_user_octets_from_client{user="hello"} 1294565404 (1.21 GB)
telemt_user_octets_to_client{user="hello"} 37298133671 (34.74 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 73667.6 (20h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 157673
telemt_connections_bad_total 1830
telemt_handshake_timeouts_total 2577
telemt_upstream_connect_attempt_total 20400
telemt_upstream_connect_success_total 20398
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 20400
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9409
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10966
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 404
telemt_me_reconnect_attempts_total 17842
telemt_me_reconnect_success_total 16679
telemt_me_reader_eof_total 17850
telemt_me_idle_close_by_peer_total 17850
telemt_me_route_drop_no_conn_total 61020
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 147449
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
telemt_pool_swap_total 65
telemt_me_writer_removed_unexpected_total 16862
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 16659
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 183
telemt_user_connections_total{user="hello"} 147374
telemt_user_connections_current{user="hello"} 182
telemt_user_octets_from_client{user="hello"} 2777752120 (2.59 GB)
telemt_user_octets_to_client{user="hello"} 69413679972 (64.65 GB)
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 73643.5 (20h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 226408
telemt_connections_bad_total 13468
telemt_handshake_timeouts_total 1446
telemt_upstream_connect_attempt_total 32827
telemt_upstream_connect_success_total 22978
telemt_upstream_connect_fail_total 9849
telemt_upstream_connect_attempts_per_request{bucket="1"} 32827
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11558
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11251
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 161
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9849
telemt_me_keepalive_timeout_total 3305
telemt_me_reconnect_attempts_total 59968
telemt_me_reconnect_success_total 16440
telemt_me_reader_eof_total 18322
telemt_me_idle_close_by_peer_total 18315
telemt_me_route_drop_no_conn_total 82577
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 189090
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
telemt_me_writer_removed_unexpected_total 18023
telemt_me_refill_failed_total 1356
telemt_me_writer_restored_same_endpoint_total 16430
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1583
telemt_user_connections_total{user="hello"} 191838
telemt_user_connections_current{user="hello"} 129
telemt_user_octets_from_client{user="hello"} 3187447582 (2.97 GB)
telemt_user_octets_to_client{user="hello"} 77820250589 (72.48 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 23815.1 (6h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 23654
telemt_connections_bad_total 4465
telemt_handshake_timeouts_total 91
telemt_upstream_connect_attempt_total 7436
telemt_upstream_connect_success_total 7367
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 7436
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3215
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4123
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_keepalive_timeout_total 171
telemt_me_reconnect_attempts_total 6181
telemt_me_reconnect_success_total 6159
telemt_me_reader_eof_total 6608
telemt_me_idle_close_by_peer_total 6608
telemt_me_route_drop_no_conn_total 6693
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 18423
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 6213
telemt_me_writer_restored_same_endpoint_total 6141
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 54
telemt_user_connections_total{user="hello"} 18423
telemt_user_connections_current{user="hello"} 45
telemt_user_octets_from_client{user="hello"} 134319504 (128.10 MB)
telemt_user_octets_to_client{user="hello"} 8421433868 (7.84 GB)
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 73600.0 (20h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 381808
telemt_connections_bad_total 7316
telemt_handshake_timeouts_total 2901
telemt_upstream_connect_attempt_total 15656
telemt_upstream_connect_success_total 15570
telemt_upstream_connect_fail_total 86
telemt_upstream_connect_attempts_per_request{bucket="1"} 15656
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7240
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8305
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 86
telemt_me_keepalive_timeout_total 1424
telemt_me_reconnect_attempts_total 15541
telemt_me_reconnect_success_total 11914
telemt_me_reader_eof_total 12792
telemt_me_idle_close_by_peer_total 12789
telemt_me_route_drop_no_conn_total 170713
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 372625
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
telemt_pool_swap_total 67
telemt_me_writer_removed_unexpected_total 12181
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 11907
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 267
telemt_user_connections_total{user="hello"} 360871
telemt_user_connections_current{user="hello"} 314
telemt_user_octets_from_client{user="hello"} 6037833420 (5.62 GB)
telemt_user_octets_to_client{user="hello"} 216473520236 (201.61 GB)
telemt_user_unique_ips_current{user="hello"} 117
telemt_user_unique_ips_recent_window{user="hello"} 35
```