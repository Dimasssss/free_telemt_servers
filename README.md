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

# Server Metrics 2026-03-16 14:22:39 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 2686.0 (0h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 34215
telemt_connections_bad_total 143
telemt_handshake_timeouts_total 964
telemt_upstream_connect_attempt_total 491
telemt_upstream_connect_success_total 489
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 491
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 255
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 234
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 333
telemt_me_reconnect_success_total 329
telemt_me_reader_eof_total 297
telemt_me_idle_close_by_peer_total 297
telemt_me_route_drop_no_conn_total 9650
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 31721
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 54
telemt_desync_full_logged_total 16
telemt_desync_suppressed_total 38
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 30
telemt_desync_frames_bucket_total{bucket="gt_10"} 11
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 319
telemt_me_writer_restored_same_endpoint_total 327
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 36
telemt_user_connections_total{user="hello"} 31667
telemt_user_connections_current{user="hello"} 722
telemt_user_octets_from_client{user="hello"} 805006368 (767.71 MB)
telemt_user_octets_to_client{user="hello"} 19494495656 (18.16 GB)
telemt_user_unique_ips_current{user="hello"} 210
telemt_user_unique_ips_recent_window{user="hello"} 88
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 250.1 (0h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2923
telemt_connections_bad_total 120
telemt_handshake_timeouts_total 18
telemt_upstream_connect_attempt_total 2688
telemt_upstream_connect_success_total 2681
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 2687
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2239
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 135
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 307
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 2679
telemt_user_connections_current{user="hello"} 610
telemt_user_octets_from_client{user="hello"} 42548753 (40.58 MB)
telemt_user_octets_to_client{user="hello"} 363836332 (346.98 MB)
telemt_user_msgs_from_client{user="hello"} 40337
telemt_user_msgs_to_client{user="hello"} 111019
telemt_user_unique_ips_current{user="hello"} 132
telemt_user_unique_ips_recent_window{user="hello"} 64
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 2798.9 (0h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13840
telemt_connections_bad_total 3
telemt_handshake_timeouts_total 105
telemt_upstream_connect_attempt_total 2133
telemt_upstream_connect_success_total 2103
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 2133
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1264
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 820
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_reconnect_attempts_total 29303
telemt_me_reconnect_success_total 961
telemt_me_reader_eof_total 928
telemt_me_idle_close_by_peer_total 928
telemt_me_route_drop_no_conn_total 3177
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 11989
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_writer_removed_unexpected_total 949
telemt_me_refill_failed_total 885
telemt_me_writer_restored_same_endpoint_total 917
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 1272
telemt_user_connections_total{user="hello"} 12946
telemt_user_connections_current{user="hello"} 250
telemt_user_octets_from_client{user="hello"} 165888342 (158.20 MB)
telemt_user_octets_to_client{user="hello"} 2192827258 (2.04 GB)
telemt_user_msgs_from_client{user="hello"} 4789
telemt_user_msgs_to_client{user="hello"} 14129
telemt_user_unique_ips_current{user="hello"} 94
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 2934.9 (0h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 24620
telemt_connections_bad_total 17
telemt_handshake_timeouts_total 494
telemt_upstream_connect_attempt_total 730
telemt_upstream_connect_success_total 727
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 730
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 403
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 316
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 1477
telemt_me_reconnect_success_total 504
telemt_me_reader_eof_total 512
telemt_me_idle_close_by_peer_total 512
telemt_me_route_drop_no_conn_total 7194
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 23036
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 168
telemt_desync_full_logged_total 44
telemt_desync_suppressed_total 124
telemt_desync_frames_bucket_total{bucket="1_2"} 27
telemt_desync_frames_bucket_total{bucket="3_10"} 69
telemt_desync_frames_bucket_total{bucket="gt_10"} 72
telemt_me_writer_removed_unexpected_total 531
telemt_me_refill_failed_total 30
telemt_me_writer_restored_same_endpoint_total 500
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 23018
telemt_user_connections_current{user="hello"} 467
telemt_user_octets_from_client{user="hello"} 621706576 (592.91 MB)
telemt_user_octets_to_client{user="hello"} 5002743524 (4.66 GB)
telemt_user_unique_ips_current{user="hello"} 138
telemt_user_unique_ips_recent_window{user="hello"} 65
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 395.4 (0h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1854
telemt_connections_bad_total 246
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 134
telemt_upstream_connect_success_total 132
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 134
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 72
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 67
telemt_me_reconnect_success_total 66
telemt_me_reader_eof_total 35
telemt_me_idle_close_by_peer_total 35
telemt_me_route_drop_no_conn_total 424
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1537
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 1
telemt_desync_full_logged_total 1
telemt_desync_frames_bucket_total{bucket="1_2"} 1
telemt_me_writer_removed_unexpected_total 52
telemt_me_writer_restored_same_endpoint_total 66
telemt_me_async_recovery_trigger_total 22
telemt_user_connections_total{user="hello"} 1523
telemt_user_connections_current{user="hello"} 172
telemt_user_octets_from_client{user="hello"} 161634152 (154.15 MB)
telemt_user_octets_to_client{user="hello"} 149410816 (142.49 MB)
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 2502.6 (0h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 31463
telemt_connections_bad_total 642
telemt_handshake_timeouts_total 252
telemt_upstream_connect_attempt_total 527
telemt_upstream_connect_success_total 527
telemt_upstream_connect_attempts_per_request{bucket="1"} 527
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 298
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 229
telemt_me_reconnect_attempts_total 367
telemt_me_reconnect_success_total 365
telemt_me_reader_eof_total 337
telemt_me_idle_close_by_peer_total 337
telemt_me_route_drop_no_conn_total 13193
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 29800
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9
telemt_desync_full_logged_total 4
telemt_desync_suppressed_total 5
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 7
telemt_me_writer_removed_unexpected_total 359
telemt_me_writer_restored_same_endpoint_total 361
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 208
telemt_user_connections_total{user="hello"} 29673
telemt_user_connections_current{user="hello"} 835
telemt_user_octets_from_client{user="hello"} 820673252 (782.66 MB)
telemt_user_octets_to_client{user="hello"} 7989404832 (7.44 GB)
telemt_user_unique_ips_current{user="hello"} 260
telemt_user_unique_ips_recent_window{user="hello"} 104
```