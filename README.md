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

# Server Metrics 2026-03-18 08:45:04 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.20

telemt_uptime_seconds 243.7 (0h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19645
telemt_connections_bad_total 82
telemt_handshake_timeouts_total 203
telemt_upstream_connect_attempt_total 8625
telemt_upstream_connect_success_total 8521
telemt_upstream_connect_fail_total 100
telemt_upstream_connect_attempts_per_request{bucket="1"} 8621
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8062
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 376
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 83
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 100
telemt_me_reconnect_attempts_total 336303
telemt_me_reconnect_success_total 215
telemt_me_reader_eof_total 92
telemt_me_idle_close_by_peer_total 90
telemt_me_route_drop_no_conn_total 2734
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7460
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
telemt_me_writer_removed_unexpected_total 114
telemt_me_refill_failed_total 11189
telemt_me_writer_restored_same_endpoint_total 112
telemt_me_writer_restored_fallback_total 103
telemt_me_async_recovery_trigger_total 9107
telemt_user_connections_total{user="hello"} 15677
telemt_user_connections_current{user="hello"} 1270
telemt_user_octets_from_client{user="hello"} 81351956 (77.58 MB)
telemt_user_octets_to_client{user="hello"} 1287394064 (1.20 GB)
telemt_user_msgs_from_client{user="hello"} 53489
telemt_user_msgs_to_client{user="hello"} 63365
telemt_user_unique_ips_current{user="hello"} 386
telemt_user_unique_ips_recent_window{user="hello"} 195
```

## psb.hosting

```
telemt 3.3.20

telemt_uptime_seconds 274.1 (0h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 32803
telemt_connections_bad_total 1208
telemt_handshake_timeouts_total 368
telemt_upstream_connect_attempt_total 169
telemt_upstream_connect_success_total 169
telemt_upstream_connect_attempts_per_request{bucket="1"} 169
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 128
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 97
telemt_me_reconnect_success_total 94
telemt_me_reader_eof_total 33
telemt_me_idle_close_by_peer_total 33
telemt_me_route_drop_no_conn_total 13109
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 29480
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 75
telemt_desync_full_logged_total 19
telemt_desync_suppressed_total 56
telemt_desync_frames_bucket_total{bucket="1_2"} 14
telemt_desync_frames_bucket_total{bucket="3_10"} 38
telemt_desync_frames_bucket_total{bucket="gt_10"} 23
telemt_me_writer_removed_unexpected_total 54
telemt_me_writer_restored_same_endpoint_total 93
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 1068
telemt_user_connections_total{user="hello"} 29122
telemt_user_connections_current{user="hello"} 2982
telemt_user_octets_from_client{user="hello"} 192294200 (183.39 MB)
telemt_user_octets_to_client{user="hello"} 5229969852 (4.87 GB)
telemt_user_unique_ips_current{user="hello"} 912
telemt_user_unique_ips_recent_window{user="hello"} 434
```

## koara.io

```
telemt 3.3.20

telemt_uptime_seconds 189.6 (0h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 24438
telemt_connections_bad_total 237
telemt_handshake_timeouts_total 368
telemt_upstream_connect_attempt_total 8464
telemt_upstream_connect_success_total 8464
telemt_upstream_connect_attempts_per_request{bucket="1"} 8464
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7167
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1291
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_reconnect_attempts_total 603620
telemt_me_reconnect_success_total 192
telemt_me_reader_eof_total 83
telemt_me_idle_close_by_peer_total 83
telemt_me_route_drop_no_conn_total 4597
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13260
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 6
telemt_desync_full_logged_total 5
telemt_desync_suppressed_total 1
telemt_desync_frames_bucket_total{bucket="3_10"} 6
telemt_me_writer_removed_unexpected_total 106
telemt_me_refill_failed_total 19602
telemt_me_writer_restored_same_endpoint_total 157
telemt_me_writer_restored_fallback_total 35
telemt_me_async_recovery_trigger_total 14847
telemt_user_connections_total{user="hello"} 21382
telemt_user_connections_current{user="hello"} 2223
telemt_user_octets_from_client{user="hello"} 81073939 (77.32 MB)
telemt_user_octets_to_client{user="hello"} 3496044040 (3.26 GB)
telemt_user_msgs_from_client{user="hello"} 68547
telemt_user_msgs_to_client{user="hello"} 285346
telemt_user_unique_ips_current{user="hello"} 566
telemt_user_unique_ips_recent_window{user="hello"} 275
```

## landvps.ru

```
telemt 3.3.20

telemt_uptime_seconds 219.4 (0h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 28936
telemt_connections_bad_total 445
telemt_handshake_timeouts_total 210
telemt_upstream_connect_attempt_total 10662
telemt_upstream_connect_success_total 10601
telemt_upstream_connect_fail_total 61
telemt_upstream_connect_attempts_per_request{bucket="1"} 10662
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9872
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 703
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 61
telemt_me_reconnect_attempts_total 2809561
telemt_me_reconnect_success_total 253
telemt_me_reader_eof_total 165
telemt_me_idle_close_by_peer_total 165
telemt_me_route_drop_no_conn_total 5757
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 14894
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 25
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 19
telemt_desync_frames_bucket_total{bucket="1_2"} 8
telemt_desync_frames_bucket_total{bucket="3_10"} 9
telemt_desync_frames_bucket_total{bucket="gt_10"} 8
telemt_me_writer_removed_unexpected_total 187
telemt_me_refill_failed_total 99529
telemt_me_writer_restored_same_endpoint_total 158
telemt_me_writer_restored_fallback_total 95
telemt_me_async_recovery_trigger_total 365465
telemt_user_connections_total{user="hello"} 25188
telemt_user_connections_current{user="hello"} 2950
telemt_user_octets_from_client{user="hello"} 146184362 (139.41 MB)
telemt_user_octets_to_client{user="hello"} 2924842993 (2.72 GB)
telemt_user_msgs_from_client{user="hello"} 80007
telemt_user_msgs_to_client{user="hello"} 158054
telemt_user_unique_ips_current{user="hello"} 729
telemt_user_unique_ips_recent_window{user="hello"} 361
```

## rdp-onedash.ru

```
telemt 3.3.20

telemt_uptime_seconds 114.3 (0h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13815
telemt_connections_bad_total 227
telemt_handshake_timeouts_total 76
telemt_upstream_connect_attempt_total 9584
telemt_upstream_connect_success_total 9579
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 9580
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8916
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 457
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 206
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 2908335
telemt_me_reconnect_success_total 127
telemt_me_route_drop_no_conn_total 363
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1333
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_writer_removed_unexpected_total 22
telemt_me_refill_failed_total 104849
telemt_me_writer_restored_same_endpoint_total 12
telemt_me_writer_restored_fallback_total 115
telemt_me_async_recovery_trigger_total 261820
telemt_user_connections_total{user="hello"} 11673
telemt_user_connections_current{user="hello"} 3511
telemt_user_octets_from_client{user="hello"} 82641433 (78.81 MB)
telemt_user_octets_to_client{user="hello"} 1606182128 (1.50 GB)
telemt_user_msgs_from_client{user="hello"} 83629
telemt_user_msgs_to_client{user="hello"} 258775
telemt_user_unique_ips_current{user="hello"} 762
telemt_user_unique_ips_recent_window{user="hello"} 320
```

## hostvds.com

```
telemt 3.3.20

telemt_uptime_seconds 75.3 (0h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4060
telemt_connections_bad_total 131
telemt_handshake_timeouts_total 32
telemt_upstream_connect_attempt_total 119
telemt_upstream_connect_success_total 104
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 118
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 62
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_reconnect_attempts_total 49
telemt_me_reconnect_success_total 35
telemt_me_route_drop_no_conn_total 1246
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2837
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_writer_removed_unexpected_total 22
telemt_me_writer_restored_same_endpoint_total 14
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 1984
telemt_user_connections_total{user="hello"} 2837
telemt_user_connections_current{user="hello"} 810
telemt_user_octets_from_client{user="hello"} 19621972 (18.71 MB)
telemt_user_octets_to_client{user="hello"} 155423244 (148.22 MB)
telemt_user_unique_ips_current{user="hello"} 258
telemt_user_unique_ips_recent_window{user="hello"} 172
```

## 4vps.su

```
telemt 3.3.20

telemt_uptime_seconds 70.3 (0h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5780
telemt_upstream_connect_attempt_total 121
telemt_upstream_connect_success_total 110
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 121
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 70
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_reconnect_attempts_total 44
telemt_me_reconnect_success_total 41
telemt_me_route_drop_no_conn_total 1787
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5194
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 11
telemt_desync_full_logged_total 3
telemt_desync_suppressed_total 8
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 4
telemt_desync_frames_bucket_total{bucket="gt_10"} 3
telemt_me_writer_removed_unexpected_total 22
telemt_me_writer_restored_same_endpoint_total 31
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 2494
telemt_user_connections_total{user="hello"} 5194
telemt_user_connections_current{user="hello"} 1799
telemt_user_octets_from_client{user="hello"} 15977996 (15.24 MB)
telemt_user_octets_to_client{user="hello"} 501929976 (478.68 MB)
telemt_user_unique_ips_current{user="hello"} 474
telemt_user_unique_ips_recent_window{user="hello"} 532
```