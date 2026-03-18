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

# Server Metrics 2026-03-18 16:24:32 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 3549.2 (0h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 117549
telemt_connections_bad_total 10225
telemt_handshake_timeouts_total 4309
telemt_upstream_connect_attempt_total 461
telemt_upstream_connect_success_total 461
telemt_upstream_connect_attempts_per_request{bucket="1"} 461
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 222
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 227
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 262
telemt_me_reconnect_success_total 261
telemt_me_reader_eof_total 258
telemt_me_idle_close_by_peer_total 258
telemt_me_route_drop_no_conn_total 71759
telemt_me_route_drop_channel_closed_total 24
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 95526
telemt_me_writer_pick_total{mode="p2c",result="full"} 116
telemt_me_writer_pick_total{mode="p2c",result="closed"} 293
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 574
telemt_desync_full_logged_total 155
telemt_desync_suppressed_total 419
telemt_desync_frames_bucket_total{bucket="1_2"} 151
telemt_desync_frames_bucket_total{bucket="3_10"} 180
telemt_desync_frames_bucket_total{bucket="gt_10"} 243
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 271
telemt_me_writer_restored_same_endpoint_total 250
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 75
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 95492
telemt_user_connections_current{user="hello"} 1389
telemt_user_octets_from_client{user="hello"} 1270240732 (1.18 GB)
telemt_user_octets_to_client{user="hello"} 32184995904 (29.97 GB)
telemt_user_unique_ips_current{user="hello"} 485
telemt_user_unique_ips_recent_window{user="hello"} 181
```

## psb.hosting

```
telemt 3.3.22

telemt_uptime_seconds 8377.6 (2h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 886321
telemt_connections_bad_total 57756
telemt_connections_current 3586
telemt_connections_me_current 3586
telemt_handshake_timeouts_total 14313
telemt_upstream_connect_attempt_total 1607
telemt_upstream_connect_success_total 1598
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 1607
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 888
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 700
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_reconnect_attempts_total 1136
telemt_me_reconnect_success_total 1126
telemt_me_reader_eof_total 1065
telemt_me_idle_close_by_peer_total 1064
telemt_me_route_drop_no_conn_total 922830
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 771129
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2121
telemt_desync_full_logged_total 663
telemt_desync_suppressed_total 1458
telemt_desync_frames_bucket_total{bucket="1_2"} 425
telemt_desync_frames_bucket_total{bucket="3_10"} 859
telemt_desync_frames_bucket_total{bucket="gt_10"} 837
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 1056
telemt_me_writer_restored_same_endpoint_total 1124
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 2874
telemt_user_connections_total{user="hello"} 770304
telemt_user_connections_current{user="hello"} 3586
telemt_user_octets_from_client{user="hello"} 7997270504 (7.45 GB)
telemt_user_octets_to_client{user="hello"} 213028967544 (198.40 GB)
telemt_user_unique_ips_current{user="hello"} 1139
telemt_user_unique_ips_recent_window{user="hello"} 447
```

## koara.io

```
telemt 3.3.22

telemt_uptime_seconds 8306.3 (2h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 586576
telemt_connections_bad_total 39576
telemt_connections_current 2957
telemt_connections_me_current 2957
telemt_handshake_timeouts_total 12467
telemt_upstream_connect_attempt_total 1219
telemt_upstream_connect_success_total 1214
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 1219
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 645
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 562
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_reconnect_attempts_total 751
telemt_me_reconnect_success_total 741
telemt_me_reader_eof_total 775
telemt_me_idle_close_by_peer_total 775
telemt_me_route_drop_no_conn_total 310754
telemt_me_route_drop_channel_closed_total 27
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 496725
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1868
telemt_desync_full_logged_total 552
telemt_desync_suppressed_total 1316
telemt_desync_frames_bucket_total{bucket="1_2"} 422
telemt_desync_frames_bucket_total{bucket="3_10"} 709
telemt_desync_frames_bucket_total{bucket="gt_10"} 737
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 763
telemt_me_writer_restored_same_endpoint_total 724
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 652
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 496441
telemt_user_connections_current{user="hello"} 2957
telemt_user_octets_from_client{user="hello"} 9373867708 (8.73 GB)
telemt_user_octets_to_client{user="hello"} 195025401124 (181.63 GB)
telemt_user_unique_ips_current{user="hello"} 973
telemt_user_unique_ips_recent_window{user="hello"} 379
```

## landvps.ru

```
telemt 3.3.22

telemt_uptime_seconds 9020.2 (2h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 784624
telemt_connections_bad_total 13136
telemt_connections_current 2703
telemt_connections_me_current 2703
telemt_handshake_timeouts_total 11001
telemt_upstream_connect_attempt_total 1449
telemt_upstream_connect_success_total 1438
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 1449
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 747
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 683
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 970
telemt_me_reconnect_success_total 961
telemt_me_reader_eof_total 962
telemt_me_idle_close_by_peer_total 961
telemt_me_route_drop_no_conn_total 1220733
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 709511
telemt_me_writer_pick_total{mode="p2c",result="full"} 30
telemt_me_writer_pick_total{mode="p2c",result="closed"} 61
telemt_me_endpoint_quarantine_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2810
telemt_desync_full_logged_total 717
telemt_desync_suppressed_total 2093
telemt_desync_frames_bucket_total{bucket="1_2"} 610
telemt_desync_frames_bucket_total{bucket="3_10"} 1277
telemt_desync_frames_bucket_total{bucket="gt_10"} 923
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 950
telemt_me_writer_restored_same_endpoint_total 950
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 1000
telemt_user_connections_total{user="hello"} 709491
telemt_user_connections_current{user="hello"} 2703
telemt_user_octets_from_client{user="hello"} 5616930028 (5.23 GB)
telemt_user_octets_to_client{user="hello"} 139577250740 (129.99 GB)
telemt_user_unique_ips_current{user="hello"} 834
telemt_user_unique_ips_recent_window{user="hello"} 414
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 3535.0 (0h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 281886
telemt_connections_bad_total 54406
telemt_handshake_timeouts_total 3142
telemt_upstream_connect_attempt_total 641
telemt_upstream_connect_success_total 623
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 641
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 361
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 258
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 426
telemt_me_reconnect_success_total 421
telemt_me_reader_eof_total 394
telemt_me_idle_close_by_peer_total 394
telemt_me_route_drop_no_conn_total 125808
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 203049
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 700
telemt_desync_full_logged_total 243
telemt_desync_suppressed_total 457
telemt_desync_frames_bucket_total{bucket="1_2"} 118
telemt_desync_frames_bucket_total{bucket="3_10"} 219
telemt_desync_frames_bucket_total{bucket="gt_10"} 363
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 417
telemt_me_writer_restored_same_endpoint_total 395
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 786
telemt_user_connections_total{user="hello"} 202768
telemt_user_connections_current{user="hello"} 2917
telemt_user_octets_from_client{user="hello"} 3101752100 (2.89 GB)
telemt_user_octets_to_client{user="hello"} 75650137372 (70.45 GB)
telemt_user_unique_ips_current{user="hello"} 1002
telemt_user_unique_ips_recent_window{user="hello"} 383
```

## hostvds.com

```
telemt 3.3.22

telemt_uptime_seconds 8471.0 (2h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 163017
telemt_connections_bad_total 6488
telemt_connections_current 913
telemt_connections_me_current 913
telemt_relay_adaptive_promotions_total 18
telemt_relay_adaptive_hard_promotions_total 18
telemt_handshake_timeouts_total 1429
telemt_upstream_connect_attempt_total 5702
telemt_upstream_connect_success_total 5691
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 5702
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3148
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2501
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_reconnect_attempts_total 330856
telemt_me_reconnect_success_total 1396
telemt_me_reader_eof_total 1344
telemt_me_idle_close_by_peer_total 1344
telemt_me_route_drop_no_conn_total 90900
telemt_me_route_drop_channel_closed_total 28
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 143711
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 9
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 326
telemt_desync_full_logged_total 116
telemt_desync_suppressed_total 210
telemt_desync_frames_bucket_total{bucket="1_2"} 55
telemt_desync_frames_bucket_total{bucket="3_10"} 130
telemt_desync_frames_bucket_total{bucket="gt_10"} 141
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 1327
telemt_me_refill_failed_total 10448
telemt_me_writer_restored_same_endpoint_total 1385
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 40876
telemt_user_connections_total{user="hello"} 147440
telemt_user_connections_current{user="hello"} 913
telemt_user_octets_from_client{user="hello"} 2267216185 (2.11 GB)
telemt_user_octets_to_client{user="hello"} 31773352037 (29.59 GB)
telemt_user_msgs_from_client{user="hello"} 38712
telemt_user_msgs_to_client{user="hello"} 31668
telemt_user_unique_ips_current{user="hello"} 310
telemt_user_unique_ips_recent_window{user="hello"} 135
```

## 4vps.su

```
telemt 3.3.22

telemt_uptime_seconds 7539.5 (2h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 465615
telemt_connections_bad_total 17525
telemt_connections_current 2473
telemt_connections_me_current 2473
telemt_handshake_timeouts_total 7159
telemt_upstream_connect_attempt_total 1471
telemt_upstream_connect_success_total 1471
telemt_upstream_connect_attempts_per_request{bucket="1"} 1471
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 799
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 666
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_reconnect_attempts_total 16552
telemt_me_reconnect_success_total 1042
telemt_me_reader_eof_total 997
telemt_me_idle_close_by_peer_total 997
telemt_me_route_drop_no_conn_total 305112
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="base"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 401757
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1141
telemt_desync_full_logged_total 427
telemt_desync_suppressed_total 714
telemt_desync_frames_bucket_total{bucket="1_2"} 240
telemt_desync_frames_bucket_total{bucket="3_10"} 391
telemt_desync_frames_bucket_total{bucket="gt_10"} 510
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 998
telemt_me_refill_failed_total 741
telemt_me_writer_restored_same_endpoint_total 981
telemt_me_writer_restored_fallback_total 61
telemt_me_async_recovery_trigger_total 9552
telemt_user_connections_total{user="hello"} 402022
telemt_user_connections_current{user="hello"} 2473
telemt_user_octets_from_client{user="hello"} 6512106312 (6.06 GB)
telemt_user_octets_to_client{user="hello"} 172265793960 (160.44 GB)
telemt_user_unique_ips_current{user="hello"} 819
telemt_user_unique_ips_recent_window{user="hello"} 339
```