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

# Server Metrics 2026-03-12 14:35:36 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 25333.7 (7h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 134280
telemt_connections_bad_total 1377
telemt_handshake_timeouts_total 4526
telemt_upstream_connect_attempt_total 6190
telemt_upstream_connect_success_total 6166
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 6190
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2731
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3429
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_keepalive_timeout_total 272
telemt_me_reconnect_attempts_total 4869
telemt_me_reconnect_success_total 4837
telemt_me_reader_eof_total 5088
telemt_me_idle_close_by_peer_total 5087
telemt_me_route_drop_no_conn_total 38112
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 117359
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 558
telemt_desync_full_logged_total 207
telemt_desync_suppressed_total 351
telemt_desync_frames_bucket_total{bucket="1_2"} 103
telemt_desync_frames_bucket_total{bucket="3_10"} 218
telemt_desync_frames_bucket_total{bucket="gt_10"} 237
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 4880
telemt_me_writer_restored_same_endpoint_total 4821
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 117321
telemt_user_connections_current{user="hello"} 397
telemt_user_octets_from_client{user="hello"} 1954864656 (1.82 GB)
telemt_user_octets_to_client{user="hello"} 43799372636 (40.79 GB)
telemt_user_unique_ips_current{user="hello"} 111
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 25226.4 (7h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 55649
telemt_connections_bad_total 445
telemt_handshake_timeouts_total 363
telemt_upstream_connect_attempt_total 7613
telemt_upstream_connect_success_total 7442
telemt_upstream_connect_fail_total 171
telemt_upstream_connect_attempts_per_request{bucket="1"} 7613
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3074
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4337
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 171
telemt_me_keepalive_timeout_total 168
telemt_me_reconnect_attempts_total 22012
telemt_me_reconnect_success_total 6178
telemt_me_reader_eof_total 6791
telemt_me_idle_close_by_peer_total 6791
telemt_me_route_drop_no_conn_total 24912
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 53124
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
telemt_me_writer_removed_unexpected_total 6712
telemt_me_refill_failed_total 494
telemt_me_writer_restored_same_endpoint_total 6163
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 534
telemt_user_connections_total{user="hello"} 53116
telemt_user_connections_current{user="hello"} 145
telemt_user_octets_from_client{user="hello"} 610005228 (581.75 MB)
telemt_user_octets_to_client{user="hello"} 15589022504 (14.52 GB)
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 25190.2 (6h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 76689
telemt_connections_bad_total 1423
telemt_handshake_timeouts_total 1293
telemt_upstream_connect_attempt_total 6798
telemt_upstream_connect_success_total 6798
telemt_upstream_connect_attempts_per_request{bucket="1"} 6798
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3297
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3491
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 5540
telemt_me_reconnect_success_total 5497
telemt_me_reader_eof_total 5801
telemt_me_idle_close_by_peer_total 5801
telemt_me_route_drop_no_conn_total 26924
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 70716
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
telemt_me_writer_removed_unexpected_total 5537
telemt_me_writer_restored_same_endpoint_total 5477
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 40
telemt_user_connections_total{user="hello"} 70694
telemt_user_connections_current{user="hello"} 212
telemt_user_octets_from_client{user="hello"} 1921058708 (1.79 GB)
telemt_user_octets_to_client{user="hello"} 39989844024 (37.24 GB)
telemt_user_unique_ips_current{user="hello"} 83
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 25165.6 (6h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 97514
telemt_connections_bad_total 2953
telemt_handshake_timeouts_total 723
telemt_upstream_connect_attempt_total 6490
telemt_upstream_connect_success_total 6321
telemt_upstream_connect_fail_total 169
telemt_upstream_connect_attempts_per_request{bucket="1"} 6490
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2828
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3471
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 169
telemt_me_keepalive_timeout_total 256
telemt_me_reconnect_attempts_total 19492
telemt_me_reconnect_success_total 5040
telemt_me_reader_eof_total 5624
telemt_me_idle_close_by_peer_total 5624
telemt_me_route_drop_no_conn_total 35815
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 88312
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 284
telemt_desync_full_logged_total 94
telemt_desync_suppressed_total 190
telemt_desync_frames_bucket_total{bucket="1_2"} 100
telemt_desync_frames_bucket_total{bucket="3_10"} 94
telemt_desync_frames_bucket_total{bucket="gt_10"} 90
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 5549
telemt_me_refill_failed_total 450
telemt_me_writer_restored_same_endpoint_total 5032
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 121
telemt_me_writer_removed_unexpected_minus_restored_total 509
telemt_user_connections_total{user="hello"} 88195
telemt_user_connections_current{user="hello"} 192
telemt_user_octets_from_client{user="hello"} 1521775116 (1.42 GB)
telemt_user_octets_to_client{user="hello"} 37385115304 (34.82 GB)
telemt_user_unique_ips_current{user="hello"} 65
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 25135.0 (6h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 57406
telemt_connections_bad_total 4888
telemt_handshake_timeouts_total 873
telemt_upstream_connect_attempt_total 22520
telemt_upstream_connect_success_total 22211
telemt_upstream_connect_fail_total 309
telemt_upstream_connect_attempts_per_request{bucket="1"} 22520
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17886
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4297
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 309
telemt_me_keepalive_timeout_total 105
telemt_me_reconnect_attempts_total 32831
telemt_me_reconnect_success_total 3684
telemt_me_reader_eof_total 4591
telemt_me_idle_close_by_peer_total 4591
telemt_me_seq_mismatch_total 8
telemt_me_route_drop_no_conn_total 12321
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 32951
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 443
telemt_desync_full_logged_total 123
telemt_desync_suppressed_total 320
telemt_desync_frames_bucket_total{bucket="1_2"} 16
telemt_desync_frames_bucket_total{bucket="3_10"} 369
telemt_desync_frames_bucket_total{bucket="gt_10"} 58
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 4616
telemt_me_refill_failed_total 912
telemt_me_writer_restored_same_endpoint_total 3667
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 932
telemt_user_connections_total{user="hello"} 50199
telemt_user_connections_current{user="hello"} 149
telemt_user_octets_from_client{user="hello"} 416734964 (397.43 MB)
telemt_user_octets_to_client{user="hello"} 12534698696 (11.67 GB)
telemt_user_msgs_from_client{user="hello"} 248009
telemt_user_msgs_to_client{user="hello"} 709107
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 25122.4 (6h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 153277
telemt_connections_bad_total 782
telemt_handshake_timeouts_total 1192
telemt_upstream_connect_attempt_total 5125
telemt_upstream_connect_success_total 5098
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 5125
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2424
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2672
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 3860
telemt_me_reconnect_success_total 3829
telemt_me_reader_eof_total 4036
telemt_me_idle_close_by_peer_total 4036
telemt_me_route_drop_no_conn_total 60162
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 146578
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 231
telemt_desync_full_logged_total 85
telemt_desync_suppressed_total 146
telemt_desync_frames_bucket_total{bucket="1_2"} 57
telemt_desync_frames_bucket_total{bucket="3_10"} 88
telemt_desync_frames_bucket_total{bucket="gt_10"} 86
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 3875
telemt_me_writer_restored_same_endpoint_total 3822
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 146544
telemt_user_connections_current{user="hello"} 456
telemt_user_octets_from_client{user="hello"} 2920415052 (2.72 GB)
telemt_user_octets_to_client{user="hello"} 61523924864 (57.30 GB)
telemt_user_unique_ips_current{user="hello"} 153
telemt_user_unique_ips_recent_window{user="hello"} 52
```