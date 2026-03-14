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

# Server Metrics 2026-03-14 13:49:53 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.17

telemt_uptime_seconds 2012.7 (0h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10045
telemt_connections_bad_total 1064
telemt_handshake_timeouts_total 59
telemt_upstream_connect_attempt_total 448
telemt_upstream_connect_success_total 448
telemt_upstream_connect_attempts_per_request{bucket="1"} 448
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 214
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 231
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 6
telemt_me_reconnect_attempts_total 289
telemt_me_reconnect_success_total 283
telemt_me_reader_eof_total 265
telemt_me_idle_close_by_peer_total 265
telemt_me_route_drop_no_conn_total 2852
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8705
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 14
telemt_desync_full_logged_total 8
telemt_desync_suppressed_total 6
telemt_desync_frames_bucket_total{bucket="3_10"} 8
telemt_desync_frames_bucket_total{bucket="gt_10"} 6
telemt_me_writer_removed_unexpected_total 288
telemt_me_writer_restored_same_endpoint_total 265
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 72
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 8705
telemt_user_connections_current{user="hello"} 388
telemt_user_octets_from_client{user="hello"} 131523516 (125.43 MB)
telemt_user_octets_to_client{user="hello"} 2767382556 (2.58 GB)
telemt_user_unique_ips_current{user="hello"} 108
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## psb.hosting

```
telemt 3.3.17

telemt_uptime_seconds 2010.8 (0h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4424
telemt_connections_bad_total 30
telemt_handshake_timeouts_total 36
telemt_upstream_connect_attempt_total 422
telemt_upstream_connect_success_total 403
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 422
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 183
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 215
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 263
telemt_me_reconnect_success_total 242
telemt_me_reader_eof_total 238
telemt_me_idle_close_by_peer_total 238
telemt_me_route_drop_no_conn_total 2052
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4234
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_writer_removed_unexpected_total 256
telemt_me_writer_restored_same_endpoint_total 237
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 120
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 4218
telemt_user_connections_current{user="hello"} 190
telemt_user_octets_from_client{user="hello"} 43444432 (41.43 MB)
telemt_user_octets_to_client{user="hello"} 1698459284 (1.58 GB)
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## koara.io

```
telemt 3.3.17

telemt_uptime_seconds 2015.2 (0h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4334
telemt_connections_bad_total 16
telemt_handshake_timeouts_total 69
telemt_upstream_connect_attempt_total 1654
telemt_upstream_connect_success_total 1646
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 1654
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 912
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 733
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 26
telemt_me_reconnect_attempts_total 90751
telemt_me_reconnect_success_total 1166
telemt_me_reader_eof_total 1124
telemt_me_idle_close_by_peer_total 1124
telemt_me_route_drop_no_conn_total 1451
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3707
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_writer_removed_unexpected_total 1140
telemt_me_refill_failed_total 2911
telemt_me_writer_restored_same_endpoint_total 1128
telemt_me_writer_restored_fallback_total 38
telemt_me_async_recovery_trigger_total 1685
telemt_user_connections_total{user="hello"} 4018
telemt_user_connections_current{user="hello"} 117
telemt_user_octets_from_client{user="hello"} 99638453 (95.02 MB)
telemt_user_octets_to_client{user="hello"} 3378596338 (3.15 GB)
telemt_user_msgs_from_client{user="hello"} 3762
telemt_user_msgs_to_client{user="hello"} 18362
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## landvps.ru

```
telemt 3.3.17

telemt_uptime_seconds 2020.1 (0h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6820
telemt_connections_bad_total 3
telemt_handshake_timeouts_total 59
telemt_upstream_connect_attempt_total 410
telemt_upstream_connect_success_total 409
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 410
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 189
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 216
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 19
telemt_me_reconnect_attempts_total 255
telemt_me_reconnect_success_total 251
telemt_me_reader_eof_total 223
telemt_me_idle_close_by_peer_total 223
telemt_me_route_drop_no_conn_total 3932
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6507
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 82
telemt_desync_full_logged_total 20
telemt_desync_suppressed_total 62
telemt_desync_frames_bucket_total{bucket="1_2"} 9
telemt_desync_frames_bucket_total{bucket="3_10"} 38
telemt_desync_frames_bucket_total{bucket="gt_10"} 35
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 242
telemt_me_writer_restored_same_endpoint_total 249
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 60
telemt_user_connections_total{user="hello"} 6392
telemt_user_connections_current{user="hello"} 163
telemt_user_octets_from_client{user="hello"} 92254408 (87.98 MB)
telemt_user_octets_to_client{user="hello"} 1675436112 (1.56 GB)
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## rdp-onedash.ru

```
telemt 3.3.17

telemt_uptime_seconds 2013.3 (0h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4447
telemt_connections_bad_total 506
telemt_handshake_timeouts_total 63
telemt_upstream_connect_attempt_total 523
telemt_upstream_connect_success_total 511
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 522
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 227
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 284
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 353
telemt_me_reconnect_success_total 345
telemt_me_reader_eof_total 321
telemt_me_idle_close_by_peer_total 321
telemt_me_route_drop_no_conn_total 1409
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3601
telemt_me_writer_pick_total{mode="p2c",result="full"} 2
telemt_me_writer_pick_total{mode="p2c",result="closed"} 9
telemt_me_endpoint_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 31
telemt_desync_full_logged_total 3
telemt_desync_suppressed_total 28
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 13
telemt_desync_frames_bucket_total{bucket="gt_10"} 15
telemt_me_writer_removed_unexpected_total 336
telemt_me_writer_restored_same_endpoint_total 341
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 8
telemt_user_connections_total{user="hello"} 3597
telemt_user_connections_current{user="hello"} 76
telemt_user_octets_from_client{user="hello"} 17675456 (16.86 MB)
telemt_user_octets_to_client{user="hello"} 439816424 (419.44 MB)
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## hostvds.com

```
telemt 3.3.17

telemt_uptime_seconds 2012.6 (0h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14402
telemt_connections_bad_total 17
telemt_handshake_timeouts_total 72
telemt_upstream_connect_attempt_total 458
telemt_upstream_connect_success_total 437
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 458
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 251
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 185
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 6
telemt_me_reconnect_attempts_total 291
telemt_me_reconnect_success_total 269
telemt_me_reader_eof_total 239
telemt_me_idle_close_by_peer_total 239
telemt_me_route_drop_no_conn_total 7029
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13484
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_writer_removed_unexpected_total 260
telemt_me_writer_restored_same_endpoint_total 265
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 136
telemt_user_connections_total{user="hello"} 13431
telemt_user_connections_current{user="hello"} 429
telemt_user_octets_from_client{user="hello"} 413567036 (394.41 MB)
telemt_user_octets_to_client{user="hello"} 6685385600 (6.23 GB)
telemt_user_unique_ips_current{user="hello"} 172
telemt_user_unique_ips_recent_window{user="hello"} 68
```