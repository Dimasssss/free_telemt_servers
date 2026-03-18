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

# Server Metrics 2026-03-18 13:35:26 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.20

telemt_uptime_seconds 17665.2 (4h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 658922
telemt_connections_bad_total 29350
telemt_handshake_timeouts_total 17841
telemt_upstream_connect_attempt_total 66364
telemt_upstream_connect_success_total 65409
telemt_upstream_connect_fail_total 955
telemt_upstream_connect_attempts_per_request{bucket="1"} 66364
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 60644
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4182
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 583
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 955
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 514181
telemt_me_reconnect_success_total 2531
telemt_me_reader_eof_total 2699
telemt_me_idle_close_by_peer_total 2697
telemt_me_route_drop_no_conn_total 380766
telemt_me_route_drop_channel_closed_total 141
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 508121
telemt_me_writer_pick_total{mode="p2c",result="full"} 21
telemt_me_writer_pick_total{mode="p2c",result="closed"} 54
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2261
telemt_desync_full_logged_total 771
telemt_desync_suppressed_total 1490
telemt_desync_frames_bucket_total{bucket="1_2"} 637
telemt_desync_frames_bucket_total{bucket="3_10"} 786
telemt_desync_frames_bucket_total{bucket="gt_10"} 838
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 2702
telemt_me_refill_failed_total 16672
telemt_me_writer_restored_same_endpoint_total 2426
telemt_me_writer_restored_fallback_total 105
telemt_me_async_recovery_trigger_total 11769
telemt_me_writer_removed_unexpected_minus_restored_total 171
telemt_user_connections_total{user="hello"} 566312
telemt_user_connections_current{user="hello"} 1739
telemt_user_octets_from_client{user="hello"} 7581392540 (7.06 GB)
telemt_user_octets_to_client{user="hello"} 144717694961 (134.78 GB)
telemt_user_msgs_from_client{user="hello"} 846607
telemt_user_msgs_to_client{user="hello"} 1165163
telemt_user_unique_ips_current{user="hello"} 547
telemt_user_unique_ips_recent_window{user="hello"} 271
```

## psb.hosting

```
telemt 3.3.20

telemt_uptime_seconds 17696.7 (4h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1737463
telemt_connections_bad_total 119587
telemt_handshake_timeouts_total 38540
telemt_upstream_connect_attempt_total 3120
telemt_upstream_connect_success_total 3108
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 3120
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1660
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1430
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 3290
telemt_me_reconnect_success_total 2145
telemt_me_reader_eof_total 2231
telemt_me_idle_close_by_peer_total 2230
telemt_me_route_drop_no_conn_total 1406555
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1493782
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4588
telemt_desync_full_logged_total 1446
telemt_desync_suppressed_total 3142
telemt_desync_frames_bucket_total{bucket="1_2"} 919
telemt_desync_frames_bucket_total{bucket="3_10"} 1874
telemt_desync_frames_bucket_total{bucket="gt_10"} 1795
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 2196
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 2144
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 1068
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 1492775
telemt_user_connections_current{user="hello"} 4427
telemt_user_octets_from_client{user="hello"} 36399338920 (33.90 GB)
telemt_user_octets_to_client{user="hello"} 458549825780 (427.06 GB)
telemt_user_unique_ips_current{user="hello"} 1316
telemt_user_unique_ips_recent_window{user="hello"} 648
```

## koara.io

```
telemt 3.3.20

telemt_uptime_seconds 17611.4 (4h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1268260
telemt_connections_bad_total 94579
telemt_handshake_timeouts_total 28606
telemt_upstream_connect_attempt_total 11672
telemt_upstream_connect_success_total 11672
telemt_upstream_connect_attempts_per_request{bucket="1"} 11672
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8719
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2939
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 417
telemt_me_reconnect_attempts_total 610749
telemt_me_reconnect_success_total 2520
telemt_me_reader_eof_total 2627
telemt_me_idle_close_by_peer_total 2626
telemt_me_route_drop_no_conn_total 608805
telemt_me_route_drop_channel_closed_total 24
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 987410
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3071
telemt_desync_full_logged_total 1014
telemt_desync_suppressed_total 2057
telemt_desync_frames_bucket_total{bucket="1_2"} 863
telemt_desync_frames_bucket_total{bucket="3_10"} 1104
telemt_desync_frames_bucket_total{bucket="gt_10"} 1104
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 2616
telemt_me_refill_failed_total 19751
telemt_me_writer_restored_same_endpoint_total 2485
telemt_me_writer_restored_fallback_total 35
telemt_me_async_recovery_trigger_total 14895
telemt_me_writer_removed_unexpected_minus_restored_total 96
telemt_user_connections_total{user="hello"} 994888
telemt_user_connections_current{user="hello"} 3280
telemt_user_octets_from_client{user="hello"} 12678548479 (11.81 GB)
telemt_user_octets_to_client{user="hello"} 408726739364 (380.66 GB)
telemt_user_msgs_from_client{user="hello"} 68547
telemt_user_msgs_to_client{user="hello"} 285346
telemt_user_unique_ips_current{user="hello"} 1031
telemt_user_unique_ips_recent_window{user="hello"} 537
```

## landvps.ru

```
telemt 3.3.20

telemt_uptime_seconds 17641.5 (4h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2065704
telemt_connections_bad_total 33054
telemt_handshake_timeouts_total 175560
telemt_upstream_connect_attempt_total 12603
telemt_upstream_connect_success_total 12393
telemt_upstream_connect_fail_total 210
telemt_upstream_connect_attempts_per_request{bucket="1"} 12603
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11005
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1349
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 210
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 699
telemt_me_reconnect_attempts_total 2833938
telemt_me_reconnect_success_total 1180
telemt_me_reader_eof_total 1847
telemt_me_idle_close_by_peer_total 1847
telemt_me_route_drop_no_conn_total 3146083
telemt_me_route_drop_channel_closed_total 28
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1697013
telemt_me_writer_pick_total{mode="p2c",result="success_fallback"} 8840
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_writer_pick_blocking_fallback_total 8840
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3578
telemt_desync_full_logged_total 1062
telemt_desync_suppressed_total 2516
telemt_desync_frames_bucket_total{bucket="1_2"} 913
telemt_desync_frames_bucket_total{bucket="3_10"} 1522
telemt_desync_frames_bucket_total{bucket="gt_10"} 1143
telemt_me_writer_removed_unexpected_total 1896
telemt_me_refill_failed_total 100261
telemt_me_writer_restored_same_endpoint_total 1085
telemt_me_writer_restored_fallback_total 95
telemt_me_async_recovery_trigger_total 365465
telemt_me_writer_removed_unexpected_minus_restored_total 716
telemt_user_connections_total{user="hello"} 1715487
telemt_user_connections_current{user="hello"} 3310
telemt_user_octets_from_client{user="hello"} 37230592406 (34.67 GB)
telemt_user_octets_to_client{user="hello"} 247038932933 (230.07 GB)
telemt_user_msgs_from_client{user="hello"} 80007
telemt_user_msgs_to_client{user="hello"} 158054
telemt_user_unique_ips_current{user="hello"} 919
telemt_user_unique_ips_recent_window{user="hello"} 607
```

## rdp-onedash.ru

```
telemt 3.3.20

telemt_uptime_seconds 17536.4 (4h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1379200
telemt_connections_bad_total 94794
telemt_handshake_timeouts_total 23109
telemt_upstream_connect_attempt_total 12527
telemt_upstream_connect_success_total 12526
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 12527
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10621
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1674
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 231
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 70
telemt_me_reconnect_attempts_total 2986530
telemt_me_reconnect_success_total 2096
telemt_me_reader_eof_total 2192
telemt_me_idle_close_by_peer_total 2192
telemt_me_route_drop_no_conn_total 1285730
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1153052
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3514
telemt_desync_full_logged_total 1198
telemt_desync_suppressed_total 2316
telemt_desync_frames_bucket_total{bucket="1_2"} 534
telemt_desync_frames_bucket_total{bucket="3_10"} 1369
telemt_desync_frames_bucket_total{bucket="gt_10"} 1611
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 2158
telemt_me_refill_failed_total 107230
telemt_me_writer_restored_same_endpoint_total 1981
telemt_me_writer_restored_fallback_total 115
telemt_me_async_recovery_trigger_total 267383
telemt_me_writer_removed_unexpected_minus_restored_total 62
telemt_user_connections_total{user="hello"} 1152844
telemt_user_connections_current{user="hello"} 3382
telemt_user_octets_from_client{user="hello"} 17834423081 (16.61 GB)
telemt_user_octets_to_client{user="hello"} 412446110925 (384.12 GB)
telemt_user_msgs_from_client{user="hello"} 86293
telemt_user_msgs_to_client{user="hello"} 266108
telemt_user_unique_ips_current{user="hello"} 1006
telemt_user_unique_ips_recent_window{user="hello"} 568
```

## hostvds.com

```
telemt 3.3.20

telemt_uptime_seconds 17421.7 (4h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 384224
telemt_connections_bad_total 37074
telemt_handshake_timeouts_total 2915
telemt_upstream_connect_attempt_total 3227
telemt_upstream_connect_success_total 3227
telemt_upstream_connect_attempts_per_request{bucket="1"} 3227
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1485
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1732
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 8715
telemt_me_reconnect_success_total 2261
telemt_me_reader_eof_total 2503
telemt_me_idle_close_by_peer_total 2502
telemt_me_route_drop_no_conn_total 220149
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 327525
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 868
telemt_desync_full_logged_total 306
telemt_desync_suppressed_total 562
telemt_desync_frames_bucket_total{bucket="1_2"} 164
telemt_desync_frames_bucket_total{bucket="3_10"} 336
telemt_desync_frames_bucket_total{bucket="gt_10"} 368
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 2483
telemt_me_refill_failed_total 200
telemt_me_writer_restored_same_endpoint_total 2252
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 130
telemt_me_writer_removed_unexpected_minus_restored_total 222
telemt_user_connections_total{user="hello"} 317797
telemt_user_connections_current{user="hello"} 955
telemt_user_octets_from_client{user="hello"} 4848271232 (4.52 GB)
telemt_user_octets_to_client{user="hello"} 65683195188 (61.17 GB)
telemt_user_unique_ips_current{user="hello"} 308
telemt_user_unique_ips_recent_window{user="hello"} 164
```

## 4vps.su

```
telemt 3.3.20

telemt_uptime_seconds 17492.4 (4h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1113433
telemt_connections_bad_total 118811
telemt_handshake_timeouts_total 22450
telemt_upstream_connect_attempt_total 3254
telemt_upstream_connect_success_total 3225
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 3254
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1798
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1419
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 3360
telemt_me_reconnect_success_total 2258
telemt_me_reader_eof_total 2348
telemt_me_idle_close_by_peer_total 2348
telemt_me_route_drop_no_conn_total 654849
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 883701
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3013
telemt_desync_full_logged_total 1003
telemt_desync_suppressed_total 2010
telemt_desync_frames_bucket_total{bucket="1_2"} 557
telemt_desync_frames_bucket_total{bucket="3_10"} 1021
telemt_desync_frames_bucket_total{bucket="gt_10"} 1435
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 2312
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 2248
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 54
telemt_user_connections_total{user="hello"} 883103
telemt_user_connections_current{user="hello"} 3103
telemt_user_octets_from_client{user="hello"} 17009644724 (15.84 GB)
telemt_user_octets_to_client{user="hello"} 400720513016 (373.20 GB)
telemt_user_unique_ips_current{user="hello"} 910
telemt_user_unique_ips_recent_window{user="hello"} 452
```