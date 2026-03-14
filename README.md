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

# Server Metrics 2026-03-14 21:39:46 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.17

telemt_uptime_seconds 30205.6 (8h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 144079
telemt_connections_bad_total 16381
telemt_handshake_timeouts_total 1537
telemt_upstream_connect_attempt_total 6835
telemt_upstream_connect_success_total 6833
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 6835
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3226
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3521
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 86
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 224
telemt_me_reconnect_attempts_total 5327
telemt_me_reconnect_success_total 5288
telemt_me_reader_eof_total 5620
telemt_me_idle_close_by_peer_total 5620
telemt_me_route_drop_no_conn_total 52274
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 119661
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 575
telemt_desync_full_logged_total 199
telemt_desync_suppressed_total 376
telemt_desync_frames_bucket_total{bucket="1_2"} 127
telemt_desync_frames_bucket_total{bucket="3_10"} 209
telemt_desync_frames_bucket_total{bucket="gt_10"} 239
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 5374
telemt_me_writer_restored_same_endpoint_total 5270
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 72
telemt_me_writer_removed_unexpected_minus_restored_total 86
telemt_user_connections_total{user="hello"} 119581
telemt_user_connections_current{user="hello"} 253
telemt_user_octets_from_client{user="hello"} 2532321792 (2.36 GB)
telemt_user_octets_to_client{user="hello"} 72851838972 (67.85 GB)
telemt_user_unique_ips_current{user="hello"} 79
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## psb.hosting

```
telemt 3.3.17

telemt_uptime_seconds 30203.9 (8h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 59674
telemt_connections_bad_total 737
telemt_handshake_timeouts_total 997
telemt_upstream_connect_attempt_total 7855
telemt_upstream_connect_success_total 7805
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 7855
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3236
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4433
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 136
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_timeout_total 143
telemt_me_reconnect_attempts_total 8841
telemt_me_reconnect_success_total 6259
telemt_me_reader_eof_total 6663
telemt_me_idle_close_by_peer_total 6663
telemt_me_route_drop_no_conn_total 32330
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 55699
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 11
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1
telemt_desync_full_logged_total 1
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 6422
telemt_me_refill_failed_total 79
telemt_me_writer_restored_same_endpoint_total 6254
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 120
telemt_me_writer_removed_unexpected_minus_restored_total 163
telemt_user_connections_total{user="hello"} 55620
telemt_user_connections_current{user="hello"} 115
telemt_user_octets_from_client{user="hello"} 1386739524 (1.29 GB)
telemt_user_octets_to_client{user="hello"} 25328995116 (23.59 GB)
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## koara.io

```
telemt 3.3.17

telemt_uptime_seconds 30209.6 (8h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 67569
telemt_connections_bad_total 395
telemt_handshake_timeouts_total 1912
telemt_upstream_connect_attempt_total 9940
telemt_upstream_connect_success_total 9838
telemt_upstream_connect_fail_total 102
telemt_upstream_connect_attempts_per_request{bucket="1"} 9940
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4570
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5255
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 102
telemt_me_keepalive_timeout_total 267
telemt_me_reconnect_attempts_total 105841
telemt_me_reconnect_success_total 7976
telemt_me_reader_eof_total 8525
telemt_me_idle_close_by_peer_total 8525
telemt_me_route_drop_no_conn_total 25062
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 61858
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 11
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 15
telemt_desync_full_logged_total 4
telemt_desync_suppressed_total 11
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 5
telemt_desync_frames_bucket_total{bucket="gt_10"} 6
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 8261
telemt_me_refill_failed_total 3169
telemt_me_writer_restored_same_endpoint_total 7930
telemt_me_writer_restored_fallback_total 46
telemt_me_async_recovery_trigger_total 1685
telemt_me_writer_removed_unexpected_minus_restored_total 285
telemt_user_connections_total{user="hello"} 61921
telemt_user_connections_current{user="hello"} 108
telemt_user_octets_from_client{user="hello"} 3945422037 (3.67 GB)
telemt_user_octets_to_client{user="hello"} 48815463530 (45.46 GB)
telemt_user_msgs_from_client{user="hello"} 3762
telemt_user_msgs_to_client{user="hello"} 18362
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## landvps.ru

```
telemt 3.3.17

telemt_uptime_seconds 30213.3 (8h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 85258
telemt_connections_bad_total 213
telemt_handshake_timeouts_total 619
telemt_upstream_connect_attempt_total 7376
telemt_upstream_connect_success_total 7332
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 7376
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3432
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3870
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_keepalive_timeout_total 204
telemt_me_reconnect_attempts_total 5652
telemt_me_reconnect_success_total 5623
telemt_me_reader_eof_total 5933
telemt_me_idle_close_by_peer_total 5933
telemt_me_route_drop_no_conn_total 37111
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 80813
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 662
telemt_desync_full_logged_total 170
telemt_desync_suppressed_total 492
telemt_desync_frames_bucket_total{bucket="1_2"} 120
telemt_desync_frames_bucket_total{bucket="3_10"} 278
telemt_desync_frames_bucket_total{bucket="gt_10"} 264
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 5685
telemt_me_writer_restored_same_endpoint_total 5621
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 60
telemt_me_writer_removed_unexpected_minus_restored_total 62
telemt_user_connections_total{user="hello"} 80857
telemt_user_connections_current{user="hello"} 142
telemt_user_octets_from_client{user="hello"} 1341257732 (1.25 GB)
telemt_user_octets_to_client{user="hello"} 29099194658 (27.10 GB)
telemt_user_msgs_from_client{user="hello"} 473
telemt_user_msgs_to_client{user="hello"} 2783
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## rdp-onedash.ru

```
telemt 3.3.17

telemt_uptime_seconds 30206.4 (8h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 64513
telemt_connections_bad_total 5892
telemt_handshake_timeouts_total 3385
telemt_upstream_connect_attempt_total 7363
telemt_upstream_connect_success_total 7278
telemt_upstream_connect_fail_total 85
telemt_upstream_connect_attempts_per_request{bucket="1"} 7363
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3293
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3936
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 85
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 12268
telemt_me_reconnect_success_total 5729
telemt_me_reader_eof_total 6205
telemt_me_idle_close_by_peer_total 6205
telemt_me_route_drop_no_conn_total 20754
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 52003
telemt_me_writer_pick_total{mode="p2c",result="full"} 2
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 270
telemt_desync_full_logged_total 41
telemt_desync_suppressed_total 229
telemt_desync_frames_bucket_total{bucket="1_2"} 38
telemt_desync_frames_bucket_total{bucket="3_10"} 96
telemt_desync_frames_bucket_total{bucket="gt_10"} 136
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 5988
telemt_me_refill_failed_total 203
telemt_me_writer_restored_same_endpoint_total 5725
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 259
telemt_user_connections_total{user="hello"} 51989
telemt_user_connections_current{user="hello"} 69
telemt_user_octets_from_client{user="hello"} 1410778044 (1.31 GB)
telemt_user_octets_to_client{user="hello"} 31963218604 (29.77 GB)
telemt_user_unique_ips_current{user="hello"} 26
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## hostvds.com

```
telemt 3.3.17

telemt_uptime_seconds 30206.0 (8h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 217309
telemt_connections_bad_total 7709
telemt_handshake_timeouts_total 2709
telemt_upstream_connect_attempt_total 6027
telemt_upstream_connect_success_total 5918
telemt_upstream_connect_fail_total 109
telemt_upstream_connect_attempts_per_request{bucket="1"} 6027
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2887
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3026
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 109
telemt_me_keepalive_timeout_total 261
telemt_me_reconnect_attempts_total 9383
telemt_me_reconnect_success_total 4374
telemt_me_reader_eof_total 4734
telemt_me_idle_close_by_peer_total 4734
telemt_me_route_drop_no_conn_total 121056
telemt_me_route_drop_channel_closed_total 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 200556
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 4
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 115
telemt_desync_full_logged_total 31
telemt_desync_suppressed_total 84
telemt_desync_frames_bucket_total{bucket="1_2"} 28
telemt_desync_frames_bucket_total{bucket="3_10"} 60
telemt_desync_frames_bucket_total{bucket="gt_10"} 27
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 4584
telemt_me_refill_failed_total 155
telemt_me_writer_restored_same_endpoint_total 4370
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 210
telemt_user_connections_total{user="hello"} 197040
telemt_user_connections_current{user="hello"} 373
telemt_user_octets_from_client{user="hello"} 6062941312 (5.65 GB)
telemt_user_octets_to_client{user="hello"} 108542311056 (101.09 GB)
telemt_user_unique_ips_current{user="hello"} 133
telemt_user_unique_ips_recent_window{user="hello"} 39
```