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

## 4vps.su
- Локация: Польша, Варшава
- Тариф: PL-cx21
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 2 Gbit/s
- Цена в месяц: 770 RUB
- Оплачен до: 16 апреля
- Ссылка:
```bash
tg://proxy?server=s7.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-19 10:59:56 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 47488.0 (13h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1104026
telemt_connections_bad_total 94468
telemt_connections_current 1590
telemt_connections_me_current 1590
telemt_handshake_timeouts_total 39066
telemt_upstream_connect_attempt_total 9081
telemt_upstream_connect_success_total 8921
telemt_upstream_connect_fail_total 160
telemt_upstream_connect_attempts_per_request{bucket="1"} 9081
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4349
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4569
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 160
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 92
telemt_me_reconnect_attempts_total 7706
telemt_me_reconnect_success_total 6541
telemt_me_reader_eof_total 6904
telemt_me_idle_close_by_peer_total 6901
telemt_me_seq_mismatch_total 10
telemt_me_route_drop_no_conn_total 435601
telemt_me_route_drop_channel_closed_total 166
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 857127
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 35
telemt_me_endpoint_quarantine_total 32
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4794
telemt_desync_full_logged_total 1473
telemt_desync_suppressed_total 3321
telemt_desync_frames_bucket_total{bucket="1_2"} 1581
telemt_desync_frames_bucket_total{bucket="3_10"} 1750
telemt_desync_frames_bucket_total{bucket="gt_10"} 1463
telemt_pool_swap_total 38
telemt_pool_stale_pick_total 3
telemt_me_writer_removed_unexpected_total 6671
telemt_me_refill_failed_total 35
telemt_me_writer_restored_same_endpoint_total 6520
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 130
telemt_user_connections_total{user="hello"} 851077
telemt_user_connections_current{user="hello"} 1590
telemt_user_octets_from_client{user="hello"} 12740364680 (11.87 GB)
telemt_user_octets_to_client{user="hello"} 262727496076 (244.68 GB)
telemt_user_unique_ips_current{user="hello"} 550
telemt_user_unique_ips_recent_window{user="hello"} 242
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 47492.0 (13h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2885334
telemt_connections_bad_total 168871
telemt_connections_current 4642
telemt_connections_me_current 4642
telemt_handshake_timeouts_total 56439
telemt_upstream_connect_attempt_total 9054
telemt_upstream_connect_success_total 8888
telemt_upstream_connect_fail_total 166
telemt_upstream_connect_attempts_per_request{bucket="1"} 9054
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4478
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4383
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 166
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 11246
telemt_me_reconnect_success_total 6487
telemt_me_reader_eof_total 6952
telemt_me_idle_close_by_peer_total 6951
telemt_me_seq_mismatch_total 13
telemt_me_route_drop_no_conn_total 1839411
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2428523
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 35
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10040
telemt_desync_full_logged_total 3360
telemt_desync_suppressed_total 6680
telemt_desync_frames_bucket_total{bucket="1_2"} 1922
telemt_desync_frames_bucket_total{bucket="3_10"} 3955
telemt_desync_frames_bucket_total{bucket="gt_10"} 4163
telemt_pool_swap_total 33
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 6752
telemt_me_refill_failed_total 148
telemt_me_writer_restored_same_endpoint_total 6465
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 265
telemt_user_connections_total{user="hello"} 2428144
telemt_user_connections_current{user="hello"} 4642
telemt_user_octets_from_client{user="hello"} 34249756948 (31.90 GB)
telemt_user_octets_to_client{user="hello"} 783083286700 (729.30 GB)
telemt_user_unique_ips_current{user="hello"} 1367
telemt_user_unique_ips_recent_window{user="hello"} 993
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 47489.1 (13h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2322700
telemt_connections_bad_total 267976
telemt_connections_current 3309
telemt_connections_me_current 3309
telemt_handshake_timeouts_total 50183
telemt_upstream_connect_attempt_total 8524
telemt_upstream_connect_success_total 8524
telemt_upstream_connect_attempts_per_request{bucket="1"} 8524
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4461
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4047
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 19
telemt_me_reconnect_attempts_total 6159
telemt_me_reconnect_success_total 6117
telemt_me_reader_eof_total 6460
telemt_me_idle_close_by_peer_total 6460
telemt_me_route_drop_no_conn_total 1434731
telemt_me_route_drop_channel_closed_total 74
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1830166
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7766
telemt_desync_full_logged_total 2474
telemt_desync_suppressed_total 5292
telemt_desync_frames_bucket_total{bucket="1_2"} 1722
telemt_desync_frames_bucket_total{bucket="3_10"} 2866
telemt_desync_frames_bucket_total{bucket="gt_10"} 3178
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 6223
telemt_me_writer_restored_same_endpoint_total 6101
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 106
telemt_user_connections_total{user="hello"} 1828485
telemt_user_connections_current{user="hello"} 3309
telemt_user_octets_from_client{user="hello"} 25861827812 (24.09 GB)
telemt_user_octets_to_client{user="hello"} 782668833000 (728.92 GB)
telemt_user_unique_ips_current{user="hello"} 1093
telemt_user_unique_ips_recent_window{user="hello"} 522
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 47542.4 (13h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2315859
telemt_connections_bad_total 125307
telemt_connections_current 3149
telemt_connections_me_current 3149
telemt_relay_adaptive_promotions_total 1
telemt_relay_adaptive_hard_promotions_total 1
telemt_handshake_timeouts_total 60628
telemt_upstream_connect_attempt_total 16828
telemt_upstream_connect_success_total 16662
telemt_upstream_connect_fail_total 166
telemt_upstream_connect_attempts_per_request{bucket="1"} 16828
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11670
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4828
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 162
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 166
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 9435
telemt_me_reconnect_success_total 6102
telemt_me_reader_eof_total 6475
telemt_me_idle_close_by_peer_total 6474
telemt_me_route_drop_no_conn_total 1167290
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1751493
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6404
telemt_desync_full_logged_total 2170
telemt_desync_suppressed_total 4234
telemt_desync_frames_bucket_total{bucket="1_2"} 1352
telemt_desync_frames_bucket_total{bucket="3_10"} 2488
telemt_desync_frames_bucket_total{bucket="gt_10"} 2564
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 6531
telemt_me_refill_failed_total 97
telemt_me_writer_restored_same_endpoint_total 6078
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 295
telemt_me_writer_removed_unexpected_minus_restored_total 429
telemt_user_connections_total{user="hello"} 1757689
telemt_user_connections_current{user="hello"} 3149
telemt_user_octets_from_client{user="hello"} 20009827396 (18.64 GB)
telemt_user_octets_to_client{user="hello"} 507318715458 (472.48 GB)
telemt_user_msgs_from_client{user="hello"} 28643
telemt_user_msgs_to_client{user="hello"} 76631
telemt_user_unique_ips_current{user="hello"} 1051
telemt_user_unique_ips_recent_window{user="hello"} 470
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 47485.7 (13h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2754998
telemt_connections_bad_total 613280
telemt_connections_current 3387
telemt_connections_me_current 3387
telemt_handshake_timeouts_total 54280
telemt_upstream_connect_attempt_total 8405
telemt_upstream_connect_success_total 8348
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 8405
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4272
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4045
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 7162
telemt_me_reconnect_success_total 5962
telemt_me_reader_eof_total 6328
telemt_me_idle_close_by_peer_total 6327
telemt_me_route_drop_no_conn_total 1013784
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1819590
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8030
telemt_desync_full_logged_total 2502
telemt_desync_suppressed_total 5528
telemt_desync_frames_bucket_total{bucket="1_2"} 1563
telemt_desync_frames_bucket_total{bucket="3_10"} 3461
telemt_desync_frames_bucket_total{bucket="gt_10"} 3006
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 6086
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 5938
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 124
telemt_user_connections_total{user="hello"} 1818667
telemt_user_connections_current{user="hello"} 3387
telemt_user_octets_from_client{user="hello"} 32320223244 (30.10 GB)
telemt_user_octets_to_client{user="hello"} 746818989856 (695.53 GB)
telemt_user_unique_ips_current{user="hello"} 1150
telemt_user_unique_ips_recent_window{user="hello"} 516
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 47497.7 (13h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 479456
telemt_connections_bad_total 18350
telemt_connections_current 991
telemt_connections_me_current 991
telemt_handshake_timeouts_total 3765
telemt_upstream_connect_attempt_total 11911
telemt_upstream_connect_success_total 11611
telemt_upstream_connect_fail_total 300
telemt_upstream_connect_attempts_per_request{bucket="1"} 11911
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5754
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5856
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 300
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 15640
telemt_me_reconnect_success_total 9220
telemt_me_reader_eof_total 9795
telemt_me_idle_close_by_peer_total 9795
telemt_me_route_drop_no_conn_total 247457
telemt_me_route_drop_channel_closed_total 28
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 433592
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 891
telemt_desync_full_logged_total 304
telemt_desync_suppressed_total 587
telemt_desync_frames_bucket_total{bucket="1_2"} 194
telemt_desync_frames_bucket_total{bucket="3_10"} 343
telemt_desync_frames_bucket_total{bucket="gt_10"} 354
telemt_pool_swap_total 22
telemt_pool_stale_pick_total 194
telemt_me_writer_removed_unexpected_total 9503
telemt_me_refill_failed_total 199
telemt_me_writer_restored_same_endpoint_total 9190
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 283
telemt_user_connections_total{user="hello"} 433540
telemt_user_connections_current{user="hello"} 991
telemt_user_octets_from_client{user="hello"} 7068997260 (6.58 GB)
telemt_user_octets_to_client{user="hello"} 163991091308 (152.73 GB)
telemt_user_unique_ips_current{user="hello"} 340
telemt_user_unique_ips_recent_window{user="hello"} 161
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 47488.1 (13h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1888363
telemt_connections_bad_total 166907
telemt_connections_current 3500
telemt_connections_me_current 3500
telemt_handshake_timeouts_total 71236
telemt_upstream_connect_attempt_total 9548
telemt_upstream_connect_success_total 9547
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 9548
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5158
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4386
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 50
telemt_me_reconnect_attempts_total 8508
telemt_me_reconnect_success_total 7152
telemt_me_reader_eof_total 7577
telemt_me_idle_close_by_peer_total 7576
telemt_me_route_drop_no_conn_total 816147
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1559229
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8766
telemt_desync_full_logged_total 2831
telemt_desync_suppressed_total 5935
telemt_desync_frames_bucket_total{bucket="1_2"} 1658
telemt_desync_frames_bucket_total{bucket="3_10"} 3331
telemt_desync_frames_bucket_total{bucket="gt_10"} 3777
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 7286
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 7137
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 134
telemt_user_connections_total{user="hello"} 1557963
telemt_user_connections_current{user="hello"} 3500
telemt_user_octets_from_client{user="hello"} 21713719296 (20.22 GB)
telemt_user_octets_to_client{user="hello"} 726856163544 (676.94 GB)
telemt_user_unique_ips_current{user="hello"} 1097
telemt_user_unique_ips_recent_window{user="hello"} 704
```