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

# Server Metrics 2026-03-15 01:08:31 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 10443.5 (2h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21664
telemt_connections_bad_total 366
telemt_handshake_timeouts_total 262
telemt_upstream_connect_attempt_total 2673
telemt_upstream_connect_success_total 2659
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 2673
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1236
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1419
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_reconnect_attempts_total 2122
telemt_me_reconnect_success_total 2111
telemt_me_reader_eof_total 2224
telemt_me_idle_close_by_peer_total 2224
telemt_me_route_drop_no_conn_total 6010
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 20341
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 127
telemt_desync_full_logged_total 55
telemt_desync_suppressed_total 72
telemt_desync_frames_bucket_total{bucket="1_2"} 22
telemt_desync_frames_bucket_total{bucket="3_10"} 41
telemt_desync_frames_bucket_total{bucket="gt_10"} 64
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 2113
telemt_me_writer_restored_same_endpoint_total 2080
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 20339
telemt_user_connections_current{user="hello"} 215
telemt_user_octets_from_client{user="hello"} 223905456 (213.53 MB)
telemt_user_octets_to_client{user="hello"} 6987425016 (6.51 GB)
telemt_user_unique_ips_current{user="hello"} 69
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 10449.7 (2h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10039
telemt_connections_bad_total 16
telemt_handshake_timeouts_total 30
telemt_upstream_connect_attempt_total 2928
telemt_upstream_connect_success_total 2928
telemt_upstream_connect_attempts_per_request{bucket="1"} 2928
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1290
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1638
telemt_me_reconnect_attempts_total 2385
telemt_me_reconnect_success_total 2378
telemt_me_reader_eof_total 2525
telemt_me_idle_close_by_peer_total 2525
telemt_me_route_drop_no_conn_total 3297
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9467
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 2389
telemt_me_writer_restored_same_endpoint_total 2362
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 9470
telemt_user_connections_current{user="hello"} 114
telemt_user_octets_from_client{user="hello"} 138251252 (131.85 MB)
telemt_user_octets_to_client{user="hello"} 1680603264 (1.57 GB)
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 10442.3 (2h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10301
telemt_connections_bad_total 84
telemt_handshake_timeouts_total 203
telemt_upstream_connect_attempt_total 2773
telemt_upstream_connect_success_total 2772
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 2773
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1239
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1529
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 2233
telemt_me_reconnect_success_total 2220
telemt_me_reader_eof_total 2384
telemt_me_idle_close_by_peer_total 2384
telemt_me_route_drop_no_conn_total 3493
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9700
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 2233
telemt_me_writer_restored_same_endpoint_total 2216
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 13
telemt_user_connections_total{user="hello"} 9672
telemt_user_connections_current{user="hello"} 77
telemt_user_octets_from_client{user="hello"} 1681840232 (1.57 GB)
telemt_user_octets_to_client{user="hello"} 10976018412 (10.22 GB)
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 10442.0 (2h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10601
telemt_connections_bad_total 74
telemt_handshake_timeouts_total 38
telemt_upstream_connect_attempt_total 2547
telemt_upstream_connect_success_total 2546
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 2547
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1159
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1382
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 2011
telemt_me_reconnect_success_total 2001
telemt_me_reader_eof_total 2119
telemt_me_idle_close_by_peer_total 2119
telemt_me_route_drop_no_conn_total 4166
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10221
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 54
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 44
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 25
telemt_desync_frames_bucket_total{bucket="gt_10"} 23
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 2015
telemt_me_writer_restored_same_endpoint_total 1990
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 10219
telemt_user_connections_current{user="hello"} 136
telemt_user_octets_from_client{user="hello"} 264766652 (252.50 MB)
telemt_user_octets_to_client{user="hello"} 7553009452 (7.03 GB)
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 10442.2 (2h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13248
telemt_connections_bad_total 2171
telemt_handshake_timeouts_total 372
telemt_upstream_connect_attempt_total 3347
telemt_upstream_connect_success_total 3304
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 3347
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1572
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1724
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_reconnect_attempts_total 2833
telemt_me_reconnect_success_total 2755
telemt_me_reader_eof_total 2890
telemt_me_idle_close_by_peer_total 2890
telemt_me_route_drop_no_conn_total 3353
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10453
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 2762
telemt_me_refill_failed_total 2
telemt_me_writer_restored_same_endpoint_total 2743
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 29
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 10441
telemt_user_connections_current{user="hello"} 64
telemt_user_octets_from_client{user="hello"} 164710620 (157.08 MB)
telemt_user_octets_to_client{user="hello"} 5944232252 (5.54 GB)
telemt_user_unique_ips_current{user="hello"} 22
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 10441.2 (2h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 33731
telemt_connections_bad_total 980
telemt_handshake_timeouts_total 124
telemt_upstream_connect_attempt_total 2309
telemt_upstream_connect_success_total 2296
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 2309
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1150
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1146
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_reconnect_attempts_total 1756
telemt_me_reconnect_success_total 1749
telemt_me_reader_eof_total 1826
telemt_me_idle_close_by_peer_total 1826
telemt_me_route_drop_no_conn_total 19266
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 33166
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16
telemt_desync_full_logged_total 5
telemt_desync_suppressed_total 11
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 4
telemt_desync_frames_bucket_total{bucket="gt_10"} 6
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 1738
telemt_me_writer_restored_same_endpoint_total 1722
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_user_connections_total{user="hello"} 31735
telemt_user_connections_current{user="hello"} 235
telemt_user_octets_from_client{user="hello"} 484023160 (461.60 MB)
telemt_user_octets_to_client{user="hello"} 22780666828 (21.22 GB)
telemt_user_unique_ips_current{user="hello"} 111
telemt_user_unique_ips_recent_window{user="hello"} 22
```