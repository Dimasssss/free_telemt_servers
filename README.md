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

# Server Metrics 2026-03-18 07:38:44 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 132806.9 (36h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1820391
telemt_connections_bad_total 11643
telemt_handshake_timeouts_total 37660
telemt_upstream_connect_attempt_total 28768
telemt_upstream_connect_success_total 28244
telemt_upstream_connect_fail_total 524
telemt_upstream_connect_attempts_per_request{bucket="1"} 28768
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14442
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13594
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 524
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 289
telemt_me_reconnect_attempts_total 36506
telemt_me_reconnect_success_total 19343
telemt_me_reader_eof_total 20939
telemt_me_idle_close_by_peer_total 20938
telemt_me_route_drop_no_conn_total 663693
telemt_me_route_drop_channel_closed_total 196
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1459867
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8766
telemt_desync_full_logged_total 2658
telemt_desync_suppressed_total 6108
telemt_desync_frames_bucket_total{bucket="1_2"} 2262
telemt_desync_frames_bucket_total{bucket="3_10"} 3387
telemt_desync_frames_bucket_total{bucket="gt_10"} 3117
telemt_pool_swap_total 112
telemt_me_writer_removed_unexpected_total 20166
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 19321
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 823
telemt_user_connections_total{user="hello"} 1454134
telemt_user_connections_current{user="hello"} 1292
telemt_user_octets_from_client{user="hello"} 33501842279 (31.20 GB)
telemt_user_octets_to_client{user="hello"} 515865270055 (480.44 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 445
telemt_user_unique_ips_recent_window{user="hello"} 172
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 133058.4 (36h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1914319
telemt_connections_bad_total 100009
telemt_handshake_timeouts_total 60289
telemt_upstream_connect_attempt_total 472281
telemt_upstream_connect_success_total 470631
telemt_upstream_connect_fail_total 1650
telemt_upstream_connect_attempts_per_request{bucket="1"} 472281
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 391757
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35501
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43371
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1650
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 412
telemt_me_reconnect_attempts_total 131742
telemt_me_reconnect_success_total 21103
telemt_me_reader_eof_total 23540
telemt_me_idle_close_by_peer_total 23527
telemt_me_route_drop_no_conn_total 548307
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1222718
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5661
telemt_desync_full_logged_total 1954
telemt_desync_suppressed_total 3707
telemt_desync_frames_bucket_total{bucket="1_2"} 1063
telemt_desync_frames_bucket_total{bucket="3_10"} 2291
telemt_desync_frames_bucket_total{bucket="gt_10"} 2307
telemt_pool_swap_total 75
telemt_me_writer_removed_unexpected_total 22865
telemt_me_refill_failed_total 3451
telemt_me_writer_restored_same_endpoint_total 21085
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 6668
telemt_me_writer_removed_unexpected_minus_restored_total 1762
telemt_user_connections_total{user="hello"} 1665138
telemt_user_connections_current{user="hello"} 2726
telemt_user_octets_from_client{user="hello"} 27385905969 (25.51 GB)
telemt_user_octets_to_client{user="hello"} 653455811342 (608.58 GB)
telemt_user_msgs_from_client{user="hello"} 7472583
telemt_user_msgs_to_client{user="hello"} 31958899
telemt_user_unique_ips_current{user="hello"} 821
telemt_user_unique_ips_recent_window{user="hello"} 368
```

## koara.io

Не удалось получить метрики для этого сервера.

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 132893.8 (36h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1837210
telemt_connections_bad_total 86294
telemt_handshake_timeouts_total 32885
telemt_upstream_connect_attempt_total 93106
telemt_upstream_connect_success_total 90648
telemt_upstream_connect_fail_total 2458
telemt_upstream_connect_attempts_per_request{bucket="1"} 93106
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 74575
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15653
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 387
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2458
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 361
telemt_me_reconnect_attempts_total 40791
telemt_me_reconnect_success_total 19268
telemt_me_reader_eof_total 21119
telemt_me_idle_close_by_peer_total 21116
telemt_me_route_drop_no_conn_total 831362
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1524692
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6012
telemt_desync_full_logged_total 1856
telemt_desync_suppressed_total 4156
telemt_desync_frames_bucket_total{bucket="1_2"} 1369
telemt_desync_frames_bucket_total{bucket="3_10"} 2471
telemt_desync_frames_bucket_total{bucket="gt_10"} 2172
telemt_pool_swap_total 104
telemt_me_writer_removed_unexpected_total 20299
telemt_me_refill_failed_total 663
telemt_me_writer_restored_same_endpoint_total 19248
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 1031
telemt_user_connections_total{user="hello"} 1587833
telemt_user_connections_current{user="hello"} 2768
telemt_user_octets_from_client{user="hello"} 26198147670 (24.40 GB)
telemt_user_octets_to_client{user="hello"} 721502446346 (671.95 GB)
telemt_user_msgs_from_client{user="hello"} 744103
telemt_user_msgs_to_client{user="hello"} 5214294
telemt_user_unique_ips_current{user="hello"} 697
telemt_user_unique_ips_recent_window{user="hello"} 426
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 132865.7 (36h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1319699
telemt_connections_bad_total 118584
telemt_handshake_timeouts_total 14546
telemt_upstream_connect_attempt_total 49933
telemt_upstream_connect_success_total 49240
telemt_upstream_connect_fail_total 693
telemt_upstream_connect_attempts_per_request{bucket="1"} 49933
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30305
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18503
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 432
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 693
telemt_me_keepalive_timeout_total 31
telemt_me_reconnect_attempts_total 66282
telemt_me_reconnect_success_total 26154
telemt_me_reader_eof_total 28400
telemt_me_idle_close_by_peer_total 28397
telemt_me_route_drop_no_conn_total 447672
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1089264
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4705
telemt_desync_full_logged_total 1457
telemt_desync_suppressed_total 3248
telemt_desync_frames_bucket_total{bucket="1_2"} 1219
telemt_desync_frames_bucket_total{bucket="3_10"} 1816
telemt_desync_frames_bucket_total{bucket="gt_10"} 1670
telemt_pool_swap_total 69
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 27813
telemt_me_refill_failed_total 1248
telemt_me_writer_restored_same_endpoint_total 26146
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1659
telemt_user_connections_total{user="hello"} 1105597
telemt_user_connections_current{user="hello"} 2289
telemt_user_octets_from_client{user="hello"} 22029205256 (20.52 GB)
telemt_user_octets_to_client{user="hello"} 550210692072 (512.42 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 692
telemt_user_unique_ips_recent_window{user="hello"} 322
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 133026.9 (36h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1306354
telemt_connections_bad_total 134467
telemt_handshake_timeouts_total 11023
telemt_upstream_connect_attempt_total 26455
telemt_upstream_connect_success_total 26297
telemt_upstream_connect_fail_total 158
telemt_upstream_connect_attempts_per_request{bucket="1"} 26455
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12673
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13501
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 113
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 158
telemt_me_keepalive_timeout_total 279
telemt_me_reconnect_attempts_total 31005
telemt_me_reconnect_success_total 19702
telemt_me_reader_eof_total 21318
telemt_me_idle_close_by_peer_total 21315
telemt_me_route_drop_no_conn_total 861985
telemt_me_route_drop_channel_closed_total 98
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1272872
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2533
telemt_desync_full_logged_total 891
telemt_desync_suppressed_total 1642
telemt_desync_frames_bucket_total{bucket="1_2"} 551
telemt_desync_frames_bucket_total{bucket="3_10"} 980
telemt_desync_frames_bucket_total{bucket="gt_10"} 1002
telemt_pool_swap_total 120
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 20355
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 19688
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 298
telemt_me_writer_removed_unexpected_minus_restored_total 653
telemt_user_connections_total{user="hello"} 1081527
telemt_user_connections_current{user="hello"} 978
telemt_user_octets_from_client{user="hello"} 16774748592 (15.62 GB)
telemt_user_octets_to_client{user="hello"} 472279798208 (439.84 GB)
telemt_user_unique_ips_current{user="hello"} 320
telemt_user_unique_ips_recent_window{user="hello"} 138
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 80793.7 (22h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 755027
telemt_connections_bad_total 71723
telemt_handshake_timeouts_total 15971
telemt_upstream_connect_attempt_total 27078
telemt_upstream_connect_success_total 26789
telemt_upstream_connect_fail_total 289
telemt_upstream_connect_attempts_per_request{bucket="1"} 27078
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14270
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12418
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 101
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 289
telemt_me_keepalive_timeout_total 149
telemt_me_reconnect_attempts_total 34255
telemt_me_reconnect_success_total 22632
telemt_me_reader_eof_total 23898
telemt_me_idle_close_by_peer_total 23898
telemt_me_seq_mismatch_total 37
telemt_me_route_drop_no_conn_total 217243
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 568409
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 41
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2328
telemt_desync_full_logged_total 801
telemt_desync_suppressed_total 1527
telemt_desync_frames_bucket_total{bucket="1_2"} 391
telemt_desync_frames_bucket_total{bucket="3_10"} 984
telemt_desync_frames_bucket_total{bucket="gt_10"} 953
telemt_pool_swap_total 56
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 23241
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 22585
telemt_me_writer_restored_fallback_total 47
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 609
telemt_user_connections_total{user="hello"} 568083
telemt_user_connections_current{user="hello"} 1684
telemt_user_octets_from_client{user="hello"} 29200753089 (27.20 GB)
telemt_user_octets_to_client{user="hello"} 412358488754 (384.04 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 500
telemt_user_unique_ips_recent_window{user="hello"} 211
```