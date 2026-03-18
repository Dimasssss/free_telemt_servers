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

# Server Metrics 2026-03-18 13:30:20 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.20

telemt_uptime_seconds 17359.9 (4h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 646604
telemt_connections_bad_total 27428
telemt_handshake_timeouts_total 17510
telemt_upstream_connect_attempt_total 66335
telemt_upstream_connect_success_total 65380
telemt_upstream_connect_fail_total 955
telemt_upstream_connect_attempts_per_request{bucket="1"} 66335
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 60634
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4163
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 583
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 955
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 514152
telemt_me_reconnect_success_total 2502
telemt_me_reader_eof_total 2668
telemt_me_idle_close_by_peer_total 2666
telemt_me_route_drop_no_conn_total 376974
telemt_me_route_drop_channel_closed_total 138
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 498765
telemt_me_writer_pick_total{mode="p2c",result="full"} 21
telemt_me_writer_pick_total{mode="p2c",result="closed"} 54
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2228
telemt_desync_full_logged_total 755
telemt_desync_suppressed_total 1473
telemt_desync_frames_bucket_total{bucket="1_2"} 625
telemt_desync_frames_bucket_total{bucket="3_10"} 782
telemt_desync_frames_bucket_total{bucket="gt_10"} 821
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 2671
telemt_me_refill_failed_total 16672
telemt_me_writer_restored_same_endpoint_total 2397
telemt_me_writer_restored_fallback_total 105
telemt_me_async_recovery_trigger_total 11769
telemt_me_writer_removed_unexpected_minus_restored_total 169
telemt_user_connections_total{user="hello"} 556956
telemt_user_connections_current{user="hello"} 1766
telemt_user_octets_from_client{user="hello"} 7397486824 (6.89 GB)
telemt_user_octets_to_client{user="hello"} 141910833737 (132.16 GB)
telemt_user_msgs_from_client{user="hello"} 846607
telemt_user_msgs_to_client{user="hello"} 1165163
telemt_user_unique_ips_current{user="hello"} 554
telemt_user_unique_ips_recent_window{user="hello"} 257
```

## psb.hosting

```
telemt 3.3.20

telemt_uptime_seconds 17391.1 (4h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1710154
telemt_connections_bad_total 118268
telemt_handshake_timeouts_total 37780
telemt_upstream_connect_attempt_total 3104
telemt_upstream_connect_success_total 3092
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 3104
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1651
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1423
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 3274
telemt_me_reconnect_success_total 2129
telemt_me_reader_eof_total 2214
telemt_me_idle_close_by_peer_total 2213
telemt_me_route_drop_no_conn_total 1397113
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1470013
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4508
telemt_desync_full_logged_total 1416
telemt_desync_suppressed_total 3092
telemt_desync_frames_bucket_total{bucket="1_2"} 913
telemt_desync_frames_bucket_total{bucket="3_10"} 1843
telemt_desync_frames_bucket_total{bucket="gt_10"} 1752
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 2179
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 2128
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 1068
telemt_me_writer_removed_unexpected_minus_restored_total 50
telemt_user_connections_total{user="hello"} 1469007
telemt_user_connections_current{user="hello"} 4407
telemt_user_octets_from_client{user="hello"} 36201641064 (33.72 GB)
telemt_user_octets_to_client{user="hello"} 448767565388 (417.95 GB)
telemt_user_unique_ips_current{user="hello"} 1307
telemt_user_unique_ips_recent_window{user="hello"} 608
```

## koara.io

```
telemt 3.3.20

telemt_uptime_seconds 17305.5 (4h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1233272
telemt_connections_bad_total 92573
telemt_handshake_timeouts_total 28249
telemt_upstream_connect_attempt_total 11627
telemt_upstream_connect_success_total 11627
telemt_upstream_connect_attempts_per_request{bucket="1"} 11627
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8700
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2914
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 356
telemt_me_reconnect_attempts_total 610608
telemt_me_reconnect_success_total 2475
telemt_me_reader_eof_total 2581
telemt_me_idle_close_by_peer_total 2580
telemt_me_route_drop_no_conn_total 551203
telemt_me_route_drop_channel_closed_total 24
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 955902
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3048
telemt_desync_full_logged_total 1003
telemt_desync_suppressed_total 2045
telemt_desync_frames_bucket_total{bucket="1_2"} 858
telemt_desync_frames_bucket_total{bucket="3_10"} 1094
telemt_desync_frames_bucket_total{bucket="gt_10"} 1096
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 2568
telemt_me_refill_failed_total 19748
telemt_me_writer_restored_same_endpoint_total 2440
telemt_me_writer_restored_fallback_total 35
telemt_me_async_recovery_trigger_total 14895
telemt_me_writer_removed_unexpected_minus_restored_total 93
telemt_user_connections_total{user="hello"} 963386
telemt_user_connections_current{user="hello"} 3515
telemt_user_octets_from_client{user="hello"} 12400625715 (11.55 GB)
telemt_user_octets_to_client{user="hello"} 403566494536 (375.85 GB)
telemt_user_msgs_from_client{user="hello"} 68547
telemt_user_msgs_to_client{user="hello"} 285346
telemt_user_unique_ips_current{user="hello"} 1029
telemt_user_unique_ips_recent_window{user="hello"} 514
```

## landvps.ru

```
telemt 3.3.20

telemt_uptime_seconds 17335.9 (4h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2027977
telemt_connections_bad_total 32708
telemt_handshake_timeouts_total 175059
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
telemt_me_reconnect_attempts_total 2833906
telemt_me_reconnect_success_total 1180
telemt_me_reader_eof_total 1846
telemt_me_idle_close_by_peer_total 1846
telemt_me_route_drop_no_conn_total 3073066
telemt_me_route_drop_channel_closed_total 28
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1662154
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
telemt_desync_total 3501
telemt_desync_full_logged_total 1044
telemt_desync_suppressed_total 2457
telemt_desync_frames_bucket_total{bucket="1_2"} 898
telemt_desync_frames_bucket_total{bucket="3_10"} 1484
telemt_desync_frames_bucket_total{bucket="gt_10"} 1119
telemt_me_writer_removed_unexpected_total 1895
telemt_me_refill_failed_total 100260
telemt_me_writer_restored_same_endpoint_total 1085
telemt_me_writer_restored_fallback_total 95
telemt_me_async_recovery_trigger_total 365465
telemt_me_writer_removed_unexpected_minus_restored_total 715
telemt_user_connections_total{user="hello"} 1680640
telemt_user_connections_current{user="hello"} 3256
telemt_user_octets_from_client{user="hello"} 35356564170 (32.93 GB)
telemt_user_octets_to_client{user="hello"} 244049475341 (227.29 GB)
telemt_user_msgs_from_client{user="hello"} 80007
telemt_user_msgs_to_client{user="hello"} 158054
telemt_user_unique_ips_current{user="hello"} 878
telemt_user_unique_ips_recent_window{user="hello"} 523
```

## rdp-onedash.ru

```
telemt 3.3.20

telemt_uptime_seconds 17230.5 (4h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1351676
telemt_connections_bad_total 87769
telemt_handshake_timeouts_total 22824
telemt_upstream_connect_attempt_total 12481
telemt_upstream_connect_success_total 12480
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 12481
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10608
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1642
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 230
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 70
telemt_me_reconnect_attempts_total 2986484
telemt_me_reconnect_success_total 2049
telemt_me_reader_eof_total 2144
telemt_me_idle_close_by_peer_total 2144
telemt_me_route_drop_no_conn_total 1274163
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1133944
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3447
telemt_desync_full_logged_total 1182
telemt_desync_suppressed_total 2265
telemt_desync_frames_bucket_total{bucket="1_2"} 527
telemt_desync_frames_bucket_total{bucket="3_10"} 1341
telemt_desync_frames_bucket_total{bucket="gt_10"} 1579
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 2111
telemt_me_refill_failed_total 107230
telemt_me_writer_restored_same_endpoint_total 1934
telemt_me_writer_restored_fallback_total 115
telemt_me_async_recovery_trigger_total 267383
telemt_me_writer_removed_unexpected_minus_restored_total 62
telemt_user_connections_total{user="hello"} 1133750
telemt_user_connections_current{user="hello"} 3092
telemt_user_octets_from_client{user="hello"} 17443927497 (16.25 GB)
telemt_user_octets_to_client{user="hello"} 406737118469 (378.80 GB)
telemt_user_msgs_from_client{user="hello"} 86293
telemt_user_msgs_to_client{user="hello"} 266108
telemt_user_unique_ips_current{user="hello"} 1009
telemt_user_unique_ips_recent_window{user="hello"} 517
```

## hostvds.com

```
telemt 3.3.20

telemt_uptime_seconds 17116.1 (4h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 376860
telemt_connections_bad_total 36381
telemt_handshake_timeouts_total 2761
telemt_upstream_connect_attempt_total 3104
telemt_upstream_connect_success_total 3104
telemt_upstream_connect_attempts_per_request{bucket="1"} 3104
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1419
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1675
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 8638
telemt_me_reconnect_success_total 2185
telemt_me_reader_eof_total 2424
telemt_me_idle_close_by_peer_total 2423
telemt_me_route_drop_no_conn_total 215154
telemt_me_route_drop_channel_closed_total 29
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 321278
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 855
telemt_desync_full_logged_total 300
telemt_desync_suppressed_total 555
telemt_desync_frames_bucket_total{bucket="1_2"} 164
telemt_desync_frames_bucket_total{bucket="3_10"} 330
telemt_desync_frames_bucket_total{bucket="gt_10"} 361
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 2404
telemt_me_refill_failed_total 200
telemt_me_writer_restored_same_endpoint_total 2176
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 130
telemt_me_writer_removed_unexpected_minus_restored_total 219
telemt_user_connections_total{user="hello"} 311549
telemt_user_connections_current{user="hello"} 912
telemt_user_octets_from_client{user="hello"} 4815111076 (4.48 GB)
telemt_user_octets_to_client{user="hello"} 64120302568 (59.72 GB)
telemt_user_unique_ips_current{user="hello"} 304
telemt_user_unique_ips_recent_window{user="hello"} 132
```

## 4vps.su

```
telemt 3.3.20

telemt_uptime_seconds 17186.7 (4h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1092261
telemt_connections_bad_total 118651
telemt_handshake_timeouts_total 22119
telemt_upstream_connect_attempt_total 3159
telemt_upstream_connect_success_total 3132
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 3159
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1746
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1378
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 2248
telemt_me_reconnect_success_total 2202
telemt_me_reader_eof_total 2259
telemt_me_idle_close_by_peer_total 2259
telemt_me_route_drop_no_conn_total 638715
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 865701
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2974
telemt_desync_full_logged_total 987
telemt_desync_suppressed_total 1987
telemt_desync_frames_bucket_total{bucket="1_2"} 548
telemt_desync_frames_bucket_total{bucket="3_10"} 1007
telemt_desync_frames_bucket_total{bucket="gt_10"} 1419
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 2223
telemt_me_writer_restored_same_endpoint_total 2192
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 21
telemt_user_connections_total{user="hello"} 865113
telemt_user_connections_current{user="hello"} 2826
telemt_user_octets_from_client{user="hello"} 16861456048 (15.70 GB)
telemt_user_octets_to_client{user="hello"} 394568340488 (367.47 GB)
telemt_user_unique_ips_current{user="hello"} 863
telemt_user_unique_ips_recent_window{user="hello"} 436
```