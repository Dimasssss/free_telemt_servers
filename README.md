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

# Server Metrics 2026-03-12 20:14:18 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 45637.5 (12h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 224955
telemt_connections_bad_total 2625
telemt_handshake_timeouts_total 5012
telemt_upstream_connect_attempt_total 11460
telemt_upstream_connect_success_total 11407
telemt_upstream_connect_fail_total 53
telemt_upstream_connect_attempts_per_request{bucket="1"} 11460
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5037
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6333
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 53
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1445
telemt_me_reconnect_attempts_total 12539
telemt_me_reconnect_success_total 9078
telemt_me_reader_eof_total 9637
telemt_me_idle_close_by_peer_total 9636
telemt_me_route_drop_no_conn_total 68274
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 187463
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 665
telemt_desync_full_logged_total 247
telemt_desync_suppressed_total 418
telemt_desync_frames_bucket_total{bucket="1_2"} 121
telemt_desync_frames_bucket_total{bucket="3_10"} 251
telemt_desync_frames_bucket_total{bucket="gt_10"} 293
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 9294
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 9062
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 216
telemt_user_connections_total{user="hello"} 187419
telemt_user_connections_current{user="hello"} 314
telemt_user_octets_from_client{user="hello"} 3587027060 (3.34 GB)
telemt_user_octets_to_client{user="hello"} 89328200600 (83.19 GB)
telemt_user_unique_ips_current{user="hello"} 79
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 45530.7 (12h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 100921
telemt_connections_bad_total 534
telemt_handshake_timeouts_total 787
telemt_upstream_connect_attempt_total 28629
telemt_upstream_connect_success_total 28336
telemt_upstream_connect_fail_total 293
telemt_upstream_connect_attempts_per_request{bucket="1"} 28629
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19573
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8275
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 488
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 293
telemt_me_keepalive_timeout_total 343
telemt_me_reconnect_attempts_total 48951
telemt_me_reconnect_success_total 9519
telemt_me_reader_eof_total 10925
telemt_me_idle_close_by_peer_total 10925
telemt_me_route_drop_no_conn_total 36714
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 79373
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 12
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
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 10824
telemt_me_refill_failed_total 1231
telemt_me_writer_restored_same_endpoint_total 9504
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1305
telemt_user_connections_total{user="hello"} 95877
telemt_user_connections_current{user="hello"} 90
telemt_user_octets_from_client{user="hello"} 1037754924 (989.68 MB)
telemt_user_octets_to_client{user="hello"} 28176192551 (26.24 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 45494.2 (12h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 126438
telemt_connections_bad_total 1532
telemt_handshake_timeouts_total 2187
telemt_upstream_connect_attempt_total 12640
telemt_upstream_connect_success_total 12639
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 12640
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6028
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6594
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 289
telemt_me_reconnect_attempts_total 11427
telemt_me_reconnect_success_total 10290
telemt_me_reader_eof_total 10945
telemt_me_idle_close_by_peer_total 10945
telemt_me_route_drop_no_conn_total 47769
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 117773
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 41
telemt_desync_full_logged_total 19
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 11
telemt_desync_frames_bucket_total{bucket="gt_10"} 28
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 10426
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 10270
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 136
telemt_user_connections_total{user="hello"} 117745
telemt_user_connections_current{user="hello"} 95
telemt_user_octets_from_client{user="hello"} 2498180988 (2.33 GB)
telemt_user_octets_to_client{user="hello"} 56972460528 (53.06 GB)
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 45470.0 (12h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 183288
telemt_connections_bad_total 13155
telemt_handshake_timeouts_total 1274
telemt_upstream_connect_attempt_total 23396
telemt_upstream_connect_success_total 13762
telemt_upstream_connect_fail_total 9634
telemt_upstream_connect_attempts_per_request{bucket="1"} 23396
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7652
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6002
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9634
telemt_me_keepalive_timeout_total 2435
telemt_me_reconnect_attempts_total 39765
telemt_me_reconnect_success_total 8582
telemt_me_reader_eof_total 9833
telemt_me_idle_close_by_peer_total 9826
telemt_me_route_drop_no_conn_total 62914
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 147922
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 482
telemt_desync_full_logged_total 141
telemt_desync_suppressed_total 341
telemt_desync_frames_bucket_total{bucket="1_2"} 122
telemt_desync_frames_bucket_total{bucket="3_10"} 178
telemt_desync_frames_bucket_total{bucket="gt_10"} 182
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 9705
telemt_me_refill_failed_total 971
telemt_me_writer_restored_same_endpoint_total 8572
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1123
telemt_user_connections_total{user="hello"} 150682
telemt_user_connections_current{user="hello"} 135
telemt_user_octets_from_client{user="hello"} 2828032142 (2.63 GB)
telemt_user_octets_to_client{user="hello"} 59171106365 (55.11 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## rdp-onedash.ru

Не удалось получить метрики для этого сервера.

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 45426.6 (12h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 285352
telemt_connections_bad_total 2190
telemt_handshake_timeouts_total 2206
telemt_upstream_connect_attempt_total 9544
telemt_upstream_connect_success_total 9494
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 9544
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4427
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5057
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_timeout_total 484
telemt_me_reconnect_attempts_total 10802
telemt_me_reconnect_success_total 7195
telemt_me_reader_eof_total 7675
telemt_me_idle_close_by_peer_total 7674
telemt_me_route_drop_no_conn_total 132755
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 283963
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 274
telemt_desync_full_logged_total 105
telemt_desync_suppressed_total 169
telemt_desync_frames_bucket_total{bucket="1_2"} 74
telemt_desync_frames_bucket_total{bucket="3_10"} 104
telemt_desync_frames_bucket_total{bucket="gt_10"} 96
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 7398
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 7188
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 203
telemt_user_connections_total{user="hello"} 272271
telemt_user_connections_current{user="hello"} 347
telemt_user_octets_from_client{user="hello"} 4998735272 (4.66 GB)
telemt_user_octets_to_client{user="hello"} 135917282384 (126.58 GB)
telemt_user_unique_ips_current{user="hello"} 116
telemt_user_unique_ips_recent_window{user="hello"} 42
```