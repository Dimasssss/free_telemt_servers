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

# Server Metrics 2026-03-17 02:25:10 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 27588.6 (7h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 146967
telemt_connections_bad_total 2329
telemt_handshake_timeouts_total 5331
telemt_upstream_connect_attempt_total 5947
telemt_upstream_connect_success_total 5909
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 5947
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2643
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3261
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 4543
telemt_me_reconnect_success_total 4527
telemt_me_reader_eof_total 4810
telemt_me_idle_close_by_peer_total 4810
telemt_me_route_drop_no_conn_total 45405
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 133072
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 741
telemt_desync_full_logged_total 253
telemt_desync_suppressed_total 488
telemt_desync_frames_bucket_total{bucket="1_2"} 166
telemt_desync_frames_bucket_total{bucket="3_10"} 375
telemt_desync_frames_bucket_total{bucket="gt_10"} 200
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 4564
telemt_me_writer_restored_same_endpoint_total 4506
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 133006
telemt_user_connections_current{user="hello"} 338
telemt_user_octets_from_client{user="hello"} 1850863128 (1.72 GB)
telemt_user_octets_to_client{user="hello"} 61107999980 (56.91 GB)
telemt_user_unique_ips_current{user="hello"} 128
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 27839.9 (7h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 83756
telemt_connections_bad_total 1342
telemt_handshake_timeouts_total 2918
telemt_upstream_connect_attempt_total 7417
telemt_upstream_connect_success_total 7320
telemt_upstream_connect_fail_total 97
telemt_upstream_connect_attempts_per_request{bucket="1"} 7417
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3013
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4232
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 97
telemt_me_reconnect_attempts_total 7110
telemt_me_reconnect_success_total 5944
telemt_me_reader_eof_total 6264
telemt_me_idle_close_by_peer_total 6264
telemt_me_route_drop_no_conn_total 34815
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 76063
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 183
telemt_desync_full_logged_total 60
telemt_desync_suppressed_total 123
telemt_desync_frames_bucket_total{bucket="1_2"} 45
telemt_desync_frames_bucket_total{bucket="3_10"} 85
telemt_desync_frames_bucket_total{bucket="gt_10"} 53
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 6043
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 5928
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 99
telemt_user_connections_total{user="hello"} 76006
telemt_user_connections_current{user="hello"} 172
telemt_user_octets_from_client{user="hello"} 1126957556 (1.05 GB)
telemt_user_octets_to_client{user="hello"} 35443658624 (33.01 GB)
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 27616.2 (7h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 53688
telemt_connections_bad_total 625
telemt_handshake_timeouts_total 1853
telemt_upstream_connect_attempt_total 7470
telemt_upstream_connect_success_total 7426
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 7470
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3250
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4116
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 6065
telemt_me_reconnect_success_total 6030
telemt_me_reader_eof_total 6441
telemt_me_idle_close_by_peer_total 6441
telemt_me_route_drop_no_conn_total 16826
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 45296
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
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 6110
telemt_me_writer_restored_same_endpoint_total 6019
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 80
telemt_user_connections_total{user="hello"} 45280
telemt_user_connections_current{user="hello"} 93
telemt_user_octets_from_client{user="hello"} 5542242320 (5.16 GB)
telemt_user_octets_to_client{user="hello"} 17103569684 (15.93 GB)
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 27675.4 (7h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 83654
telemt_connections_bad_total 3088
telemt_handshake_timeouts_total 756
telemt_upstream_connect_attempt_total 6462
telemt_upstream_connect_success_total 6404
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 6462
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2997
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3369
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_reconnect_attempts_total 5047
telemt_me_reconnect_success_total 5012
telemt_me_reader_eof_total 5317
telemt_me_idle_close_by_peer_total 5317
telemt_me_route_drop_no_conn_total 28943
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 77476
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 147
telemt_desync_full_logged_total 44
telemt_desync_suppressed_total 103
telemt_desync_frames_bucket_total{bucket="1_2"} 29
telemt_desync_frames_bucket_total{bucket="3_10"} 56
telemt_desync_frames_bucket_total{bucket="gt_10"} 62
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 5084
telemt_me_writer_restored_same_endpoint_total 5005
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 72
telemt_user_connections_total{user="hello"} 77460
telemt_user_connections_current{user="hello"} 164
telemt_user_octets_from_client{user="hello"} 914253948 (871.90 MB)
telemt_user_octets_to_client{user="hello"} 36665395192 (34.15 GB)
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 27647.4 (7h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 63963
telemt_connections_bad_total 15634
telemt_handshake_timeouts_total 535
telemt_upstream_connect_attempt_total 8225
telemt_upstream_connect_success_total 8119
telemt_upstream_connect_fail_total 106
telemt_upstream_connect_attempts_per_request{bucket="1"} 8225
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3659
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4325
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 135
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 106
telemt_me_reconnect_attempts_total 8977
telemt_me_reconnect_success_total 6730
telemt_me_reader_eof_total 7088
telemt_me_idle_close_by_peer_total 7088
telemt_me_route_drop_no_conn_total 18156
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 45955
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
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 6906
telemt_me_refill_failed_total 69
telemt_me_writer_restored_same_endpoint_total 6722
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 176
telemt_user_connections_total{user="hello"} 45950
telemt_user_connections_current{user="hello"} 93
telemt_user_octets_from_client{user="hello"} 534075248 (509.33 MB)
telemt_user_octets_to_client{user="hello"} 14660448008 (13.65 GB)
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 27808.3 (7h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 155730
telemt_connections_bad_total 5423
telemt_handshake_timeouts_total 1062
telemt_upstream_connect_attempt_total 5721
telemt_upstream_connect_success_total 5689
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 5721
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2687
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2997
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_reconnect_attempts_total 4327
telemt_me_reconnect_success_total 4313
telemt_me_reader_eof_total 4619
telemt_me_idle_close_by_peer_total 4619
telemt_me_route_drop_no_conn_total 174975
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 221613
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 141
telemt_desync_full_logged_total 83
telemt_desync_suppressed_total 58
telemt_desync_frames_bucket_total{bucket="1_2"} 43
telemt_desync_frames_bucket_total{bucket="3_10"} 46
telemt_desync_frames_bucket_total{bucket="gt_10"} 52
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 4373
telemt_me_writer_restored_same_endpoint_total 4303
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 60
telemt_user_connections_total{user="hello"} 143869
telemt_user_connections_current{user="hello"} 327
telemt_user_octets_from_client{user="hello"} 2343514416 (2.18 GB)
telemt_user_octets_to_client{user="hello"} 118628909384 (110.48 GB)
telemt_user_unique_ips_current{user="hello"} 148
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 15814.9 (4h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 113
telemt_connections_bad_total 75
telemt_handshake_timeouts_total 2
telemt_upstream_connect_attempt_total 7963
telemt_upstream_connect_success_total 7963
telemt_upstream_connect_attempts_per_request{bucket="1"} 7963
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4635
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3325
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 7157
telemt_me_reconnect_success_total 7115
telemt_me_reader_eof_total 7798
telemt_me_idle_close_by_peer_total 7798
telemt_me_route_drop_no_conn_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 36
telemt_me_writer_pick_total{mode="p2c",result="full"} 3
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 7188
telemt_me_writer_restored_same_endpoint_total 7115
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 73
telemt_user_connections_total{user="hello"} 36
telemt_user_octets_from_client{user="hello"} 157473040 (150.18 MB)
telemt_user_octets_to_client{user="hello"} 23027108 (21.96 MB)
```