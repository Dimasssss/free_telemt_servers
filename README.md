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

# Server Metrics 2026-03-15 08:45:56 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 37888.0 (10h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 139981
telemt_connections_bad_total 1132
telemt_handshake_timeouts_total 3481
telemt_upstream_connect_attempt_total 9164
telemt_upstream_connect_success_total 9110
telemt_upstream_connect_fail_total 54
telemt_upstream_connect_attempts_per_request{bucket="1"} 9164
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4056
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5047
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 54
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 7246
telemt_me_reconnect_success_total 7219
telemt_me_reader_eof_total 7708
telemt_me_idle_close_by_peer_total 7708
telemt_me_route_drop_no_conn_total 287352
telemt_me_route_drop_channel_closed_total 40
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 174041
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1016
telemt_desync_full_logged_total 427
telemt_desync_suppressed_total 589
telemt_desync_frames_bucket_total{bucket="1_2"} 174
telemt_desync_frames_bucket_total{bucket="3_10"} 413
telemt_desync_frames_bucket_total{bucket="gt_10"} 429
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 7283
telemt_me_writer_restored_same_endpoint_total 7188
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 130167
telemt_user_connections_current{user="hello"} 345
telemt_user_octets_from_client{user="hello"} 1768262880 (1.65 GB)
telemt_user_octets_to_client{user="hello"} 128398860308 (119.58 GB)
telemt_user_unique_ips_current{user="hello"} 107
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 37895.5 (10h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 42948
telemt_connections_bad_total 283
telemt_handshake_timeouts_total 2227
telemt_upstream_connect_attempt_total 10360
telemt_upstream_connect_success_total 10360
telemt_upstream_connect_attempts_per_request{bucket="1"} 10360
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4435
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5892
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 9559
telemt_me_reconnect_success_total 8434
telemt_me_reader_eof_total 9042
telemt_me_idle_close_by_peer_total 9042
telemt_me_route_drop_no_conn_total 21627
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 38925
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 8553
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 8418
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 119
telemt_user_connections_total{user="hello"} 38927
telemt_user_connections_current{user="hello"} 172
telemt_user_octets_from_client{user="hello"} 886178832 (845.13 MB)
telemt_user_octets_to_client{user="hello"} 14067481800 (13.10 GB)
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 37887.9 (10h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 52604
telemt_connections_bad_total 491
telemt_handshake_timeouts_total 1914
telemt_upstream_connect_attempt_total 10072
telemt_upstream_connect_success_total 10071
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 10072
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4417
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5645
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 8190
telemt_me_reconnect_success_total 8150
telemt_me_reader_eof_total 8805
telemt_me_idle_close_by_peer_total 8805
telemt_me_route_drop_no_conn_total 18387
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 47945
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
telemt_me_writer_removed_unexpected_total 8228
telemt_me_writer_restored_same_endpoint_total 8146
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 78
telemt_user_connections_total{user="hello"} 47878
telemt_user_connections_current{user="hello"} 117
telemt_user_octets_from_client{user="hello"} 8998466364 (8.38 GB)
telemt_user_octets_to_client{user="hello"} 31960659612 (29.77 GB)
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 37887.8 (10h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 64341
telemt_connections_bad_total 165
telemt_handshake_timeouts_total 409
telemt_upstream_connect_attempt_total 8974
telemt_upstream_connect_success_total 8973
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 8974
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4233
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4713
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 7110
telemt_me_reconnect_success_total 7080
telemt_me_reader_eof_total 7567
telemt_me_idle_close_by_peer_total 7567
telemt_me_route_drop_no_conn_total 27673
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 58373
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 123
telemt_desync_full_logged_total 37
telemt_desync_suppressed_total 86
telemt_desync_frames_bucket_total{bucket="1_2"} 28
telemt_desync_frames_bucket_total{bucket="3_10"} 54
telemt_desync_frames_bucket_total{bucket="gt_10"} 41
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 7152
telemt_me_writer_restored_same_endpoint_total 7069
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 72
telemt_user_connections_total{user="hello"} 58306
telemt_user_connections_current{user="hello"} 237
telemt_user_octets_from_client{user="hello"} 1150831284 (1.07 GB)
telemt_user_octets_to_client{user="hello"} 35947968356 (33.48 GB)
telemt_user_unique_ips_current{user="hello"} 71
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 12959.2 (3h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20553
telemt_connections_bad_total 2476
telemt_handshake_timeouts_total 324
telemt_upstream_connect_attempt_total 4589
telemt_upstream_connect_success_total 4549
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 4589
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2008
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2529
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_reconnect_attempts_total 98112
telemt_me_reconnect_success_total 3710
telemt_me_reader_eof_total 3825
telemt_me_idle_close_by_peer_total 3825
telemt_me_route_drop_no_conn_total 6329
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 17186
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
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 3667
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 3606
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_user_connections_total{user="hello"} 17326
telemt_user_connections_current{user="hello"} 63
telemt_user_octets_from_client{user="hello"} 142597957 (135.99 MB)
telemt_user_octets_to_client{user="hello"} 10267182251 (9.56 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 22
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 37887.0 (10h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 167340
telemt_connections_bad_total 21659
telemt_handshake_timeouts_total 950
telemt_upstream_connect_attempt_total 8198
telemt_upstream_connect_success_total 8149
telemt_upstream_connect_fail_total 49
telemt_upstream_connect_attempts_per_request{bucket="1"} 8198
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4139
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4009
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 49
telemt_me_reconnect_attempts_total 6267
telemt_me_reconnect_success_total 6236
telemt_me_reader_eof_total 6648
telemt_me_idle_close_by_peer_total 6648
telemt_me_route_drop_no_conn_total 79691
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 140257
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
telemt_me_writer_removed_unexpected_total 6273
telemt_me_writer_restored_same_endpoint_total 6209
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 138803
telemt_user_connections_current{user="hello"} 440
telemt_user_octets_from_client{user="hello"} 3708437828 (3.45 GB)
telemt_user_octets_to_client{user="hello"} 73017618260 (68.00 GB)
telemt_user_unique_ips_current{user="hello"} 187
telemt_user_unique_ips_recent_window{user="hello"} 70
```