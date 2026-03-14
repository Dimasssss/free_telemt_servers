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

# Server Metrics 2026-03-14 23:36:56 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 4948.3 (1h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9727
telemt_connections_bad_total 241
telemt_handshake_timeouts_total 180
telemt_upstream_connect_attempt_total 1303
telemt_upstream_connect_success_total 1296
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 1303
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 618
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 674
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_reconnect_attempts_total 1017
telemt_me_reconnect_success_total 1012
telemt_me_reader_eof_total 1041
telemt_me_idle_close_by_peer_total 1041
telemt_me_route_drop_no_conn_total 2666
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8898
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 45
telemt_desync_full_logged_total 18
telemt_desync_suppressed_total 27
telemt_desync_frames_bucket_total{bucket="1_2"} 11
telemt_desync_frames_bucket_total{bucket="3_10"} 14
telemt_desync_frames_bucket_total{bucket="gt_10"} 20
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 1006
telemt_me_writer_restored_same_endpoint_total 981
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_user_connections_total{user="hello"} 8897
telemt_user_connections_current{user="hello"} 209
telemt_user_octets_from_client{user="hello"} 84536824 (80.62 MB)
telemt_user_octets_to_client{user="hello"} 2662721468 (2.48 GB)
telemt_user_unique_ips_current{user="hello"} 69
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 4954.7 (1h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4071
telemt_connections_bad_total 9
telemt_handshake_timeouts_total 14
telemt_upstream_connect_attempt_total 1419
telemt_upstream_connect_success_total 1419
telemt_upstream_connect_attempts_per_request{bucket="1"} 1419
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 635
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 784
telemt_me_reconnect_attempts_total 1134
telemt_me_reconnect_success_total 1131
telemt_me_reader_eof_total 1182
telemt_me_idle_close_by_peer_total 1182
telemt_me_route_drop_no_conn_total 1481
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3827
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 1134
telemt_me_writer_restored_same_endpoint_total 1115
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 3828
telemt_user_connections_current{user="hello"} 106
telemt_user_octets_from_client{user="hello"} 40604112 (38.72 MB)
telemt_user_octets_to_client{user="hello"} 633749664 (604.39 MB)
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 4947.4 (1h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4809
telemt_connections_bad_total 20
telemt_handshake_timeouts_total 66
telemt_upstream_connect_attempt_total 1327
telemt_upstream_connect_success_total 1326
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 1327
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 592
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 730
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 1045
telemt_me_reconnect_success_total 1035
telemt_me_reader_eof_total 1096
telemt_me_idle_close_by_peer_total 1096
telemt_me_route_drop_no_conn_total 1529
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4560
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 1034
telemt_me_writer_restored_same_endpoint_total 1031
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 14
telemt_user_connections_total{user="hello"} 4551
telemt_user_connections_current{user="hello"} 53
telemt_user_octets_from_client{user="hello"} 1020708784 (973.42 MB)
telemt_user_octets_to_client{user="hello"} 8798721676 (8.19 GB)
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 4947.0 (1h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4476
telemt_connections_bad_total 12
telemt_handshake_timeouts_total 15
telemt_upstream_connect_attempt_total 1224
telemt_upstream_connect_success_total 1223
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 1224
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 564
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 657
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 946
telemt_me_reconnect_success_total 940
telemt_me_reader_eof_total 974
telemt_me_idle_close_by_peer_total 974
telemt_me_route_drop_no_conn_total 2114
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4321
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
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 940
telemt_me_writer_restored_same_endpoint_total 929
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_user_connections_total{user="hello"} 4321
telemt_user_connections_current{user="hello"} 121
telemt_user_octets_from_client{user="hello"} 99218896 (94.62 MB)
telemt_user_octets_to_client{user="hello"} 4717084720 (4.39 GB)
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 4947.2 (1h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6184
telemt_connections_bad_total 1149
telemt_handshake_timeouts_total 329
telemt_upstream_connect_attempt_total 1821
telemt_upstream_connect_success_total 1799
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 1821
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 910
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 885
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_reconnect_attempts_total 1586
telemt_me_reconnect_success_total 1517
telemt_me_reader_eof_total 1552
telemt_me_idle_close_by_peer_total 1552
telemt_me_route_drop_no_conn_total 1326
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4596
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 1511
telemt_me_refill_failed_total 2
telemt_me_writer_restored_same_endpoint_total 1505
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 29
telemt_user_connections_total{user="hello"} 4591
telemt_user_connections_current{user="hello"} 55
telemt_user_octets_from_client{user="hello"} 47003104 (44.83 MB)
telemt_user_octets_to_client{user="hello"} 3580987760 (3.34 GB)
telemt_user_unique_ips_current{user="hello"} 17
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 4946.2 (1h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16148
telemt_connections_bad_total 370
telemt_handshake_timeouts_total 67
telemt_upstream_connect_attempt_total 1173
telemt_upstream_connect_success_total 1168
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 1173
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 569
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 599
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_reconnect_attempts_total 887
telemt_me_reconnect_success_total 885
telemt_me_reader_eof_total 894
telemt_me_idle_close_by_peer_total 894
telemt_me_route_drop_no_conn_total 8531
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 15694
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 15
telemt_desync_full_logged_total 4
telemt_desync_suppressed_total 11
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 4
telemt_desync_frames_bucket_total{bucket="gt_10"} 6
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 864
telemt_me_writer_restored_same_endpoint_total 858
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_user_connections_total{user="hello"} 15230
telemt_user_connections_current{user="hello"} 299
telemt_user_octets_from_client{user="hello"} 287437324 (274.12 MB)
telemt_user_octets_to_client{user="hello"} 13236877244 (12.33 GB)
telemt_user_unique_ips_current{user="hello"} 127
telemt_user_unique_ips_recent_window{user="hello"} 28
```