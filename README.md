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

# Server Metrics 2026-03-16 13:57:05 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 1151.0 (0h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15369
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 308
telemt_upstream_connect_attempt_total 197
telemt_upstream_connect_success_total 195
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 197
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 119
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 76
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 86
telemt_me_reconnect_success_total 84
telemt_me_reader_eof_total 52
telemt_me_idle_close_by_peer_total 52
telemt_me_route_drop_no_conn_total 3779
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 14245
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 74
telemt_me_writer_restored_same_endpoint_total 82
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 36
telemt_user_connections_total{user="hello"} 14195
telemt_user_connections_current{user="hello"} 709
telemt_user_octets_from_client{user="hello"} 412250344 (393.15 MB)
telemt_user_octets_to_client{user="hello"} 9563628032 (8.91 GB)
telemt_user_unique_ips_current{user="hello"} 215
telemt_user_unique_ips_recent_window{user="hello"} 68
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 656.2 (0h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7597
telemt_connections_bad_total 603
telemt_handshake_timeouts_total 43
telemt_upstream_connect_attempt_total 6739
telemt_upstream_connect_success_total 6727
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 6737
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5495
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 438
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 794
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 6725
telemt_user_connections_current{user="hello"} 618
telemt_user_octets_from_client{user="hello"} 43516643 (41.50 MB)
telemt_user_octets_to_client{user="hello"} 863032172 (823.05 MB)
telemt_user_msgs_from_client{user="hello"} 76797
telemt_user_msgs_to_client{user="hello"} 299952
telemt_user_unique_ips_current{user="hello"} 112
telemt_user_unique_ips_recent_window{user="hello"} 73
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 1264.5 (0h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6513
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 56
telemt_upstream_connect_attempt_total 1641
telemt_upstream_connect_success_total 1611
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 1641
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 987
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 605
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_reconnect_attempts_total 9733
telemt_me_reconnect_success_total 755
telemt_me_reader_eof_total 674
telemt_me_idle_close_by_peer_total 674
telemt_me_route_drop_no_conn_total 1428
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5304
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_writer_removed_unexpected_total 695
telemt_me_refill_failed_total 280
telemt_me_writer_restored_same_endpoint_total 711
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 996
telemt_user_connections_total{user="hello"} 6041
telemt_user_connections_current{user="hello"} 256
telemt_user_octets_from_client{user="hello"} 64707687 (61.71 MB)
telemt_user_octets_to_client{user="hello"} 958004092 (913.62 MB)
telemt_user_msgs_from_client{user="hello"} 2552
telemt_user_msgs_to_client{user="hello"} 5015
telemt_user_unique_ips_current{user="hello"} 79
telemt_user_unique_ips_recent_window{user="hello"} 90
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 1400.4 (0h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12976
telemt_connections_bad_total 5
telemt_handshake_timeouts_total 170
telemt_upstream_connect_attempt_total 345
telemt_upstream_connect_success_total 344
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 345
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 222
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 120
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 228
telemt_me_reconnect_success_total 221
telemt_me_reader_eof_total 193
telemt_me_idle_close_by_peer_total 193
telemt_me_route_drop_no_conn_total 3577
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12325
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 9
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 59
telemt_desync_full_logged_total 18
telemt_desync_suppressed_total 41
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 27
telemt_desync_frames_bucket_total{bucket="gt_10"} 30
telemt_me_writer_removed_unexpected_total 208
telemt_me_writer_restored_same_endpoint_total 217
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 18
telemt_user_connections_total{user="hello"} 12309
telemt_user_connections_current{user="hello"} 440
telemt_user_octets_from_client{user="hello"} 250267664 (238.67 MB)
telemt_user_octets_to_client{user="hello"} 2222381088 (2.07 GB)
telemt_user_unique_ips_current{user="hello"} 137
telemt_user_unique_ips_recent_window{user="hello"} 62
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 1389.8 (0h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8616
telemt_connections_bad_total 2682
telemt_handshake_timeouts_total 69
telemt_upstream_connect_attempt_total 321
telemt_upstream_connect_success_total 321
telemt_upstream_connect_attempts_per_request{bucket="1"} 321
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 146
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 175
telemt_me_reconnect_attempts_total 202
telemt_me_reconnect_success_total 197
telemt_me_reader_eof_total 175
telemt_me_idle_close_by_peer_total 175
telemt_me_route_drop_no_conn_total 1327
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5613
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
telemt_me_writer_removed_unexpected_total 194
telemt_me_writer_restored_same_endpoint_total 196
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 14
telemt_user_connections_total{user="hello"} 5601
telemt_user_connections_current{user="hello"} 192
telemt_user_octets_from_client{user="hello"} 142434976 (135.84 MB)
telemt_user_octets_to_client{user="hello"} 857071356 (817.37 MB)
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 968.2 (0h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12789
telemt_connections_bad_total 222
telemt_handshake_timeouts_total 54
telemt_upstream_connect_attempt_total 148
telemt_upstream_connect_success_total 148
telemt_upstream_connect_attempts_per_request{bucket="1"} 148
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 109
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39
telemt_me_reconnect_attempts_total 78
telemt_me_reconnect_success_total 77
telemt_me_reader_eof_total 45
telemt_me_idle_close_by_peer_total 45
telemt_me_route_drop_no_conn_total 6297
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12168
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5
telemt_desync_full_logged_total 2
telemt_desync_suppressed_total 3
telemt_desync_frames_bucket_total{bucket="1_2"} 1
telemt_desync_frames_bucket_total{bucket="3_10"} 4
telemt_me_writer_removed_unexpected_total 67
telemt_me_writer_restored_same_endpoint_total 73
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 208
telemt_user_connections_total{user="hello"} 12044
telemt_user_connections_current{user="hello"} 716
telemt_user_octets_from_client{user="hello"} 313268080 (298.76 MB)
telemt_user_octets_to_client{user="hello"} 1959057148 (1.82 GB)
telemt_user_unique_ips_current{user="hello"} 250
telemt_user_unique_ips_recent_window{user="hello"} 106
```