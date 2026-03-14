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

# Server Metrics 2026-03-14 08:08:55 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 174934.6 (48h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 672052
telemt_connections_bad_total 32445
telemt_handshake_timeouts_total 13192
telemt_upstream_connect_attempt_total 44485
telemt_upstream_connect_success_total 44260
telemt_upstream_connect_fail_total 225
telemt_upstream_connect_attempts_per_request{bucket="1"} 44485
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20262
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23846
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 152
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 225
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 5722
telemt_me_reconnect_attempts_total 39851
telemt_me_reconnect_success_total 35156
telemt_me_reader_eof_total 37589
telemt_me_idle_close_by_peer_total 37588
telemt_me_route_drop_no_conn_total 222396
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 573045
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2222
telemt_desync_full_logged_total 754
telemt_desync_suppressed_total 1468
telemt_desync_frames_bucket_total{bucket="1_2"} 478
telemt_desync_frames_bucket_total{bucket="3_10"} 816
telemt_desync_frames_bucket_total{bucket="gt_10"} 928
telemt_pool_swap_total 161
telemt_me_writer_removed_unexpected_total 35679
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 35136
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 523
telemt_user_connections_total{user="hello"} 572927
telemt_user_connections_current{user="hello"} 326
telemt_user_octets_from_client{user="hello"} 16638686810 (15.50 GB)
telemt_user_octets_to_client{user="hello"} 274910162656 (256.03 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 102
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 174827.2 (48h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 338140
telemt_connections_bad_total 2328
telemt_handshake_timeouts_total 2690
telemt_upstream_connect_attempt_total 151655
telemt_upstream_connect_success_total 150358
telemt_upstream_connect_fail_total 1297
telemt_upstream_connect_attempts_per_request{bucket="1"} 151655
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 110419
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37511
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2428
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1297
telemt_me_keepalive_timeout_total 4049
telemt_me_reconnect_attempts_total 178927
telemt_me_reconnect_success_total 38329
telemt_me_reader_eof_total 43772
telemt_me_idle_close_by_peer_total 43772
telemt_me_route_drop_no_conn_total 112922
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 216855
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
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 43088
telemt_me_refill_failed_total 4387
telemt_me_writer_restored_same_endpoint_total 38312
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 4759
telemt_user_connections_total{user="hello"} 319961
telemt_user_connections_current{user="hello"} 113
telemt_user_octets_from_client{user="hello"} 3305441047 (3.08 GB)
telemt_user_octets_to_client{user="hello"} 104098061999 (96.95 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 174791.0 (48h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 395538
telemt_connections_bad_total 3181
telemt_handshake_timeouts_total 35321
telemt_upstream_connect_attempt_total 46121
telemt_upstream_connect_success_total 46112
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 46121
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21091
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24953
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3504
telemt_me_reconnect_attempts_total 38640
telemt_me_reconnect_success_total 37351
telemt_me_reader_eof_total 40172
telemt_me_idle_close_by_peer_total 40172
telemt_me_route_drop_no_conn_total 142966
telemt_me_route_drop_channel_closed_total 21
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 343193
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
telemt_pool_swap_total 166
telemt_me_writer_removed_unexpected_total 37805
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 37330
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 454
telemt_user_connections_total{user="hello"} 342951
telemt_user_connections_current{user="hello"} 159
telemt_user_octets_from_client{user="hello"} 13622355636 (12.69 GB)
telemt_user_octets_to_client{user="hello"} 141843332340 (132.10 GB)
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 174766.4 (48h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 497756
telemt_connections_bad_total 16275
telemt_handshake_timeouts_total 4556
telemt_upstream_connect_attempt_total 76669
telemt_upstream_connect_success_total 66050
telemt_upstream_connect_fail_total 10619
telemt_upstream_connect_attempts_per_request{bucket="1"} 76669
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38809
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26889
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 343
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10619
telemt_me_keepalive_timeout_total 5457
telemt_me_reconnect_attempts_total 145929
telemt_me_reconnect_success_total 38298
telemt_me_reader_eof_total 42890
telemt_me_idle_close_by_peer_total 42882
telemt_me_route_drop_no_conn_total 180409
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 424617
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 34
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1840
telemt_desync_full_logged_total 547
telemt_desync_suppressed_total 1293
telemt_desync_frames_bucket_total{bucket="1_2"} 432
telemt_desync_frames_bucket_total{bucket="3_10"} 704
telemt_desync_frames_bucket_total{bucket="gt_10"} 704
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 42099
telemt_me_refill_failed_total 3356
telemt_me_writer_restored_same_endpoint_total 38288
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3801
telemt_user_connections_total{user="hello"} 443493
telemt_user_connections_current{user="hello"} 140
telemt_user_octets_from_client{user="hello"} 9518436875 (8.86 GB)
telemt_user_octets_to_client{user="hello"} 181880901784 (169.39 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 124938.0 (34h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 204536
telemt_connections_bad_total 30803
telemt_handshake_timeouts_total 1764
telemt_upstream_connect_attempt_total 43834
telemt_upstream_connect_success_total 43414
telemt_upstream_connect_fail_total 420
telemt_upstream_connect_attempts_per_request{bucket="1"} 43834
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21718
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21553
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 143
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 420
telemt_me_keepalive_timeout_total 2549
telemt_me_reconnect_attempts_total 45759
telemt_me_reconnect_success_total 32323
telemt_me_reader_eof_total 34589
telemt_me_idle_close_by_peer_total 34589
telemt_me_route_drop_no_conn_total 61219
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 161474
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
telemt_me_writer_removed_unexpected_total 33042
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 32305
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 719
telemt_user_connections_total{user="hello"} 166234
telemt_user_connections_current{user="hello"} 79
telemt_user_octets_from_client{user="hello"} 2454950373 (2.29 GB)
telemt_user_octets_to_client{user="hello"} 78997708507 (73.57 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 174722.5 (48h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1003340
telemt_connections_bad_total 36284
telemt_handshake_timeouts_total 26217
telemt_upstream_connect_attempt_total 36223
telemt_upstream_connect_success_total 36029
telemt_upstream_connect_fail_total 194
telemt_upstream_connect_attempts_per_request{bucket="1"} 36223
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16948
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19040
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 194
telemt_me_keepalive_timeout_total 4739
telemt_me_reconnect_attempts_total 32052
telemt_me_reconnect_success_total 27370
telemt_me_reader_eof_total 29377
telemt_me_idle_close_by_peer_total 29374
telemt_me_route_drop_no_conn_total 471803
telemt_me_route_drop_channel_closed_total 25
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 929848
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
telemt_pool_swap_total 166
telemt_me_writer_removed_unexpected_total 27863
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 27363
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 493
telemt_user_connections_total{user="hello"} 902485
telemt_user_connections_current{user="hello"} 401
telemt_user_octets_from_client{user="hello"} 15360564308 (14.31 GB)
telemt_user_octets_to_client{user="hello"} 450468337060 (419.53 GB)
telemt_user_unique_ips_current{user="hello"} 161
telemt_user_unique_ips_recent_window{user="hello"} 61
```