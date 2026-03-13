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

# Server Metrics 2026-03-13 15:56:11 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 116572.1 (32h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 484340
telemt_connections_bad_total 3511
telemt_handshake_timeouts_total 8880
telemt_upstream_connect_attempt_total 29094
telemt_upstream_connect_success_total 28954
telemt_upstream_connect_fail_total 140
telemt_upstream_connect_attempts_per_request{bucket="1"} 29094
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13071
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15819
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 140
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2506
telemt_me_reconnect_attempts_total 26658
telemt_me_reconnect_success_total 23122
telemt_me_reader_eof_total 24703
telemt_me_idle_close_by_peer_total 24702
telemt_me_route_drop_no_conn_total 158277
telemt_me_route_drop_channel_closed_total 28
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 425281
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1380
telemt_desync_full_logged_total 485
telemt_desync_suppressed_total 895
telemt_desync_frames_bucket_total{bucket="1_2"} 302
telemt_desync_frames_bucket_total{bucket="3_10"} 495
telemt_desync_frames_bucket_total{bucket="gt_10"} 583
telemt_pool_swap_total 106
telemt_me_writer_removed_unexpected_total 23477
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 23106
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 355
telemt_user_connections_total{user="hello"} 424858
telemt_user_connections_current{user="hello"} 388
telemt_user_octets_from_client{user="hello"} 7557582924 (7.04 GB)
telemt_user_octets_to_client{user="hello"} 198151455168 (184.54 GB)
telemt_user_unique_ips_current{user="hello"} 108
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 116465.2 (32h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 233508
telemt_connections_bad_total 1840
telemt_handshake_timeouts_total 1678
telemt_upstream_connect_attempt_total 90179
telemt_upstream_connect_success_total 89390
telemt_upstream_connect_fail_total 789
telemt_upstream_connect_attempts_per_request{bucket="1"} 90179
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 63985
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24373
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1032
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 789
telemt_me_keepalive_timeout_total 1417
telemt_me_reconnect_attempts_total 116309
telemt_me_reconnect_success_total 26024
telemt_me_reader_eof_total 29602
telemt_me_idle_close_by_peer_total 29602
telemt_me_route_drop_no_conn_total 81710
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 163605
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 28
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 32
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 18
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 29069
telemt_me_refill_failed_total 2817
telemt_me_writer_restored_same_endpoint_total 26007
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 3045
telemt_user_connections_total{user="hello"} 220932
telemt_user_connections_current{user="hello"} 221
telemt_user_octets_from_client{user="hello"} 2289529844 (2.13 GB)
telemt_user_octets_to_client{user="hello"} 69324256057 (64.56 GB)
telemt_user_msgs_from_client{user="hello"} 889100
telemt_user_msgs_to_client{user="hello"} 5447940
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 116429.0 (32h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 280884
telemt_connections_bad_total 2438
telemt_handshake_timeouts_total 13487
telemt_upstream_connect_attempt_total 31211
telemt_upstream_connect_success_total 31207
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 31211
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14472
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16704
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2406
telemt_me_reconnect_attempts_total 26555
telemt_me_reconnect_success_total 25334
telemt_me_reader_eof_total 27159
telemt_me_idle_close_by_peer_total 27159
telemt_me_route_drop_no_conn_total 101532
telemt_me_route_drop_channel_closed_total 16
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 254969
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 103
telemt_desync_full_logged_total 47
telemt_desync_suppressed_total 56
telemt_desync_frames_bucket_total{bucket="1_2"} 9
telemt_desync_frames_bucket_total{bucket="3_10"} 34
telemt_desync_frames_bucket_total{bucket="gt_10"} 60
telemt_pool_swap_total 106
telemt_me_writer_removed_unexpected_total 25616
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 25314
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 282
telemt_user_connections_total{user="hello"} 254883
telemt_user_connections_current{user="hello"} 141
telemt_user_octets_from_client{user="hello"} 9668901524 (9.00 GB)
telemt_user_octets_to_client{user="hello"} 107841936968 (100.44 GB)
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 116404.5 (32h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 381733
telemt_connections_bad_total 15057
telemt_handshake_timeouts_total 3771
telemt_upstream_connect_attempt_total 43098
telemt_upstream_connect_success_total 32916
telemt_upstream_connect_fail_total 10182
telemt_upstream_connect_attempts_per_request{bucket="1"} 43098
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16562
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16134
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 211
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10182
telemt_me_keepalive_timeout_total 4166
telemt_me_reconnect_attempts_total 105490
telemt_me_reconnect_success_total 24041
telemt_me_reader_eof_total 27294
telemt_me_idle_close_by_peer_total 27287
telemt_me_route_drop_no_conn_total 136776
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 331226
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1327
telemt_desync_full_logged_total 394
telemt_desync_suppressed_total 933
telemt_desync_frames_bucket_total{bucket="1_2"} 328
telemt_desync_frames_bucket_total{bucket="3_10"} 502
telemt_desync_frames_bucket_total{bucket="gt_10"} 497
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 26893
telemt_me_refill_failed_total 2540
telemt_me_writer_restored_same_endpoint_total 24031
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 2852
telemt_user_connections_total{user="hello"} 334137
telemt_user_connections_current{user="hello"} 168
telemt_user_octets_from_client{user="hello"} 6954275766 (6.48 GB)
telemt_user_octets_to_client{user="hello"} 124247692809 (115.71 GB)
telemt_user_msgs_from_client{user="hello"} 68310
telemt_user_msgs_to_client{user="hello"} 114408
telemt_user_unique_ips_current{user="hello"} 64
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 66576.0 (18h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 104456
telemt_connections_bad_total 13350
telemt_handshake_timeouts_total 1320
telemt_upstream_connect_attempt_total 26840
telemt_upstream_connect_success_total 26607
telemt_upstream_connect_fail_total 233
telemt_upstream_connect_attempts_per_request{bucket="1"} 26840
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13851
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12680
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 76
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 233
telemt_me_keepalive_timeout_total 1057
telemt_me_reconnect_attempts_total 29559
telemt_me_reconnect_success_total 18386
telemt_me_reader_eof_total 19719
telemt_me_idle_close_by_peer_total 19719
telemt_me_route_drop_no_conn_total 32174
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 81494
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 390
telemt_desync_full_logged_total 76
telemt_desync_suppressed_total 314
telemt_desync_frames_bucket_total{bucket="1_2"} 52
telemt_desync_frames_bucket_total{bucket="3_10"} 214
telemt_desync_frames_bucket_total{bucket="gt_10"} 124
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 18892
telemt_me_refill_failed_total 347
telemt_me_writer_restored_same_endpoint_total 18368
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 506
telemt_user_connections_total{user="hello"} 86393
telemt_user_connections_current{user="hello"} 125
telemt_user_octets_from_client{user="hello"} 1001089461 (954.71 MB)
telemt_user_octets_to_client{user="hello"} 26393615299 (24.58 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 116361.6 (32h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 704967
telemt_connections_bad_total 24106
telemt_handshake_timeouts_total 23349
telemt_upstream_connect_attempt_total 24396
telemt_upstream_connect_success_total 24274
telemt_upstream_connect_fail_total 122
telemt_upstream_connect_attempts_per_request{bucket="1"} 24396
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11388
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12861
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 122
telemt_me_keepalive_timeout_total 2555
telemt_me_reconnect_attempts_total 23108
telemt_me_reconnect_success_total 18479
telemt_me_reader_eof_total 19831
telemt_me_idle_close_by_peer_total 19828
telemt_me_route_drop_no_conn_total 332665
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 661394
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 665
telemt_desync_full_logged_total 215
telemt_desync_suppressed_total 450
telemt_desync_frames_bucket_total{bucket="1_2"} 236
telemt_desync_frames_bucket_total{bucket="3_10"} 219
telemt_desync_frames_bucket_total{bucket="gt_10"} 210
telemt_pool_swap_total 108
telemt_me_writer_removed_unexpected_total 18858
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 18472
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 379
telemt_user_connections_total{user="hello"} 634341
telemt_user_connections_current{user="hello"} 472
telemt_user_octets_from_client{user="hello"} 10665486344 (9.93 GB)
telemt_user_octets_to_client{user="hello"} 326415290712 (304.00 GB)
telemt_user_unique_ips_current{user="hello"} 160
telemt_user_unique_ips_recent_window{user="hello"} 78
```