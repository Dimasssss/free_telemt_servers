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

# Server Metrics 2026-03-14 07:43:27 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 173407.0 (48h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 664980
telemt_connections_bad_total 32381
telemt_handshake_timeouts_total 13122
telemt_upstream_connect_attempt_total 44136
telemt_upstream_connect_success_total 43913
telemt_upstream_connect_fail_total 223
telemt_upstream_connect_attempts_per_request{bucket="1"} 44136
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20084
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23677
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 152
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 223
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 5697
telemt_me_reconnect_attempts_total 39591
telemt_me_reconnect_success_total 34897
telemt_me_reader_eof_total 37318
telemt_me_idle_close_by_peer_total 37317
telemt_me_route_drop_no_conn_total 219944
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 566400
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2159
telemt_desync_full_logged_total 734
telemt_desync_suppressed_total 1425
telemt_desync_frames_bucket_total{bucket="1_2"} 466
telemt_desync_frames_bucket_total{bucket="3_10"} 794
telemt_desync_frames_bucket_total{bucket="gt_10"} 899
telemt_pool_swap_total 160
telemt_me_writer_removed_unexpected_total 35416
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 34877
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 519
telemt_user_connections_total{user="hello"} 566284
telemt_user_connections_current{user="hello"} 404
telemt_user_octets_from_client{user="hello"} 16528945490 (15.39 GB)
telemt_user_octets_to_client{user="hello"} 271493442364 (252.85 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 117
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 173299.9 (48h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 334813
telemt_connections_bad_total 2328
telemt_handshake_timeouts_total 2587
telemt_upstream_connect_attempt_total 151146
telemt_upstream_connect_success_total 149861
telemt_upstream_connect_fail_total 1285
telemt_upstream_connect_attempts_per_request{bucket="1"} 151146
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 110211
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37225
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2425
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1285
telemt_me_keepalive_timeout_total 4031
telemt_me_reconnect_attempts_total 178516
telemt_me_reconnect_success_total 37922
telemt_me_reader_eof_total 43327
telemt_me_idle_close_by_peer_total 43327
telemt_me_route_drop_no_conn_total 111368
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 213886
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 43
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 33
telemt_desync_full_logged_total 11
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 42676
telemt_me_refill_failed_total 4387
telemt_me_writer_restored_same_endpoint_total 37905
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 4754
telemt_user_connections_total{user="hello"} 316992
telemt_user_connections_current{user="hello"} 108
telemt_user_octets_from_client{user="hello"} 3286287883 (3.06 GB)
telemt_user_octets_to_client{user="hello"} 103461614223 (96.36 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 173263.6 (48h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 391631
telemt_connections_bad_total 3175
telemt_handshake_timeouts_total 35214
telemt_upstream_connect_attempt_total 45766
telemt_upstream_connect_success_total 45757
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 45766
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20925
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24764
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3492
telemt_me_reconnect_attempts_total 38371
telemt_me_reconnect_success_total 37085
telemt_me_reader_eof_total 39874
telemt_me_idle_close_by_peer_total 39874
telemt_me_route_drop_no_conn_total 141593
telemt_me_route_drop_channel_closed_total 20
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 339618
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 112
telemt_desync_full_logged_total 52
telemt_desync_suppressed_total 60
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 38
telemt_desync_frames_bucket_total{bucket="gt_10"} 62
telemt_pool_swap_total 164
telemt_me_writer_removed_unexpected_total 37533
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 37064
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 448
telemt_user_connections_total{user="hello"} 339391
telemt_user_connections_current{user="hello"} 155
telemt_user_octets_from_client{user="hello"} 13586539460 (12.65 GB)
telemt_user_octets_to_client{user="hello"} 137832296296 (128.37 GB)
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 173239.0 (48h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 493903
telemt_connections_bad_total 16265
telemt_handshake_timeouts_total 4540
telemt_upstream_connect_attempt_total 76222
telemt_upstream_connect_success_total 65625
telemt_upstream_connect_fail_total 10597
telemt_upstream_connect_attempts_per_request{bucket="1"} 76222
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38609
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26664
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 343
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10597
telemt_me_keepalive_timeout_total 5440
telemt_me_reconnect_attempts_total 144023
telemt_me_reconnect_success_total 37960
telemt_me_reader_eof_total 42499
telemt_me_idle_close_by_peer_total 42491
telemt_me_route_drop_no_conn_total 179052
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 420936
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 33
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1796
telemt_desync_full_logged_total 537
telemt_desync_suppressed_total 1259
telemt_desync_frames_bucket_total{bucket="1_2"} 428
telemt_desync_frames_bucket_total{bucket="3_10"} 682
telemt_desync_frames_bucket_total{bucket="gt_10"} 686
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 41708
telemt_me_refill_failed_total 3307
telemt_me_writer_restored_same_endpoint_total 37950
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3748
telemt_user_connections_total{user="hello"} 439815
telemt_user_connections_current{user="hello"} 178
telemt_user_octets_from_client{user="hello"} 9465500763 (8.82 GB)
telemt_user_octets_to_client{user="hello"} 180258934144 (167.88 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 123410.6 (34h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 201391
telemt_connections_bad_total 29836
telemt_handshake_timeouts_total 1753
telemt_upstream_connect_attempt_total 43344
telemt_upstream_connect_success_total 42927
telemt_upstream_connect_fail_total 417
telemt_upstream_connect_attempts_per_request{bucket="1"} 43344
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21495
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21290
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 142
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 417
telemt_me_keepalive_timeout_total 2529
telemt_me_reconnect_attempts_total 45316
telemt_me_reconnect_success_total 31882
telemt_me_reader_eof_total 34133
telemt_me_idle_close_by_peer_total 34133
telemt_me_route_drop_no_conn_total 60199
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 159394
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 701
telemt_desync_full_logged_total 171
telemt_desync_suppressed_total 530
telemt_desync_frames_bucket_total{bucket="1_2"} 114
telemt_desync_frames_bucket_total{bucket="3_10"} 335
telemt_desync_frames_bucket_total{bucket="gt_10"} 252
telemt_pool_swap_total 96
telemt_me_writer_removed_unexpected_total 32598
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 31864
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 716
telemt_user_connections_total{user="hello"} 164144
telemt_user_connections_current{user="hello"} 83
telemt_user_octets_from_client{user="hello"} 2424934989 (2.26 GB)
telemt_user_octets_to_client{user="hello"} 77345977055 (72.03 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 173195.2 (48h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 993178
telemt_connections_bad_total 36098
telemt_handshake_timeouts_total 26179
telemt_upstream_connect_attempt_total 35921
telemt_upstream_connect_success_total 35732
telemt_upstream_connect_fail_total 189
telemt_upstream_connect_attempts_per_request{bucket="1"} 35921
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16809
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18882
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 189
telemt_me_keepalive_timeout_total 4722
telemt_me_reconnect_attempts_total 31843
telemt_me_reconnect_success_total 27161
telemt_me_reader_eof_total 29161
telemt_me_idle_close_by_peer_total 29158
telemt_me_route_drop_no_conn_total 467253
telemt_me_route_drop_channel_closed_total 25
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 920190
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 770
telemt_desync_full_logged_total 254
telemt_desync_suppressed_total 516
telemt_desync_frames_bucket_total{bucket="1_2"} 257
telemt_desync_frames_bucket_total{bucket="3_10"} 253
telemt_desync_frames_bucket_total{bucket="gt_10"} 260
telemt_pool_swap_total 165
telemt_me_writer_removed_unexpected_total 27654
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 27154
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 493
telemt_user_connections_total{user="hello"} 892834
telemt_user_connections_current{user="hello"} 437
telemt_user_octets_from_client{user="hello"} 15256731984 (14.21 GB)
telemt_user_octets_to_client{user="hello"} 448077813708 (417.30 GB)
telemt_user_unique_ips_current{user="hello"} 165
telemt_user_unique_ips_recent_window{user="hello"} 75
```