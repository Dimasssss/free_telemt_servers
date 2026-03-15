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

# Server Metrics 2026-03-15 07:49:55 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 34526.9 (9h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 114025
telemt_connections_bad_total 853
telemt_handshake_timeouts_total 2499
telemt_upstream_connect_attempt_total 8396
telemt_upstream_connect_success_total 8346
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 8396
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3755
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4585
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 6641
telemt_me_reconnect_success_total 6616
telemt_me_reader_eof_total 7085
telemt_me_idle_close_by_peer_total 7085
telemt_me_route_drop_no_conn_total 184986
telemt_me_route_drop_channel_closed_total 31
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 131120
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 905
telemt_desync_full_logged_total 387
telemt_desync_suppressed_total 518
telemt_desync_frames_bucket_total{bucket="1_2"} 152
telemt_desync_frames_bucket_total{bucket="3_10"} 376
telemt_desync_frames_bucket_total{bucket="gt_10"} 377
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 6675
telemt_me_writer_restored_same_endpoint_total 6585
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 106404
telemt_user_connections_current{user="hello"} 322
telemt_user_octets_from_client{user="hello"} 1511326700 (1.41 GB)
telemt_user_octets_to_client{user="hello"} 90616889692 (84.39 GB)
telemt_user_unique_ips_current{user="hello"} 105
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 34534.0 (9h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 36012
telemt_connections_bad_total 247
telemt_handshake_timeouts_total 1001
telemt_upstream_connect_attempt_total 9194
telemt_upstream_connect_success_total 9194
telemt_upstream_connect_attempts_per_request{bucket="1"} 9194
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4031
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5151
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 7484
telemt_me_reconnect_success_total 7451
telemt_me_reader_eof_total 8015
telemt_me_idle_close_by_peer_total 8015
telemt_me_route_drop_no_conn_total 18773
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 33417
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 7523
telemt_me_writer_restored_same_endpoint_total 7435
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 72
telemt_user_connections_total{user="hello"} 33420
telemt_user_connections_current{user="hello"} 144
telemt_user_octets_from_client{user="hello"} 807387844 (769.99 MB)
telemt_user_octets_to_client{user="hello"} 12685219376 (11.81 GB)
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 34526.6 (9h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 45794
telemt_connections_bad_total 479
telemt_handshake_timeouts_total 1870
telemt_upstream_connect_attempt_total 9143
telemt_upstream_connect_success_total 9142
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 9143
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4019
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5116
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 7436
telemt_me_reconnect_success_total 7401
telemt_me_reader_eof_total 8013
telemt_me_idle_close_by_peer_total 8013
telemt_me_route_drop_no_conn_total 15762
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 41397
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1
telemt_desync_full_logged_total 1
telemt_desync_frames_bucket_total{bucket="3_10"} 1
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 7469
telemt_me_writer_restored_same_endpoint_total 7397
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 68
telemt_user_connections_total{user="hello"} 41335
telemt_user_connections_current{user="hello"} 108
telemt_user_octets_from_client{user="hello"} 8868993624 (8.26 GB)
telemt_user_octets_to_client{user="hello"} 22076778812 (20.56 GB)
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 34526.3 (9h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 53453
telemt_connections_bad_total 149
telemt_handshake_timeouts_total 361
telemt_upstream_connect_attempt_total 8085
telemt_upstream_connect_success_total 8084
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 8085
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3795
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4268
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 6381
telemt_me_reconnect_success_total 6356
telemt_me_reader_eof_total 6807
telemt_me_idle_close_by_peer_total 6807
telemt_me_route_drop_no_conn_total 23153
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 48342
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 87
telemt_desync_full_logged_total 26
telemt_desync_suppressed_total 61
telemt_desync_frames_bucket_total{bucket="1_2"} 23
telemt_desync_frames_bucket_total{bucket="3_10"} 34
telemt_desync_frames_bucket_total{bucket="gt_10"} 30
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 6425
telemt_me_writer_restored_same_endpoint_total 6345
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 69
telemt_user_connections_total{user="hello"} 48276
telemt_user_connections_current{user="hello"} 178
telemt_user_octets_from_client{user="hello"} 910548256 (868.37 MB)
telemt_user_octets_to_client{user="hello"} 28695654460 (26.72 GB)
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 9597.7 (2h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14179
telemt_connections_bad_total 1853
telemt_handshake_timeouts_total 165
telemt_upstream_connect_attempt_total 3670
telemt_upstream_connect_success_total 3632
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 3670
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1584
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2036
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_reconnect_attempts_total 97370
telemt_me_reconnect_success_total 2972
telemt_me_reader_eof_total 3036
telemt_me_idle_close_by_peer_total 3036
telemt_me_route_drop_no_conn_total 3979
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 11713
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 2917
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 2868
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_user_connections_total{user="hello"} 11859
telemt_user_connections_current{user="hello"} 79
telemt_user_octets_from_client{user="hello"} 88688281 (84.58 MB)
telemt_user_octets_to_client{user="hello"} 8742720775 (8.14 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 34525.6 (9h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 146168
telemt_connections_bad_total 19716
telemt_handshake_timeouts_total 667
telemt_upstream_connect_attempt_total 7473
telemt_upstream_connect_success_total 7428
telemt_upstream_connect_fail_total 45
telemt_upstream_connect_attempts_per_request{bucket="1"} 7473
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3742
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3685
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 45
telemt_me_reconnect_attempts_total 5720
telemt_me_reconnect_success_total 5692
telemt_me_reader_eof_total 6073
telemt_me_idle_close_by_peer_total 6073
telemt_me_route_drop_no_conn_total 68946
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 122006
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 30
telemt_desync_full_logged_total 14
telemt_desync_suppressed_total 16
telemt_desync_frames_bucket_total{bucket="1_2"} 8
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 10
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 5722
telemt_me_writer_restored_same_endpoint_total 5665
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 30
telemt_user_connections_total{user="hello"} 120542
telemt_user_connections_current{user="hello"} 403
telemt_user_octets_from_client{user="hello"} 2940455796 (2.74 GB)
telemt_user_octets_to_client{user="hello"} 64311090452 (59.89 GB)
telemt_user_unique_ips_current{user="hello"} 175
telemt_user_unique_ips_recent_window{user="hello"} 55
```