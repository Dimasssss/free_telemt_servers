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

# Server Metrics 2026-03-14 22:40:58 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 1590.9 (0h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3946
telemt_connections_bad_total 199
telemt_handshake_timeouts_total 86
telemt_upstream_connect_attempt_total 387
telemt_upstream_connect_success_total 384
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 387
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 213
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 170
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 278
telemt_me_reconnect_success_total 275
telemt_me_reader_eof_total 240
telemt_me_idle_close_by_peer_total 240
telemt_me_route_drop_no_conn_total 801
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3506
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 31
telemt_desync_full_logged_total 11
telemt_desync_suppressed_total 20
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 15
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 260
telemt_me_writer_restored_same_endpoint_total 244
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_user_connections_total{user="hello"} 3506
telemt_user_connections_current{user="hello"} 223
telemt_user_octets_from_client{user="hello"} 36594044 (34.90 MB)
telemt_user_octets_to_client{user="hello"} 690991912 (658.98 MB)
telemt_user_unique_ips_current{user="hello"} 64
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 1597.5 (0h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 929
telemt_connections_bad_total 5
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 487
telemt_upstream_connect_success_total 487
telemt_upstream_connect_attempts_per_request{bucket="1"} 487
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 194
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 293
telemt_me_reconnect_attempts_total 376
telemt_me_reconnect_success_total 376
telemt_me_reader_eof_total 360
telemt_me_idle_close_by_peer_total 360
telemt_me_route_drop_no_conn_total 457
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 879
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 368
telemt_me_writer_restored_same_endpoint_total 360
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_user_connections_total{user="hello"} 879
telemt_user_connections_current{user="hello"} 97
telemt_user_octets_from_client{user="hello"} 6209860 (5.92 MB)
telemt_user_octets_to_client{user="hello"} 54992912 (52.45 MB)
telemt_user_unique_ips_current{user="hello"} 23
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 1590.0 (0h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1682
telemt_connections_bad_total 15
telemt_handshake_timeouts_total 34
telemt_upstream_connect_attempt_total 401
telemt_upstream_connect_success_total 401
telemt_upstream_connect_attempts_per_request{bucket="1"} 401
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 176
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 224
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 291
telemt_me_reconnect_success_total 288
telemt_me_reader_eof_total 278
telemt_me_idle_close_by_peer_total 278
telemt_me_route_drop_no_conn_total 440
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1577
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 278
telemt_me_writer_restored_same_endpoint_total 284
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 14
telemt_user_connections_total{user="hello"} 1577
telemt_user_connections_current{user="hello"} 66
telemt_user_octets_from_client{user="hello"} 93436384 (89.11 MB)
telemt_user_octets_to_client{user="hello"} 1098900268 (1.02 GB)
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 1589.8 (0h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1601
telemt_connections_bad_total 5
telemt_upstream_connect_attempt_total 373
telemt_upstream_connect_success_total 373
telemt_upstream_connect_attempts_per_request{bucket="1"} 373
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 151
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 221
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 267
telemt_me_reconnect_success_total 265
telemt_me_reader_eof_total 246
telemt_me_idle_close_by_peer_total 246
telemt_me_route_drop_no_conn_total 560
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1549
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 260
telemt_me_writer_restored_same_endpoint_total 254
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_user_connections_total{user="hello"} 1549
telemt_user_connections_current{user="hello"} 116
telemt_user_octets_from_client{user="hello"} 33059004 (31.53 MB)
telemt_user_octets_to_client{user="hello"} 2844378772 (2.65 GB)
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 1589.8 (0h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2022
telemt_connections_bad_total 281
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 451
telemt_upstream_connect_success_total 443
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 451
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 273
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 169
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 339
telemt_me_reconnect_success_total 338
telemt_me_reader_eof_total 303
telemt_me_idle_close_by_peer_total 303
telemt_me_route_drop_no_conn_total 388
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1697
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_writer_removed_unexpected_total 322
telemt_me_writer_restored_same_endpoint_total 326
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 29
telemt_user_connections_total{user="hello"} 1697
telemt_user_connections_current{user="hello"} 62
telemt_user_octets_from_client{user="hello"} 14756300 (14.07 MB)
telemt_user_octets_to_client{user="hello"} 1480522764 (1.38 GB)
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 1589.0 (0h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5134
telemt_connections_bad_total 51
telemt_handshake_timeouts_total 14
telemt_upstream_connect_attempt_total 382
telemt_upstream_connect_success_total 381
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 382
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 194
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 187
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 273
telemt_me_reconnect_success_total 273
telemt_me_reader_eof_total 236
telemt_me_idle_close_by_peer_total 236
telemt_me_route_drop_no_conn_total 2269
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4896
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 13
telemt_desync_full_logged_total 3
telemt_desync_suppressed_total 10
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 4
telemt_desync_frames_bucket_total{bucket="gt_10"} 4
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 251
telemt_me_writer_restored_same_endpoint_total 246
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_user_connections_total{user="hello"} 4896
telemt_user_connections_current{user="hello"} 285
telemt_user_octets_from_client{user="hello"} 68857812 (65.67 MB)
telemt_user_octets_to_client{user="hello"} 5047302732 (4.70 GB)
telemt_user_unique_ips_current{user="hello"} 120
telemt_user_unique_ips_recent_window{user="hello"} 30
```