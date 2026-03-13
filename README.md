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

# Server Metrics 2026-03-13 14:03:54 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 109835.7 (30h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 453414
telemt_connections_bad_total 3215
telemt_handshake_timeouts_total 8506
telemt_upstream_connect_attempt_total 27669
telemt_upstream_connect_success_total 27539
telemt_upstream_connect_fail_total 130
telemt_upstream_connect_attempts_per_request{bucket="1"} 27669
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12432
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15044
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 130
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2410
telemt_me_reconnect_attempts_total 25577
telemt_me_reconnect_success_total 22047
telemt_me_reader_eof_total 23544
telemt_me_idle_close_by_peer_total 23543
telemt_me_route_drop_no_conn_total 145695
telemt_me_route_drop_channel_closed_total 27
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 396396
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1317
telemt_desync_full_logged_total 468
telemt_desync_suppressed_total 849
telemt_desync_frames_bucket_total{bucket="1_2"} 285
telemt_desync_frames_bucket_total{bucket="3_10"} 479
telemt_desync_frames_bucket_total{bucket="gt_10"} 553
telemt_pool_swap_total 98
telemt_me_writer_removed_unexpected_total 22386
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 22031
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 339
telemt_user_connections_total{user="hello"} 395975
telemt_user_connections_current{user="hello"} 371
telemt_user_octets_from_client{user="hello"} 7158777936 (6.67 GB)
telemt_user_octets_to_client{user="hello"} 181341944544 (168.89 GB)
telemt_user_unique_ips_current{user="hello"} 103
telemt_user_unique_ips_recent_window{user="hello"} 52
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 109728.6 (30h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 212770
telemt_connections_bad_total 1759
telemt_handshake_timeouts_total 1530
telemt_upstream_connect_attempt_total 72326
telemt_upstream_connect_success_total 71588
telemt_upstream_connect_fail_total 738
telemt_upstream_connect_attempts_per_request{bucket="1"} 72326
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 48497
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22404
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 687
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 738
telemt_me_keepalive_timeout_total 1396
telemt_me_reconnect_attempts_total 105296
telemt_me_reconnect_success_total 26020
telemt_me_reader_eof_total 29257
telemt_me_idle_close_by_peer_total 29257
telemt_me_route_drop_no_conn_total 79930
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 161102
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 25
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
telemt_me_writer_removed_unexpected_total 28721
telemt_me_refill_failed_total 2473
telemt_me_writer_restored_same_endpoint_total 26003
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 2701
telemt_user_connections_total{user="hello"} 200984
telemt_user_connections_current{user="hello"} 208
telemt_user_octets_from_client{user="hello"} 2041478309 (1.90 GB)
telemt_user_octets_to_client{user="hello"} 64900059711 (60.44 GB)
telemt_user_msgs_from_client{user="hello"} 592051
telemt_user_msgs_to_client{user="hello"} 4107119
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 109692.3 (30h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 258620
telemt_connections_bad_total 2090
telemt_handshake_timeouts_total 10656
telemt_upstream_connect_attempt_total 29465
telemt_upstream_connect_success_total 29461
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 29465
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13670
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15764
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2280
telemt_me_reconnect_attempts_total 25159
telemt_me_reconnect_success_total 23944
telemt_me_reader_eof_total 25651
telemt_me_idle_close_by_peer_total 25651
telemt_me_route_drop_no_conn_total 94017
telemt_me_route_drop_channel_closed_total 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 236564
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
telemt_pool_swap_total 99
telemt_me_writer_removed_unexpected_total 24204
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 23924
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 260
telemt_user_connections_total{user="hello"} 236481
telemt_user_connections_current{user="hello"} 203
telemt_user_octets_from_client{user="hello"} 9478550528 (8.83 GB)
telemt_user_octets_to_client{user="hello"} 101327204428 (94.37 GB)
telemt_user_unique_ips_current{user="hello"} 74
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 109667.3 (30h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 356848
telemt_connections_bad_total 15040
telemt_handshake_timeouts_total 3432
telemt_upstream_connect_attempt_total 41418
telemt_upstream_connect_success_total 31300
telemt_upstream_connect_fail_total 10118
telemt_upstream_connect_attempts_per_request{bucket="1"} 41418
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15814
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15268
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 209
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10118
telemt_me_keepalive_timeout_total 4128
telemt_me_reconnect_attempts_total 96605
telemt_me_reconnect_success_total 22777
telemt_me_reader_eof_total 25775
telemt_me_idle_close_by_peer_total 25768
telemt_me_route_drop_no_conn_total 127828
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 307843
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1179
telemt_desync_full_logged_total 349
telemt_desync_suppressed_total 830
telemt_desync_frames_bucket_total{bucket="1_2"} 292
telemt_desync_frames_bucket_total{bucket="3_10"} 442
telemt_desync_frames_bucket_total{bucket="gt_10"} 445
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 25373
telemt_me_refill_failed_total 2302
telemt_me_writer_restored_same_endpoint_total 22767
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 2596
telemt_user_connections_total{user="hello"} 310753
telemt_user_connections_current{user="hello"} 263
telemt_user_octets_from_client{user="hello"} 6764364942 (6.30 GB)
telemt_user_octets_to_client{user="hello"} 116325077305 (108.34 GB)
telemt_user_msgs_from_client{user="hello"} 68310
telemt_user_msgs_to_client{user="hello"} 114408
telemt_user_unique_ips_current{user="hello"} 78
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 59839.0 (16h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 90089
telemt_connections_bad_total 12071
telemt_handshake_timeouts_total 1207
telemt_upstream_connect_attempt_total 24935
telemt_upstream_connect_success_total 24731
telemt_upstream_connect_fail_total 204
telemt_upstream_connect_attempts_per_request{bucket="1"} 24935
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12996
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11666
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 69
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 204
telemt_me_keepalive_timeout_total 1004
telemt_me_reconnect_attempts_total 26740
telemt_me_reconnect_success_total 16820
telemt_me_reader_eof_total 18041
telemt_me_idle_close_by_peer_total 18041
telemt_me_route_drop_no_conn_total 26833
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 69051
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 194
telemt_desync_full_logged_total 37
telemt_desync_suppressed_total 157
telemt_desync_frames_bucket_total{bucket="1_2"} 31
telemt_desync_frames_bucket_total{bucket="3_10"} 84
telemt_desync_frames_bucket_total{bucket="gt_10"} 79
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 17277
telemt_me_refill_failed_total 308
telemt_me_writer_restored_same_endpoint_total 16802
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 457
telemt_user_connections_total{user="hello"} 73951
telemt_user_connections_current{user="hello"} 114
telemt_user_octets_from_client{user="hello"} 895025685 (853.56 MB)
telemt_user_octets_to_client{user="hello"} 21606243343 (20.12 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 109623.9 (30h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 641405
telemt_connections_bad_total 17990
telemt_handshake_timeouts_total 18988
telemt_upstream_connect_attempt_total 23090
telemt_upstream_connect_success_total 22972
telemt_upstream_connect_fail_total 118
telemt_upstream_connect_attempts_per_request{bucket="1"} 23090
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10763
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12184
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 118
telemt_me_keepalive_timeout_total 2511
telemt_me_reconnect_attempts_total 22154
telemt_me_reconnect_success_total 17529
telemt_me_reader_eof_total 18819
telemt_me_idle_close_by_peer_total 18816
telemt_me_route_drop_no_conn_total 310829
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 609936
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
telemt_pool_swap_total 101
telemt_me_writer_removed_unexpected_total 17901
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 17522
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 372
telemt_user_connections_total{user="hello"} 582883
telemt_user_connections_current{user="hello"} 438
telemt_user_octets_from_client{user="hello"} 10181316500 (9.48 GB)
telemt_user_octets_to_client{user="hello"} 308261706456 (287.09 GB)
telemt_user_unique_ips_current{user="hello"} 178
telemt_user_unique_ips_recent_window{user="hello"} 71
```