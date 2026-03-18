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

# Server Metrics 2026-03-18 13:25:15 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.20

telemt_uptime_seconds 17054.2 (4h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 635385
telemt_connections_bad_total 26412
telemt_handshake_timeouts_total 17184
telemt_upstream_connect_attempt_total 66244
telemt_upstream_connect_success_total 65289
telemt_upstream_connect_fail_total 955
telemt_upstream_connect_attempts_per_request{bucket="1"} 66244
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 60586
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4120
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 583
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 955
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 514104
telemt_me_reconnect_success_total 2454
telemt_me_reader_eof_total 2615
telemt_me_idle_close_by_peer_total 2613
telemt_me_route_drop_no_conn_total 372811
telemt_me_route_drop_channel_closed_total 137
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 489606
telemt_me_writer_pick_total{mode="p2c",result="full"} 21
telemt_me_writer_pick_total{mode="p2c",result="closed"} 54
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2199
telemt_desync_full_logged_total 740
telemt_desync_suppressed_total 1459
telemt_desync_frames_bucket_total{bucket="1_2"} 619
telemt_desync_frames_bucket_total{bucket="3_10"} 773
telemt_desync_frames_bucket_total{bucket="gt_10"} 807
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 2623
telemt_me_refill_failed_total 16672
telemt_me_writer_restored_same_endpoint_total 2349
telemt_me_writer_restored_fallback_total 105
telemt_me_async_recovery_trigger_total 11769
telemt_me_writer_removed_unexpected_minus_restored_total 169
telemt_user_connections_total{user="hello"} 547808
telemt_user_connections_current{user="hello"} 1839
telemt_user_octets_from_client{user="hello"} 7280915020 (6.78 GB)
telemt_user_octets_to_client{user="hello"} 139057320981 (129.51 GB)
telemt_user_msgs_from_client{user="hello"} 846607
telemt_user_msgs_to_client{user="hello"} 1165163
telemt_user_unique_ips_current{user="hello"} 564
telemt_user_unique_ips_recent_window{user="hello"} 241
```

## psb.hosting

```
telemt 3.3.20

telemt_uptime_seconds 17085.5 (4h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1683127
telemt_connections_bad_total 117470
telemt_handshake_timeouts_total 37304
telemt_upstream_connect_attempt_total 3015
telemt_upstream_connect_success_total 3003
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 3015
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1601
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1384
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 3228
telemt_me_reconnect_success_total 2086
telemt_me_reader_eof_total 2164
telemt_me_idle_close_by_peer_total 2163
telemt_me_route_drop_no_conn_total 1385889
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1447226
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4460
telemt_desync_full_logged_total 1391
telemt_desync_suppressed_total 3069
telemt_desync_frames_bucket_total{bucket="1_2"} 905
telemt_desync_frames_bucket_total{bucket="3_10"} 1818
telemt_desync_frames_bucket_total{bucket="gt_10"} 1737
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 2135
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 2085
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 1068
telemt_me_writer_removed_unexpected_minus_restored_total 49
telemt_user_connections_total{user="hello"} 1446226
telemt_user_connections_current{user="hello"} 4318
telemt_user_octets_from_client{user="hello"} 35745070580 (33.29 GB)
telemt_user_octets_to_client{user="hello"} 439710522488 (409.51 GB)
telemt_user_unique_ips_current{user="hello"} 1318
telemt_user_unique_ips_recent_window{user="hello"} 580
```

## koara.io

```
telemt 3.3.20

telemt_uptime_seconds 17000.8 (4h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1209568
telemt_connections_bad_total 90658
telemt_handshake_timeouts_total 27966
telemt_upstream_connect_attempt_total 11536
telemt_upstream_connect_success_total 11536
telemt_upstream_connect_attempts_per_request{bucket="1"} 11536
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8651
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2872
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 308
telemt_me_reconnect_attempts_total 609378
telemt_me_reconnect_success_total 2429
telemt_me_reader_eof_total 2499
telemt_me_idle_close_by_peer_total 2498
telemt_me_route_drop_no_conn_total 533743
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 935657
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3019
telemt_desync_full_logged_total 994
telemt_desync_suppressed_total 2025
telemt_desync_frames_bucket_total{bucket="1_2"} 855
telemt_desync_frames_bucket_total{bucket="3_10"} 1086
telemt_desync_frames_bucket_total{bucket="gt_10"} 1078
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 2485
telemt_me_refill_failed_total 19711
telemt_me_writer_restored_same_endpoint_total 2394
telemt_me_writer_restored_fallback_total 35
telemt_me_async_recovery_trigger_total 14895
telemt_me_writer_removed_unexpected_minus_restored_total 56
telemt_user_connections_total{user="hello"} 943146
telemt_user_connections_current{user="hello"} 3394
telemt_user_octets_from_client{user="hello"} 12143166999 (11.31 GB)
telemt_user_octets_to_client{user="hello"} 397384666436 (370.09 GB)
telemt_user_msgs_from_client{user="hello"} 68547
telemt_user_msgs_to_client{user="hello"} 285346
telemt_user_unique_ips_current{user="hello"} 1031
telemt_user_unique_ips_recent_window{user="hello"} 483
```

## landvps.ru

```
telemt 3.3.20

telemt_uptime_seconds 17030.8 (4h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1997542
telemt_connections_bad_total 32417
telemt_handshake_timeouts_total 174242
telemt_upstream_connect_attempt_total 12551
telemt_upstream_connect_success_total 12348
telemt_upstream_connect_fail_total 203
telemt_upstream_connect_attempts_per_request{bucket="1"} 12551
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10979
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1330
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 203
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 699
telemt_me_reconnect_attempts_total 2832562
telemt_me_reconnect_success_total 1180
telemt_me_reader_eof_total 1804
telemt_me_idle_close_by_peer_total 1804
telemt_me_route_drop_no_conn_total 3036103
telemt_me_route_drop_channel_closed_total 28
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1635555
telemt_me_writer_pick_total{mode="p2c",result="success_fallback"} 8840
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_writer_pick_blocking_fallback_total 8840
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3391
telemt_desync_full_logged_total 1028
telemt_desync_suppressed_total 2363
telemt_desync_frames_bucket_total{bucket="1_2"} 875
telemt_desync_frames_bucket_total{bucket="3_10"} 1427
telemt_desync_frames_bucket_total{bucket="gt_10"} 1089
telemt_me_writer_removed_unexpected_total 1853
telemt_me_refill_failed_total 100218
telemt_me_writer_restored_same_endpoint_total 1085
telemt_me_writer_restored_fallback_total 95
telemt_me_async_recovery_trigger_total 365465
telemt_me_writer_removed_unexpected_minus_restored_total 673
telemt_user_connections_total{user="hello"} 1654057
telemt_user_connections_current{user="hello"} 3160
telemt_user_octets_from_client{user="hello"} 33229548690 (30.95 GB)
telemt_user_octets_to_client{user="hello"} 241184996033 (224.62 GB)
telemt_user_msgs_from_client{user="hello"} 80007
telemt_user_msgs_to_client{user="hello"} 158054
telemt_user_unique_ips_current{user="hello"} 864
telemt_user_unique_ips_recent_window{user="hello"} 440
```

## rdp-onedash.ru

```
telemt 3.3.20

telemt_uptime_seconds 16925.5 (4h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1327988
telemt_connections_bad_total 82828
telemt_handshake_timeouts_total 22231
telemt_upstream_connect_attempt_total 12420
telemt_upstream_connect_success_total 12419
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 12420
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10575
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1615
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 229
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 70
telemt_me_reconnect_attempts_total 2986466
telemt_me_reconnect_success_total 2031
telemt_me_reader_eof_total 2121
telemt_me_idle_close_by_peer_total 2121
telemt_me_route_drop_no_conn_total 1256243
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1116458
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3399
telemt_desync_full_logged_total 1162
telemt_desync_suppressed_total 2237
telemt_desync_frames_bucket_total{bucket="1_2"} 511
telemt_desync_frames_bucket_total{bucket="3_10"} 1331
telemt_desync_frames_bucket_total{bucket="gt_10"} 1557
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 2091
telemt_me_refill_failed_total 107230
telemt_me_writer_restored_same_endpoint_total 1916
telemt_me_writer_restored_fallback_total 115
telemt_me_async_recovery_trigger_total 267383
telemt_me_writer_removed_unexpected_minus_restored_total 60
telemt_user_connections_total{user="hello"} 1116510
telemt_user_connections_current{user="hello"} 3080
telemt_user_octets_from_client{user="hello"} 17141972237 (15.96 GB)
telemt_user_octets_to_client{user="hello"} 401156832637 (373.61 GB)
telemt_user_msgs_from_client{user="hello"} 86293
telemt_user_msgs_to_client{user="hello"} 266108
telemt_user_unique_ips_current{user="hello"} 1040
telemt_user_unique_ips_recent_window{user="hello"} 484
```

## hostvds.com

```
telemt 3.3.20

telemt_uptime_seconds 16810.8 (4h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 369685
telemt_connections_bad_total 34673
telemt_handshake_timeouts_total 2726
telemt_upstream_connect_attempt_total 3083
telemt_upstream_connect_success_total 3083
telemt_upstream_connect_attempts_per_request{bucket="1"} 3083
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1410
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1663
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 8617
telemt_me_reconnect_success_total 2164
telemt_me_reader_eof_total 2403
telemt_me_idle_close_by_peer_total 2402
telemt_me_route_drop_no_conn_total 212085
telemt_me_route_drop_channel_closed_total 29
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 316118
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 832
telemt_desync_full_logged_total 293
telemt_desync_suppressed_total 539
telemt_desync_frames_bucket_total{bucket="1_2"} 159
telemt_desync_frames_bucket_total{bucket="3_10"} 320
telemt_desync_frames_bucket_total{bucket="gt_10"} 353
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 2383
telemt_me_refill_failed_total 200
telemt_me_writer_restored_same_endpoint_total 2155
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 130
telemt_me_writer_removed_unexpected_minus_restored_total 219
telemt_user_connections_total{user="hello"} 306390
telemt_user_connections_current{user="hello"} 917
telemt_user_octets_from_client{user="hello"} 4771859756 (4.44 GB)
telemt_user_octets_to_client{user="hello"} 62388699392 (58.10 GB)
telemt_user_unique_ips_current{user="hello"} 308
telemt_user_unique_ips_recent_window{user="hello"} 130
```

## 4vps.su

```
telemt 3.3.20

telemt_uptime_seconds 16881.5 (4h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1074737
telemt_connections_bad_total 118437
telemt_handshake_timeouts_total 21735
telemt_upstream_connect_attempt_total 3111
telemt_upstream_connect_success_total 3084
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 3111
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1718
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1358
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 2210
telemt_me_reconnect_success_total 2164
telemt_me_reader_eof_total 2221
telemt_me_idle_close_by_peer_total 2221
telemt_me_route_drop_no_conn_total 629201
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 850247
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2908
telemt_desync_full_logged_total 968
telemt_desync_suppressed_total 1940
telemt_desync_frames_bucket_total{bucket="1_2"} 527
telemt_desync_frames_bucket_total{bucket="3_10"} 984
telemt_desync_frames_bucket_total{bucket="gt_10"} 1397
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 2185
telemt_me_writer_restored_same_endpoint_total 2154
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 21
telemt_user_connections_total{user="hello"} 849679
telemt_user_connections_current{user="hello"} 2907
telemt_user_octets_from_client{user="hello"} 16694020536 (15.55 GB)
telemt_user_octets_to_client{user="hello"} 388688692632 (361.99 GB)
telemt_user_unique_ips_current{user="hello"} 868
telemt_user_unique_ips_recent_window{user="hello"} 415
```