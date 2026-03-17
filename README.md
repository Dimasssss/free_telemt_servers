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

# Server Metrics 2026-03-17 02:09:55 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 26673.2 (7h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 143663
telemt_connections_bad_total 2251
telemt_handshake_timeouts_total 5289
telemt_upstream_connect_attempt_total 5696
telemt_upstream_connect_success_total 5659
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 5696
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2516
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3138
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 4336
telemt_me_reconnect_success_total 4321
telemt_me_reader_eof_total 4584
telemt_me_idle_close_by_peer_total 4584
telemt_me_route_drop_no_conn_total 44252
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 130046
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 715
telemt_desync_full_logged_total 244
telemt_desync_suppressed_total 471
telemt_desync_frames_bucket_total{bucket="1_2"} 156
telemt_desync_frames_bucket_total{bucket="3_10"} 363
telemt_desync_frames_bucket_total{bucket="gt_10"} 196
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 4357
telemt_me_writer_restored_same_endpoint_total 4300
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 36
telemt_user_connections_total{user="hello"} 129979
telemt_user_connections_current{user="hello"} 378
telemt_user_octets_from_client{user="hello"} 1818777460 (1.69 GB)
telemt_user_octets_to_client{user="hello"} 60289313644 (56.15 GB)
telemt_user_unique_ips_current{user="hello"} 139
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 26924.9 (7h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 82297
telemt_connections_bad_total 1277
telemt_handshake_timeouts_total 2918
telemt_upstream_connect_attempt_total 6983
telemt_upstream_connect_success_total 6892
telemt_upstream_connect_fail_total 91
telemt_upstream_connect_attempts_per_request{bucket="1"} 6983
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2881
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3936
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 91
telemt_me_reconnect_attempts_total 5576
telemt_me_reconnect_success_total 5563
telemt_me_reader_eof_total 5840
telemt_me_idle_close_by_peer_total 5840
telemt_me_route_drop_no_conn_total 34299
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 74719
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 176
telemt_desync_full_logged_total 58
telemt_desync_suppressed_total 118
telemt_desync_frames_bucket_total{bucket="1_2"} 42
telemt_desync_frames_bucket_total{bucket="3_10"} 82
telemt_desync_frames_bucket_total{bucket="gt_10"} 52
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 5619
telemt_me_writer_restored_same_endpoint_total 5547
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 56
telemt_user_connections_total{user="hello"} 74662
telemt_user_connections_current{user="hello"} 178
telemt_user_octets_from_client{user="hello"} 1122363812 (1.05 GB)
telemt_user_octets_to_client{user="hello"} 35246132428 (32.83 GB)
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 26700.7 (7h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 52699
telemt_connections_bad_total 584
telemt_handshake_timeouts_total 1847
telemt_upstream_connect_attempt_total 7241
telemt_upstream_connect_success_total 7198
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 7241
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3144
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3994
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 5881
telemt_me_reconnect_success_total 5848
telemt_me_reader_eof_total 6250
telemt_me_idle_close_by_peer_total 6250
telemt_me_route_drop_no_conn_total 16420
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 44431
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 29
telemt_desync_full_logged_total 12
telemt_desync_suppressed_total 17
telemt_desync_frames_bucket_total{bucket="1_2"} 9
telemt_desync_frames_bucket_total{bucket="3_10"} 9
telemt_desync_frames_bucket_total{bucket="gt_10"} 11
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 5925
telemt_me_writer_restored_same_endpoint_total 5837
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 77
telemt_user_connections_total{user="hello"} 44416
telemt_user_connections_current{user="hello"} 102
telemt_user_octets_from_client{user="hello"} 5538043016 (5.16 GB)
telemt_user_octets_to_client{user="hello"} 16854902376 (15.70 GB)
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 26760.1 (7h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 81855
telemt_connections_bad_total 3085
telemt_handshake_timeouts_total 528
telemt_upstream_connect_attempt_total 6258
telemt_upstream_connect_success_total 6200
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 6257
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2902
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3261
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_reconnect_attempts_total 4886
telemt_me_reconnect_success_total 4852
telemt_me_reader_eof_total 5147
telemt_me_idle_close_by_peer_total 5147
telemt_me_route_drop_no_conn_total 28282
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 75967
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 146
telemt_desync_full_logged_total 43
telemt_desync_suppressed_total 103
telemt_desync_frames_bucket_total{bucket="1_2"} 29
telemt_desync_frames_bucket_total{bucket="3_10"} 56
telemt_desync_frames_bucket_total{bucket="gt_10"} 61
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 4923
telemt_me_writer_restored_same_endpoint_total 4845
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 71
telemt_user_connections_total{user="hello"} 75951
telemt_user_connections_current{user="hello"} 164
telemt_user_octets_from_client{user="hello"} 902471636 (860.66 MB)
telemt_user_octets_to_client{user="hello"} 36233627092 (33.75 GB)
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 26732.1 (7h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 62228
telemt_connections_bad_total 15461
telemt_handshake_timeouts_total 409
telemt_upstream_connect_attempt_total 8010
telemt_upstream_connect_success_total 7907
telemt_upstream_connect_fail_total 103
telemt_upstream_connect_attempts_per_request{bucket="1"} 8010
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3564
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 134
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 103
telemt_me_reconnect_attempts_total 8808
telemt_me_reconnect_success_total 6563
telemt_me_reader_eof_total 6910
telemt_me_idle_close_by_peer_total 6910
telemt_me_route_drop_no_conn_total 17711
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 44538
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 31
telemt_desync_full_logged_total 12
telemt_desync_suppressed_total 19
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 13
telemt_desync_frames_bucket_total{bucket="gt_10"} 12
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 6736
telemt_me_refill_failed_total 69
telemt_me_writer_restored_same_endpoint_total 6555
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 173
telemt_user_connections_total{user="hello"} 44533
telemt_user_connections_current{user="hello"} 94
telemt_user_octets_from_client{user="hello"} 466115796 (444.52 MB)
telemt_user_octets_to_client{user="hello"} 14293015056 (13.31 GB)
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 26893.1 (7h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 152171
telemt_connections_bad_total 4610
telemt_handshake_timeouts_total 1045
telemt_upstream_connect_attempt_total 5524
telemt_upstream_connect_success_total 5492
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 5524
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2594
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2893
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_reconnect_attempts_total 4173
telemt_me_reconnect_success_total 4160
telemt_me_reader_eof_total 4454
telemt_me_idle_close_by_peer_total 4454
telemt_me_route_drop_no_conn_total 173684
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 219023
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 140
telemt_desync_full_logged_total 82
telemt_desync_suppressed_total 58
telemt_desync_frames_bucket_total{bucket="1_2"} 43
telemt_desync_frames_bucket_total{bucket="3_10"} 45
telemt_desync_frames_bucket_total{bucket="gt_10"} 52
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 4219
telemt_me_writer_restored_same_endpoint_total 4150
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 141278
telemt_user_connections_current{user="hello"} 370
telemt_user_octets_from_client{user="hello"} 2320748584 (2.16 GB)
telemt_user_octets_to_client{user="hello"} 116047662184 (108.08 GB)
telemt_user_unique_ips_current{user="hello"} 150
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 14899.6 (4h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 113
telemt_connections_bad_total 75
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 7508
telemt_upstream_connect_success_total 7508
telemt_upstream_connect_attempts_per_request{bucket="1"} 7508
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4373
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3132
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 6746
telemt_me_reconnect_success_total 6705
telemt_me_reader_eof_total 7345
telemt_me_idle_close_by_peer_total 7345
telemt_me_route_drop_no_conn_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 36
telemt_me_writer_pick_total{mode="p2c",result="full"} 3
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 6773
telemt_me_writer_restored_same_endpoint_total 6705
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 68
telemt_user_connections_total{user="hello"} 36
telemt_user_octets_from_client{user="hello"} 157473040 (150.18 MB)
telemt_user_octets_to_client{user="hello"} 23027108 (21.96 MB)
```