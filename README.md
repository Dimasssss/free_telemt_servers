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

# Server Metrics 2026-03-18 19:03:26 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 13085.4 (3h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 348800
telemt_connections_bad_total 21421
telemt_handshake_timeouts_total 7898
telemt_upstream_connect_attempt_total 2212
telemt_upstream_connect_success_total 2212
telemt_upstream_connect_attempts_per_request{bucket="1"} 2212
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1081
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1098
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 1538
telemt_me_reconnect_success_total 1531
telemt_me_reader_eof_total 1584
telemt_me_idle_close_by_peer_total 1584
telemt_me_seq_mismatch_total 5
telemt_me_route_drop_no_conn_total 152177
telemt_me_route_drop_channel_closed_total 63
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 299605
telemt_me_writer_pick_total{mode="p2c",result="full"} 116
telemt_me_writer_pick_total{mode="p2c",result="closed"} 293
telemt_me_endpoint_quarantine_total 26
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1799
telemt_desync_full_logged_total 515
telemt_desync_suppressed_total 1284
telemt_desync_frames_bucket_total{bucket="1_2"} 435
telemt_desync_frames_bucket_total{bucket="3_10"} 559
telemt_desync_frames_bucket_total{bucket="gt_10"} 805
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 1559
telemt_me_writer_restored_same_endpoint_total 1515
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 75
telemt_me_writer_removed_unexpected_minus_restored_total 28
telemt_user_connections_total{user="hello"} 299485
telemt_user_connections_current{user="hello"} 1145
telemt_user_octets_from_client{user="hello"} 5577968004 (5.19 GB)
telemt_user_octets_to_client{user="hello"} 99955517208 (93.09 GB)
telemt_user_unique_ips_current{user="hello"} 419
telemt_user_unique_ips_recent_window{user="hello"} 149
```

## psb.hosting

```
telemt 3.3.22

telemt_uptime_seconds 17912.7 (4h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1744950
telemt_connections_bad_total 118869
telemt_connections_current 4198
telemt_connections_me_current 4198
telemt_handshake_timeouts_total 31260
telemt_upstream_connect_attempt_total 2889
telemt_upstream_connect_success_total 2875
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 2889
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1528
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1326
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 71
telemt_me_reconnect_attempts_total 1983
telemt_me_reconnect_success_total 1966
telemt_me_reader_eof_total 1963
telemt_me_idle_close_by_peer_total 1962
telemt_me_route_drop_no_conn_total 1651637
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1508857
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4940
telemt_desync_full_logged_total 1581
telemt_desync_suppressed_total 3359
telemt_desync_frames_bucket_total{bucket="1_2"} 863
telemt_desync_frames_bucket_total{bucket="3_10"} 1963
telemt_desync_frames_bucket_total{bucket="gt_10"} 2114
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 1915
telemt_me_writer_restored_same_endpoint_total 1964
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 2874
telemt_user_connections_total{user="hello"} 1504019
telemt_user_connections_current{user="hello"} 4198
telemt_user_octets_from_client{user="hello"} 21764384776 (20.27 GB)
telemt_user_octets_to_client{user="hello"} 471493924092 (439.11 GB)
telemt_user_unique_ips_current{user="hello"} 1253
telemt_user_unique_ips_recent_window{user="hello"} 552
```

## koara.io

```
telemt 3.3.22

telemt_uptime_seconds 17841.3 (4h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1324740
telemt_connections_bad_total 114827
telemt_connections_current 3605
telemt_connections_me_current 3605
telemt_handshake_timeouts_total 27314
telemt_upstream_connect_attempt_total 2474
telemt_upstream_connect_success_total 2461
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 2474
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1294
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1152
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 29
telemt_me_reconnect_attempts_total 1568
telemt_me_reconnect_success_total 1553
telemt_me_reader_eof_total 1650
telemt_me_idle_close_by_peer_total 1650
telemt_me_route_drop_no_conn_total 542608
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1052639
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5006
telemt_desync_full_logged_total 1538
telemt_desync_suppressed_total 3468
telemt_desync_frames_bucket_total{bucket="1_2"} 1248
telemt_desync_frames_bucket_total{bucket="3_10"} 1897
telemt_desync_frames_bucket_total{bucket="gt_10"} 1861
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 1597
telemt_me_writer_restored_same_endpoint_total 1536
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 652
telemt_me_writer_removed_unexpected_minus_restored_total 44
telemt_user_connections_total{user="hello"} 1051928
telemt_user_connections_current{user="hello"} 3605
telemt_user_octets_from_client{user="hello"} 23246128940 (21.65 GB)
telemt_user_octets_to_client{user="hello"} 483907783352 (450.67 GB)
telemt_user_unique_ips_current{user="hello"} 1119
telemt_user_unique_ips_recent_window{user="hello"} 436
```

## landvps.ru

```
telemt 3.3.22

telemt_uptime_seconds 18555.8 (5h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1952216
telemt_connections_bad_total 44899
telemt_connections_current 3047
telemt_connections_me_current 3047
telemt_handshake_timeouts_total 19904
telemt_upstream_connect_attempt_total 2787
telemt_upstream_connect_success_total 2766
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 2787
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1429
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1307
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 18
telemt_me_reconnect_attempts_total 1826
telemt_me_reconnect_success_total 1804
telemt_me_reader_eof_total 1864
telemt_me_idle_close_by_peer_total 1863
telemt_me_route_drop_no_conn_total 3430856
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1751255
telemt_me_writer_pick_total{mode="p2c",result="full"} 30
telemt_me_writer_pick_total{mode="p2c",result="closed"} 61
telemt_me_endpoint_quarantine_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6438
telemt_desync_full_logged_total 1590
telemt_desync_suppressed_total 4848
telemt_desync_frames_bucket_total{bucket="1_2"} 1440
telemt_desync_frames_bucket_total{bucket="3_10"} 3055
telemt_desync_frames_bucket_total{bucket="gt_10"} 1943
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 1811
telemt_me_writer_restored_same_endpoint_total 1793
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 1000
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 1751178
telemt_user_connections_current{user="hello"} 3047
telemt_user_octets_from_client{user="hello"} 15862222080 (14.77 GB)
telemt_user_octets_to_client{user="hello"} 273400839240 (254.62 GB)
telemt_user_unique_ips_current{user="hello"} 911
telemt_user_unique_ips_recent_window{user="hello"} 392
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 13070.6 (3h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 965800
telemt_connections_bad_total 167346
telemt_handshake_timeouts_total 8927
telemt_upstream_connect_attempt_total 2278
telemt_upstream_connect_success_total 2204
telemt_upstream_connect_fail_total 73
telemt_upstream_connect_attempts_per_request{bucket="1"} 2277
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1159
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1017
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 73
telemt_me_keepalive_timeout_total 52
telemt_me_reconnect_attempts_total 3614
telemt_me_reconnect_success_total 1518
telemt_me_reader_eof_total 1619
telemt_me_idle_close_by_peer_total 1619
telemt_me_route_drop_no_conn_total 416298
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 714486
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2506
telemt_desync_full_logged_total 867
telemt_desync_suppressed_total 1639
telemt_desync_frames_bucket_total{bucket="1_2"} 474
telemt_desync_frames_bucket_total{bucket="3_10"} 861
telemt_desync_frames_bucket_total{bucket="gt_10"} 1171
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1608
telemt_me_refill_failed_total 65
telemt_me_writer_restored_same_endpoint_total 1492
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 786
telemt_me_writer_removed_unexpected_minus_restored_total 90
telemt_user_connections_total{user="hello"} 713912
telemt_user_connections_current{user="hello"} 3295
telemt_user_octets_from_client{user="hello"} 12349275764 (11.50 GB)
telemt_user_octets_to_client{user="hello"} 319806616040 (297.84 GB)
telemt_user_unique_ips_current{user="hello"} 1096
telemt_user_unique_ips_recent_window{user="hello"} 420
```

## hostvds.com

```
telemt 3.3.22

telemt_uptime_seconds 18004.6 (5h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 307531
telemt_connections_bad_total 10459
telemt_connections_current 758
telemt_connections_me_current 758
telemt_relay_adaptive_promotions_total 18
telemt_relay_adaptive_hard_promotions_total 18
telemt_handshake_timeouts_total 3238
telemt_upstream_connect_attempt_total 7145
telemt_upstream_connect_success_total 7123
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 7145
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3681
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3371
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 51
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_reconnect_attempts_total 331857
telemt_me_reconnect_success_total 2388
telemt_me_reader_eof_total 2410
telemt_me_idle_close_by_peer_total 2410
telemt_me_route_drop_no_conn_total 192896
telemt_me_route_drop_channel_closed_total 91
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 273947
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 9
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 535
telemt_desync_full_logged_total 198
telemt_desync_suppressed_total 337
telemt_desync_frames_bucket_total{bucket="1_2"} 105
telemt_desync_frames_bucket_total{bucket="3_10"} 215
telemt_desync_frames_bucket_total{bucket="gt_10"} 215
telemt_pool_swap_total 15
telemt_pool_stale_pick_total 980
telemt_me_writer_removed_unexpected_total 2340
telemt_me_refill_failed_total 10448
telemt_me_writer_restored_same_endpoint_total 2377
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 40876
telemt_user_connections_total{user="hello"} 277638
telemt_user_connections_current{user="hello"} 758
telemt_user_octets_from_client{user="hello"} 3830036789 (3.57 GB)
telemt_user_octets_to_client{user="hello"} 58451356169 (54.44 GB)
telemt_user_msgs_from_client{user="hello"} 38712
telemt_user_msgs_to_client{user="hello"} 31668
telemt_user_unique_ips_current{user="hello"} 248
telemt_user_unique_ips_recent_window{user="hello"} 112
```

## 4vps.su

```
telemt 3.3.22

telemt_uptime_seconds 17075.2 (4h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1030333
telemt_connections_bad_total 76227
telemt_connections_current 3437
telemt_connections_me_current 3437
telemt_handshake_timeouts_total 19562
telemt_upstream_connect_attempt_total 2847
telemt_upstream_connect_success_total 2846
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 2847
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1530
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1296
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 17495
telemt_me_reconnect_success_total 1977
telemt_me_reader_eof_total 1994
telemt_me_idle_close_by_peer_total 1994
telemt_me_route_drop_no_conn_total 492687
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="base"} 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 861128
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3566
telemt_desync_full_logged_total 1208
telemt_desync_suppressed_total 2358
telemt_desync_frames_bucket_total{bucket="1_2"} 834
telemt_desync_frames_bucket_total{bucket="3_10"} 1245
telemt_desync_frames_bucket_total{bucket="gt_10"} 1487
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 1949
telemt_me_refill_failed_total 741
telemt_me_writer_restored_same_endpoint_total 1916
telemt_me_writer_restored_fallback_total 61
telemt_me_async_recovery_trigger_total 9552
telemt_user_connections_total{user="hello"} 860068
telemt_user_connections_current{user="hello"} 3437
telemt_user_octets_from_client{user="hello"} 17048004152 (15.88 GB)
telemt_user_octets_to_client{user="hello"} 475439081628 (442.79 GB)
telemt_user_unique_ips_current{user="hello"} 988
telemt_user_unique_ips_recent_window{user="hello"} 442
```