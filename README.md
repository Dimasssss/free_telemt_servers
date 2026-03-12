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

# Server Metrics 2026-03-12 13:44:31 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 22268.5 (6h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 117926
telemt_connections_bad_total 1359
telemt_handshake_timeouts_total 3963
telemt_upstream_connect_attempt_total 5387
telemt_upstream_connect_success_total 5363
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 5387
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2401
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2956
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_keepalive_timeout_total 243
telemt_me_reconnect_attempts_total 4245
telemt_me_reconnect_success_total 4217
telemt_me_reader_eof_total 4424
telemt_me_idle_close_by_peer_total 4423
telemt_me_route_drop_no_conn_total 33138
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 103852
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 486
telemt_desync_full_logged_total 182
telemt_desync_suppressed_total 304
telemt_desync_frames_bucket_total{bucket="1_2"} 92
telemt_desync_frames_bucket_total{bucket="3_10"} 191
telemt_desync_frames_bucket_total{bucket="gt_10"} 203
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 4251
telemt_me_writer_restored_same_endpoint_total 4201
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 34
telemt_user_connections_total{user="hello"} 103816
telemt_user_connections_current{user="hello"} 393
telemt_user_octets_from_client{user="hello"} 1690053700 (1.57 GB)
telemt_user_octets_to_client{user="hello"} 39842177232 (37.11 GB)
telemt_user_unique_ips_current{user="hello"} 106
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 22161.3 (6h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 47847
telemt_connections_bad_total 336
telemt_handshake_timeouts_total 346
telemt_upstream_connect_attempt_total 6570
telemt_upstream_connect_success_total 6414
telemt_upstream_connect_fail_total 156
telemt_upstream_connect_attempts_per_request{bucket="1"} 6570
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2667
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3729
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 156
telemt_me_keepalive_timeout_total 154
telemt_me_reconnect_attempts_total 21115
telemt_me_reconnect_success_total 5284
telemt_me_reader_eof_total 5873
telemt_me_idle_close_by_peer_total 5873
telemt_me_route_drop_no_conn_total 20980
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 45691
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 31
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 5807
telemt_me_refill_failed_total 494
telemt_me_writer_restored_same_endpoint_total 5269
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 523
telemt_user_connections_total{user="hello"} 45688
telemt_user_connections_current{user="hello"} 154
telemt_user_octets_from_client{user="hello"} 556383152 (530.61 MB)
telemt_user_octets_to_client{user="hello"} 13240100260 (12.33 GB)
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 22124.9 (6h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 64794
telemt_connections_bad_total 136
telemt_handshake_timeouts_total 736
telemt_upstream_connect_attempt_total 6037
telemt_upstream_connect_success_total 6037
telemt_upstream_connect_attempts_per_request{bucket="1"} 6037
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2937
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3091
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 101
telemt_me_reconnect_attempts_total 4912
telemt_me_reconnect_success_total 4874
telemt_me_reader_eof_total 5147
telemt_me_idle_close_by_peer_total 5147
telemt_me_route_drop_no_conn_total 22621
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 61008
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 4
telemt_desync_frames_bucket_total{bucket="3_10"} 6
telemt_desync_frames_bucket_total{bucket="gt_10"} 4
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 4908
telemt_me_writer_restored_same_endpoint_total 4854
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 34
telemt_user_connections_total{user="hello"} 60991
telemt_user_connections_current{user="hello"} 175
telemt_user_octets_from_client{user="hello"} 1821041768 (1.70 GB)
telemt_user_octets_to_client{user="hello"} 35700896112 (33.25 GB)
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 22100.6 (6h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 83826
telemt_connections_bad_total 1463
telemt_handshake_timeouts_total 378
telemt_upstream_connect_attempt_total 6013
telemt_upstream_connect_success_total 5862
telemt_upstream_connect_fail_total 151
telemt_upstream_connect_attempts_per_request{bucket="1"} 6013
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2584
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3259
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 151
telemt_me_keepalive_timeout_total 235
telemt_me_reconnect_attempts_total 15131
telemt_me_reconnect_success_total 4712
telemt_me_reader_eof_total 5167
telemt_me_idle_close_by_peer_total 5167
telemt_me_route_drop_no_conn_total 31501
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 76948
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 239
telemt_desync_full_logged_total 83
telemt_desync_suppressed_total 156
telemt_desync_frames_bucket_total{bucket="1_2"} 86
telemt_desync_frames_bucket_total{bucket="3_10"} 76
telemt_desync_frames_bucket_total{bucket="gt_10"} 77
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 5092
telemt_me_refill_failed_total 324
telemt_me_writer_restored_same_endpoint_total 4704
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 121
telemt_me_writer_removed_unexpected_minus_restored_total 380
telemt_user_connections_total{user="hello"} 76832
telemt_user_connections_current{user="hello"} 187
telemt_user_octets_from_client{user="hello"} 1275153580 (1.19 GB)
telemt_user_octets_to_client{user="hello"} 34051978240 (31.71 GB)
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 22069.9 (6h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 48471
telemt_connections_bad_total 4154
telemt_handshake_timeouts_total 683
telemt_upstream_connect_attempt_total 15543
telemt_upstream_connect_success_total 15276
telemt_upstream_connect_fail_total 267
telemt_upstream_connect_attempts_per_request{bucket="1"} 15543
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11590
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3662
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 267
telemt_me_keepalive_timeout_total 104
telemt_me_reconnect_attempts_total 28683
telemt_me_reconnect_success_total 3666
telemt_me_reader_eof_total 4444
telemt_me_idle_close_by_peer_total 4444
telemt_me_seq_mismatch_total 8
telemt_me_route_drop_no_conn_total 11983
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 31997
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 428
telemt_desync_full_logged_total 118
telemt_desync_suppressed_total 310
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 355
telemt_desync_frames_bucket_total{bucket="gt_10"} 58
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 4469
telemt_me_refill_failed_total 783
telemt_me_writer_restored_same_endpoint_total 3649
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 803
telemt_user_connections_total{user="hello"} 42461
telemt_user_connections_current{user="hello"} 126
telemt_user_octets_from_client{user="hello"} 345756621 (329.74 MB)
telemt_user_octets_to_client{user="hello"} 10954290838 (10.20 GB)
telemt_user_msgs_from_client{user="hello"} 148005
telemt_user_msgs_to_client{user="hello"} 428049
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 22056.8 (6h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 130405
telemt_connections_bad_total 772
telemt_handshake_timeouts_total 989
telemt_upstream_connect_attempt_total 4550
telemt_upstream_connect_success_total 4527
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 4550
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2164
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2361
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_timeout_total 98
telemt_me_reconnect_attempts_total 3421
telemt_me_reconnect_success_total 3392
telemt_me_reader_eof_total 3576
telemt_me_idle_close_by_peer_total 3576
telemt_me_route_drop_no_conn_total 52140
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 124468
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 220
telemt_desync_full_logged_total 77
telemt_desync_suppressed_total 143
telemt_desync_frames_bucket_total{bucket="1_2"} 52
telemt_desync_frames_bucket_total{bucket="3_10"} 87
telemt_desync_frames_bucket_total{bucket="gt_10"} 81
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 3434
telemt_me_writer_restored_same_endpoint_total 3385
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 42
telemt_user_connections_total{user="hello"} 124435
telemt_user_connections_current{user="hello"} 445
telemt_user_octets_from_client{user="hello"} 2722855600 (2.54 GB)
telemt_user_octets_to_client{user="hello"} 53127008004 (49.48 GB)
telemt_user_unique_ips_current{user="hello"} 137
telemt_user_unique_ips_recent_window{user="hello"} 49
```