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

# Server Metrics 2026-03-18 13:40:31 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.20

telemt_uptime_seconds 17970.7 (4h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 670442
telemt_connections_bad_total 31283
telemt_handshake_timeouts_total 18173
telemt_upstream_connect_attempt_total 66384
telemt_upstream_connect_success_total 65429
telemt_upstream_connect_fail_total 955
telemt_upstream_connect_attempts_per_request{bucket="1"} 66384
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 60649
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4197
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 583
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 955
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 514201
telemt_me_reconnect_success_total 2550
telemt_me_reader_eof_total 2719
telemt_me_idle_close_by_peer_total 2717
telemt_me_route_drop_no_conn_total 384533
telemt_me_route_drop_channel_closed_total 148
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 516960
telemt_me_writer_pick_total{mode="p2c",result="full"} 21
telemt_me_writer_pick_total{mode="p2c",result="closed"} 54
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2298
telemt_desync_full_logged_total 787
telemt_desync_suppressed_total 1511
telemt_desync_frames_bucket_total{bucket="1_2"} 642
telemt_desync_frames_bucket_total{bucket="3_10"} 794
telemt_desync_frames_bucket_total{bucket="gt_10"} 862
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 2722
telemt_me_refill_failed_total 16672
telemt_me_writer_restored_same_endpoint_total 2445
telemt_me_writer_restored_fallback_total 105
telemt_me_async_recovery_trigger_total 11769
telemt_me_writer_removed_unexpected_minus_restored_total 172
telemt_user_connections_total{user="hello"} 575147
telemt_user_connections_current{user="hello"} 1632
telemt_user_octets_from_client{user="hello"} 7905143760 (7.36 GB)
telemt_user_octets_to_client{user="hello"} 147337814865 (137.22 GB)
telemt_user_msgs_from_client{user="hello"} 846607
telemt_user_msgs_to_client{user="hello"} 1165163
telemt_user_unique_ips_current{user="hello"} 532
telemt_user_unique_ips_recent_window{user="hello"} 244
```

## psb.hosting

```
telemt 3.3.20

telemt_uptime_seconds 18001.8 (5h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1764661
telemt_connections_bad_total 120928
telemt_handshake_timeouts_total 39122
telemt_upstream_connect_attempt_total 3135
telemt_upstream_connect_success_total 3123
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 3135
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1672
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1433
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 3305
telemt_me_reconnect_success_total 2160
telemt_me_reader_eof_total 2246
telemt_me_idle_close_by_peer_total 2245
telemt_me_route_drop_no_conn_total 1415722
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1517610
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4700
telemt_desync_full_logged_total 1477
telemt_desync_suppressed_total 3223
telemt_desync_frames_bucket_total{bucket="1_2"} 944
telemt_desync_frames_bucket_total{bucket="3_10"} 1912
telemt_desync_frames_bucket_total{bucket="gt_10"} 1844
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 2211
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 2159
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 1068
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 1516599
telemt_user_connections_current{user="hello"} 4418
telemt_user_octets_from_client{user="hello"} 36611541356 (34.10 GB)
telemt_user_octets_to_client{user="hello"} 467803363312 (435.68 GB)
telemt_user_unique_ips_current{user="hello"} 1324
telemt_user_unique_ips_recent_window{user="hello"} 648
```

## koara.io

```
telemt 3.3.20

telemt_uptime_seconds 17916.6 (4h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1293284
telemt_connections_bad_total 97903
telemt_handshake_timeouts_total 28948
telemt_upstream_connect_attempt_total 11705
telemt_upstream_connect_success_total 11705
telemt_upstream_connect_attempts_per_request{bucket="1"} 11705
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8734
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2957
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 449
telemt_me_reconnect_attempts_total 610782
telemt_me_reconnect_success_total 2553
telemt_me_reader_eof_total 2660
telemt_me_idle_close_by_peer_total 2659
telemt_me_route_drop_no_conn_total 622798
telemt_me_route_drop_channel_closed_total 24
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1007681
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3158
telemt_desync_full_logged_total 1041
telemt_desync_suppressed_total 2117
telemt_desync_frames_bucket_total{bucket="1_2"} 883
telemt_desync_frames_bucket_total{bucket="3_10"} 1137
telemt_desync_frames_bucket_total{bucket="gt_10"} 1138
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 2649
telemt_me_refill_failed_total 19751
telemt_me_writer_restored_same_endpoint_total 2518
telemt_me_writer_restored_fallback_total 35
telemt_me_async_recovery_trigger_total 14895
telemt_me_writer_removed_unexpected_minus_restored_total 96
telemt_user_connections_total{user="hello"} 1015160
telemt_user_connections_current{user="hello"} 3258
telemt_user_octets_from_client{user="hello"} 13053108323 (12.16 GB)
telemt_user_octets_to_client{user="hello"} 414827447864 (386.34 GB)
telemt_user_msgs_from_client{user="hello"} 68547
telemt_user_msgs_to_client{user="hello"} 285346
telemt_user_unique_ips_current{user="hello"} 1020
telemt_user_unique_ips_recent_window{user="hello"} 500
```

## landvps.ru

```
telemt 3.3.20

telemt_uptime_seconds 17947.0 (4h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2098347
telemt_connections_bad_total 33413
telemt_handshake_timeouts_total 176187
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
telemt_me_route_drop_no_conn_total 3224773
telemt_me_route_drop_channel_closed_total 28
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1726936
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
telemt_desync_total 3672
telemt_desync_full_logged_total 1076
telemt_desync_suppressed_total 2596
telemt_desync_frames_bucket_total{bucket="1_2"} 935
telemt_desync_frames_bucket_total{bucket="3_10"} 1549
telemt_desync_frames_bucket_total{bucket="gt_10"} 1188
telemt_me_writer_removed_unexpected_total 1896
telemt_me_refill_failed_total 100261
telemt_me_writer_restored_same_endpoint_total 1085
telemt_me_writer_restored_fallback_total 95
telemt_me_async_recovery_trigger_total 365465
telemt_me_writer_removed_unexpected_minus_restored_total 716
telemt_user_connections_total{user="hello"} 1745397
telemt_user_connections_current{user="hello"} 2928
telemt_user_octets_from_client{user="hello"} 39172998542 (36.48 GB)
telemt_user_octets_to_client{user="hello"} 250529480029 (233.32 GB)
telemt_user_msgs_from_client{user="hello"} 80007
telemt_user_msgs_to_client{user="hello"} 158054
telemt_user_unique_ips_current{user="hello"} 919
telemt_user_unique_ips_recent_window{user="hello"} 519
```

## rdp-onedash.ru

```
telemt 3.3.20

telemt_uptime_seconds 17841.7 (4h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1410349
telemt_connections_bad_total 99299
telemt_handshake_timeouts_total 23441
telemt_upstream_connect_attempt_total 14707
telemt_upstream_connect_success_total 14679
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 14707
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12138
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1743
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 798
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 70
telemt_me_reconnect_attempts_total 2986543
telemt_me_reconnect_success_total 2108
telemt_me_reader_eof_total 2206
telemt_me_idle_close_by_peer_total 2206
telemt_me_route_drop_no_conn_total 1304083
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1174502
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3583
telemt_desync_full_logged_total 1217
telemt_desync_suppressed_total 2366
telemt_desync_frames_bucket_total{bucket="1_2"} 555
telemt_desync_frames_bucket_total{bucket="3_10"} 1388
telemt_desync_frames_bucket_total{bucket="gt_10"} 1640
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 2172
telemt_me_refill_failed_total 107230
telemt_me_writer_restored_same_endpoint_total 1993
telemt_me_writer_restored_fallback_total 115
telemt_me_async_recovery_trigger_total 267383
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 1176435
telemt_user_connections_current{user="hello"} 2822
telemt_user_octets_from_client{user="hello"} 18602536975 (17.32 GB)
telemt_user_octets_to_client{user="hello"} 417609295225 (388.93 GB)
telemt_user_msgs_from_client{user="hello"} 89703
telemt_user_msgs_to_client{user="hello"} 269409
telemt_user_unique_ips_current{user="hello"} 954
telemt_user_unique_ips_recent_window{user="hello"} 514
```

## hostvds.com

```
telemt 3.3.20

telemt_uptime_seconds 17727.9 (4h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 393886
telemt_connections_bad_total 40296
telemt_handshake_timeouts_total 2961
telemt_upstream_connect_attempt_total 3266
telemt_upstream_connect_success_total 3266
telemt_upstream_connect_attempts_per_request{bucket="1"} 3266
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1503
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1753
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 8754
telemt_me_reconnect_success_total 2300
telemt_me_reader_eof_total 2542
telemt_me_idle_close_by_peer_total 2541
telemt_me_route_drop_no_conn_total 223927
telemt_me_route_drop_channel_closed_total 32
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 333304
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 880
telemt_desync_full_logged_total 311
telemt_desync_suppressed_total 569
telemt_desync_frames_bucket_total{bucket="1_2"} 167
telemt_desync_frames_bucket_total{bucket="3_10"} 340
telemt_desync_frames_bucket_total{bucket="gt_10"} 373
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 2522
telemt_me_refill_failed_total 200
telemt_me_writer_restored_same_endpoint_total 2291
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 130
telemt_me_writer_removed_unexpected_minus_restored_total 222
telemt_user_connections_total{user="hello"} 323572
telemt_user_connections_current{user="hello"} 990
telemt_user_octets_from_client{user="hello"} 4988293376 (4.65 GB)
telemt_user_octets_to_client{user="hello"} 67499286456 (62.86 GB)
telemt_user_unique_ips_current{user="hello"} 310
telemt_user_unique_ips_recent_window{user="hello"} 131
```

## 4vps.su

```
telemt 3.3.20

telemt_uptime_seconds 17797.7 (4h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1131251
telemt_connections_bad_total 118981
telemt_handshake_timeouts_total 22781
telemt_upstream_connect_attempt_total 3296
telemt_upstream_connect_success_total 3267
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 3296
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1821
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1438
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 3402
telemt_me_reconnect_success_total 2300
telemt_me_reader_eof_total 2390
telemt_me_idle_close_by_peer_total 2390
telemt_me_route_drop_no_conn_total 664345
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 899778
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3046
telemt_desync_full_logged_total 1017
telemt_desync_suppressed_total 2029
telemt_desync_frames_bucket_total{bucket="1_2"} 560
telemt_desync_frames_bucket_total{bucket="3_10"} 1030
telemt_desync_frames_bucket_total{bucket="gt_10"} 1456
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 2354
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 2290
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 54
telemt_user_connections_total{user="hello"} 899160
telemt_user_connections_current{user="hello"} 3017
telemt_user_octets_from_client{user="hello"} 18179491756 (16.93 GB)
telemt_user_octets_to_client{user="hello"} 408390481332 (380.34 GB)
telemt_user_unique_ips_current{user="hello"} 922
telemt_user_unique_ips_recent_window{user="hello"} 454
```