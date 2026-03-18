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

# Server Metrics 2026-03-18 08:55:15 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.20

telemt_uptime_seconds 855.3 (0h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 45424
telemt_connections_bad_total 159
telemt_handshake_timeouts_total 852
telemt_upstream_connect_attempt_total 28608
telemt_upstream_connect_success_total 28143
telemt_upstream_connect_fail_total 465
telemt_upstream_connect_attempts_per_request{bucket="1"} 28608
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26699
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1167
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 277
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 465
telemt_me_reconnect_attempts_total 413944
telemt_me_reconnect_success_total 264
telemt_me_reader_eof_total 140
telemt_me_idle_close_by_peer_total 138
telemt_me_route_drop_no_conn_total 2952
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7470
telemt_me_writer_pick_total{mode="p2c",result="full"} 21
telemt_me_writer_pick_total{mode="p2c",result="closed"} 52
telemt_me_endpoint_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 7
telemt_desync_full_logged_total 3
telemt_desync_suppressed_total 4
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 5
telemt_me_writer_removed_unexpected_total 166
telemt_me_refill_failed_total 13613
telemt_me_writer_restored_same_endpoint_total 161
telemt_me_writer_restored_fallback_total 103
telemt_me_async_recovery_trigger_total 10397
telemt_user_connections_total{user="hello"} 35240
telemt_user_connections_current{user="hello"} 1695
telemt_user_octets_from_client{user="hello"} 268959137 (256.50 MB)
telemt_user_octets_to_client{user="hello"} 5903566904 (5.50 GB)
telemt_user_msgs_from_client{user="hello"} 321106
telemt_user_msgs_to_client{user="hello"} 455020
telemt_user_unique_ips_current{user="hello"} 476
telemt_user_unique_ips_recent_window{user="hello"} 265
```

## psb.hosting

```
telemt 3.3.20

telemt_uptime_seconds 886.1 (0h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 88527
telemt_connections_bad_total 12829
telemt_handshake_timeouts_total 1442
telemt_upstream_connect_attempt_total 205
telemt_upstream_connect_success_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 205
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 162
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_reconnect_attempts_total 133
telemt_me_reconnect_success_total 130
telemt_me_reader_eof_total 78
telemt_me_idle_close_by_peer_total 78
telemt_me_route_drop_no_conn_total 26763
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 70517
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 289
telemt_desync_full_logged_total 79
telemt_desync_suppressed_total 210
telemt_desync_frames_bucket_total{bucket="1_2"} 49
telemt_desync_frames_bucket_total{bucket="3_10"} 126
telemt_desync_frames_bucket_total{bucket="gt_10"} 114
telemt_me_writer_removed_unexpected_total 99
telemt_me_writer_restored_same_endpoint_total 129
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 1068
telemt_user_connections_total{user="hello"} 70167
telemt_user_connections_current{user="hello"} 3264
telemt_user_octets_from_client{user="hello"} 2040802756 (1.90 GB)
telemt_user_octets_to_client{user="hello"} 18133313288 (16.89 GB)
telemt_user_unique_ips_current{user="hello"} 993
telemt_user_unique_ips_recent_window{user="hello"} 473
```

## koara.io

```
telemt 3.3.20

telemt_uptime_seconds 801.3 (0h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 58834
telemt_connections_bad_total 1718
telemt_handshake_timeouts_total 1316
telemt_upstream_connect_attempt_total 8537
telemt_upstream_connect_success_total 8537
telemt_upstream_connect_attempts_per_request{bucket="1"} 8537
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7168
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1363
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_reconnect_attempts_total 603693
telemt_me_reconnect_success_total 265
telemt_me_reader_eof_total 160
telemt_me_idle_close_by_peer_total 160
telemt_me_route_drop_no_conn_total 19139
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 40893
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 73
telemt_desync_full_logged_total 28
telemt_desync_suppressed_total 45
telemt_desync_frames_bucket_total{bucket="1_2"} 17
telemt_desync_frames_bucket_total{bucket="3_10"} 28
telemt_desync_frames_bucket_total{bucket="gt_10"} 28
telemt_me_writer_removed_unexpected_total 183
telemt_me_refill_failed_total 19602
telemt_me_writer_restored_same_endpoint_total 230
telemt_me_writer_restored_fallback_total 35
telemt_me_async_recovery_trigger_total 14847
telemt_user_connections_total{user="hello"} 49009
telemt_user_connections_current{user="hello"} 2069
telemt_user_octets_from_client{user="hello"} 293745883 (280.14 MB)
telemt_user_octets_to_client{user="hello"} 11476695420 (10.69 GB)
telemt_user_msgs_from_client{user="hello"} 68547
telemt_user_msgs_to_client{user="hello"} 285346
telemt_user_unique_ips_current{user="hello"} 609
telemt_user_unique_ips_recent_window{user="hello"} 286
```

## landvps.ru

```
telemt 3.3.20

telemt_uptime_seconds 831.2 (0h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 73857
telemt_connections_bad_total 1510
telemt_handshake_timeouts_total 2650
telemt_upstream_connect_attempt_total 10755
telemt_upstream_connect_success_total 10693
telemt_upstream_connect_fail_total 62
telemt_upstream_connect_attempts_per_request{bucket="1"} 10755
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9943
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 723
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 62
telemt_me_reconnect_attempts_total 2809654
telemt_me_reconnect_success_total 345
telemt_me_reader_eof_total 292
telemt_me_idle_close_by_peer_total 292
telemt_me_route_drop_no_conn_total 19901
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 51788
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 98
telemt_desync_full_logged_total 33
telemt_desync_suppressed_total 65
telemt_desync_frames_bucket_total{bucket="1_2"} 26
telemt_desync_frames_bucket_total{bucket="3_10"} 34
telemt_desync_frames_bucket_total{bucket="gt_10"} 38
telemt_me_writer_removed_unexpected_total 314
telemt_me_refill_failed_total 99529
telemt_me_writer_restored_same_endpoint_total 250
telemt_me_writer_restored_fallback_total 95
telemt_me_async_recovery_trigger_total 365465
telemt_user_connections_total{user="hello"} 62068
telemt_user_connections_current{user="hello"} 2927
telemt_user_octets_from_client{user="hello"} 504055514 (480.70 MB)
telemt_user_octets_to_client{user="hello"} 13278556069 (12.37 GB)
telemt_user_msgs_from_client{user="hello"} 80007
telemt_user_msgs_to_client{user="hello"} 158054
telemt_user_unique_ips_current{user="hello"} 821
telemt_user_unique_ips_recent_window{user="hello"} 408
```

## rdp-onedash.ru

```
telemt 3.3.20

telemt_uptime_seconds 726.2 (0h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 57669
telemt_connections_bad_total 1733
telemt_handshake_timeouts_total 443
telemt_upstream_connect_attempt_total 9895
telemt_upstream_connect_success_total 9894
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 9895
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9174
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 514
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 206
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 2982205
telemt_me_reconnect_success_total 326
telemt_me_reader_eof_total 243
telemt_me_idle_close_by_peer_total 243
telemt_me_route_drop_no_conn_total 11960
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 39173
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 115
telemt_desync_full_logged_total 42
telemt_desync_suppressed_total 73
telemt_desync_frames_bucket_total{bucket="1_2"} 22
telemt_desync_frames_bucket_total{bucket="3_10"} 47
telemt_desync_frames_bucket_total{bucket="gt_10"} 46
telemt_me_writer_removed_unexpected_total 265
telemt_me_refill_failed_total 107151
telemt_me_writer_restored_same_endpoint_total 211
telemt_me_writer_restored_fallback_total 115
telemt_me_async_recovery_trigger_total 267383
telemt_user_connections_total{user="hello"} 48657
telemt_user_connections_current{user="hello"} 2432
telemt_user_octets_from_client{user="hello"} 674529037 (643.28 MB)
telemt_user_octets_to_client{user="hello"} 16007374937 (14.91 GB)
telemt_user_msgs_from_client{user="hello"} 86293
telemt_user_msgs_to_client{user="hello"} 266108
telemt_user_unique_ips_current{user="hello"} 736
telemt_user_unique_ips_recent_window{user="hello"} 342
```

## hostvds.com

```
telemt 3.3.20

telemt_uptime_seconds 611.1 (0h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14136
telemt_connections_bad_total 3039
telemt_handshake_timeouts_total 59
telemt_upstream_connect_attempt_total 121
telemt_upstream_connect_success_total 121
telemt_upstream_connect_attempts_per_request{bucket="1"} 121
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 84
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37
telemt_me_reconnect_attempts_total 52
telemt_me_reconnect_success_total 52
telemt_me_reader_eof_total 16
telemt_me_idle_close_by_peer_total 16
telemt_me_route_drop_no_conn_total 3260
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10377
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 22
telemt_desync_full_logged_total 8
telemt_desync_suppressed_total 14
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 10
telemt_desync_frames_bucket_total{bucket="gt_10"} 9
telemt_me_writer_removed_unexpected_total 38
telemt_me_writer_restored_same_endpoint_total 44
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 130
telemt_user_connections_total{user="hello"} 10376
telemt_user_connections_current{user="hello"} 847
telemt_user_octets_from_client{user="hello"} 515493056 (491.61 MB)
telemt_user_octets_to_client{user="hello"} 1625517136 (1.51 GB)
telemt_user_unique_ips_current{user="hello"} 294
telemt_user_unique_ips_recent_window{user="hello"} 130
```

## 4vps.su

```
telemt 3.3.20

telemt_uptime_seconds 682.2 (0h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 33737
telemt_connections_bad_total 18
telemt_handshake_timeouts_total 844
telemt_upstream_connect_attempt_total 139
telemt_upstream_connect_success_total 128
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 139
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 86
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_reconnect_attempts_total 62
telemt_me_reconnect_success_total 59
telemt_me_reader_eof_total 17
telemt_me_idle_close_by_peer_total 17
telemt_me_route_drop_no_conn_total 14154
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 30464
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 93
telemt_desync_full_logged_total 28
telemt_desync_suppressed_total 65
telemt_desync_frames_bucket_total{bucket="1_2"} 17
telemt_desync_frames_bucket_total{bucket="3_10"} 45
telemt_desync_frames_bucket_total{bucket="gt_10"} 31
telemt_me_writer_removed_unexpected_total 40
telemt_me_writer_restored_same_endpoint_total 49
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 2494
telemt_user_connections_total{user="hello"} 30422
telemt_user_connections_current{user="hello"} 1923
telemt_user_octets_from_client{user="hello"} 345035012 (329.05 MB)
telemt_user_octets_to_client{user="hello"} 12701290524 (11.83 GB)
telemt_user_unique_ips_current{user="hello"} 598
telemt_user_unique_ips_recent_window{user="hello"} 264
```