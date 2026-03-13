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

# Server Metrics 2026-03-13 07:48:52 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 87328.0 (24h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 336525
telemt_connections_bad_total 3167
telemt_handshake_timeouts_total 7485
telemt_upstream_connect_attempt_total 21891
telemt_upstream_connect_success_total 21791
telemt_upstream_connect_fail_total 100
telemt_upstream_connect_attempts_per_request{bucket="1"} 21891
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9793
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11950
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 100
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1657
telemt_me_reconnect_attempts_total 20930
telemt_me_reconnect_success_total 17425
telemt_me_reader_eof_total 18635
telemt_me_idle_close_by_peer_total 18634
telemt_me_route_drop_no_conn_total 105239
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 286342
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 955
telemt_desync_full_logged_total 352
telemt_desync_suppressed_total 603
telemt_desync_frames_bucket_total{bucket="1_2"} 190
telemt_desync_frames_bucket_total{bucket="3_10"} 350
telemt_desync_frames_bucket_total{bucket="gt_10"} 415
telemt_pool_swap_total 79
telemt_me_writer_removed_unexpected_total 17720
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 17409
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 295
telemt_user_connections_total{user="hello"} 286035
telemt_user_connections_current{user="hello"} 254
telemt_user_octets_from_client{user="hello"} 4749156572 (4.42 GB)
telemt_user_octets_to_client{user="hello"} 132912791204 (123.78 GB)
telemt_user_unique_ips_current{user="hello"} 85
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 87220.7 (24h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 153159
telemt_connections_bad_total 1478
telemt_handshake_timeouts_total 1180
telemt_upstream_connect_attempt_total 44748
telemt_upstream_connect_success_total 44146
telemt_upstream_connect_fail_total 602
telemt_upstream_connect_attempts_per_request{bucket="1"} 44748
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25802
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17833
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 511
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 602
telemt_me_keepalive_timeout_total 672
telemt_me_reconnect_attempts_total 75956
telemt_me_reconnect_success_total 23303
telemt_me_reader_eof_total 25641
telemt_me_idle_close_by_peer_total 25641
telemt_me_route_drop_no_conn_total 57572
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 128243
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 18
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
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 25140
telemt_me_refill_failed_total 1643
telemt_me_writer_restored_same_endpoint_total 23288
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1837
telemt_user_connections_total{user="hello"} 144735
telemt_user_connections_current{user="hello"} 131
telemt_user_octets_from_client{user="hello"} 1500661640 (1.40 GB)
telemt_user_octets_to_client{user="hello"} 46268772719 (43.09 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 87184.4 (24h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 185246
telemt_connections_bad_total 1973
telemt_handshake_timeouts_total 3082
telemt_upstream_connect_attempt_total 23666
telemt_upstream_connect_success_total 23664
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 23666
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10883
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12758
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 568
telemt_me_reconnect_attempts_total 20460
telemt_me_reconnect_success_total 19283
telemt_me_reader_eof_total 20677
telemt_me_idle_close_by_peer_total 20677
telemt_me_route_drop_no_conn_total 71519
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 173322
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 62
telemt_desync_full_logged_total 30
telemt_desync_suppressed_total 32
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 20
telemt_desync_frames_bucket_total{bucket="gt_10"} 39
telemt_pool_swap_total 80
telemt_me_writer_removed_unexpected_total 19493
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 19263
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 210
telemt_user_connections_total{user="hello"} 173252
telemt_user_connections_current{user="hello"} 135
telemt_user_octets_from_client{user="hello"} 4529924368 (4.22 GB)
telemt_user_octets_to_client{user="hello"} 74522658520 (69.40 GB)
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 87160.1 (24h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 268041
telemt_connections_bad_total 13617
telemt_handshake_timeouts_total 2018
telemt_upstream_connect_attempt_total 36386
telemt_upstream_connect_success_total 26435
telemt_upstream_connect_fail_total 9951
telemt_upstream_connect_attempts_per_request{bucket="1"} 36386
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13227
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13022
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 177
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9951
telemt_me_keepalive_timeout_total 3368
telemt_me_reconnect_attempts_total 70776
telemt_me_reconnect_success_total 19232
telemt_me_reader_eof_total 21452
telemt_me_idle_close_by_peer_total 21445
telemt_me_route_drop_no_conn_total 96414
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 227111
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 814
telemt_desync_full_logged_total 237
telemt_desync_suppressed_total 577
telemt_desync_frames_bucket_total{bucket="1_2"} 199
telemt_desync_frames_bucket_total{bucket="3_10"} 303
telemt_desync_frames_bucket_total{bucket="gt_10"} 312
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 21090
telemt_me_refill_failed_total 1606
telemt_me_writer_restored_same_endpoint_total 19222
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1858
telemt_user_connections_total{user="hello"} 229839
telemt_user_connections_current{user="hello"} 205
telemt_user_octets_from_client{user="hello"} 5224693222 (4.87 GB)
telemt_user_octets_to_client{user="hello"} 87468401161 (81.46 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 65
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 37331.6 (10h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 45910
telemt_connections_bad_total 7645
telemt_handshake_timeouts_total 401
telemt_upstream_connect_attempt_total 12711
telemt_upstream_connect_success_total 12581
telemt_upstream_connect_fail_total 130
telemt_upstream_connect_attempts_per_request{bucket="1"} 12711
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5482
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7056
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 130
telemt_me_keepalive_timeout_total 304
telemt_me_reconnect_attempts_total 11674
telemt_me_reconnect_success_total 10705
telemt_me_reader_eof_total 11419
telemt_me_idle_close_by_peer_total 11419
telemt_me_route_drop_no_conn_total 13254
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 36593
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 64
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 58
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 23
telemt_desync_frames_bucket_total{bucket="gt_10"} 34
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 10829
telemt_me_refill_failed_total 29
telemt_me_writer_restored_same_endpoint_total 10687
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 124
telemt_user_connections_total{user="hello"} 36592
telemt_user_connections_current{user="hello"} 67
telemt_user_octets_from_client{user="hello"} 265766460 (253.45 MB)
telemt_user_octets_to_client{user="hello"} 11063045180 (10.30 GB)
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 87116.6 (24h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 456493
telemt_connections_bad_total 11701
telemt_handshake_timeouts_total 3692
telemt_upstream_connect_attempt_total 18460
telemt_upstream_connect_success_total 18361
telemt_upstream_connect_fail_total 99
telemt_upstream_connect_attempts_per_request{bucket="1"} 18460
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8587
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9749
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 99
telemt_me_keepalive_timeout_total 1522
telemt_me_reconnect_attempts_total 17682
telemt_me_reconnect_success_total 14041
telemt_me_reader_eof_total 15083
telemt_me_idle_close_by_peer_total 15080
telemt_me_route_drop_no_conn_total 215947
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 442840
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 369
telemt_desync_full_logged_total 142
telemt_desync_suppressed_total 227
telemt_desync_frames_bucket_total{bucket="1_2"} 89
telemt_desync_frames_bucket_total{bucket="3_10"} 132
telemt_desync_frames_bucket_total{bucket="gt_10"} 148
telemt_pool_swap_total 82
telemt_me_writer_removed_unexpected_total 14334
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 14034
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 293
telemt_user_connections_total{user="hello"} 425252
telemt_user_connections_current{user="hello"} 433
telemt_user_octets_from_client{user="hello"} 7908477112 (7.37 GB)
telemt_user_octets_to_client{user="hello"} 245843551556 (228.96 GB)
telemt_user_unique_ips_current{user="hello"} 152
telemt_user_unique_ips_recent_window{user="hello"} 59
```