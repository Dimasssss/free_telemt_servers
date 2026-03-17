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

# Server Metrics 2026-03-17 17:27:51 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 81754.2 (22h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 980944
telemt_connections_bad_total 6536
telemt_handshake_timeouts_total 27721
telemt_upstream_connect_attempt_total 19357
telemt_upstream_connect_success_total 18879
telemt_upstream_connect_fail_total 478
telemt_upstream_connect_attempts_per_request{bucket="1"} 19357
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9838
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8873
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 168
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 478
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 172
telemt_me_reconnect_attempts_total 29605
telemt_me_reconnect_success_total 12489
telemt_me_reader_eof_total 13604
telemt_me_idle_close_by_peer_total 13603
telemt_me_route_drop_no_conn_total 448916
telemt_me_route_drop_channel_closed_total 122
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 897081
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5973
telemt_desync_full_logged_total 1693
telemt_desync_suppressed_total 4280
telemt_desync_frames_bucket_total{bucket="1_2"} 1655
telemt_desync_frames_bucket_total{bucket="3_10"} 2305
telemt_desync_frames_bucket_total{bucket="gt_10"} 2013
telemt_pool_swap_total 60
telemt_me_writer_removed_unexpected_total 13199
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 12467
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 710
telemt_user_connections_total{user="hello"} 891342
telemt_user_connections_current{user="hello"} 1199
telemt_user_octets_from_client{user="hello"} 13709241179 (12.77 GB)
telemt_user_octets_to_client{user="hello"} 304191305431 (283.30 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 386
telemt_user_unique_ips_recent_window{user="hello"} 151
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 82007.6 (22h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 825189
telemt_connections_bad_total 49350
telemt_handshake_timeouts_total 31042
telemt_upstream_connect_attempt_total 314967
telemt_upstream_connect_success_total 314227
telemt_upstream_connect_fail_total 740
telemt_upstream_connect_attempts_per_request{bucket="1"} 314967
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 260360
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23994
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29871
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 740
telemt_me_keepalive_timeout_total 342
telemt_me_reconnect_attempts_total 49834
telemt_me_reconnect_success_total 13565
telemt_me_reader_eof_total 15251
telemt_me_idle_close_by_peer_total 15251
telemt_me_route_drop_no_conn_total 233768
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 411862
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1538
telemt_desync_full_logged_total 487
telemt_desync_suppressed_total 1051
telemt_desync_frames_bucket_total{bucket="1_2"} 347
telemt_desync_frames_bucket_total{bucket="3_10"} 672
telemt_desync_frames_bucket_total{bucket="gt_10"} 519
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 14861
telemt_me_refill_failed_total 1129
telemt_me_writer_restored_same_endpoint_total 13549
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 1296
telemt_user_connections_total{user="hello"} 708296
telemt_user_connections_current{user="hello"} 1867
telemt_user_octets_from_client{user="hello"} 9428828959 (8.78 GB)
telemt_user_octets_to_client{user="hello"} 191484491490 (178.33 GB)
telemt_user_msgs_from_client{user="hello"} 4948325
telemt_user_msgs_to_client{user="hello"} 20618189
telemt_user_unique_ips_current{user="hello"} 405
telemt_user_unique_ips_recent_window{user="hello"} 459
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 81782.3 (22h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 423263
telemt_connections_bad_total 13897
telemt_handshake_timeouts_total 20577
telemt_upstream_connect_attempt_total 20523
telemt_upstream_connect_success_total 20406
telemt_upstream_connect_fail_total 117
telemt_upstream_connect_attempts_per_request{bucket="1"} 20523
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9270
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11050
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 81
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 117
telemt_me_keepalive_timeout_total 94
telemt_me_reconnect_attempts_total 36929
telemt_me_reconnect_success_total 16261
telemt_me_reader_eof_total 17792
telemt_me_idle_close_by_peer_total 17785
telemt_me_route_drop_no_conn_total 203206
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 367868
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1064
telemt_desync_full_logged_total 322
telemt_desync_suppressed_total 742
telemt_desync_frames_bucket_total{bucket="1_2"} 356
telemt_desync_frames_bucket_total{bucket="3_10"} 459
telemt_desync_frames_bucket_total{bucket="gt_10"} 249
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 17125
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 16249
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 864
telemt_user_connections_total{user="hello"} 366027
telemt_user_connections_current{user="hello"} 1491
telemt_user_octets_from_client{user="hello"} 24321940000 (22.65 GB)
telemt_user_octets_to_client{user="hello"} 128175294940 (119.37 GB)
telemt_user_unique_ips_current{user="hello"} 366
telemt_user_unique_ips_recent_window{user="hello"} 172
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 81841.3 (22h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 887722
telemt_connections_bad_total 19942
telemt_handshake_timeouts_total 16669
telemt_upstream_connect_attempt_total 80289
telemt_upstream_connect_success_total 79894
telemt_upstream_connect_fail_total 395
telemt_upstream_connect_attempts_per_request{bucket="1"} 80289
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 68694
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10844
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 29
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 327
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 395
telemt_me_keepalive_timeout_total 239
telemt_me_reconnect_attempts_total 32721
telemt_me_reconnect_success_total 12422
telemt_me_reader_eof_total 13720
telemt_me_idle_close_by_peer_total 13719
telemt_me_route_drop_no_conn_total 377945
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 708691
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2286
telemt_desync_full_logged_total 734
telemt_desync_suppressed_total 1552
telemt_desync_frames_bucket_total{bucket="1_2"} 538
telemt_desync_frames_bucket_total{bucket="3_10"} 1027
telemt_desync_frames_bucket_total{bucket="gt_10"} 721
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 13279
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 12413
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 857
telemt_user_connections_total{user="hello"} 771811
telemt_user_connections_current{user="hello"} 1835
telemt_user_octets_from_client{user="hello"} 9385954211 (8.74 GB)
telemt_user_octets_to_client{user="hello"} 248708388933 (231.63 GB)
telemt_user_msgs_from_client{user="hello"} 734453
telemt_user_msgs_to_client{user="hello"} 5166140
telemt_user_unique_ips_current{user="hello"} 452
telemt_user_unique_ips_recent_window{user="hello"} 212
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 81813.3 (22h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 461133
telemt_connections_bad_total 71546
telemt_handshake_timeouts_total 4408
telemt_upstream_connect_attempt_total 38676
telemt_upstream_connect_success_total 38176
telemt_upstream_connect_fail_total 500
telemt_upstream_connect_attempts_per_request{bucket="1"} 38676
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25027
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12792
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 357
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 500
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 50066
telemt_me_reconnect_success_total 17588
telemt_me_reader_eof_total 19203
telemt_me_idle_close_by_peer_total 19201
telemt_me_route_drop_no_conn_total 135657
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 348790
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1536
telemt_desync_full_logged_total 373
telemt_desync_suppressed_total 1163
telemt_desync_frames_bucket_total{bucket="1_2"} 644
telemt_desync_frames_bucket_total{bucket="3_10"} 612
telemt_desync_frames_bucket_total{bucket="gt_10"} 280
telemt_pool_swap_total 37
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 18895
telemt_me_refill_failed_total 1010
telemt_me_writer_restored_same_endpoint_total 17580
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1307
telemt_user_connections_total{user="hello"} 365495
telemt_user_connections_current{user="hello"} 1658
telemt_user_octets_from_client{user="hello"} 6034959760 (5.62 GB)
telemt_user_octets_to_client{user="hello"} 161544289156 (150.45 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 428
telemt_user_unique_ips_recent_window{user="hello"} 210
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 81975.1 (22h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 829218
telemt_connections_bad_total 60404
telemt_handshake_timeouts_total 7882
telemt_upstream_connect_attempt_total 16491
telemt_upstream_connect_success_total 16399
telemt_upstream_connect_fail_total 92
telemt_upstream_connect_attempts_per_request{bucket="1"} 16491
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7857
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8470
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 65
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 92
telemt_me_keepalive_timeout_total 117
telemt_me_reconnect_attempts_total 23540
telemt_me_reconnect_success_total 12271
telemt_me_reader_eof_total 13356
telemt_me_idle_close_by_peer_total 13354
telemt_me_route_drop_no_conn_total 620070
telemt_me_route_drop_channel_closed_total 73
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 854367
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1519
telemt_desync_full_logged_total 526
telemt_desync_suppressed_total 993
telemt_desync_frames_bucket_total{bucket="1_2"} 362
telemt_desync_frames_bucket_total{bucket="3_10"} 593
telemt_desync_frames_bucket_total{bucket="gt_10"} 564
telemt_pool_swap_total 65
telemt_me_writer_removed_unexpected_total 12830
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 12257
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 559
telemt_user_connections_total{user="hello"} 717436
telemt_user_connections_current{user="hello"} 889
telemt_user_octets_from_client{user="hello"} 10773170652 (10.03 GB)
telemt_user_octets_to_client{user="hello"} 316199130068 (294.48 GB)
telemt_user_unique_ips_current{user="hello"} 313
telemt_user_unique_ips_recent_window{user="hello"} 111
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 29741.6 (8h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 112706
telemt_connections_bad_total 7507
telemt_handshake_timeouts_total 1958
telemt_upstream_connect_attempt_total 14285
telemt_upstream_connect_success_total 14165
telemt_upstream_connect_fail_total 120
telemt_upstream_connect_attempts_per_request{bucket="1"} 14285
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7617
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6489
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 120
telemt_me_keepalive_timeout_total 51
telemt_me_reconnect_attempts_total 24077
telemt_me_reconnect_success_total 12502
telemt_me_reader_eof_total 13238
telemt_me_idle_close_by_peer_total 13238
telemt_me_seq_mismatch_total 15
telemt_me_route_drop_no_conn_total 29324
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 96879
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 17
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 152
telemt_desync_full_logged_total 43
telemt_desync_suppressed_total 109
telemt_desync_frames_bucket_total{bucket="1_2"} 46
telemt_desync_frames_bucket_total{bucket="3_10"} 52
telemt_desync_frames_bucket_total{bucket="gt_10"} 54
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 13012
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 12479
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 510
telemt_user_connections_total{user="hello"} 96856
telemt_user_connections_current{user="hello"} 1095
telemt_user_octets_from_client{user="hello"} 4591777861 (4.28 GB)
telemt_user_octets_to_client{user="hello"} 100705244994 (93.79 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 290
telemt_user_unique_ips_recent_window{user="hello"} 120
```