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

# Server Metrics 2026-03-18 12:08:41 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.20

telemt_uptime_seconds 12460.6 (3h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 445817
telemt_connections_bad_total 5902
telemt_handshake_timeouts_total 12264
telemt_upstream_connect_attempt_total 65416
telemt_upstream_connect_success_total 64480
telemt_upstream_connect_fail_total 936
telemt_upstream_connect_attempts_per_request{bucket="1"} 65416
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 60193
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3704
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 583
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 936
telemt_me_keepalive_timeout_total 6
telemt_me_reconnect_attempts_total 509679
telemt_me_reconnect_success_total 1877
telemt_me_reader_eof_total 1903
telemt_me_idle_close_by_peer_total 1901
telemt_me_route_drop_no_conn_total 247975
telemt_me_route_drop_channel_closed_total 82
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 334600
telemt_me_writer_pick_total{mode="p2c",result="full"} 21
telemt_me_writer_pick_total{mode="p2c",result="closed"} 54
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1386
telemt_desync_full_logged_total 447
telemt_desync_suppressed_total 939
telemt_desync_frames_bucket_total{bucket="1_2"} 402
telemt_desync_frames_bucket_total{bucket="3_10"} 509
telemt_desync_frames_bucket_total{bucket="gt_10"} 475
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 1915
telemt_me_refill_failed_total 16552
telemt_me_writer_restored_same_endpoint_total 1772
telemt_me_writer_restored_fallback_total 105
telemt_me_async_recovery_trigger_total 11769
telemt_me_writer_removed_unexpected_minus_restored_total 38
telemt_user_connections_total{user="hello"} 392890
telemt_user_connections_current{user="hello"} 1708
telemt_user_octets_from_client{user="hello"} 5469522404 (5.09 GB)
telemt_user_octets_to_client{user="hello"} 103968248601 (96.83 GB)
telemt_user_msgs_from_client{user="hello"} 846607
telemt_user_msgs_to_client{user="hello"} 1165163
telemt_user_unique_ips_current{user="hello"} 561
telemt_user_unique_ips_recent_window{user="hello"} 280
```

## psb.hosting

```
telemt 3.3.20

telemt_uptime_seconds 12491.8 (3h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1264455
telemt_connections_bad_total 91618
telemt_handshake_timeouts_total 29240
telemt_upstream_connect_attempt_total 2130
telemt_upstream_connect_success_total 2118
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 2130
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1145
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 957
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_failed_total 1
telemt_me_reconnect_attempts_total 1482
telemt_me_reconnect_success_total 1438
telemt_me_reader_eof_total 1457
telemt_me_idle_close_by_peer_total 1456
telemt_me_route_drop_no_conn_total 1147546
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1088019
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3437
telemt_desync_full_logged_total 1005
telemt_desync_suppressed_total 2432
telemt_desync_frames_bucket_total{bucket="1_2"} 675
telemt_desync_frames_bucket_total{bucket="3_10"} 1395
telemt_desync_frames_bucket_total{bucket="gt_10"} 1367
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 1439
telemt_me_writer_restored_same_endpoint_total 1437
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 1068
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 1087292
telemt_user_connections_current{user="hello"} 4346
telemt_user_octets_from_client{user="hello"} 26164160080 (24.37 GB)
telemt_user_octets_to_client{user="hello"} 310833336992 (289.49 GB)
telemt_user_unique_ips_current{user="hello"} 1220
telemt_user_unique_ips_recent_window{user="hello"} 604
```

## koara.io

```
telemt 3.3.20

telemt_uptime_seconds 12406.5 (3h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 881991
telemt_connections_bad_total 65218
telemt_handshake_timeouts_total 21765
telemt_upstream_connect_attempt_total 10578
telemt_upstream_connect_success_total 10578
telemt_upstream_connect_attempts_per_request{bucket="1"} 10578
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8196
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2371
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 607397
telemt_me_reconnect_success_total 1705
telemt_me_reader_eof_total 1720
telemt_me_idle_close_by_peer_total 1719
telemt_me_route_drop_no_conn_total 384780
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 660726
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1757
telemt_desync_full_logged_total 616
telemt_desync_suppressed_total 1141
telemt_desync_frames_bucket_total{bucket="1_2"} 448
telemt_desync_frames_bucket_total{bucket="3_10"} 667
telemt_desync_frames_bucket_total{bucket="gt_10"} 642
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 1711
telemt_me_refill_failed_total 19672
telemt_me_writer_restored_same_endpoint_total 1670
telemt_me_writer_restored_fallback_total 35
telemt_me_async_recovery_trigger_total 14895
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 668348
telemt_user_connections_current{user="hello"} 3311
telemt_user_octets_from_client{user="hello"} 7984756883 (7.44 GB)
telemt_user_octets_to_client{user="hello"} 276254970864 (257.28 GB)
telemt_user_msgs_from_client{user="hello"} 68547
telemt_user_msgs_to_client{user="hello"} 285346
telemt_user_unique_ips_current{user="hello"} 1040
telemt_user_unique_ips_recent_window{user="hello"} 515
```

## landvps.ru

```
telemt 3.3.20

telemt_uptime_seconds 12436.8 (3h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1383617
telemt_connections_bad_total 20568
telemt_handshake_timeouts_total 157910
telemt_upstream_connect_attempt_total 12282
telemt_upstream_connect_success_total 12110
telemt_upstream_connect_fail_total 172
telemt_upstream_connect_attempts_per_request{bucket="1"} 12282
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10833
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1238
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 172
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 699
telemt_me_reconnect_attempts_total 2825708
telemt_me_reconnect_success_total 1178
telemt_me_reader_eof_total 1593
telemt_me_idle_close_by_peer_total 1593
telemt_me_route_drop_no_conn_total 1988420
telemt_me_route_drop_channel_closed_total 20
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1084729
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
telemt_desync_total 2231
telemt_desync_full_logged_total 728
telemt_desync_suppressed_total 1503
telemt_desync_frames_bucket_total{bucket="1_2"} 557
telemt_desync_frames_bucket_total{bucket="3_10"} 879
telemt_desync_frames_bucket_total{bucket="gt_10"} 795
telemt_me_writer_removed_unexpected_total 1637
telemt_me_refill_failed_total 100004
telemt_me_writer_restored_same_endpoint_total 1083
telemt_me_writer_restored_fallback_total 95
telemt_me_async_recovery_trigger_total 365465
telemt_me_writer_removed_unexpected_minus_restored_total 459
telemt_user_connections_total{user="hello"} 1103419
telemt_user_connections_current{user="hello"} 3231
telemt_user_octets_from_client{user="hello"} 7942653802 (7.40 GB)
telemt_user_octets_to_client{user="hello"} 191122065117 (178.00 GB)
telemt_user_msgs_from_client{user="hello"} 80007
telemt_user_msgs_to_client{user="hello"} 158054
telemt_user_unique_ips_current{user="hello"} 937
telemt_user_unique_ips_recent_window{user="hello"} 479
```

## rdp-onedash.ru

```
telemt 3.3.20

telemt_uptime_seconds 12331.5 (3h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 910131
telemt_connections_bad_total 40050
telemt_handshake_timeouts_total 15831
telemt_upstream_connect_attempt_total 11587
telemt_upstream_connect_success_total 11586
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 11587
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10068
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1294
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 224
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 61
telemt_me_reconnect_attempts_total 2983395
telemt_me_reconnect_success_total 1431
telemt_me_reader_eof_total 1429
telemt_me_idle_close_by_peer_total 1429
telemt_me_route_drop_no_conn_total 554511
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 774096
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2676
telemt_desync_full_logged_total 877
telemt_desync_suppressed_total 1799
telemt_desync_frames_bucket_total{bucket="1_2"} 398
telemt_desync_frames_bucket_total{bucket="3_10"} 1052
telemt_desync_frames_bucket_total{bucket="gt_10"} 1226
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 1405
telemt_me_refill_failed_total 107153
telemt_me_writer_restored_same_endpoint_total 1316
telemt_me_writer_restored_fallback_total 115
telemt_me_async_recovery_trigger_total 267383
telemt_user_connections_total{user="hello"} 774351
telemt_user_connections_current{user="hello"} 3421
telemt_user_octets_from_client{user="hello"} 11004818345 (10.25 GB)
telemt_user_octets_to_client{user="hello"} 298829642301 (278.31 GB)
telemt_user_msgs_from_client{user="hello"} 86293
telemt_user_msgs_to_client{user="hello"} 266108
telemt_user_unique_ips_current{user="hello"} 1059
telemt_user_unique_ips_recent_window{user="hello"} 575
```

## hostvds.com

```
telemt 3.3.20

telemt_uptime_seconds 12217.3 (3h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 257544
telemt_connections_bad_total 23523
telemt_handshake_timeouts_total 1984
telemt_upstream_connect_attempt_total 2446
telemt_upstream_connect_success_total 2446
telemt_upstream_connect_attempts_per_request{bucket="1"} 2446
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1189
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1257
telemt_me_reconnect_attempts_total 2936
telemt_me_reconnect_success_total 1768
telemt_me_reader_eof_total 1839
telemt_me_idle_close_by_peer_total 1838
telemt_me_route_drop_no_conn_total 125473
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 222169
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 565
telemt_desync_full_logged_total 196
telemt_desync_suppressed_total 369
telemt_desync_frames_bucket_total{bucket="1_2"} 110
telemt_desync_frames_bucket_total{bucket="3_10"} 200
telemt_desync_frames_bucket_total{bucket="gt_10"} 255
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1816
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 1760
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 130
telemt_me_writer_removed_unexpected_minus_restored_total 48
telemt_user_connections_total{user="hello"} 212473
telemt_user_connections_current{user="hello"} 998
telemt_user_octets_from_client{user="hello"} 4058658544 (3.78 GB)
telemt_user_octets_to_client{user="hello"} 49037358380 (45.67 GB)
telemt_user_unique_ips_current{user="hello"} 345
telemt_user_unique_ips_recent_window{user="hello"} 167
```

## 4vps.su

```
telemt 3.3.20

telemt_uptime_seconds 12287.5 (3h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 733111
telemt_connections_bad_total 104556
telemt_handshake_timeouts_total 15966
telemt_upstream_connect_attempt_total 2237
telemt_upstream_connect_success_total 2215
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 2237
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1229
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 978
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_reconnect_attempts_total 1567
telemt_me_reconnect_success_total 1541
telemt_me_reader_eof_total 1573
telemt_me_idle_close_by_peer_total 1573
telemt_me_route_drop_no_conn_total 293556
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 559065
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2064
telemt_desync_full_logged_total 716
telemt_desync_suppressed_total 1348
telemt_desync_frames_bucket_total{bucket="1_2"} 344
telemt_desync_frames_bucket_total{bucket="3_10"} 736
telemt_desync_frames_bucket_total{bucket="gt_10"} 984
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 1546
telemt_me_writer_restored_same_endpoint_total 1531
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 558624
telemt_user_connections_current{user="hello"} 3114
telemt_user_octets_from_client{user="hello"} 11570973964 (10.78 GB)
telemt_user_octets_to_client{user="hello"} 285868782400 (266.24 GB)
telemt_user_unique_ips_current{user="hello"} 950
telemt_user_unique_ips_recent_window{user="hello"} 442
```