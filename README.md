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

# Server Metrics 2026-03-12 14:04:55 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 23492.4 (6h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 124643
telemt_connections_bad_total 1363
telemt_handshake_timeouts_total 4395
telemt_upstream_connect_attempt_total 5786
telemt_upstream_connect_success_total 5762
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 5786
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2550
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3206
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_keepalive_timeout_total 250
telemt_me_reconnect_attempts_total 4558
telemt_me_reconnect_success_total 4529
telemt_me_reader_eof_total 4741
telemt_me_idle_close_by_peer_total 4740
telemt_me_route_drop_no_conn_total 34888
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 109322
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 525
telemt_desync_full_logged_total 193
telemt_desync_suppressed_total 332
telemt_desync_frames_bucket_total{bucket="1_2"} 97
telemt_desync_frames_bucket_total{bucket="3_10"} 204
telemt_desync_frames_bucket_total{bucket="gt_10"} 224
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 4568
telemt_me_writer_restored_same_endpoint_total 4513
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 109284
telemt_user_connections_current{user="hello"} 347
telemt_user_octets_from_client{user="hello"} 1854227008 (1.73 GB)
telemt_user_octets_to_client{user="hello"} 41426073196 (38.58 GB)
telemt_user_unique_ips_current{user="hello"} 114
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 23385.6 (6h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 50782
telemt_connections_bad_total 403
telemt_handshake_timeouts_total 357
telemt_upstream_connect_attempt_total 6832
telemt_upstream_connect_success_total 6672
telemt_upstream_connect_fail_total 160
telemt_upstream_connect_attempts_per_request{bucket="1"} 6832
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2780
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3871
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 160
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 21330
telemt_me_reconnect_success_total 5498
telemt_me_reader_eof_total 6103
telemt_me_idle_close_by_peer_total 6103
telemt_me_route_drop_no_conn_total 22951
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 48462
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 5
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
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 6024
telemt_me_refill_failed_total 494
telemt_me_writer_restored_same_endpoint_total 5483
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 526
telemt_user_connections_total{user="hello"} 48456
telemt_user_connections_current{user="hello"} 163
telemt_user_octets_from_client{user="hello"} 576286188 (549.59 MB)
telemt_user_octets_to_client{user="hello"} 13841305692 (12.89 GB)
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 23349.3 (6h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 69648
telemt_connections_bad_total 1339
telemt_handshake_timeouts_total 833
telemt_upstream_connect_attempt_total 6289
telemt_upstream_connect_success_total 6289
telemt_upstream_connect_attempts_per_request{bucket="1"} 6289
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3053
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3227
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 111
telemt_me_reconnect_attempts_total 5120
telemt_me_reconnect_success_total 5082
telemt_me_reader_eof_total 5370
telemt_me_idle_close_by_peer_total 5370
telemt_me_route_drop_no_conn_total 24171
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 64445
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 4
telemt_desync_frames_bucket_total{bucket="3_10"} 6
telemt_desync_frames_bucket_total{bucket="gt_10"} 4
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 5118
telemt_me_writer_restored_same_endpoint_total 5062
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 36
telemt_user_connections_total{user="hello"} 64425
telemt_user_connections_current{user="hello"} 200
telemt_user_octets_from_client{user="hello"} 1846121176 (1.72 GB)
telemt_user_octets_to_client{user="hello"} 36380580428 (33.88 GB)
telemt_user_unique_ips_current{user="hello"} 80
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 23324.5 (6h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 88673
telemt_connections_bad_total 1512
telemt_handshake_timeouts_total 421
telemt_upstream_connect_attempt_total 6223
telemt_upstream_connect_success_total 6065
telemt_upstream_connect_fail_total 158
telemt_upstream_connect_attempts_per_request{bucket="1"} 6223
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2683
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3361
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 158
telemt_me_keepalive_timeout_total 237
telemt_me_reconnect_attempts_total 16667
telemt_me_reconnect_success_total 4871
telemt_me_reader_eof_total 5369
telemt_me_idle_close_by_peer_total 5369
telemt_me_route_drop_no_conn_total 33185
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 81535
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 260
telemt_desync_full_logged_total 89
telemt_desync_suppressed_total 171
telemt_desync_frames_bucket_total{bucket="1_2"} 93
telemt_desync_frames_bucket_total{bucket="3_10"} 87
telemt_desync_frames_bucket_total{bucket="gt_10"} 80
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 5294
telemt_me_refill_failed_total 367
telemt_me_writer_restored_same_endpoint_total 4863
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 121
telemt_me_writer_removed_unexpected_minus_restored_total 423
telemt_user_connections_total{user="hello"} 81418
telemt_user_connections_current{user="hello"} 189
telemt_user_octets_from_client{user="hello"} 1309905520 (1.22 GB)
telemt_user_octets_to_client{user="hello"} 35081091900 (32.67 GB)
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 23294.1 (6h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 51815
telemt_connections_bad_total 4416
telemt_handshake_timeouts_total 684
telemt_upstream_connect_attempt_total 18281
telemt_upstream_connect_success_total 17993
telemt_upstream_connect_fail_total 288
telemt_upstream_connect_attempts_per_request{bucket="1"} 18281
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14047
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3918
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 288
telemt_me_keepalive_timeout_total 105
telemt_me_reconnect_attempts_total 30075
telemt_me_reconnect_success_total 3680
telemt_me_reader_eof_total 4501
telemt_me_idle_close_by_peer_total 4501
telemt_me_seq_mismatch_total 8
telemt_me_route_drop_no_conn_total 12103
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 32352
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 439
telemt_desync_full_logged_total 121
telemt_desync_suppressed_total 318
telemt_desync_frames_bucket_total{bucket="1_2"} 16
telemt_desync_frames_bucket_total{bucket="3_10"} 365
telemt_desync_frames_bucket_total{bucket="gt_10"} 58
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 4526
telemt_me_refill_failed_total 826
telemt_me_writer_restored_same_endpoint_total 3663
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 846
telemt_user_connections_total{user="hello"} 45473
telemt_user_connections_current{user="hello"} 162
telemt_user_octets_from_client{user="hello"} 376234070 (358.80 MB)
telemt_user_octets_to_client{user="hello"} 11691853421 (10.89 GB)
telemt_user_msgs_from_client{user="hello"} 189691
telemt_user_msgs_to_client{user="hello"} 539131
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 23281.2 (6h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 139633
telemt_connections_bad_total 776
telemt_handshake_timeouts_total 1084
telemt_upstream_connect_attempt_total 4793
telemt_upstream_connect_success_total 4770
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 4793
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2263
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2505
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_timeout_total 112
telemt_me_reconnect_attempts_total 3618
telemt_me_reconnect_success_total 3589
telemt_me_reader_eof_total 3775
telemt_me_idle_close_by_peer_total 3775
telemt_me_route_drop_no_conn_total 55548
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 133398
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 224
telemt_desync_full_logged_total 79
telemt_desync_suppressed_total 145
telemt_desync_frames_bucket_total{bucket="1_2"} 53
telemt_desync_frames_bucket_total{bucket="3_10"} 87
telemt_desync_frames_bucket_total{bucket="gt_10"} 84
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 3633
telemt_me_writer_restored_same_endpoint_total 3582
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 44
telemt_user_connections_total{user="hello"} 133365
telemt_user_connections_current{user="hello"} 489
telemt_user_octets_from_client{user="hello"} 2813247956 (2.62 GB)
telemt_user_octets_to_client{user="hello"} 55196645240 (51.41 GB)
telemt_user_unique_ips_current{user="hello"} 127
telemt_user_unique_ips_recent_window{user="hello"} 59
```