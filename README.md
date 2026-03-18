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

# Server Metrics 2026-03-18 12:39:18 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.20

telemt_uptime_seconds 14297.2 (3h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 516687
telemt_connections_bad_total 7901
telemt_handshake_timeouts_total 14601
telemt_upstream_connect_attempt_total 65834
telemt_upstream_connect_success_total 64889
telemt_upstream_connect_fail_total 945
telemt_upstream_connect_attempts_per_request{bucket="1"} 65834
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 60391
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3915
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 583
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 945
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 511247
telemt_me_reconnect_success_total 2194
telemt_me_reader_eof_total 2262
telemt_me_idle_close_by_peer_total 2260
telemt_me_route_drop_no_conn_total 309564
telemt_me_route_drop_channel_closed_total 98
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 397060
telemt_me_writer_pick_total{mode="p2c",result="full"} 21
telemt_me_writer_pick_total{mode="p2c",result="closed"} 54
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1700
telemt_desync_full_logged_total 559
telemt_desync_suppressed_total 1141
telemt_desync_frames_bucket_total{bucket="1_2"} 479
telemt_desync_frames_bucket_total{bucket="3_10"} 598
telemt_desync_frames_bucket_total{bucket="gt_10"} 623
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 2276
telemt_me_refill_failed_total 16591
telemt_me_writer_restored_same_endpoint_total 2089
telemt_me_writer_restored_fallback_total 105
telemt_me_async_recovery_trigger_total 11769
telemt_me_writer_removed_unexpected_minus_restored_total 82
telemt_user_connections_total{user="hello"} 455308
telemt_user_connections_current{user="hello"} 1727
telemt_user_octets_from_client{user="hello"} 6215068504 (5.79 GB)
telemt_user_octets_to_client{user="hello"} 117991000869 (109.89 GB)
telemt_user_msgs_from_client{user="hello"} 846607
telemt_user_msgs_to_client{user="hello"} 1165163
telemt_user_unique_ips_current{user="hello"} 555
telemt_user_unique_ips_recent_window{user="hello"} 268
```

## psb.hosting

```
telemt 3.3.20

telemt_uptime_seconds 14327.7 (3h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1424587
telemt_connections_bad_total 102909
telemt_handshake_timeouts_total 31960
telemt_upstream_connect_attempt_total 2526
telemt_upstream_connect_success_total 2514
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 2526
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1352
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1146
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 1785
telemt_me_reconnect_success_total 1736
telemt_me_reader_eof_total 1763
telemt_me_idle_close_by_peer_total 1762
telemt_me_route_drop_no_conn_total 1223082
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1224595
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3868
telemt_desync_full_logged_total 1156
telemt_desync_suppressed_total 2712
telemt_desync_frames_bucket_total{bucket="1_2"} 761
telemt_desync_frames_bucket_total{bucket="3_10"} 1558
telemt_desync_frames_bucket_total{bucket="gt_10"} 1549
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 1745
telemt_me_writer_restored_same_endpoint_total 1735
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 1068
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 1223641
telemt_user_connections_current{user="hello"} 4065
telemt_user_octets_from_client{user="hello"} 30832484692 (28.71 GB)
telemt_user_octets_to_client{user="hello"} 358844330848 (334.20 GB)
telemt_user_unique_ips_current{user="hello"} 1243
telemt_user_unique_ips_recent_window{user="hello"} 596
```

## koara.io

```
telemt 3.3.20

telemt_uptime_seconds 14242.8 (3h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1012863
telemt_connections_bad_total 74042
telemt_handshake_timeouts_total 24763
telemt_upstream_connect_attempt_total 10903
telemt_upstream_connect_success_total 10903
telemt_upstream_connect_attempts_per_request{bucket="1"} 10903
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8351
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2541
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 607633
telemt_me_reconnect_success_total 1938
telemt_me_reader_eof_total 1964
telemt_me_idle_close_by_peer_total 1963
telemt_me_route_drop_no_conn_total 429723
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 770047
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2203
telemt_desync_full_logged_total 754
telemt_desync_suppressed_total 1449
telemt_desync_frames_bucket_total{bucket="1_2"} 604
telemt_desync_frames_bucket_total{bucket="3_10"} 820
telemt_desync_frames_bucket_total{bucket="gt_10"} 779
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 1948
telemt_me_refill_failed_total 19672
telemt_me_writer_restored_same_endpoint_total 1903
telemt_me_writer_restored_fallback_total 35
telemt_me_async_recovery_trigger_total 14895
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 777553
telemt_user_connections_current{user="hello"} 3285
telemt_user_octets_from_client{user="hello"} 9250454255 (8.62 GB)
telemt_user_octets_to_client{user="hello"} 322070191104 (299.95 GB)
telemt_user_msgs_from_client{user="hello"} 68547
telemt_user_msgs_to_client{user="hello"} 285346
telemt_user_unique_ips_current{user="hello"} 977
telemt_user_unique_ips_recent_window{user="hello"} 511
```

## landvps.ru

```
telemt 3.3.20

telemt_uptime_seconds 14272.9 (3h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1654592
telemt_connections_bad_total 23742
telemt_handshake_timeouts_total 164461
telemt_upstream_connect_attempt_total 12383
telemt_upstream_connect_success_total 12201
telemt_upstream_connect_fail_total 182
telemt_upstream_connect_attempts_per_request{bucket="1"} 12383
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10888
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1274
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 182
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 699
telemt_me_reconnect_attempts_total 2828461
telemt_me_reconnect_success_total 1179
telemt_me_reader_eof_total 1678
telemt_me_idle_close_by_peer_total 1678
telemt_me_route_drop_no_conn_total 2439765
telemt_me_route_drop_channel_closed_total 21
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1330285
telemt_me_writer_pick_total{mode="p2c",result="success_fallback"} 8840
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_writer_pick_blocking_fallback_total 8840
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2820
telemt_desync_full_logged_total 879
telemt_desync_suppressed_total 1941
telemt_desync_frames_bucket_total{bucket="1_2"} 701
telemt_desync_frames_bucket_total{bucket="3_10"} 1179
telemt_desync_frames_bucket_total{bucket="gt_10"} 940
telemt_me_writer_removed_unexpected_total 1724
telemt_me_refill_failed_total 100090
telemt_me_writer_restored_same_endpoint_total 1084
telemt_me_writer_restored_fallback_total 95
telemt_me_async_recovery_trigger_total 365465
telemt_me_writer_removed_unexpected_minus_restored_total 545
telemt_user_connections_total{user="hello"} 1348891
telemt_user_connections_current{user="hello"} 3474
telemt_user_octets_from_client{user="hello"} 17006094918 (15.84 GB)
telemt_user_octets_to_client{user="hello"} 211490573333 (196.97 GB)
telemt_user_msgs_from_client{user="hello"} 80007
telemt_user_msgs_to_client{user="hello"} 158054
telemt_user_unique_ips_current{user="hello"} 950
telemt_user_unique_ips_recent_window{user="hello"} 618
```

## rdp-onedash.ru

```
telemt 3.3.20

telemt_uptime_seconds 14167.8 (3h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1051884
telemt_connections_bad_total 43577
telemt_handshake_timeouts_total 18509
telemt_upstream_connect_attempt_total 11971
telemt_upstream_connect_success_total 11970
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 11971
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10291
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1453
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 226
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 61
telemt_me_reconnect_attempts_total 2983684
telemt_me_reconnect_success_total 1719
telemt_me_reader_eof_total 1720
telemt_me_idle_close_by_peer_total 1720
telemt_me_route_drop_no_conn_total 665928
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 897945
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3012
telemt_desync_full_logged_total 1010
telemt_desync_suppressed_total 2002
telemt_desync_frames_bucket_total{bucket="1_2"} 428
telemt_desync_frames_bucket_total{bucket="3_10"} 1180
telemt_desync_frames_bucket_total{bucket="gt_10"} 1404
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 1697
telemt_me_refill_failed_total 107153
telemt_me_writer_restored_same_endpoint_total 1604
telemt_me_writer_restored_fallback_total 115
telemt_me_async_recovery_trigger_total 267383
telemt_user_connections_total{user="hello"} 898139
telemt_user_connections_current{user="hello"} 3271
telemt_user_octets_from_client{user="hello"} 13708130973 (12.77 GB)
telemt_user_octets_to_client{user="hello"} 339567738601 (316.25 GB)
telemt_user_msgs_from_client{user="hello"} 86293
telemt_user_msgs_to_client{user="hello"} 266108
telemt_user_unique_ips_current{user="hello"} 1044
telemt_user_unique_ips_recent_window{user="hello"} 553
```

## hostvds.com

```
telemt 3.3.20

telemt_uptime_seconds 14055.2 (3h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 299239
telemt_connections_bad_total 26964
telemt_handshake_timeouts_total 2301
telemt_upstream_connect_attempt_total 2748
telemt_upstream_connect_success_total 2748
telemt_upstream_connect_attempts_per_request{bucket="1"} 2748
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1283
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1463
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 5704
telemt_me_reconnect_success_total 1970
telemt_me_reader_eof_total 2125
telemt_me_idle_close_by_peer_total 2124
telemt_me_route_drop_no_conn_total 159619
telemt_me_route_drop_channel_closed_total 15
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 257690
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 672
telemt_desync_full_logged_total 232
telemt_desync_suppressed_total 440
telemt_desync_frames_bucket_total{bucket="1_2"} 137
telemt_desync_frames_bucket_total{bucket="3_10"} 245
telemt_desync_frames_bucket_total{bucket="gt_10"} 290
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 2105
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 1962
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 130
telemt_me_writer_removed_unexpected_minus_restored_total 135
telemt_user_connections_total{user="hello"} 247984
telemt_user_connections_current{user="hello"} 890
telemt_user_octets_from_client{user="hello"} 4328498380 (4.03 GB)
telemt_user_octets_to_client{user="hello"} 53876578124 (50.18 GB)
telemt_user_unique_ips_current{user="hello"} 323
telemt_user_unique_ips_recent_window{user="hello"} 148
```

## 4vps.su

```
telemt 3.3.20

telemt_uptime_seconds 14123.9 (3h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 866638
telemt_connections_bad_total 115058
telemt_handshake_timeouts_total 18400
telemt_upstream_connect_attempt_total 2564
telemt_upstream_connect_success_total 2538
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 2564
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1412
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1118
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_reconnect_attempts_total 1802
telemt_me_reconnect_success_total 1774
telemt_me_reader_eof_total 1812
telemt_me_idle_close_by_peer_total 1812
telemt_me_route_drop_no_conn_total 391748
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 666160
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2368
telemt_desync_full_logged_total 809
telemt_desync_suppressed_total 1559
telemt_desync_frames_bucket_total{bucket="1_2"} 406
telemt_desync_frames_bucket_total{bucket="3_10"} 820
telemt_desync_frames_bucket_total{bucket="gt_10"} 1142
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 1784
telemt_me_writer_restored_same_endpoint_total 1764
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 665658
telemt_user_connections_current{user="hello"} 3072
telemt_user_octets_from_client{user="hello"} 14454235256 (13.46 GB)
telemt_user_octets_to_client{user="hello"} 329373996820 (306.75 GB)
telemt_user_unique_ips_current{user="hello"} 909
telemt_user_unique_ips_recent_window{user="hello"} 421
```