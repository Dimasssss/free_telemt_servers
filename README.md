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

# Server Metrics 2026-03-15 04:08:21 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 21216.2 (5h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 49953
telemt_connections_bad_total 388
telemt_handshake_timeouts_total 495
telemt_upstream_connect_attempt_total 5389
telemt_upstream_connect_success_total 5356
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 5389
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2437
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2915
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 4300
telemt_me_reconnect_success_total 4283
telemt_me_reader_eof_total 4576
telemt_me_idle_close_by_peer_total 4576
telemt_me_route_drop_no_conn_total 14953
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 47494
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 321
telemt_desync_full_logged_total 143
telemt_desync_suppressed_total 178
telemt_desync_frames_bucket_total{bucket="1_2"} 56
telemt_desync_frames_bucket_total{bucket="3_10"} 135
telemt_desync_frames_bucket_total{bucket="gt_10"} 130
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 4308
telemt_me_writer_restored_same_endpoint_total 4252
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 25
telemt_user_connections_total{user="hello"} 47492
telemt_user_connections_current{user="hello"} 250
telemt_user_octets_from_client{user="hello"} 497426812 (474.38 MB)
telemt_user_octets_to_client{user="hello"} 16144733136 (15.04 GB)
telemt_user_unique_ips_current{user="hello"} 85
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 21222.6 (5h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18080
telemt_connections_bad_total 56
telemt_handshake_timeouts_total 60
telemt_upstream_connect_attempt_total 5925
telemt_upstream_connect_success_total 5925
telemt_upstream_connect_attempts_per_request{bucket="1"} 5925
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2597
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3322
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_reconnect_attempts_total 4864
telemt_me_reconnect_success_total 4843
telemt_me_reader_eof_total 5196
telemt_me_idle_close_by_peer_total 5196
telemt_me_route_drop_no_conn_total 9889
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 17089
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 4885
telemt_me_writer_restored_same_endpoint_total 4827
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 42
telemt_user_connections_total{user="hello"} 17093
telemt_user_connections_current{user="hello"} 128
telemt_user_octets_from_client{user="hello"} 603334668 (575.38 MB)
telemt_user_octets_to_client{user="hello"} 4812167108 (4.48 GB)
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 21215.1 (5h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21432
telemt_connections_bad_total 424
telemt_handshake_timeouts_total 1323
telemt_upstream_connect_attempt_total 5717
telemt_upstream_connect_success_total 5716
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 5717
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2508
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3202
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 4661
telemt_me_reconnect_success_total 4638
telemt_me_reader_eof_total 5006
telemt_me_idle_close_by_peer_total 5006
telemt_me_route_drop_no_conn_total 7038
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 19018
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 4675
telemt_me_writer_restored_same_endpoint_total 4634
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 18973
telemt_user_connections_current{user="hello"} 56
telemt_user_octets_from_client{user="hello"} 8693148140 (8.10 GB)
telemt_user_octets_to_client{user="hello"} 14949352360 (13.92 GB)
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 21215.0 (5h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 23183
telemt_connections_bad_total 103
telemt_handshake_timeouts_total 101
telemt_upstream_connect_attempt_total 5069
telemt_upstream_connect_success_total 5068
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 5069
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2358
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2697
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 4016
telemt_me_reconnect_success_total 4001
telemt_me_reader_eof_total 4275
telemt_me_idle_close_by_peer_total 4275
telemt_me_route_drop_no_conn_total 10714
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 21888
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 59
telemt_desync_full_logged_total 14
telemt_desync_suppressed_total 45
telemt_desync_frames_bucket_total{bucket="1_2"} 10
telemt_desync_frames_bucket_total{bucket="3_10"} 26
telemt_desync_frames_bucket_total{bucket="gt_10"} 23
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 4038
telemt_me_writer_restored_same_endpoint_total 3990
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 21810
telemt_user_connections_current{user="hello"} 140
telemt_user_octets_from_client{user="hello"} 484956428 (462.49 MB)
telemt_user_octets_to_client{user="hello"} 12970635264 (12.08 GB)
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## rdp-onedash.ru

Не удалось получить метрики для этого сервера.

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 21214.1 (5h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 63866
telemt_connections_bad_total 1511
telemt_handshake_timeouts_total 256
telemt_upstream_connect_attempt_total 4779
telemt_upstream_connect_success_total 4752
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 4779
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2393
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2358
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_reconnect_attempts_total 3693
telemt_me_reconnect_success_total 3678
telemt_me_reader_eof_total 3899
telemt_me_idle_close_by_peer_total 3899
telemt_me_route_drop_no_conn_total 35029
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 61773
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
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 3687
telemt_me_writer_restored_same_endpoint_total 3651
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 60332
telemt_user_connections_current{user="hello"} 217
telemt_user_octets_from_client{user="hello"} 1781537864 (1.66 GB)
telemt_user_octets_to_client{user="hello"} 39114206640 (36.43 GB)
telemt_user_unique_ips_current{user="hello"} 115
telemt_user_unique_ips_recent_window{user="hello"} 32
```