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

# Server Metrics 2026-03-18 12:44:30 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.20

telemt_uptime_seconds 14603.7 (4h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 529569
telemt_connections_bad_total 9549
telemt_handshake_timeouts_total 14897
telemt_upstream_connect_attempt_total 65928
telemt_upstream_connect_success_total 64979
telemt_upstream_connect_fail_total 949
telemt_upstream_connect_attempts_per_request{bucket="1"} 65928
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 60437
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3959
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 583
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 949
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 511866
telemt_me_reconnect_success_total 2235
telemt_me_reader_eof_total 2320
telemt_me_idle_close_by_peer_total 2318
telemt_me_route_drop_no_conn_total 317640
telemt_me_route_drop_channel_closed_total 98
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 407629
telemt_me_writer_pick_total{mode="p2c",result="full"} 21
telemt_me_writer_pick_total{mode="p2c",result="closed"} 54
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1753
telemt_desync_full_logged_total 577
telemt_desync_suppressed_total 1176
telemt_desync_frames_bucket_total{bucket="1_2"} 499
telemt_desync_frames_bucket_total{bucket="3_10"} 614
telemt_desync_frames_bucket_total{bucket="gt_10"} 640
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 2335
telemt_me_refill_failed_total 16609
telemt_me_writer_restored_same_endpoint_total 2130
telemt_me_writer_restored_fallback_total 105
telemt_me_async_recovery_trigger_total 11769
telemt_me_writer_removed_unexpected_minus_restored_total 100
telemt_user_connections_total{user="hello"} 465875
telemt_user_connections_current{user="hello"} 1715
telemt_user_octets_from_client{user="hello"} 6355490068 (5.92 GB)
telemt_user_octets_to_client{user="hello"} 120424512613 (112.15 GB)
telemt_user_msgs_from_client{user="hello"} 846607
telemt_user_msgs_to_client{user="hello"} 1165163
telemt_user_unique_ips_current{user="hello"} 562
telemt_user_unique_ips_recent_window{user="hello"} 248
```

## psb.hosting

```
telemt 3.3.20

telemt_uptime_seconds 14634.7 (4h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1455335
telemt_connections_bad_total 108138
telemt_handshake_timeouts_total 32605
telemt_upstream_connect_attempt_total 2623
telemt_upstream_connect_success_total 2611
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 2623
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1402
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1193
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 2926
telemt_me_reconnect_success_total 1789
telemt_me_reader_eof_total 1850
telemt_me_idle_close_by_peer_total 1849
telemt_me_route_drop_no_conn_total 1242636
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1247695
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3937
telemt_desync_full_logged_total 1193
telemt_desync_suppressed_total 2744
telemt_desync_frames_bucket_total{bucket="1_2"} 775
telemt_desync_frames_bucket_total{bucket="3_10"} 1586
telemt_desync_frames_bucket_total{bucket="gt_10"} 1576
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 1832
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 1788
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 1068
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 1246729
telemt_user_connections_current{user="hello"} 4097
telemt_user_octets_from_client{user="hello"} 31048471488 (28.92 GB)
telemt_user_octets_to_client{user="hello"} 366963190208 (341.76 GB)
telemt_user_unique_ips_current{user="hello"} 1258
telemt_user_unique_ips_recent_window{user="hello"} 592
```

## koara.io

```
telemt 3.3.20

telemt_uptime_seconds 14549.4 (4h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1035616
telemt_connections_bad_total 75110
telemt_handshake_timeouts_total 25139
telemt_upstream_connect_attempt_total 10986
telemt_upstream_connect_success_total 10986
telemt_upstream_connect_attempts_per_request{bucket="1"} 10986
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8389
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2586
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 607671
telemt_me_reconnect_success_total 1976
telemt_me_reader_eof_total 2004
telemt_me_idle_close_by_peer_total 2003
telemt_me_route_drop_no_conn_total 438670
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 788620
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2234
telemt_desync_full_logged_total 771
telemt_desync_suppressed_total 1463
telemt_desync_frames_bucket_total{bucket="1_2"} 614
telemt_desync_frames_bucket_total{bucket="3_10"} 830
telemt_desync_frames_bucket_total{bucket="gt_10"} 790
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 1988
telemt_me_refill_failed_total 19672
telemt_me_writer_restored_same_endpoint_total 1941
telemt_me_writer_restored_fallback_total 35
telemt_me_async_recovery_trigger_total 14895
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 796128
telemt_user_connections_current{user="hello"} 3364
telemt_user_octets_from_client{user="hello"} 9411024387 (8.76 GB)
telemt_user_octets_to_client{user="hello"} 328765046908 (306.19 GB)
telemt_user_msgs_from_client{user="hello"} 68547
telemt_user_msgs_to_client{user="hello"} 285346
telemt_user_unique_ips_current{user="hello"} 1011
telemt_user_unique_ips_recent_window{user="hello"} 497
```

## landvps.ru

```
telemt 3.3.20

telemt_uptime_seconds 14579.8 (4h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1706899
telemt_connections_bad_total 23864
telemt_handshake_timeouts_total 165688
telemt_upstream_connect_attempt_total 12437
telemt_upstream_connect_success_total 12248
telemt_upstream_connect_fail_total 189
telemt_upstream_connect_attempts_per_request{bucket="1"} 12437
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10917
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1292
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 189
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 699
telemt_me_reconnect_attempts_total 2829421
telemt_me_reconnect_success_total 1179
telemt_me_reader_eof_total 1708
telemt_me_idle_close_by_peer_total 1708
telemt_me_route_drop_no_conn_total 2538660
telemt_me_route_drop_channel_closed_total 21
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1378275
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
telemt_desync_total 2855
telemt_desync_full_logged_total 894
telemt_desync_suppressed_total 1961
telemt_desync_frames_bucket_total{bucket="1_2"} 710
telemt_desync_frames_bucket_total{bucket="3_10"} 1194
telemt_desync_frames_bucket_total{bucket="gt_10"} 951
telemt_me_writer_removed_unexpected_total 1754
telemt_me_refill_failed_total 100120
telemt_me_writer_restored_same_endpoint_total 1084
telemt_me_writer_restored_fallback_total 95
telemt_me_async_recovery_trigger_total 365465
telemt_me_writer_removed_unexpected_minus_restored_total 575
telemt_user_connections_total{user="hello"} 1396874
telemt_user_connections_current{user="hello"} 3345
telemt_user_octets_from_client{user="hello"} 18778222654 (17.49 GB)
telemt_user_octets_to_client{user="hello"} 214483256437 (199.75 GB)
telemt_user_msgs_from_client{user="hello"} 80007
telemt_user_msgs_to_client{user="hello"} 158054
telemt_user_unique_ips_current{user="hello"} 926
telemt_user_unique_ips_recent_window{user="hello"} 612
```

## rdp-onedash.ru

```
telemt 3.3.20

telemt_uptime_seconds 14474.7 (4h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1074617
telemt_connections_bad_total 45107
telemt_handshake_timeouts_total 18755
telemt_upstream_connect_attempt_total 12045
telemt_upstream_connect_success_total 12044
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 12045
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10333
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1485
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 226
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 61
telemt_me_reconnect_attempts_total 2983731
telemt_me_reconnect_success_total 1766
telemt_me_reader_eof_total 1767
telemt_me_idle_close_by_peer_total 1767
telemt_me_route_drop_no_conn_total 676112
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 917238
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3056
telemt_desync_full_logged_total 1025
telemt_desync_suppressed_total 2031
telemt_desync_frames_bucket_total{bucket="1_2"} 435
telemt_desync_frames_bucket_total{bucket="3_10"} 1195
telemt_desync_frames_bucket_total{bucket="gt_10"} 1426
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 1744
telemt_me_refill_failed_total 107153
telemt_me_writer_restored_same_endpoint_total 1651
telemt_me_writer_restored_fallback_total 115
telemt_me_async_recovery_trigger_total 267383
telemt_user_connections_total{user="hello"} 917423
telemt_user_connections_current{user="hello"} 3397
telemt_user_octets_from_client{user="hello"} 14105777425 (13.14 GB)
telemt_user_octets_to_client{user="hello"} 346874041209 (323.05 GB)
telemt_user_msgs_from_client{user="hello"} 86293
telemt_user_msgs_to_client{user="hello"} 266108
telemt_user_unique_ips_current{user="hello"} 1063
telemt_user_unique_ips_recent_window{user="hello"} 576
```

## hostvds.com

```
telemt 3.3.20

telemt_uptime_seconds 14367.4 (3h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 306569
telemt_connections_bad_total 27460
telemt_handshake_timeouts_total 2365
telemt_upstream_connect_attempt_total 2771
telemt_upstream_connect_success_total 2771
telemt_upstream_connect_attempts_per_request{bucket="1"} 2771
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1286
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1482
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 5727
telemt_me_reconnect_success_total 1993
telemt_me_reader_eof_total 2147
telemt_me_idle_close_by_peer_total 2146
telemt_me_route_drop_no_conn_total 165627
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 263932
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 676
telemt_desync_full_logged_total 234
telemt_desync_suppressed_total 442
telemt_desync_frames_bucket_total{bucket="1_2"} 138
telemt_desync_frames_bucket_total{bucket="3_10"} 248
telemt_desync_frames_bucket_total{bucket="gt_10"} 290
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 2127
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 1985
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 130
telemt_me_writer_removed_unexpected_minus_restored_total 134
telemt_user_connections_total{user="hello"} 254224
telemt_user_connections_current{user="hello"} 915
telemt_user_octets_from_client{user="hello"} 4363584128 (4.06 GB)
telemt_user_octets_to_client{user="hello"} 54511310368 (50.77 GB)
telemt_user_unique_ips_current{user="hello"} 327
telemt_user_unique_ips_recent_window{user="hello"} 128
```

## 4vps.su

```
telemt 3.3.20

telemt_uptime_seconds 14430.4 (4h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 884016
telemt_connections_bad_total 115606
telemt_handshake_timeouts_total 18707
telemt_upstream_connect_attempt_total 2602
telemt_upstream_connect_success_total 2576
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 2602
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1437
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1131
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_reconnect_attempts_total 1840
telemt_me_reconnect_success_total 1812
telemt_me_reader_eof_total 1850
telemt_me_idle_close_by_peer_total 1850
telemt_me_route_drop_no_conn_total 401778
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 682145
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2427
telemt_desync_full_logged_total 831
telemt_desync_suppressed_total 1596
telemt_desync_frames_bucket_total{bucket="1_2"} 415
telemt_desync_frames_bucket_total{bucket="3_10"} 844
telemt_desync_frames_bucket_total{bucket="gt_10"} 1168
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 1822
telemt_me_writer_restored_same_endpoint_total 1802
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 681639
telemt_user_connections_current{user="hello"} 2837
telemt_user_octets_from_client{user="hello"} 14735446524 (13.72 GB)
telemt_user_octets_to_client{user="hello"} 334674130204 (311.69 GB)
telemt_user_unique_ips_current{user="hello"} 902
telemt_user_unique_ips_recent_window{user="hello"} 390
```