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

# Server Metrics 2026-03-15 00:37:59 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 8611.8 (2h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17984
telemt_connections_bad_total 362
telemt_handshake_timeouts_total 245
telemt_upstream_connect_attempt_total 2203
telemt_upstream_connect_success_total 2192
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 2203
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1032
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1156
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_reconnect_attempts_total 1741
telemt_me_reconnect_success_total 1732
telemt_me_reader_eof_total 1813
telemt_me_idle_close_by_peer_total 1813
telemt_me_route_drop_no_conn_total 4875
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16777
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
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 1731
telemt_me_writer_restored_same_endpoint_total 1701
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_user_connections_total{user="hello"} 16776
telemt_user_connections_current{user="hello"} 237
telemt_user_octets_from_client{user="hello"} 195708328 (186.64 MB)
telemt_user_octets_to_client{user="hello"} 5128223120 (4.78 GB)
telemt_user_unique_ips_current{user="hello"} 77
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 8618.4 (2h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8080
telemt_connections_bad_total 12
telemt_handshake_timeouts_total 24
telemt_upstream_connect_attempt_total 2422
telemt_upstream_connect_success_total 2422
telemt_upstream_connect_attempts_per_request{bucket="1"} 2422
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1065
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1357
telemt_me_reconnect_attempts_total 1965
telemt_me_reconnect_success_total 1959
telemt_me_reader_eof_total 2075
telemt_me_idle_close_by_peer_total 2075
telemt_me_route_drop_no_conn_total 2519
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7636
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 1969
telemt_me_writer_restored_same_endpoint_total 1943
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 7638
telemt_user_connections_current{user="hello"} 101
telemt_user_octets_from_client{user="hello"} 76601792 (73.05 MB)
telemt_user_octets_to_client{user="hello"} 1453153080 (1.35 GB)
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 8610.7 (2h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8564
telemt_connections_bad_total 72
telemt_handshake_timeouts_total 161
telemt_upstream_connect_attempt_total 2291
telemt_upstream_connect_success_total 2290
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 2291
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1015
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1271
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 1837
telemt_me_reconnect_success_total 1825
telemt_me_reader_eof_total 1956
telemt_me_idle_close_by_peer_total 1956
telemt_me_route_drop_no_conn_total 2761
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8066
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 1834
telemt_me_writer_restored_same_endpoint_total 1821
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 8047
telemt_user_connections_current{user="hello"} 91
telemt_user_octets_from_client{user="hello"} 1051897636 (1003.17 MB)
telemt_user_octets_to_client{user="hello"} 10903768172 (10.15 GB)
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 8610.5 (2h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8311
telemt_connections_bad_total 72
telemt_handshake_timeouts_total 34
telemt_upstream_connect_attempt_total 2125
telemt_upstream_connect_success_total 2124
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 2125
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 973
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1148
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 1675
telemt_me_reconnect_success_total 1666
telemt_me_reader_eof_total 1757
telemt_me_idle_close_by_peer_total 1757
telemt_me_route_drop_no_conn_total 3532
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7977
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 39
telemt_desync_full_logged_total 4
telemt_desync_suppressed_total 35
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 20
telemt_desync_frames_bucket_total{bucket="gt_10"} 16
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 1676
telemt_me_writer_restored_same_endpoint_total 1655
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 7977
telemt_user_connections_current{user="hello"} 105
telemt_user_octets_from_client{user="hello"} 190564076 (181.74 MB)
telemt_user_octets_to_client{user="hello"} 6155523956 (5.73 GB)
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 8610.8 (2h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11309
telemt_connections_bad_total 1839
telemt_handshake_timeouts_total 361
telemt_upstream_connect_attempt_total 2819
telemt_upstream_connect_success_total 2782
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 2819
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1359
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1418
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_reconnect_attempts_total 2397
telemt_me_reconnect_success_total 2323
telemt_me_reader_eof_total 2417
telemt_me_idle_close_by_peer_total 2417
telemt_me_route_drop_no_conn_total 2666
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8894
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 2323
telemt_me_refill_failed_total 2
telemt_me_writer_restored_same_endpoint_total 2311
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 29
telemt_user_connections_total{user="hello"} 8885
telemt_user_connections_current{user="hello"} 44
telemt_user_octets_from_client{user="hello"} 116758412 (111.35 MB)
telemt_user_octets_to_client{user="hello"} 4717182356 (4.39 GB)
telemt_user_unique_ips_current{user="hello"} 22
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 8609.7 (2h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 28085
telemt_connections_bad_total 407
telemt_handshake_timeouts_total 98
telemt_upstream_connect_attempt_total 1922
telemt_upstream_connect_success_total 1914
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 1922
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 954
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 960
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 1460
telemt_me_reconnect_success_total 1456
telemt_me_reader_eof_total 1509
telemt_me_idle_close_by_peer_total 1509
telemt_me_route_drop_no_conn_total 16403
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 28223
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
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 1441
telemt_me_writer_restored_same_endpoint_total 1429
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_user_connections_total{user="hello"} 26810
telemt_user_connections_current{user="hello"} 261
telemt_user_octets_from_client{user="hello"} 432775624 (412.73 MB)
telemt_user_octets_to_client{user="hello"} 20230079016 (18.84 GB)
telemt_user_unique_ips_current{user="hello"} 124
telemt_user_unique_ips_recent_window{user="hello"} 32
```