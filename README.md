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

# Server Metrics 2026-03-18 07:03:05 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 130667.9 (36h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1710492
telemt_connections_bad_total 11614
telemt_handshake_timeouts_total 37075
telemt_upstream_connect_attempt_total 28308
telemt_upstream_connect_success_total 27785
telemt_upstream_connect_fail_total 523
telemt_upstream_connect_attempts_per_request{bucket="1"} 28308
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14203
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13374
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 523
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 286
telemt_me_reconnect_attempts_total 36134
telemt_me_reconnect_success_total 18973
telemt_me_reader_eof_total 20559
telemt_me_idle_close_by_peer_total 20558
telemt_me_route_drop_no_conn_total 645792
telemt_me_route_drop_channel_closed_total 182
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1415981
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8525
telemt_desync_full_logged_total 2578
telemt_desync_suppressed_total 5947
telemt_desync_frames_bucket_total{bucket="1_2"} 2208
telemt_desync_frames_bucket_total{bucket="3_10"} 3293
telemt_desync_frames_bucket_total{bucket="gt_10"} 3024
telemt_pool_swap_total 111
telemt_me_writer_removed_unexpected_total 19796
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 18951
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 823
telemt_user_connections_total{user="hello"} 1410226
telemt_user_connections_current{user="hello"} 1288
telemt_user_octets_from_client{user="hello"} 32910180775 (30.65 GB)
telemt_user_octets_to_client{user="hello"} 504002855823 (469.39 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 432
telemt_user_unique_ips_recent_window{user="hello"} 198
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 130919.3 (36h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1802228
telemt_connections_bad_total 91789
telemt_handshake_timeouts_total 57657
telemt_upstream_connect_attempt_total 471913
telemt_upstream_connect_success_total 470268
telemt_upstream_connect_fail_total 1645
telemt_upstream_connect_attempts_per_request{bucket="1"} 471913
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 391627
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35272
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43367
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1645
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 411
telemt_me_reconnect_attempts_total 128748
telemt_me_reconnect_success_total 20829
telemt_me_reader_eof_total 23183
telemt_me_idle_close_by_peer_total 23170
telemt_me_route_drop_no_conn_total 495419
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1125404
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5170
telemt_desync_full_logged_total 1804
telemt_desync_suppressed_total 3366
telemt_desync_frames_bucket_total{bucket="1_2"} 974
telemt_desync_frames_bucket_total{bucket="3_10"} 2098
telemt_desync_frames_bucket_total{bucket="gt_10"} 2098
telemt_pool_swap_total 75
telemt_me_writer_removed_unexpected_total 22505
telemt_me_refill_failed_total 3366
telemt_me_writer_restored_same_endpoint_total 20811
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 6668
telemt_me_writer_removed_unexpected_minus_restored_total 1676
telemt_user_connections_total{user="hello"} 1567739
telemt_user_connections_current{user="hello"} 2363
telemt_user_octets_from_client{user="hello"} 23945628713 (22.30 GB)
telemt_user_octets_to_client{user="hello"} 614955110482 (572.72 GB)
telemt_user_msgs_from_client{user="hello"} 7472583
telemt_user_msgs_to_client{user="hello"} 31958899
telemt_user_unique_ips_current{user="hello"} 754
telemt_user_unique_ips_recent_window{user="hello"} 368
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 130695.4 (36h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1307507
telemt_connections_bad_total 82215
telemt_handshake_timeouts_total 32159
telemt_upstream_connect_attempt_total 29551
telemt_upstream_connect_success_total 29385
telemt_upstream_connect_fail_total 166
telemt_upstream_connect_attempts_per_request{bucket="1"} 29551
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13545
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15738
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 97
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 166
telemt_me_keepalive_timeout_total 162
telemt_me_reconnect_attempts_total 43530
telemt_me_reconnect_success_total 22816
telemt_me_reader_eof_total 24784
telemt_me_idle_close_by_peer_total 24776
telemt_me_route_drop_no_conn_total 471312
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 972476
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3383
telemt_desync_full_logged_total 1095
telemt_desync_suppressed_total 2288
telemt_desync_frames_bucket_total{bucket="1_2"} 909
telemt_desync_frames_bucket_total{bucket="3_10"} 1297
telemt_desync_frames_bucket_total{bucket="gt_10"} 1177
telemt_pool_swap_total 109
telemt_me_writer_removed_unexpected_total 23780
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 22804
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 964
telemt_user_connections_total{user="hello"} 970529
telemt_user_connections_current{user="hello"} 1613
telemt_user_octets_from_client{user="hello"} 48590727136 (45.25 GB)
telemt_user_octets_to_client{user="hello"} 471961718064 (439.55 GB)
telemt_user_unique_ips_current{user="hello"} 486
telemt_user_unique_ips_recent_window{user="hello"} 374
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 130754.8 (36h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1695745
telemt_connections_bad_total 84209
telemt_handshake_timeouts_total 30144
telemt_upstream_connect_attempt_total 92680
telemt_upstream_connect_success_total 90225
telemt_upstream_connect_fail_total 2455
telemt_upstream_connect_attempts_per_request{bucket="1"} 92680
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 74321
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15486
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 385
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2455
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 350
telemt_me_reconnect_attempts_total 39365
telemt_me_reconnect_success_total 18937
telemt_me_reader_eof_total 20738
telemt_me_idle_close_by_peer_total 20735
telemt_me_route_drop_no_conn_total 685787
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1396805
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5415
telemt_desync_full_logged_total 1731
telemt_desync_suppressed_total 3684
telemt_desync_frames_bucket_total{bucket="1_2"} 1275
telemt_desync_frames_bucket_total{bucket="3_10"} 2215
telemt_desync_frames_bucket_total{bucket="gt_10"} 1925
telemt_pool_swap_total 103
telemt_me_writer_removed_unexpected_total 19926
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 18917
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 989
telemt_user_connections_total{user="hello"} 1460027
telemt_user_connections_current{user="hello"} 2414
telemt_user_octets_from_client{user="hello"} 24055278554 (22.40 GB)
telemt_user_octets_to_client{user="hello"} 691287382706 (643.81 GB)
telemt_user_msgs_from_client{user="hello"} 744103
telemt_user_msgs_to_client{user="hello"} 5214294
telemt_user_unique_ips_current{user="hello"} 659
telemt_user_unique_ips_recent_window{user="hello"} 330
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 130726.5 (36h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1221407
telemt_connections_bad_total 109610
telemt_handshake_timeouts_total 13056
telemt_upstream_connect_attempt_total 49701
telemt_upstream_connect_success_total 49014
telemt_upstream_connect_fail_total 687
telemt_upstream_connect_attempts_per_request{bucket="1"} 49701
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30167
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18417
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 430
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 687
telemt_me_keepalive_timeout_total 31
telemt_me_reconnect_attempts_total 63520
telemt_me_reconnect_success_total 26018
telemt_me_reader_eof_total 28180
telemt_me_idle_close_by_peer_total 28177
telemt_me_route_drop_no_conn_total 397016
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1006185
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4344
telemt_desync_full_logged_total 1350
telemt_desync_suppressed_total 2994
telemt_desync_frames_bucket_total{bucket="1_2"} 1167
telemt_desync_frames_bucket_total{bucket="3_10"} 1670
telemt_desync_frames_bucket_total{bucket="gt_10"} 1507
telemt_pool_swap_total 69
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 27591
telemt_me_refill_failed_total 1166
telemt_me_writer_restored_same_endpoint_total 26010
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1573
telemt_user_connections_total{user="hello"} 1022572
telemt_user_connections_current{user="hello"} 2051
telemt_user_octets_from_client{user="hello"} 19439790244 (18.10 GB)
telemt_user_octets_to_client{user="hello"} 514222313628 (478.91 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 655
telemt_user_unique_ips_recent_window{user="hello"} 299
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 130887.9 (36h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1275339
telemt_connections_bad_total 133741
telemt_handshake_timeouts_total 10873
telemt_upstream_connect_attempt_total 26045
telemt_upstream_connect_success_total 25889
telemt_upstream_connect_fail_total 156
telemt_upstream_connect_attempts_per_request{bucket="1"} 26045
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12470
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13296
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 113
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 156
telemt_me_keepalive_timeout_total 269
telemt_me_reconnect_attempts_total 30685
telemt_me_reconnect_success_total 19382
telemt_me_reader_eof_total 20970
telemt_me_idle_close_by_peer_total 20967
telemt_me_route_drop_no_conn_total 849432
telemt_me_route_drop_channel_closed_total 96
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1244773
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2424
telemt_desync_full_logged_total 857
telemt_desync_suppressed_total 1567
telemt_desync_frames_bucket_total{bucket="1_2"} 542
telemt_desync_frames_bucket_total{bucket="3_10"} 927
telemt_desync_frames_bucket_total{bucket="gt_10"} 955
telemt_pool_swap_total 118
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 20032
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 19368
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 298
telemt_me_writer_removed_unexpected_minus_restored_total 650
telemt_user_connections_total{user="hello"} 1053429
telemt_user_connections_current{user="hello"} 833
telemt_user_octets_from_client{user="hello"} 16484046472 (15.35 GB)
telemt_user_octets_to_client{user="hello"} 464648318548 (432.74 GB)
telemt_user_unique_ips_current{user="hello"} 290
telemt_user_unique_ips_recent_window{user="hello"} 135
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 78654.7 (21h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 686146
telemt_connections_bad_total 59264
telemt_handshake_timeouts_total 15016
telemt_upstream_connect_attempt_total 26586
telemt_upstream_connect_success_total 26305
telemt_upstream_connect_fail_total 281
telemt_upstream_connect_attempts_per_request{bucket="1"} 26586
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14035
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12169
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 101
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 281
telemt_me_keepalive_timeout_total 149
telemt_me_reconnect_attempts_total 33861
telemt_me_reconnect_success_total 22241
telemt_me_reader_eof_total 23501
telemt_me_idle_close_by_peer_total 23501
telemt_me_seq_mismatch_total 37
telemt_me_route_drop_no_conn_total 196000
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 516566
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 41
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2190
telemt_desync_full_logged_total 752
telemt_desync_suppressed_total 1438
telemt_desync_frames_bucket_total{bucket="1_2"} 356
telemt_desync_frames_bucket_total{bucket="3_10"} 949
telemt_desync_frames_bucket_total{bucket="gt_10"} 885
telemt_pool_swap_total 56
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 22843
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 22194
telemt_me_writer_restored_fallback_total 47
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 602
telemt_user_connections_total{user="hello"} 516269
telemt_user_connections_current{user="hello"} 1511
telemt_user_octets_from_client{user="hello"} 27951097357 (26.03 GB)
telemt_user_octets_to_client{user="hello"} 380483506402 (354.35 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 431
telemt_user_unique_ips_recent_window{user="hello"} 229
```