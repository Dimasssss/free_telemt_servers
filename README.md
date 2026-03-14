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

# Server Metrics 2026-03-14 22:35:53 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 1285.9 (0h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3140
telemt_connections_bad_total 109
telemt_handshake_timeouts_total 79
telemt_upstream_connect_attempt_total 324
telemt_upstream_connect_success_total 321
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 324
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 185
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 135
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 215
telemt_me_reconnect_success_total 212
telemt_me_reader_eof_total 177
telemt_me_idle_close_by_peer_total 177
telemt_me_route_drop_no_conn_total 529
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2843
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 30
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 20
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 11
telemt_desync_frames_bucket_total{bucket="gt_10"} 15
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 197
telemt_me_writer_restored_same_endpoint_total 181
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_user_connections_total{user="hello"} 2843
telemt_user_connections_current{user="hello"} 234
telemt_user_octets_from_client{user="hello"} 32396260 (30.90 MB)
telemt_user_octets_to_client{user="hello"} 522104808 (497.92 MB)
telemt_user_unique_ips_current{user="hello"} 68
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 1292.3 (0h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 768
telemt_connections_bad_total 3
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 412
telemt_upstream_connect_success_total 412
telemt_upstream_connect_attempts_per_request{bucket="1"} 412
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 172
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 240
telemt_me_reconnect_attempts_total 301
telemt_me_reconnect_success_total 301
telemt_me_reader_eof_total 285
telemt_me_idle_close_by_peer_total 285
telemt_me_route_drop_no_conn_total 399
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 727
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 293
telemt_me_writer_restored_same_endpoint_total 285
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_user_connections_total{user="hello"} 727
telemt_user_connections_current{user="hello"} 97
telemt_user_octets_from_client{user="hello"} 5225788 (4.98 MB)
telemt_user_octets_to_client{user="hello"} 39534260 (37.70 MB)
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 2
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 1285.2 (0h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1472
telemt_connections_bad_total 13
telemt_handshake_timeouts_total 34
telemt_upstream_connect_attempt_total 343
telemt_upstream_connect_success_total 343
telemt_upstream_connect_attempts_per_request{bucket="1"} 343
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 155
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 188
telemt_me_reconnect_attempts_total 233
telemt_me_reconnect_success_total 230
telemt_me_reader_eof_total 220
telemt_me_idle_close_by_peer_total 220
telemt_me_route_drop_no_conn_total 347
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1378
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 220
telemt_me_writer_restored_same_endpoint_total 226
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 14
telemt_user_connections_total{user="hello"} 1378
telemt_user_connections_current{user="hello"} 87
telemt_user_octets_from_client{user="hello"} 92383744 (88.10 MB)
telemt_user_octets_to_client{user="hello"} 961709728 (917.16 MB)
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 1284.8 (0h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1267
telemt_connections_bad_total 2
telemt_upstream_connect_attempt_total 315
telemt_upstream_connect_success_total 315
telemt_upstream_connect_attempts_per_request{bucket="1"} 315
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 127
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 187
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 209
telemt_me_reconnect_success_total 207
telemt_me_reader_eof_total 188
telemt_me_idle_close_by_peer_total 188
telemt_me_route_drop_no_conn_total 436
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1231
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 202
telemt_me_writer_restored_same_endpoint_total 196
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_user_connections_total{user="hello"} 1231
telemt_user_connections_current{user="hello"} 120
telemt_user_octets_from_client{user="hello"} 21325768 (20.34 MB)
telemt_user_octets_to_client{user="hello"} 2642503144 (2.46 GB)
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 1284.9 (0h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1733
telemt_connections_bad_total 226
telemt_handshake_timeouts_total 1
telemt_upstream_connect_attempt_total 360
telemt_upstream_connect_success_total 352
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 360
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 228
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 123
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 248
telemt_me_reconnect_success_total 247
telemt_me_reader_eof_total 213
telemt_me_idle_close_by_peer_total 213
telemt_me_route_drop_no_conn_total 278
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1471
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_writer_removed_unexpected_total 229
telemt_me_writer_restored_same_endpoint_total 235
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 29
telemt_user_connections_total{user="hello"} 1471
telemt_user_connections_current{user="hello"} 77
telemt_user_octets_from_client{user="hello"} 10997668 (10.49 MB)
telemt_user_octets_to_client{user="hello"} 1127174824 (1.05 GB)
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 1283.8 (0h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4295
telemt_connections_bad_total 44
telemt_handshake_timeouts_total 14
telemt_upstream_connect_attempt_total 328
telemt_upstream_connect_success_total 327
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 328
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 171
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 156
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 219
telemt_me_reconnect_success_total 218
telemt_me_reader_eof_total 182
telemt_me_idle_close_by_peer_total 182
telemt_me_route_drop_no_conn_total 1807
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4106
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
telemt_me_writer_removed_unexpected_total 197
telemt_me_writer_restored_same_endpoint_total 191
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_user_connections_total{user="hello"} 4106
telemt_user_connections_current{user="hello"} 317
telemt_user_octets_from_client{user="hello"} 55675176 (53.10 MB)
telemt_user_octets_to_client{user="hello"} 4057056232 (3.78 GB)
telemt_user_unique_ips_current{user="hello"} 131
telemt_user_unique_ips_recent_window{user="hello"} 30
```