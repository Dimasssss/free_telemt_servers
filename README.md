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

# Server Metrics 2026-03-15 03:46:51 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 19926.2 (5h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 46488
telemt_connections_bad_total 383
telemt_handshake_timeouts_total 320
telemt_upstream_connect_attempt_total 5073
telemt_upstream_connect_success_total 5041
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 5073
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2296
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2741
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 4028
telemt_me_reconnect_success_total 4012
telemt_me_reader_eof_total 4278
telemt_me_idle_close_by_peer_total 4278
telemt_me_route_drop_no_conn_total 13788
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 44299
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 264
telemt_desync_full_logged_total 122
telemt_desync_suppressed_total 142
telemt_desync_frames_bucket_total{bucket="1_2"} 47
telemt_desync_frames_bucket_total{bucket="3_10"} 113
telemt_desync_frames_bucket_total{bucket="gt_10"} 104
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 4033
telemt_me_writer_restored_same_endpoint_total 3981
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 21
telemt_user_connections_total{user="hello"} 44297
telemt_user_connections_current{user="hello"} 263
telemt_user_octets_from_client{user="hello"} 477015416 (454.92 MB)
telemt_user_octets_to_client{user="hello"} 14889134396 (13.87 GB)
telemt_user_unique_ips_current{user="hello"} 77
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 19932.4 (5h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17002
telemt_connections_bad_total 51
telemt_handshake_timeouts_total 55
telemt_upstream_connect_attempt_total 5590
telemt_upstream_connect_success_total 5590
telemt_upstream_connect_attempts_per_request{bucket="1"} 5590
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2450
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3134
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_reconnect_attempts_total 4573
telemt_me_reconnect_success_total 4554
telemt_me_reader_eof_total 4874
telemt_me_idle_close_by_peer_total 4874
telemt_me_route_drop_no_conn_total 8634
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16060
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 4592
telemt_me_writer_restored_same_endpoint_total 4538
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 38
telemt_user_connections_total{user="hello"} 16064
telemt_user_connections_current{user="hello"} 140
telemt_user_octets_from_client{user="hello"} 593541936 (566.05 MB)
telemt_user_octets_to_client{user="hello"} 4211095048 (3.92 GB)
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 19924.9 (5h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18913
telemt_connections_bad_total 424
telemt_handshake_timeouts_total 317
telemt_upstream_connect_attempt_total 5367
telemt_upstream_connect_success_total 5366
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 5367
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2365
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2995
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 4354
telemt_me_reconnect_success_total 4331
telemt_me_reader_eof_total 4668
telemt_me_idle_close_by_peer_total 4668
telemt_me_route_drop_no_conn_total 6599
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 17570
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 4367
telemt_me_writer_restored_same_endpoint_total 4327
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 36
telemt_user_connections_total{user="hello"} 17525
telemt_user_connections_current{user="hello"} 62
telemt_user_octets_from_client{user="hello"} 8687273088 (8.09 GB)
telemt_user_octets_to_client{user="hello"} 14557798232 (13.56 GB)
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 19924.8 (5h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21182
telemt_connections_bad_total 103
telemt_handshake_timeouts_total 95
telemt_upstream_connect_attempt_total 4793
telemt_upstream_connect_success_total 4792
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 4793
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2223
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2556
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 3783
telemt_me_reconnect_success_total 3769
telemt_me_reader_eof_total 4020
telemt_me_idle_close_by_peer_total 4020
telemt_me_route_drop_no_conn_total 10046
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 20142
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 56
telemt_desync_full_logged_total 12
telemt_desync_suppressed_total 44
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 26
telemt_desync_frames_bucket_total{bucket="gt_10"} 23
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 3804
telemt_me_writer_restored_same_endpoint_total 3758
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 20065
telemt_user_connections_current{user="hello"} 115
telemt_user_octets_from_client{user="hello"} 450924584 (430.04 MB)
telemt_user_octets_to_client{user="hello"} 12661402556 (11.79 GB)
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## rdp-onedash.ru

Не удалось получить метрики для этого сервера.

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 19924.0 (5h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 60132
telemt_connections_bad_total 1485
telemt_handshake_timeouts_total 242
telemt_upstream_connect_attempt_total 4506
telemt_upstream_connect_success_total 4481
telemt_upstream_connect_fail_total 25
telemt_upstream_connect_attempts_per_request{bucket="1"} 4506
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2250
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2230
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 25
telemt_me_reconnect_attempts_total 3466
telemt_me_reconnect_success_total 3452
telemt_me_reader_eof_total 3656
telemt_me_idle_close_by_peer_total 3656
telemt_me_route_drop_no_conn_total 32839
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 58188
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
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 3458
telemt_me_writer_restored_same_endpoint_total 3425
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 56747
telemt_user_connections_current{user="hello"} 237
telemt_user_octets_from_client{user="hello"} 1753636448 (1.63 GB)
telemt_user_octets_to_client{user="hello"} 37136928668 (34.59 GB)
telemt_user_unique_ips_current{user="hello"} 111
telemt_user_unique_ips_recent_window{user="hello"} 37
```