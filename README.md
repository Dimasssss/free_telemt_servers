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

# Server Metrics 2026-03-14 05:15:46 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 164546.2 (45h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 636055
telemt_connections_bad_total 32287
telemt_handshake_timeouts_total 12974
telemt_upstream_connect_attempt_total 42009
telemt_upstream_connect_success_total 41794
telemt_upstream_connect_fail_total 215
telemt_upstream_connect_attempts_per_request{bucket="1"} 42009
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19086
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22557
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 151
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 215
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 5563
telemt_me_reconnect_attempts_total 37906
telemt_me_reconnect_success_total 33220
telemt_me_reader_eof_total 35512
telemt_me_idle_close_by_peer_total 35511
telemt_me_route_drop_no_conn_total 207084
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 538654
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1902
telemt_desync_full_logged_total 643
telemt_desync_suppressed_total 1259
telemt_desync_frames_bucket_total{bucket="1_2"} 410
telemt_desync_frames_bucket_total{bucket="3_10"} 697
telemt_desync_frames_bucket_total{bucket="gt_10"} 795
telemt_pool_swap_total 151
telemt_me_writer_removed_unexpected_total 33728
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 33200
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 508
telemt_user_connections_total{user="hello"} 538538
telemt_user_connections_current{user="hello"} 291
telemt_user_octets_from_client{user="hello"} 15869893070 (14.78 GB)
telemt_user_octets_to_client{user="hello"} 260545117312 (242.65 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 80
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 164439.0 (45h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 321245
telemt_connections_bad_total 2280
telemt_handshake_timeouts_total 2334
telemt_upstream_connect_attempt_total 147905
telemt_upstream_connect_success_total 146700
telemt_upstream_connect_fail_total 1205
telemt_upstream_connect_attempts_per_request{bucket="1"} 147905
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 109054
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35228
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2418
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1205
telemt_me_keepalive_timeout_total 3890
telemt_me_reconnect_attempts_total 172014
telemt_me_reconnect_success_total 35203
telemt_me_reader_eof_total 40419
telemt_me_idle_close_by_peer_total 40419
telemt_me_route_drop_no_conn_total 102346
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 201168
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 42
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 33
telemt_desync_full_logged_total 11
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 39809
telemt_me_refill_failed_total 4269
telemt_me_writer_restored_same_endpoint_total 35186
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 4606
telemt_user_connections_total{user="hello"} 304277
telemt_user_connections_current{user="hello"} 115
telemt_user_octets_from_client{user="hello"} 3158146831 (2.94 GB)
telemt_user_octets_to_client{user="hello"} 98662703883 (91.89 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 164402.7 (45h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 373405
telemt_connections_bad_total 2957
telemt_handshake_timeouts_total 34909
telemt_upstream_connect_attempt_total 43548
telemt_upstream_connect_success_total 43539
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 43548
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19877
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23594
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3405
telemt_me_reconnect_attempts_total 36593
telemt_me_reconnect_success_total 35310
telemt_me_reader_eof_total 37961
telemt_me_idle_close_by_peer_total 37961
telemt_me_route_drop_no_conn_total 134053
telemt_me_route_drop_channel_closed_total 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 322574
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 112
telemt_desync_full_logged_total 52
telemt_desync_suppressed_total 60
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 38
telemt_desync_frames_bucket_total{bucket="gt_10"} 62
telemt_pool_swap_total 155
telemt_me_writer_removed_unexpected_total 35739
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 35289
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 429
telemt_user_connections_total{user="hello"} 322351
telemt_user_connections_current{user="hello"} 115
telemt_user_octets_from_client{user="hello"} 12721329288 (11.85 GB)
telemt_user_octets_to_client{user="hello"} 128627276136 (119.79 GB)
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 164378.2 (45h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 475191
telemt_connections_bad_total 15639
telemt_handshake_timeouts_total 4414
telemt_upstream_connect_attempt_total 73496
telemt_upstream_connect_success_total 62961
telemt_upstream_connect_fail_total 10535
telemt_upstream_connect_attempts_per_request{bucket="1"} 73496
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37417
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25200
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 335
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10535
telemt_me_keepalive_timeout_total 5297
telemt_me_reconnect_attempts_total 141793
telemt_me_reconnect_success_total 35742
telemt_me_reader_eof_total 40183
telemt_me_idle_close_by_peer_total 40175
telemt_me_route_drop_no_conn_total 170625
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 403615
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 33
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1716
telemt_desync_full_logged_total 505
telemt_desync_suppressed_total 1211
telemt_desync_frames_bucket_total{bucket="1_2"} 404
telemt_desync_frames_bucket_total{bucket="3_10"} 648
telemt_desync_frames_bucket_total{bucket="gt_10"} 664
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 39465
telemt_me_refill_failed_total 3307
telemt_me_writer_restored_same_endpoint_total 35732
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3723
telemt_user_connections_total{user="hello"} 422456
telemt_user_connections_current{user="hello"} 126
telemt_user_octets_from_client{user="hello"} 9221858667 (8.59 GB)
telemt_user_octets_to_client{user="hello"} 165907071616 (154.51 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 114549.8 (31h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 187402
telemt_connections_bad_total 27179
telemt_handshake_timeouts_total 1658
telemt_upstream_connect_attempt_total 41094
telemt_upstream_connect_success_total 40712
telemt_upstream_connect_fail_total 382
telemt_upstream_connect_attempts_per_request{bucket="1"} 41094
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20423
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20155
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 134
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 382
telemt_me_keepalive_timeout_total 2411
telemt_me_reconnect_attempts_total 43530
telemt_me_reconnect_success_total 30105
telemt_me_reader_eof_total 32231
telemt_me_idle_close_by_peer_total 32231
telemt_me_route_drop_no_conn_total 55590
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 148530
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 622
telemt_desync_full_logged_total 146
telemt_desync_suppressed_total 476
telemt_desync_frames_bucket_total{bucket="1_2"} 98
telemt_desync_frames_bucket_total{bucket="3_10"} 306
telemt_desync_frames_bucket_total{bucket="gt_10"} 218
telemt_pool_swap_total 87
telemt_me_writer_removed_unexpected_total 30795
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 30087
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 690
telemt_user_connections_total{user="hello"} 153283
telemt_user_connections_current{user="hello"} 65
telemt_user_octets_from_client{user="hello"} 2266183437 (2.11 GB)
telemt_user_octets_to_client{user="hello"} 69736552975 (64.95 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 164334.3 (45h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 935311
telemt_connections_bad_total 32071
telemt_handshake_timeouts_total 25796
telemt_upstream_connect_attempt_total 34155
telemt_upstream_connect_success_total 33971
telemt_upstream_connect_fail_total 184
telemt_upstream_connect_attempts_per_request{bucket="1"} 34155
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15933
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17997
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 184
telemt_me_keepalive_timeout_total 4592
telemt_me_reconnect_attempts_total 30515
telemt_me_reconnect_success_total 25843
telemt_me_reader_eof_total 27739
telemt_me_idle_close_by_peer_total 27736
telemt_me_route_drop_no_conn_total 442762
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 869918
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 760
telemt_desync_full_logged_total 250
telemt_desync_suppressed_total 510
telemt_desync_frames_bucket_total{bucket="1_2"} 256
telemt_desync_frames_bucket_total{bucket="3_10"} 248
telemt_desync_frames_bucket_total{bucket="gt_10"} 256
telemt_pool_swap_total 155
telemt_me_writer_removed_unexpected_total 26317
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 25836
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 474
telemt_user_connections_total{user="hello"} 842578
telemt_user_connections_current{user="hello"} 341
telemt_user_octets_from_client{user="hello"} 14685023912 (13.68 GB)
telemt_user_octets_to_client{user="hello"} 428557581576 (399.13 GB)
telemt_user_unique_ips_current{user="hello"} 139
telemt_user_unique_ips_recent_window{user="hello"} 37
```