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

# Server Metrics 2026-03-17 21:47:58 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 97361.2 (27h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1192121
telemt_connections_bad_total 8645
telemt_handshake_timeouts_total 31563
telemt_upstream_connect_attempt_total 22105
telemt_upstream_connect_success_total 21614
telemt_upstream_connect_fail_total 491
telemt_upstream_connect_attempts_per_request{bucket="1"} 22105
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11160
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10246
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 491
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 31564
telemt_me_reconnect_success_total 14434
telemt_me_reader_eof_total 15691
telemt_me_idle_close_by_peer_total 15690
telemt_me_route_drop_no_conn_total 531632
telemt_me_route_drop_channel_closed_total 155
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1093335
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7231
telemt_desync_full_logged_total 2084
telemt_desync_suppressed_total 5147
telemt_desync_frames_bucket_total{bucket="1_2"} 1936
telemt_desync_frames_bucket_total{bucket="3_10"} 2739
telemt_desync_frames_bucket_total{bucket="gt_10"} 2556
telemt_pool_swap_total 77
telemt_me_writer_removed_unexpected_total 15183
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 14412
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 749
telemt_user_connections_total{user="hello"} 1087567
telemt_user_connections_current{user="hello"} 624
telemt_user_octets_from_client{user="hello"} 19541062263 (18.20 GB)
telemt_user_octets_to_client{user="hello"} 386671681779 (360.12 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 235
telemt_user_unique_ips_recent_window{user="hello"} 72
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 97612.7 (27h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1250496
telemt_connections_bad_total 59663
telemt_handshake_timeouts_total 44471
telemt_upstream_connect_attempt_total 457572
telemt_upstream_connect_success_total 456677
telemt_upstream_connect_fail_total 895
telemt_upstream_connect_attempts_per_request{bucket="1"} 457572
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 382818
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30566
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43291
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 895
telemt_me_keepalive_timeout_total 342
telemt_me_reconnect_attempts_total 57946
telemt_me_reconnect_success_total 14792
telemt_me_reader_eof_total 16774
telemt_me_idle_close_by_peer_total 16774
telemt_me_route_drop_no_conn_total 319925
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 644982
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2876
telemt_desync_full_logged_total 921
telemt_desync_suppressed_total 1955
telemt_desync_frames_bucket_total{bucket="1_2"} 547
telemt_desync_frames_bucket_total{bucket="3_10"} 1182
telemt_desync_frames_bucket_total{bucket="gt_10"} 1147
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 16324
telemt_me_refill_failed_total 1344
telemt_me_writer_restored_same_endpoint_total 14776
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 1532
telemt_user_connections_total{user="hello"} 1081412
telemt_user_connections_current{user="hello"} 1084
telemt_user_octets_from_client{user="hello"} 14901017570 (13.88 GB)
telemt_user_octets_to_client{user="hello"} 362846137550 (337.93 GB)
telemt_user_msgs_from_client{user="hello"} 7417237
telemt_user_msgs_to_client{user="hello"} 31692884
telemt_user_unique_ips_current{user="hello"} 341
telemt_user_unique_ips_recent_window{user="hello"} 95
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 97388.6 (27h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 710125
telemt_connections_bad_total 42278
telemt_handshake_timeouts_total 22696
telemt_upstream_connect_attempt_total 23199
telemt_upstream_connect_success_total 23062
telemt_upstream_connect_fail_total 137
telemt_upstream_connect_attempts_per_request{bucket="1"} 23199
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10558
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12410
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 137
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 38806
telemt_me_reconnect_success_total 18129
telemt_me_reader_eof_total 19782
telemt_me_idle_close_by_peer_total 19775
telemt_me_route_drop_no_conn_total 297727
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 611380
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1972
telemt_desync_full_logged_total 601
telemt_desync_suppressed_total 1371
telemt_desync_frames_bucket_total{bucket="1_2"} 549
telemt_desync_frames_bucket_total{bucket="3_10"} 777
telemt_desync_frames_bucket_total{bucket="gt_10"} 646
telemt_pool_swap_total 74
telemt_me_writer_removed_unexpected_total 19023
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 18117
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 894
telemt_user_connections_total{user="hello"} 609650
telemt_user_connections_current{user="hello"} 935
telemt_user_octets_from_client{user="hello"} 30522780804 (28.43 GB)
telemt_user_octets_to_client{user="hello"} 266106385940 (247.83 GB)
telemt_user_unique_ips_current{user="hello"} 270
telemt_user_unique_ips_recent_window{user="hello"} 87
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 97448.1 (27h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1209566
telemt_connections_bad_total 38944
telemt_handshake_timeouts_total 21444
telemt_upstream_connect_attempt_total 82824
telemt_upstream_connect_success_total 82397
telemt_upstream_connect_fail_total 427
telemt_upstream_connect_attempts_per_request{bucket="1"} 82824
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 69898
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12126
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 29
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 344
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 427
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 315
telemt_me_reconnect_attempts_total 34457
telemt_me_reconnect_success_total 14137
telemt_me_reader_eof_total 15599
telemt_me_idle_close_by_peer_total 15597
telemt_me_route_drop_no_conn_total 501487
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 989252
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3522
telemt_desync_full_logged_total 1133
telemt_desync_suppressed_total 2389
telemt_desync_frames_bucket_total{bucket="1_2"} 866
telemt_desync_frames_bucket_total{bucket="3_10"} 1480
telemt_desync_frames_bucket_total{bucket="gt_10"} 1176
telemt_pool_swap_total 72
telemt_me_writer_removed_unexpected_total 15036
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 14128
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 899
telemt_user_connections_total{user="hello"} 1051750
telemt_user_connections_current{user="hello"} 898
telemt_user_octets_from_client{user="hello"} 16489668719 (15.36 GB)
telemt_user_octets_to_client{user="hello"} 452983228225 (421.87 GB)
telemt_user_msgs_from_client{user="hello"} 734453
telemt_user_msgs_to_client{user="hello"} 5166140
telemt_user_unique_ips_current{user="hello"} 273
telemt_user_unique_ips_recent_window{user="hello"} 79
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 97420.0 (27h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 764747
telemt_connections_bad_total 91511
telemt_handshake_timeouts_total 6382
telemt_upstream_connect_attempt_total 41780
telemt_upstream_connect_success_total 41221
telemt_upstream_connect_fail_total 559
telemt_upstream_connect_attempts_per_request{bucket="1"} 41780
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26416
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14406
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 399
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 559
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 53548
telemt_me_reconnect_success_total 19846
telemt_me_reader_eof_total 21615
telemt_me_idle_close_by_peer_total 21613
telemt_me_route_drop_no_conn_total 240224
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 610266
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2799
telemt_desync_full_logged_total 821
telemt_desync_suppressed_total 1978
telemt_desync_frames_bucket_total{bucket="1_2"} 892
telemt_desync_frames_bucket_total{bucket="3_10"} 1125
telemt_desync_frames_bucket_total{bucket="gt_10"} 782
telemt_pool_swap_total 48
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 21233
telemt_me_refill_failed_total 1048
telemt_me_writer_restored_same_endpoint_total 19838
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1387
telemt_user_connections_total{user="hello"} 626880
telemt_user_connections_current{user="hello"} 791
telemt_user_octets_from_client{user="hello"} 12076299528 (11.25 GB)
telemt_user_octets_to_client{user="hello"} 307664717380 (286.54 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 289
telemt_user_unique_ips_recent_window{user="hello"} 84
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 97580.9 (27h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1002320
telemt_connections_bad_total 76601
telemt_handshake_timeouts_total 9409
telemt_upstream_connect_attempt_total 19283
telemt_upstream_connect_success_total 19171
telemt_upstream_connect_fail_total 112
telemt_upstream_connect_attempts_per_request{bucket="1"} 19283
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9165
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9889
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 107
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 112
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 25564
telemt_me_reconnect_success_total 14286
telemt_me_reader_eof_total 15519
telemt_me_idle_close_by_peer_total 15517
telemt_me_route_drop_no_conn_total 686777
telemt_me_route_drop_channel_closed_total 86
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 990929
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2054
telemt_desync_full_logged_total 715
telemt_desync_suppressed_total 1339
telemt_desync_frames_bucket_total{bucket="1_2"} 459
telemt_desync_frames_bucket_total{bucket="3_10"} 777
telemt_desync_frames_bucket_total{bucket="gt_10"} 818
telemt_pool_swap_total 83
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 14874
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 14272
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 588
telemt_user_connections_total{user="hello"} 853958
telemt_user_connections_current{user="hello"} 468
telemt_user_octets_from_client{user="hello"} 13310595992 (12.40 GB)
telemt_user_octets_to_client{user="hello"} 364269350552 (339.25 GB)
telemt_user_unique_ips_current{user="hello"} 187
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 45348.2 (12h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 340145
telemt_connections_bad_total 43623
telemt_handshake_timeouts_total 10529
telemt_upstream_connect_attempt_total 18016
telemt_upstream_connect_success_total 17849
telemt_upstream_connect_fail_total 167
telemt_upstream_connect_attempts_per_request{bucket="1"} 18016
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9546
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8210
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 93
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 167
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 26995
telemt_me_reconnect_success_total 15402
telemt_me_reader_eof_total 16282
telemt_me_idle_close_by_peer_total 16282
telemt_me_seq_mismatch_total 20
telemt_me_route_drop_no_conn_total 83447
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 258954
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 857
telemt_desync_full_logged_total 249
telemt_desync_suppressed_total 608
telemt_desync_frames_bucket_total{bucket="1_2"} 206
telemt_desync_frames_bucket_total{bucket="3_10"} 333
telemt_desync_frames_bucket_total{bucket="gt_10"} 318
telemt_pool_swap_total 24
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 15944
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 15374
telemt_me_writer_restored_fallback_total 28
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 542
telemt_user_connections_total{user="hello"} 258894
telemt_user_connections_current{user="hello"} 475
telemt_user_octets_from_client{user="hello"} 21121945661 (19.67 GB)
telemt_user_octets_to_client{user="hello"} 215537349966 (200.73 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 160
telemt_user_unique_ips_recent_window{user="hello"} 46
```