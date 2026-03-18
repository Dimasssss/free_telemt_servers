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

# Server Metrics 2026-03-18 05:41:37 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 125779.8 (34h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1491050
telemt_connections_bad_total 10585
telemt_handshake_timeouts_total 35425
telemt_upstream_connect_attempt_total 27374
telemt_upstream_connect_success_total 26856
telemt_upstream_connect_fail_total 518
telemt_upstream_connect_attempts_per_request{bucket="1"} 27374
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13757
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12891
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 518
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 267
telemt_me_reconnect_attempts_total 35469
telemt_me_reconnect_success_total 18319
telemt_me_reader_eof_total 19867
telemt_me_idle_close_by_peer_total 19866
telemt_me_route_drop_no_conn_total 613286
telemt_me_route_drop_channel_closed_total 167
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1331577
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8147
telemt_desync_full_logged_total 2449
telemt_desync_suppressed_total 5698
telemt_desync_frames_bucket_total{bucket="1_2"} 2135
telemt_desync_frames_bucket_total{bucket="3_10"} 3134
telemt_desync_frames_bucket_total{bucket="gt_10"} 2878
telemt_pool_swap_total 108
telemt_me_writer_removed_unexpected_total 19129
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 18297
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 810
telemt_user_connections_total{user="hello"} 1325805
telemt_user_connections_current{user="hello"} 895
telemt_user_octets_from_client{user="hello"} 31915836535 (29.72 GB)
telemt_user_octets_to_client{user="hello"} 475033739095 (442.41 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 363
telemt_user_unique_ips_recent_window{user="hello"} 139
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 126031.5 (35h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1602318
telemt_connections_bad_total 76089
telemt_handshake_timeouts_total 52666
telemt_upstream_connect_attempt_total 470802
telemt_upstream_connect_success_total 469176
telemt_upstream_connect_fail_total 1626
telemt_upstream_connect_attempts_per_request{bucket="1"} 470802
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 391077
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34731
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43366
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1626
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 343
telemt_me_reconnect_attempts_total 126733
telemt_me_reconnect_success_total 20003
telemt_me_reader_eof_total 22296
telemt_me_idle_close_by_peer_total 22283
telemt_me_route_drop_no_conn_total 421319
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 954295
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4292
telemt_desync_full_logged_total 1491
telemt_desync_suppressed_total 2801
telemt_desync_frames_bucket_total{bucket="1_2"} 845
telemt_desync_frames_bucket_total{bucket="3_10"} 1740
telemt_desync_frames_bucket_total{bucket="gt_10"} 1707
telemt_pool_swap_total 73
telemt_me_writer_removed_unexpected_total 21631
telemt_me_refill_failed_total 3329
telemt_me_writer_restored_same_endpoint_total 19985
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 6668
telemt_me_writer_removed_unexpected_minus_restored_total 1628
telemt_user_connections_total{user="hello"} 1396643
telemt_user_connections_current{user="hello"} 1550
telemt_user_octets_from_client{user="hello"} 19285675437 (17.96 GB)
telemt_user_octets_to_client{user="hello"} 534374496354 (497.68 GB)
telemt_user_msgs_from_client{user="hello"} 7472583
telemt_user_msgs_to_client{user="hello"} 31958899
telemt_user_unique_ips_current{user="hello"} 562
telemt_user_unique_ips_recent_window{user="hello"} 225
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 125807.7 (34h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1078365
telemt_connections_bad_total 73708
telemt_handshake_timeouts_total 28944
telemt_upstream_connect_attempt_total 28734
telemt_upstream_connect_success_total 28572
telemt_upstream_connect_fail_total 162
telemt_upstream_connect_attempts_per_request{bucket="1"} 28734
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13114
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15356
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 97
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 162
telemt_me_keepalive_timeout_total 124
telemt_me_reconnect_attempts_total 42981
telemt_me_reconnect_success_total 22278
telemt_me_reader_eof_total 24210
telemt_me_idle_close_by_peer_total 24203
telemt_me_route_drop_no_conn_total 380919
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 845258
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2862
telemt_desync_full_logged_total 935
telemt_desync_suppressed_total 1927
telemt_desync_frames_bucket_total{bucket="1_2"} 785
telemt_desync_frames_bucket_total{bucket="3_10"} 1114
telemt_desync_frames_bucket_total{bucket="gt_10"} 963
telemt_pool_swap_total 105
telemt_me_writer_removed_unexpected_total 23223
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 22266
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 945
telemt_user_connections_total{user="hello"} 843362
telemt_user_connections_current{user="hello"} 1316
telemt_user_octets_from_client{user="hello"} 46221170976 (43.05 GB)
telemt_user_octets_to_client{user="hello"} 408423306112 (380.37 GB)
telemt_user_unique_ips_current{user="hello"} 406
telemt_user_unique_ips_recent_window{user="hello"} 159
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 125866.9 (34h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1492773
telemt_connections_bad_total 73723
telemt_handshake_timeouts_total 25875
telemt_upstream_connect_attempt_total 91739
telemt_upstream_connect_success_total 89292
telemt_upstream_connect_fail_total 2447
telemt_upstream_connect_attempts_per_request{bucket="1"} 91739
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 73843
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15037
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 379
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2447
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 320
telemt_me_reconnect_attempts_total 38695
telemt_me_reconnect_success_total 18277
telemt_me_reader_eof_total 20051
telemt_me_idle_close_by_peer_total 20048
telemt_me_route_drop_no_conn_total 600262
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1218432
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4713
telemt_desync_full_logged_total 1535
telemt_desync_suppressed_total 3178
telemt_desync_frames_bucket_total{bucket="1_2"} 1120
telemt_desync_frames_bucket_total{bucket="3_10"} 1972
telemt_desync_frames_bucket_total{bucket="gt_10"} 1621
telemt_pool_swap_total 100
telemt_me_writer_removed_unexpected_total 19254
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 18257
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 977
telemt_user_connections_total{user="hello"} 1281707
telemt_user_connections_current{user="hello"} 1551
telemt_user_octets_from_client{user="hello"} 20965100390 (19.53 GB)
telemt_user_octets_to_client{user="hello"} 627250673218 (584.17 GB)
telemt_user_msgs_from_client{user="hello"} 744103
telemt_user_msgs_to_client{user="hello"} 5214294
telemt_user_unique_ips_current{user="hello"} 492
telemt_user_unique_ips_recent_window{user="hello"} 178
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 125838.8 (34h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1050673
telemt_connections_bad_total 105583
telemt_handshake_timeouts_total 10237
telemt_upstream_connect_attempt_total 48731
telemt_upstream_connect_success_total 48059
telemt_upstream_connect_fail_total 672
telemt_upstream_connect_attempts_per_request{bucket="1"} 48731
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29667
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17968
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 424
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 672
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 60300
telemt_me_reconnect_success_total 25332
telemt_me_reader_eof_total 27401
telemt_me_idle_close_by_peer_total 27398
telemt_me_route_drop_no_conn_total 338106
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 860987
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3748
telemt_desync_full_logged_total 1152
telemt_desync_suppressed_total 2596
telemt_desync_frames_bucket_total{bucket="1_2"} 1090
telemt_desync_frames_bucket_total{bucket="3_10"} 1452
telemt_desync_frames_bucket_total{bucket="gt_10"} 1206
telemt_pool_swap_total 67
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 26815
telemt_me_refill_failed_total 1087
telemt_me_writer_restored_same_endpoint_total 25324
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1483
telemt_user_connections_total{user="hello"} 877456
telemt_user_connections_current{user="hello"} 1578
telemt_user_octets_from_client{user="hello"} 16714732232 (15.57 GB)
telemt_user_octets_to_client{user="hello"} 441216330704 (410.91 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 508
telemt_user_unique_ips_recent_window{user="hello"} 213
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 126000.0 (35h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1210603
telemt_connections_bad_total 127712
telemt_handshake_timeouts_total 10528
telemt_upstream_connect_attempt_total 25034
telemt_upstream_connect_success_total 24887
telemt_upstream_connect_fail_total 147
telemt_upstream_connect_attempts_per_request{bucket="1"} 25034
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11948
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12820
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 147
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 29944
telemt_me_reconnect_success_total 18649
telemt_me_reader_eof_total 20203
telemt_me_idle_close_by_peer_total 20201
telemt_me_route_drop_no_conn_total 826031
telemt_me_route_drop_channel_closed_total 90
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1189178
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2263
telemt_desync_full_logged_total 791
telemt_desync_suppressed_total 1472
telemt_desync_frames_bucket_total{bucket="1_2"} 505
telemt_desync_frames_bucket_total{bucket="3_10"} 860
telemt_desync_frames_bucket_total{bucket="gt_10"} 898
telemt_pool_swap_total 114
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 19287
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 18635
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 298
telemt_me_writer_removed_unexpected_minus_restored_total 638
telemt_user_connections_total{user="hello"} 997859
telemt_user_connections_current{user="hello"} 748
telemt_user_octets_from_client{user="hello"} 15829892068 (14.74 GB)
telemt_user_octets_to_client{user="hello"} 444727823636 (414.19 GB)
telemt_user_unique_ips_current{user="hello"} 254
telemt_user_unique_ips_recent_window{user="hello"} 95
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 73767.1 (20h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 568544
telemt_connections_bad_total 54654
telemt_handshake_timeouts_total 13521
telemt_upstream_connect_attempt_total 25639
telemt_upstream_connect_success_total 25373
telemt_upstream_connect_fail_total 266
telemt_upstream_connect_attempts_per_request{bucket="1"} 25639
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13561
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11716
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 266
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 33188
telemt_me_reconnect_success_total 21573
telemt_me_reader_eof_total 22796
telemt_me_idle_close_by_peer_total 22796
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 140046
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 413960
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 37
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1807
telemt_desync_full_logged_total 602
telemt_desync_suppressed_total 1205
telemt_desync_frames_bucket_total{bucket="1_2"} 297
telemt_desync_frames_bucket_total{bucket="3_10"} 807
telemt_desync_frames_bucket_total{bucket="gt_10"} 703
telemt_pool_swap_total 51
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 22164
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 21530
telemt_me_writer_restored_fallback_total 43
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 591
telemt_user_connections_total{user="hello"} 413714
telemt_user_connections_current{user="hello"} 1075
telemt_user_octets_from_client{user="hello"} 26185472013 (24.39 GB)
telemt_user_octets_to_client{user="hello"} 325266677818 (302.93 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 333
telemt_user_unique_ips_recent_window{user="hello"} 146
```