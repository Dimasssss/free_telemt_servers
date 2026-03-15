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

# Server Metrics 2026-03-15 18:43:01 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 73712.6 (20h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 346703
telemt_connections_bad_total 4199
telemt_handshake_timeouts_total 12073
telemt_upstream_connect_attempt_total 17815
telemt_upstream_connect_success_total 17727
telemt_upstream_connect_fail_total 88
telemt_upstream_connect_attempts_per_request{bucket="1"} 17815
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7857
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9832
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 88
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 32
telemt_me_reconnect_attempts_total 17460
telemt_me_reconnect_success_total 14061
telemt_me_reader_eof_total 14977
telemt_me_idle_close_by_peer_total 14977
telemt_me_route_drop_no_conn_total 466402
telemt_me_route_drop_channel_closed_total 76
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 378161
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1895
telemt_desync_full_logged_total 749
telemt_desync_suppressed_total 1146
telemt_desync_frames_bucket_total{bucket="1_2"} 358
telemt_desync_frames_bucket_total{bucket="3_10"} 736
telemt_desync_frames_bucket_total{bucket="gt_10"} 801
telemt_pool_swap_total 65
telemt_me_writer_removed_unexpected_total 14320
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 14027
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 259
telemt_user_connections_total{user="hello"} 317253
telemt_user_connections_current{user="hello"} 400
telemt_user_octets_from_client{user="hello"} 6471070888 (6.03 GB)
telemt_user_octets_to_client{user="hello"} 246196410208 (229.29 GB)
telemt_user_unique_ips_current{user="hello"} 114
telemt_user_unique_ips_recent_window{user="hello"} 51
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 73719.0 (20h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 139483
telemt_connections_bad_total 2839
telemt_handshake_timeouts_total 12555
telemt_upstream_connect_attempt_total 19852
telemt_upstream_connect_success_total 19852
telemt_upstream_connect_attempts_per_request{bucket="1"} 19852
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8452
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11061
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 339
telemt_me_keepalive_timeout_total 44
telemt_me_reconnect_attempts_total 18512
telemt_me_reconnect_success_total 16145
telemt_me_reader_eof_total 17262
telemt_me_idle_close_by_peer_total 17261
telemt_me_route_drop_no_conn_total 58029
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 118449
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3
telemt_desync_full_logged_total 3
telemt_desync_frames_bucket_total{bucket="1_2"} 1
telemt_desync_frames_bucket_total{bucket="3_10"} 2
telemt_pool_swap_total 64
telemt_me_writer_removed_unexpected_total 16434
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 16129
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 289
telemt_user_connections_total{user="hello"} 118429
telemt_user_connections_current{user="hello"} 236
telemt_user_octets_from_client{user="hello"} 2248347140 (2.09 GB)
telemt_user_octets_to_client{user="hello"} 59378832720 (55.30 GB)
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 73711.5 (20h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 142802
telemt_connections_bad_total 1700
telemt_handshake_timeouts_total 3306
telemt_upstream_connect_attempt_total 21446
telemt_upstream_connect_success_total 21438
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 21446
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9308
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12094
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 25076
telemt_me_reconnect_success_total 17716
telemt_me_reader_eof_total 19014
telemt_me_idle_close_by_peer_total 19014
telemt_me_route_drop_no_conn_total 55813
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 125871
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 59
telemt_desync_full_logged_total 23
telemt_desync_suppressed_total 36
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 29
telemt_desync_frames_bucket_total{bucket="gt_10"} 25
telemt_pool_swap_total 60
telemt_me_writer_removed_unexpected_total 18116
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 17708
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 400
telemt_user_connections_total{user="hello"} 125763
telemt_user_connections_current{user="hello"} 177
telemt_user_octets_from_client{user="hello"} 10770826260 (10.03 GB)
telemt_user_octets_to_client{user="hello"} 69409460204 (64.64 GB)
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 73711.1 (20h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 198926
telemt_connections_bad_total 963
telemt_handshake_timeouts_total 1350
telemt_upstream_connect_attempt_total 17387
telemt_upstream_connect_success_total 17373
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 17387
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8317
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8986
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 67
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 13793
telemt_me_reconnect_success_total 13710
telemt_me_reader_eof_total 14590
telemt_me_idle_close_by_peer_total 14590
telemt_me_route_drop_no_conn_total 74780
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 183350
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 645
telemt_desync_full_logged_total 243
telemt_desync_suppressed_total 402
telemt_desync_frames_bucket_total{bucket="1_2"} 134
telemt_desync_frames_bucket_total{bucket="3_10"} 303
telemt_desync_frames_bucket_total{bucket="gt_10"} 208
telemt_pool_swap_total 67
telemt_me_writer_removed_unexpected_total 13873
telemt_me_writer_restored_same_endpoint_total 13699
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 163
telemt_user_connections_total{user="hello"} 183261
telemt_user_connections_current{user="hello"} 258
telemt_user_octets_from_client{user="hello"} 3439029320 (3.20 GB)
telemt_user_octets_to_client{user="hello"} 85513607204 (79.64 GB)
telemt_user_unique_ips_current{user="hello"} 73
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 48782.6 (13h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 120378
telemt_connections_bad_total 24717
telemt_handshake_timeouts_total 2465
telemt_upstream_connect_attempt_total 14434
telemt_upstream_connect_success_total 14349
telemt_upstream_connect_fail_total 85
telemt_upstream_connect_attempts_per_request{bucket="1"} 14434
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6579
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7692
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 78
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 85
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 106157
telemt_me_reconnect_success_total 11710
telemt_me_reader_eof_total 12310
telemt_me_idle_close_by_peer_total 12310
telemt_me_route_drop_no_conn_total 41117
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 89859
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 280
telemt_desync_full_logged_total 60
telemt_desync_suppressed_total 220
telemt_desync_frames_bucket_total{bucket="1_2"} 45
telemt_desync_frames_bucket_total{bucket="3_10"} 103
telemt_desync_frames_bucket_total{bucket="gt_10"} 132
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 11782
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 11606
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 72
telemt_user_connections_total{user="hello"} 89991
telemt_user_connections_current{user="hello"} 140
telemt_user_octets_from_client{user="hello"} 1507341345 (1.40 GB)
telemt_user_octets_to_client{user="hello"} 34794201843 (32.40 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 73710.9 (20h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 497098
telemt_connections_bad_total 57830
telemt_handshake_timeouts_total 4026
telemt_upstream_connect_attempt_total 15813
telemt_upstream_connect_success_total 15722
telemt_upstream_connect_fail_total 91
telemt_upstream_connect_attempts_per_request{bucket="1"} 15813
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7580
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8108
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 15
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 91
telemt_me_keepalive_timeout_total 62
telemt_me_reconnect_attempts_total 13335
telemt_me_reconnect_success_total 12030
telemt_me_reader_eof_total 12779
telemt_me_idle_close_by_peer_total 12779
telemt_me_route_drop_no_conn_total 319581
telemt_me_route_drop_channel_closed_total 82
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 458931
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 317
telemt_desync_full_logged_total 86
telemt_desync_suppressed_total 231
telemt_desync_frames_bucket_total{bucket="1_2"} 169
telemt_desync_frames_bucket_total{bucket="3_10"} 94
telemt_desync_frames_bucket_total{bucket="gt_10"} 54
telemt_pool_swap_total 62
telemt_me_writer_removed_unexpected_total 12199
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 12003
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 169
telemt_user_connections_total{user="hello"} 416995
telemt_user_connections_current{user="hello"} 609
telemt_user_octets_from_client{user="hello"} 10692205060 (9.96 GB)
telemt_user_octets_to_client{user="hello"} 230478243384 (214.65 GB)
telemt_user_unique_ips_current{user="hello"} 201
telemt_user_unique_ips_recent_window{user="hello"} 55
```