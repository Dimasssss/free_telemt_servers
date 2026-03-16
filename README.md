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

# Server Metrics 2026-03-16 23:32:10 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 17209.2 (4h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 105761
telemt_connections_bad_total 1609
telemt_handshake_timeouts_total 4502
telemt_upstream_connect_attempt_total 3524
telemt_upstream_connect_success_total 3501
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 3524
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1565
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1931
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 2611
telemt_me_reconnect_success_total 2601
telemt_me_reader_eof_total 2734
telemt_me_idle_close_by_peer_total 2734
telemt_me_route_drop_no_conn_total 33303
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 95323
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 539
telemt_desync_full_logged_total 154
telemt_desync_suppressed_total 385
telemt_desync_frames_bucket_total{bucket="1_2"} 123
telemt_desync_frames_bucket_total{bucket="3_10"} 246
telemt_desync_frames_bucket_total{bucket="gt_10"} 170
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 2616
telemt_me_writer_restored_same_endpoint_total 2580
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 15
telemt_user_connections_total{user="hello"} 95275
telemt_user_connections_current{user="hello"} 374
telemt_user_octets_from_client{user="hello"} 1524992216 (1.42 GB)
telemt_user_octets_to_client{user="hello"} 50480701148 (47.01 GB)
telemt_user_unique_ips_current{user="hello"} 132
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 17460.5 (4h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 67908
telemt_connections_bad_total 846
telemt_handshake_timeouts_total 2771
telemt_upstream_connect_attempt_total 3994
telemt_upstream_connect_success_total 3942
telemt_upstream_connect_fail_total 52
telemt_upstream_connect_attempts_per_request{bucket="1"} 3994
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1726
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2141
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 52
telemt_me_reconnect_attempts_total 3057
telemt_me_reconnect_success_total 3050
telemt_me_reader_eof_total 3217
telemt_me_idle_close_by_peer_total 3217
telemt_me_route_drop_no_conn_total 27097
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 61422
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 114
telemt_desync_full_logged_total 32
telemt_desync_suppressed_total 82
telemt_desync_frames_bucket_total{bucket="1_2"} 28
telemt_desync_frames_bucket_total{bucket="3_10"} 48
telemt_desync_frames_bucket_total{bucket="gt_10"} 38
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 3090
telemt_me_writer_restored_same_endpoint_total 3034
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 40
telemt_user_connections_total{user="hello"} 61371
telemt_user_connections_current{user="hello"} 188
telemt_user_octets_from_client{user="hello"} 875174940 (834.63 MB)
telemt_user_octets_to_client{user="hello"} 28340751364 (26.39 GB)
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 17236.8 (4h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 37166
telemt_connections_bad_total 424
telemt_handshake_timeouts_total 947
telemt_upstream_connect_attempt_total 4403
telemt_upstream_connect_success_total 4374
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 4403
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1860
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2489
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 3493
telemt_me_reconnect_success_total 3468
telemt_me_reader_eof_total 3694
telemt_me_idle_close_by_peer_total 3694
telemt_me_route_drop_no_conn_total 12764
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 34862
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16
telemt_desync_full_logged_total 7
telemt_desync_suppressed_total 9
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 6
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 3508
telemt_me_writer_restored_same_endpoint_total 3457
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 40
telemt_user_connections_total{user="hello"} 34858
telemt_user_connections_current{user="hello"} 102
telemt_user_octets_from_client{user="hello"} 635343368 (605.91 MB)
telemt_user_octets_to_client{user="hello"} 13824439212 (12.88 GB)
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 17296.0 (4h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 67873
telemt_connections_bad_total 3002
telemt_handshake_timeouts_total 446
telemt_upstream_connect_attempt_total 3819
telemt_upstream_connect_success_total 3776
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 3819
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1780
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1974
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_reconnect_attempts_total 2897
telemt_me_reconnect_success_total 2871
telemt_me_reader_eof_total 3030
telemt_me_idle_close_by_peer_total 3030
telemt_me_route_drop_no_conn_total 22203
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 62543
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 143
telemt_desync_full_logged_total 40
telemt_desync_suppressed_total 103
telemt_desync_frames_bucket_total{bucket="1_2"} 29
telemt_desync_frames_bucket_total{bucket="3_10"} 55
telemt_desync_frames_bucket_total{bucket="gt_10"} 59
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 2904
telemt_me_writer_restored_same_endpoint_total 2864
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 62528
telemt_user_connections_current{user="hello"} 183
telemt_user_octets_from_client{user="hello"} 799110160 (762.09 MB)
telemt_user_octets_to_client{user="hello"} 27957771060 (26.04 GB)
telemt_user_unique_ips_current{user="hello"} 70
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 17268.0 (4h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 48895
telemt_connections_bad_total 13653
telemt_handshake_timeouts_total 204
telemt_upstream_connect_attempt_total 4709
telemt_upstream_connect_success_total 4639
telemt_upstream_connect_fail_total 70
telemt_upstream_connect_attempts_per_request{bucket="1"} 4709
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2099
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2445
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 95
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 70
telemt_me_reconnect_attempts_total 4856
telemt_me_reconnect_success_total 3743
telemt_me_reader_eof_total 3911
telemt_me_idle_close_by_peer_total 3911
telemt_me_route_drop_no_conn_total 13101
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 33540
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
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
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 3849
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 3735
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 106
telemt_user_connections_total{user="hello"} 33536
telemt_user_connections_current{user="hello"} 91
telemt_user_octets_from_client{user="hello"} 265702408 (253.39 MB)
telemt_user_octets_to_client{user="hello"} 12853136756 (11.97 GB)
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 17429.1 (4h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 111901
telemt_connections_bad_total 1173
telemt_handshake_timeouts_total 898
telemt_upstream_connect_attempt_total 3474
telemt_upstream_connect_success_total 3452
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 3474
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1648
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1800
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_reconnect_attempts_total 2568
telemt_me_reconnect_success_total 2563
telemt_me_reader_eof_total 2731
telemt_me_idle_close_by_peer_total 2731
telemt_me_route_drop_no_conn_total 116179
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 156301
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 97
telemt_desync_full_logged_total 46
telemt_desync_suppressed_total 51
telemt_desync_frames_bucket_total{bucket="1_2"} 20
telemt_desync_frames_bucket_total{bucket="3_10"} 36
telemt_desync_frames_bucket_total{bucket="gt_10"} 41
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 2603
telemt_me_writer_restored_same_endpoint_total 2553
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 40
telemt_user_connections_total{user="hello"} 105922
telemt_user_connections_current{user="hello"} 357
telemt_user_octets_from_client{user="hello"} 1950279784 (1.82 GB)
telemt_user_octets_to_client{user="hello"} 75372477580 (70.20 GB)
telemt_user_unique_ips_current{user="hello"} 161
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 5435.5 (1h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 92
telemt_connections_bad_total 55
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 2396
telemt_upstream_connect_success_total 2396
telemt_upstream_connect_attempts_per_request{bucket="1"} 2396
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1396
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 997
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 2102
telemt_me_reconnect_success_total 2090
telemt_me_reader_eof_total 2263
telemt_me_idle_close_by_peer_total 2263
telemt_me_route_drop_no_conn_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 36
telemt_me_writer_pick_total{mode="p2c",result="full"} 3
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 2108
telemt_me_writer_restored_same_endpoint_total 2090
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 18
telemt_user_connections_total{user="hello"} 36
telemt_user_octets_from_client{user="hello"} 157473040 (150.18 MB)
telemt_user_octets_to_client{user="hello"} 23027108 (21.96 MB)
```