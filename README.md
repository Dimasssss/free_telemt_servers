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

# Server Metrics 2026-03-15 08:40:51 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 37583.1 (10h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 137043
telemt_connections_bad_total 1104
telemt_handshake_timeouts_total 3463
telemt_upstream_connect_attempt_total 9061
telemt_upstream_connect_success_total 9007
telemt_upstream_connect_fail_total 54
telemt_upstream_connect_attempts_per_request{bucket="1"} 9061
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4028
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4972
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 54
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 7171
telemt_me_reconnect_success_total 7144
telemt_me_reader_eof_total 7633
telemt_me_idle_close_by_peer_total 7633
telemt_me_route_drop_no_conn_total 271240
telemt_me_route_drop_channel_closed_total 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 167290
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1014
telemt_desync_full_logged_total 425
telemt_desync_suppressed_total 589
telemt_desync_frames_bucket_total{bucket="1_2"} 174
telemt_desync_frames_bucket_total{bucket="3_10"} 411
telemt_desync_frames_bucket_total{bucket="gt_10"} 429
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 7208
telemt_me_writer_restored_same_endpoint_total 7113
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 127402
telemt_user_connections_current{user="hello"} 305
telemt_user_octets_from_client{user="hello"} 1745832176 (1.63 GB)
telemt_user_octets_to_client{user="hello"} 123699971368 (115.20 GB)
telemt_user_unique_ips_current{user="hello"} 104
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 37590.2 (10h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 42123
telemt_connections_bad_total 267
telemt_handshake_timeouts_total 2069
telemt_upstream_connect_attempt_total 10254
telemt_upstream_connect_success_total 10254
telemt_upstream_connect_attempts_per_request{bucket="1"} 10254
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4391
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5830
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 9494
telemt_me_reconnect_success_total 8369
telemt_me_reader_eof_total 8976
telemt_me_idle_close_by_peer_total 8976
telemt_me_route_drop_no_conn_total 21325
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 38302
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 8487
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 8353
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 118
telemt_user_connections_total{user="hello"} 38304
telemt_user_connections_current{user="hello"} 155
telemt_user_octets_from_client{user="hello"} 883155064 (842.24 MB)
telemt_user_octets_to_client{user="hello"} 14002602088 (13.04 GB)
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 37582.8 (10h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 52052
telemt_connections_bad_total 488
telemt_handshake_timeouts_total 1913
telemt_upstream_connect_attempt_total 9984
telemt_upstream_connect_success_total 9983
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 9984
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4377
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5597
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 8144
telemt_me_reconnect_success_total 8104
telemt_me_reader_eof_total 8759
telemt_me_idle_close_by_peer_total 8759
telemt_me_route_drop_no_conn_total 18109
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 47427
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 22
telemt_desync_full_logged_total 11
telemt_desync_suppressed_total 11
telemt_desync_frames_bucket_total{bucket="3_10"} 11
telemt_desync_frames_bucket_total{bucket="gt_10"} 11
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 8182
telemt_me_writer_restored_same_endpoint_total 8100
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 78
telemt_user_connections_total{user="hello"} 47360
telemt_user_connections_current{user="hello"} 133
telemt_user_octets_from_client{user="hello"} 8982828456 (8.37 GB)
telemt_user_octets_to_client{user="hello"} 31354792628 (29.20 GB)
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 37582.6 (10h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 63432
telemt_connections_bad_total 165
telemt_handshake_timeouts_total 409
telemt_upstream_connect_attempt_total 8915
telemt_upstream_connect_success_total 8914
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 8915
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4210
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4677
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 7080
telemt_me_reconnect_success_total 7050
telemt_me_reader_eof_total 7537
telemt_me_idle_close_by_peer_total 7537
telemt_me_route_drop_no_conn_total 27363
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 57506
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 118
telemt_desync_full_logged_total 35
telemt_desync_suppressed_total 83
telemt_desync_frames_bucket_total{bucket="1_2"} 27
telemt_desync_frames_bucket_total{bucket="3_10"} 52
telemt_desync_frames_bucket_total{bucket="gt_10"} 39
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 7122
telemt_me_writer_restored_same_endpoint_total 7039
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 72
telemt_user_connections_total{user="hello"} 57439
telemt_user_connections_current{user="hello"} 261
telemt_user_octets_from_client{user="hello"} 1132835092 (1.06 GB)
telemt_user_octets_to_client{user="hello"} 35531573528 (33.09 GB)
telemt_user_unique_ips_current{user="hello"} 85
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 12654.0 (3h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20139
telemt_connections_bad_total 2414
telemt_handshake_timeouts_total 320
telemt_upstream_connect_attempt_total 4472
telemt_upstream_connect_success_total 4432
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 4472
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1956
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2464
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_reconnect_attempts_total 98018
telemt_me_reconnect_success_total 3618
telemt_me_reader_eof_total 3710
telemt_me_idle_close_by_peer_total 3710
telemt_me_route_drop_no_conn_total 6166
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16845
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8
telemt_desync_full_logged_total 2
telemt_desync_suppressed_total 6
telemt_desync_frames_bucket_total{bucket="3_10"} 5
telemt_desync_frames_bucket_total{bucket="gt_10"} 3
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 3573
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 3514
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_user_connections_total{user="hello"} 16985
telemt_user_connections_current{user="hello"} 90
telemt_user_octets_from_client{user="hello"} 135885913 (129.59 MB)
telemt_user_octets_to_client{user="hello"} 10220500435 (9.52 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 37581.9 (10h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 165205
telemt_connections_bad_total 21475
telemt_handshake_timeouts_total 901
telemt_upstream_connect_attempt_total 8129
telemt_upstream_connect_success_total 8080
telemt_upstream_connect_fail_total 49
telemt_upstream_connect_attempts_per_request{bucket="1"} 8129
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4099
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3980
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 49
telemt_me_reconnect_attempts_total 6239
telemt_me_reconnect_success_total 6209
telemt_me_reader_eof_total 6619
telemt_me_idle_close_by_peer_total 6619
telemt_me_route_drop_no_conn_total 78628
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 138407
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 41
telemt_desync_full_logged_total 18
telemt_desync_suppressed_total 23
telemt_desync_frames_bucket_total{bucket="1_2"} 9
telemt_desync_frames_bucket_total{bucket="3_10"} 18
telemt_desync_frames_bucket_total{bucket="gt_10"} 14
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 6244
telemt_me_writer_restored_same_endpoint_total 6182
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 136950
telemt_user_connections_current{user="hello"} 457
telemt_user_octets_from_client{user="hello"} 3678212656 (3.43 GB)
telemt_user_octets_to_client{user="hello"} 72412694228 (67.44 GB)
telemt_user_unique_ips_current{user="hello"} 195
telemt_user_unique_ips_recent_window{user="hello"} 63
```