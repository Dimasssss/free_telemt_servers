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

# Server Metrics 2026-03-12 10:30:15 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 10612.3 (2h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 54890
telemt_connections_bad_total 48
telemt_handshake_timeouts_total 2395
telemt_upstream_connect_attempt_total 2559
telemt_upstream_connect_success_total 2548
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 2559
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1147
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1399
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 62
telemt_me_reconnect_attempts_total 2004
telemt_me_reconnect_success_total 1991
telemt_me_reader_eof_total 2061
telemt_me_idle_close_by_peer_total 2061
telemt_me_route_drop_no_conn_total 15235
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 49655
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 192
telemt_desync_full_logged_total 75
telemt_desync_suppressed_total 117
telemt_desync_frames_bucket_total{bucket="1_2"} 39
telemt_desync_frames_bucket_total{bucket="3_10"} 72
telemt_desync_frames_bucket_total{bucket="gt_10"} 81
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 1999
telemt_me_writer_restored_same_endpoint_total 1975
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 8
telemt_user_connections_total{user="hello"} 49628
telemt_user_connections_current{user="hello"} 312
telemt_user_octets_from_client{user="hello"} 724093768 (690.55 MB)
telemt_user_octets_to_client{user="hello"} 14320109648 (13.34 GB)
telemt_user_unique_ips_current{user="hello"} 96
telemt_user_unique_ips_recent_window{user="hello"} 51
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 10505.5 (2h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 22580
telemt_connections_bad_total 129
telemt_handshake_timeouts_total 181
telemt_upstream_connect_attempt_total 3906
telemt_upstream_connect_success_total 3835
telemt_upstream_connect_fail_total 71
telemt_upstream_connect_attempts_per_request{bucket="1"} 3906
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1417
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2416
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 71
telemt_me_keepalive_timeout_total 79
telemt_me_reconnect_attempts_total 6973
telemt_me_reconnect_success_total 3281
telemt_me_reader_eof_total 3438
telemt_me_idle_close_by_peer_total 3438
telemt_me_route_drop_no_conn_total 8439
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 21517
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 30
telemt_desync_full_logged_total 8
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 11
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 3408
telemt_me_refill_failed_total 115
telemt_me_writer_restored_same_endpoint_total 3266
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 127
telemt_user_connections_total{user="hello"} 21515
telemt_user_connections_current{user="hello"} 141
telemt_user_octets_from_client{user="hello"} 235141264 (224.25 MB)
telemt_user_octets_to_client{user="hello"} 4396201244 (4.09 GB)
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 10469.3 (2h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 31778
telemt_connections_bad_total 87
telemt_handshake_timeouts_total 245
telemt_upstream_connect_attempt_total 2872
telemt_upstream_connect_success_total 2872
telemt_upstream_connect_attempts_per_request{bucket="1"} 2872
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1420
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1448
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 51
telemt_me_reconnect_attempts_total 2325
telemt_me_reconnect_success_total 2310
telemt_me_reader_eof_total 2411
telemt_me_idle_close_by_peer_total 2411
telemt_me_route_drop_no_conn_total 10313
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 29604
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 4
telemt_desync_frames_bucket_total{bucket="3_10"} 6
telemt_desync_frames_bucket_total{bucket="gt_10"} 4
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 2311
telemt_me_writer_restored_same_endpoint_total 2290
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 29597
telemt_user_connections_current{user="hello"} 166
telemt_user_octets_from_client{user="hello"} 393328492 (375.11 MB)
telemt_user_octets_to_client{user="hello"} 27545010260 (25.65 GB)
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 10445.0 (2h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 38063
telemt_connections_bad_total 1031
telemt_handshake_timeouts_total 197
telemt_upstream_connect_attempt_total 2967
telemt_upstream_connect_success_total 2896
telemt_upstream_connect_fail_total 71
telemt_upstream_connect_attempts_per_request{bucket="1"} 2967
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1244
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1643
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 71
telemt_me_keepalive_timeout_total 135
telemt_me_reconnect_attempts_total 2372
telemt_me_reconnect_success_total 2336
telemt_me_reader_eof_total 2441
telemt_me_idle_close_by_peer_total 2441
telemt_me_route_drop_no_conn_total 10885
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 34231
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 152
telemt_desync_full_logged_total 51
telemt_desync_suppressed_total 101
telemt_desync_frames_bucket_total{bucket="1_2"} 57
telemt_desync_frames_bucket_total{bucket="3_10"} 53
telemt_desync_frames_bucket_total{bucket="gt_10"} 42
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 2372
telemt_me_writer_restored_same_endpoint_total 2328
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 121
telemt_me_writer_removed_unexpected_minus_restored_total 36
telemt_user_connections_total{user="hello"} 34230
telemt_user_connections_current{user="hello"} 263
telemt_user_octets_from_client{user="hello"} 867407260 (827.22 MB)
telemt_user_octets_to_client{user="hello"} 18307900312 (17.05 GB)
telemt_user_unique_ips_current{user="hello"} 77
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 10414.2 (2h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20438
telemt_connections_bad_total 2015
telemt_handshake_timeouts_total 323
telemt_upstream_connect_attempt_total 3305
telemt_upstream_connect_success_total 3187
telemt_upstream_connect_fail_total 118
telemt_upstream_connect_attempts_per_request{bucket="1"} 3305
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1160
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2020
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 118
telemt_me_keepalive_timeout_total 70
telemt_me_reconnect_attempts_total 10164
telemt_me_reconnect_success_total 2628
telemt_me_reader_eof_total 2851
telemt_me_idle_close_by_peer_total 2851
telemt_me_seq_mismatch_total 5
telemt_me_route_drop_no_conn_total 5844
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 17544
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 294
telemt_desync_full_logged_total 81
telemt_desync_suppressed_total 213
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 252
telemt_desync_frames_bucket_total{bucket="gt_10"} 35
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 2873
telemt_me_refill_failed_total 235
telemt_me_writer_restored_same_endpoint_total 2612
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 245
telemt_user_connections_total{user="hello"} 17541
telemt_user_connections_current{user="hello"} 82
telemt_user_octets_from_client{user="hello"} 82709348 (78.88 MB)
telemt_user_octets_to_client{user="hello"} 4465480364 (4.16 GB)
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 10401.1 (2h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 51692
telemt_connections_bad_total 560
telemt_handshake_timeouts_total 671
telemt_upstream_connect_attempt_total 1972
telemt_upstream_connect_success_total 1961
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 1972
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 957
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1002
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 60
telemt_me_reconnect_attempts_total 1424
telemt_me_reconnect_success_total 1411
telemt_me_reader_eof_total 1483
telemt_me_idle_close_by_peer_total 1483
telemt_me_route_drop_no_conn_total 22705
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 48560
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 116
telemt_desync_full_logged_total 38
telemt_desync_suppressed_total 78
telemt_desync_frames_bucket_total{bucket="1_2"} 35
telemt_desync_frames_bucket_total{bucket="3_10"} 45
telemt_desync_frames_bucket_total{bucket="gt_10"} 36
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 1430
telemt_me_writer_restored_same_endpoint_total 1404
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 48524
telemt_user_connections_current{user="hello"} 379
telemt_user_octets_from_client{user="hello"} 1812400660 (1.69 GB)
telemt_user_octets_to_client{user="hello"} 28335864636 (26.39 GB)
telemt_user_unique_ips_current{user="hello"} 114
telemt_user_unique_ips_recent_window{user="hello"} 50
```