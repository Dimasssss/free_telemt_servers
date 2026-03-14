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

# Server Metrics 2026-03-14 13:44:47 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.17

telemt_uptime_seconds 1707.4 (0h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8898
telemt_connections_bad_total 1064
telemt_handshake_timeouts_total 52
telemt_upstream_connect_attempt_total 328
telemt_upstream_connect_success_total 328
telemt_upstream_connect_attempts_per_request{bucket="1"} 328
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 154
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 171
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 6
telemt_me_reconnect_attempts_total 215
telemt_me_reconnect_success_total 213
telemt_me_reader_eof_total 190
telemt_me_idle_close_by_peer_total 190
telemt_me_route_drop_no_conn_total 2549
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7598
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10
telemt_desync_full_logged_total 4
telemt_desync_suppressed_total 6
telemt_desync_frames_bucket_total{bucket="3_10"} 4
telemt_desync_frames_bucket_total{bucket="gt_10"} 6
telemt_me_writer_removed_unexpected_total 213
telemt_me_writer_restored_same_endpoint_total 195
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 72
telemt_user_connections_total{user="hello"} 7598
telemt_user_connections_current{user="hello"} 347
telemt_user_octets_from_client{user="hello"} 118133532 (112.66 MB)
telemt_user_octets_to_client{user="hello"} 2282848904 (2.13 GB)
telemt_user_unique_ips_current{user="hello"} 107
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## psb.hosting

```
telemt 3.3.17

telemt_uptime_seconds 1705.4 (0h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3884
telemt_connections_bad_total 30
telemt_handshake_timeouts_total 36
telemt_upstream_connect_attempt_total 291
telemt_upstream_connect_success_total 273
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 291
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 129
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 141
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 178
telemt_me_reconnect_success_total 160
telemt_me_reader_eof_total 151
telemt_me_idle_close_by_peer_total 151
telemt_me_route_drop_no_conn_total 1498
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3707
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_writer_removed_unexpected_total 169
telemt_me_writer_restored_same_endpoint_total 155
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 120
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 3691
telemt_user_connections_current{user="hello"} 185
telemt_user_octets_from_client{user="hello"} 39533460 (37.70 MB)
telemt_user_octets_to_client{user="hello"} 1270396320 (1.18 GB)
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## koara.io

```
telemt 3.3.17

telemt_uptime_seconds 1710.5 (0h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3692
telemt_connections_bad_total 12
telemt_handshake_timeouts_total 54
telemt_upstream_connect_attempt_total 1517
telemt_upstream_connect_success_total 1509
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 1517
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 842
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 666
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 26
telemt_me_reconnect_attempts_total 90213
telemt_me_reconnect_success_total 1076
telemt_me_reader_eof_total 1017
telemt_me_idle_close_by_peer_total 1017
telemt_me_route_drop_no_conn_total 1203
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3150
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_writer_removed_unexpected_total 1033
telemt_me_refill_failed_total 2897
telemt_me_writer_restored_same_endpoint_total 1038
telemt_me_writer_restored_fallback_total 38
telemt_me_async_recovery_trigger_total 1685
telemt_user_connections_total{user="hello"} 3461
telemt_user_connections_current{user="hello"} 133
telemt_user_octets_from_client{user="hello"} 82948497 (79.11 MB)
telemt_user_octets_to_client{user="hello"} 2875529642 (2.68 GB)
telemt_user_msgs_from_client{user="hello"} 3762
telemt_user_msgs_to_client{user="hello"} 18362
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## landvps.ru

```
telemt 3.3.17

telemt_uptime_seconds 1714.6 (0h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5980
telemt_connections_bad_total 3
telemt_handshake_timeouts_total 51
telemt_upstream_connect_attempt_total 294
telemt_upstream_connect_success_total 293
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 294
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 135
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 155
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 18
telemt_me_reconnect_attempts_total 186
telemt_me_reconnect_success_total 184
telemt_me_reader_eof_total 155
telemt_me_idle_close_by_peer_total 155
telemt_me_route_drop_no_conn_total 3589
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5727
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 69
telemt_desync_full_logged_total 18
telemt_desync_suppressed_total 51
telemt_desync_frames_bucket_total{bucket="1_2"} 8
telemt_desync_frames_bucket_total{bucket="3_10"} 34
telemt_desync_frames_bucket_total{bucket="gt_10"} 27
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 173
telemt_me_writer_restored_same_endpoint_total 182
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 60
telemt_user_connections_total{user="hello"} 5612
telemt_user_connections_current{user="hello"} 251
telemt_user_octets_from_client{user="hello"} 81473492 (77.70 MB)
telemt_user_octets_to_client{user="hello"} 1487306272 (1.39 GB)
telemt_user_unique_ips_current{user="hello"} 72
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## rdp-onedash.ru

```
telemt 3.3.17

telemt_uptime_seconds 1707.8 (0h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3897
telemt_connections_bad_total 397
telemt_handshake_timeouts_total 58
telemt_upstream_connect_attempt_total 385
telemt_upstream_connect_success_total 374
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 385
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 157
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 217
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 261
telemt_me_reconnect_success_total 255
telemt_me_reader_eof_total 231
telemt_me_idle_close_by_peer_total 231
telemt_me_route_drop_no_conn_total 1235
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3182
telemt_me_writer_pick_total{mode="p2c",result="full"} 2
telemt_me_writer_pick_total{mode="p2c",result="closed"} 8
telemt_me_endpoint_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 31
telemt_desync_full_logged_total 3
telemt_desync_suppressed_total 28
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 13
telemt_desync_frames_bucket_total{bucket="gt_10"} 15
telemt_me_writer_removed_unexpected_total 245
telemt_me_writer_restored_same_endpoint_total 251
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 8
telemt_user_connections_total{user="hello"} 3178
telemt_user_connections_current{user="hello"} 70
telemt_user_octets_from_client{user="hello"} 15543236 (14.82 MB)
telemt_user_octets_to_client{user="hello"} 336830508 (321.23 MB)
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## hostvds.com

```
telemt 3.3.17

telemt_uptime_seconds 1707.2 (0h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12492
telemt_connections_bad_total 16
telemt_handshake_timeouts_total 50
telemt_upstream_connect_attempt_total 338
telemt_upstream_connect_success_total 319
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 338
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 187
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 131
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 217
telemt_me_reconnect_success_total 198
telemt_me_reader_eof_total 168
telemt_me_idle_close_by_peer_total 168
telemt_me_route_drop_no_conn_total 5655
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 11688
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_writer_removed_unexpected_total 188
telemt_me_writer_restored_same_endpoint_total 194
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 136
telemt_user_connections_total{user="hello"} 11635
telemt_user_connections_current{user="hello"} 434
telemt_user_octets_from_client{user="hello"} 391184356 (373.06 MB)
telemt_user_octets_to_client{user="hello"} 5605353092 (5.22 GB)
telemt_user_unique_ips_current{user="hello"} 181
telemt_user_unique_ips_recent_window{user="hello"} 62
```