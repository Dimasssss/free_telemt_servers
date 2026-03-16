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

# Server Metrics 2026-03-16 14:43:06 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 3912.9 (1h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 47361
telemt_connections_bad_total 258
telemt_handshake_timeouts_total 1184
telemt_upstream_connect_attempt_total 743
telemt_upstream_connect_success_total 741
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 743
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 368
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 373
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 498
telemt_me_reconnect_success_total 492
telemt_me_reader_eof_total 480
telemt_me_idle_close_by_peer_total 480
telemt_me_route_drop_no_conn_total 13547
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 44011
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 121
telemt_desync_full_logged_total 34
telemt_desync_suppressed_total 87
telemt_desync_frames_bucket_total{bucket="1_2"} 22
telemt_desync_frames_bucket_total{bucket="3_10"} 77
telemt_desync_frames_bucket_total{bucket="gt_10"} 22
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 483
telemt_me_writer_restored_same_endpoint_total 490
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 36
telemt_user_connections_total{user="hello"} 43953
telemt_user_connections_current{user="hello"} 742
telemt_user_octets_from_client{user="hello"} 1029641748 (981.94 MB)
telemt_user_octets_to_client{user="hello"} 27964408176 (26.04 GB)
telemt_user_unique_ips_current{user="hello"} 224
telemt_user_unique_ips_recent_window{user="hello"} 88
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 1478.9 (0h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15272
telemt_connections_bad_total 281
telemt_handshake_timeouts_total 87
telemt_upstream_connect_attempt_total 14395
telemt_upstream_connect_success_total 14383
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 14393
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12040
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 793
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1550
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 14381
telemt_user_connections_current{user="hello"} 597
telemt_user_octets_from_client{user="hello"} 211496073 (201.70 MB)
telemt_user_octets_to_client{user="hello"} 2746547837 (2.56 GB)
telemt_user_msgs_from_client{user="hello"} 232245
telemt_user_msgs_to_client{user="hello"} 813846
telemt_user_unique_ips_current{user="hello"} 139
telemt_user_unique_ips_recent_window{user="hello"} 88
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 4025.9 (1h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18717
telemt_connections_bad_total 6
telemt_handshake_timeouts_total 131
telemt_upstream_connect_attempt_total 2264
telemt_upstream_connect_success_total 2230
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 2264
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1331
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 879
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_reconnect_attempts_total 32010
telemt_me_reconnect_success_total 1012
telemt_me_reader_eof_total 1061
telemt_me_idle_close_by_peer_total 1061
telemt_me_route_drop_no_conn_total 4898
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16669
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_writer_removed_unexpected_total 1084
telemt_me_refill_failed_total 968
telemt_me_writer_restored_same_endpoint_total 968
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 1272
telemt_me_writer_removed_unexpected_minus_restored_total 72
telemt_user_connections_total{user="hello"} 17623
telemt_user_connections_current{user="hello"} 257
telemt_user_octets_from_client{user="hello"} 202580402 (193.20 MB)
telemt_user_octets_to_client{user="hello"} 2974198806 (2.77 GB)
telemt_user_msgs_from_client{user="hello"} 4789
telemt_user_msgs_to_client{user="hello"} 14129
telemt_user_unique_ips_current{user="hello"} 93
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 4162.1 (1h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 33528
telemt_connections_bad_total 18
telemt_handshake_timeouts_total 544
telemt_upstream_connect_attempt_total 950
telemt_upstream_connect_success_total 946
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 950
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 491
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 445
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 2995
telemt_me_reconnect_success_total 676
telemt_me_reader_eof_total 726
telemt_me_idle_close_by_peer_total 726
telemt_me_route_drop_no_conn_total 10349
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 31616
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 202
telemt_desync_full_logged_total 51
telemt_desync_suppressed_total 151
telemt_desync_frames_bucket_total{bucket="1_2"} 36
telemt_desync_frames_bucket_total{bucket="3_10"} 79
telemt_desync_frames_bucket_total{bucket="gt_10"} 87
telemt_me_writer_removed_unexpected_total 746
telemt_me_refill_failed_total 72
telemt_me_writer_restored_same_endpoint_total 672
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 70
telemt_user_connections_total{user="hello"} 31596
telemt_user_connections_current{user="hello"} 457
telemt_user_octets_from_client{user="hello"} 690452064 (658.47 MB)
telemt_user_octets_to_client{user="hello"} 7189842332 (6.70 GB)
telemt_user_unique_ips_current{user="hello"} 142
telemt_user_unique_ips_recent_window{user="hello"} 67
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 1623.5 (0h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8409
telemt_connections_bad_total 2702
telemt_handshake_timeouts_total 39
telemt_upstream_connect_attempt_total 350
telemt_upstream_connect_success_total 346
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 350
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 124
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 213
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 238
telemt_me_reconnect_success_total 235
telemt_me_reader_eof_total 209
telemt_me_idle_close_by_peer_total 209
telemt_me_route_drop_no_conn_total 1746
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5379
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16
telemt_desync_full_logged_total 5
telemt_desync_suppressed_total 11
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 6
telemt_desync_frames_bucket_total{bucket="gt_10"} 6
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 222
telemt_me_writer_restored_same_endpoint_total 235
telemt_me_async_recovery_trigger_total 22
telemt_user_connections_total{user="hello"} 5365
telemt_user_connections_current{user="hello"} 168
telemt_user_octets_from_client{user="hello"} 211141632 (201.36 MB)
telemt_user_octets_to_client{user="hello"} 932065124 (888.89 MB)
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 3729.6 (1h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 48038
telemt_connections_bad_total 1058
telemt_handshake_timeouts_total 909
telemt_upstream_connect_attempt_total 825
telemt_upstream_connect_success_total 825
telemt_upstream_connect_attempts_per_request{bucket="1"} 825
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 436
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 388
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 1668
telemt_me_reconnect_success_total 577
telemt_me_reader_eof_total 586
telemt_me_idle_close_by_peer_total 586
telemt_me_route_drop_no_conn_total 19684
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 44786
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 5
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9
telemt_desync_full_logged_total 4
telemt_desync_suppressed_total 5
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 7
telemt_me_writer_removed_unexpected_total 608
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 573
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 208
telemt_me_writer_removed_unexpected_minus_restored_total 31
telemt_user_connections_total{user="hello"} 44658
telemt_user_connections_current{user="hello"} 792
telemt_user_octets_from_client{user="hello"} 1077349164 (1.00 GB)
telemt_user_octets_to_client{user="hello"} 12262882984 (11.42 GB)
telemt_user_unique_ips_current{user="hello"} 286
telemt_user_unique_ips_recent_window{user="hello"} 107
```