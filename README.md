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

# Server Metrics 2026-03-15 00:12:33 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 7085.3 (1h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14599
telemt_connections_bad_total 291
telemt_handshake_timeouts_total 199
telemt_upstream_connect_attempt_total 1783
telemt_upstream_connect_success_total 1774
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 1783
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 843
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 927
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_reconnect_attempts_total 1409
telemt_me_reconnect_success_total 1402
telemt_me_reader_eof_total 1457
telemt_me_idle_close_by_peer_total 1457
telemt_me_route_drop_no_conn_total 4015
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13582
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 90
telemt_desync_full_logged_total 37
telemt_desync_suppressed_total 53
telemt_desync_frames_bucket_total{bucket="1_2"} 14
telemt_desync_frames_bucket_total{bucket="3_10"} 30
telemt_desync_frames_bucket_total{bucket="gt_10"} 46
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 1399
telemt_me_writer_restored_same_endpoint_total 1371
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_user_connections_total{user="hello"} 13581
telemt_user_connections_current{user="hello"} 280
telemt_user_octets_from_client{user="hello"} 174547156 (166.46 MB)
telemt_user_octets_to_client{user="hello"} 4356747664 (4.06 GB)
telemt_user_unique_ips_current{user="hello"} 85
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 7091.7 (1h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6419
telemt_connections_bad_total 12
telemt_handshake_timeouts_total 23
telemt_upstream_connect_attempt_total 1981
telemt_upstream_connect_success_total 1981
telemt_upstream_connect_attempts_per_request{bucket="1"} 1981
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 873
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1108
telemt_me_reconnect_attempts_total 1610
telemt_me_reconnect_success_total 1605
telemt_me_reader_eof_total 1689
telemt_me_idle_close_by_peer_total 1689
telemt_me_route_drop_no_conn_total 2039
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6049
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 1612
telemt_me_writer_restored_same_endpoint_total 1589
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 6050
telemt_user_connections_current{user="hello"} 128
telemt_user_octets_from_client{user="hello"} 58867676 (56.14 MB)
telemt_user_octets_to_client{user="hello"} 897760964 (856.17 MB)
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 7084.3 (1h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6816
telemt_connections_bad_total 71
telemt_handshake_timeouts_total 117
telemt_upstream_connect_attempt_total 1873
telemt_upstream_connect_success_total 1872
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 1873
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 822
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1046
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 1505
telemt_me_reconnect_success_total 1494
telemt_me_reader_eof_total 1593
telemt_me_idle_close_by_peer_total 1593
telemt_me_route_drop_no_conn_total 2319
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6405
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 1499
telemt_me_writer_restored_same_endpoint_total 1490
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 6386
telemt_user_connections_current{user="hello"} 79
telemt_user_octets_from_client{user="hello"} 1031963040 (984.16 MB)
telemt_user_octets_to_client{user="hello"} 9412489704 (8.77 GB)
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 7084.1 (1h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6627
telemt_connections_bad_total 40
telemt_handshake_timeouts_total 25
telemt_upstream_connect_attempt_total 1735
telemt_upstream_connect_success_total 1734
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 1735
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 795
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 937
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 1371
telemt_me_reconnect_success_total 1363
telemt_me_reader_eof_total 1427
telemt_me_idle_close_by_peer_total 1427
telemt_me_route_drop_no_conn_total 3006
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6379
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
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 1369
telemt_me_writer_restored_same_endpoint_total 1352
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 6379
telemt_user_connections_current{user="hello"} 107
telemt_user_octets_from_client{user="hello"} 174927128 (166.82 MB)
telemt_user_octets_to_client{user="hello"} 5875419276 (5.47 GB)
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 7084.2 (1h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8710
telemt_connections_bad_total 1564
telemt_handshake_timeouts_total 361
telemt_upstream_connect_attempt_total 2371
telemt_upstream_connect_success_total 2342
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 2371
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1157
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1181
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_reconnect_attempts_total 2043
telemt_me_reconnect_success_total 1972
telemt_me_reader_eof_total 2040
telemt_me_idle_close_by_peer_total 2040
telemt_me_route_drop_no_conn_total 2168
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6603
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 1970
telemt_me_refill_failed_total 2
telemt_me_writer_restored_same_endpoint_total 1960
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 29
telemt_user_connections_total{user="hello"} 6598
telemt_user_connections_current{user="hello"} 78
telemt_user_octets_from_client{user="hello"} 55102252 (52.55 MB)
telemt_user_octets_to_client{user="hello"} 4054263812 (3.78 GB)
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 7083.1 (1h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 22907
telemt_connections_bad_total 377
telemt_handshake_timeouts_total 84
telemt_upstream_connect_attempt_total 1585
telemt_upstream_connect_success_total 1579
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 1585
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 785
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 794
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_reconnect_attempts_total 1211
telemt_me_reconnect_success_total 1209
telemt_me_reader_eof_total 1242
telemt_me_idle_close_by_peer_total 1242
telemt_me_route_drop_no_conn_total 13156
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 22808
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
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 1192
telemt_me_writer_restored_same_endpoint_total 1182
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_user_connections_total{user="hello"} 21812
telemt_user_connections_current{user="hello"} 341
telemt_user_octets_from_client{user="hello"} 385534188 (367.67 MB)
telemt_user_octets_to_client{user="hello"} 17910813496 (16.68 GB)
telemt_user_unique_ips_current{user="hello"} 148
telemt_user_unique_ips_recent_window{user="hello"} 40
```