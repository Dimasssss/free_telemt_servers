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

# Server Metrics 2026-03-16 18:58:26 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 785.4 (0h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6064
telemt_connections_bad_total 64
telemt_handshake_timeouts_total 67
telemt_upstream_connect_attempt_total 162
telemt_upstream_connect_success_total 161
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 162
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 88
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 73
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 94
telemt_me_reconnect_success_total 94
telemt_me_reader_eof_total 61
telemt_me_idle_close_by_peer_total 61
telemt_me_route_drop_no_conn_total 1854
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5755
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 62
telemt_desync_full_logged_total 12
telemt_desync_suppressed_total 50
telemt_desync_frames_bucket_total{bucket="1_2"} 27
telemt_desync_frames_bucket_total{bucket="3_10"} 15
telemt_desync_frames_bucket_total{bucket="gt_10"} 20
telemt_me_writer_removed_unexpected_total 83
telemt_me_writer_restored_same_endpoint_total 73
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 46
telemt_user_connections_total{user="hello"} 5751
telemt_user_connections_current{user="hello"} 611
telemt_user_octets_from_client{user="hello"} 116278440 (110.89 MB)
telemt_user_octets_to_client{user="hello"} 4030393048 (3.75 GB)
telemt_user_unique_ips_current{user="hello"} 191
telemt_user_unique_ips_recent_window{user="hello"} 55
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 1036.7 (0h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7421
telemt_connections_bad_total 2
telemt_handshake_timeouts_total 97
telemt_upstream_connect_attempt_total 163
telemt_upstream_connect_success_total 158
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 163
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 84
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 62
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_reconnect_attempts_total 49
telemt_me_reconnect_success_total 49
telemt_me_reader_eof_total 22
telemt_me_idle_close_by_peer_total 22
telemt_me_route_drop_no_conn_total 3319
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7052
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16
telemt_desync_full_logged_total 4
telemt_desync_suppressed_total 12
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 7
telemt_desync_frames_bucket_total{bucket="gt_10"} 4
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 45
telemt_me_writer_restored_same_endpoint_total 33
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_user_connections_total{user="hello"} 7052
telemt_user_connections_current{user="hello"} 388
telemt_user_octets_from_client{user="hello"} 64165920 (61.19 MB)
telemt_user_octets_to_client{user="hello"} 2392597064 (2.23 GB)
telemt_user_unique_ips_current{user="hello"} 116
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 812.6 (0h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2872
telemt_handshake_timeouts_total 9
telemt_upstream_connect_attempt_total 112
telemt_upstream_connect_success_total 111
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 112
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 51
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 44
telemt_me_reconnect_success_total 44
telemt_me_reader_eof_total 20
telemt_me_idle_close_by_peer_total 20
telemt_me_route_drop_no_conn_total 806
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2792
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 20
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_writer_removed_unexpected_total 40
telemt_me_writer_restored_same_endpoint_total 33
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_user_connections_total{user="hello"} 2792
telemt_user_connections_current{user="hello"} 217
telemt_user_octets_from_client{user="hello"} 38055464 (36.29 MB)
telemt_user_octets_to_client{user="hello"} 1241911840 (1.16 GB)
telemt_user_unique_ips_current{user="hello"} 78
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 872.0 (0h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7126
telemt_connections_bad_total 22
telemt_handshake_timeouts_total 54
telemt_upstream_connect_attempt_total 101
telemt_upstream_connect_success_total 100
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 101
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 59
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 30
telemt_me_reconnect_success_total 30
telemt_me_reader_eof_total 4
telemt_me_idle_close_by_peer_total 4
telemt_me_route_drop_no_conn_total 1642
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6750
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_desync_total 26
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 17
telemt_desync_frames_bucket_total{bucket="1_2"} 8
telemt_desync_frames_bucket_total{bucket="3_10"} 6
telemt_desync_frames_bucket_total{bucket="gt_10"} 12
telemt_me_writer_removed_unexpected_total 26
telemt_me_writer_restored_same_endpoint_total 23
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 270
telemt_user_connections_total{user="hello"} 6748
telemt_user_connections_current{user="hello"} 360
telemt_user_octets_from_client{user="hello"} 74400476 (70.95 MB)
telemt_user_octets_to_client{user="hello"} 2073763944 (1.93 GB)
telemt_user_unique_ips_current{user="hello"} 118
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 843.9 (0h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3518
telemt_connections_bad_total 968
telemt_handshake_timeouts_total 6
telemt_upstream_connect_attempt_total 174
telemt_upstream_connect_success_total 171
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 174
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 121
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 106
telemt_me_reconnect_success_total 105
telemt_me_reader_eof_total 64
telemt_me_idle_close_by_peer_total 64
telemt_me_route_drop_no_conn_total 792
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2383
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_writer_removed_unexpected_total 86
telemt_me_writer_restored_same_endpoint_total 97
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_user_connections_total{user="hello"} 2383
telemt_user_connections_current{user="hello"} 222
telemt_user_octets_from_client{user="hello"} 11773960 (11.23 MB)
telemt_user_octets_to_client{user="hello"} 471708488 (449.86 MB)
telemt_user_unique_ips_current{user="hello"} 76
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 1005.2 (0h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10914
telemt_connections_bad_total 27
telemt_handshake_timeouts_total 39
telemt_upstream_connect_attempt_total 129
telemt_upstream_connect_success_total 127
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 129
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 72
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 55
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 18
telemt_me_reconnect_success_total 18
telemt_me_route_drop_no_conn_total 4048
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10463
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2
telemt_desync_full_logged_total 1
telemt_desync_suppressed_total 1
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 22
telemt_me_writer_restored_same_endpoint_total 8
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 10461
telemt_user_connections_current{user="hello"} 699
telemt_user_octets_from_client{user="hello"} 78059856 (74.44 MB)
telemt_user_octets_to_client{user="hello"} 4360128232 (4.06 GB)
telemt_user_unique_ips_current{user="hello"} 236
telemt_user_unique_ips_recent_window{user="hello"} 97
```