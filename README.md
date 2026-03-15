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

# Server Metrics 2026-03-15 06:23:29 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 29341.2 (8h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 81704
telemt_connections_bad_total 448
telemt_handshake_timeouts_total 1594
telemt_upstream_connect_attempt_total 7206
telemt_upstream_connect_success_total 7163
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 7206
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3259
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3900
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 5717
telemt_me_reconnect_success_total 5697
telemt_me_reader_eof_total 6100
telemt_me_idle_close_by_peer_total 6100
telemt_me_route_drop_no_conn_total 74515
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 85195
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 650
telemt_desync_full_logged_total 290
telemt_desync_suppressed_total 360
telemt_desync_frames_bucket_total{bucket="1_2"} 114
telemt_desync_frames_bucket_total{bucket="3_10"} 274
telemt_desync_frames_bucket_total{bucket="gt_10"} 262
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 5742
telemt_me_writer_restored_same_endpoint_total 5666
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 45
telemt_user_connections_total{user="hello"} 76538
telemt_user_connections_current{user="hello"} 305
telemt_user_octets_from_client{user="hello"} 958812004 (914.39 MB)
telemt_user_octets_to_client{user="hello"} 39873167096 (37.13 GB)
telemt_user_unique_ips_current{user="hello"} 100
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 29348.5 (8h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 27634
telemt_connections_bad_total 67
telemt_handshake_timeouts_total 111
telemt_upstream_connect_attempt_total 7940
telemt_upstream_connect_success_total 7940
telemt_upstream_connect_attempts_per_request{bucket="1"} 7940
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3482
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4451
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 6489
telemt_me_reconnect_success_total 6463
telemt_me_reader_eof_total 6948
telemt_me_idle_close_by_peer_total 6948
telemt_me_route_drop_no_conn_total 14179
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 26336
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 6522
telemt_me_writer_restored_same_endpoint_total 6447
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 26339
telemt_user_connections_current{user="hello"} 168
telemt_user_octets_from_client{user="hello"} 733999108 (700.00 MB)
telemt_user_octets_to_client{user="hello"} 10088359900 (9.40 GB)
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 29340.9 (8h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 35305
telemt_connections_bad_total 455
telemt_handshake_timeouts_total 1771
telemt_upstream_connect_attempt_total 7843
telemt_upstream_connect_success_total 7842
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 7843
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3440
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4396
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 6395
telemt_me_reconnect_success_total 6368
telemt_me_reader_eof_total 6885
telemt_me_idle_close_by_peer_total 6885
telemt_me_route_drop_no_conn_total 12311
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 31911
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 6422
telemt_me_writer_restored_same_endpoint_total 6364
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 54
telemt_user_connections_total{user="hello"} 31860
telemt_user_connections_current{user="hello"} 96
telemt_user_octets_from_client{user="hello"} 8770689376 (8.17 GB)
telemt_user_octets_to_client{user="hello"} 17742116668 (16.52 GB)
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 29340.7 (8h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 37428
telemt_connections_bad_total 129
telemt_handshake_timeouts_total 245
telemt_upstream_connect_attempt_total 6927
telemt_upstream_connect_success_total 6926
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 6927
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3222
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3683
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 5485
telemt_me_reconnect_success_total 5465
telemt_me_reader_eof_total 5854
telemt_me_idle_close_by_peer_total 5854
telemt_me_route_drop_no_conn_total 17021
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 34738
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 73
telemt_desync_full_logged_total 19
telemt_desync_suppressed_total 54
telemt_desync_frames_bucket_total{bucket="1_2"} 19
telemt_desync_frames_bucket_total{bucket="3_10"} 30
telemt_desync_frames_bucket_total{bucket="gt_10"} 24
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 5521
telemt_me_writer_restored_same_endpoint_total 5454
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 56
telemt_user_connections_total{user="hello"} 34657
telemt_user_connections_current{user="hello"} 160
telemt_user_octets_from_client{user="hello"} 625769036 (596.78 MB)
telemt_user_octets_to_client{user="hello"} 23085020972 (21.50 GB)
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 4412.3 (1h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6298
telemt_connections_bad_total 854
telemt_handshake_timeouts_total 140
telemt_upstream_connect_attempt_total 1852
telemt_upstream_connect_success_total 1824
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 1852
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 794
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1022
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_reconnect_attempts_total 95825
telemt_me_reconnect_success_total 1434
telemt_me_reader_eof_total 1410
telemt_me_idle_close_by_peer_total 1410
telemt_me_route_drop_no_conn_total 1618
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5056
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 1359
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 1330
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_user_connections_total{user="hello"} 5201
telemt_user_connections_current{user="hello"} 52
telemt_user_octets_from_client{user="hello"} 31570225 (30.11 MB)
telemt_user_octets_to_client{user="hello"} 1788985367 (1.67 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 20
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 29340.0 (8h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 98194
telemt_connections_bad_total 1792
telemt_handshake_timeouts_total 430
telemt_upstream_connect_attempt_total 6476
telemt_upstream_connect_success_total 6439
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 6476
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3226
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3212
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_reconnect_attempts_total 4990
telemt_me_reconnect_success_total 4967
telemt_me_reader_eof_total 5287
telemt_me_idle_close_by_peer_total 5287
telemt_me_route_drop_no_conn_total 52795
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 93229
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 22
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 12
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 9
telemt_desync_frames_bucket_total{bucket="gt_10"} 7
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 4987
telemt_me_writer_restored_same_endpoint_total 4940
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 91787
telemt_user_connections_current{user="hello"} 292
telemt_user_octets_from_client{user="hello"} 2301363544 (2.14 GB)
telemt_user_octets_to_client{user="hello"} 48986812516 (45.62 GB)
telemt_user_unique_ips_current{user="hello"} 141
telemt_user_unique_ips_recent_window{user="hello"} 44
```