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

# Server Metrics 2026-03-18 17:31:15 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 7550.8 (2h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 224028
telemt_connections_bad_total 14892
telemt_handshake_timeouts_total 5830
telemt_upstream_connect_attempt_total 1224
telemt_upstream_connect_success_total 1224
telemt_upstream_connect_attempts_per_request{bucket="1"} 1224
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 612
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 586
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 810
telemt_me_reconnect_success_total 808
telemt_me_reader_eof_total 830
telemt_me_idle_close_by_peer_total 830
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 106010
telemt_me_route_drop_channel_closed_total 43
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 188681
telemt_me_writer_pick_total{mode="p2c",result="full"} 116
telemt_me_writer_pick_total{mode="p2c",result="closed"} 293
telemt_me_endpoint_quarantine_total 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1037
telemt_desync_full_logged_total 318
telemt_desync_suppressed_total 719
telemt_desync_frames_bucket_total{bucket="1_2"} 249
telemt_desync_frames_bucket_total{bucket="3_10"} 344
telemt_desync_frames_bucket_total{bucket="gt_10"} 444
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 828
telemt_me_writer_restored_same_endpoint_total 795
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 75
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 188597
telemt_user_connections_current{user="hello"} 1363
telemt_user_octets_from_client{user="hello"} 2658937748 (2.48 GB)
telemt_user_octets_to_client{user="hello"} 63683827360 (59.31 GB)
telemt_user_unique_ips_current{user="hello"} 462
telemt_user_unique_ips_recent_window{user="hello"} 179
```

## psb.hosting

```
telemt 3.3.22

telemt_uptime_seconds 12378.7 (3h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1270043
telemt_connections_bad_total 76555
telemt_connections_current 3731
telemt_connections_me_current 3731
telemt_handshake_timeouts_total 25480
telemt_upstream_connect_attempt_total 2177
telemt_upstream_connect_success_total 2166
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 2177
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1172
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 975
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 56
telemt_me_reconnect_attempts_total 1532
telemt_me_reconnect_success_total 1518
telemt_me_reader_eof_total 1479
telemt_me_idle_close_by_peer_total 1478
telemt_me_route_drop_no_conn_total 1236131
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1101917
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3162
telemt_desync_full_logged_total 1019
telemt_desync_suppressed_total 2143
telemt_desync_frames_bucket_total{bucket="1_2"} 601
telemt_desync_frames_bucket_total{bucket="3_10"} 1252
telemt_desync_frames_bucket_total{bucket="gt_10"} 1309
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 1454
telemt_me_writer_restored_same_endpoint_total 1516
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 2874
telemt_user_connections_total{user="hello"} 1101049
telemt_user_connections_current{user="hello"} 3731
telemt_user_octets_from_client{user="hello"} 14443784684 (13.45 GB)
telemt_user_octets_to_client{user="hello"} 317657412492 (295.84 GB)
telemt_user_unique_ips_current{user="hello"} 1135
telemt_user_unique_ips_recent_window{user="hello"} 663
```

## koara.io

```
telemt 3.3.22

telemt_uptime_seconds 12307.3 (3h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 875120
telemt_connections_bad_total 68324
telemt_connections_current 3255
telemt_connections_me_current 3255
telemt_handshake_timeouts_total 19666
telemt_upstream_connect_attempt_total 1723
telemt_upstream_connect_success_total 1714
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 1723
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 902
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 799
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 29
telemt_me_reconnect_attempts_total 1079
telemt_me_reconnect_success_total 1068
telemt_me_reader_eof_total 1128
telemt_me_idle_close_by_peer_total 1128
telemt_me_route_drop_no_conn_total 406743
telemt_me_route_drop_channel_closed_total 36
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 726801
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2969
telemt_desync_full_logged_total 902
telemt_desync_suppressed_total 2067
telemt_desync_frames_bucket_total{bucket="1_2"} 709
telemt_desync_frames_bucket_total{bucket="3_10"} 1112
telemt_desync_frames_bucket_total{bucket="gt_10"} 1148
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 1102
telemt_me_writer_restored_same_endpoint_total 1051
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 652
telemt_me_writer_removed_unexpected_minus_restored_total 34
telemt_user_connections_total{user="hello"} 726441
telemt_user_connections_current{user="hello"} 3255
telemt_user_octets_from_client{user="hello"} 14291592652 (13.31 GB)
telemt_user_octets_to_client{user="hello"} 309865094300 (288.58 GB)
telemt_user_unique_ips_current{user="hello"} 1022
telemt_user_unique_ips_recent_window{user="hello"} 451
```

## landvps.ru

```
telemt 3.3.22

telemt_uptime_seconds 13021.9 (3h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1288375
telemt_connections_bad_total 26942
telemt_connections_current 2935
telemt_connections_me_current 2935
telemt_handshake_timeouts_total 15344
telemt_upstream_connect_attempt_total 2034
telemt_upstream_connect_success_total 2020
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 2034
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1039
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 959
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 18
telemt_me_reconnect_attempts_total 1338
telemt_me_reconnect_success_total 1321
telemt_me_reader_eof_total 1350
telemt_me_idle_close_by_peer_total 1349
telemt_me_route_drop_no_conn_total 2172750
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1155453
telemt_me_writer_pick_total{mode="p2c",result="full"} 30
telemt_me_writer_pick_total{mode="p2c",result="closed"} 61
telemt_me_endpoint_quarantine_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4279
telemt_desync_full_logged_total 1090
telemt_desync_suppressed_total 3189
telemt_desync_frames_bucket_total{bucket="1_2"} 1004
telemt_desync_frames_bucket_total{bucket="3_10"} 1949
telemt_desync_frames_bucket_total{bucket="gt_10"} 1326
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 1319
telemt_me_writer_restored_same_endpoint_total 1310
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 1000
telemt_user_connections_total{user="hello"} 1155381
telemt_user_connections_current{user="hello"} 2935
telemt_user_octets_from_client{user="hello"} 9947168632 (9.26 GB)
telemt_user_octets_to_client{user="hello"} 196071981664 (182.61 GB)
telemt_user_unique_ips_current{user="hello"} 881
telemt_user_unique_ips_recent_window{user="hello"} 439
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 7536.8 (2h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 566251
telemt_connections_bad_total 100253
telemt_handshake_timeouts_total 5393
telemt_upstream_connect_attempt_total 1373
telemt_upstream_connect_success_total 1330
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 1373
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 701
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 618
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_timeout_total 31
telemt_me_reconnect_attempts_total 1910
telemt_me_reconnect_success_total 910
telemt_me_reader_eof_total 940
telemt_me_idle_close_by_peer_total 940
telemt_me_route_drop_no_conn_total 232059
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 418147
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1649
telemt_desync_full_logged_total 548
telemt_desync_suppressed_total 1101
telemt_desync_frames_bucket_total{bucket="1_2"} 299
telemt_desync_frames_bucket_total{bucket="3_10"} 551
telemt_desync_frames_bucket_total{bucket="gt_10"} 799
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 950
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 884
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 786
telemt_me_writer_removed_unexpected_minus_restored_total 40
telemt_user_connections_total{user="hello"} 417673
telemt_user_connections_current{user="hello"} 3218
telemt_user_octets_from_client{user="hello"} 6687186024 (6.23 GB)
telemt_user_octets_to_client{user="hello"} 176198747540 (164.10 GB)
telemt_user_unique_ips_current{user="hello"} 1072
telemt_user_unique_ips_recent_window{user="hello"} 442
```

## hostvds.com

```
telemt 3.3.22

telemt_uptime_seconds 12474.1 (3h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 225297
telemt_connections_bad_total 7786
telemt_connections_current 984
telemt_connections_me_current 984
telemt_relay_adaptive_promotions_total 18
telemt_relay_adaptive_hard_promotions_total 18
telemt_handshake_timeouts_total 2470
telemt_upstream_connect_attempt_total 6281
telemt_upstream_connect_success_total 6268
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 6281
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3364
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2852
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 36
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_reconnect_attempts_total 331260
telemt_me_reconnect_success_total 1795
telemt_me_reader_eof_total 1774
telemt_me_idle_close_by_peer_total 1774
telemt_me_route_drop_no_conn_total 133578
telemt_me_route_drop_channel_closed_total 59
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 200365
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 9
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 407
telemt_desync_full_logged_total 146
telemt_desync_suppressed_total 261
telemt_desync_frames_bucket_total{bucket="1_2"} 71
telemt_desync_frames_bucket_total{bucket="3_10"} 168
telemt_desync_frames_bucket_total{bucket="gt_10"} 168
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 1735
telemt_me_refill_failed_total 10448
telemt_me_writer_restored_same_endpoint_total 1784
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 40876
telemt_user_connections_total{user="hello"} 204087
telemt_user_connections_current{user="hello"} 984
telemt_user_octets_from_client{user="hello"} 2984844413 (2.78 GB)
telemt_user_octets_to_client{user="hello"} 42878160541 (39.93 GB)
telemt_user_msgs_from_client{user="hello"} 38712
telemt_user_msgs_to_client{user="hello"} 31668
telemt_user_unique_ips_current{user="hello"} 316
telemt_user_unique_ips_recent_window{user="hello"} 154
```

## 4vps.su

```
telemt 3.3.22

telemt_uptime_seconds 11541.0 (3h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 704938
telemt_connections_bad_total 49329
telemt_connections_current 2915
telemt_connections_me_current 2915
telemt_handshake_timeouts_total 13418
telemt_upstream_connect_attempt_total 2034
telemt_upstream_connect_success_total 2033
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 2034
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1121
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 903
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 16942
telemt_me_reconnect_success_total 1428
telemt_me_reader_eof_total 1406
telemt_me_idle_close_by_peer_total 1406
telemt_me_route_drop_no_conn_total 396423
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="base"} 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 590792
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2260
telemt_desync_full_logged_total 773
telemt_desync_suppressed_total 1487
telemt_desync_frames_bucket_total{bucket="1_2"} 559
telemt_desync_frames_bucket_total{bucket="3_10"} 804
telemt_desync_frames_bucket_total{bucket="gt_10"} 897
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 1389
telemt_me_refill_failed_total 741
telemt_me_writer_restored_same_endpoint_total 1367
telemt_me_writer_restored_fallback_total 61
telemt_me_async_recovery_trigger_total 9552
telemt_user_connections_total{user="hello"} 589819
telemt_user_connections_current{user="hello"} 2915
telemt_user_octets_from_client{user="hello"} 11208725200 (10.44 GB)
telemt_user_octets_to_client{user="hello"} 288076524552 (268.29 GB)
telemt_user_unique_ips_current{user="hello"} 902
telemt_user_unique_ips_recent_window{user="hello"} 368
```