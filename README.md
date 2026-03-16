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

# Server Metrics 2026-03-16 13:46:51 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 538.1 (0h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8519
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 69
telemt_upstream_connect_attempt_total 113
telemt_upstream_connect_success_total 112
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 113
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 80
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 46
telemt_me_reconnect_success_total 46
telemt_me_reader_eof_total 12
telemt_me_idle_close_by_peer_total 12
telemt_me_route_drop_no_conn_total 1812
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7898
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_writer_removed_unexpected_total 34
telemt_me_writer_restored_same_endpoint_total 44
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 36
telemt_user_connections_total{user="hello"} 7849
telemt_user_connections_current{user="hello"} 737
telemt_user_octets_from_client{user="hello"} 278714400 (265.80 MB)
telemt_user_octets_to_client{user="hello"} 3746248408 (3.49 GB)
telemt_user_unique_ips_current{user="hello"} 213
telemt_user_unique_ips_recent_window{user="hello"} 90
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 41.2 (0h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1077
telemt_connections_bad_total 53
telemt_handshake_timeouts_total 5
telemt_upstream_connect_attempt_total 1005
telemt_upstream_connect_success_total 1004
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 1005
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 799
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 96
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1002
telemt_user_connections_current{user="hello"} 435
telemt_user_octets_from_client{user="hello"} 2515315 (2.40 MB)
telemt_user_octets_to_client{user="hello"} 68949215 (65.76 MB)
telemt_user_msgs_from_client{user="hello"} 5829
telemt_user_msgs_to_client{user="hello"} 24599
telemt_user_unique_ips_current{user="hello"} 100
telemt_user_unique_ips_recent_window{user="hello"} 64
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 651.5 (0h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3616
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 44
telemt_upstream_connect_attempt_total 935
telemt_upstream_connect_success_total 917
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 935
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 523
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 394
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_reconnect_attempts_total 662
telemt_me_reconnect_success_total 485
telemt_me_reader_eof_total 369
telemt_me_idle_close_by_peer_total 369
telemt_me_route_drop_no_conn_total 796
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2916
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 20
telemt_me_endpoint_quarantine_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_writer_removed_unexpected_total 388
telemt_me_refill_failed_total 5
telemt_me_writer_restored_same_endpoint_total 441
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 856
telemt_user_connections_total{user="hello"} 3276
telemt_user_connections_current{user="hello"} 267
telemt_user_octets_from_client{user="hello"} 53279435 (50.81 MB)
telemt_user_octets_to_client{user="hello"} 488279449 (465.66 MB)
telemt_user_msgs_from_client{user="hello"} 1400
telemt_user_msgs_to_client{user="hello"} 3646
telemt_user_unique_ips_current{user="hello"} 91
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 787.3 (0h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8247
telemt_connections_bad_total 5
telemt_handshake_timeouts_total 140
telemt_upstream_connect_attempt_total 195
telemt_upstream_connect_success_total 194
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 195
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 134
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 58
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 124
telemt_me_reconnect_success_total 120
telemt_me_reader_eof_total 87
telemt_me_idle_close_by_peer_total 87
telemt_me_route_drop_no_conn_total 2084
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7770
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 9
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 37
telemt_desync_full_logged_total 11
telemt_desync_suppressed_total 26
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 16
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_me_writer_removed_unexpected_total 102
telemt_me_writer_restored_same_endpoint_total 116
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 18
telemt_user_connections_total{user="hello"} 7755
telemt_user_connections_current{user="hello"} 473
telemt_user_octets_from_client{user="hello"} 224564740 (214.16 MB)
telemt_user_octets_to_client{user="hello"} 1238150024 (1.15 GB)
telemt_user_unique_ips_current{user="hello"} 143
telemt_user_unique_ips_recent_window{user="hello"} 67
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 776.7 (0h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4854
telemt_connections_bad_total 1471
telemt_handshake_timeouts_total 54
telemt_upstream_connect_attempt_total 157
telemt_upstream_connect_success_total 157
telemt_upstream_connect_attempts_per_request{bucket="1"} 157
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 67
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 90
telemt_me_reconnect_attempts_total 84
telemt_me_reconnect_success_total 82
telemt_me_reader_eof_total 56
telemt_me_idle_close_by_peer_total 56
telemt_me_route_drop_no_conn_total 752
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3165
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 2
telemt_desync_full_logged_total 2
telemt_desync_frames_bucket_total{bucket="1_2"} 1
telemt_desync_frames_bucket_total{bucket="3_10"} 1
telemt_me_writer_removed_unexpected_total 74
telemt_me_writer_restored_same_endpoint_total 81
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 14
telemt_user_connections_total{user="hello"} 3153
telemt_user_connections_current{user="hello"} 208
telemt_user_octets_from_client{user="hello"} 132199716 (126.08 MB)
telemt_user_octets_to_client{user="hello"} 439044960 (418.71 MB)
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 354.7 (0h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5532
telemt_connections_bad_total 64
telemt_handshake_timeouts_total 42
telemt_upstream_connect_attempt_total 125
telemt_upstream_connect_success_total 125
telemt_upstream_connect_attempts_per_request{bucket="1"} 125
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 86
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39
telemt_me_reconnect_attempts_total 59
telemt_me_reconnect_success_total 58
telemt_me_reader_eof_total 22
telemt_me_idle_close_by_peer_total 22
telemt_me_route_drop_no_conn_total 3570
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5339
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_writer_removed_unexpected_total 44
telemt_me_writer_restored_same_endpoint_total 54
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 208
telemt_user_connections_total{user="hello"} 5218
telemt_user_connections_current{user="hello"} 694
telemt_user_octets_from_client{user="hello"} 211431708 (201.64 MB)
telemt_user_octets_to_client{user="hello"} 844067564 (804.97 MB)
telemt_user_unique_ips_current{user="hello"} 268
telemt_user_unique_ips_recent_window{user="hello"} 96
```