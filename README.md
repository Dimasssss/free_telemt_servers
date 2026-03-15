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

# Server Metrics 2026-03-15 09:16:27 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 39719.0 (11h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 151879
telemt_connections_bad_total 1151
telemt_handshake_timeouts_total 3860
telemt_upstream_connect_attempt_total 9844
telemt_upstream_connect_success_total 9788
telemt_upstream_connect_fail_total 56
telemt_upstream_connect_attempts_per_request{bucket="1"} 9844
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4352
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5426
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 56
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 16
telemt_me_reconnect_attempts_total 9004
telemt_me_reconnect_success_total 7790
telemt_me_reader_eof_total 8328
telemt_me_idle_close_by_peer_total 8328
telemt_me_route_drop_no_conn_total 323448
telemt_me_route_drop_channel_closed_total 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 192124
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1121
telemt_desync_full_logged_total 459
telemt_desync_suppressed_total 662
telemt_desync_frames_bucket_total{bucket="1_2"} 191
telemt_desync_frames_bucket_total{bucket="3_10"} 453
telemt_desync_frames_bucket_total{bucket="gt_10"} 477
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 7898
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 7759
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 108
telemt_user_connections_total{user="hello"} 141278
telemt_user_connections_current{user="hello"} 374
telemt_user_octets_from_client{user="hello"} 1922479116 (1.79 GB)
telemt_user_octets_to_client{user="hello"} 145976161248 (135.95 GB)
telemt_user_unique_ips_current{user="hello"} 123
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 39725.8 (11h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 47227
telemt_connections_bad_total 300
telemt_handshake_timeouts_total 2729
telemt_upstream_connect_attempt_total 10779
telemt_upstream_connect_success_total 10779
telemt_upstream_connect_attempts_per_request{bucket="1"} 10779
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4612
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6122
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 11071
telemt_me_reconnect_success_total 8756
telemt_me_reader_eof_total 9418
telemt_me_idle_close_by_peer_total 9418
telemt_me_route_drop_no_conn_total 23712
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 42587
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 8916
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 8740
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 160
telemt_user_connections_total{user="hello"} 42588
telemt_user_connections_current{user="hello"} 175
telemt_user_octets_from_client{user="hello"} 911095508 (868.89 MB)
telemt_user_octets_to_client{user="hello"} 15827715532 (14.74 GB)
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 39718.0 (11h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 56360
telemt_connections_bad_total 498
telemt_handshake_timeouts_total 1940
telemt_upstream_connect_attempt_total 10518
telemt_upstream_connect_success_total 10517
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 10518
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4609
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5898
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 8547
telemt_me_reconnect_success_total 8504
telemt_me_reader_eof_total 9189
telemt_me_idle_close_by_peer_total 9189
telemt_me_route_drop_no_conn_total 20352
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 51579
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 26
telemt_desync_full_logged_total 12
telemt_desync_suppressed_total 14
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 14
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 8586
telemt_me_writer_restored_same_endpoint_total 8500
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 82
telemt_user_connections_total{user="hello"} 51508
telemt_user_connections_current{user="hello"} 168
telemt_user_octets_from_client{user="hello"} 9125122936 (8.50 GB)
telemt_user_octets_to_client{user="hello"} 33635750868 (31.33 GB)
telemt_user_unique_ips_current{user="hello"} 70
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 39717.6 (11h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 70814
telemt_connections_bad_total 181
telemt_handshake_timeouts_total 435
telemt_upstream_connect_attempt_total 9473
telemt_upstream_connect_success_total 9472
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 9473
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4469
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4975
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 7507
telemt_me_reconnect_success_total 7476
telemt_me_reader_eof_total 7986
telemt_me_idle_close_by_peer_total 7986
telemt_me_route_drop_no_conn_total 30207
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 64343
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 136
telemt_desync_full_logged_total 41
telemt_desync_suppressed_total 95
telemt_desync_frames_bucket_total{bucket="1_2"} 29
telemt_desync_frames_bucket_total{bucket="3_10"} 59
telemt_desync_frames_bucket_total{bucket="gt_10"} 48
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 7553
telemt_me_writer_restored_same_endpoint_total 7465
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 77
telemt_user_connections_total{user="hello"} 64275
telemt_user_connections_current{user="hello"} 241
telemt_user_octets_from_client{user="hello"} 1279642652 (1.19 GB)
telemt_user_octets_to_client{user="hello"} 39507460868 (36.79 GB)
telemt_user_unique_ips_current{user="hello"} 79
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 14789.1 (4h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 23985
telemt_connections_bad_total 2804
telemt_handshake_timeouts_total 351
telemt_upstream_connect_attempt_total 5159
telemt_upstream_connect_success_total 5112
telemt_upstream_connect_fail_total 47
telemt_upstream_connect_attempts_per_request{bucket="1"} 5159
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2274
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2824
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 47
telemt_me_reconnect_attempts_total 98587
telemt_me_reconnect_success_total 4182
telemt_me_reader_eof_total 4320
telemt_me_idle_close_by_peer_total 4320
telemt_me_route_drop_no_conn_total 7536
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 20197
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 39
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 33
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 16
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 4143
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 4078
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_user_connections_total{user="hello"} 20337
telemt_user_connections_current{user="hello"} 96
telemt_user_octets_from_client{user="hello"} 179154009 (170.85 MB)
telemt_user_octets_to_client{user="hello"} 10838214727 (10.09 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 39716.9 (11h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 180585
telemt_connections_bad_total 22485
telemt_handshake_timeouts_total 1066
telemt_upstream_connect_attempt_total 8540
telemt_upstream_connect_success_total 8490
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 8540
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4316
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4173
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_reconnect_attempts_total 6519
telemt_me_reconnect_success_total 6485
telemt_me_reader_eof_total 6914
telemt_me_idle_close_by_peer_total 6914
telemt_me_route_drop_no_conn_total 85905
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 152179
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 48
telemt_desync_full_logged_total 21
telemt_desync_suppressed_total 27
telemt_desync_frames_bucket_total{bucket="1_2"} 10
telemt_desync_frames_bucket_total{bucket="3_10"} 20
telemt_desync_frames_bucket_total{bucket="gt_10"} 18
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 6525
telemt_me_writer_restored_same_endpoint_total 6458
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 40
telemt_user_connections_total{user="hello"} 150720
telemt_user_connections_current{user="hello"} 444
telemt_user_octets_from_client{user="hello"} 4077600588 (3.80 GB)
telemt_user_octets_to_client{user="hello"} 77494667192 (72.17 GB)
telemt_user_unique_ips_current{user="hello"} 184
telemt_user_unique_ips_recent_window{user="hello"} 74
```