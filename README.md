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

# Server Metrics 2026-03-17 14:29:06 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 71029.9 (19h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 750451
telemt_connections_bad_total 5726
telemt_handshake_timeouts_total 22295
telemt_upstream_connect_attempt_total 17233
telemt_upstream_connect_success_total 16776
telemt_upstream_connect_fail_total 457
telemt_upstream_connect_attempts_per_request{bucket="1"} 17233
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8790
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7836
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 457
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 121
telemt_me_reconnect_attempts_total 21500
telemt_me_reconnect_success_total 10935
telemt_me_reader_eof_total 11819
telemt_me_idle_close_by_peer_total 11818
telemt_me_route_drop_no_conn_total 298480
telemt_me_route_drop_channel_closed_total 75
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 680210
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4669
telemt_desync_full_logged_total 1324
telemt_desync_suppressed_total 3345
telemt_desync_frames_bucket_total{bucket="1_2"} 1301
telemt_desync_frames_bucket_total{bucket="3_10"} 1909
telemt_desync_frames_bucket_total{bucket="gt_10"} 1459
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 11418
telemt_me_refill_failed_total 325
telemt_me_writer_restored_same_endpoint_total 10913
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 483
telemt_user_connections_total{user="hello"} 682086
telemt_user_connections_current{user="hello"} 912
telemt_user_octets_from_client{user="hello"} 11499438655 (10.71 GB)
telemt_user_octets_to_client{user="hello"} 229055286039 (213.32 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 320
telemt_user_unique_ips_recent_window{user="hello"} 145
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 71281.7 (19h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 474372
telemt_connections_bad_total 30448
telemt_handshake_timeouts_total 23741
telemt_upstream_connect_attempt_total 53397
telemt_upstream_connect_success_total 52957
telemt_upstream_connect_fail_total 440
telemt_upstream_connect_attempts_per_request{bucket="1"} 53397
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38160
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10819
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3978
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 440
telemt_me_keepalive_timeout_total 326
telemt_me_reconnect_attempts_total 33608
telemt_me_reconnect_success_total 13378
telemt_me_reader_eof_total 14572
telemt_me_idle_close_by_peer_total 14572
telemt_me_route_drop_no_conn_total 188479
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 361331
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1448
telemt_desync_full_logged_total 455
telemt_desync_suppressed_total 993
telemt_desync_frames_bucket_total{bucket="1_2"} 323
telemt_desync_frames_bucket_total{bucket="3_10"} 632
telemt_desync_frames_bucket_total{bucket="gt_10"} 493
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 14173
telemt_me_refill_failed_total 628
telemt_me_writer_restored_same_endpoint_total 13362
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 795
telemt_user_connections_total{user="hello"} 397217
telemt_user_connections_current{user="hello"} 661
telemt_user_octets_from_client{user="hello"} 4299349612 (4.00 GB)
telemt_user_octets_to_client{user="hello"} 122854187677 (114.42 GB)
telemt_user_msgs_from_client{user="hello"} 507297
telemt_user_msgs_to_client{user="hello"} 1619079
telemt_user_unique_ips_current{user="hello"} 170
telemt_user_unique_ips_recent_window{user="hello"} 190
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 71057.6 (19h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 246480
telemt_connections_bad_total 7815
telemt_handshake_timeouts_total 17011
telemt_upstream_connect_attempt_total 18745
telemt_upstream_connect_success_total 18650
telemt_upstream_connect_fail_total 95
telemt_upstream_connect_attempts_per_request{bucket="1"} 18745
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8338
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10232
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 95
telemt_me_keepalive_timeout_total 40
telemt_me_reconnect_attempts_total 23377
telemt_me_reconnect_success_total 15062
telemt_me_reader_eof_total 16191
telemt_me_idle_close_by_peer_total 16188
telemt_me_route_drop_no_conn_total 104861
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 208850
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 775
telemt_desync_full_logged_total 223
telemt_desync_suppressed_total 552
telemt_desync_frames_bucket_total{bucket="1_2"} 280
telemt_desync_frames_bucket_total{bucket="3_10"} 349
telemt_desync_frames_bucket_total{bucket="gt_10"} 146
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 15529
telemt_me_refill_failed_total 257
telemt_me_writer_restored_same_endpoint_total 15051
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 467
telemt_user_connections_total{user="hello"} 208719
telemt_user_connections_current{user="hello"} 325
telemt_user_octets_from_client{user="hello"} 16197022880 (15.08 GB)
telemt_user_octets_to_client{user="hello"} 53985247224 (50.28 GB)
telemt_user_unique_ips_current{user="hello"} 116
telemt_user_unique_ips_recent_window{user="hello"} 50
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 71116.8 (19h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 572833
telemt_connections_bad_total 8108
telemt_handshake_timeouts_total 13118
telemt_upstream_connect_attempt_total 16590
telemt_upstream_connect_success_total 16436
telemt_upstream_connect_fail_total 154
telemt_upstream_connect_attempts_per_request{bucket="1"} 16590
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8229
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8089
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 154
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 22587
telemt_me_reconnect_success_total 11837
telemt_me_reader_eof_total 12830
telemt_me_idle_close_by_peer_total 12830
telemt_me_route_drop_no_conn_total 208895
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 491489
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1663
telemt_desync_full_logged_total 572
telemt_desync_suppressed_total 1091
telemt_desync_frames_bucket_total{bucket="1_2"} 425
telemt_desync_frames_bucket_total{bucket="3_10"} 744
telemt_desync_frames_bucket_total{bucket="gt_10"} 494
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 12378
telemt_me_refill_failed_total 331
telemt_me_writer_restored_same_endpoint_total 11828
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 541
telemt_user_connections_total{user="hello"} 492318
telemt_user_connections_current{user="hello"} 728
telemt_user_octets_from_client{user="hello"} 6213238806 (5.79 GB)
telemt_user_octets_to_client{user="hello"} 159453245415 (148.50 GB)
telemt_user_msgs_from_client{user="hello"} 4070
telemt_user_msgs_to_client{user="hello"} 5224
telemt_user_unique_ips_current{user="hello"} 198
telemt_user_unique_ips_recent_window{user="hello"} 114
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 71088.7 (19h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 274861
telemt_connections_bad_total 56839
telemt_handshake_timeouts_total 3496
telemt_upstream_connect_attempt_total 20781
telemt_upstream_connect_success_total 20326
telemt_upstream_connect_fail_total 455
telemt_upstream_connect_attempts_per_request{bucket="1"} 20781
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9162
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10881
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 283
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 455
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 36872
telemt_me_reconnect_success_total 16372
telemt_me_reader_eof_total 17602
telemt_me_idle_close_by_peer_total 17600
telemt_me_route_drop_no_conn_total 77695
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 203096
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1106
telemt_desync_full_logged_total 233
telemt_desync_suppressed_total 873
telemt_desync_frames_bucket_total{bucket="1_2"} 552
telemt_desync_frames_bucket_total{bucket="3_10"} 425
telemt_desync_frames_bucket_total{bucket="gt_10"} 129
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 17287
telemt_me_refill_failed_total 636
telemt_me_writer_restored_same_endpoint_total 16364
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 915
telemt_user_connections_total{user="hello"} 203558
telemt_user_connections_current{user="hello"} 265
telemt_user_octets_from_client{user="hello"} 2609855331 (2.43 GB)
telemt_user_octets_to_client{user="hello"} 73741270891 (68.68 GB)
telemt_user_msgs_from_client{user="hello"} 1159
telemt_user_msgs_to_client{user="hello"} 2341
telemt_user_unique_ips_current{user="hello"} 83
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 71251.4 (19h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 661326
telemt_connections_bad_total 53974
telemt_handshake_timeouts_total 6562
telemt_upstream_connect_attempt_total 14240
telemt_upstream_connect_success_total 14164
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 14240
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6989
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7152
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 20856
telemt_me_reconnect_success_total 10575
telemt_me_reader_eof_total 11538
telemt_me_idle_close_by_peer_total 11538
telemt_me_route_drop_no_conn_total 464009
telemt_me_route_drop_channel_closed_total 36
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 662289
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 885
telemt_desync_full_logged_total 332
telemt_desync_suppressed_total 553
telemt_desync_frames_bucket_total{bucket="1_2"} 226
telemt_desync_frames_bucket_total{bucket="3_10"} 342
telemt_desync_frames_bucket_total{bucket="gt_10"} 317
telemt_pool_swap_total 61
telemt_me_writer_removed_unexpected_total 11059
telemt_me_refill_failed_total 319
telemt_me_writer_restored_same_endpoint_total 10561
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 484
telemt_user_connections_total{user="hello"} 566761
telemt_user_connections_current{user="hello"} 884
telemt_user_octets_from_client{user="hello"} 8462509864 (7.88 GB)
telemt_user_octets_to_client{user="hello"} 255695180456 (238.13 GB)
telemt_user_unique_ips_current{user="hello"} 327
telemt_user_unique_ips_recent_window{user="hello"} 121
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 19016.9 (5h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15350
telemt_connections_bad_total 67
telemt_handshake_timeouts_total 308
telemt_upstream_connect_attempt_total 10627
telemt_upstream_connect_success_total 10543
telemt_upstream_connect_fail_total 84
telemt_upstream_connect_attempts_per_request{bucket="1"} 10627
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5779
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4755
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 84
telemt_me_keepalive_timeout_total 13
telemt_me_reconnect_attempts_total 19688
telemt_me_reconnect_success_total 9391
telemt_me_reader_eof_total 9913
telemt_me_idle_close_by_peer_total 9913
telemt_me_seq_mismatch_total 10
telemt_me_route_drop_no_conn_total 5399
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 14586
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 9803
telemt_me_refill_failed_total 320
telemt_me_writer_restored_same_endpoint_total 9376
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 412
telemt_user_connections_total{user="hello"} 14687
telemt_user_connections_current{user="hello"} 73
telemt_user_octets_from_client{user="hello"} 434715289 (414.58 MB)
telemt_user_octets_to_client{user="hello"} 22757229302 (21.19 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 22
telemt_user_unique_ips_recent_window{user="hello"} 5
```