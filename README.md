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

# Server Metrics 2026-03-16 14:02:11 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 1458.8 (0h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19436
telemt_connections_bad_total 2
telemt_handshake_timeouts_total 434
telemt_upstream_connect_attempt_total 233
telemt_upstream_connect_success_total 231
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 233
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 133
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 98
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 122
telemt_me_reconnect_success_total 120
telemt_me_reader_eof_total 88
telemt_me_idle_close_by_peer_total 88
telemt_me_route_drop_no_conn_total 5327
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 18054
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3
telemt_desync_full_logged_total 3
telemt_desync_frames_bucket_total{bucket="1_2"} 1
telemt_desync_frames_bucket_total{bucket="3_10"} 1
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 110
telemt_me_writer_restored_same_endpoint_total 118
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 36
telemt_user_connections_total{user="hello"} 18003
telemt_user_connections_current{user="hello"} 748
telemt_user_octets_from_client{user="hello"} 436921536 (416.68 MB)
telemt_user_octets_to_client{user="hello"} 12358519920 (11.51 GB)
telemt_user_unique_ips_current{user="hello"} 210
telemt_user_unique_ips_recent_window{user="hello"} 90
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 961.7 (0h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11141
telemt_connections_bad_total 776
telemt_handshake_timeouts_total 55
telemt_upstream_connect_attempt_total 9896
telemt_upstream_connect_success_total 9875
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 9889
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8076
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 615
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1184
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 9873
telemt_user_connections_current{user="hello"} 633
telemt_user_octets_from_client{user="hello"} 58503800 (55.79 MB)
telemt_user_octets_to_client{user="hello"} 1224101177 (1.14 GB)
telemt_user_msgs_from_client{user="hello"} 109267
telemt_user_msgs_to_client{user="hello"} 427891
telemt_user_unique_ips_current{user="hello"} 118
telemt_user_unique_ips_recent_window{user="hello"} 72
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 1571.8 (0h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8218
telemt_connections_bad_total 2
telemt_handshake_timeouts_total 56
telemt_upstream_connect_attempt_total 1922
telemt_upstream_connect_success_total 1892
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 1922
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1202
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 671
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_reconnect_attempts_total 27841
telemt_me_reconnect_success_total 812
telemt_me_reader_eof_total 736
telemt_me_idle_close_by_peer_total 736
telemt_me_route_drop_no_conn_total 1802
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6704
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_writer_removed_unexpected_total 757
telemt_me_refill_failed_total 844
telemt_me_writer_restored_same_endpoint_total 768
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 1272
telemt_user_connections_total{user="hello"} 7660
telemt_user_connections_current{user="hello"} 282
telemt_user_octets_from_client{user="hello"} 72945038 (69.57 MB)
telemt_user_octets_to_client{user="hello"} 1237102754 (1.15 GB)
telemt_user_msgs_from_client{user="hello"} 4789
telemt_user_msgs_to_client{user="hello"} 14129
telemt_user_unique_ips_current{user="hello"} 99
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 1707.7 (0h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15139
telemt_connections_bad_total 6
telemt_handshake_timeouts_total 173
telemt_upstream_connect_attempt_total 367
telemt_upstream_connect_success_total 366
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 367
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 235
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 128
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 250
telemt_me_reconnect_success_total 243
telemt_me_reader_eof_total 217
telemt_me_idle_close_by_peer_total 217
telemt_me_route_drop_no_conn_total 4362
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 14390
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 9
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 97
telemt_desync_full_logged_total 27
telemt_desync_suppressed_total 70
telemt_desync_frames_bucket_total{bucket="1_2"} 16
telemt_desync_frames_bucket_total{bucket="3_10"} 38
telemt_desync_frames_bucket_total{bucket="gt_10"} 43
telemt_me_writer_removed_unexpected_total 232
telemt_me_writer_restored_same_endpoint_total 239
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 18
telemt_user_connections_total{user="hello"} 14374
telemt_user_connections_current{user="hello"} 451
telemt_user_octets_from_client{user="hello"} 264619368 (252.36 MB)
telemt_user_octets_to_client{user="hello"} 2653016076 (2.47 GB)
telemt_user_unique_ips_current{user="hello"} 137
telemt_user_unique_ips_recent_window{user="hello"} 79
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 1697.0 (0h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10458
telemt_connections_bad_total 3277
telemt_handshake_timeouts_total 71
telemt_upstream_connect_attempt_total 364
telemt_upstream_connect_success_total 364
telemt_upstream_connect_attempts_per_request{bucket="1"} 364
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 155
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 209
telemt_me_reconnect_attempts_total 245
telemt_me_reconnect_success_total 239
telemt_me_reader_eof_total 218
telemt_me_idle_close_by_peer_total 218
telemt_me_route_drop_no_conn_total 1602
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6820
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
telemt_me_writer_removed_unexpected_total 237
telemt_me_writer_restored_same_endpoint_total 238
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 14
telemt_user_connections_total{user="hello"} 6808
telemt_user_connections_current{user="hello"} 200
telemt_user_octets_from_client{user="hello"} 185705996 (177.10 MB)
telemt_user_octets_to_client{user="hello"} 1333736864 (1.24 GB)
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 1275.7 (0h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16477
telemt_connections_bad_total 313
telemt_handshake_timeouts_total 68
telemt_upstream_connect_attempt_total 253
telemt_upstream_connect_success_total 253
telemt_upstream_connect_attempts_per_request{bucket="1"} 253
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 166
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 87
telemt_me_reconnect_attempts_total 138
telemt_me_reconnect_success_total 136
telemt_me_reader_eof_total 106
telemt_me_idle_close_by_peer_total 106
telemt_me_route_drop_no_conn_total 7616
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 15656
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
telemt_me_writer_removed_unexpected_total 128
telemt_me_writer_restored_same_endpoint_total 132
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 208
telemt_user_connections_total{user="hello"} 15532
telemt_user_connections_current{user="hello"} 688
telemt_user_octets_from_client{user="hello"} 350247676 (334.02 MB)
telemt_user_octets_to_client{user="hello"} 2819985704 (2.63 GB)
telemt_user_unique_ips_current{user="hello"} 270
telemt_user_unique_ips_recent_window{user="hello"} 112
```