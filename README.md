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

# Server Metrics 2026-03-18 18:37:48 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 11547.7 (3h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 314977
telemt_connections_bad_total 19105
telemt_handshake_timeouts_total 7329
telemt_upstream_connect_attempt_total 1904
telemt_upstream_connect_success_total 1904
telemt_upstream_connect_attempts_per_request{bucket="1"} 1904
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 945
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 933
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 1316
telemt_me_reconnect_success_total 1310
telemt_me_reader_eof_total 1357
telemt_me_idle_close_by_peer_total 1357
telemt_me_seq_mismatch_total 4
telemt_me_route_drop_no_conn_total 139762
telemt_me_route_drop_channel_closed_total 58
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 270385
telemt_me_writer_pick_total{mode="p2c",result="full"} 116
telemt_me_writer_pick_total{mode="p2c",result="closed"} 293
telemt_me_endpoint_quarantine_total 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1582
telemt_desync_full_logged_total 452
telemt_desync_suppressed_total 1130
telemt_desync_frames_bucket_total{bucket="1_2"} 388
telemt_desync_frames_bucket_total{bucket="3_10"} 499
telemt_desync_frames_bucket_total{bucket="gt_10"} 695
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 1336
telemt_me_writer_restored_same_endpoint_total 1295
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 75
telemt_me_writer_removed_unexpected_minus_restored_total 26
telemt_user_connections_total{user="hello"} 270269
telemt_user_connections_current{user="hello"} 1316
telemt_user_octets_from_client{user="hello"} 3749477332 (3.49 GB)
telemt_user_octets_to_client{user="hello"} 91099460928 (84.84 GB)
telemt_user_unique_ips_current{user="hello"} 463
telemt_user_unique_ips_recent_window{user="hello"} 164
```

## psb.hosting

```
telemt 3.3.22

telemt_uptime_seconds 16375.6 (4h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1604991
telemt_connections_bad_total 107163
telemt_connections_current 3920
telemt_connections_me_current 3920
telemt_handshake_timeouts_total 30167
telemt_upstream_connect_attempt_total 2728
telemt_upstream_connect_success_total 2714
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 2728
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1442
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1251
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 71
telemt_me_reconnect_attempts_total 1865
telemt_me_reconnect_success_total 1850
telemt_me_reader_eof_total 1838
telemt_me_idle_close_by_peer_total 1837
telemt_me_route_drop_no_conn_total 1550613
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1388896
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4468
telemt_desync_full_logged_total 1415
telemt_desync_suppressed_total 3053
telemt_desync_frames_bucket_total{bucket="1_2"} 778
telemt_desync_frames_bucket_total{bucket="3_10"} 1762
telemt_desync_frames_bucket_total{bucket="gt_10"} 1928
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 1795
telemt_me_writer_restored_same_endpoint_total 1848
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 2874
telemt_user_connections_total{user="hello"} 1384060
telemt_user_connections_current{user="hello"} 3920
telemt_user_octets_from_client{user="hello"} 18355308492 (17.09 GB)
telemt_user_octets_to_client{user="hello"} 428453332288 (399.03 GB)
telemt_user_unique_ips_current{user="hello"} 1204
telemt_user_unique_ips_recent_window{user="hello"} 461
```

## koara.io

```
telemt 3.3.22

telemt_uptime_seconds 16304.2 (4h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1200901
telemt_connections_bad_total 106978
telemt_connections_current 3623
telemt_connections_me_current 3623
telemt_handshake_timeouts_total 24700
telemt_upstream_connect_attempt_total 2285
telemt_upstream_connect_success_total 2272
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 2285
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1195
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1063
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 29
telemt_me_reconnect_attempts_total 1422
telemt_me_reconnect_success_total 1408
telemt_me_reader_eof_total 1494
telemt_me_idle_close_by_peer_total 1494
telemt_me_route_drop_no_conn_total 503823
telemt_me_route_drop_channel_closed_total 47
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 960271
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4493
telemt_desync_full_logged_total 1401
telemt_desync_suppressed_total 3092
telemt_desync_frames_bucket_total{bucket="1_2"} 1108
telemt_desync_frames_bucket_total{bucket="3_10"} 1692
telemt_desync_frames_bucket_total{bucket="gt_10"} 1693
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 1449
telemt_me_writer_restored_same_endpoint_total 1391
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 652
telemt_me_writer_removed_unexpected_minus_restored_total 41
telemt_user_connections_total{user="hello"} 959562
telemt_user_connections_current{user="hello"} 3623
telemt_user_octets_from_client{user="hello"} 21853560248 (20.35 GB)
telemt_user_octets_to_client{user="hello"} 432975019216 (403.24 GB)
telemt_user_unique_ips_current{user="hello"} 1105
telemt_user_unique_ips_recent_window{user="hello"} 447
```

## landvps.ru

```
telemt 3.3.22

telemt_uptime_seconds 17018.1 (4h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1773220
telemt_connections_bad_total 38372
telemt_connections_current 3023
telemt_connections_me_current 3023
telemt_handshake_timeouts_total 18850
telemt_upstream_connect_attempt_total 2534
telemt_upstream_connect_success_total 2515
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 2534
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1309
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1179
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 18
telemt_me_reconnect_attempts_total 1661
telemt_me_reconnect_success_total 1639
telemt_me_reader_eof_total 1689
telemt_me_idle_close_by_peer_total 1688
telemt_me_route_drop_no_conn_total 3097277
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1590900
telemt_me_writer_pick_total{mode="p2c",result="full"} 30
telemt_me_writer_pick_total{mode="p2c",result="closed"} 61
telemt_me_endpoint_quarantine_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6047
telemt_desync_full_logged_total 1477
telemt_desync_suppressed_total 4570
telemt_desync_frames_bucket_total{bucket="1_2"} 1342
telemt_desync_frames_bucket_total{bucket="3_10"} 2879
telemt_desync_frames_bucket_total{bucket="gt_10"} 1826
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 1646
telemt_me_writer_restored_same_endpoint_total 1628
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 1000
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 1590834
telemt_user_connections_current{user="hello"} 3023
telemt_user_octets_from_client{user="hello"} 14368498772 (13.38 GB)
telemt_user_octets_to_client{user="hello"} 251492876200 (234.22 GB)
telemt_user_unique_ips_current{user="hello"} 937
telemt_user_unique_ips_recent_window{user="hello"} 495
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 11533.2 (3h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 865524
telemt_connections_bad_total 154074
telemt_handshake_timeouts_total 8203
telemt_upstream_connect_attempt_total 2002
telemt_upstream_connect_success_total 1936
telemt_upstream_connect_fail_total 66
telemt_upstream_connect_attempts_per_request{bucket="1"} 2002
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1010
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 902
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 66
telemt_me_keepalive_timeout_total 45
telemt_me_reconnect_attempts_total 3431
telemt_me_reconnect_success_total 1338
telemt_me_reader_eof_total 1429
telemt_me_idle_close_by_peer_total 1429
telemt_me_route_drop_no_conn_total 367721
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 635895
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2234
telemt_desync_full_logged_total 781
telemt_desync_suppressed_total 1453
telemt_desync_frames_bucket_total{bucket="1_2"} 427
telemt_desync_frames_bucket_total{bucket="3_10"} 754
telemt_desync_frames_bucket_total{bucket="gt_10"} 1053
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 1425
telemt_me_refill_failed_total 65
telemt_me_writer_restored_same_endpoint_total 1312
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 786
telemt_me_writer_removed_unexpected_minus_restored_total 87
telemt_user_connections_total{user="hello"} 635395
telemt_user_connections_current{user="hello"} 3693
telemt_user_octets_from_client{user="hello"} 10932264420 (10.18 GB)
telemt_user_octets_to_client{user="hello"} 276915209628 (257.90 GB)
telemt_user_unique_ips_current{user="hello"} 1129
telemt_user_unique_ips_recent_window{user="hello"} 438
```

## hostvds.com

```
telemt 3.3.22

telemt_uptime_seconds 16466.1 (4h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 288548
telemt_connections_bad_total 10437
telemt_connections_current 735
telemt_connections_me_current 735
telemt_relay_adaptive_promotions_total 18
telemt_relay_adaptive_hard_promotions_total 18
telemt_handshake_timeouts_total 2993
telemt_upstream_connect_attempt_total 6929
telemt_upstream_connect_success_total 6909
telemt_upstream_connect_fail_total 20
telemt_upstream_connect_attempts_per_request{bucket="1"} 6929
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3586
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3253
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 50
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 20
telemt_me_reconnect_attempts_total 331686
telemt_me_reconnect_success_total 2219
telemt_me_reader_eof_total 2232
telemt_me_idle_close_by_peer_total 2232
telemt_me_route_drop_no_conn_total 185072
telemt_me_route_drop_channel_closed_total 89
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 256319
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 9
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 507
telemt_desync_full_logged_total 188
telemt_desync_suppressed_total 319
telemt_desync_frames_bucket_total{bucket="1_2"} 99
telemt_desync_frames_bucket_total{bucket="3_10"} 208
telemt_desync_frames_bucket_total{bucket="gt_10"} 200
telemt_pool_swap_total 14
telemt_pool_stale_pick_total 980
telemt_me_writer_removed_unexpected_total 2168
telemt_me_refill_failed_total 10448
telemt_me_writer_restored_same_endpoint_total 2208
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 40876
telemt_user_connections_total{user="hello"} 260010
telemt_user_connections_current{user="hello"} 735
telemt_user_octets_from_client{user="hello"} 3657876673 (3.41 GB)
telemt_user_octets_to_client{user="hello"} 54521424001 (50.78 GB)
telemt_user_msgs_from_client{user="hello"} 38712
telemt_user_msgs_to_client{user="hello"} 31668
telemt_user_unique_ips_current{user="hello"} 240
telemt_user_unique_ips_recent_window{user="hello"} 101
```

## 4vps.su

```
telemt 3.3.22

telemt_uptime_seconds 15537.5 (4h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 918328
telemt_connections_bad_total 58066
telemt_connections_current 3244
telemt_connections_me_current 3244
telemt_handshake_timeouts_total 16699
telemt_upstream_connect_attempt_total 2663
telemt_upstream_connect_success_total 2662
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 2663
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1442
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1203
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 17354
telemt_me_reconnect_success_total 1838
telemt_me_reader_eof_total 1846
telemt_me_idle_close_by_peer_total 1846
telemt_me_route_drop_no_conn_total 465423
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="base"} 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 780896
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3217
telemt_desync_full_logged_total 1098
telemt_desync_suppressed_total 2119
telemt_desync_frames_bucket_total{bucket="1_2"} 749
telemt_desync_frames_bucket_total{bucket="3_10"} 1146
telemt_desync_frames_bucket_total{bucket="gt_10"} 1322
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 1807
telemt_me_refill_failed_total 741
telemt_me_writer_restored_same_endpoint_total 1777
telemt_me_writer_restored_fallback_total 61
telemt_me_async_recovery_trigger_total 9552
telemt_user_connections_total{user="hello"} 779844
telemt_user_connections_current{user="hello"} 3244
telemt_user_octets_from_client{user="hello"} 15794844304 (14.71 GB)
telemt_user_octets_to_client{user="hello"} 416695282960 (388.08 GB)
telemt_user_unique_ips_current{user="hello"} 920
telemt_user_unique_ips_recent_window{user="hello"} 374
```