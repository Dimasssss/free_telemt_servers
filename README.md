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

## 4vps.su
- Локация: Польша, Варшава
- Тариф: PL-cx21
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 2 Gbit/s
- Цена в месяц: 770 RUB
- Оплачен до: 16 апреля
- Ссылка:
```bash
tg://proxy?server=s7.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-17 03:26:14 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 31252.2 (8h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 162670
telemt_connections_bad_total 2382
telemt_handshake_timeouts_total 5578
telemt_upstream_connect_attempt_total 6705
telemt_upstream_connect_success_total 6666
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 6705
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2996
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3665
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 5126
telemt_me_reconnect_success_total 5110
telemt_me_reader_eof_total 5435
telemt_me_idle_close_by_peer_total 5435
telemt_me_route_drop_no_conn_total 51952
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 147701
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 872
telemt_desync_full_logged_total 307
telemt_desync_suppressed_total 565
telemt_desync_frames_bucket_total{bucket="1_2"} 198
telemt_desync_frames_bucket_total{bucket="3_10"} 446
telemt_desync_frames_bucket_total{bucket="gt_10"} 228
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 5154
telemt_me_writer_restored_same_endpoint_total 5089
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 44
telemt_user_connections_total{user="hello"} 147510
telemt_user_connections_current{user="hello"} 392
telemt_user_octets_from_client{user="hello"} 1980528672 (1.84 GB)
telemt_user_octets_to_client{user="hello"} 67933418568 (63.27 GB)
telemt_user_unique_ips_current{user="hello"} 146
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 31503.7 (8h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 90976
telemt_connections_bad_total 1433
telemt_handshake_timeouts_total 3258
telemt_upstream_connect_attempt_total 8739
telemt_upstream_connect_success_total 8624
telemt_upstream_connect_fail_total 115
telemt_upstream_connect_attempts_per_request{bucket="1"} 8739
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3565
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4984
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 115
telemt_me_reconnect_attempts_total 8242
telemt_me_reconnect_success_total 7075
telemt_me_reader_eof_total 7465
telemt_me_idle_close_by_peer_total 7465
telemt_me_route_drop_no_conn_total 38152
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 82605
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 205
telemt_desync_full_logged_total 67
telemt_desync_suppressed_total 138
telemt_desync_frames_bucket_total{bucket="1_2"} 49
telemt_desync_frames_bucket_total{bucket="3_10"} 99
telemt_desync_frames_bucket_total{bucket="gt_10"} 57
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 7181
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 7059
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 106
telemt_user_connections_total{user="hello"} 82549
telemt_user_connections_current{user="hello"} 201
telemt_user_octets_from_client{user="hello"} 1167641548 (1.09 GB)
telemt_user_octets_to_client{user="hello"} 37751851836 (35.16 GB)
telemt_user_unique_ips_current{user="hello"} 76
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 31280.1 (8h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 59276
telemt_connections_bad_total 788
telemt_handshake_timeouts_total 2031
telemt_upstream_connect_attempt_total 8394
telemt_upstream_connect_success_total 8347
telemt_upstream_connect_fail_total 47
telemt_upstream_connect_attempts_per_request{bucket="1"} 8394
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3680
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4607
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 47
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 6814
telemt_me_reconnect_success_total 6775
telemt_me_reader_eof_total 7247
telemt_me_idle_close_by_peer_total 7247
telemt_me_route_drop_no_conn_total 18741
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 50139
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 38
telemt_desync_full_logged_total 14
telemt_desync_suppressed_total 24
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 14
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 6863
telemt_me_writer_restored_same_endpoint_total 6764
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 88
telemt_user_connections_total{user="hello"} 50123
telemt_user_connections_current{user="hello"} 162
telemt_user_octets_from_client{user="hello"} 5580073300 (5.20 GB)
telemt_user_octets_to_client{user="hello"} 18027047124 (16.79 GB)
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 31339.3 (8h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 92909
telemt_connections_bad_total 3397
telemt_handshake_timeouts_total 1600
telemt_upstream_connect_attempt_total 7228
telemt_upstream_connect_success_total 7165
telemt_upstream_connect_fail_total 63
telemt_upstream_connect_attempts_per_request{bucket="1"} 7228
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3364
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3758
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 63
telemt_me_reconnect_attempts_total 5635
telemt_me_reconnect_success_total 5596
telemt_me_reader_eof_total 5948
telemt_me_idle_close_by_peer_total 5948
telemt_me_route_drop_no_conn_total 31918
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 85261
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 156
telemt_desync_full_logged_total 48
telemt_desync_suppressed_total 108
telemt_desync_frames_bucket_total{bucket="1_2"} 32
telemt_desync_frames_bucket_total{bucket="3_10"} 58
telemt_desync_frames_bucket_total{bucket="gt_10"} 66
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 5675
telemt_me_writer_restored_same_endpoint_total 5589
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 79
telemt_user_connections_total{user="hello"} 85245
telemt_user_connections_current{user="hello"} 178
telemt_user_octets_from_client{user="hello"} 973584816 (928.48 MB)
telemt_user_octets_to_client{user="hello"} 40938227200 (38.13 GB)
telemt_user_unique_ips_current{user="hello"} 69
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 31311.3 (8h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 70261
telemt_connections_bad_total 16292
telemt_handshake_timeouts_total 1230
telemt_upstream_connect_attempt_total 9268
telemt_upstream_connect_success_total 9148
telemt_upstream_connect_fail_total 120
telemt_upstream_connect_attempts_per_request{bucket="1"} 9268
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4114
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4896
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 138
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 120
telemt_me_reconnect_attempts_total 9834
telemt_me_reconnect_success_total 7584
telemt_me_reader_eof_total 7990
telemt_me_idle_close_by_peer_total 7990
telemt_me_route_drop_no_conn_total 20186
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 50763
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 31
telemt_desync_full_logged_total 12
telemt_desync_suppressed_total 19
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 13
telemt_desync_frames_bucket_total{bucket="gt_10"} 12
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 7768
telemt_me_refill_failed_total 69
telemt_me_writer_restored_same_endpoint_total 7576
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 184
telemt_user_connections_total{user="hello"} 50758
telemt_user_connections_current{user="hello"} 92
telemt_user_octets_from_client{user="hello"} 597648832 (569.96 MB)
telemt_user_octets_to_client{user="hello"} 21894287144 (20.39 GB)
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 31472.2 (8h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 179730
telemt_connections_bad_total 16582
telemt_handshake_timeouts_total 1128
telemt_upstream_connect_attempt_total 6519
telemt_upstream_connect_success_total 6483
telemt_upstream_connect_fail_total 36
telemt_upstream_connect_attempts_per_request{bucket="1"} 6519
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3075
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3403
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 36
telemt_me_reconnect_attempts_total 4949
telemt_me_reconnect_success_total 4933
telemt_me_reader_eof_total 5286
telemt_me_idle_close_by_peer_total 5286
telemt_me_route_drop_no_conn_total 182123
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 234068
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 143
telemt_desync_full_logged_total 85
telemt_desync_suppressed_total 58
telemt_desync_frames_bucket_total{bucket="1_2"} 45
telemt_desync_frames_bucket_total{bucket="3_10"} 46
telemt_desync_frames_bucket_total{bucket="gt_10"} 52
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 5003
telemt_me_writer_restored_same_endpoint_total 4923
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 70
telemt_user_connections_total{user="hello"} 156323
telemt_user_connections_current{user="hello"} 358
telemt_user_octets_from_client{user="hello"} 2450291612 (2.28 GB)
telemt_user_octets_to_client{user="hello"} 124850419280 (116.28 GB)
telemt_user_unique_ips_current{user="hello"} 161
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 19478.6 (5h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 157
telemt_connections_bad_total 119
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 9814
telemt_upstream_connect_success_total 9814
telemt_upstream_connect_attempts_per_request{bucket="1"} 9814
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5690
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4121
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 8836
telemt_me_reconnect_success_total 8788
telemt_me_reader_eof_total 9642
telemt_me_idle_close_by_peer_total 9642
telemt_me_route_drop_no_conn_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 36
telemt_me_writer_pick_total{mode="p2c",result="full"} 3
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 8874
telemt_me_writer_restored_same_endpoint_total 8788
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 86
telemt_user_connections_total{user="hello"} 36
telemt_user_octets_from_client{user="hello"} 157473040 (150.18 MB)
telemt_user_octets_to_client{user="hello"} 23027108 (21.96 MB)
```