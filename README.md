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

# Server Metrics 2026-03-15 06:33:39 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 29951.4 (8h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 85286
telemt_connections_bad_total 450
telemt_handshake_timeouts_total 1651
telemt_upstream_connect_attempt_total 7345
telemt_upstream_connect_success_total 7302
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 7345
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3323
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3975
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 5813
telemt_me_reconnect_success_total 5793
telemt_me_reader_eof_total 6207
telemt_me_idle_close_by_peer_total 6207
telemt_me_route_drop_no_conn_total 91841
telemt_me_route_drop_channel_closed_total 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 91043
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 687
telemt_desync_full_logged_total 302
telemt_desync_suppressed_total 385
telemt_desync_frames_bucket_total{bucket="1_2"} 120
telemt_desync_frames_bucket_total{bucket="3_10"} 285
telemt_desync_frames_bucket_total{bucket="gt_10"} 282
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 5839
telemt_me_writer_restored_same_endpoint_total 5762
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 79914
telemt_user_connections_current{user="hello"} 277
telemt_user_octets_from_client{user="hello"} 1014427892 (967.43 MB)
telemt_user_octets_to_client{user="hello"} 45356393188 (42.24 GB)
telemt_user_unique_ips_current{user="hello"} 94
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 29957.6 (8h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 28513
telemt_connections_bad_total 113
telemt_handshake_timeouts_total 120
telemt_upstream_connect_attempt_total 8092
telemt_upstream_connect_success_total 8092
telemt_upstream_connect_attempts_per_request{bucket="1"} 8092
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3555
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4530
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 6598
telemt_me_reconnect_success_total 6572
telemt_me_reader_eof_total 7069
telemt_me_idle_close_by_peer_total 7069
telemt_me_route_drop_no_conn_total 14428
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 27126
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 6633
telemt_me_writer_restored_same_endpoint_total 6556
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 61
telemt_user_connections_total{user="hello"} 27129
telemt_user_connections_current{user="hello"} 152
telemt_user_octets_from_client{user="hello"} 738157660 (703.96 MB)
telemt_user_octets_to_client{user="hello"} 10258350644 (9.55 GB)
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 29950.0 (8h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 36347
telemt_connections_bad_total 455
telemt_handshake_timeouts_total 1773
telemt_upstream_connect_attempt_total 8000
telemt_upstream_connect_success_total 7999
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 8000
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3523
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4470
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 6509
telemt_me_reconnect_success_total 6481
telemt_me_reader_eof_total 7012
telemt_me_idle_close_by_peer_total 7012
telemt_me_route_drop_no_conn_total 12607
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 32923
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 6537
telemt_me_writer_restored_same_endpoint_total 6477
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 56
telemt_user_connections_total{user="hello"} 32870
telemt_user_connections_current{user="hello"} 109
telemt_user_octets_from_client{user="hello"} 8778218792 (8.18 GB)
telemt_user_octets_to_client{user="hello"} 17884120152 (16.66 GB)
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 29949.9 (8h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 40324
telemt_connections_bad_total 129
telemt_handshake_timeouts_total 264
telemt_upstream_connect_attempt_total 7076
telemt_upstream_connect_success_total 7075
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 7076
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3291
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3763
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 5591
telemt_me_reconnect_success_total 5570
telemt_me_reader_eof_total 5971
telemt_me_idle_close_by_peer_total 5971
telemt_me_route_drop_no_conn_total 17685
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 36332
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 78
telemt_desync_full_logged_total 21
telemt_desync_suppressed_total 57
telemt_desync_frames_bucket_total{bucket="1_2"} 19
telemt_desync_frames_bucket_total{bucket="3_10"} 32
telemt_desync_frames_bucket_total{bucket="gt_10"} 27
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 5627
telemt_me_writer_restored_same_endpoint_total 5559
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 36251
telemt_user_connections_current{user="hello"} 206
telemt_user_octets_from_client{user="hello"} 641491376 (611.77 MB)
telemt_user_octets_to_client{user="hello"} 23590243108 (21.97 GB)
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 5021.3 (1h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7247
telemt_connections_bad_total 963
telemt_handshake_timeouts_total 145
telemt_upstream_connect_attempt_total 2109
telemt_upstream_connect_success_total 2080
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 2109
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 903
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1167
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_reconnect_attempts_total 96037
telemt_me_reconnect_success_total 1645
telemt_me_reader_eof_total 1623
telemt_me_idle_close_by_peer_total 1623
telemt_me_route_drop_no_conn_total 1905
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5870
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 1572
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 1541
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_user_connections_total{user="hello"} 6015
telemt_user_connections_current{user="hello"} 48
telemt_user_octets_from_client{user="hello"} 34808381 (33.20 MB)
telemt_user_octets_to_client{user="hello"} 1883301023 (1.75 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 29949.1 (8h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 101651
telemt_connections_bad_total 1946
telemt_handshake_timeouts_total 453
telemt_upstream_connect_attempt_total 6611
telemt_upstream_connect_success_total 6574
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 6611
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3296
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3277
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_reconnect_attempts_total 5082
telemt_me_reconnect_success_total 5059
telemt_me_reader_eof_total 5389
telemt_me_idle_close_by_peer_total 5389
telemt_me_route_drop_no_conn_total 54601
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 96364
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
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 5081
telemt_me_writer_restored_same_endpoint_total 5032
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 94922
telemt_user_connections_current{user="hello"} 380
telemt_user_octets_from_client{user="hello"} 2385557752 (2.22 GB)
telemt_user_octets_to_client{user="hello"} 49509751336 (46.11 GB)
telemt_user_unique_ips_current{user="hello"} 158
telemt_user_unique_ips_recent_window{user="hello"} 60
```