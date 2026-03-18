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

# Server Metrics 2026-03-18 00:20:52 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 106535.8 (29h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1256884
telemt_connections_bad_total 9421
telemt_handshake_timeouts_total 32414
telemt_upstream_connect_attempt_total 23879
telemt_upstream_connect_success_total 23381
telemt_upstream_connect_fail_total 498
telemt_upstream_connect_attempts_per_request{bucket="1"} 23879
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12059
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11114
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 498
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 32901
telemt_me_reconnect_success_total 15766
telemt_me_reader_eof_total 17126
telemt_me_idle_close_by_peer_total 17125
telemt_me_route_drop_no_conn_total 554604
telemt_me_route_drop_channel_closed_total 158
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1155021
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7509
telemt_desync_full_logged_total 2198
telemt_desync_suppressed_total 5311
telemt_desync_frames_bucket_total{bucket="1_2"} 2008
telemt_desync_frames_bucket_total{bucket="3_10"} 2846
telemt_desync_frames_bucket_total{bucket="gt_10"} 2655
telemt_pool_swap_total 87
telemt_me_writer_removed_unexpected_total 16535
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 15744
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 769
telemt_user_connections_total{user="hello"} 1149236
telemt_user_connections_current{user="hello"} 523
telemt_user_octets_from_client{user="hello"} 22690485575 (21.13 GB)
telemt_user_octets_to_client{user="hello"} 413306714983 (384.92 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 225
telemt_user_unique_ips_recent_window{user="hello"} 57
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 106787.3 (29h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1334904
telemt_connections_bad_total 62019
telemt_handshake_timeouts_total 45871
telemt_upstream_connect_attempt_total 466423
telemt_upstream_connect_success_total 464878
telemt_upstream_connect_fail_total 1545
telemt_upstream_connect_attempts_per_request{bucket="1"} 466423
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 389126
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32402
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43348
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1545
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 343
telemt_me_reconnect_attempts_total 122059
telemt_me_reconnect_success_total 16631
telemt_me_reader_eof_total 18729
telemt_me_idle_close_by_peer_total 18719
telemt_me_route_drop_no_conn_total 345250
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 716540
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3269
telemt_desync_full_logged_total 1083
telemt_desync_suppressed_total 2186
telemt_desync_frames_bucket_total{bucket="1_2"} 636
telemt_desync_frames_bucket_total{bucket="3_10"} 1344
telemt_desync_frames_bucket_total{bucket="gt_10"} 1289
telemt_pool_swap_total 60
telemt_me_writer_removed_unexpected_total 18175
telemt_me_refill_failed_total 3289
telemt_me_writer_restored_same_endpoint_total 16613
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 6668
telemt_me_writer_removed_unexpected_minus_restored_total 1544
telemt_user_connections_total{user="hello"} 1158890
telemt_user_connections_current{user="hello"} 596
telemt_user_octets_from_client{user="hello"} 15805494397 (14.72 GB)
telemt_user_octets_to_client{user="hello"} 397138095710 (369.86 GB)
telemt_user_msgs_from_client{user="hello"} 7472583
telemt_user_msgs_to_client{user="hello"} 31958899
telemt_user_unique_ips_current{user="hello"} 232
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 106563.4 (29h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 789081
telemt_connections_bad_total 50981
telemt_handshake_timeouts_total 23884
telemt_upstream_connect_attempt_total 25042
telemt_upstream_connect_success_total 24898
telemt_upstream_connect_fail_total 144
telemt_upstream_connect_attempts_per_request{bucket="1"} 25042
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11421
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13382
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 144
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 40210
telemt_me_reconnect_success_total 19528
telemt_me_reader_eof_total 21278
telemt_me_idle_close_by_peer_total 21271
telemt_me_route_drop_no_conn_total 319651
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 670687
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2148
telemt_desync_full_logged_total 700
telemt_desync_suppressed_total 1448
telemt_desync_frames_bucket_total{bucket="1_2"} 611
telemt_desync_frames_bucket_total{bucket="3_10"} 831
telemt_desync_frames_bucket_total{bucket="gt_10"} 706
telemt_pool_swap_total 84
telemt_me_writer_removed_unexpected_total 20441
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 19516
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 913
telemt_user_connections_total{user="hello"} 668898
telemt_user_connections_current{user="hello"} 473
telemt_user_octets_from_client{user="hello"} 32068477336 (29.87 GB)
telemt_user_octets_to_client{user="hello"} 295731424232 (275.42 GB)
telemt_user_unique_ips_current{user="hello"} 191
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 106622.9 (29h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1276028
telemt_connections_bad_total 51928
telemt_handshake_timeouts_total 21780
telemt_upstream_connect_attempt_total 86201
telemt_upstream_connect_success_total 84784
telemt_upstream_connect_fail_total 1417
telemt_upstream_connect_attempts_per_request{bucket="1"} 86201
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 71311
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13083
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 30
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 360
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1417
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 315
telemt_me_reconnect_attempts_total 35804
telemt_me_reconnect_success_total 15444
telemt_me_reader_eof_total 17047
telemt_me_idle_close_by_peer_total 17045
telemt_me_route_drop_no_conn_total 522970
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1038952
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3916
telemt_desync_full_logged_total 1295
telemt_desync_suppressed_total 2621
telemt_desync_frames_bucket_total{bucket="1_2"} 954
telemt_desync_frames_bucket_total{bucket="3_10"} 1648
telemt_desync_frames_bucket_total{bucket="gt_10"} 1314
telemt_pool_swap_total 82
telemt_me_writer_removed_unexpected_total 16371
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 15434
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 927
telemt_user_connections_total{user="hello"} 1102078
telemt_user_connections_current{user="hello"} 542
telemt_user_octets_from_client{user="hello"} 17306193835 (16.12 GB)
telemt_user_octets_to_client{user="hello"} 511329991042 (476.21 GB)
telemt_user_msgs_from_client{user="hello"} 738254
telemt_user_msgs_to_client{user="hello"} 5205558
telemt_user_unique_ips_current{user="hello"} 176
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 106594.6 (29h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 833258
telemt_connections_bad_total 98453
telemt_handshake_timeouts_total 6731
telemt_upstream_connect_attempt_total 44078
telemt_upstream_connect_success_total 43469
telemt_upstream_connect_fail_total 609
telemt_upstream_connect_attempts_per_request{bucket="1"} 44078
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27493
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15566
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 410
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 609
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 56615
telemt_me_reconnect_success_total 21657
telemt_me_reader_eof_total 23545
telemt_me_idle_close_by_peer_total 23543
telemt_me_route_drop_no_conn_total 263993
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 669847
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3175
telemt_desync_full_logged_total 941
telemt_desync_suppressed_total 2234
telemt_desync_frames_bucket_total{bucket="1_2"} 1004
telemt_desync_frames_bucket_total{bucket="3_10"} 1270
telemt_desync_frames_bucket_total{bucket="gt_10"} 901
telemt_pool_swap_total 53
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 23105
telemt_me_refill_failed_total 1087
telemt_me_writer_restored_same_endpoint_total 21649
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1448
telemt_user_connections_total{user="hello"} 686455
telemt_user_connections_current{user="hello"} 486
telemt_user_octets_from_client{user="hello"} 13506796916 (12.58 GB)
telemt_user_octets_to_client{user="hello"} 346021234264 (322.26 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 198
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 106755.7 (29h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1070774
telemt_connections_bad_total 101197
telemt_handshake_timeouts_total 9583
telemt_upstream_connect_attempt_total 21210
telemt_upstream_connect_success_total 21092
telemt_upstream_connect_fail_total 118
telemt_upstream_connect_attempts_per_request{bucket="1"} 21210
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10070
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10905
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 107
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 118
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 27052
telemt_me_reconnect_success_total 15770
telemt_me_reader_eof_total 17115
telemt_me_idle_close_by_peer_total 17113
telemt_me_route_drop_no_conn_total 719188
telemt_me_route_drop_channel_closed_total 88
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1035601
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
telemt_pool_swap_total 93
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 16375
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 15756
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 605
telemt_user_connections_total{user="hello"} 891428
telemt_user_connections_current{user="hello"} 406
telemt_user_octets_from_client{user="hello"} 14330499636 (13.35 GB)
telemt_user_octets_to_client{user="hello"} 377618663268 (351.68 GB)
telemt_user_unique_ips_current{user="hello"} 158
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 54522.9 (15h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 388724
telemt_connections_bad_total 44672
telemt_handshake_timeouts_total 10815
telemt_upstream_connect_attempt_total 20532
telemt_upstream_connect_success_total 20346
telemt_upstream_connect_fail_total 186
telemt_upstream_connect_attempts_per_request{bucket="1"} 20532
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10865
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9385
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 186
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 29062
telemt_me_reconnect_success_total 17463
telemt_me_reader_eof_total 18474
telemt_me_idle_close_by_peer_total 18474
telemt_me_seq_mismatch_total 22
telemt_me_route_drop_no_conn_total 97329
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 287999
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1084
telemt_desync_full_logged_total 342
telemt_desync_suppressed_total 742
telemt_desync_frames_bucket_total{bucket="1_2"} 214
telemt_desync_frames_bucket_total{bucket="3_10"} 463
telemt_desync_frames_bucket_total{bucket="gt_10"} 407
telemt_pool_swap_total 34
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 18025
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 17433
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 562
telemt_user_connections_total{user="hello"} 287940
telemt_user_connections_current{user="hello"} 298
telemt_user_octets_from_client{user="hello"} 22089590381 (20.57 GB)
telemt_user_octets_to_client{user="hello"} 237138235414 (220.85 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 114
telemt_user_unique_ips_recent_window{user="hello"} 22
```