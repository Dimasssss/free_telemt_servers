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

# Server Metrics 2026-03-12 10:40:28 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 11225.8 (3h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 57987
telemt_connections_bad_total 118
telemt_handshake_timeouts_total 2432
telemt_upstream_connect_attempt_total 2770
telemt_upstream_connect_success_total 2758
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 2770
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1252
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1504
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 76
telemt_me_reconnect_attempts_total 2169
telemt_me_reconnect_success_total 2156
telemt_me_reader_eof_total 2229
telemt_me_idle_close_by_peer_total 2228
telemt_me_route_drop_no_conn_total 16016
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 52536
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 201
telemt_desync_full_logged_total 78
telemt_desync_suppressed_total 123
telemt_desync_frames_bucket_total{bucket="1_2"} 40
telemt_desync_frames_bucket_total{bucket="3_10"} 73
telemt_desync_frames_bucket_total{bucket="gt_10"} 88
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 2168
telemt_me_writer_restored_same_endpoint_total 2140
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 52509
telemt_user_connections_current{user="hello"} 330
telemt_user_octets_from_client{user="hello"} 754071364 (719.14 MB)
telemt_user_octets_to_client{user="hello"} 15546185728 (14.48 GB)
telemt_user_unique_ips_current{user="hello"} 100
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 11119.0 (3h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 23990
telemt_connections_bad_total 139
telemt_handshake_timeouts_total 185
telemt_upstream_connect_attempt_total 4129
telemt_upstream_connect_success_total 4051
telemt_upstream_connect_fail_total 78
telemt_upstream_connect_attempts_per_request{bucket="1"} 4129
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1510
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2539
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 78
telemt_me_keepalive_timeout_total 86
telemt_me_reconnect_attempts_total 8362
telemt_me_reconnect_success_total 3454
telemt_me_reader_eof_total 3650
telemt_me_idle_close_by_peer_total 3650
telemt_me_route_drop_no_conn_total 8815
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 22865
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 30
telemt_desync_full_logged_total 8
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 11
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 3620
telemt_me_refill_failed_total 153
telemt_me_writer_restored_same_endpoint_total 3439
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 166
telemt_user_connections_total{user="hello"} 22863
telemt_user_connections_current{user="hello"} 154
telemt_user_octets_from_client{user="hello"} 244467288 (233.14 MB)
telemt_user_octets_to_client{user="hello"} 4909064000 (4.57 GB)
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 11082.6 (3h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 33544
telemt_connections_bad_total 95
telemt_handshake_timeouts_total 247
telemt_upstream_connect_attempt_total 3062
telemt_upstream_connect_success_total 3062
telemt_upstream_connect_attempts_per_request{bucket="1"} 3062
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1524
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1534
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 51
telemt_me_reconnect_attempts_total 2470
telemt_me_reconnect_success_total 2454
telemt_me_reader_eof_total 2556
telemt_me_idle_close_by_peer_total 2556
telemt_me_route_drop_no_conn_total 10916
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 31320
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 4
telemt_desync_frames_bucket_total{bucket="3_10"} 6
telemt_desync_frames_bucket_total{bucket="gt_10"} 4
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 2456
telemt_me_writer_restored_same_endpoint_total 2434
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 31311
telemt_user_connections_current{user="hello"} 166
telemt_user_octets_from_client{user="hello"} 422653412 (403.07 MB)
telemt_user_octets_to_client{user="hello"} 28047308164 (26.12 GB)
telemt_user_unique_ips_current{user="hello"} 75
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 11058.5 (3h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 40665
telemt_connections_bad_total 1031
telemt_handshake_timeouts_total 205
telemt_upstream_connect_attempt_total 3166
telemt_upstream_connect_success_total 3090
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 3166
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1317
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1764
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_keepalive_timeout_total 149
telemt_me_reconnect_attempts_total 2521
telemt_me_reconnect_success_total 2484
telemt_me_reader_eof_total 2591
telemt_me_idle_close_by_peer_total 2591
telemt_me_route_drop_no_conn_total 11877
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 36672
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 156
telemt_desync_full_logged_total 53
telemt_desync_suppressed_total 103
telemt_desync_frames_bucket_total{bucket="1_2"} 61
telemt_desync_frames_bucket_total{bucket="3_10"} 53
telemt_desync_frames_bucket_total{bucket="gt_10"} 42
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 2522
telemt_me_writer_restored_same_endpoint_total 2476
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 121
telemt_me_writer_removed_unexpected_minus_restored_total 38
telemt_user_connections_total{user="hello"} 36671
telemt_user_connections_current{user="hello"} 208
telemt_user_octets_from_client{user="hello"} 887093040 (846.00 MB)
telemt_user_octets_to_client{user="hello"} 22002699256 (20.49 GB)
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 11027.8 (3h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21488
telemt_connections_bad_total 2124
telemt_handshake_timeouts_total 332
telemt_upstream_connect_attempt_total 3565
telemt_upstream_connect_success_total 3438
telemt_upstream_connect_fail_total 127
telemt_upstream_connect_attempts_per_request{bucket="1"} 3565
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1244
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2187
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 127
telemt_me_keepalive_timeout_total 73
telemt_me_reconnect_attempts_total 11652
telemt_me_reconnect_success_total 2834
telemt_me_reader_eof_total 3101
telemt_me_idle_close_by_peer_total 3101
telemt_me_seq_mismatch_total 5
telemt_me_route_drop_no_conn_total 6276
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 18414
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 304
telemt_desync_full_logged_total 85
telemt_desync_suppressed_total 219
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 257
telemt_desync_frames_bucket_total{bucket="gt_10"} 40
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 3123
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 2818
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 289
telemt_user_connections_total{user="hello"} 18411
telemt_user_connections_current{user="hello"} 91
telemt_user_octets_from_client{user="hello"} 88143028 (84.06 MB)
telemt_user_octets_to_client{user="hello"} 4875867656 (4.54 GB)
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 11014.7 (3h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 55416
telemt_connections_bad_total 569
telemt_handshake_timeouts_total 681
telemt_upstream_connect_attempt_total 2117
telemt_upstream_connect_success_total 2105
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 2117
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1029
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1074
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 61
telemt_me_reconnect_attempts_total 1524
telemt_me_reconnect_success_total 1510
telemt_me_reader_eof_total 1583
telemt_me_idle_close_by_peer_total 1583
telemt_me_route_drop_no_conn_total 24501
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 52162
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 122
telemt_desync_full_logged_total 41
telemt_desync_suppressed_total 81
telemt_desync_frames_bucket_total{bucket="1_2"} 38
telemt_desync_frames_bucket_total{bucket="3_10"} 46
telemt_desync_frames_bucket_total{bucket="gt_10"} 38
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 1530
telemt_me_writer_restored_same_endpoint_total 1503
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 52126
telemt_user_connections_current{user="hello"} 364
telemt_user_octets_from_client{user="hello"} 1858242004 (1.73 GB)
telemt_user_octets_to_client{user="hello"} 29867931128 (27.82 GB)
telemt_user_unique_ips_current{user="hello"} 103
telemt_user_unique_ips_recent_window{user="hello"} 40
```