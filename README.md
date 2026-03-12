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

# Server Metrics 2026-03-12 07:56:54 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 1411.7 (0h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10028
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 1669
telemt_upstream_connect_attempt_total 311
telemt_upstream_connect_success_total 309
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 311
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 155
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 153
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 31
telemt_me_reconnect_attempts_total 202
telemt_me_reconnect_success_total 202
telemt_me_reader_eof_total 172
telemt_me_idle_close_by_peer_total 172
telemt_me_route_drop_no_conn_total 2280
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7796
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 50
telemt_desync_full_logged_total 15
telemt_desync_suppressed_total 35
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 22
telemt_desync_frames_bucket_total{bucket="gt_10"} 22
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 192
telemt_me_writer_restored_same_endpoint_total 186
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_user_connections_total{user="hello"} 7795
telemt_user_connections_current{user="hello"} 326
telemt_user_octets_from_client{user="hello"} 60675252 (57.86 MB)
telemt_user_octets_to_client{user="hello"} 2047010248 (1.91 GB)
telemt_user_unique_ips_current{user="hello"} 95
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 1304.6 (0h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2797
telemt_connections_bad_total 4
telemt_handshake_timeouts_total 13
telemt_upstream_connect_attempt_total 433
telemt_upstream_connect_success_total 419
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 433
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 147
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 272
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 314
telemt_me_reconnect_success_total 313
telemt_me_reader_eof_total 267
telemt_me_idle_close_by_peer_total 267
telemt_me_route_drop_no_conn_total 924
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2679
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_writer_removed_unexpected_total 290
telemt_me_writer_restored_same_endpoint_total 298
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_user_connections_total{user="hello"} 2678
telemt_user_connections_current{user="hello"} 138
telemt_user_octets_from_client{user="hello"} 9537220 (9.10 MB)
telemt_user_octets_to_client{user="hello"} 272815228 (260.18 MB)
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 1268.2 (0h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4027
telemt_connections_bad_total 3
telemt_handshake_timeouts_total 25
telemt_upstream_connect_attempt_total 306
telemt_upstream_connect_success_total 306
telemt_upstream_connect_attempts_per_request{bucket="1"} 306
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 173
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 133
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 199
telemt_me_reconnect_success_total 198
telemt_me_reader_eof_total 162
telemt_me_idle_close_by_peer_total 162
telemt_me_route_drop_no_conn_total 1036
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3857
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8
telemt_desync_full_logged_total 4
telemt_desync_suppressed_total 4
telemt_desync_frames_bucket_total{bucket="3_10"} 4
telemt_desync_frames_bucket_total{bucket="gt_10"} 4
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 175
telemt_me_writer_restored_same_endpoint_total 178
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_user_connections_total{user="hello"} 3855
telemt_user_connections_current{user="hello"} 154
telemt_user_octets_from_client{user="hello"} 31879704 (30.40 MB)
telemt_user_octets_to_client{user="hello"} 4012882744 (3.74 GB)
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 1244.3 (0h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4713
telemt_connections_bad_total 7
telemt_handshake_timeouts_total 20
telemt_upstream_connect_attempt_total 212
telemt_upstream_connect_success_total 187
telemt_upstream_connect_fail_total 25
telemt_upstream_connect_attempts_per_request{bucket="1"} 212
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 97
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 25
telemt_me_reconnect_attempts_total 94
telemt_me_reconnect_success_total 75
telemt_me_reader_eof_total 63
telemt_me_idle_close_by_peer_total 63
telemt_me_route_drop_no_conn_total 1196
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4235
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 13
telemt_desync_full_logged_total 3
telemt_desync_suppressed_total 10
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 4
telemt_desync_frames_bucket_total{bucket="gt_10"} 6
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 82
telemt_me_writer_restored_same_endpoint_total 67
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 121
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 4235
telemt_user_connections_current{user="hello"} 223
telemt_user_octets_from_client{user="hello"} 31435776 (29.98 MB)
telemt_user_octets_to_client{user="hello"} 804876092 (767.59 MB)
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 1213.4 (0h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1984
telemt_connections_bad_total 295
telemt_handshake_timeouts_total 40
telemt_upstream_connect_attempt_total 313
telemt_upstream_connect_success_total 295
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 313
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 148
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 147
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 190
telemt_me_reconnect_success_total 190
telemt_me_reader_eof_total 161
telemt_me_idle_close_by_peer_total 161
telemt_me_route_drop_no_conn_total 388
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1575
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 14
telemt_desync_full_logged_total 7
telemt_desync_suppressed_total 7
telemt_desync_frames_bucket_total{bucket="1_2"} 1
telemt_desync_frames_bucket_total{bucket="3_10"} 13
telemt_me_writer_removed_unexpected_total 179
telemt_me_writer_restored_same_endpoint_total 179
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 18
telemt_user_connections_total{user="hello"} 1575
telemt_user_connections_current{user="hello"} 95
telemt_user_octets_from_client{user="hello"} 6059648 (5.78 MB)
telemt_user_octets_to_client{user="hello"} 288988424 (275.60 MB)
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 1200.2 (0h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5518
telemt_connections_bad_total 490
telemt_handshake_timeouts_total 46
telemt_upstream_connect_attempt_total 181
telemt_upstream_connect_success_total 179
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 181
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 104
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 75
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 73
telemt_me_reconnect_success_total 72
telemt_me_reader_eof_total 52
telemt_me_idle_close_by_peer_total 52
telemt_me_route_drop_no_conn_total 2290
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4712
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4
telemt_desync_full_logged_total 2
telemt_desync_suppressed_total 2
telemt_desync_frames_bucket_total{bucket="3_10"} 4
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 74
telemt_me_writer_restored_same_endpoint_total 65
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 4711
telemt_user_connections_current{user="hello"} 244
telemt_user_octets_from_client{user="hello"} 198717276 (189.51 MB)
telemt_user_octets_to_client{user="hello"} 1118618212 (1.04 GB)
telemt_user_unique_ips_current{user="hello"} 86
telemt_user_unique_ips_recent_window{user="hello"} 37
```