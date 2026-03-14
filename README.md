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

# Server Metrics 2026-03-14 06:21:56 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 168516.2 (46h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 647768
telemt_connections_bad_total 32325
telemt_handshake_timeouts_total 13026
telemt_upstream_connect_attempt_total 42936
telemt_upstream_connect_success_total 42719
telemt_upstream_connect_fail_total 217
telemt_upstream_connect_attempts_per_request{bucket="1"} 42936
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19501
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23066
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 152
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 217
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 5606
telemt_me_reconnect_attempts_total 38614
telemt_me_reconnect_success_total 33925
telemt_me_reader_eof_total 36281
telemt_me_idle_close_by_peer_total 36280
telemt_me_route_drop_no_conn_total 212882
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 549837
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1988
telemt_desync_full_logged_total 680
telemt_desync_suppressed_total 1308
telemt_desync_frames_bucket_total{bucket="1_2"} 433
telemt_desync_frames_bucket_total{bucket="3_10"} 727
telemt_desync_frames_bucket_total{bucket="gt_10"} 828
telemt_pool_swap_total 156
telemt_me_writer_removed_unexpected_total 34438
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 33905
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 513
telemt_user_connections_total{user="hello"} 549722
telemt_user_connections_current{user="hello"} 303
telemt_user_octets_from_client{user="hello"} 16075061538 (14.97 GB)
telemt_user_octets_to_client{user="hello"} 266728791356 (248.41 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 91
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 168409.0 (46h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 326639
telemt_connections_bad_total 2307
telemt_handshake_timeouts_total 2403
telemt_upstream_connect_attempt_total 149600
telemt_upstream_connect_success_total 148345
telemt_upstream_connect_fail_total 1255
telemt_upstream_connect_attempts_per_request{bucket="1"} 149600
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 109603
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36320
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2422
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1255
telemt_me_keepalive_timeout_total 3986
telemt_me_reconnect_attempts_total 175950
telemt_me_reconnect_success_total 36641
telemt_me_reader_eof_total 41952
telemt_me_idle_close_by_peer_total 41952
telemt_me_route_drop_no_conn_total 105996
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 206297
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
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 41335
telemt_me_refill_failed_total 4347
telemt_me_writer_restored_same_endpoint_total 36624
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 4694
telemt_user_connections_total{user="hello"} 309404
telemt_user_connections_current{user="hello"} 105
telemt_user_octets_from_client{user="hello"} 3232153959 (3.01 GB)
telemt_user_octets_to_client{user="hello"} 100834632931 (93.91 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 168372.8 (46h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 381124
telemt_connections_bad_total 2967
telemt_handshake_timeouts_total 34948
telemt_upstream_connect_attempt_total 44524
telemt_upstream_connect_success_total 44515
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 44524
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20319
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24128
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3468
telemt_me_reconnect_attempts_total 37364
telemt_me_reconnect_success_total 36079
telemt_me_reader_eof_total 38795
telemt_me_idle_close_by_peer_total 38795
telemt_me_route_drop_no_conn_total 137367
telemt_me_route_drop_channel_closed_total 20
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 329984
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
telemt_pool_swap_total 159
telemt_me_writer_removed_unexpected_total 36515
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 36058
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 436
telemt_user_connections_total{user="hello"} 329757
telemt_user_connections_current{user="hello"} 135
telemt_user_octets_from_client{user="hello"} 13391580168 (12.47 GB)
telemt_user_octets_to_client{user="hello"} 130833194848 (121.85 GB)
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 168348.3 (46h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 481841
telemt_connections_bad_total 15658
telemt_handshake_timeouts_total 4488
telemt_upstream_connect_attempt_total 74823
telemt_upstream_connect_success_total 64260
telemt_upstream_connect_fail_total 10563
telemt_upstream_connect_attempts_per_request{bucket="1"} 74823
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37990
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25920
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 341
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10563
telemt_me_keepalive_timeout_total 5387
telemt_me_reconnect_attempts_total 142907
telemt_me_reconnect_success_total 36849
telemt_me_reader_eof_total 41323
telemt_me_idle_close_by_peer_total 41315
telemt_me_route_drop_no_conn_total 173809
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 409824
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 33
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1757
telemt_desync_full_logged_total 521
telemt_desync_suppressed_total 1236
telemt_desync_frames_bucket_total{bucket="1_2"} 418
telemt_desync_frames_bucket_total{bucket="3_10"} 667
telemt_desync_frames_bucket_total{bucket="gt_10"} 672
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 40584
telemt_me_refill_failed_total 3307
telemt_me_writer_restored_same_endpoint_total 36839
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3735
telemt_user_connections_total{user="hello"} 428669
telemt_user_connections_current{user="hello"} 187
telemt_user_octets_from_client{user="hello"} 9285493307 (8.65 GB)
telemt_user_octets_to_client{user="hello"} 173122576888 (161.23 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 118519.8 (32h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 193468
telemt_connections_bad_total 28688
telemt_handshake_timeouts_total 1667
telemt_upstream_connect_attempt_total 42148
telemt_upstream_connect_success_total 41751
telemt_upstream_connect_fail_total 397
telemt_upstream_connect_attempts_per_request{bucket="1"} 42148
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20935
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20677
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 139
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 397
telemt_me_keepalive_timeout_total 2452
telemt_me_reconnect_attempts_total 44397
telemt_me_reconnect_success_total 30971
telemt_me_reader_eof_total 33152
telemt_me_idle_close_by_peer_total 33152
telemt_me_route_drop_no_conn_total 57431
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 152953
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 623
telemt_desync_full_logged_total 147
telemt_desync_suppressed_total 476
telemt_desync_frames_bucket_total{bucket="1_2"} 99
telemt_desync_frames_bucket_total{bucket="3_10"} 306
telemt_desync_frames_bucket_total{bucket="gt_10"} 218
telemt_pool_swap_total 90
telemt_me_writer_removed_unexpected_total 31673
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 30953
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 702
telemt_user_connections_total{user="hello"} 157702
telemt_user_connections_current{user="hello"} 55
telemt_user_octets_from_client{user="hello"} 2357863329 (2.20 GB)
telemt_user_octets_to_client{user="hello"} 71708092803 (66.78 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 21
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 168304.2 (46h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 960673
telemt_connections_bad_total 36019
telemt_handshake_timeouts_total 25990
telemt_upstream_connect_attempt_total 34922
telemt_upstream_connect_success_total 34735
telemt_upstream_connect_fail_total 187
telemt_upstream_connect_attempts_per_request{bucket="1"} 34922
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16325
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18369
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 187
telemt_me_keepalive_timeout_total 4693
telemt_me_reconnect_attempts_total 31106
telemt_me_reconnect_success_total 26429
telemt_me_reader_eof_total 28367
telemt_me_idle_close_by_peer_total 28364
telemt_me_route_drop_no_conn_total 453022
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 890474
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 760
telemt_desync_full_logged_total 250
telemt_desync_suppressed_total 510
telemt_desync_frames_bucket_total{bucket="1_2"} 256
telemt_desync_frames_bucket_total{bucket="3_10"} 248
telemt_desync_frames_bucket_total{bucket="gt_10"} 256
telemt_pool_swap_total 159
telemt_me_writer_removed_unexpected_total 26911
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 26422
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 482
telemt_user_connections_total{user="hello"} 863124
telemt_user_connections_current{user="hello"} 388
telemt_user_octets_from_client{user="hello"} 14908249052 (13.88 GB)
telemt_user_octets_to_client{user="hello"} 437992772628 (407.91 GB)
telemt_user_unique_ips_current{user="hello"} 149
telemt_user_unique_ips_recent_window{user="hello"} 55
```