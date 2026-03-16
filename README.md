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

# Server Metrics 2026-03-16 19:03:32 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 1090.9 (0h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8777
telemt_connections_bad_total 85
telemt_handshake_timeouts_total 151
telemt_upstream_connect_attempt_total 238
telemt_upstream_connect_success_total 234
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 238
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 129
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 105
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 124
telemt_me_reconnect_success_total 124
telemt_me_reader_eof_total 92
telemt_me_idle_close_by_peer_total 92
telemt_me_route_drop_no_conn_total 2559
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8167
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 67
telemt_desync_full_logged_total 15
telemt_desync_suppressed_total 52
telemt_desync_frames_bucket_total{bucket="1_2"} 32
telemt_desync_frames_bucket_total{bucket="3_10"} 15
telemt_desync_frames_bucket_total{bucket="gt_10"} 20
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 113
telemt_me_writer_restored_same_endpoint_total 103
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 46
telemt_user_connections_total{user="hello"} 8163
telemt_user_connections_current{user="hello"} 684
telemt_user_octets_from_client{user="hello"} 160523028 (153.09 MB)
telemt_user_octets_to_client{user="hello"} 6373509408 (5.94 GB)
telemt_user_unique_ips_current{user="hello"} 198
telemt_user_unique_ips_recent_window{user="hello"} 72
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 1342.2 (0h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9339
telemt_connections_bad_total 2
telemt_handshake_timeouts_total 199
telemt_upstream_connect_attempt_total 215
telemt_upstream_connect_success_total 210
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 215
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 101
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 92
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_reconnect_attempts_total 101
telemt_me_reconnect_success_total 101
telemt_me_reader_eof_total 76
telemt_me_idle_close_by_peer_total 76
telemt_me_route_drop_no_conn_total 4135
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8835
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 20
telemt_desync_full_logged_total 7
telemt_desync_suppressed_total 13
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 8
telemt_desync_frames_bucket_total{bucket="gt_10"} 6
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 99
telemt_me_writer_restored_same_endpoint_total 85
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_user_connections_total{user="hello"} 8835
telemt_user_connections_current{user="hello"} 411
telemt_user_octets_from_client{user="hello"} 73950028 (70.52 MB)
telemt_user_octets_to_client{user="hello"} 3102378196 (2.89 GB)
telemt_user_unique_ips_current{user="hello"} 124
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 1118.4 (0h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4099
telemt_handshake_timeouts_total 9
telemt_upstream_connect_attempt_total 202
telemt_upstream_connect_success_total 200
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 202
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 96
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 103
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 90
telemt_me_reconnect_success_total 90
telemt_me_reader_eof_total 65
telemt_me_idle_close_by_peer_total 65
telemt_me_route_drop_no_conn_total 1132
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3994
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 86
telemt_me_writer_restored_same_endpoint_total 79
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_user_connections_total{user="hello"} 3994
telemt_user_connections_current{user="hello"} 212
telemt_user_octets_from_client{user="hello"} 107544920 (102.56 MB)
telemt_user_octets_to_client{user="hello"} 1617493648 (1.51 GB)
telemt_user_unique_ips_current{user="hello"} 80
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 1177.8 (0h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9277
telemt_connections_bad_total 22
telemt_handshake_timeouts_total 57
telemt_upstream_connect_attempt_total 209
telemt_upstream_connect_success_total 204
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 209
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 117
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 86
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_reconnect_attempts_total 90
telemt_me_reconnect_success_total 89
telemt_me_reader_eof_total 63
telemt_me_idle_close_by_peer_total 63
telemt_me_route_drop_no_conn_total 2360
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8815
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 27
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 17
telemt_desync_frames_bucket_total{bucket="1_2"} 8
telemt_desync_frames_bucket_total{bucket="3_10"} 7
telemt_desync_frames_bucket_total{bucket="gt_10"} 12
telemt_me_writer_removed_unexpected_total 85
telemt_me_writer_restored_same_endpoint_total 82
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 270
telemt_user_connections_total{user="hello"} 8813
telemt_user_connections_current{user="hello"} 431
telemt_user_octets_from_client{user="hello"} 111077804 (105.93 MB)
telemt_user_octets_to_client{user="hello"} 2895302468 (2.70 GB)
telemt_user_unique_ips_current{user="hello"} 122
telemt_user_unique_ips_recent_window{user="hello"} 56
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 1149.7 (0h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4891
telemt_connections_bad_total 1318
telemt_handshake_timeouts_total 11
telemt_upstream_connect_attempt_total 277
telemt_upstream_connect_success_total 272
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 277
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 174
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 85
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_reconnect_attempts_total 164
telemt_me_reconnect_success_total 163
telemt_me_reader_eof_total 127
telemt_me_idle_close_by_peer_total 127
telemt_me_route_drop_no_conn_total 1227
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3350
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9
telemt_desync_full_logged_total 3
telemt_desync_suppressed_total 6
telemt_desync_frames_bucket_total{bucket="3_10"} 4
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 144
telemt_me_writer_restored_same_endpoint_total 155
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_user_connections_total{user="hello"} 3350
telemt_user_connections_current{user="hello"} 191
telemt_user_octets_from_client{user="hello"} 26957100 (25.71 MB)
telemt_user_octets_to_client{user="hello"} 751009752 (716.22 MB)
telemt_user_unique_ips_current{user="hello"} 70
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 1311.3 (0h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13916
telemt_connections_bad_total 27
telemt_handshake_timeouts_total 40
telemt_upstream_connect_attempt_total 195
telemt_upstream_connect_success_total 193
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 195
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 100
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 93
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 84
telemt_me_reconnect_success_total 84
telemt_me_reader_eof_total 66
telemt_me_idle_close_by_peer_total 66
telemt_me_route_drop_no_conn_total 5788
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13394
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
telemt_me_writer_removed_unexpected_total 88
telemt_me_writer_restored_same_endpoint_total 74
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 13391
telemt_user_connections_current{user="hello"} 652
telemt_user_octets_from_client{user="hello"} 107632444 (102.65 MB)
telemt_user_octets_to_client{user="hello"} 5287434056 (4.92 GB)
telemt_user_unique_ips_current{user="hello"} 221
telemt_user_unique_ips_recent_window{user="hello"} 87
```