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

# Server Metrics 2026-03-17 20:36:27 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 93070.6 (25h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1151885
telemt_connections_bad_total 8631
telemt_handshake_timeouts_total 30448
telemt_upstream_connect_attempt_total 21279
telemt_upstream_connect_success_total 20789
telemt_upstream_connect_fail_total 490
telemt_upstream_connect_attempts_per_request{bucket="1"} 21279
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10769
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9813
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 207
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 490
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 30954
telemt_me_reconnect_success_total 13825
telemt_me_reader_eof_total 15033
telemt_me_idle_close_by_peer_total 15032
telemt_me_route_drop_no_conn_total 515605
telemt_me_route_drop_channel_closed_total 153
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1055714
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7028
telemt_desync_full_logged_total 2014
telemt_desync_suppressed_total 5014
telemt_desync_frames_bucket_total{bucket="1_2"} 1888
telemt_desync_frames_bucket_total{bucket="3_10"} 2673
telemt_desync_frames_bucket_total{bucket="gt_10"} 2467
telemt_pool_swap_total 72
telemt_me_writer_removed_unexpected_total 14565
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 13803
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 740
telemt_user_connections_total{user="hello"} 1049949
telemt_user_connections_current{user="hello"} 645
telemt_user_octets_from_client{user="hello"} 17384458367 (16.19 GB)
telemt_user_octets_to_client{user="hello"} 367714431859 (342.46 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 271
telemt_user_unique_ips_recent_window{user="hello"} 83
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 93322.2 (25h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1176132
telemt_connections_bad_total 59041
telemt_handshake_timeouts_total 42015
telemt_upstream_connect_attempt_total 456808
telemt_upstream_connect_success_total 455928
telemt_upstream_connect_fail_total 880
telemt_upstream_connect_attempts_per_request{bucket="1"} 456808
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 382477
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30160
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43289
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 880
telemt_me_keepalive_timeout_total 342
telemt_me_reconnect_attempts_total 57412
telemt_me_reconnect_success_total 14260
telemt_me_reader_eof_total 16207
telemt_me_idle_close_by_peer_total 16207
telemt_me_route_drop_no_conn_total 296137
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 576190
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2485
telemt_desync_full_logged_total 794
telemt_desync_suppressed_total 1691
telemt_desync_frames_bucket_total{bucket="1_2"} 486
telemt_desync_frames_bucket_total{bucket="3_10"} 1040
telemt_desync_frames_bucket_total{bucket="gt_10"} 959
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 15785
telemt_me_refill_failed_total 1344
telemt_me_writer_restored_same_endpoint_total 14244
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 1525
telemt_user_connections_total{user="hello"} 1012619
telemt_user_connections_current{user="hello"} 1383
telemt_user_octets_from_client{user="hello"} 14073090550 (13.11 GB)
telemt_user_octets_to_client{user="hello"} 328809189762 (306.23 GB)
telemt_user_msgs_from_client{user="hello"} 7417237
telemt_user_msgs_to_client{user="hello"} 31692884
telemt_user_unique_ips_current{user="hello"} 404
telemt_user_unique_ips_recent_window{user="hello"} 130
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 93098.2 (25h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 647433
telemt_connections_bad_total 36159
telemt_handshake_timeouts_total 22285
telemt_upstream_connect_attempt_total 22453
telemt_upstream_connect_success_total 22324
telemt_upstream_connect_fail_total 129
telemt_upstream_connect_attempts_per_request{bucket="1"} 22453
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10206
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12024
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 129
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 38283
telemt_me_reconnect_success_total 17609
telemt_me_reader_eof_total 19225
telemt_me_idle_close_by_peer_total 19218
telemt_me_route_drop_no_conn_total 278386
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 558654
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1744
telemt_desync_full_logged_total 520
telemt_desync_suppressed_total 1224
telemt_desync_frames_bucket_total{bucket="1_2"} 500
telemt_desync_frames_bucket_total{bucket="3_10"} 689
telemt_desync_frames_bucket_total{bucket="gt_10"} 555
telemt_pool_swap_total 69
telemt_me_writer_removed_unexpected_total 18494
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 17597
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 885
telemt_user_connections_total{user="hello"} 556929
telemt_user_connections_current{user="hello"} 1071
telemt_user_octets_from_client{user="hello"} 28349900908 (26.40 GB)
telemt_user_octets_to_client{user="hello"} 229870457448 (214.08 GB)
telemt_user_unique_ips_current{user="hello"} 302
telemt_user_unique_ips_recent_window{user="hello"} 121
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 93159.4 (25h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1149825
telemt_connections_bad_total 33772
telemt_handshake_timeouts_total 21120
telemt_upstream_connect_attempt_total 82019
telemt_upstream_connect_success_total 81607
telemt_upstream_connect_fail_total 412
telemt_upstream_connect_attempts_per_request{bucket="1"} 82019
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 69543
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11696
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 29
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 339
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 412
telemt_me_keepalive_timeout_total 273
telemt_me_reconnect_attempts_total 33877
telemt_me_reconnect_success_total 13566
telemt_me_reader_eof_total 14956
telemt_me_idle_close_by_peer_total 14955
telemt_me_route_drop_no_conn_total 480804
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 936748
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3195
telemt_desync_full_logged_total 1021
telemt_desync_suppressed_total 2174
telemt_desync_frames_bucket_total{bucket="1_2"} 780
telemt_desync_frames_bucket_total{bucket="3_10"} 1358
telemt_desync_frames_bucket_total{bucket="gt_10"} 1057
telemt_pool_swap_total 68
telemt_me_writer_removed_unexpected_total 14451
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 13557
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 885
telemt_user_connections_total{user="hello"} 999267
telemt_user_connections_current{user="hello"} 1299
telemt_user_octets_from_client{user="hello"} 14865334827 (13.84 GB)
telemt_user_octets_to_client{user="hello"} 406683037769 (378.75 GB)
telemt_user_msgs_from_client{user="hello"} 734453
telemt_user_msgs_to_client{user="hello"} 5166140
telemt_user_unique_ips_current{user="hello"} 372
telemt_user_unique_ips_recent_window{user="hello"} 116
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 93129.4 (25h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 705433
telemt_connections_bad_total 88623
telemt_handshake_timeouts_total 6031
telemt_upstream_connect_attempt_total 40804
telemt_upstream_connect_success_total 40257
telemt_upstream_connect_fail_total 547
telemt_upstream_connect_attempts_per_request{bucket="1"} 40804
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25995
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13870
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 392
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 547
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 51585
telemt_me_reconnect_success_total 19100
telemt_me_reader_eof_total 20804
telemt_me_idle_close_by_peer_total 20802
telemt_me_route_drop_no_conn_total 219451
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 556305
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2558
telemt_desync_full_logged_total 724
telemt_desync_suppressed_total 1834
telemt_desync_frames_bucket_total{bucket="1_2"} 861
telemt_desync_frames_bucket_total{bucket="3_10"} 1020
telemt_desync_frames_bucket_total{bucket="gt_10"} 677
telemt_pool_swap_total 46
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 20443
telemt_me_refill_failed_total 1010
telemt_me_writer_restored_same_endpoint_total 19092
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1343
telemt_user_connections_total{user="hello"} 572931
telemt_user_connections_current{user="hello"} 1205
telemt_user_octets_from_client{user="hello"} 11270526964 (10.50 GB)
telemt_user_octets_to_client{user="hello"} 273186201036 (254.42 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 353
telemt_user_unique_ips_recent_window{user="hello"} 130
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 93290.5 (25h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 960922
telemt_connections_bad_total 68389
telemt_handshake_timeouts_total 9154
telemt_upstream_connect_attempt_total 18454
telemt_upstream_connect_success_total 18350
telemt_upstream_connect_fail_total 104
telemt_upstream_connect_attempts_per_request{bucket="1"} 18454
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8722
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9512
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 106
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 104
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 24958
telemt_me_reconnect_success_total 13683
telemt_me_reader_eof_total 14868
telemt_me_idle_close_by_peer_total 14866
telemt_me_route_drop_no_conn_total 674063
telemt_me_route_drop_channel_closed_total 86
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 963404
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1920
telemt_desync_full_logged_total 673
telemt_desync_suppressed_total 1247
telemt_desync_frames_bucket_total{bucket="1_2"} 446
telemt_desync_frames_bucket_total{bucket="3_10"} 732
telemt_desync_frames_bucket_total{bucket="gt_10"} 742
telemt_pool_swap_total 78
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 14264
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 13669
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 581
telemt_user_connections_total{user="hello"} 826438
telemt_user_connections_current{user="hello"} 723
telemt_user_octets_from_client{user="hello"} 12830888756 (11.95 GB)
telemt_user_octets_to_client{user="hello"} 357346862220 (332.81 GB)
telemt_user_unique_ips_current{user="hello"} 240
telemt_user_unique_ips_recent_window{user="hello"} 77
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 41057.6 (11h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 291156
telemt_connections_bad_total 38511
telemt_handshake_timeouts_total 8226
telemt_upstream_connect_attempt_total 17103
telemt_upstream_connect_success_total 16943
telemt_upstream_connect_fail_total 160
telemt_upstream_connect_attempts_per_request{bucket="1"} 17103
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9082
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7770
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 160
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 26305
telemt_me_reconnect_success_total 14714
telemt_me_reader_eof_total 15550
telemt_me_idle_close_by_peer_total 15550
telemt_me_seq_mismatch_total 20
telemt_me_route_drop_no_conn_total 71293
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 224446
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 669
telemt_desync_full_logged_total 183
telemt_desync_suppressed_total 486
telemt_desync_frames_bucket_total{bucket="1_2"} 177
telemt_desync_frames_bucket_total{bucket="3_10"} 255
telemt_desync_frames_bucket_total{bucket="gt_10"} 237
telemt_pool_swap_total 19
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 15251
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 14686
telemt_me_writer_restored_fallback_total 28
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 537
telemt_user_connections_total{user="hello"} 224393
telemt_user_connections_current{user="hello"} 727
telemt_user_octets_from_client{user="hello"} 20375231021 (18.98 GB)
telemt_user_octets_to_client{user="hello"} 184712386514 (172.03 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 217
telemt_user_unique_ips_recent_window{user="hello"} 70
```