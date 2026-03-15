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

# Server Metrics 2026-03-15 01:33:57 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 11969.9 (3h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 24937
telemt_connections_bad_total 366
telemt_handshake_timeouts_total 267
telemt_upstream_connect_attempt_total 3080
telemt_upstream_connect_success_total 3061
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 3080
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1398
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1659
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_reconnect_attempts_total 2437
telemt_me_reconnect_success_total 2425
telemt_me_reader_eof_total 2568
telemt_me_idle_close_by_peer_total 2568
telemt_me_route_drop_no_conn_total 6977
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 23542
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 133
telemt_desync_full_logged_total 61
telemt_desync_suppressed_total 72
telemt_desync_frames_bucket_total{bucket="1_2"} 23
telemt_desync_frames_bucket_total{bucket="3_10"} 45
telemt_desync_frames_bucket_total{bucket="gt_10"} 65
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 2430
telemt_me_writer_restored_same_endpoint_total 2394
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 23540
telemt_user_connections_current{user="hello"} 216
telemt_user_octets_from_client{user="hello"} 253926032 (242.16 MB)
telemt_user_octets_to_client{user="hello"} 9709674276 (9.04 GB)
telemt_user_unique_ips_current{user="hello"} 68
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 11976.5 (3h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11452
telemt_connections_bad_total 17
telemt_handshake_timeouts_total 31
telemt_upstream_connect_attempt_total 3339
telemt_upstream_connect_success_total 3339
telemt_upstream_connect_attempts_per_request{bucket="1"} 3339
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1479
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1860
telemt_me_reconnect_attempts_total 2710
telemt_me_reconnect_success_total 2701
telemt_me_reader_eof_total 2876
telemt_me_idle_close_by_peer_total 2876
telemt_me_route_drop_no_conn_total 4010
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10815
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 2716
telemt_me_writer_restored_same_endpoint_total 2685
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 15
telemt_user_connections_total{user="hello"} 10819
telemt_user_connections_current{user="hello"} 108
telemt_user_octets_from_client{user="hello"} 156500160 (149.25 MB)
telemt_user_octets_to_client{user="hello"} 1856606188 (1.73 GB)
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 11969.0 (3h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11762
telemt_connections_bad_total 84
telemt_handshake_timeouts_total 219
telemt_upstream_connect_attempt_total 3200
telemt_upstream_connect_success_total 3199
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 3200
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1423
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1772
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 2574
telemt_me_reconnect_success_total 2560
telemt_me_reader_eof_total 2757
telemt_me_idle_close_by_peer_total 2757
telemt_me_route_drop_no_conn_total 3985
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 11108
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 2575
telemt_me_writer_restored_same_endpoint_total 2556
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 15
telemt_user_connections_total{user="hello"} 11067
telemt_user_connections_current{user="hello"} 58
telemt_user_octets_from_client{user="hello"} 6288237488 (5.86 GB)
telemt_user_octets_to_client{user="hello"} 12384405196 (11.53 GB)
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 11968.8 (3h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12202
telemt_connections_bad_total 76
telemt_handshake_timeouts_total 39
telemt_upstream_connect_attempt_total 2925
telemt_upstream_connect_success_total 2924
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 2925
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1336
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1580
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 2303
telemt_me_reconnect_success_total 2292
telemt_me_reader_eof_total 2433
telemt_me_idle_close_by_peer_total 2433
telemt_me_route_drop_no_conn_total 4761
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 11684
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
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 2309
telemt_me_writer_restored_same_endpoint_total 2281
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 11682
telemt_user_connections_current{user="hello"} 141
telemt_user_octets_from_client{user="hello"} 327150792 (312.00 MB)
telemt_user_octets_to_client{user="hello"} 8979717188 (8.36 GB)
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 11969.0 (3h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15076
telemt_connections_bad_total 2444
telemt_handshake_timeouts_total 385
telemt_upstream_connect_attempt_total 3927
telemt_upstream_connect_success_total 3874
telemt_upstream_connect_fail_total 53
telemt_upstream_connect_attempts_per_request{bucket="1"} 3927
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1799
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2065
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 53
telemt_me_reconnect_attempts_total 3317
telemt_me_reconnect_success_total 3238
telemt_me_reader_eof_total 3404
telemt_me_idle_close_by_peer_total 3404
telemt_me_route_drop_no_conn_total 4124
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 11956
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 3248
telemt_me_refill_failed_total 2
telemt_me_writer_restored_same_endpoint_total 3226
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 29
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 11944
telemt_user_connections_current{user="hello"} 72
telemt_user_octets_from_client{user="hello"} 175492112 (167.36 MB)
telemt_user_octets_to_client{user="hello"} 6519279108 (6.07 GB)
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 11968.0 (3h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 38256
telemt_connections_bad_total 1004
telemt_handshake_timeouts_total 150
telemt_upstream_connect_attempt_total 2656
telemt_upstream_connect_success_total 2638
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 2656
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1322
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1315
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_reconnect_attempts_total 2012
telemt_me_reconnect_success_total 2005
telemt_me_reader_eof_total 2106
telemt_me_idle_close_by_peer_total 2106
telemt_me_route_drop_no_conn_total 21477
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 37518
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
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 1996
telemt_me_writer_restored_same_endpoint_total 1978
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_user_connections_total{user="hello"} 36087
telemt_user_connections_current{user="hello"} 221
telemt_user_octets_from_client{user="hello"} 1124057048 (1.05 GB)
telemt_user_octets_to_client{user="hello"} 24261616184 (22.60 GB)
telemt_user_unique_ips_current{user="hello"} 105
telemt_user_unique_ips_recent_window{user="hello"} 35
```