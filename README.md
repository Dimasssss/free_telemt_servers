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

# Server Metrics 2026-03-18 22:13:03 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 1476.0 (0h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18529
telemt_connections_bad_total 1252
telemt_connections_current 716
telemt_connections_me_current 716
telemt_handshake_timeouts_total 145
telemt_upstream_connect_attempt_total 239
telemt_upstream_connect_success_total 235
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 239
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 135
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 130
telemt_me_reconnect_success_total 130
telemt_me_reader_eof_total 98
telemt_me_idle_close_by_peer_total 98
telemt_me_route_drop_no_conn_total 4413
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16158
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 56
telemt_desync_full_logged_total 25
telemt_desync_suppressed_total 31
telemt_desync_frames_bucket_total{bucket="1_2"} 9
telemt_desync_frames_bucket_total{bucket="3_10"} 18
telemt_desync_frames_bucket_total{bucket="gt_10"} 29
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 120
telemt_me_writer_restored_same_endpoint_total 120
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 136
telemt_user_connections_total{user="hello"} 16157
telemt_user_connections_current{user="hello"} 716
telemt_user_octets_from_client{user="hello"} 159467792 (152.08 MB)
telemt_user_octets_to_client{user="hello"} 3810811112 (3.55 GB)
telemt_user_unique_ips_current{user="hello"} 280
telemt_user_unique_ips_recent_window{user="hello"} 80
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 1479.6 (0h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 49810
telemt_connections_bad_total 1469
telemt_connections_current 2037
telemt_connections_me_current 2037
telemt_handshake_timeouts_total 416
telemt_upstream_connect_attempt_total 214
telemt_upstream_connect_success_total 211
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 214
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 106
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 104
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 101
telemt_me_reconnect_success_total 101
telemt_me_reader_eof_total 83
telemt_me_idle_close_by_peer_total 83
telemt_me_seq_mismatch_total 1
telemt_me_route_drop_no_conn_total 20113
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 45691
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 110
telemt_desync_full_logged_total 41
telemt_desync_suppressed_total 69
telemt_desync_frames_bucket_total{bucket="1_2"} 29
telemt_desync_frames_bucket_total{bucket="3_10"} 39
telemt_desync_frames_bucket_total{bucket="gt_10"} 42
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 106
telemt_me_writer_restored_same_endpoint_total 91
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 45690
telemt_user_connections_current{user="hello"} 2037
telemt_user_octets_from_client{user="hello"} 1636162580 (1.52 GB)
telemt_user_octets_to_client{user="hello"} 12898650616 (12.01 GB)
telemt_user_unique_ips_current{user="hello"} 743
telemt_user_unique_ips_recent_window{user="hello"} 207
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 1476.9 (0h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 42093
telemt_connections_bad_total 4100
telemt_connections_current 1579
telemt_connections_me_current 1579
telemt_handshake_timeouts_total 827
telemt_upstream_connect_attempt_total 313
telemt_upstream_connect_success_total 313
telemt_upstream_connect_attempts_per_request{bucket="1"} 313
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 180
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 133
telemt_me_reconnect_attempts_total 203
telemt_me_reconnect_success_total 203
telemt_me_reader_eof_total 181
telemt_me_idle_close_by_peer_total 181
telemt_me_route_drop_no_conn_total 14927
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 35985
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 130
telemt_desync_full_logged_total 51
telemt_desync_suppressed_total 79
telemt_desync_frames_bucket_total{bucket="1_2"} 25
telemt_desync_frames_bucket_total{bucket="3_10"} 50
telemt_desync_frames_bucket_total{bucket="gt_10"} 55
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 201
telemt_me_writer_restored_same_endpoint_total 187
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_user_connections_total{user="hello"} 35978
telemt_user_connections_current{user="hello"} 1579
telemt_user_octets_from_client{user="hello"} 409565256 (390.59 MB)
telemt_user_octets_to_client{user="hello"} 21604950628 (20.12 GB)
telemt_user_unique_ips_current{user="hello"} 608
telemt_user_unique_ips_recent_window{user="hello"} 174
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 1530.0 (0h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 48795
telemt_connections_bad_total 3274
telemt_connections_current 1306
telemt_connections_me_current 1306
telemt_handshake_timeouts_total 565
telemt_upstream_connect_attempt_total 289
telemt_upstream_connect_success_total 289
telemt_upstream_connect_attempts_per_request{bucket="1"} 289
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 165
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 123
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 182
telemt_me_reconnect_success_total 181
telemt_me_reader_eof_total 163
telemt_me_idle_close_by_peer_total 163
telemt_me_route_drop_no_conn_total 30816
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 42837
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 92
telemt_desync_full_logged_total 33
telemt_desync_suppressed_total 59
telemt_desync_frames_bucket_total{bucket="1_2"} 19
telemt_desync_frames_bucket_total{bucket="3_10"} 40
telemt_desync_frames_bucket_total{bucket="gt_10"} 33
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 183
telemt_me_writer_restored_same_endpoint_total 157
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 268
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 42785
telemt_user_connections_current{user="hello"} 1306
telemt_user_octets_from_client{user="hello"} 323134452 (308.17 MB)
telemt_user_octets_to_client{user="hello"} 8418281744 (7.84 GB)
telemt_user_unique_ips_current{user="hello"} 540
telemt_user_unique_ips_recent_window{user="hello"} 154
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 1473.4 (0h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 43778
telemt_connections_bad_total 1885
telemt_connections_current 1631
telemt_connections_me_current 1631
telemt_handshake_timeouts_total 1106
telemt_upstream_connect_attempt_total 252
telemt_upstream_connect_success_total 249
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 252
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 138
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 111
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 137
telemt_me_reconnect_success_total 136
telemt_me_reader_eof_total 109
telemt_me_idle_close_by_peer_total 109
telemt_me_route_drop_no_conn_total 11328
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 35030
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 154
telemt_desync_full_logged_total 68
telemt_desync_suppressed_total 86
telemt_desync_frames_bucket_total{bucket="1_2"} 38
telemt_desync_frames_bucket_total{bucket="3_10"} 53
telemt_desync_frames_bucket_total{bucket="gt_10"} 63
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 130
telemt_me_writer_restored_same_endpoint_total 112
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_user_connections_total{user="hello"} 35019
telemt_user_connections_current{user="hello"} 1631
telemt_user_octets_from_client{user="hello"} 370068464 (352.92 MB)
telemt_user_octets_to_client{user="hello"} 23719026960 (22.09 GB)
telemt_user_unique_ips_current{user="hello"} 660
telemt_user_unique_ips_recent_window{user="hello"} 178
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 1484.9 (0h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9479
telemt_connections_bad_total 2418
telemt_connections_current 417
telemt_connections_me_current 417
telemt_handshake_timeouts_total 11
telemt_upstream_connect_attempt_total 420
telemt_upstream_connect_success_total 408
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 420
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 266
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 142
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_reconnect_attempts_total 304
telemt_me_reconnect_success_total 302
telemt_me_reader_eof_total 244
telemt_me_idle_close_by_peer_total 244
telemt_me_route_drop_no_conn_total 2542
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6850
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
telemt_me_writer_removed_unexpected_total 266
telemt_me_writer_restored_same_endpoint_total 272
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_user_connections_total{user="hello"} 6850
telemt_user_connections_current{user="hello"} 417
telemt_user_octets_from_client{user="hello"} 165777472 (158.10 MB)
telemt_user_octets_to_client{user="hello"} 3098832612 (2.89 GB)
telemt_user_unique_ips_current{user="hello"} 173
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 1475.8 (0h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 34849
telemt_connections_bad_total 5465
telemt_connections_current 1505
telemt_connections_me_current 1505
telemt_handshake_timeouts_total 911
telemt_upstream_connect_attempt_total 255
telemt_upstream_connect_success_total 255
telemt_upstream_connect_attempts_per_request{bucket="1"} 255
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 147
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 108
telemt_me_reconnect_attempts_total 144
telemt_me_reconnect_success_total 144
telemt_me_reader_eof_total 127
telemt_me_idle_close_by_peer_total 127
telemt_me_route_drop_no_conn_total 8032
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 27599
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 256
telemt_desync_full_logged_total 85
telemt_desync_suppressed_total 171
telemt_desync_frames_bucket_total{bucket="1_2"} 58
telemt_desync_frames_bucket_total{bucket="3_10"} 96
telemt_desync_frames_bucket_total{bucket="gt_10"} 102
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 147
telemt_me_writer_restored_same_endpoint_total 129
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 27599
telemt_user_connections_current{user="hello"} 1505
telemt_user_octets_from_client{user="hello"} 332552984 (317.15 MB)
telemt_user_octets_to_client{user="hello"} 19365815576 (18.04 GB)
telemt_user_unique_ips_current{user="hello"} 588
telemt_user_unique_ips_recent_window{user="hello"} 143
```