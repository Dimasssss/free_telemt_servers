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

# Server Metrics 2026-03-16 14:12:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 2072.3 (0h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 27095
telemt_connections_bad_total 143
telemt_handshake_timeouts_total 701
telemt_upstream_connect_attempt_total 383
telemt_upstream_connect_success_total 381
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 383
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 212
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 169
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 225
telemt_me_reconnect_success_total 221
telemt_me_reader_eof_total 189
telemt_me_idle_close_by_peer_total 189
telemt_me_route_drop_no_conn_total 7975
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 25068
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 23
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 17
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 9
telemt_desync_frames_bucket_total{bucket="gt_10"} 8
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 211
telemt_me_writer_restored_same_endpoint_total 219
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 36
telemt_user_connections_total{user="hello"} 25015
telemt_user_connections_current{user="hello"} 746
telemt_user_octets_from_client{user="hello"} 506953364 (483.47 MB)
telemt_user_octets_to_client{user="hello"} 17310725612 (16.12 GB)
telemt_user_unique_ips_current{user="hello"} 215
telemt_user_unique_ips_recent_window{user="hello"} 84
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 1574.9 (0h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17260
telemt_connections_bad_total 776
telemt_handshake_timeouts_total 74
telemt_upstream_connect_attempt_total 15748
telemt_upstream_connect_success_total 15727
telemt_upstream_connect_fail_total 20
telemt_upstream_connect_attempts_per_request{bucket="1"} 15747
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12890
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 938
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1899
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 15725
telemt_user_connections_current{user="hello"} 573
telemt_user_octets_from_client{user="hello"} 120491622 (114.91 MB)
telemt_user_octets_to_client{user="hello"} 1941589911 (1.81 GB)
telemt_user_msgs_from_client{user="hello"} 181111
telemt_user_msgs_to_client{user="hello"} 675428
telemt_user_unique_ips_current{user="hello"} 121
telemt_user_unique_ips_recent_window{user="hello"} 68
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 2185.0 (0h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10922
telemt_connections_bad_total 3
telemt_handshake_timeouts_total 72
telemt_upstream_connect_attempt_total 2064
telemt_upstream_connect_success_total 2034
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 2064
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1243
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 772
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_reconnect_attempts_total 29250
telemt_me_reconnect_success_total 909
telemt_me_reader_eof_total 874
telemt_me_idle_close_by_peer_total 874
telemt_me_route_drop_no_conn_total 2518
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9265
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_writer_removed_unexpected_total 895
telemt_me_refill_failed_total 885
telemt_me_writer_restored_same_endpoint_total 865
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 1272
telemt_user_connections_total{user="hello"} 10222
telemt_user_connections_current{user="hello"} 326
telemt_user_octets_from_client{user="hello"} 95144854 (90.74 MB)
telemt_user_octets_to_client{user="hello"} 1613576466 (1.50 GB)
telemt_user_msgs_from_client{user="hello"} 4789
telemt_user_msgs_to_client{user="hello"} 14129
telemt_user_unique_ips_current{user="hello"} 104
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 2321.2 (0h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19723
telemt_connections_bad_total 16
telemt_handshake_timeouts_total 195
telemt_upstream_connect_attempt_total 543
telemt_upstream_connect_success_total 541
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 543
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 325
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 212
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 376
telemt_me_reconnect_success_total 365
telemt_me_reader_eof_total 343
telemt_me_idle_close_by_peer_total 343
telemt_me_route_drop_no_conn_total 5821
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 18736
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 9
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 154
telemt_desync_full_logged_total 40
telemt_desync_suppressed_total 114
telemt_desync_frames_bucket_total{bucket="1_2"} 24
telemt_desync_frames_bucket_total{bucket="3_10"} 62
telemt_desync_frames_bucket_total{bucket="gt_10"} 68
telemt_me_writer_removed_unexpected_total 358
telemt_me_writer_restored_same_endpoint_total 361
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 18
telemt_user_connections_total{user="hello"} 18719
telemt_user_connections_current{user="hello"} 438
telemt_user_octets_from_client{user="hello"} 338465228 (322.79 MB)
telemt_user_octets_to_client{user="hello"} 4027170880 (3.75 GB)
telemt_user_unique_ips_current{user="hello"} 144
telemt_user_unique_ips_recent_window{user="hello"} 60
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 2310.6 (0h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14630
telemt_connections_bad_total 4449
telemt_handshake_timeouts_total 73
telemt_upstream_connect_attempt_total 581
telemt_upstream_connect_success_total 580
telemt_upstream_connect_attempts_per_request{bucket="1"} 580
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 250
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 329
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 415
telemt_me_reconnect_success_total 408
telemt_me_reader_eof_total 391
telemt_me_idle_close_by_peer_total 391
telemt_me_route_drop_no_conn_total 2297
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9680
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2
telemt_desync_full_logged_total 2
telemt_desync_frames_bucket_total{bucket="1_2"} 1
telemt_desync_frames_bucket_total{bucket="3_10"} 1
telemt_me_writer_removed_unexpected_total 410
telemt_me_writer_restored_same_endpoint_total 407
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 9668
telemt_user_connections_current{user="hello"} 204
telemt_user_octets_from_client{user="hello"} 239552700 (228.46 MB)
telemt_user_octets_to_client{user="hello"} 2840159372 (2.65 GB)
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 1888.7 (0h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 23695
telemt_connections_bad_total 471
telemt_handshake_timeouts_total 115
telemt_upstream_connect_attempt_total 343
telemt_upstream_connect_success_total 343
telemt_upstream_connect_attempts_per_request{bucket="1"} 343
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 207
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 136
telemt_me_reconnect_attempts_total 200
telemt_me_reconnect_success_total 199
telemt_me_reader_eof_total 168
telemt_me_idle_close_by_peer_total 168
telemt_me_route_drop_no_conn_total 10475
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 22505
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8
telemt_desync_full_logged_total 3
telemt_desync_suppressed_total 5
telemt_desync_frames_bucket_total{bucket="1_2"} 1
telemt_desync_frames_bucket_total{bucket="3_10"} 7
telemt_me_writer_removed_unexpected_total 190
telemt_me_writer_restored_same_endpoint_total 195
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 208
telemt_user_connections_total{user="hello"} 22380
telemt_user_connections_current{user="hello"} 785
telemt_user_octets_from_client{user="hello"} 498518356 (475.42 MB)
telemt_user_octets_to_client{user="hello"} 4943431428 (4.60 GB)
telemt_user_unique_ips_current{user="hello"} 270
telemt_user_unique_ips_recent_window{user="hello"} 111
```