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

# Server Metrics 2026-03-17 14:54:43 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 72566.6 (20h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 782899
telemt_connections_bad_total 5885
telemt_handshake_timeouts_total 23248
telemt_upstream_connect_attempt_total 17466
telemt_upstream_connect_success_total 17006
telemt_upstream_connect_fail_total 460
telemt_upstream_connect_attempts_per_request{bucket="1"} 17466
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8927
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7929
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 460
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 121
telemt_me_reconnect_attempts_total 24397
telemt_me_reconnect_success_total 11071
telemt_me_reader_eof_total 12038
telemt_me_idle_close_by_peer_total 12037
telemt_me_route_drop_no_conn_total 314108
telemt_me_route_drop_channel_closed_total 78
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 710045
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4998
telemt_desync_full_logged_total 1384
telemt_desync_suppressed_total 3614
telemt_desync_frames_bucket_total{bucket="1_2"} 1449
telemt_desync_frames_bucket_total{bucket="3_10"} 1993
telemt_desync_frames_bucket_total{bucket="gt_10"} 1556
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 11640
telemt_me_refill_failed_total 411
telemt_me_writer_restored_same_endpoint_total 11049
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 569
telemt_user_connections_total{user="hello"} 711904
telemt_user_connections_current{user="hello"} 1037
telemt_user_octets_from_client{user="hello"} 11751114763 (10.94 GB)
telemt_user_octets_to_client{user="hello"} 237236536379 (220.94 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 340
telemt_user_unique_ips_recent_window{user="hello"} 145
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 72817.8 (20h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 500871
telemt_connections_bad_total 31663
telemt_handshake_timeouts_total 25370
telemt_upstream_connect_attempt_total 73102
telemt_upstream_connect_success_total 72603
telemt_upstream_connect_fail_total 499
telemt_upstream_connect_attempts_per_request{bucket="1"} 73102
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 55551
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11729
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5321
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 499
telemt_me_keepalive_timeout_total 329
telemt_me_reconnect_attempts_total 35914
telemt_me_reconnect_success_total 13412
telemt_me_reader_eof_total 14673
telemt_me_idle_close_by_peer_total 14673
telemt_me_route_drop_no_conn_total 190756
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 364579
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1467
telemt_desync_full_logged_total 461
telemt_desync_suppressed_total 1006
telemt_desync_frames_bucket_total{bucket="1_2"} 329
telemt_desync_frames_bucket_total{bucket="3_10"} 644
telemt_desync_frames_bucket_total{bucket="gt_10"} 494
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 14278
telemt_me_refill_failed_total 699
telemt_me_writer_restored_same_endpoint_total 13396
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 866
telemt_user_connections_total{user="hello"} 420034
telemt_user_connections_current{user="hello"} 759
telemt_user_octets_from_client{user="hello"} 4589813991 (4.27 GB)
telemt_user_octets_to_client{user="hello"} 125675840491 (117.04 GB)
telemt_user_msgs_from_client{user="hello"} 794365
telemt_user_msgs_to_client{user="hello"} 2652975
telemt_user_unique_ips_current{user="hello"} 215
telemt_user_unique_ips_recent_window{user="hello"} 109
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 72593.6 (20h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 259888
telemt_connections_bad_total 7830
telemt_handshake_timeouts_total 17197
telemt_upstream_connect_attempt_total 19092
telemt_upstream_connect_success_total 18995
telemt_upstream_connect_fail_total 97
telemt_upstream_connect_attempts_per_request{bucket="1"} 19092
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8526
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10389
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 97
telemt_me_keepalive_timeout_total 41
telemt_me_reconnect_attempts_total 26380
telemt_me_reconnect_success_total 15312
telemt_me_reader_eof_total 16524
telemt_me_idle_close_by_peer_total 16521
telemt_me_route_drop_no_conn_total 119839
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 221330
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 790
telemt_desync_full_logged_total 227
telemt_desync_suppressed_total 563
telemt_desync_frames_bucket_total{bucket="1_2"} 288
telemt_desync_frames_bucket_total{bucket="3_10"} 356
telemt_desync_frames_bucket_total{bucket="gt_10"} 146
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 15866
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 15301
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 554
telemt_user_connections_total{user="hello"} 221196
telemt_user_connections_current{user="hello"} 359
telemt_user_octets_from_client{user="hello"} 18040905836 (16.80 GB)
telemt_user_octets_to_client{user="hello"} 55030451948 (51.25 GB)
telemt_user_unique_ips_current{user="hello"} 123
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 72653.1 (20h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 600217
telemt_connections_bad_total 8554
telemt_handshake_timeouts_total 13364
telemt_upstream_connect_attempt_total 16747
telemt_upstream_connect_success_total 16589
telemt_upstream_connect_fail_total 158
telemt_upstream_connect_attempts_per_request{bucket="1"} 16747
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8324
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8146
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 110
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 158
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 25338
telemt_me_reconnect_success_total 11899
telemt_me_reader_eof_total 12970
telemt_me_idle_close_by_peer_total 12969
telemt_me_route_drop_no_conn_total 225129
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 515468
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1798
telemt_desync_full_logged_total 608
telemt_desync_suppressed_total 1190
telemt_desync_frames_bucket_total{bucket="1_2"} 453
telemt_desync_frames_bucket_total{bucket="3_10"} 801
telemt_desync_frames_bucket_total{bucket="gt_10"} 544
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 12526
telemt_me_refill_failed_total 415
telemt_me_writer_restored_same_endpoint_total 11890
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 627
telemt_user_connections_total{user="hello"} 516294
telemt_user_connections_current{user="hello"} 653
telemt_user_octets_from_client{user="hello"} 6411564746 (5.97 GB)
telemt_user_octets_to_client{user="hello"} 164528364723 (153.23 GB)
telemt_user_msgs_from_client{user="hello"} 4070
telemt_user_msgs_to_client{user="hello"} 5224
telemt_user_unique_ips_current{user="hello"} 179
telemt_user_unique_ips_recent_window{user="hello"} 85
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 72625.1 (20h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 284404
telemt_connections_bad_total 57152
telemt_handshake_timeouts_total 3610
telemt_upstream_connect_attempt_total 21132
telemt_upstream_connect_success_total 20662
telemt_upstream_connect_fail_total 470
telemt_upstream_connect_attempts_per_request{bucket="1"} 21132
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9297
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11078
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 287
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 470
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 39774
telemt_me_reconnect_success_total 16615
telemt_me_reader_eof_total 17930
telemt_me_idle_close_by_peer_total 17928
telemt_me_route_drop_no_conn_total 79975
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 211668
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1120
telemt_desync_full_logged_total 238
telemt_desync_suppressed_total 882
telemt_desync_frames_bucket_total{bucket="1_2"} 560
telemt_desync_frames_bucket_total{bucket="3_10"} 431
telemt_desync_frames_bucket_total{bucket="gt_10"} 129
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 17618
telemt_me_refill_failed_total 719
telemt_me_writer_restored_same_endpoint_total 16607
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1003
telemt_user_connections_total{user="hello"} 212165
telemt_user_connections_current{user="hello"} 278
telemt_user_octets_from_client{user="hello"} 2668360923 (2.49 GB)
telemt_user_octets_to_client{user="hello"} 75581311619 (70.39 GB)
telemt_user_msgs_from_client{user="hello"} 1159
telemt_user_msgs_to_client{user="hello"} 2341
telemt_user_unique_ips_current{user="hello"} 91
telemt_user_unique_ips_recent_window{user="hello"} 63
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 72786.9 (20h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 685630
telemt_connections_bad_total 54487
telemt_handshake_timeouts_total 6791
telemt_upstream_connect_attempt_total 14571
telemt_upstream_connect_success_total 14491
telemt_upstream_connect_fail_total 80
telemt_upstream_connect_attempts_per_request{bucket="1"} 14571
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7136
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7332
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 80
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 21136
telemt_me_reconnect_success_total 10846
telemt_me_reader_eof_total 11813
telemt_me_idle_close_by_peer_total 11813
telemt_me_route_drop_no_conn_total 490898
telemt_me_route_drop_channel_closed_total 36
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 692246
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 964
telemt_desync_full_logged_total 355
telemt_desync_suppressed_total 609
telemt_desync_frames_bucket_total{bucket="1_2"} 241
telemt_desync_frames_bucket_total{bucket="3_10"} 385
telemt_desync_frames_bucket_total{bucket="gt_10"} 338
telemt_pool_swap_total 61
telemt_me_writer_removed_unexpected_total 11334
telemt_me_refill_failed_total 319
telemt_me_writer_restored_same_endpoint_total 10832
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 488
telemt_user_connections_total{user="hello"} 589391
telemt_user_connections_current{user="hello"} 927
telemt_user_octets_from_client{user="hello"} 8686180392 (8.09 GB)
telemt_user_octets_to_client{user="hello"} 263548918620 (245.45 GB)
telemt_user_unique_ips_current{user="hello"} 329
telemt_user_unique_ips_recent_window{user="hello"} 135
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 20553.1 (5h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16210
telemt_connections_bad_total 71
telemt_handshake_timeouts_total 308
telemt_upstream_connect_attempt_total 11175
telemt_upstream_connect_success_total 11087
telemt_upstream_connect_fail_total 88
telemt_upstream_connect_attempts_per_request{bucket="1"} 11175
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6067
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5001
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 88
telemt_me_keepalive_timeout_total 13
telemt_me_reconnect_attempts_total 21438
telemt_me_reconnect_success_total 9886
telemt_me_reader_eof_total 10481
telemt_me_idle_close_by_peer_total 10481
telemt_me_seq_mismatch_total 10
telemt_me_route_drop_no_conn_total 5937
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 15421
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 10346
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 9871
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 460
telemt_user_connections_total{user="hello"} 15519
telemt_user_connections_current{user="hello"} 59
telemt_user_octets_from_client{user="hello"} 472167933 (450.29 MB)
telemt_user_octets_to_client{user="hello"} 23209772942 (21.62 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 16
telemt_user_unique_ips_recent_window{user="hello"} 3
```