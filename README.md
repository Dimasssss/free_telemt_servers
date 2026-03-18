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

## 4vps.su
- Локация: Польша, Варшава
- Тариф: PL-cx21
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 2 Gbit/s
- Цена в месяц: 770 RUB
- Оплачен до: 16 апреля
- Ссылка:
```bash
tg://proxy?server=s7.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-18 22:07:55 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 1168.5 (0h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14648
telemt_connections_bad_total 999
telemt_connections_current 752
telemt_connections_me_current 752
telemt_handshake_timeouts_total 123
telemt_upstream_connect_attempt_total 201
telemt_upstream_connect_success_total 197
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 201
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 122
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 75
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 92
telemt_me_reconnect_success_total 92
telemt_me_reader_eof_total 58
telemt_me_idle_close_by_peer_total 58
telemt_me_route_drop_no_conn_total 3331
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12729
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 51
telemt_desync_full_logged_total 23
telemt_desync_suppressed_total 28
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 16
telemt_desync_frames_bucket_total{bucket="gt_10"} 28
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 80
telemt_me_writer_restored_same_endpoint_total 82
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 136
telemt_user_connections_total{user="hello"} 12728
telemt_user_connections_current{user="hello"} 752
telemt_user_octets_from_client{user="hello"} 140071384 (133.58 MB)
telemt_user_octets_to_client{user="hello"} 2902367640 (2.70 GB)
telemt_user_unique_ips_current{user="hello"} 291
telemt_user_unique_ips_recent_window{user="hello"} 106
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 1172.0 (0h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 40452
telemt_connections_bad_total 1375
telemt_connections_current 2013
telemt_connections_me_current 2013
telemt_handshake_timeouts_total 343
telemt_upstream_connect_attempt_total 176
telemt_upstream_connect_success_total 173
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 176
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 93
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 80
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 63
telemt_me_reconnect_success_total 63
telemt_me_reader_eof_total 45
telemt_me_idle_close_by_peer_total 45
telemt_me_seq_mismatch_total 1
telemt_me_route_drop_no_conn_total 17365
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 37117
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 89
telemt_desync_full_logged_total 30
telemt_desync_suppressed_total 59
telemt_desync_frames_bucket_total{bucket="1_2"} 28
telemt_desync_frames_bucket_total{bucket="3_10"} 24
telemt_desync_frames_bucket_total{bucket="gt_10"} 37
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 68
telemt_me_writer_restored_same_endpoint_total 53
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 37117
telemt_user_connections_current{user="hello"} 2013
telemt_user_octets_from_client{user="hello"} 1049158572 (1000.56 MB)
telemt_user_octets_to_client{user="hello"} 9010429716 (8.39 GB)
telemt_user_unique_ips_current{user="hello"} 731
telemt_user_unique_ips_recent_window{user="hello"} 188
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 1169.6 (0h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 34472
telemt_connections_bad_total 3043
telemt_connections_current 1577
telemt_connections_me_current 1577
telemt_handshake_timeouts_total 660
telemt_upstream_connect_attempt_total 277
telemt_upstream_connect_success_total 277
telemt_upstream_connect_attempts_per_request{bucket="1"} 277
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 165
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 112
telemt_me_reconnect_attempts_total 167
telemt_me_reconnect_success_total 167
telemt_me_reader_eof_total 145
telemt_me_idle_close_by_peer_total 145
telemt_me_route_drop_no_conn_total 11800
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 29758
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 113
telemt_desync_full_logged_total 43
telemt_desync_suppressed_total 70
telemt_desync_frames_bucket_total{bucket="1_2"} 24
telemt_desync_frames_bucket_total{bucket="3_10"} 45
telemt_desync_frames_bucket_total{bucket="gt_10"} 44
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 165
telemt_me_writer_restored_same_endpoint_total 151
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_user_connections_total{user="hello"} 29748
telemt_user_connections_current{user="hello"} 1577
telemt_user_octets_from_client{user="hello"} 356048672 (339.55 MB)
telemt_user_octets_to_client{user="hello"} 17247807216 (16.06 GB)
telemt_user_unique_ips_current{user="hello"} 608
telemt_user_unique_ips_recent_window{user="hello"} 152
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 1222.5 (0h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 42071
telemt_connections_bad_total 3148
telemt_connections_current 1401
telemt_connections_me_current 1401
telemt_handshake_timeouts_total 477
telemt_upstream_connect_attempt_total 261
telemt_upstream_connect_success_total 261
telemt_upstream_connect_attempts_per_request{bucket="1"} 261
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 157
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 103
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 154
telemt_me_reconnect_success_total 154
telemt_me_reader_eof_total 135
telemt_me_idle_close_by_peer_total 135
telemt_me_route_drop_no_conn_total 28417
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 36981
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 82
telemt_desync_full_logged_total 27
telemt_desync_suppressed_total 55
telemt_desync_frames_bucket_total{bucket="1_2"} 17
telemt_desync_frames_bucket_total{bucket="3_10"} 34
telemt_desync_frames_bucket_total{bucket="gt_10"} 31
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 155
telemt_me_writer_restored_same_endpoint_total 130
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 268
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 36945
telemt_user_connections_current{user="hello"} 1401
telemt_user_octets_from_client{user="hello"} 281303820 (268.27 MB)
telemt_user_octets_to_client{user="hello"} 6372030392 (5.93 GB)
telemt_user_unique_ips_current{user="hello"} 550
telemt_user_unique_ips_recent_window{user="hello"} 163
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 1165.8 (0h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 35340
telemt_connections_bad_total 1533
telemt_connections_current 1641
telemt_connections_me_current 1641
telemt_handshake_timeouts_total 888
telemt_upstream_connect_attempt_total 215
telemt_upstream_connect_success_total 212
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 215
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 121
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 100
telemt_me_reconnect_success_total 100
telemt_me_reader_eof_total 73
telemt_me_idle_close_by_peer_total 73
telemt_me_route_drop_no_conn_total 8583
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 28282
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 133
telemt_desync_full_logged_total 57
telemt_desync_suppressed_total 76
telemt_desync_frames_bucket_total{bucket="1_2"} 28
telemt_desync_frames_bucket_total{bucket="3_10"} 45
telemt_desync_frames_bucket_total{bucket="gt_10"} 60
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 94
telemt_me_writer_restored_same_endpoint_total 76
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_user_connections_total{user="hello"} 28271
telemt_user_connections_current{user="hello"} 1641
telemt_user_octets_from_client{user="hello"} 253336188 (241.60 MB)
telemt_user_octets_to_client{user="hello"} 19912373368 (18.54 GB)
telemt_user_unique_ips_current{user="hello"} 658
telemt_user_unique_ips_recent_window{user="hello"} 158
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 1177.3 (0h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8216
telemt_connections_bad_total 2357
telemt_connections_current 441
telemt_connections_me_current 441
telemt_handshake_timeouts_total 10
telemt_upstream_connect_attempt_total 341
telemt_upstream_connect_success_total 329
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 341
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 222
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 107
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_reconnect_attempts_total 225
telemt_me_reconnect_success_total 224
telemt_me_reader_eof_total 164
telemt_me_idle_close_by_peer_total 164
telemt_me_route_drop_no_conn_total 2059
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5663
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 24
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 18
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 10
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_me_writer_removed_unexpected_total 186
telemt_me_writer_restored_same_endpoint_total 194
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_user_connections_total{user="hello"} 5663
telemt_user_connections_current{user="hello"} 441
telemt_user_octets_from_client{user="hello"} 158901192 (151.54 MB)
telemt_user_octets_to_client{user="hello"} 2511191164 (2.34 GB)
telemt_user_unique_ips_current{user="hello"} 177
telemt_user_unique_ips_recent_window{user="hello"} 57
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 1168.1 (0h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 28612
telemt_connections_bad_total 4311
telemt_connections_current 1558
telemt_connections_me_current 1558
telemt_handshake_timeouts_total 754
telemt_upstream_connect_attempt_total 218
telemt_upstream_connect_success_total 218
telemt_upstream_connect_attempts_per_request{bucket="1"} 218
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 132
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 86
telemt_me_reconnect_attempts_total 107
telemt_me_reconnect_success_total 107
telemt_me_reader_eof_total 89
telemt_me_idle_close_by_peer_total 89
telemt_me_route_drop_no_conn_total 6443
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 22734
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 188
telemt_desync_full_logged_total 67
telemt_desync_suppressed_total 121
telemt_desync_frames_bucket_total{bucket="1_2"} 36
telemt_desync_frames_bucket_total{bucket="3_10"} 72
telemt_desync_frames_bucket_total{bucket="gt_10"} 80
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 109
telemt_me_writer_restored_same_endpoint_total 92
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 22734
telemt_user_connections_current{user="hello"} 1558
telemt_user_octets_from_client{user="hello"} 274081760 (261.38 MB)
telemt_user_octets_to_client{user="hello"} 15099744536 (14.06 GB)
telemt_user_unique_ips_current{user="hello"} 596
telemt_user_unique_ips_recent_window{user="hello"} 159
```