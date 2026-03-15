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

# Server Metrics 2026-03-15 10:22:48 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 43700.4 (12h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 180577
telemt_connections_bad_total 1296
telemt_handshake_timeouts_total 4166
telemt_upstream_connect_attempt_total 10969
telemt_upstream_connect_success_total 10911
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 10969
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4855
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6044
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 11098
telemt_me_reconnect_success_total 8729
telemt_me_reader_eof_total 9343
telemt_me_idle_close_by_peer_total 9343
telemt_me_route_drop_no_conn_total 410725
telemt_me_route_drop_channel_closed_total 60
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 229281
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1348
telemt_desync_full_logged_total 537
telemt_desync_suppressed_total 811
telemt_desync_frames_bucket_total{bucket="1_2"} 220
telemt_desync_frames_bucket_total{bucket="3_10"} 541
telemt_desync_frames_bucket_total{bucket="gt_10"} 587
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 8884
telemt_me_refill_failed_total 73
telemt_me_writer_restored_same_endpoint_total 8698
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 155
telemt_user_connections_total{user="hello"} 168584
telemt_user_connections_current{user="hello"} 386
telemt_user_octets_from_client{user="hello"} 2630469628 (2.45 GB)
telemt_user_octets_to_client{user="hello"} 176440500408 (164.32 GB)
telemt_user_unique_ips_current{user="hello"} 117
telemt_user_unique_ips_recent_window{user="hello"} 50
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 43707.5 (12h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 57991
telemt_connections_bad_total 2308
telemt_handshake_timeouts_total 3049
telemt_upstream_connect_attempt_total 11768
telemt_upstream_connect_success_total 11768
telemt_upstream_connect_attempts_per_request{bucket="1"} 11768
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5045
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6653
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 70
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 11883
telemt_me_reconnect_success_total 9561
telemt_me_reader_eof_total 10278
telemt_me_idle_close_by_peer_total 10278
telemt_me_route_drop_no_conn_total 27464
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 50782
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 9738
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 9545
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 177
telemt_user_connections_total{user="hello"} 50780
telemt_user_connections_current{user="hello"} 217
telemt_user_octets_from_client{user="hello"} 1012728304 (965.81 MB)
telemt_user_octets_to_client{user="hello"} 21900793524 (20.40 GB)
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 43700.0 (12h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 65237
telemt_connections_bad_total 641
telemt_handshake_timeouts_total 2434
telemt_upstream_connect_attempt_total 12051
telemt_upstream_connect_success_total 12050
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 12051
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5171
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6868
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 9895
telemt_me_reconnect_success_total 9848
telemt_me_reader_eof_total 10576
telemt_me_idle_close_by_peer_total 10576
telemt_me_route_drop_no_conn_total 24521
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 59541
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 30
telemt_desync_full_logged_total 13
telemt_desync_suppressed_total 17
telemt_desync_frames_bucket_total{bucket="3_10"} 13
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 9940
telemt_me_writer_restored_same_endpoint_total 9844
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 92
telemt_user_connections_total{user="hello"} 59465
telemt_user_connections_current{user="hello"} 170
telemt_user_octets_from_client{user="hello"} 9285761240 (8.65 GB)
telemt_user_octets_to_client{user="hello"} 36904023328 (34.37 GB)
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 43699.6 (12h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 84954
telemt_connections_bad_total 207
telemt_handshake_timeouts_total 585
telemt_upstream_connect_attempt_total 10327
telemt_upstream_connect_success_total 10326
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 10327
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4919
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5376
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 8187
telemt_me_reconnect_success_total 8148
telemt_me_reader_eof_total 8704
telemt_me_idle_close_by_peer_total 8704
telemt_me_route_drop_no_conn_total 35617
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 77286
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 163
telemt_desync_full_logged_total 50
telemt_desync_suppressed_total 113
telemt_desync_frames_bucket_total{bucket="1_2"} 40
telemt_desync_frames_bucket_total{bucket="3_10"} 64
telemt_desync_frames_bucket_total{bucket="gt_10"} 59
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 8233
telemt_me_writer_restored_same_endpoint_total 8137
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 85
telemt_user_connections_total{user="hello"} 77216
telemt_user_connections_current{user="hello"} 195
telemt_user_octets_from_client{user="hello"} 1563357468 (1.46 GB)
telemt_user_octets_to_client{user="hello"} 48986592880 (45.62 GB)
telemt_user_unique_ips_current{user="hello"} 70
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 18771.1 (5h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 31796
telemt_connections_bad_total 3513
telemt_handshake_timeouts_total 495
telemt_upstream_connect_attempt_total 6271
telemt_upstream_connect_success_total 6220
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 6271
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2786
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3414
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_reconnect_attempts_total 99517
telemt_me_reconnect_success_total 5109
telemt_me_reader_eof_total 5292
telemt_me_idle_close_by_peer_total 5292
telemt_me_route_drop_no_conn_total 10622
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 27008
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 40
telemt_desync_full_logged_total 7
telemt_desync_suppressed_total 33
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 17
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 5078
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 5005
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_user_connections_total{user="hello"} 27148
telemt_user_connections_current{user="hello"} 112
telemt_user_octets_from_client{user="hello"} 409659365 (390.68 MB)
telemt_user_octets_to_client{user="hello"} 12577337771 (11.71 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 43699.1 (12h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 231080
telemt_connections_bad_total 43945
telemt_handshake_timeouts_total 1457
telemt_upstream_connect_attempt_total 9340
telemt_upstream_connect_success_total 9285
telemt_upstream_connect_fail_total 55
telemt_upstream_connect_attempts_per_request{bucket="1"} 9340
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4693
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4591
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 55
telemt_me_reconnect_attempts_total 7137
telemt_me_reconnect_success_total 7097
telemt_me_reader_eof_total 7565
telemt_me_idle_close_by_peer_total 7565
telemt_me_route_drop_no_conn_total 100940
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 179610
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 71
telemt_desync_full_logged_total 33
telemt_desync_suppressed_total 38
telemt_desync_frames_bucket_total{bucket="1_2"} 10
telemt_desync_frames_bucket_total{bucket="3_10"} 31
telemt_desync_frames_bucket_total{bucket="gt_10"} 30
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 7148
telemt_me_writer_restored_same_endpoint_total 7070
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 177982
telemt_user_connections_current{user="hello"} 488
telemt_user_octets_from_client{user="hello"} 4398304224 (4.10 GB)
telemt_user_octets_to_client{user="hello"} 91343700908 (85.07 GB)
telemt_user_unique_ips_current{user="hello"} 206
telemt_user_unique_ips_recent_window{user="hello"} 77
```