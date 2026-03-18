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

# Server Metrics 2026-03-18 08:19:36 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 963.5 (0h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 45105
telemt_connections_bad_total 19
telemt_handshake_timeouts_total 419
telemt_upstream_connect_attempt_total 15918
telemt_upstream_connect_success_total 15586
telemt_upstream_connect_fail_total 330
telemt_upstream_connect_attempts_per_request{bucket="1"} 15916
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14657
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 725
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 204
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 330
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 317417
telemt_me_reconnect_success_total 400
telemt_me_reader_eof_total 279
telemt_me_idle_close_by_peer_total 279
telemt_me_route_drop_no_conn_total 12486
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 23629
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 27
telemt_me_endpoint_quarantine_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 118
telemt_desync_full_logged_total 35
telemt_desync_suppressed_total 83
telemt_desync_frames_bucket_total{bucket="1_2"} 33
telemt_desync_frames_bucket_total{bucket="3_10"} 48
telemt_desync_frames_bucket_total{bucket="gt_10"} 37
telemt_me_writer_removed_unexpected_total 308
telemt_me_refill_failed_total 9906
telemt_me_writer_restored_same_endpoint_total 397
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 14752
telemt_user_connections_total{user="hello"} 38738
telemt_user_connections_current{user="hello"} 1485
telemt_user_octets_from_client{user="hello"} 538639457 (513.69 MB)
telemt_user_octets_to_client{user="hello"} 5437557304 (5.06 GB)
telemt_user_msgs_from_client{user="hello"} 142420
telemt_user_msgs_to_client{user="hello"} 179907
telemt_user_unique_ips_current{user="hello"} 444
telemt_user_unique_ips_recent_window{user="hello"} 282
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 135510.6 (37h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2081828
telemt_connections_bad_total 111347
telemt_handshake_timeouts_total 63014
telemt_upstream_connect_attempt_total 472731
telemt_upstream_connect_success_total 471073
telemt_upstream_connect_fail_total 1658
telemt_upstream_connect_attempts_per_request{bucket="1"} 472731
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 391927
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35772
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43372
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1658
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 437
telemt_me_reconnect_attempts_total 136171
telemt_me_reconnect_success_total 21403
telemt_me_reader_eof_total 23968
telemt_me_idle_close_by_peer_total 23954
telemt_me_route_drop_no_conn_total 683647
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1370873
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6162
telemt_desync_full_logged_total 2142
telemt_desync_suppressed_total 4020
telemt_desync_frames_bucket_total{bucket="1_2"} 1168
telemt_desync_frames_bucket_total{bucket="3_10"} 2490
telemt_desync_frames_bucket_total{bucket="gt_10"} 2504
telemt_pool_swap_total 75
telemt_me_writer_removed_unexpected_total 23294
telemt_me_refill_failed_total 3580
telemt_me_writer_restored_same_endpoint_total 21385
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 6668
telemt_me_writer_removed_unexpected_minus_restored_total 1891
telemt_user_connections_total{user="hello"} 1813252
telemt_user_connections_current{user="hello"} 3201
telemt_user_octets_from_client{user="hello"} 30756414701 (28.64 GB)
telemt_user_octets_to_client{user="hello"} 714400898726 (665.34 GB)
telemt_user_msgs_from_client{user="hello"} 7472583
telemt_user_msgs_to_client{user="hello"} 31958899
telemt_user_unique_ips_current{user="hello"} 990
telemt_user_unique_ips_recent_window{user="hello"} 463
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 135286.5 (37h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1572689
telemt_connections_bad_total 95493
telemt_handshake_timeouts_total 36079
telemt_upstream_connect_attempt_total 30516
telemt_upstream_connect_success_total 30346
telemt_upstream_connect_fail_total 170
telemt_upstream_connect_attempts_per_request{bucket="1"} 30516
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14069
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16174
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 98
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 170
telemt_me_keepalive_timeout_total 179
telemt_me_reconnect_attempts_total 46398
telemt_me_reconnect_success_total 23517
telemt_me_reader_eof_total 25584
telemt_me_idle_close_by_peer_total 25576
telemt_me_route_drop_no_conn_total 681115
telemt_me_route_drop_channel_closed_total 24
telemt_me_route_drop_queue_full_total 15
telemt_me_route_drop_queue_full_profile_total{profile="high"} 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1157956
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4167
telemt_desync_full_logged_total 1412
telemt_desync_suppressed_total 2755
telemt_desync_frames_bucket_total{bucket="1_2"} 1130
telemt_desync_frames_bucket_total{bucket="3_10"} 1608
telemt_desync_frames_bucket_total{bucket="gt_10"} 1429
telemt_pool_swap_total 110
telemt_me_writer_removed_unexpected_total 24569
telemt_me_refill_failed_total 709
telemt_me_writer_restored_same_endpoint_total 23505
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 1052
telemt_user_connections_total{user="hello"} 1155912
telemt_user_connections_current{user="hello"} 2032
telemt_user_octets_from_client{user="hello"} 51259255308 (47.74 GB)
telemt_user_octets_to_client{user="hello"} 531717275400 (495.20 GB)
telemt_user_unique_ips_current{user="hello"} 613
telemt_user_unique_ips_recent_window{user="hello"} 284
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 135346.0 (37h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2036170
telemt_connections_bad_total 90637
telemt_handshake_timeouts_total 39414
telemt_upstream_connect_attempt_total 93672
telemt_upstream_connect_success_total 91206
telemt_upstream_connect_fail_total 2466
telemt_upstream_connect_attempts_per_request{bucket="1"} 93672
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 74900
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15885
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 388
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2466
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 364
telemt_me_reconnect_attempts_total 42129
telemt_me_reconnect_success_total 19663
telemt_me_reader_eof_total 21554
telemt_me_idle_close_by_peer_total 21551
telemt_me_route_drop_no_conn_total 1060764
telemt_me_route_drop_channel_closed_total 27
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1700588
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6567
telemt_desync_full_logged_total 2013
telemt_desync_suppressed_total 4554
telemt_desync_frames_bucket_total{bucket="1_2"} 1468
telemt_desync_frames_bucket_total{bucket="3_10"} 2709
telemt_desync_frames_bucket_total{bucket="gt_10"} 2390
telemt_pool_swap_total 104
telemt_me_writer_removed_unexpected_total 20733
telemt_me_refill_failed_total 692
telemt_me_writer_restored_same_endpoint_total 19643
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 1070
telemt_user_connections_total{user="hello"} 1763643
telemt_user_connections_current{user="hello"} 2834
telemt_user_octets_from_client{user="hello"} 28783224318 (26.81 GB)
telemt_user_octets_to_client{user="hello"} 754605822370 (702.78 GB)
telemt_user_msgs_from_client{user="hello"} 744103
telemt_user_msgs_to_client{user="hello"} 5214294
telemt_user_unique_ips_current{user="hello"} 782
telemt_user_unique_ips_recent_window{user="hello"} 358
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 135317.9 (37h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1477271
telemt_connections_bad_total 122043
telemt_handshake_timeouts_total 18093
telemt_upstream_connect_attempt_total 50188
telemt_upstream_connect_success_total 49481
telemt_upstream_connect_fail_total 707
telemt_upstream_connect_attempts_per_request{bucket="1"} 50188
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30447
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18602
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 432
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 707
telemt_me_keepalive_timeout_total 40
telemt_me_reconnect_attempts_total 70515
telemt_me_reconnect_success_total 26259
telemt_me_reader_eof_total 28628
telemt_me_idle_close_by_peer_total 28625
telemt_me_route_drop_no_conn_total 631573
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1229411
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5303
telemt_desync_full_logged_total 1642
telemt_desync_suppressed_total 3661
telemt_desync_frames_bucket_total{bucket="1_2"} 1330
telemt_desync_frames_bucket_total{bucket="3_10"} 2051
telemt_desync_frames_bucket_total{bucket="gt_10"} 1922
telemt_pool_swap_total 69
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 28047
telemt_me_refill_failed_total 1377
telemt_me_writer_restored_same_endpoint_total 26251
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1788
telemt_user_connections_total{user="hello"} 1245652
telemt_user_connections_current{user="hello"} 2470
telemt_user_octets_from_client{user="hello"} 24015218420 (22.37 GB)
telemt_user_octets_to_client{user="hello"} 593025616332 (552.30 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 781
telemt_user_unique_ips_recent_window{user="hello"} 382
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 135479.1 (37h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1367185
telemt_connections_bad_total 143752
telemt_handshake_timeouts_total 11231
telemt_upstream_connect_attempt_total 27050
telemt_upstream_connect_success_total 26891
telemt_upstream_connect_fail_total 159
telemt_upstream_connect_attempts_per_request{bucket="1"} 27050
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12999
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13769
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 113
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 159
telemt_me_keepalive_timeout_total 292
telemt_me_reconnect_attempts_total 31464
telemt_me_reconnect_success_total 20148
telemt_me_reader_eof_total 21787
telemt_me_idle_close_by_peer_total 21784
telemt_me_route_drop_no_conn_total 934710
telemt_me_route_drop_channel_closed_total 102
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1321886
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2596
telemt_desync_full_logged_total 911
telemt_desync_suppressed_total 1685
telemt_desync_frames_bucket_total{bucket="1_2"} 559
telemt_desync_frames_bucket_total{bucket="3_10"} 1003
telemt_desync_frames_bucket_total{bucket="gt_10"} 1034
telemt_pool_swap_total 121
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 20812
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 20134
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 298
telemt_me_writer_removed_unexpected_minus_restored_total 664
telemt_user_connections_total{user="hello"} 1130542
telemt_user_connections_current{user="hello"} 997
telemt_user_octets_from_client{user="hello"} 17111149524 (15.94 GB)
telemt_user_octets_to_client{user="hello"} 478623301212 (445.75 GB)
telemt_user_unique_ips_current{user="hello"} 306
telemt_user_unique_ips_recent_window{user="hello"} 125
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 83246.0 (23h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 847070
telemt_connections_bad_total 78677
telemt_handshake_timeouts_total 17917
telemt_upstream_connect_attempt_total 27548
telemt_upstream_connect_success_total 27230
telemt_upstream_connect_fail_total 318
telemt_upstream_connect_attempts_per_request{bucket="1"} 27548
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14495
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12626
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 318
telemt_me_keepalive_timeout_total 164
telemt_me_reconnect_attempts_total 38215
telemt_me_reconnect_success_total 22926
telemt_me_reader_eof_total 24284
telemt_me_idle_close_by_peer_total 24284
telemt_me_seq_mismatch_total 37
telemt_me_route_drop_no_conn_total 269073
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 645661
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 41
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2564
telemt_desync_full_logged_total 881
telemt_desync_suppressed_total 1683
telemt_desync_frames_bucket_total{bucket="1_2"} 443
telemt_desync_frames_bucket_total{bucket="3_10"} 1042
telemt_desync_frames_bucket_total{bucket="gt_10"} 1079
telemt_pool_swap_total 56
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 23658
telemt_me_refill_failed_total 473
telemt_me_writer_restored_same_endpoint_total 22879
telemt_me_writer_restored_fallback_total 47
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 732
telemt_user_connections_total{user="hello"} 645298
telemt_user_connections_current{user="hello"} 1920
telemt_user_octets_from_client{user="hello"} 30634331669 (28.53 GB)
telemt_user_octets_to_client{user="hello"} 452001862142 (420.96 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 567
telemt_user_unique_ips_recent_window{user="hello"} 265
```