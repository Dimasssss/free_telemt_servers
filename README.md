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

# Server Metrics 2026-03-12 21:50:09 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 51406.1 (14h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 240507
telemt_connections_bad_total 2683
telemt_handshake_timeouts_total 5186
telemt_upstream_connect_attempt_total 12909
telemt_upstream_connect_success_total 12849
telemt_upstream_connect_fail_total 60
telemt_upstream_connect_attempts_per_request{bucket="1"} 12909
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5690
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7115
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 60
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1463
telemt_me_reconnect_attempts_total 13680
telemt_me_reconnect_success_total 10213
telemt_me_reader_eof_total 10858
telemt_me_idle_close_by_peer_total 10857
telemt_me_route_drop_no_conn_total 73846
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 198176
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 671
telemt_desync_full_logged_total 248
telemt_desync_suppressed_total 423
telemt_desync_frames_bucket_total{bucket="1_2"} 122
telemt_desync_frames_bucket_total{bucket="3_10"} 253
telemt_desync_frames_bucket_total{bucket="gt_10"} 296
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 10438
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 10197
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 225
telemt_user_connections_total{user="hello"} 197943
telemt_user_connections_current{user="hello"} 214
telemt_user_octets_from_client{user="hello"} 3715634824 (3.46 GB)
telemt_user_octets_to_client{user="hello"} 96718942564 (90.08 GB)
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 51299.1 (14h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 107306
telemt_connections_bad_total 549
telemt_handshake_timeouts_total 806
telemt_upstream_connect_attempt_total 30832
telemt_upstream_connect_success_total 30495
telemt_upstream_connect_fail_total 337
telemt_upstream_connect_attempts_per_request{bucket="1"} 30832
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20467
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9531
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 497
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 337
telemt_me_keepalive_timeout_total 378
telemt_me_reconnect_attempts_total 52068
telemt_me_reconnect_success_total 11419
telemt_me_reader_eof_total 12929
telemt_me_idle_close_by_peer_total 12929
telemt_me_route_drop_no_conn_total 38941
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 85556
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 13
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
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 12773
telemt_me_refill_failed_total 1269
telemt_me_writer_restored_same_endpoint_total 11404
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1354
telemt_user_connections_total{user="hello"} 102059
telemt_user_connections_current{user="hello"} 77
telemt_user_octets_from_client{user="hello"} 1121766156 (1.04 GB)
telemt_user_octets_to_client{user="hello"} 31822242831 (29.64 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 51262.9 (14h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 133594
telemt_connections_bad_total 1578
telemt_handshake_timeouts_total 2213
telemt_upstream_connect_attempt_total 14117
telemt_upstream_connect_success_total 14116
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 14117
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6665
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7434
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 312
telemt_me_reconnect_attempts_total 12642
telemt_me_reconnect_success_total 11501
telemt_me_reader_eof_total 12244
telemt_me_idle_close_by_peer_total 12244
telemt_me_route_drop_no_conn_total 50394
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 124714
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 47
telemt_desync_full_logged_total 22
telemt_desync_suppressed_total 25
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 13
telemt_desync_frames_bucket_total{bucket="gt_10"} 32
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 11645
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 11481
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 144
telemt_user_connections_total{user="hello"} 124680
telemt_user_connections_current{user="hello"} 100
telemt_user_octets_from_client{user="hello"} 2554350796 (2.38 GB)
telemt_user_octets_to_client{user="hello"} 59823041264 (55.71 GB)
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 51238.3 (14h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 194686
telemt_connections_bad_total 13178
telemt_handshake_timeouts_total 1365
telemt_upstream_connect_attempt_total 25210
telemt_upstream_connect_success_total 15534
telemt_upstream_connect_fail_total 9676
telemt_upstream_connect_attempts_per_request{bucket="1"} 25210
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8424
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6994
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 108
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9676
telemt_me_keepalive_timeout_total 2465
telemt_me_reconnect_attempts_total 42335
telemt_me_reconnect_success_total 10091
telemt_me_reader_eof_total 11443
telemt_me_idle_close_by_peer_total 11436
telemt_me_route_drop_no_conn_total 68134
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 158936
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 11
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
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 11261
telemt_me_refill_failed_total 1004
telemt_me_writer_restored_same_endpoint_total 10081
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1170
telemt_user_connections_total{user="hello"} 161691
telemt_user_connections_current{user="hello"} 113
telemt_user_octets_from_client{user="hello"} 2948457658 (2.75 GB)
telemt_user_octets_to_client{user="hello"} 66517141637 (61.95 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 1409.9 (0h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1528
telemt_connections_bad_total 250
telemt_upstream_connect_attempt_total 317
telemt_upstream_connect_success_total 314
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 317
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 177
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 135
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 203
telemt_me_reconnect_success_total 202
telemt_me_reader_eof_total 186
telemt_me_idle_close_by_peer_total 186
telemt_me_route_drop_no_conn_total 452
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1161
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 201
telemt_me_writer_restored_same_endpoint_total 186
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 25
telemt_user_connections_total{user="hello"} 1161
telemt_user_connections_current{user="hello"} 28
telemt_user_octets_from_client{user="hello"} 4728328 (4.51 MB)
telemt_user_octets_to_client{user="hello"} 839013368 (800.15 MB)
telemt_user_unique_ips_current{user="hello"} 15
telemt_user_unique_ips_recent_window{user="hello"} 6
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 51194.9 (14h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 314654
telemt_connections_bad_total 4448
telemt_handshake_timeouts_total 2465
telemt_upstream_connect_attempt_total 10670
telemt_upstream_connect_success_total 10613
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 10670
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4968
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5632
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_keepalive_timeout_total 499
telemt_me_reconnect_attempts_total 11661
telemt_me_reconnect_success_total 8053
telemt_me_reader_eof_total 8600
telemt_me_idle_close_by_peer_total 8599
telemt_me_route_drop_no_conn_total 143153
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 310047
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 293
telemt_desync_full_logged_total 110
telemt_desync_suppressed_total 183
telemt_desync_frames_bucket_total{bucket="1_2"} 74
telemt_desync_frames_bucket_total{bucket="3_10"} 110
telemt_desync_frames_bucket_total{bucket="gt_10"} 109
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 8265
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 8046
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 212
telemt_user_connections_total{user="hello"} 298349
telemt_user_connections_current{user="hello"} 287
telemt_user_octets_from_client{user="hello"} 5319812428 (4.95 GB)
telemt_user_octets_to_client{user="hello"} 149563112228 (139.29 GB)
telemt_user_unique_ips_current{user="hello"} 92
telemt_user_unique_ips_recent_window{user="hello"} 27
```