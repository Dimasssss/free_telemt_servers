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

# Server Metrics 2026-03-15 00:27:49 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 8001.2 (2h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16737
telemt_connections_bad_total 358
telemt_handshake_timeouts_total 226
telemt_upstream_connect_attempt_total 2020
telemt_upstream_connect_success_total 2009
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 2020
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 949
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1056
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_reconnect_attempts_total 1601
telemt_me_reconnect_success_total 1593
telemt_me_reader_eof_total 1659
telemt_me_idle_close_by_peer_total 1659
telemt_me_route_drop_no_conn_total 4530
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 15591
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 100
telemt_desync_full_logged_total 44
telemt_desync_suppressed_total 56
telemt_desync_frames_bucket_total{bucket="1_2"} 18
telemt_desync_frames_bucket_total{bucket="3_10"} 32
telemt_desync_frames_bucket_total{bucket="gt_10"} 50
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 1591
telemt_me_writer_restored_same_endpoint_total 1562
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_user_connections_total{user="hello"} 15590
telemt_user_connections_current{user="hello"} 240
telemt_user_octets_from_client{user="hello"} 187682728 (178.99 MB)
telemt_user_octets_to_client{user="hello"} 4923819224 (4.59 GB)
telemt_user_unique_ips_current{user="hello"} 70
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 8007.7 (2h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7443
telemt_connections_bad_total 12
telemt_handshake_timeouts_total 23
telemt_upstream_connect_attempt_total 2225
telemt_upstream_connect_success_total 2225
telemt_upstream_connect_attempts_per_request{bucket="1"} 2225
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 979
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1246
telemt_me_reconnect_attempts_total 1811
telemt_me_reconnect_success_total 1805
telemt_me_reader_eof_total 1904
telemt_me_idle_close_by_peer_total 1904
telemt_me_route_drop_no_conn_total 2334
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7036
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 1814
telemt_me_writer_restored_same_endpoint_total 1789
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 7037
telemt_user_connections_current{user="hello"} 116
telemt_user_octets_from_client{user="hello"} 64049532 (61.08 MB)
telemt_user_octets_to_client{user="hello"} 1262477116 (1.18 GB)
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 8000.4 (2h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7837
telemt_connections_bad_total 72
telemt_handshake_timeouts_total 144
telemt_upstream_connect_attempt_total 2106
telemt_upstream_connect_success_total 2105
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 2106
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 927
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1174
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 1695
telemt_me_reconnect_success_total 1683
telemt_me_reader_eof_total 1800
telemt_me_idle_close_by_peer_total 1800
telemt_me_route_drop_no_conn_total 2575
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7375
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 1691
telemt_me_writer_restored_same_endpoint_total 1679
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 8
telemt_user_connections_total{user="hello"} 7356
telemt_user_connections_current{user="hello"} 76
telemt_user_octets_from_client{user="hello"} 1048515760 (999.94 MB)
telemt_user_octets_to_client{user="hello"} 10512716456 (9.79 GB)
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 8000.0 (2h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7572
telemt_connections_bad_total 56
telemt_handshake_timeouts_total 34
telemt_upstream_connect_attempt_total 1957
telemt_upstream_connect_success_total 1956
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 1957
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 891
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1062
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 1550
telemt_me_reconnect_success_total 1541
telemt_me_reader_eof_total 1617
telemt_me_idle_close_by_peer_total 1617
telemt_me_route_drop_no_conn_total 3290
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7284
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
telemt_me_writer_removed_unexpected_total 1549
telemt_me_writer_restored_same_endpoint_total 1530
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 8
telemt_user_connections_total{user="hello"} 7284
telemt_user_connections_current{user="hello"} 114
telemt_user_octets_from_client{user="hello"} 187963420 (179.26 MB)
telemt_user_octets_to_client{user="hello"} 6004720680 (5.59 GB)
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 8000.3 (2h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10262
telemt_connections_bad_total 1727
telemt_handshake_timeouts_total 361
telemt_upstream_connect_attempt_total 2627
telemt_upstream_connect_success_total 2595
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 2627
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1273
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1318
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_reconnect_attempts_total 2253
telemt_me_reconnect_success_total 2181
telemt_me_reader_eof_total 2262
telemt_me_idle_close_by_peer_total 2262
telemt_me_route_drop_no_conn_total 2462
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7968
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 2181
telemt_me_refill_failed_total 2
telemt_me_writer_restored_same_endpoint_total 2169
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 29
telemt_user_connections_total{user="hello"} 7961
telemt_user_connections_current{user="hello"} 55
telemt_user_octets_from_client{user="hello"} 85961612 (81.98 MB)
telemt_user_octets_to_client{user="hello"} 4430531360 (4.13 GB)
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 7999.3 (2h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 26253
telemt_connections_bad_total 395
telemt_handshake_timeouts_total 98
telemt_upstream_connect_attempt_total 1772
telemt_upstream_connect_success_total 1765
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 1772
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 877
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 888
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_reconnect_attempts_total 1354
telemt_me_reconnect_success_total 1351
telemt_me_reader_eof_total 1394
telemt_me_idle_close_by_peer_total 1394
telemt_me_route_drop_no_conn_total 15289
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 26450
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
telemt_me_writer_removed_unexpected_total 1335
telemt_me_writer_restored_same_endpoint_total 1324
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_user_connections_total{user="hello"} 25037
telemt_user_connections_current{user="hello"} 295
telemt_user_octets_from_client{user="hello"} 418155844 (398.78 MB)
telemt_user_octets_to_client{user="hello"} 19738089440 (18.38 GB)
telemt_user_unique_ips_current{user="hello"} 133
telemt_user_unique_ips_recent_window{user="hello"} 27
```