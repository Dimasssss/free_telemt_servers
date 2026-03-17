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

# Server Metrics 2026-03-17 22:08:24 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 98587.9 (27h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1201115
telemt_connections_bad_total 8696
telemt_handshake_timeouts_total 31613
telemt_upstream_connect_attempt_total 22354
telemt_upstream_connect_success_total 21861
telemt_upstream_connect_fail_total 493
telemt_upstream_connect_attempts_per_request{bucket="1"} 22354
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11282
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10371
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 493
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 31768
telemt_me_reconnect_success_total 14636
telemt_me_reader_eof_total 15909
telemt_me_idle_close_by_peer_total 15908
telemt_me_route_drop_no_conn_total 535510
telemt_me_route_drop_channel_closed_total 155
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1102057
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7298
telemt_desync_full_logged_total 2109
telemt_desync_suppressed_total 5189
telemt_desync_frames_bucket_total{bucket="1_2"} 1950
telemt_desync_frames_bucket_total{bucket="3_10"} 2759
telemt_desync_frames_bucket_total{bucket="gt_10"} 2589
telemt_pool_swap_total 78
telemt_me_writer_removed_unexpected_total 15388
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 14614
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 752
telemt_user_connections_total{user="hello"} 1096288
telemt_user_connections_current{user="hello"} 579
telemt_user_octets_from_client{user="hello"} 20056277299 (18.68 GB)
telemt_user_octets_to_client{user="hello"} 391800039363 (364.89 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 230
telemt_user_unique_ips_recent_window{user="hello"} 60
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 98839.2 (27h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1265189
telemt_connections_bad_total 60128
telemt_handshake_timeouts_total 44762
telemt_upstream_connect_attempt_total 457761
telemt_upstream_connect_success_total 456865
telemt_upstream_connect_fail_total 896
telemt_upstream_connect_attempts_per_request{bucket="1"} 457761
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 382902
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30670
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43291
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 896
telemt_me_keepalive_timeout_total 342
telemt_me_reconnect_attempts_total 58091
telemt_me_reconnect_success_total 14935
telemt_me_reader_eof_total 16925
telemt_me_idle_close_by_peer_total 16925
telemt_me_route_drop_no_conn_total 325065
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 658668
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2962
telemt_desync_full_logged_total 956
telemt_desync_suppressed_total 2006
telemt_desync_frames_bucket_total{bucket="1_2"} 562
telemt_desync_frames_bucket_total{bucket="3_10"} 1213
telemt_desync_frames_bucket_total{bucket="gt_10"} 1187
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 16470
telemt_me_refill_failed_total 1344
telemt_me_writer_restored_same_endpoint_total 14919
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 1535
telemt_user_connections_total{user="hello"} 1095098
telemt_user_connections_current{user="hello"} 923
telemt_user_octets_from_client{user="hello"} 15089553822 (14.05 GB)
telemt_user_octets_to_client{user="hello"} 369044325034 (343.70 GB)
telemt_user_msgs_from_client{user="hello"} 7417237
telemt_user_msgs_to_client{user="hello"} 31692884
telemt_user_unique_ips_current{user="hello"} 313
telemt_user_unique_ips_recent_window{user="hello"} 78
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 98616.4 (27h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 723930
telemt_connections_bad_total 44528
telemt_handshake_timeouts_total 22745
telemt_upstream_connect_attempt_total 23408
telemt_upstream_connect_success_total 23270
telemt_upstream_connect_fail_total 138
telemt_upstream_connect_attempts_per_request{bucket="1"} 23408
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10649
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12527
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 138
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 38971
telemt_me_reconnect_success_total 18293
telemt_me_reader_eof_total 19955
telemt_me_idle_close_by_peer_total 19948
telemt_me_route_drop_no_conn_total 302334
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 622405
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2034
telemt_desync_full_logged_total 624
telemt_desync_suppressed_total 1410
telemt_desync_frames_bucket_total{bucket="1_2"} 566
telemt_desync_frames_bucket_total{bucket="3_10"} 798
telemt_desync_frames_bucket_total{bucket="gt_10"} 670
telemt_pool_swap_total 75
telemt_me_writer_removed_unexpected_total 19189
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 18281
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 896
telemt_user_connections_total{user="hello"} 620675
telemt_user_connections_current{user="hello"} 778
telemt_user_octets_from_client{user="hello"} 30775902348 (28.66 GB)
telemt_user_octets_to_client{user="hello"} 270699433576 (252.11 GB)
telemt_user_unique_ips_current{user="hello"} 256
telemt_user_unique_ips_recent_window{user="hello"} 50
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 98674.6 (27h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1221969
telemt_connections_bad_total 41530
telemt_handshake_timeouts_total 21561
telemt_upstream_connect_attempt_total 83046
telemt_upstream_connect_success_total 82615
telemt_upstream_connect_fail_total 431
telemt_upstream_connect_attempts_per_request{bucket="1"} 83046
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 69993
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12248
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 29
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 345
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 431
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 315
telemt_me_reconnect_attempts_total 34633
telemt_me_reconnect_success_total 14311
telemt_me_reader_eof_total 15782
telemt_me_idle_close_by_peer_total 15780
telemt_me_route_drop_no_conn_total 505572
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 998711
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3607
telemt_desync_full_logged_total 1171
telemt_desync_suppressed_total 2436
telemt_desync_frames_bucket_total{bucket="1_2"} 883
telemt_desync_frames_bucket_total{bucket="3_10"} 1510
telemt_desync_frames_bucket_total{bucket="gt_10"} 1214
telemt_pool_swap_total 73
telemt_me_writer_removed_unexpected_total 15213
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 14302
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 902
telemt_user_connections_total{user="hello"} 1061209
telemt_user_connections_current{user="hello"} 782
telemt_user_octets_from_client{user="hello"} 16666868295 (15.52 GB)
telemt_user_octets_to_client{user="hello"} 463314050781 (431.49 GB)
telemt_user_msgs_from_client{user="hello"} 734453
telemt_user_msgs_to_client{user="hello"} 5166140
telemt_user_unique_ips_current{user="hello"} 258
telemt_user_unique_ips_recent_window{user="hello"} 69
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 98646.5 (27h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 777183
telemt_connections_bad_total 91927
telemt_handshake_timeouts_total 6399
telemt_upstream_connect_attempt_total 41990
telemt_upstream_connect_success_total 41423
telemt_upstream_connect_fail_total 567
telemt_upstream_connect_attempts_per_request{bucket="1"} 41990
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26525
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14499
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 399
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 567
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 54956
telemt_me_reconnect_success_total 20005
telemt_me_reader_eof_total 21814
telemt_me_idle_close_by_peer_total 21812
telemt_me_route_drop_no_conn_total 245849
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 622026
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2843
telemt_desync_full_logged_total 837
telemt_desync_suppressed_total 2006
telemt_desync_frames_bucket_total{bucket="1_2"} 907
telemt_desync_frames_bucket_total{bucket="3_10"} 1140
telemt_desync_frames_bucket_total{bucket="gt_10"} 796
telemt_pool_swap_total 48
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 21435
telemt_me_refill_failed_total 1087
telemt_me_writer_restored_same_endpoint_total 19997
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1430
telemt_user_connections_total{user="hello"} 638636
telemt_user_connections_current{user="hello"} 713
telemt_user_octets_from_client{user="hello"} 12385580612 (11.53 GB)
telemt_user_octets_to_client{user="hello"} 315795243184 (294.11 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 276
telemt_user_unique_ips_recent_window{user="hello"} 65
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 98807.8 (27h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1012860
telemt_connections_bad_total 79911
telemt_handshake_timeouts_total 9480
telemt_upstream_connect_attempt_total 19505
telemt_upstream_connect_success_total 19393
telemt_upstream_connect_fail_total 112
telemt_upstream_connect_attempts_per_request{bucket="1"} 19505
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9265
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10011
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 107
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 112
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 25743
telemt_me_reconnect_success_total 14465
telemt_me_reader_eof_total 15711
telemt_me_idle_close_by_peer_total 15709
telemt_me_route_drop_no_conn_total 690024
telemt_me_route_drop_channel_closed_total 86
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 997228
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2072
telemt_desync_full_logged_total 722
telemt_desync_suppressed_total 1350
telemt_desync_frames_bucket_total{bucket="1_2"} 461
telemt_desync_frames_bucket_total{bucket="3_10"} 784
telemt_desync_frames_bucket_total{bucket="gt_10"} 827
telemt_pool_swap_total 84
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 15057
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 14451
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 592
telemt_user_connections_total{user="hello"} 860257
telemt_user_connections_current{user="hello"} 521
telemt_user_octets_from_client{user="hello"} 13344947572 (12.43 GB)
telemt_user_octets_to_client{user="hello"} 366633627728 (341.45 GB)
telemt_user_unique_ips_current{user="hello"} 188
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 46574.7 (12h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 349606
telemt_connections_bad_total 44357
telemt_handshake_timeouts_total 10546
telemt_upstream_connect_attempt_total 18277
telemt_upstream_connect_success_total 18107
telemt_upstream_connect_fail_total 170
telemt_upstream_connect_attempts_per_request{bucket="1"} 18277
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9674
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8340
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 93
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 170
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 27210
telemt_me_reconnect_success_total 15616
telemt_me_reader_eof_total 16504
telemt_me_idle_close_by_peer_total 16504
telemt_me_seq_mismatch_total 21
telemt_me_route_drop_no_conn_total 86364
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 265484
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 893
telemt_desync_full_logged_total 267
telemt_desync_suppressed_total 626
telemt_desync_frames_bucket_total{bucket="1_2"} 209
telemt_desync_frames_bucket_total{bucket="3_10"} 353
telemt_desync_frames_bucket_total{bucket="gt_10"} 331
telemt_pool_swap_total 25
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 16160
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 15587
telemt_me_writer_restored_fallback_total 29
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 544
telemt_user_connections_total{user="hello"} 265424
telemt_user_connections_current{user="hello"} 471
telemt_user_octets_from_client{user="hello"} 21238276297 (19.78 GB)
telemt_user_octets_to_client{user="hello"} 219974789030 (204.87 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 151
telemt_user_unique_ips_recent_window{user="hello"} 40
```