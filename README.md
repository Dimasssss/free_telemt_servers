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

# Server Metrics 2026-03-13 00:38:56 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 61532.9 (17h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 257877
telemt_connections_bad_total 2764
telemt_handshake_timeouts_total 5289
telemt_upstream_connect_attempt_total 15507
telemt_upstream_connect_success_total 15439
telemt_upstream_connect_fail_total 68
telemt_upstream_connect_attempts_per_request{bucket="1"} 15507
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6831
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8562
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 68
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1497
telemt_me_reconnect_attempts_total 15795
telemt_me_reconnect_success_total 12322
telemt_me_reader_eof_total 13143
telemt_me_idle_close_by_peer_total 13142
telemt_me_route_drop_no_conn_total 80190
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 213668
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 722
telemt_desync_full_logged_total 269
telemt_desync_suppressed_total 453
telemt_desync_frames_bucket_total{bucket="1_2"} 125
telemt_desync_frames_bucket_total{bucket="3_10"} 270
telemt_desync_frames_bucket_total{bucket="gt_10"} 327
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 12567
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 12306
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 245
telemt_user_connections_total{user="hello"} 213436
telemt_user_connections_current{user="hello"} 220
telemt_user_octets_from_client{user="hello"} 3902003520 (3.63 GB)
telemt_user_octets_to_client{user="hello"} 108270653884 (100.83 GB)
telemt_user_unique_ips_current{user="hello"} 69
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 61425.9 (17h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 119385
telemt_connections_bad_total 711
telemt_handshake_timeouts_total 969
telemt_upstream_connect_attempt_total 34895
telemt_upstream_connect_success_total 34479
telemt_upstream_connect_fail_total 416
telemt_upstream_connect_attempts_per_request{bucket="1"} 34895
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21971
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12007
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 501
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 416
telemt_me_keepalive_timeout_total 433
telemt_me_reconnect_attempts_total 57774
telemt_me_reconnect_success_total 14878
telemt_me_reader_eof_total 16601
telemt_me_idle_close_by_peer_total 16601
telemt_me_route_drop_no_conn_total 42815
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 96782
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 14
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
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 16326
telemt_me_refill_failed_total 1339
telemt_me_writer_restored_same_endpoint_total 14863
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1448
telemt_user_connections_total{user="hello"} 113282
telemt_user_connections_current{user="hello"} 79
telemt_user_octets_from_client{user="hello"} 1231732384 (1.15 GB)
telemt_user_octets_to_client{user="hello"} 34637493327 (32.26 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 61389.4 (17h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 144835
telemt_connections_bad_total 1668
telemt_handshake_timeouts_total 2329
telemt_upstream_connect_attempt_total 16886
telemt_upstream_connect_success_total 16884
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 16886
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7887
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8976
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 358
telemt_me_reconnect_attempts_total 14894
telemt_me_reconnect_success_total 13742
telemt_me_reader_eof_total 14694
telemt_me_idle_close_by_peer_total 14694
telemt_me_route_drop_no_conn_total 55118
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 135419
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 52
telemt_desync_full_logged_total 26
telemt_desync_suppressed_total 26
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 13
telemt_desync_frames_bucket_total{bucket="gt_10"} 36
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 13913
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 13722
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 171
telemt_user_connections_total{user="hello"} 135383
telemt_user_connections_current{user="hello"} 70
telemt_user_octets_from_client{user="hello"} 2625844320 (2.45 GB)
telemt_user_octets_to_client{user="hello"} 62236247160 (57.96 GB)
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 61365.2 (17h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 207837
telemt_connections_bad_total 13285
telemt_handshake_timeouts_total 1426
telemt_upstream_connect_attempt_total 28948
telemt_upstream_connect_success_total 19195
telemt_upstream_connect_fail_total 9753
telemt_upstream_connect_attempts_per_request{bucket="1"} 28948
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9930
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9112
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 145
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9753
telemt_me_keepalive_timeout_total 3197
telemt_me_reconnect_attempts_total 47851
telemt_me_reconnect_success_total 13227
telemt_me_reader_eof_total 14769
telemt_me_idle_close_by_peer_total 14762
telemt_me_route_drop_no_conn_total 74233
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 171660
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 499
telemt_desync_full_logged_total 143
telemt_desync_suppressed_total 356
telemt_desync_frames_bucket_total{bucket="1_2"} 124
telemt_desync_frames_bucket_total{bucket="3_10"} 186
telemt_desync_frames_bucket_total{bucket="gt_10"} 189
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 14508
telemt_me_refill_failed_total 1078
telemt_me_writer_restored_same_endpoint_total 13217
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1281
telemt_user_connections_total{user="hello"} 174414
telemt_user_connections_current{user="hello"} 108
telemt_user_octets_from_client{user="hello"} 3010444514 (2.80 GB)
telemt_user_octets_to_client{user="hello"} 71858980537 (66.92 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 11536.8 (3h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10357
telemt_connections_bad_total 2126
telemt_handshake_timeouts_total 22
telemt_upstream_connect_attempt_total 3614
telemt_upstream_connect_success_total 3579
telemt_upstream_connect_fail_total 35
telemt_upstream_connect_attempts_per_request{bucket="1"} 3614
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1582
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1981
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 35
telemt_me_keepalive_timeout_total 63
telemt_me_reconnect_attempts_total 2995
telemt_me_reconnect_success_total 2989
telemt_me_reader_eof_total 3177
telemt_me_idle_close_by_peer_total 3177
telemt_me_route_drop_no_conn_total 3198
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7864
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 3003
telemt_me_writer_restored_same_endpoint_total 2973
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 7864
telemt_user_connections_current{user="hello"} 28
telemt_user_octets_from_client{user="hello"} 32114080 (30.63 MB)
telemt_user_octets_to_client{user="hello"} 2753188156 (2.56 GB)
telemt_user_unique_ips_current{user="hello"} 20
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 61321.7 (17h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 346884
telemt_connections_bad_total 6494
telemt_handshake_timeouts_total 2577
telemt_upstream_connect_attempt_total 12937
telemt_upstream_connect_success_total 12867
telemt_upstream_connect_fail_total 70
telemt_upstream_connect_attempts_per_request{bucket="1"} 12937
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6036
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6811
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 70
telemt_me_keepalive_timeout_total 1330
telemt_me_reconnect_attempts_total 13399
telemt_me_reconnect_success_total 9782
telemt_me_reader_eof_total 10497
telemt_me_idle_close_by_peer_total 10495
telemt_me_route_drop_no_conn_total 155158
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 339524
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 300
telemt_desync_full_logged_total 117
telemt_desync_suppressed_total 183
telemt_desync_frames_bucket_total{bucket="1_2"} 74
telemt_desync_frames_bucket_total{bucket="3_10"} 112
telemt_desync_frames_bucket_total{bucket="gt_10"} 114
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 10016
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 9775
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 234
telemt_user_connections_total{user="hello"} 327825
telemt_user_connections_current{user="hello"} 276
telemt_user_octets_from_client{user="hello"} 5588906620 (5.21 GB)
telemt_user_octets_to_client{user="hello"} 176096318496 (164.00 GB)
telemt_user_unique_ips_current{user="hello"} 93
telemt_user_unique_ips_recent_window{user="hello"} 26
```