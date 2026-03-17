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

# Server Metrics 2026-03-17 16:41:59 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 79002.6 (21h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 922284
telemt_connections_bad_total 6484
telemt_handshake_timeouts_total 25914
telemt_upstream_connect_attempt_total 18788
telemt_upstream_connect_success_total 18316
telemt_upstream_connect_fail_total 472
telemt_upstream_connect_attempts_per_request{bucket="1"} 18788
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9562
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8595
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 159
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 472
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 169
telemt_me_reconnect_attempts_total 29172
telemt_me_reconnect_success_total 12058
telemt_me_reader_eof_total 13164
telemt_me_idle_close_by_peer_total 13163
telemt_me_route_drop_no_conn_total 428450
telemt_me_route_drop_channel_closed_total 111
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 847796
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5649
telemt_desync_full_logged_total 1581
telemt_desync_suppressed_total 4068
telemt_desync_frames_bucket_total{bucket="1_2"} 1606
telemt_desync_frames_bucket_total{bucket="3_10"} 2190
telemt_desync_frames_bucket_total{bucket="gt_10"} 1853
telemt_pool_swap_total 59
telemt_me_writer_removed_unexpected_total 12758
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 12036
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 700
telemt_user_connections_total{user="hello"} 842077
telemt_user_connections_current{user="hello"} 1200
telemt_user_octets_from_client{user="hello"} 13149587007 (12.25 GB)
telemt_user_octets_to_client{user="hello"} 281255869939 (261.94 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 384
telemt_user_unique_ips_recent_window{user="hello"} 166
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 79254.6 (22h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 662151
telemt_connections_bad_total 39227
telemt_handshake_timeouts_total 29263
telemt_upstream_connect_attempt_total 198759
telemt_upstream_connect_success_total 198122
telemt_upstream_connect_fail_total 630
telemt_upstream_connect_attempts_per_request{bucket="1"} 198752
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 163781
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17786
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16553
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 630
telemt_me_keepalive_timeout_total 332
telemt_me_reconnect_attempts_total 45692
telemt_me_reconnect_success_total 13551
telemt_me_reader_eof_total 15107
telemt_me_idle_close_by_peer_total 15107
telemt_me_route_drop_no_conn_total 204327
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 383948
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1502
telemt_desync_full_logged_total 471
telemt_desync_suppressed_total 1031
telemt_desync_frames_bucket_total{bucket="1_2"} 342
telemt_desync_frames_bucket_total{bucket="3_10"} 652
telemt_desync_frames_bucket_total{bucket="gt_10"} 508
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 14718
telemt_me_refill_failed_total 1000
telemt_me_writer_restored_same_endpoint_total 13535
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 1167
telemt_user_connections_total{user="hello"} 564454
telemt_user_connections_current{user="hello"} 2168
telemt_user_octets_from_client{user="hello"} 6668335722 (6.21 GB)
telemt_user_octets_to_client{user="hello"} 153296586873 (142.77 GB)
telemt_user_msgs_from_client{user="hello"} 2781048
telemt_user_msgs_to_client{user="hello"} 11062633
telemt_user_unique_ips_current{user="hello"} 428
telemt_user_unique_ips_recent_window{user="hello"} 302
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 79030.5 (21h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 331271
telemt_connections_bad_total 9121
telemt_handshake_timeouts_total 19718
telemt_upstream_connect_attempt_total 20094
telemt_upstream_connect_success_total 19985
telemt_upstream_connect_fail_total 109
telemt_upstream_connect_attempts_per_request{bucket="1"} 20094
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9057
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10844
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 79
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 109
telemt_me_keepalive_timeout_total 71
telemt_me_reconnect_attempts_total 36638
telemt_me_reconnect_success_total 15973
telemt_me_reader_eof_total 17477
telemt_me_idle_close_by_peer_total 17474
telemt_me_route_drop_no_conn_total 174194
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 287150
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 888
telemt_desync_full_logged_total 261
telemt_desync_suppressed_total 627
telemt_desync_frames_bucket_total{bucket="1_2"} 307
telemt_desync_frames_bucket_total{bucket="3_10"} 393
telemt_desync_frames_bucket_total{bucket="gt_10"} 188
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 16827
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 15961
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 854
telemt_user_connections_total{user="hello"} 285338
telemt_user_connections_current{user="hello"} 1587
telemt_user_octets_from_client{user="hello"} 21443419072 (19.97 GB)
telemt_user_octets_to_client{user="hello"} 79596102536 (74.13 GB)
telemt_user_unique_ips_current{user="hello"} 320
telemt_user_unique_ips_recent_window{user="hello"} 163
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 79089.3 (21h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 759179
telemt_connections_bad_total 12542
telemt_handshake_timeouts_total 15163
telemt_upstream_connect_attempt_total 79904
telemt_upstream_connect_success_total 79513
telemt_upstream_connect_fail_total 391
telemt_upstream_connect_attempts_per_request{bucket="1"} 79904
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 68483
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10688
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 28
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 314
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 391
telemt_me_keepalive_timeout_total 112
telemt_me_reconnect_attempts_total 32467
telemt_me_reconnect_success_total 12173
telemt_me_reader_eof_total 13457
telemt_me_idle_close_by_peer_total 13456
telemt_me_route_drop_no_conn_total 279185
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 596238
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1989
telemt_desync_full_logged_total 665
telemt_desync_suppressed_total 1324
telemt_desync_frames_bucket_total{bucket="1_2"} 485
telemt_desync_frames_bucket_total{bucket="3_10"} 894
telemt_desync_frames_bucket_total{bucket="gt_10"} 610
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 13019
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 12164
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 846
telemt_user_connections_total{user="hello"} 659379
telemt_user_connections_current{user="hello"} 1770
telemt_user_octets_from_client{user="hello"} 8065329207 (7.51 GB)
telemt_user_octets_to_client{user="hello"} 201677064889 (187.83 GB)
telemt_user_msgs_from_client{user="hello"} 734453
telemt_user_msgs_to_client{user="hello"} 5166140
telemt_user_unique_ips_current{user="hello"} 368
telemt_user_unique_ips_recent_window{user="hello"} 189
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 79061.3 (21h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 359885
telemt_connections_bad_total 65122
telemt_handshake_timeouts_total 4035
telemt_upstream_connect_attempt_total 38118
telemt_upstream_connect_success_total 37626
telemt_upstream_connect_fail_total 492
telemt_upstream_connect_attempts_per_request{bucket="1"} 38118
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24725
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12557
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 344
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 492
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 48461
telemt_me_reconnect_success_total 17170
telemt_me_reader_eof_total 18740
telemt_me_idle_close_by_peer_total 18738
telemt_me_route_drop_no_conn_total 97247
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 259105
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1252
telemt_desync_full_logged_total 277
telemt_desync_suppressed_total 975
telemt_desync_frames_bucket_total{bucket="1_2"} 587
telemt_desync_frames_bucket_total{bucket="3_10"} 490
telemt_desync_frames_bucket_total{bucket="gt_10"} 175
telemt_pool_swap_total 37
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 18430
telemt_me_refill_failed_total 973
telemt_me_writer_restored_same_endpoint_total 17162
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1260
telemt_user_connections_total{user="hello"} 275810
telemt_user_connections_current{user="hello"} 1789
telemt_user_octets_from_client{user="hello"} 3588426324 (3.34 GB)
telemt_user_octets_to_client{user="hello"} 108181490468 (100.75 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 354
telemt_user_unique_ips_recent_window{user="hello"} 197
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 79222.9 (22h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 788873
telemt_connections_bad_total 60209
telemt_handshake_timeouts_total 7374
telemt_upstream_connect_attempt_total 15963
telemt_upstream_connect_success_total 15876
telemt_upstream_connect_fail_total 87
telemt_upstream_connect_attempts_per_request{bucket="1"} 15963
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7637
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8192
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 87
telemt_me_keepalive_timeout_total 62
telemt_me_reconnect_attempts_total 23172
telemt_me_reconnect_success_total 11907
telemt_me_reader_eof_total 12963
telemt_me_idle_close_by_peer_total 12961
telemt_me_route_drop_no_conn_total 592536
telemt_me_route_drop_channel_closed_total 66
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 812903
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1324
telemt_desync_full_logged_total 466
telemt_desync_suppressed_total 858
telemt_desync_frames_bucket_total{bucket="1_2"} 303
telemt_desync_frames_bucket_total{bucket="3_10"} 520
telemt_desync_frames_bucket_total{bucket="gt_10"} 501
telemt_pool_swap_total 63
telemt_me_writer_removed_unexpected_total 12455
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 11893
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 548
telemt_user_connections_total{user="hello"} 681229
telemt_user_connections_current{user="hello"} 907
telemt_user_octets_from_client{user="hello"} 9826369884 (9.15 GB)
telemt_user_octets_to_client{user="hello"} 304444121488 (283.54 GB)
telemt_user_unique_ips_current{user="hello"} 324
telemt_user_unique_ips_recent_window{user="hello"} 140
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 26989.4 (7h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 44021
telemt_connections_bad_total 1084
telemt_handshake_timeouts_total 416
telemt_upstream_connect_attempt_total 13855
telemt_upstream_connect_success_total 13738
telemt_upstream_connect_fail_total 117
telemt_upstream_connect_attempts_per_request{bucket="1"} 13855
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7412
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6275
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 117
telemt_me_keepalive_timeout_total 51
telemt_me_reconnect_attempts_total 23790
telemt_me_reconnect_success_total 12217
telemt_me_reader_eof_total 12935
telemt_me_idle_close_by_peer_total 12935
telemt_me_seq_mismatch_total 14
telemt_me_route_drop_no_conn_total 14378
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 40342
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 37
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 27
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 15
telemt_desync_frames_bucket_total{bucket="gt_10"} 20
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 12720
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 12197
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 503
telemt_user_connections_total{user="hello"} 40357
telemt_user_connections_current{user="hello"} 1076
telemt_user_octets_from_client{user="hello"} 1983840545 (1.85 GB)
telemt_user_octets_to_client{user="hello"} 49193195622 (45.81 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 208
telemt_user_unique_ips_recent_window{user="hello"} 124
```