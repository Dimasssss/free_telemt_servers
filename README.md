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

# Server Metrics 2026-03-18 04:25:18 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 121200.5 (33h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1383198
telemt_connections_bad_total 10523
telemt_handshake_timeouts_total 33990
telemt_upstream_connect_attempt_total 26651
telemt_upstream_connect_success_total 26139
telemt_upstream_connect_fail_total 512
telemt_upstream_connect_attempts_per_request{bucket="1"} 26651
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13387
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12544
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 512
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 34967
telemt_me_reconnect_success_total 17821
telemt_me_reader_eof_total 19332
telemt_me_idle_close_by_peer_total 19331
telemt_me_route_drop_no_conn_total 592211
telemt_me_route_drop_channel_closed_total 162
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1273789
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7965
telemt_desync_full_logged_total 2378
telemt_desync_suppressed_total 5587
telemt_desync_frames_bucket_total{bucket="1_2"} 2105
telemt_desync_frames_bucket_total{bucket="3_10"} 3049
telemt_desync_frames_bucket_total{bucket="gt_10"} 2811
telemt_pool_swap_total 103
telemt_me_writer_removed_unexpected_total 18620
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 17799
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 799
telemt_user_connections_total{user="hello"} 1267997
telemt_user_connections_current{user="hello"} 760
telemt_user_octets_from_client{user="hello"} 25577889075 (23.82 GB)
telemt_user_octets_to_client{user="hello"} 448381746259 (417.59 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 310
telemt_user_unique_ips_recent_window{user="hello"} 89
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 121452.3 (33h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1490860
telemt_connections_bad_total 71004
telemt_handshake_timeouts_total 48433
telemt_upstream_connect_attempt_total 469989
telemt_upstream_connect_success_total 468377
telemt_upstream_connect_fail_total 1612
telemt_upstream_connect_attempts_per_request{bucket="1"} 469989
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 390712
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34303
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43360
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1612
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 343
telemt_me_reconnect_attempts_total 126152
telemt_me_reconnect_success_total 19425
telemt_me_reader_eof_total 21683
telemt_me_idle_close_by_peer_total 21670
telemt_me_route_drop_no_conn_total 387060
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 855514
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3841
telemt_desync_full_logged_total 1339
telemt_desync_suppressed_total 2502
telemt_desync_frames_bucket_total{bucket="1_2"} 751
telemt_desync_frames_bucket_total{bucket="3_10"} 1576
telemt_desync_frames_bucket_total{bucket="gt_10"} 1514
telemt_pool_swap_total 69
telemt_me_writer_removed_unexpected_total 21044
telemt_me_refill_failed_total 3329
telemt_me_writer_restored_same_endpoint_total 19407
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 6668
telemt_me_writer_removed_unexpected_minus_restored_total 1619
telemt_user_connections_total{user="hello"} 1297839
telemt_user_connections_current{user="hello"} 1226
telemt_user_octets_from_client{user="hello"} 17576317041 (16.37 GB)
telemt_user_octets_to_client{user="hello"} 477294744786 (444.52 GB)
telemt_user_msgs_from_client{user="hello"} 7472583
telemt_user_msgs_to_client{user="hello"} 31958899
telemt_user_unique_ips_current{user="hello"} 437
telemt_user_unique_ips_recent_window{user="hello"} 151
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 121228.4 (33h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 930325
telemt_connections_bad_total 65222
telemt_handshake_timeouts_total 26849
telemt_upstream_connect_attempt_total 28011
telemt_upstream_connect_success_total 27851
telemt_upstream_connect_fail_total 160
telemt_upstream_connect_attempts_per_request{bucket="1"} 28011
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12771
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14978
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 97
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 160
telemt_me_keepalive_timeout_total 124
telemt_me_reconnect_attempts_total 42476
telemt_me_reconnect_success_total 21778
telemt_me_reader_eof_total 23676
telemt_me_idle_close_by_peer_total 23669
telemt_me_route_drop_no_conn_total 353126
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 770297
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2446
telemt_desync_full_logged_total 809
telemt_desync_suppressed_total 1637
telemt_desync_frames_bucket_total{bucket="1_2"} 699
telemt_desync_frames_bucket_total{bucket="3_10"} 944
telemt_desync_frames_bucket_total{bucket="gt_10"} 803
telemt_pool_swap_total 100
telemt_me_writer_removed_unexpected_total 22713
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 21766
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 935
telemt_user_connections_total{user="hello"} 768407
telemt_user_connections_current{user="hello"} 899
telemt_user_octets_from_client{user="hello"} 44903574680 (41.82 GB)
telemt_user_octets_to_client{user="hello"} 353761539436 (329.47 GB)
telemt_user_unique_ips_current{user="hello"} 275
telemt_user_unique_ips_recent_window{user="hello"} 118
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 121287.5 (33h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1388793
telemt_connections_bad_total 66756
telemt_handshake_timeouts_total 24256
telemt_upstream_connect_attempt_total 91036
telemt_upstream_connect_success_total 88599
telemt_upstream_connect_fail_total 2437
telemt_upstream_connect_attempts_per_request{bucket="1"} 91036
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 73498
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14692
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 376
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2437
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 320
telemt_me_reconnect_attempts_total 38213
telemt_me_reconnect_success_total 17804
telemt_me_reader_eof_total 19546
telemt_me_idle_close_by_peer_total 19543
telemt_me_route_drop_no_conn_total 566276
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1129484
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4207
telemt_desync_full_logged_total 1386
telemt_desync_suppressed_total 2821
telemt_desync_frames_bucket_total{bucket="1_2"} 1040
telemt_desync_frames_bucket_total{bucket="3_10"} 1759
telemt_desync_frames_bucket_total{bucket="gt_10"} 1408
telemt_pool_swap_total 95
telemt_me_writer_removed_unexpected_total 18769
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 17784
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 965
telemt_user_connections_total{user="hello"} 1192790
telemt_user_connections_current{user="hello"} 972
telemt_user_octets_from_client{user="hello"} 18579642082 (17.30 GB)
telemt_user_octets_to_client{user="hello"} 575124094650 (535.63 GB)
telemt_user_msgs_from_client{user="hello"} 744103
telemt_user_msgs_to_client{user="hello"} 5214294
telemt_user_unique_ips_current{user="hello"} 321
telemt_user_unique_ips_recent_window{user="hello"} 120
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 121259.5 (33h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 953060
telemt_connections_bad_total 102331
telemt_handshake_timeouts_total 8399
telemt_upstream_connect_attempt_total 47901
telemt_upstream_connect_success_total 47242
telemt_upstream_connect_fail_total 659
telemt_upstream_connect_attempts_per_request{bucket="1"} 47901
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29249
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17572
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 421
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 659
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 59698
telemt_me_reconnect_success_total 24732
telemt_me_reader_eof_total 26759
telemt_me_idle_close_by_peer_total 26756
telemt_me_route_drop_no_conn_total 303872
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 775416
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3467
telemt_desync_full_logged_total 1052
telemt_desync_suppressed_total 2415
telemt_desync_frames_bucket_total{bucket="1_2"} 1045
telemt_desync_frames_bucket_total{bucket="3_10"} 1362
telemt_desync_frames_bucket_total{bucket="gt_10"} 1060
telemt_pool_swap_total 63
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 26208
telemt_me_refill_failed_total 1087
telemt_me_writer_restored_same_endpoint_total 24724
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1476
telemt_user_connections_total{user="hello"} 791928
telemt_user_connections_current{user="hello"} 1036
telemt_user_octets_from_client{user="hello"} 15089183460 (14.05 GB)
telemt_user_octets_to_client{user="hello"} 399473298712 (372.04 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 371
telemt_user_unique_ips_recent_window{user="hello"} 135
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 121420.8 (33h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1171078
telemt_connections_bad_total 126870
telemt_handshake_timeouts_total 10326
telemt_upstream_connect_attempt_total 24170
telemt_upstream_connect_success_total 24031
telemt_upstream_connect_fail_total 139
telemt_upstream_connect_attempts_per_request{bucket="1"} 24170
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11525
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12387
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 139
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 29303
telemt_me_reconnect_success_total 18009
telemt_me_reader_eof_total 19521
telemt_me_idle_close_by_peer_total 19519
telemt_me_route_drop_no_conn_total 811021
telemt_me_route_drop_channel_closed_total 90
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1153156
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2147
telemt_desync_full_logged_total 755
telemt_desync_suppressed_total 1392
telemt_desync_frames_bucket_total{bucket="1_2"} 473
telemt_desync_frames_bucket_total{bucket="3_10"} 812
telemt_desync_frames_bucket_total{bucket="gt_10"} 862
telemt_pool_swap_total 109
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 18641
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 17995
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 298
telemt_me_writer_removed_unexpected_minus_restored_total 632
telemt_user_connections_total{user="hello"} 961846
telemt_user_connections_current{user="hello"} 586
telemt_user_octets_from_client{user="hello"} 15319212496 (14.27 GB)
telemt_user_octets_to_client{user="hello"} 424357162656 (395.21 GB)
telemt_user_unique_ips_current{user="hello"} 203
telemt_user_unique_ips_recent_window{user="hello"} 56
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 69187.7 (19h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 499044
telemt_connections_bad_total 52256
telemt_handshake_timeouts_total 12755
telemt_upstream_connect_attempt_total 24697
telemt_upstream_connect_success_total 24448
telemt_upstream_connect_fail_total 249
telemt_upstream_connect_attempts_per_request{bucket="1"} 24697
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13062
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11290
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 249
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 32478
telemt_me_reconnect_success_total 20867
telemt_me_reader_eof_total 22058
telemt_me_idle_close_by_peer_total 22058
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 119571
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 356059
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 37
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1554
telemt_desync_full_logged_total 508
telemt_desync_suppressed_total 1046
telemt_desync_frames_bucket_total{bucket="1_2"} 258
telemt_desync_frames_bucket_total{bucket="3_10"} 698
telemt_desync_frames_bucket_total{bucket="gt_10"} 598
telemt_pool_swap_total 47
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 21453
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 20824
telemt_me_writer_restored_fallback_total 43
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 586
telemt_user_connections_total{user="hello"} 355852
telemt_user_connections_current{user="hello"} 809
telemt_user_octets_from_client{user="hello"} 23435012389 (21.83 GB)
telemt_user_octets_to_client{user="hello"} 290410606838 (270.47 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 230
telemt_user_unique_ips_recent_window{user="hello"} 82
```