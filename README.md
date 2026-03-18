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

# Server Metrics 2026-03-18 08:24:42 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 1269.0 (0h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 58507
telemt_connections_bad_total 34
telemt_handshake_timeouts_total 569
telemt_upstream_connect_attempt_total 17223
telemt_upstream_connect_success_total 16892
telemt_upstream_connect_fail_total 331
telemt_upstream_connect_attempts_per_request{bucket="1"} 17223
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15865
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 823
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 204
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 331
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 317498
telemt_me_reconnect_success_total 481
telemt_me_reader_eof_total 397
telemt_me_idle_close_by_peer_total 397
telemt_me_route_drop_no_conn_total 15670
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 34574
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 29
telemt_me_endpoint_quarantine_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 146
telemt_desync_full_logged_total 47
telemt_desync_suppressed_total 99
telemt_desync_frames_bucket_total{bucket="1_2"} 41
telemt_desync_frames_bucket_total{bucket="3_10"} 57
telemt_desync_frames_bucket_total{bucket="gt_10"} 48
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 390
telemt_me_refill_failed_total 9906
telemt_me_writer_restored_same_endpoint_total 478
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 14752
telemt_user_connections_total{user="hello"} 50873
telemt_user_connections_current{user="hello"} 1455
telemt_user_octets_from_client{user="hello"} 635791047 (606.34 MB)
telemt_user_octets_to_client{user="hello"} 7827890598 (7.29 GB)
telemt_user_msgs_from_client{user="hello"} 160740
telemt_user_msgs_to_client{user="hello"} 206050
telemt_user_unique_ips_current{user="hello"} 447
telemt_user_unique_ips_recent_window{user="hello"} 194
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 135816.4 (37h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2102077
telemt_connections_bad_total 112911
telemt_handshake_timeouts_total 63506
telemt_upstream_connect_attempt_total 472768
telemt_upstream_connect_success_total 471110
telemt_upstream_connect_fail_total 1658
telemt_upstream_connect_attempts_per_request{bucket="1"} 472768
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 391937
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35799
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43372
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1658
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 437
telemt_me_reconnect_attempts_total 136208
telemt_me_reconnect_success_total 21439
telemt_me_reader_eof_total 24004
telemt_me_idle_close_by_peer_total 23990
telemt_me_route_drop_no_conn_total 692999
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1388515
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6261
telemt_desync_full_logged_total 2169
telemt_desync_suppressed_total 4092
telemt_desync_frames_bucket_total{bucket="1_2"} 1187
telemt_desync_frames_bucket_total{bucket="3_10"} 2530
telemt_desync_frames_bucket_total{bucket="gt_10"} 2544
telemt_pool_swap_total 75
telemt_me_writer_removed_unexpected_total 23330
telemt_me_refill_failed_total 3580
telemt_me_writer_restored_same_endpoint_total 21421
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 6668
telemt_me_writer_removed_unexpected_minus_restored_total 1891
telemt_user_connections_total{user="hello"} 1830885
telemt_user_connections_current{user="hello"} 3209
telemt_user_octets_from_client{user="hello"} 30934885493 (28.81 GB)
telemt_user_octets_to_client{user="hello"} 722256756314 (672.65 GB)
telemt_user_msgs_from_client{user="hello"} 7472583
telemt_user_msgs_to_client{user="hello"} 31958899
telemt_user_unique_ips_current{user="hello"} 1009
telemt_user_unique_ips_recent_window{user="hello"} 463
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 135592.1 (37h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1590543
telemt_connections_bad_total 96391
telemt_handshake_timeouts_total 36293
telemt_upstream_connect_attempt_total 30541
telemt_upstream_connect_success_total 30371
telemt_upstream_connect_fail_total 170
telemt_upstream_connect_attempts_per_request{bucket="1"} 30541
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14076
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16192
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 98
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 170
telemt_me_keepalive_timeout_total 179
telemt_me_reconnect_attempts_total 46423
telemt_me_reconnect_success_total 23542
telemt_me_reader_eof_total 25608
telemt_me_idle_close_by_peer_total 25600
telemt_me_route_drop_no_conn_total 687752
telemt_me_route_drop_channel_closed_total 24
telemt_me_route_drop_queue_full_total 15
telemt_me_route_drop_queue_full_profile_total{profile="high"} 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1170991
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4224
telemt_desync_full_logged_total 1437
telemt_desync_suppressed_total 2787
telemt_desync_frames_bucket_total{bucket="1_2"} 1143
telemt_desync_frames_bucket_total{bucket="3_10"} 1631
telemt_desync_frames_bucket_total{bucket="gt_10"} 1450
telemt_pool_swap_total 110
telemt_me_writer_removed_unexpected_total 24594
telemt_me_refill_failed_total 709
telemt_me_writer_restored_same_endpoint_total 23530
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 1052
telemt_user_connections_total{user="hello"} 1168940
telemt_user_connections_current{user="hello"} 2163
telemt_user_octets_from_client{user="hello"} 51572903116 (48.03 GB)
telemt_user_octets_to_client{user="hello"} 535618234864 (498.83 GB)
telemt_user_unique_ips_current{user="hello"} 621
telemt_user_unique_ips_recent_window{user="hello"} 290
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 135651.6 (37h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2058287
telemt_connections_bad_total 91371
telemt_handshake_timeouts_total 39752
telemt_upstream_connect_attempt_total 93710
telemt_upstream_connect_success_total 91244
telemt_upstream_connect_fail_total 2466
telemt_upstream_connect_attempts_per_request{bucket="1"} 93710
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 74920
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15902
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 34
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 388
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2466
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 364
telemt_me_reconnect_attempts_total 42167
telemt_me_reconnect_success_total 19701
telemt_me_reader_eof_total 21593
telemt_me_idle_close_by_peer_total 21590
telemt_me_route_drop_no_conn_total 1076569
telemt_me_route_drop_channel_closed_total 28
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1720492
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6648
telemt_desync_full_logged_total 2034
telemt_desync_suppressed_total 4614
telemt_desync_frames_bucket_total{bucket="1_2"} 1481
telemt_desync_frames_bucket_total{bucket="3_10"} 2739
telemt_desync_frames_bucket_total{bucket="gt_10"} 2428
telemt_pool_swap_total 104
telemt_me_writer_removed_unexpected_total 20771
telemt_me_refill_failed_total 692
telemt_me_writer_restored_same_endpoint_total 19681
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 1070
telemt_user_connections_total{user="hello"} 1783563
telemt_user_connections_current{user="hello"} 3014
telemt_user_octets_from_client{user="hello"} 29081591866 (27.08 GB)
telemt_user_octets_to_client{user="hello"} 759565725422 (707.40 GB)
telemt_user_msgs_from_client{user="hello"} 744103
telemt_user_msgs_to_client{user="hello"} 5214294
telemt_user_unique_ips_current{user="hello"} 802
telemt_user_unique_ips_recent_window{user="hello"} 403
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 135623.5 (37h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1496149
telemt_connections_bad_total 125848
telemt_handshake_timeouts_total 18512
telemt_upstream_connect_attempt_total 50202
telemt_upstream_connect_success_total 49495
telemt_upstream_connect_fail_total 707
telemt_upstream_connect_attempts_per_request{bucket="1"} 50202
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30453
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18610
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 432
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 707
telemt_me_keepalive_timeout_total 40
telemt_me_reconnect_attempts_total 70529
telemt_me_reconnect_success_total 26272
telemt_me_reader_eof_total 28642
telemt_me_idle_close_by_peer_total 28639
telemt_me_route_drop_no_conn_total 637461
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1242827
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5374
telemt_desync_full_logged_total 1659
telemt_desync_suppressed_total 3715
telemt_desync_frames_bucket_total{bucket="1_2"} 1353
telemt_desync_frames_bucket_total{bucket="3_10"} 2072
telemt_desync_frames_bucket_total{bucket="gt_10"} 1949
telemt_pool_swap_total 69
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 28061
telemt_me_refill_failed_total 1377
telemt_me_writer_restored_same_endpoint_total 26264
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1789
telemt_user_connections_total{user="hello"} 1259053
telemt_user_connections_current{user="hello"} 2463
telemt_user_octets_from_client{user="hello"} 24132107844 (22.47 GB)
telemt_user_octets_to_client{user="hello"} 598510217956 (557.41 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 779
telemt_user_unique_ips_recent_window{user="hello"} 344
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 135784.8 (37h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1372642
telemt_connections_bad_total 144580
telemt_handshake_timeouts_total 11255
telemt_upstream_connect_attempt_total 27074
telemt_upstream_connect_success_total 26915
telemt_upstream_connect_fail_total 159
telemt_upstream_connect_attempts_per_request{bucket="1"} 27074
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13010
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13782
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 113
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 159
telemt_me_keepalive_timeout_total 292
telemt_me_reconnect_attempts_total 31488
telemt_me_reconnect_success_total 20172
telemt_me_reader_eof_total 21811
telemt_me_idle_close_by_peer_total 21808
telemt_me_route_drop_no_conn_total 936924
telemt_me_route_drop_channel_closed_total 103
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1326334
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2597
telemt_desync_full_logged_total 912
telemt_desync_suppressed_total 1685
telemt_desync_frames_bucket_total{bucket="1_2"} 560
telemt_desync_frames_bucket_total{bucket="3_10"} 1003
telemt_desync_frames_bucket_total{bucket="gt_10"} 1034
telemt_pool_swap_total 121
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 20836
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 20158
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 298
telemt_me_writer_removed_unexpected_minus_restored_total 664
telemt_user_connections_total{user="hello"} 1134985
telemt_user_connections_current{user="hello"} 936
telemt_user_octets_from_client{user="hello"} 17167567008 (15.99 GB)
telemt_user_octets_to_client{user="hello"} 479583033744 (446.65 GB)
telemt_user_unique_ips_current{user="hello"} 296
telemt_user_unique_ips_recent_window{user="hello"} 106
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 83551.6 (23h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 858351
telemt_connections_bad_total 79140
telemt_handshake_timeouts_total 18058
telemt_upstream_connect_attempt_total 27557
telemt_upstream_connect_success_total 27239
telemt_upstream_connect_fail_total 318
telemt_upstream_connect_attempts_per_request{bucket="1"} 27557
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14501
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12629
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 318
telemt_me_keepalive_timeout_total 164
telemt_me_reconnect_attempts_total 38224
telemt_me_reconnect_success_total 22935
telemt_me_reader_eof_total 24293
telemt_me_idle_close_by_peer_total 24293
telemt_me_seq_mismatch_total 37
telemt_me_route_drop_no_conn_total 272896
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 655754
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 41
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2595
telemt_desync_full_logged_total 889
telemt_desync_suppressed_total 1706
telemt_desync_frames_bucket_total{bucket="1_2"} 446
telemt_desync_frames_bucket_total{bucket="3_10"} 1057
telemt_desync_frames_bucket_total{bucket="gt_10"} 1092
telemt_pool_swap_total 56
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 23667
telemt_me_refill_failed_total 473
telemt_me_writer_restored_same_endpoint_total 22888
telemt_me_writer_restored_fallback_total 47
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 732
telemt_user_connections_total{user="hello"} 655383
telemt_user_connections_current{user="hello"} 1996
telemt_user_octets_from_client{user="hello"} 30800651929 (28.69 GB)
telemt_user_octets_to_client{user="hello"} 457239396326 (425.84 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 575
telemt_user_unique_ips_recent_window{user="hello"} 245
```