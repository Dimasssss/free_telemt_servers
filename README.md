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

# Server Metrics 2026-03-16 19:18:48 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 2007.3 (0h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15578
telemt_connections_bad_total 153
telemt_handshake_timeouts_total 524
telemt_upstream_connect_attempt_total 382
telemt_upstream_connect_success_total 376
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 382
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 183
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 193
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_reconnect_attempts_total 222
telemt_me_reconnect_success_total 221
telemt_me_reader_eof_total 196
telemt_me_idle_close_by_peer_total 196
telemt_me_route_drop_no_conn_total 4819
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 14214
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 90
telemt_desync_full_logged_total 19
telemt_desync_suppressed_total 71
telemt_desync_frames_bucket_total{bucket="1_2"} 43
telemt_desync_frames_bucket_total{bucket="3_10"} 24
telemt_desync_frames_bucket_total{bucket="gt_10"} 23
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 212
telemt_me_writer_restored_same_endpoint_total 200
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 46
telemt_user_connections_total{user="hello"} 14209
telemt_user_connections_current{user="hello"} 572
telemt_user_octets_from_client{user="hello"} 266259880 (253.93 MB)
telemt_user_octets_to_client{user="hello"} 12328643548 (11.48 GB)
telemt_user_unique_ips_current{user="hello"} 201
telemt_user_unique_ips_recent_window{user="hello"} 67
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 2258.6 (0h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14563
telemt_connections_bad_total 11
telemt_handshake_timeouts_total 471
telemt_upstream_connect_attempt_total 418
telemt_upstream_connect_success_total 411
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 418
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 192
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 190
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_reconnect_attempts_total 258
telemt_me_reconnect_success_total 257
telemt_me_reader_eof_total 235
telemt_me_idle_close_by_peer_total 235
telemt_me_route_drop_no_conn_total 6288
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13591
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 61
telemt_desync_full_logged_total 18
telemt_desync_suppressed_total 43
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 25
telemt_desync_frames_bucket_total{bucket="gt_10"} 21
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 258
telemt_me_writer_restored_same_endpoint_total 241
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 13590
telemt_user_connections_current{user="hello"} 379
telemt_user_octets_from_client{user="hello"} 140891332 (134.36 MB)
telemt_user_octets_to_client{user="hello"} 4674962516 (4.35 GB)
telemt_user_unique_ips_current{user="hello"} 117
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 2034.8 (0h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7294
telemt_connections_bad_total 45
telemt_handshake_timeouts_total 76
telemt_upstream_connect_attempt_total 400
telemt_upstream_connect_success_total 398
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 400
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 189
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 207
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 244
telemt_me_reconnect_success_total 243
telemt_me_reader_eof_total 228
telemt_me_idle_close_by_peer_total 228
telemt_me_route_drop_no_conn_total 2195
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6995
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3
telemt_desync_full_logged_total 1
telemt_desync_suppressed_total 2
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 241
telemt_me_writer_restored_same_endpoint_total 232
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_user_connections_total{user="hello"} 6994
telemt_user_connections_current{user="hello"} 177
telemt_user_octets_from_client{user="hello"} 164615788 (156.99 MB)
telemt_user_octets_to_client{user="hello"} 2680738064 (2.50 GB)
telemt_user_unique_ips_current{user="hello"} 73
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 2094.0 (0h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15592
telemt_connections_bad_total 25
telemt_handshake_timeouts_total 114
telemt_upstream_connect_attempt_total 381
telemt_upstream_connect_success_total 374
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 381
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 197
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 174
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_reconnect_attempts_total 217
telemt_me_reconnect_success_total 215
telemt_me_reader_eof_total 197
telemt_me_idle_close_by_peer_total 197
telemt_me_route_drop_no_conn_total 4551
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 14809
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 44
telemt_desync_full_logged_total 12
telemt_desync_suppressed_total 32
telemt_desync_frames_bucket_total{bucket="1_2"} 11
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 21
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 214
telemt_me_writer_restored_same_endpoint_total 208
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 270
telemt_user_connections_total{user="hello"} 14805
telemt_user_connections_current{user="hello"} 346
telemt_user_octets_from_client{user="hello"} 230373624 (219.70 MB)
telemt_user_octets_to_client{user="hello"} 5388620312 (5.02 GB)
telemt_user_unique_ips_current{user="hello"} 116
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 2065.9 (0h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8472
telemt_connections_bad_total 2368
telemt_handshake_timeouts_total 31
telemt_upstream_connect_attempt_total 517
telemt_upstream_connect_success_total 510
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 517
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 274
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 218
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_reconnect_attempts_total 358
telemt_me_reconnect_success_total 357
telemt_me_reader_eof_total 322
telemt_me_idle_close_by_peer_total 322
telemt_me_route_drop_no_conn_total 2321
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5794
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9
telemt_desync_full_logged_total 3
telemt_desync_suppressed_total 6
telemt_desync_frames_bucket_total{bucket="3_10"} 4
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 339
telemt_me_writer_restored_same_endpoint_total 349
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_user_connections_total{user="hello"} 5794
telemt_user_connections_current{user="hello"} 234
telemt_user_octets_from_client{user="hello"} 39886952 (38.04 MB)
telemt_user_octets_to_client{user="hello"} 1243185504 (1.16 GB)
telemt_user_unique_ips_current{user="hello"} 76
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 2227.7 (0h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 23077
telemt_connections_bad_total 36
telemt_handshake_timeouts_total 80
telemt_upstream_connect_attempt_total 364
telemt_upstream_connect_success_total 361
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 364
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 178
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 183
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 209
telemt_me_reconnect_success_total 209
telemt_me_reader_eof_total 202
telemt_me_idle_close_by_peer_total 202
telemt_me_route_drop_no_conn_total 9175
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 22179
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 19
telemt_desync_full_logged_total 5
telemt_desync_suppressed_total 14
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 7
telemt_desync_frames_bucket_total{bucket="gt_10"} 8
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 215
telemt_me_writer_restored_same_endpoint_total 199
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 22175
telemt_user_connections_current{user="hello"} 679
telemt_user_octets_from_client{user="hello"} 258276936 (246.31 MB)
telemt_user_octets_to_client{user="hello"} 12189798752 (11.35 GB)
telemt_user_unique_ips_current{user="hello"} 230
telemt_user_unique_ips_recent_window{user="hello"} 83
```