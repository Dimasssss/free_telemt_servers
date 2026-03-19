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

# Server Metrics 2026-03-19 07:45:33 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 35825.4 (9h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 635273
telemt_connections_bad_total 65035
telemt_connections_current 1415
telemt_connections_me_current 1415
telemt_handshake_timeouts_total 23974
telemt_upstream_connect_attempt_total 6856
telemt_upstream_connect_success_total 6729
telemt_upstream_connect_fail_total 127
telemt_upstream_connect_attempts_per_request{bucket="1"} 6856
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3266
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3460
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 127
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 68
telemt_me_reconnect_attempts_total 6095
telemt_me_reconnect_success_total 4945
telemt_me_reader_eof_total 5250
telemt_me_idle_close_by_peer_total 5249
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 180351
telemt_me_route_drop_channel_closed_total 62
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 481286
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 27
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3284
telemt_desync_full_logged_total 923
telemt_desync_suppressed_total 2361
telemt_desync_frames_bucket_total{bucket="1_2"} 1166
telemt_desync_frames_bucket_total{bucket="3_10"} 1228
telemt_desync_frames_bucket_total{bucket="gt_10"} 890
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 5037
telemt_me_refill_failed_total 35
telemt_me_writer_restored_same_endpoint_total 4928
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 92
telemt_user_connections_total{user="hello"} 478398
telemt_user_connections_current{user="hello"} 1415
telemt_user_octets_from_client{user="hello"} 6260526592 (5.83 GB)
telemt_user_octets_to_client{user="hello"} 160499231740 (149.48 GB)
telemt_user_unique_ips_current{user="hello"} 513
telemt_user_unique_ips_recent_window{user="hello"} 210
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 35829.5 (9h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1511908
telemt_connections_bad_total 83606
telemt_connections_current 3858
telemt_connections_me_current 3858
telemt_handshake_timeouts_total 36331
telemt_upstream_connect_attempt_total 6710
telemt_upstream_connect_success_total 6582
telemt_upstream_connect_fail_total 128
telemt_upstream_connect_attempts_per_request{bucket="1"} 6710
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3266
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3299
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 128
telemt_me_keepalive_timeout_total 26
telemt_me_reconnect_attempts_total 5938
telemt_me_reconnect_success_total 4783
telemt_me_reader_eof_total 5075
telemt_me_idle_close_by_peer_total 5075
telemt_me_seq_mismatch_total 12
telemt_me_route_drop_no_conn_total 624875
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1243181
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 34
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5573
telemt_desync_full_logged_total 1861
telemt_desync_suppressed_total 3712
telemt_desync_frames_bucket_total{bucket="1_2"} 990
telemt_desync_frames_bucket_total{bucket="3_10"} 2117
telemt_desync_frames_bucket_total{bucket="gt_10"} 2466
telemt_pool_swap_total 29
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 4908
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 4762
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 125
telemt_user_connections_total{user="hello"} 1243087
telemt_user_connections_current{user="hello"} 3858
telemt_user_octets_from_client{user="hello"} 22633135092 (21.08 GB)
telemt_user_octets_to_client{user="hello"} 492647677256 (458.81 GB)
telemt_user_unique_ips_current{user="hello"} 1381
telemt_user_unique_ips_recent_window{user="hello"} 597
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 35827.1 (9h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1290243
telemt_connections_bad_total 183349
telemt_connections_current 3155
telemt_connections_me_current 3155
telemt_handshake_timeouts_total 34364
telemt_upstream_connect_attempt_total 6395
telemt_upstream_connect_success_total 6395
telemt_upstream_connect_attempts_per_request{bucket="1"} 6395
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3301
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3084
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 4625
telemt_me_reconnect_success_total 4600
telemt_me_reader_eof_total 4873
telemt_me_idle_close_by_peer_total 4873
telemt_me_route_drop_no_conn_total 544088
telemt_me_route_drop_channel_closed_total 44
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 970567
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4570
telemt_desync_full_logged_total 1420
telemt_desync_suppressed_total 3150
telemt_desync_frames_bucket_total{bucket="1_2"} 968
telemt_desync_frames_bucket_total{bucket="3_10"} 1631
telemt_desync_frames_bucket_total{bucket="gt_10"} 1971
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 4685
telemt_me_writer_restored_same_endpoint_total 4584
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 85
telemt_user_connections_total{user="hello"} 970165
telemt_user_connections_current{user="hello"} 3155
telemt_user_octets_from_client{user="hello"} 17419777000 (16.22 GB)
telemt_user_octets_to_client{user="hello"} 491228843912 (457.49 GB)
telemt_user_unique_ips_current{user="hello"} 1080
telemt_user_unique_ips_recent_window{user="hello"} 503
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 35879.7 (9h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1331421
telemt_connections_bad_total 89842
telemt_connections_current 2853
telemt_connections_me_current 2853
telemt_handshake_timeouts_total 32590
telemt_upstream_connect_attempt_total 6275
telemt_upstream_connect_success_total 6275
telemt_upstream_connect_attempts_per_request{bucket="1"} 6275
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3178
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3081
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 5528
telemt_me_reconnect_success_total 4466
telemt_me_reader_eof_total 4740
telemt_me_idle_close_by_peer_total 4739
telemt_me_route_drop_no_conn_total 501189
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 918859
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3471
telemt_desync_full_logged_total 1192
telemt_desync_suppressed_total 2279
telemt_desync_frames_bucket_total{bucket="1_2"} 669
telemt_desync_frames_bucket_total{bucket="3_10"} 1351
telemt_desync_frames_bucket_total{bucket="gt_10"} 1451
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 4562
telemt_me_refill_failed_total 32
telemt_me_writer_restored_same_endpoint_total 4442
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 272
telemt_me_writer_removed_unexpected_minus_restored_total 96
telemt_user_connections_total{user="hello"} 917648
telemt_user_connections_current{user="hello"} 2853
telemt_user_octets_from_client{user="hello"} 12793354828 (11.91 GB)
telemt_user_octets_to_client{user="hello"} 318063548384 (296.22 GB)
telemt_user_unique_ips_current{user="hello"} 973
telemt_user_unique_ips_recent_window{user="hello"} 457
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 35823.1 (9h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1603045
telemt_connections_bad_total 429037
telemt_connections_current 3338
telemt_connections_me_current 3338
telemt_handshake_timeouts_total 34378
telemt_upstream_connect_attempt_total 6248
telemt_upstream_connect_success_total 6209
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 6248
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3141
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3047
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_reconnect_attempts_total 4452
telemt_me_reconnect_success_total 4419
telemt_me_reader_eof_total 4684
telemt_me_idle_close_by_peer_total 4684
telemt_me_route_drop_no_conn_total 403313
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 969594
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4692
telemt_desync_full_logged_total 1456
telemt_desync_suppressed_total 3236
telemt_desync_frames_bucket_total{bucket="1_2"} 1027
telemt_desync_frames_bucket_total{bucket="3_10"} 2130
telemt_desync_frames_bucket_total{bucket="gt_10"} 1535
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 4477
telemt_me_writer_restored_same_endpoint_total 4395
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 58
telemt_user_connections_total{user="hello"} 969275
telemt_user_connections_current{user="hello"} 3338
telemt_user_octets_from_client{user="hello"} 20443946676 (19.04 GB)
telemt_user_octets_to_client{user="hello"} 469993961872 (437.72 GB)
telemt_user_unique_ips_current{user="hello"} 1113
telemt_user_unique_ips_recent_window{user="hello"} 566
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 35835.0 (9h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 270301
telemt_connections_bad_total 13099
telemt_connections_current 912
telemt_connections_me_current 912
telemt_handshake_timeouts_total 2470
telemt_upstream_connect_attempt_total 9344
telemt_upstream_connect_success_total 9102
telemt_upstream_connect_fail_total 242
telemt_upstream_connect_attempts_per_request{bucket="1"} 9344
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4472
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4629
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 242
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 12684
telemt_me_reconnect_success_total 7308
telemt_me_reader_eof_total 7760
telemt_me_idle_close_by_peer_total 7760
telemt_me_route_drop_no_conn_total 126741
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 240779
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 357
telemt_desync_full_logged_total 123
telemt_desync_suppressed_total 234
telemt_desync_frames_bucket_total{bucket="1_2"} 109
telemt_desync_frames_bucket_total{bucket="3_10"} 151
telemt_desync_frames_bucket_total{bucket="gt_10"} 97
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 7524
telemt_me_refill_failed_total 167
telemt_me_writer_restored_same_endpoint_total 7278
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 216
telemt_user_connections_total{user="hello"} 240752
telemt_user_connections_current{user="hello"} 912
telemt_user_octets_from_client{user="hello"} 3594704172 (3.35 GB)
telemt_user_octets_to_client{user="hello"} 115863452184 (107.91 GB)
telemt_user_unique_ips_current{user="hello"} 313
telemt_user_unique_ips_recent_window{user="hello"} 127
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 35825.8 (9h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1019902
telemt_connections_bad_total 93289
telemt_connections_current 3082
telemt_connections_me_current 3082
telemt_handshake_timeouts_total 45341
telemt_upstream_connect_attempt_total 7235
telemt_upstream_connect_success_total 7235
telemt_upstream_connect_attempts_per_request{bucket="1"} 7235
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3856
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3376
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 6779
telemt_me_reconnect_success_total 5444
telemt_me_reader_eof_total 5782
telemt_me_idle_close_by_peer_total 5782
telemt_me_route_drop_no_conn_total 406031
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 842420
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5024
telemt_desync_full_logged_total 1662
telemt_desync_suppressed_total 3362
telemt_desync_frames_bucket_total{bucket="1_2"} 1010
telemt_desync_frames_bucket_total{bucket="3_10"} 1920
telemt_desync_frames_bucket_total{bucket="gt_10"} 2094
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 5547
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 5429
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 103
telemt_user_connections_total{user="hello"} 841490
telemt_user_connections_current{user="hello"} 3082
telemt_user_octets_from_client{user="hello"} 12382209644 (11.53 GB)
telemt_user_octets_to_client{user="hello"} 453542572196 (422.39 GB)
telemt_user_unique_ips_current{user="hello"} 984
telemt_user_unique_ips_recent_window{user="hello"} 425
```