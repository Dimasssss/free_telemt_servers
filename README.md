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

# Server Metrics 2026-03-17 18:13:48 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 84511.9 (23h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1026339
telemt_connections_bad_total 6684
telemt_handshake_timeouts_total 28085
telemt_upstream_connect_attempt_total 19782
telemt_upstream_connect_success_total 19301
telemt_upstream_connect_fail_total 481
telemt_upstream_connect_attempts_per_request{bucket="1"} 19782
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10052
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9065
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 184
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 481
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 173
telemt_me_reconnect_attempts_total 29898
telemt_me_reconnect_success_total 12779
telemt_me_reader_eof_total 13920
telemt_me_idle_close_by_peer_total 13919
telemt_me_route_drop_no_conn_total 468568
telemt_me_route_drop_channel_closed_total 133
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 939972
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6228
telemt_desync_full_logged_total 1770
telemt_desync_suppressed_total 4458
telemt_desync_frames_bucket_total{bucket="1_2"} 1714
telemt_desync_frames_bucket_total{bucket="3_10"} 2397
telemt_desync_frames_bucket_total{bucket="gt_10"} 2117
telemt_pool_swap_total 63
telemt_me_writer_removed_unexpected_total 13497
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 12757
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 718
telemt_user_connections_total{user="hello"} 934213
telemt_user_connections_current{user="hello"} 1091
telemt_user_octets_from_client{user="hello"} 14241746035 (13.26 GB)
telemt_user_octets_to_client{user="hello"} 325247096711 (302.91 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 366
telemt_user_unique_ips_recent_window{user="hello"} 125
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 84764.1 (23h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 939606
telemt_connections_bad_total 53947
telemt_handshake_timeouts_total 32987
telemt_upstream_connect_attempt_total 401042
telemt_upstream_connect_success_total 400216
telemt_upstream_connect_fail_total 826
telemt_upstream_connect_attempts_per_request{bucket="1"} 401042
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 333757
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27660
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38797
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 826
telemt_me_keepalive_timeout_total 342
telemt_me_reconnect_attempts_total 54410
telemt_me_reconnect_success_total 13565
telemt_me_reader_eof_total 15393
telemt_me_idle_close_by_peer_total 15393
telemt_me_route_drop_no_conn_total 240109
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 424995
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1579
telemt_desync_full_logged_total 503
telemt_desync_suppressed_total 1076
telemt_desync_frames_bucket_total{bucket="1_2"} 360
telemt_desync_frames_bucket_total{bucket="3_10"} 689
telemt_desync_frames_bucket_total{bucket="gt_10"} 530
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 15004
telemt_me_refill_failed_total 1272
telemt_me_writer_restored_same_endpoint_total 13549
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 1439
telemt_user_connections_total{user="hello"} 807274
telemt_user_connections_current{user="hello"} 1552
telemt_user_octets_from_client{user="hello"} 10870751510 (10.12 GB)
telemt_user_octets_to_client{user="hello"} 214539055998 (199.81 GB)
telemt_user_msgs_from_client{user="hello"} 6521263
telemt_user_msgs_to_client{user="hello"} 27357262
telemt_user_unique_ips_current{user="hello"} 365
telemt_user_unique_ips_recent_window{user="hello"} 200
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 84539.5 (23h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 486969
telemt_connections_bad_total 18144
telemt_handshake_timeouts_total 21030
telemt_upstream_connect_attempt_total 20951
telemt_upstream_connect_success_total 20833
telemt_upstream_connect_fail_total 118
telemt_upstream_connect_attempts_per_request{bucket="1"} 20951
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9470
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11277
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 81
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 118
telemt_me_keepalive_timeout_total 103
telemt_me_reconnect_attempts_total 37224
telemt_me_reconnect_success_total 16556
telemt_me_reader_eof_total 18106
telemt_me_idle_close_by_peer_total 18099
telemt_me_route_drop_no_conn_total 225172
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 423728
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1199
telemt_desync_full_logged_total 359
telemt_desync_suppressed_total 840
telemt_desync_frames_bucket_total{bucket="1_2"} 387
telemt_desync_frames_bucket_total{bucket="3_10"} 508
telemt_desync_frames_bucket_total{bucket="gt_10"} 304
telemt_pool_swap_total 60
telemt_me_writer_removed_unexpected_total 17425
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 16544
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 869
telemt_user_connections_total{user="hello"} 421939
telemt_user_connections_current{user="hello"} 1313
telemt_user_octets_from_client{user="hello"} 26180169720 (24.38 GB)
telemt_user_octets_to_client{user="hello"} 153744181372 (143.19 GB)
telemt_user_unique_ips_current{user="hello"} 366
telemt_user_unique_ips_recent_window{user="hello"} 153
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 84598.8 (23h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 966612
telemt_connections_bad_total 23584
telemt_handshake_timeouts_total 18838
telemt_upstream_connect_attempt_total 80676
telemt_upstream_connect_success_total 80277
telemt_upstream_connect_fail_total 399
telemt_upstream_connect_attempts_per_request{bucket="1"} 80676
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 68896
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11018
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 29
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 334
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 399
telemt_me_keepalive_timeout_total 273
telemt_me_reconnect_attempts_total 32976
telemt_me_reconnect_success_total 12674
telemt_me_reader_eof_total 13996
telemt_me_idle_close_by_peer_total 13995
telemt_me_route_drop_no_conn_total 405759
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 775783
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2474
telemt_desync_full_logged_total 797
telemt_desync_suppressed_total 1677
telemt_desync_frames_bucket_total{bucket="1_2"} 603
telemt_desync_frames_bucket_total{bucket="3_10"} 1099
telemt_desync_frames_bucket_total{bucket="gt_10"} 772
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 13539
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 12665
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 865
telemt_user_connections_total{user="hello"} 838874
telemt_user_connections_current{user="hello"} 1624
telemt_user_octets_from_client{user="hello"} 10350692895 (9.64 GB)
telemt_user_octets_to_client{user="hello"} 292194058397 (272.13 GB)
telemt_user_msgs_from_client{user="hello"} 734453
telemt_user_msgs_to_client{user="hello"} 5166140
telemt_user_unique_ips_current{user="hello"} 432
telemt_user_unique_ips_recent_window{user="hello"} 163
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 84570.5 (23h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 539879
telemt_connections_bad_total 75116
telemt_handshake_timeouts_total 4969
telemt_upstream_connect_attempt_total 39144
telemt_upstream_connect_success_total 38633
telemt_upstream_connect_fail_total 511
telemt_upstream_connect_attempts_per_request{bucket="1"} 39144
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25275
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12991
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 367
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 511
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 50391
telemt_me_reconnect_success_total 17910
telemt_me_reader_eof_total 19541
telemt_me_idle_close_by_peer_total 19539
telemt_me_route_drop_no_conn_total 159962
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 411617
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1846
telemt_desync_full_logged_total 468
telemt_desync_suppressed_total 1378
telemt_desync_frames_bucket_total{bucket="1_2"} 722
telemt_desync_frames_bucket_total{bucket="3_10"} 723
telemt_desync_frames_bucket_total{bucket="gt_10"} 401
telemt_pool_swap_total 39
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 19226
telemt_me_refill_failed_total 1010
telemt_me_writer_restored_same_endpoint_total 17902
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1316
telemt_user_connections_total{user="hello"} 428296
telemt_user_connections_current{user="hello"} 1494
telemt_user_octets_from_client{user="hello"} 7710509664 (7.18 GB)
telemt_user_octets_to_client{user="hello"} 195017487260 (181.62 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 457
telemt_user_unique_ips_recent_window{user="hello"} 180
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 84732.7 (23h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 865278
telemt_connections_bad_total 60843
telemt_handshake_timeouts_total 8336
telemt_upstream_connect_attempt_total 16974
telemt_upstream_connect_success_total 16879
telemt_upstream_connect_fail_total 95
telemt_upstream_connect_attempts_per_request{bucket="1"} 16974
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8047
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8736
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 87
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 95
telemt_me_keepalive_timeout_total 122
telemt_me_reconnect_attempts_total 23877
telemt_me_reconnect_success_total 12604
telemt_me_reader_eof_total 13713
telemt_me_idle_close_by_peer_total 13711
telemt_me_route_drop_no_conn_total 636055
telemt_me_route_drop_channel_closed_total 80
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 885915
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1632
telemt_desync_full_logged_total 558
telemt_desync_suppressed_total 1074
telemt_desync_frames_bucket_total{bucket="1_2"} 404
telemt_desync_frames_bucket_total{bucket="3_10"} 632
telemt_desync_frames_bucket_total{bucket="gt_10"} 596
telemt_pool_swap_total 69
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 13172
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 12590
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 568
telemt_user_connections_total{user="hello"} 748972
telemt_user_connections_current{user="hello"} 760
telemt_user_octets_from_client{user="hello"} 11386057808 (10.60 GB)
telemt_user_octets_to_client{user="hello"} 326076611052 (303.68 GB)
telemt_user_unique_ips_current{user="hello"} 282
telemt_user_unique_ips_recent_window{user="hello"} 88
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 32498.7 (9h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 170485
telemt_connections_bad_total 19200
telemt_handshake_timeouts_total 5299
telemt_upstream_connect_attempt_total 14870
telemt_upstream_connect_success_total 14741
telemt_upstream_connect_fail_total 129
telemt_upstream_connect_attempts_per_request{bucket="1"} 14870
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7934
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6742
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 65
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 129
telemt_me_keepalive_timeout_total 51
telemt_me_reconnect_attempts_total 24491
telemt_me_reconnect_success_total 12912
telemt_me_reader_eof_total 13670
telemt_me_idle_close_by_peer_total 13670
telemt_me_seq_mismatch_total 16
telemt_me_route_drop_no_conn_total 41245
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 135490
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 306
telemt_desync_full_logged_total 88
telemt_desync_suppressed_total 218
telemt_desync_frames_bucket_total{bucket="1_2"} 93
telemt_desync_frames_bucket_total{bucket="3_10"} 116
telemt_desync_frames_bucket_total{bucket="gt_10"} 97
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 13426
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 12888
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 514
telemt_user_connections_total{user="hello"} 135442
telemt_user_connections_current{user="hello"} 980
telemt_user_octets_from_client{user="hello"} 11352568453 (10.57 GB)
telemt_user_octets_to_client{user="hello"} 126253138726 (117.58 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 253
telemt_user_unique_ips_recent_window{user="hello"} 102
```