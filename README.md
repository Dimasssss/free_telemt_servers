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

# Server Metrics 2026-03-15 03:25:55 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 18687.5 (5h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 42952
telemt_connections_bad_total 375
telemt_handshake_timeouts_total 305
telemt_upstream_connect_attempt_total 4747
telemt_upstream_connect_success_total 4717
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 4747
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2132
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2581
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 3791
telemt_me_reconnect_success_total 3776
telemt_me_reader_eof_total 4022
telemt_me_idle_close_by_peer_total 4022
telemt_me_route_drop_no_conn_total 12713
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 40907
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 247
telemt_desync_full_logged_total 107
telemt_desync_suppressed_total 140
telemt_desync_frames_bucket_total{bucket="1_2"} 46
telemt_desync_frames_bucket_total{bucket="3_10"} 100
telemt_desync_frames_bucket_total{bucket="gt_10"} 101
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 3795
telemt_me_writer_restored_same_endpoint_total 3745
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 40904
telemt_user_connections_current{user="hello"} 244
telemt_user_octets_from_client{user="hello"} 441874172 (421.40 MB)
telemt_user_octets_to_client{user="hello"} 13663768332 (12.73 GB)
telemt_user_unique_ips_current{user="hello"} 83
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 18694.2 (5h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16122
telemt_connections_bad_total 49
telemt_handshake_timeouts_total 42
telemt_upstream_connect_attempt_total 5239
telemt_upstream_connect_success_total 5239
telemt_upstream_connect_attempts_per_request{bucket="1"} 5239
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2301
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2934
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 4308
telemt_me_reconnect_success_total 4289
telemt_me_reader_eof_total 4591
telemt_me_idle_close_by_peer_total 4591
telemt_me_route_drop_no_conn_total 8195
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 15261
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 4322
telemt_me_writer_restored_same_endpoint_total 4273
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 15265
telemt_user_connections_current{user="hello"} 124
telemt_user_octets_from_client{user="hello"} 587021516 (559.83 MB)
telemt_user_octets_to_client{user="hello"} 3980312444 (3.71 GB)
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 18686.7 (5h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17486
telemt_connections_bad_total 418
telemt_handshake_timeouts_total 295
telemt_upstream_connect_attempt_total 5025
telemt_upstream_connect_success_total 5024
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 5025
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2207
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2811
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 4098
telemt_me_reconnect_success_total 4078
telemt_me_reader_eof_total 4395
telemt_me_idle_close_by_peer_total 4395
telemt_me_route_drop_no_conn_total 6032
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16217
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 4110
telemt_me_writer_restored_same_endpoint_total 4074
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 16172
telemt_user_connections_current{user="hello"} 48
telemt_user_octets_from_client{user="hello"} 8682313480 (8.09 GB)
telemt_user_octets_to_client{user="hello"} 14403523944 (13.41 GB)
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 18686.4 (5h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19875
telemt_connections_bad_total 101
telemt_handshake_timeouts_total 93
telemt_upstream_connect_attempt_total 4475
telemt_upstream_connect_success_total 4474
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 4475
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2063
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2399
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 3551
telemt_me_reconnect_success_total 3537
telemt_me_reader_eof_total 3772
telemt_me_idle_close_by_peer_total 3772
telemt_me_route_drop_no_conn_total 9433
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 18907
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
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 3571
telemt_me_writer_restored_same_endpoint_total 3526
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 34
telemt_user_connections_total{user="hello"} 18830
telemt_user_connections_current{user="hello"} 110
telemt_user_octets_from_client{user="hello"} 446066084 (425.40 MB)
telemt_user_octets_to_client{user="hello"} 12352881644 (11.50 GB)
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 18686.6 (5h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21298
telemt_connections_bad_total 3653
telemt_handshake_timeouts_total 397
telemt_upstream_connect_attempt_total 5779
telemt_upstream_connect_success_total 5711
telemt_upstream_connect_fail_total 68
telemt_upstream_connect_attempts_per_request{bucket="1"} 5779
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2604
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3095
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 68
telemt_me_reconnect_attempts_total 4846
telemt_me_reconnect_success_total 4763
telemt_me_reader_eof_total 5055
telemt_me_idle_close_by_peer_total 5055
telemt_me_route_drop_no_conn_total 6290
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16834
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 4785
telemt_me_refill_failed_total 2
telemt_me_writer_restored_same_endpoint_total 4751
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 29
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 16825
telemt_user_connections_current{user="hello"} 60
telemt_user_octets_from_client{user="hello"} 233634718 (222.81 MB)
telemt_user_octets_to_client{user="hello"} 8741461339 (8.14 GB)
telemt_user_msgs_from_client{user="hello"} 11
telemt_user_msgs_to_client{user="hello"} 7
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 18685.6 (5h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 56869
telemt_connections_bad_total 1428
telemt_handshake_timeouts_total 222
telemt_upstream_connect_attempt_total 4207
telemt_upstream_connect_success_total 4184
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 4207
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2100
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2083
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_reconnect_attempts_total 3255
telemt_me_reconnect_success_total 3243
telemt_me_reader_eof_total 3424
telemt_me_idle_close_by_peer_total 3424
telemt_me_route_drop_no_conn_total 30806
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 55082
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
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 3246
telemt_me_writer_restored_same_endpoint_total 3216
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 53643
telemt_user_connections_current{user="hello"} 258
telemt_user_octets_from_client{user="hello"} 1723741944 (1.61 GB)
telemt_user_octets_to_client{user="hello"} 35638259780 (33.19 GB)
telemt_user_unique_ips_current{user="hello"} 123
telemt_user_unique_ips_recent_window{user="hello"} 42
```