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

# Server Metrics 2026-03-15 00:32:54 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 8306.6 (2h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17394
telemt_connections_bad_total 359
telemt_handshake_timeouts_total 235
telemt_upstream_connect_attempt_total 2127
telemt_upstream_connect_success_total 2116
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 2127
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1003
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1109
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_reconnect_attempts_total 1665
telemt_me_reconnect_success_total 1656
telemt_me_reader_eof_total 1737
telemt_me_idle_close_by_peer_total 1737
telemt_me_route_drop_no_conn_total 4724
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16216
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
telemt_me_writer_removed_unexpected_total 1655
telemt_me_writer_restored_same_endpoint_total 1625
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_user_connections_total{user="hello"} 16215
telemt_user_connections_current{user="hello"} 257
telemt_user_octets_from_client{user="hello"} 191422480 (182.55 MB)
telemt_user_octets_to_client{user="hello"} 5031986476 (4.69 GB)
telemt_user_unique_ips_current{user="hello"} 77
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 8313.1 (2h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7830
telemt_connections_bad_total 12
telemt_handshake_timeouts_total 23
telemt_upstream_connect_attempt_total 2343
telemt_upstream_connect_success_total 2343
telemt_upstream_connect_attempts_per_request{bucket="1"} 2343
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1035
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1308
telemt_me_reconnect_attempts_total 1886
telemt_me_reconnect_success_total 1881
telemt_me_reader_eof_total 1995
telemt_me_idle_close_by_peer_total 1995
telemt_me_route_drop_no_conn_total 2451
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7406
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 1889
telemt_me_writer_restored_same_endpoint_total 1865
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 8
telemt_user_connections_total{user="hello"} 7407
telemt_user_connections_current{user="hello"} 110
telemt_user_octets_from_client{user="hello"} 75340880 (71.85 MB)
telemt_user_octets_to_client{user="hello"} 1433636948 (1.34 GB)
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 8305.7 (2h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8208
telemt_connections_bad_total 72
telemt_handshake_timeouts_total 153
telemt_upstream_connect_attempt_total 2217
telemt_upstream_connect_success_total 2215
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 2216
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 979
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1232
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 1763
telemt_me_reconnect_success_total 1750
telemt_me_reader_eof_total 1881
telemt_me_idle_close_by_peer_total 1881
telemt_me_route_drop_no_conn_total 2641
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7730
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 1759
telemt_me_writer_restored_same_endpoint_total 1746
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 7711
telemt_user_connections_current{user="hello"} 98
telemt_user_octets_from_client{user="hello"} 1050603404 (1001.93 MB)
telemt_user_octets_to_client{user="hello"} 10836474652 (10.09 GB)
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 8305.4 (2h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8017
telemt_connections_bad_total 56
telemt_handshake_timeouts_total 34
telemt_upstream_connect_attempt_total 2064
telemt_upstream_connect_success_total 2063
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 2064
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 943
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1117
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 1614
telemt_me_reconnect_success_total 1605
telemt_me_reader_eof_total 1694
telemt_me_idle_close_by_peer_total 1694
telemt_me_route_drop_no_conn_total 3383
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7711
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 33
telemt_desync_full_logged_total 3
telemt_desync_suppressed_total 30
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 18
telemt_desync_frames_bucket_total{bucket="gt_10"} 13
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 1613
telemt_me_writer_restored_same_endpoint_total 1594
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 8
telemt_user_connections_total{user="hello"} 7711
telemt_user_connections_current{user="hello"} 138
telemt_user_octets_from_client{user="hello"} 189708424 (180.92 MB)
telemt_user_octets_to_client{user="hello"} 6126389096 (5.71 GB)
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 8305.5 (2h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10779
telemt_connections_bad_total 1783
telemt_handshake_timeouts_total 361
telemt_upstream_connect_attempt_total 2740
telemt_upstream_connect_success_total 2703
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 2740
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1329
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1370
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_reconnect_attempts_total 2318
telemt_me_reconnect_success_total 2246
telemt_me_reader_eof_total 2340
telemt_me_idle_close_by_peer_total 2340
telemt_me_route_drop_no_conn_total 2597
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8427
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 2246
telemt_me_refill_failed_total 2
telemt_me_writer_restored_same_endpoint_total 2234
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 29
telemt_user_connections_total{user="hello"} 8420
telemt_user_connections_current{user="hello"} 71
telemt_user_octets_from_client{user="hello"} 99271980 (94.67 MB)
telemt_user_octets_to_client{user="hello"} 4486047016 (4.18 GB)
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 8304.5 (2h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 27264
telemt_connections_bad_total 396
telemt_handshake_timeouts_total 98
telemt_upstream_connect_attempt_total 1867
telemt_upstream_connect_success_total 1859
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 1867
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 930
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 929
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 1405
telemt_me_reconnect_success_total 1401
telemt_me_reader_eof_total 1454
telemt_me_idle_close_by_peer_total 1454
telemt_me_route_drop_no_conn_total 15790
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 27434
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
telemt_me_writer_removed_unexpected_total 1386
telemt_me_writer_restored_same_endpoint_total 1374
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_user_connections_total{user="hello"} 26021
telemt_user_connections_current{user="hello"} 255
telemt_user_octets_from_client{user="hello"} 427428032 (407.63 MB)
telemt_user_octets_to_client{user="hello"} 20024643820 (18.65 GB)
telemt_user_unique_ips_current{user="hello"} 124
telemt_user_unique_ips_recent_window{user="hello"} 31
```