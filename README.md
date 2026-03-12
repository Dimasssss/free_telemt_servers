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

# Server Metrics 2026-03-12 14:10:02 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 23799.3 (6h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 126044
telemt_connections_bad_total 1371
telemt_handshake_timeouts_total 4425
telemt_upstream_connect_attempt_total 5870
telemt_upstream_connect_success_total 5846
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 5870
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2592
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3248
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_keepalive_timeout_total 253
telemt_me_reconnect_attempts_total 4637
telemt_me_reconnect_success_total 4607
telemt_me_reader_eof_total 4839
telemt_me_idle_close_by_peer_total 4838
telemt_me_route_drop_no_conn_total 35363
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 110498
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 526
telemt_desync_full_logged_total 194
telemt_desync_suppressed_total 332
telemt_desync_frames_bucket_total{bucket="1_2"} 97
telemt_desync_frames_bucket_total{bucket="3_10"} 205
telemt_desync_frames_bucket_total{bucket="gt_10"} 224
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 4646
telemt_me_writer_restored_same_endpoint_total 4591
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 110460
telemt_user_connections_current{user="hello"} 315
telemt_user_octets_from_client{user="hello"} 1864523096 (1.74 GB)
telemt_user_octets_to_client{user="hello"} 41744477328 (38.88 GB)
telemt_user_unique_ips_current{user="hello"} 104
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 23692.3 (6h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 51452
telemt_connections_bad_total 403
telemt_handshake_timeouts_total 358
telemt_upstream_connect_attempt_total 6973
telemt_upstream_connect_success_total 6806
telemt_upstream_connect_fail_total 167
telemt_upstream_connect_attempts_per_request{bucket="1"} 6973
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2845
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3937
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 167
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 21420
telemt_me_reconnect_success_total 5587
telemt_me_reader_eof_total 6196
telemt_me_idle_close_by_peer_total 6196
telemt_me_route_drop_no_conn_total 23188
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 49118
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
telemt_me_writer_removed_unexpected_total 6117
telemt_me_refill_failed_total 494
telemt_me_writer_restored_same_endpoint_total 5572
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 530
telemt_user_connections_total{user="hello"} 49112
telemt_user_connections_current{user="hello"} 142
telemt_user_octets_from_client{user="hello"} 579042484 (552.22 MB)
telemt_user_octets_to_client{user="hello"} 14015451052 (13.05 GB)
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 23656.0 (6h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 70816
telemt_connections_bad_total 1383
telemt_handshake_timeouts_total 850
telemt_upstream_connect_attempt_total 6398
telemt_upstream_connect_success_total 6398
telemt_upstream_connect_attempts_per_request{bucket="1"} 6398
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3112
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3277
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 112
telemt_me_reconnect_attempts_total 5185
telemt_me_reconnect_success_total 5146
telemt_me_reader_eof_total 5446
telemt_me_idle_close_by_peer_total 5446
telemt_me_route_drop_no_conn_total 24640
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 65516
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
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 5182
telemt_me_writer_restored_same_endpoint_total 5126
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 36
telemt_user_connections_total{user="hello"} 65496
telemt_user_connections_current{user="hello"} 182
telemt_user_octets_from_client{user="hello"} 1855935996 (1.73 GB)
telemt_user_octets_to_client{user="hello"} 36866853516 (34.33 GB)
telemt_user_unique_ips_current{user="hello"} 73
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 23631.7 (6h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 90103
telemt_connections_bad_total 1512
telemt_handshake_timeouts_total 680
telemt_upstream_connect_attempt_total 6303
telemt_upstream_connect_success_total 6142
telemt_upstream_connect_fail_total 161
telemt_upstream_connect_attempts_per_request{bucket="1"} 6303
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2727
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3394
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 161
telemt_me_keepalive_timeout_total 238
telemt_me_reconnect_attempts_total 18012
telemt_me_reconnect_success_total 4904
telemt_me_reader_eof_total 5445
telemt_me_idle_close_by_peer_total 5445
telemt_me_route_drop_no_conn_total 33649
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 82683
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 4
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
telemt_me_writer_removed_unexpected_total 5370
telemt_me_refill_failed_total 408
telemt_me_writer_restored_same_endpoint_total 4896
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 121
telemt_me_writer_removed_unexpected_minus_restored_total 466
telemt_user_connections_total{user="hello"} 82566
telemt_user_connections_current{user="hello"} 164
telemt_user_octets_from_client{user="hello"} 1329877236 (1.24 GB)
telemt_user_octets_to_client{user="hello"} 35196335556 (32.78 GB)
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 23601.1 (6h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 52776
telemt_connections_bad_total 4472
telemt_handshake_timeouts_total 696
telemt_upstream_connect_attempt_total 18990
telemt_upstream_connect_success_total 18691
telemt_upstream_connect_fail_total 299
telemt_upstream_connect_attempts_per_request{bucket="1"} 18990
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14686
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3977
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 299
telemt_me_keepalive_timeout_total 105
telemt_me_reconnect_attempts_total 30943
telemt_me_reconnect_success_total 3684
telemt_me_reader_eof_total 4532
telemt_me_idle_close_by_peer_total 4532
telemt_me_seq_mismatch_total 8
telemt_me_route_drop_no_conn_total 12140
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 32575
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 442
telemt_desync_full_logged_total 122
telemt_desync_suppressed_total 320
telemt_desync_frames_bucket_total{bucket="1_2"} 16
telemt_desync_frames_bucket_total{bucket="3_10"} 368
telemt_desync_frames_bucket_total{bucket="gt_10"} 58
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 4557
telemt_me_refill_failed_total 853
telemt_me_writer_restored_same_endpoint_total 3667
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 873
telemt_user_connections_total{user="hello"} 46347
telemt_user_connections_current{user="hello"} 103
telemt_user_octets_from_client{user="hello"} 382603782 (364.88 MB)
telemt_user_octets_to_client{user="hello"} 11803500295 (10.99 GB)
telemt_user_msgs_from_client{user="hello"} 197996
telemt_user_msgs_to_client{user="hello"} 588162
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 23588.0 (6h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 141850
telemt_connections_bad_total 776
telemt_handshake_timeouts_total 1096
telemt_upstream_connect_attempt_total 4896
telemt_upstream_connect_success_total 4872
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 4896
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2310
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2560
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_keepalive_timeout_total 112
telemt_me_reconnect_attempts_total 3677
telemt_me_reconnect_success_total 3648
telemt_me_reader_eof_total 3845
telemt_me_idle_close_by_peer_total 3845
telemt_me_route_drop_no_conn_total 56143
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 135537
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
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 3692
telemt_me_writer_restored_same_endpoint_total 3641
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 44
telemt_user_connections_total{user="hello"} 135505
telemt_user_connections_current{user="hello"} 461
telemt_user_octets_from_client{user="hello"} 2825774232 (2.63 GB)
telemt_user_octets_to_client{user="hello"} 56339435100 (52.47 GB)
telemt_user_unique_ips_current{user="hello"} 136
telemt_user_unique_ips_recent_window{user="hello"} 60
```