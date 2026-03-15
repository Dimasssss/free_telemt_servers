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

# Server Metrics 2026-03-15 03:00:28 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 17160.8 (4h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 38475
telemt_connections_bad_total 375
telemt_handshake_timeouts_total 294
telemt_upstream_connect_attempt_total 4370
telemt_upstream_connect_success_total 4342
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 4370
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1956
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2382
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 3478
telemt_me_reconnect_success_total 3464
telemt_me_reader_eof_total 3681
telemt_me_idle_close_by_peer_total 3681
telemt_me_route_drop_no_conn_total 11413
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 36577
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 194
telemt_desync_full_logged_total 87
telemt_desync_suppressed_total 107
telemt_desync_frames_bucket_total{bucket="1_2"} 37
telemt_desync_frames_bucket_total{bucket="3_10"} 77
telemt_desync_frames_bucket_total{bucket="gt_10"} 80
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 3479
telemt_me_writer_restored_same_endpoint_total 3433
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 15
telemt_user_connections_total{user="hello"} 36575
telemt_user_connections_current{user="hello"} 233
telemt_user_octets_from_client{user="hello"} 391673824 (373.53 MB)
telemt_user_octets_to_client{user="hello"} 13026604776 (12.13 GB)
telemt_user_unique_ips_current{user="hello"} 78
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 17167.3 (4h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15216
telemt_connections_bad_total 37
telemt_handshake_timeouts_total 40
telemt_upstream_connect_attempt_total 4818
telemt_upstream_connect_success_total 4818
telemt_upstream_connect_attempts_per_request{bucket="1"} 4818
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2131
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2683
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 3945
telemt_me_reconnect_success_total 3927
telemt_me_reader_eof_total 4193
telemt_me_idle_close_by_peer_total 4193
telemt_me_route_drop_no_conn_total 7421
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 14401
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 3954
telemt_me_writer_restored_same_endpoint_total 3911
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 14405
telemt_user_connections_current{user="hello"} 118
telemt_user_octets_from_client{user="hello"} 581153160 (554.23 MB)
telemt_user_octets_to_client{user="hello"} 3736702240 (3.48 GB)
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 17160.0 (4h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16050
telemt_connections_bad_total 355
telemt_handshake_timeouts_total 270
telemt_upstream_connect_attempt_total 4612
telemt_upstream_connect_success_total 4611
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 4612
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2039
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2566
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 3744
telemt_me_reconnect_success_total 3724
telemt_me_reader_eof_total 4008
telemt_me_idle_close_by_peer_total 4008
telemt_me_route_drop_no_conn_total 5590
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 14921
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 3752
telemt_me_writer_restored_same_endpoint_total 3720
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 28
telemt_user_connections_total{user="hello"} 14878
telemt_user_connections_current{user="hello"} 67
telemt_user_octets_from_client{user="hello"} 8644749244 (8.05 GB)
telemt_user_octets_to_client{user="hello"} 13872610804 (12.92 GB)
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 17159.7 (4h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18146
telemt_connections_bad_total 92
telemt_handshake_timeouts_total 76
telemt_upstream_connect_attempt_total 4132
telemt_upstream_connect_success_total 4131
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 4132
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1914
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2206
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 3272
telemt_me_reconnect_success_total 3259
telemt_me_reader_eof_total 3468
telemt_me_idle_close_by_peer_total 3468
telemt_me_route_drop_no_conn_total 6968
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 17215
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 55
telemt_desync_full_logged_total 11
telemt_desync_suppressed_total 44
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 25
telemt_desync_frames_bucket_total{bucket="gt_10"} 23
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 3288
telemt_me_writer_restored_same_endpoint_total 3248
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 17213
telemt_user_connections_current{user="hello"} 140
telemt_user_octets_from_client{user="hello"} 438774264 (418.45 MB)
telemt_user_octets_to_client{user="hello"} 12124327032 (11.29 GB)
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 17159.9 (4h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19850
telemt_connections_bad_total 3379
telemt_handshake_timeouts_total 395
telemt_upstream_connect_attempt_total 5360
telemt_upstream_connect_success_total 5293
telemt_upstream_connect_fail_total 66
telemt_upstream_connect_attempts_per_request{bucket="1"} 5359
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2415
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2867
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 66
telemt_me_reconnect_attempts_total 4498
telemt_me_reconnect_success_total 4414
telemt_me_reader_eof_total 4673
telemt_me_idle_close_by_peer_total 4673
telemt_me_route_drop_no_conn_total 5785
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 15691
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 4434
telemt_me_refill_failed_total 2
telemt_me_writer_restored_same_endpoint_total 4402
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 29
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 15682
telemt_user_connections_current{user="hello"} 64
telemt_user_octets_from_client{user="hello"} 198234702 (189.05 MB)
telemt_user_octets_to_client{user="hello"} 7513986799 (7.00 GB)
telemt_user_msgs_from_client{user="hello"} 11
telemt_user_msgs_to_client{user="hello"} 7
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 17158.8 (4h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 52427
telemt_connections_bad_total 1205
telemt_handshake_timeouts_total 189
telemt_upstream_connect_attempt_total 3841
telemt_upstream_connect_success_total 3819
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 3841
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1946
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1872
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_reconnect_attempts_total 2952
telemt_me_reconnect_success_total 2941
telemt_me_reader_eof_total 3096
telemt_me_idle_close_by_peer_total 3096
telemt_me_route_drop_no_conn_total 28338
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 51019
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16
telemt_desync_full_logged_total 5
telemt_desync_suppressed_total 11
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 4
telemt_desync_frames_bucket_total{bucket="gt_10"} 6
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 2940
telemt_me_writer_restored_same_endpoint_total 2914
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_user_connections_total{user="hello"} 49588
telemt_user_connections_current{user="hello"} 221
telemt_user_octets_from_client{user="hello"} 1675263836 (1.56 GB)
telemt_user_octets_to_client{user="hello"} 30225174900 (28.15 GB)
telemt_user_unique_ips_current{user="hello"} 108
telemt_user_unique_ips_recent_window{user="hello"} 36
```