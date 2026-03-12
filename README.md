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

# Server Metrics 2026-03-12 16:07:48 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 30865.6 (8h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 163815
telemt_connections_bad_total 2027
telemt_handshake_timeouts_total 4753
telemt_upstream_connect_attempt_total 7510
telemt_upstream_connect_success_total 7481
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 7510
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3354
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4120
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 289
telemt_me_reconnect_attempts_total 5921
telemt_me_reconnect_success_total 5877
telemt_me_reader_eof_total 6181
telemt_me_idle_close_by_peer_total 6180
telemt_me_route_drop_no_conn_total 47605
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 140930
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 606
telemt_desync_full_logged_total 227
telemt_desync_suppressed_total 379
telemt_desync_frames_bucket_total{bucket="1_2"} 113
telemt_desync_frames_bucket_total{bucket="3_10"} 233
telemt_desync_frames_bucket_total{bucket="gt_10"} 260
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 5934
telemt_me_writer_restored_same_endpoint_total 5861
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 140895
telemt_user_connections_current{user="hello"} 379
telemt_user_octets_from_client{user="hello"} 2379389332 (2.22 GB)
telemt_user_octets_to_client{user="hello"} 54367302024 (50.63 GB)
telemt_user_unique_ips_current{user="hello"} 113
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 30759.2 (8h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 68615
telemt_connections_bad_total 457
telemt_handshake_timeouts_total 527
telemt_upstream_connect_attempt_total 9934
telemt_upstream_connect_success_total 9725
telemt_upstream_connect_fail_total 209
telemt_upstream_connect_attempts_per_request{bucket="1"} 9934
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3852
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5811
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 209
telemt_me_keepalive_timeout_total 260
telemt_me_reconnect_attempts_total 28113
telemt_me_reconnect_success_total 8146
telemt_me_reader_eof_total 8927
telemt_me_idle_close_by_peer_total 8927
telemt_me_route_drop_no_conn_total 30444
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 65220
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 7
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
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 8825
telemt_me_refill_failed_total 623
telemt_me_writer_restored_same_endpoint_total 8131
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 679
telemt_user_connections_total{user="hello"} 65211
telemt_user_connections_current{user="hello"} 143
telemt_user_octets_from_client{user="hello"} 722672924 (689.19 MB)
telemt_user_octets_to_client{user="hello"} 18429102172 (17.16 GB)
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 30722.4 (8h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 93272
telemt_connections_bad_total 1480
telemt_handshake_timeouts_total 1887
telemt_upstream_connect_attempt_total 8401
telemt_upstream_connect_success_total 8401
telemt_upstream_connect_attempts_per_request{bucket="1"} 8401
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4058
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4333
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 159
telemt_me_reconnect_attempts_total 6834
telemt_me_reconnect_success_total 6776
telemt_me_reader_eof_total 7171
telemt_me_idle_close_by_peer_total 7171
telemt_me_route_drop_no_conn_total 34349
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 86040
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 20
telemt_desync_full_logged_total 11
telemt_desync_suppressed_total 9
telemt_desync_frames_bucket_total{bucket="1_2"} 1
telemt_desync_frames_bucket_total{bucket="3_10"} 8
telemt_desync_frames_bucket_total{bucket="gt_10"} 11
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 6834
telemt_me_writer_restored_same_endpoint_total 6756
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 58
telemt_user_connections_total{user="hello"} 86014
telemt_user_connections_current{user="hello"} 148
telemt_user_octets_from_client{user="hello"} 2163866520 (2.02 GB)
telemt_user_octets_to_client{user="hello"} 43942746524 (40.92 GB)
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 30697.8 (8h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 127733
telemt_connections_bad_total 13051
telemt_handshake_timeouts_total 977
telemt_upstream_connect_attempt_total 7105
telemt_upstream_connect_success_total 6895
telemt_upstream_connect_fail_total 209
telemt_upstream_connect_attempts_per_request{bucket="1"} 7104
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3170
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3698
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 209
telemt_me_keepalive_timeout_total 302
telemt_me_reconnect_attempts_total 27906
telemt_me_reconnect_success_total 5324
telemt_me_reader_eof_total 6164
telemt_me_idle_close_by_peer_total 6164
telemt_me_route_drop_no_conn_total 44917
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 107036
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 376
telemt_desync_full_logged_total 114
telemt_desync_suppressed_total 262
telemt_desync_frames_bucket_total{bucket="1_2"} 114
telemt_desync_frames_bucket_total{bucket="3_10"} 139
telemt_desync_frames_bucket_total{bucket="gt_10"} 123
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 6091
telemt_me_refill_failed_total 704
telemt_me_writer_restored_same_endpoint_total 5316
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 121
telemt_me_writer_removed_unexpected_minus_restored_total 767
telemt_user_connections_total{user="hello"} 106916
telemt_user_connections_current{user="hello"} 178
telemt_user_octets_from_client{user="hello"} 2050068592 (1.91 GB)
telemt_user_octets_to_client{user="hello"} 45822544996 (42.68 GB)
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 30667.2 (8h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 72229
telemt_connections_bad_total 5939
telemt_handshake_timeouts_total 1084
telemt_upstream_connect_attempt_total 35050
telemt_upstream_connect_success_total 34671
telemt_upstream_connect_fail_total 378
telemt_upstream_connect_attempts_per_request{bucket="1"} 35049
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29267
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5370
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 378
telemt_me_keepalive_timeout_total 119
telemt_me_reconnect_attempts_total 41039
telemt_me_reconnect_success_total 3684
telemt_me_reader_eof_total 4848
telemt_me_idle_close_by_peer_total 4848
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 12734
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 34123
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 25
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 448
telemt_desync_full_logged_total 125
telemt_desync_suppressed_total 323
telemt_desync_frames_bucket_total{bucket="1_2"} 17
telemt_desync_frames_bucket_total{bucket="3_10"} 372
telemt_desync_frames_bucket_total{bucket="gt_10"} 59
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 4874
telemt_me_refill_failed_total 1170
telemt_me_writer_restored_same_endpoint_total 3667
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 1190
telemt_user_connections_total{user="hello"} 63554
telemt_user_connections_current{user="hello"} 130
telemt_user_octets_from_client{user="hello"} 568664297 (542.32 MB)
telemt_user_octets_to_client{user="hello"} 19300273463 (17.97 GB)
telemt_user_msgs_from_client{user="hello"} 473726
telemt_user_msgs_to_client{user="hello"} 1876097
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 30654.6 (8h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 191533
telemt_connections_bad_total 953
telemt_handshake_timeouts_total 1507
telemt_upstream_connect_attempt_total 6478
telemt_upstream_connect_success_total 6445
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 6478
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3015
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3421
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_keepalive_timeout_total 361
telemt_me_reconnect_attempts_total 5947
telemt_me_reconnect_success_total 4881
telemt_me_reader_eof_total 5152
telemt_me_idle_close_by_peer_total 5151
telemt_me_route_drop_no_conn_total 74302
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 183379
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 253
telemt_desync_full_logged_total 100
telemt_desync_suppressed_total 153
telemt_desync_frames_bucket_total{bucket="1_2"} 66
telemt_desync_frames_bucket_total{bucket="3_10"} 94
telemt_desync_frames_bucket_total{bucket="gt_10"} 93
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 4977
telemt_me_refill_failed_total 32
telemt_me_writer_restored_same_endpoint_total 4874
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 96
telemt_user_connections_total{user="hello"} 183333
telemt_user_connections_current{user="hello"} 409
telemt_user_octets_from_client{user="hello"} 3528005984 (3.29 GB)
telemt_user_octets_to_client{user="hello"} 81315199580 (75.73 GB)
telemt_user_unique_ips_current{user="hello"} 146
telemt_user_unique_ips_recent_window{user="hello"} 73
```