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

# Server Metrics 2026-03-15 00:17:38 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 7390.6 (2h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15370
telemt_connections_bad_total 293
telemt_handshake_timeouts_total 206
telemt_upstream_connect_attempt_total 1887
telemt_upstream_connect_success_total 1876
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 1887
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 897
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 975
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_reconnect_attempts_total 1468
telemt_me_reconnect_success_total 1461
telemt_me_reader_eof_total 1526
telemt_me_idle_close_by_peer_total 1526
telemt_me_route_drop_no_conn_total 4128
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 14330
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 92
telemt_desync_full_logged_total 38
telemt_desync_suppressed_total 54
telemt_desync_frames_bucket_total{bucket="1_2"} 14
telemt_desync_frames_bucket_total{bucket="3_10"} 32
telemt_desync_frames_bucket_total{bucket="gt_10"} 46
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 1458
telemt_me_writer_restored_same_endpoint_total 1430
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_user_connections_total{user="hello"} 14329
telemt_user_connections_current{user="hello"} 257
telemt_user_octets_from_client{user="hello"} 178974168 (170.68 MB)
telemt_user_octets_to_client{user="hello"} 4668529848 (4.35 GB)
telemt_user_unique_ips_current{user="hello"} 75
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 7396.9 (2h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6813
telemt_connections_bad_total 12
telemt_handshake_timeouts_total 23
telemt_upstream_connect_attempt_total 2091
telemt_upstream_connect_success_total 2091
telemt_upstream_connect_attempts_per_request{bucket="1"} 2091
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 925
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1166
telemt_me_reconnect_attempts_total 1677
telemt_me_reconnect_success_total 1672
telemt_me_reader_eof_total 1769
telemt_me_idle_close_by_peer_total 1769
telemt_me_route_drop_no_conn_total 2125
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6436
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 1679
telemt_me_writer_restored_same_endpoint_total 1656
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 6437
telemt_user_connections_current{user="hello"} 125
telemt_user_octets_from_client{user="hello"} 61232896 (58.40 MB)
telemt_user_octets_to_client{user="hello"} 1149811036 (1.07 GB)
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 7389.6 (2h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7144
telemt_connections_bad_total 71
telemt_handshake_timeouts_total 126
telemt_upstream_connect_attempt_total 1987
telemt_upstream_connect_success_total 1986
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 1987
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 877
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1105
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 1576
telemt_me_reconnect_success_total 1564
telemt_me_reader_eof_total 1679
telemt_me_idle_close_by_peer_total 1679
telemt_me_route_drop_no_conn_total 2406
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6717
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 1570
telemt_me_writer_restored_same_endpoint_total 1560
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 6698
telemt_user_connections_current{user="hello"} 94
telemt_user_octets_from_client{user="hello"} 1035053352 (987.10 MB)
telemt_user_octets_to_client{user="hello"} 9773115488 (9.10 GB)
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 7389.3 (2h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6933
telemt_connections_bad_total 42
telemt_handshake_timeouts_total 31
telemt_upstream_connect_attempt_total 1835
telemt_upstream_connect_success_total 1834
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 1835
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 848
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 984
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 1428
telemt_me_reconnect_success_total 1419
telemt_me_reader_eof_total 1493
telemt_me_idle_close_by_peer_total 1493
telemt_me_route_drop_no_conn_total 3124
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6679
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 12
telemt_desync_full_logged_total 2
telemt_desync_suppressed_total 10
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 5
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 1425
telemt_me_writer_restored_same_endpoint_total 1408
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 6679
telemt_user_connections_current{user="hello"} 104
telemt_user_octets_from_client{user="hello"} 185238484 (176.66 MB)
telemt_user_octets_to_client{user="hello"} 5911878484 (5.51 GB)
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 7389.5 (2h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9034
telemt_connections_bad_total 1618
telemt_handshake_timeouts_total 361
telemt_upstream_connect_attempt_total 2475
telemt_upstream_connect_success_total 2443
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 2475
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1213
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1226
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_reconnect_attempts_total 2101
telemt_me_reconnect_success_total 2029
telemt_me_reader_eof_total 2108
telemt_me_idle_close_by_peer_total 2108
telemt_me_route_drop_no_conn_total 2253
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6868
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 2027
telemt_me_refill_failed_total 2
telemt_me_writer_restored_same_endpoint_total 2017
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 29
telemt_user_connections_total{user="hello"} 6863
telemt_user_connections_current{user="hello"} 56
telemt_user_octets_from_client{user="hello"} 57540896 (54.88 MB)
telemt_user_octets_to_client{user="hello"} 4168454740 (3.88 GB)
telemt_user_unique_ips_current{user="hello"} 20
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 7388.5 (2h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 23953
telemt_connections_bad_total 377
telemt_handshake_timeouts_total 85
telemt_upstream_connect_attempt_total 1681
telemt_upstream_connect_success_total 1674
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 1681
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 832
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 842
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_reconnect_attempts_total 1263
telemt_me_reconnect_success_total 1260
telemt_me_reader_eof_total 1303
telemt_me_idle_close_by_peer_total 1303
telemt_me_route_drop_no_conn_total 13707
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 23918
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
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 1244
telemt_me_writer_restored_same_endpoint_total 1233
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_user_connections_total{user="hello"} 22822
telemt_user_connections_current{user="hello"} 286
telemt_user_octets_from_client{user="hello"} 402708024 (384.05 MB)
telemt_user_octets_to_client{user="hello"} 18745786676 (17.46 GB)
telemt_user_unique_ips_current{user="hello"} 136
telemt_user_unique_ips_recent_window{user="hello"} 37
```