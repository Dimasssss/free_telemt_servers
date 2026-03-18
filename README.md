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

# Server Metrics 2026-03-18 02:18:00 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 113563.3 (31h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1314732
telemt_connections_bad_total 9741
telemt_handshake_timeouts_total 32949
telemt_upstream_connect_attempt_total 25278
telemt_upstream_connect_success_total 24773
telemt_upstream_connect_fail_total 504
telemt_upstream_connect_attempts_per_request{bucket="1"} 25277
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12707
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11858
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 504
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 33946
telemt_me_reconnect_success_total 16805
telemt_me_reader_eof_total 18247
telemt_me_idle_close_by_peer_total 18246
telemt_me_route_drop_no_conn_total 569005
telemt_me_route_drop_channel_closed_total 158
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1210429
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7697
telemt_desync_full_logged_total 2280
telemt_desync_suppressed_total 5417
telemt_desync_frames_bucket_total{bucket="1_2"} 2061
telemt_desync_frames_bucket_total{bucket="3_10"} 2926
telemt_desync_frames_bucket_total{bucket="gt_10"} 2710
telemt_pool_swap_total 95
telemt_me_writer_removed_unexpected_total 17591
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 16783
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 786
telemt_user_connections_total{user="hello"} 1204641
telemt_user_connections_current{user="hello"} 510
telemt_user_octets_from_client{user="hello"} 24297175887 (22.63 GB)
telemt_user_octets_to_client{user="hello"} 424352576259 (395.21 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 244
telemt_user_unique_ips_recent_window{user="hello"} 68
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 113814.5 (31h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1387424
telemt_connections_bad_total 64218
telemt_handshake_timeouts_total 47036
telemt_upstream_connect_attempt_total 468092
telemt_upstream_connect_success_total 466516
telemt_upstream_connect_fail_total 1576
telemt_upstream_connect_attempts_per_request{bucket="1"} 468092
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 389870
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33289
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43355
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1576
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 343
telemt_me_reconnect_attempts_total 123357
telemt_me_reconnect_success_total 17917
telemt_me_reader_eof_total 20089
telemt_me_idle_close_by_peer_total 20076
telemt_me_route_drop_no_conn_total 357590
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 763709
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3571
telemt_desync_full_logged_total 1216
telemt_desync_suppressed_total 2355
telemt_desync_frames_bucket_total{bucket="1_2"} 699
telemt_desync_frames_bucket_total{bucket="3_10"} 1488
telemt_desync_frames_bucket_total{bucket="gt_10"} 1384
telemt_pool_swap_total 66
telemt_me_writer_removed_unexpected_total 19482
telemt_me_refill_failed_total 3289
telemt_me_writer_restored_same_endpoint_total 17899
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 6668
telemt_me_writer_removed_unexpected_minus_restored_total 1565
telemt_user_connections_total{user="hello"} 1206060
telemt_user_connections_current{user="hello"} 692
telemt_user_octets_from_client{user="hello"} 16299319769 (15.18 GB)
telemt_user_octets_to_client{user="hello"} 423213957078 (394.15 GB)
telemt_user_msgs_from_client{user="hello"} 7472583
telemt_user_msgs_to_client{user="hello"} 31958899
telemt_user_unique_ips_current{user="hello"} 259
telemt_user_unique_ips_recent_window{user="hello"} 56
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 113590.6 (31h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 835173
telemt_connections_bad_total 58065
telemt_handshake_timeouts_total 24521
telemt_upstream_connect_attempt_total 26559
telemt_upstream_connect_success_total 26407
telemt_upstream_connect_fail_total 152
telemt_upstream_connect_attempts_per_request{bucket="1"} 26559
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12109
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14199
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 94
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 152
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 41378
telemt_me_reconnect_success_total 20686
telemt_me_reader_eof_total 22514
telemt_me_idle_close_by_peer_total 22507
telemt_me_route_drop_no_conn_total 331257
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 703944
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2219
telemt_desync_full_logged_total 720
telemt_desync_suppressed_total 1499
telemt_desync_frames_bucket_total{bucket="1_2"} 632
telemt_desync_frames_bucket_total{bucket="3_10"} 861
telemt_desync_frames_bucket_total{bucket="gt_10"} 726
telemt_pool_swap_total 92
telemt_me_writer_removed_unexpected_total 21610
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 20674
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 924
telemt_user_connections_total{user="hello"} 702062
telemt_user_connections_current{user="hello"} 436
telemt_user_octets_from_client{user="hello"} 43854811432 (40.84 GB)
telemt_user_octets_to_client{user="hello"} 312034791972 (290.61 GB)
telemt_user_unique_ips_current{user="hello"} 184
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 113650.0 (31h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1314864
telemt_connections_bad_total 58664
telemt_handshake_timeouts_total 22083
telemt_upstream_connect_attempt_total 89348
telemt_upstream_connect_success_total 86935
telemt_upstream_connect_fail_total 2413
telemt_upstream_connect_attempts_per_request{bucket="1"} 89348
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 72668
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13870
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 30
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 367
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2413
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 320
telemt_me_reconnect_attempts_total 36887
telemt_me_reconnect_success_total 16490
telemt_me_reader_eof_total 18172
telemt_me_idle_close_by_peer_total 18170
telemt_me_route_drop_no_conn_total 540906
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1068221
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3976
telemt_desync_full_logged_total 1315
telemt_desync_suppressed_total 2661
telemt_desync_frames_bucket_total{bucket="1_2"} 971
telemt_desync_frames_bucket_total{bucket="3_10"} 1671
telemt_desync_frames_bucket_total{bucket="gt_10"} 1334
telemt_pool_swap_total 90
telemt_me_writer_removed_unexpected_total 17440
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 16479
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 950
telemt_user_connections_total{user="hello"} 1131600
telemt_user_connections_current{user="hello"} 533
telemt_user_octets_from_client{user="hello"} 17743140786 (16.52 GB)
telemt_user_octets_to_client{user="hello"} 534507570530 (497.80 GB)
telemt_user_msgs_from_client{user="hello"} 744103
telemt_user_msgs_to_client{user="hello"} 5214294
telemt_user_unique_ips_current{user="hello"} 189
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 113622.1 (31h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 872918
telemt_connections_bad_total 100421
telemt_handshake_timeouts_total 6875
telemt_upstream_connect_attempt_total 46108
telemt_upstream_connect_success_total 45479
telemt_upstream_connect_fail_total 629
telemt_upstream_connect_attempts_per_request{bucket="1"} 46108
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28422
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16641
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 416
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 629
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 58279
telemt_me_reconnect_success_total 23317
telemt_me_reader_eof_total 25284
telemt_me_idle_close_by_peer_total 25281
telemt_me_route_drop_no_conn_total 278995
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 706160
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3229
telemt_desync_full_logged_total 967
telemt_desync_suppressed_total 2262
telemt_desync_frames_bucket_total{bucket="1_2"} 1008
telemt_desync_frames_bucket_total{bucket="3_10"} 1288
telemt_desync_frames_bucket_total{bucket="gt_10"} 933
telemt_pool_swap_total 58
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 24783
telemt_me_refill_failed_total 1087
telemt_me_writer_restored_same_endpoint_total 23309
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1466
telemt_user_connections_total{user="hello"} 722720
telemt_user_connections_current{user="hello"} 484
telemt_user_octets_from_client{user="hello"} 13910696404 (12.96 GB)
telemt_user_octets_to_client{user="hello"} 357535026808 (332.98 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 206
telemt_user_unique_ips_recent_window{user="hello"} 55
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 113782.8 (31h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1121837
telemt_connections_bad_total 119956
telemt_handshake_timeouts_total 9860
telemt_upstream_connect_attempt_total 22672
telemt_upstream_connect_success_total 22542
telemt_upstream_connect_fail_total 130
telemt_upstream_connect_attempts_per_request{bucket="1"} 22672
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10806
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11617
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 130
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 28158
telemt_me_reconnect_success_total 16869
telemt_me_reader_eof_total 18297
telemt_me_idle_close_by_peer_total 18295
telemt_me_route_drop_no_conn_total 773176
telemt_me_route_drop_channel_closed_total 89
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1096831
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2106
telemt_desync_full_logged_total 737
telemt_desync_suppressed_total 1369
telemt_desync_frames_bucket_total{bucket="1_2"} 461
telemt_desync_frames_bucket_total{bucket="3_10"} 802
telemt_desync_frames_bucket_total{bucket="gt_10"} 843
telemt_pool_swap_total 101
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 17489
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 16855
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 298
telemt_me_writer_removed_unexpected_minus_restored_total 620
telemt_user_connections_total{user="hello"} 921181
telemt_user_connections_current{user="hello"} 365
telemt_user_octets_from_client{user="hello"} 14914323712 (13.89 GB)
telemt_user_octets_to_client{user="hello"} 401153005204 (373.60 GB)
telemt_user_unique_ips_current{user="hello"} 143
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 61550.2 (17h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 425380
telemt_connections_bad_total 44723
telemt_handshake_timeouts_total 11160
telemt_upstream_connect_attempt_total 22768
telemt_upstream_connect_success_total 22548
telemt_upstream_connect_fail_total 220
telemt_upstream_connect_attempts_per_request{bucket="1"} 22768
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12086
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10366
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 220
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 30922
telemt_me_reconnect_success_total 19315
telemt_me_reader_eof_total 20422
telemt_me_idle_close_by_peer_total 20422
telemt_me_seq_mismatch_total 28
telemt_me_route_drop_no_conn_total 105104
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 308357
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 32
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1348
telemt_desync_full_logged_total 424
telemt_desync_suppressed_total 924
telemt_desync_frames_bucket_total{bucket="1_2"} 226
telemt_desync_frames_bucket_total{bucket="3_10"} 602
telemt_desync_frames_bucket_total{bucket="gt_10"} 520
telemt_pool_swap_total 40
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 19893
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 19277
telemt_me_writer_restored_fallback_total 38
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 578
telemt_user_connections_total{user="hello"} 308293
telemt_user_connections_current{user="hello"} 424
telemt_user_octets_from_client{user="hello"} 22590460065 (21.04 GB)
telemt_user_octets_to_client{user="hello"} 259446922962 (241.63 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 133
telemt_user_unique_ips_recent_window{user="hello"} 47
```