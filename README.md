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

# Server Metrics 2026-03-15 00:43:04 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 8917.0 (2h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18513
telemt_connections_bad_total 364
telemt_handshake_timeouts_total 254
telemt_upstream_connect_attempt_total 2255
telemt_upstream_connect_success_total 2244
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 2255
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1053
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1187
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_reconnect_attempts_total 1793
telemt_me_reconnect_success_total 1783
telemt_me_reader_eof_total 1865
telemt_me_idle_close_by_peer_total 1865
telemt_me_route_drop_no_conn_total 5034
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 17278
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 105
telemt_desync_full_logged_total 46
telemt_desync_suppressed_total 59
telemt_desync_frames_bucket_total{bucket="1_2"} 20
telemt_desync_frames_bucket_total{bucket="3_10"} 33
telemt_desync_frames_bucket_total{bucket="gt_10"} 52
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 1783
telemt_me_writer_restored_same_endpoint_total 1752
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_user_connections_total{user="hello"} 17277
telemt_user_connections_current{user="hello"} 232
telemt_user_octets_from_client{user="hello"} 199011248 (189.79 MB)
telemt_user_octets_to_client{user="hello"} 5190985136 (4.83 GB)
telemt_user_unique_ips_current{user="hello"} 76
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 8923.5 (2h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8384
telemt_connections_bad_total 14
telemt_handshake_timeouts_total 25
telemt_upstream_connect_attempt_total 2479
telemt_upstream_connect_success_total 2479
telemt_upstream_connect_attempts_per_request{bucket="1"} 2479
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1083
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1396
telemt_me_reconnect_attempts_total 2022
telemt_me_reconnect_success_total 2017
telemt_me_reader_eof_total 2133
telemt_me_idle_close_by_peer_total 2133
telemt_me_route_drop_no_conn_total 2633
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7917
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 2027
telemt_me_writer_restored_same_endpoint_total 2001
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 7919
telemt_user_connections_current{user="hello"} 112
telemt_user_octets_from_client{user="hello"} 79396336 (75.72 MB)
telemt_user_octets_to_client{user="hello"} 1478828612 (1.38 GB)
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 8916.1 (2h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8845
telemt_connections_bad_total 79
telemt_handshake_timeouts_total 170
telemt_upstream_connect_attempt_total 2347
telemt_upstream_connect_success_total 2346
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 2347
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1036
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1306
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 1893
telemt_me_reconnect_success_total 1881
telemt_me_reader_eof_total 2012
telemt_me_idle_close_by_peer_total 2012
telemt_me_route_drop_no_conn_total 2836
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8319
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 1890
telemt_me_writer_restored_same_endpoint_total 1877
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 8300
telemt_user_connections_current{user="hello"} 73
telemt_user_octets_from_client{user="hello"} 1091249072 (1.02 GB)
telemt_user_octets_to_client{user="hello"} 10907694696 (10.16 GB)
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 8915.8 (2h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8726
telemt_connections_bad_total 74
telemt_handshake_timeouts_total 34
telemt_upstream_connect_attempt_total 2178
telemt_upstream_connect_success_total 2177
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 2178
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 990
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1184
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 1728
telemt_me_reconnect_success_total 1719
telemt_me_reader_eof_total 1810
telemt_me_idle_close_by_peer_total 1810
telemt_me_route_drop_no_conn_total 3663
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8383
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 42
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 36
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 22
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 1729
telemt_me_writer_restored_same_endpoint_total 1708
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 8383
telemt_user_connections_current{user="hello"} 132
telemt_user_octets_from_client{user="hello"} 200643500 (191.35 MB)
telemt_user_octets_to_client{user="hello"} 6319029016 (5.89 GB)
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 8916.0 (2h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11721
telemt_connections_bad_total 1899
telemt_handshake_timeouts_total 364
telemt_upstream_connect_attempt_total 2888
telemt_upstream_connect_success_total 2851
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 2888
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1380
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1465
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_reconnect_attempts_total 2466
telemt_me_reconnect_success_total 2392
telemt_me_reader_eof_total 2486
telemt_me_idle_close_by_peer_total 2486
telemt_me_route_drop_no_conn_total 2778
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9239
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 2392
telemt_me_refill_failed_total 2
telemt_me_writer_restored_same_endpoint_total 2380
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 29
telemt_user_connections_total{user="hello"} 9227
telemt_user_connections_current{user="hello"} 54
telemt_user_octets_from_client{user="hello"} 152793640 (145.72 MB)
telemt_user_octets_to_client{user="hello"} 5140333840 (4.79 GB)
telemt_user_unique_ips_current{user="hello"} 21
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 8915.0 (2h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 29061
telemt_connections_bad_total 527
telemt_handshake_timeouts_total 107
telemt_upstream_connect_attempt_total 1959
telemt_upstream_connect_success_total 1951
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 1959
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 972
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 979
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 1497
telemt_me_reconnect_success_total 1492
telemt_me_reader_eof_total 1546
telemt_me_idle_close_by_peer_total 1546
telemt_me_route_drop_no_conn_total 16940
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 29058
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
telemt_me_writer_removed_unexpected_total 1478
telemt_me_writer_restored_same_endpoint_total 1465
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_user_connections_total{user="hello"} 27645
telemt_user_connections_current{user="hello"} 250
telemt_user_octets_from_client{user="hello"} 437877832 (417.59 MB)
telemt_user_octets_to_client{user="hello"} 20335816168 (18.94 GB)
telemt_user_unique_ips_current{user="hello"} 111
telemt_user_unique_ips_recent_window{user="hello"} 34
```