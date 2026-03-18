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

# Server Metrics 2026-03-18 11:53:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.20

telemt_uptime_seconds 11544.7 (3h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 411203
telemt_connections_bad_total 5553
telemt_handshake_timeouts_total 11107
telemt_upstream_connect_attempt_total 65231
telemt_upstream_connect_success_total 64296
telemt_upstream_connect_fail_total 935
telemt_upstream_connect_attempts_per_request{bucket="1"} 65231
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 60094
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3619
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 583
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 935
telemt_me_keepalive_timeout_total 6
telemt_me_reconnect_attempts_total 509539
telemt_me_reconnect_success_total 1738
telemt_me_reader_eof_total 1765
telemt_me_idle_close_by_peer_total 1763
telemt_me_route_drop_no_conn_total 222062
telemt_me_route_drop_channel_closed_total 77
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 302914
telemt_me_writer_pick_total{mode="p2c",result="full"} 21
telemt_me_writer_pick_total{mode="p2c",result="closed"} 54
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1229
telemt_desync_full_logged_total 395
telemt_desync_suppressed_total 834
telemt_desync_frames_bucket_total{bucket="1_2"} 352
telemt_desync_frames_bucket_total{bucket="3_10"} 444
telemt_desync_frames_bucket_total{bucket="gt_10"} 433
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 1776
telemt_me_refill_failed_total 16552
telemt_me_writer_restored_same_endpoint_total 1633
telemt_me_writer_restored_fallback_total 105
telemt_me_async_recovery_trigger_total 11769
telemt_me_writer_removed_unexpected_minus_restored_total 38
telemt_user_connections_total{user="hello"} 361218
telemt_user_connections_current{user="hello"} 1675
telemt_user_octets_from_client{user="hello"} 4674301656 (4.35 GB)
telemt_user_octets_to_client{user="hello"} 96258162665 (89.65 GB)
telemt_user_msgs_from_client{user="hello"} 846607
telemt_user_msgs_to_client{user="hello"} 1165163
telemt_user_unique_ips_current{user="hello"} 555
telemt_user_unique_ips_recent_window{user="hello"} 237
```

## psb.hosting

```
telemt 3.3.20

telemt_uptime_seconds 11576.5 (3h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1188110
telemt_connections_bad_total 88923
telemt_handshake_timeouts_total 27489
telemt_upstream_connect_attempt_total 1992
telemt_upstream_connect_success_total 1980
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 1992
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1078
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 886
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_failed_total 1
telemt_me_reconnect_attempts_total 1388
telemt_me_reconnect_success_total 1345
telemt_me_reader_eof_total 1356
telemt_me_idle_close_by_peer_total 1355
telemt_me_route_drop_no_conn_total 1118258
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1019785
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3293
telemt_desync_full_logged_total 944
telemt_desync_suppressed_total 2349
telemt_desync_frames_bucket_total{bucket="1_2"} 647
telemt_desync_frames_bucket_total{bucket="3_10"} 1341
telemt_desync_frames_bucket_total{bucket="gt_10"} 1305
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 1344
telemt_me_writer_restored_same_endpoint_total 1344
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 1068
telemt_user_connections_total{user="hello"} 1019072
telemt_user_connections_current{user="hello"} 3892
telemt_user_octets_from_client{user="hello"} 25097023852 (23.37 GB)
telemt_user_octets_to_client{user="hello"} 284053491828 (264.55 GB)
telemt_user_unique_ips_current{user="hello"} 1156
telemt_user_unique_ips_recent_window{user="hello"} 558
```

## koara.io

```
telemt 3.3.20

telemt_uptime_seconds 11491.7 (3h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 809764
telemt_connections_bad_total 58674
telemt_handshake_timeouts_total 19949
telemt_upstream_connect_attempt_total 10464
telemt_upstream_connect_success_total 10464
telemt_upstream_connect_attempts_per_request{bucket="1"} 10464
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8142
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2311
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 40
telemt_me_reconnect_attempts_total 607326
telemt_me_reconnect_success_total 1636
telemt_me_reader_eof_total 1647
telemt_me_idle_close_by_peer_total 1646
telemt_me_route_drop_no_conn_total 362475
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 605335
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1490
telemt_desync_full_logged_total 530
telemt_desync_suppressed_total 960
telemt_desync_frames_bucket_total{bucket="1_2"} 359
telemt_desync_frames_bucket_total{bucket="3_10"} 568
telemt_desync_frames_bucket_total{bucket="gt_10"} 563
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1641
telemt_me_refill_failed_total 19672
telemt_me_writer_restored_same_endpoint_total 1601
telemt_me_writer_restored_fallback_total 35
telemt_me_async_recovery_trigger_total 14895
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 612985
telemt_user_connections_current{user="hello"} 2955
telemt_user_octets_from_client{user="hello"} 7420827095 (6.91 GB)
telemt_user_octets_to_client{user="hello"} 250473297512 (233.27 GB)
telemt_user_msgs_from_client{user="hello"} 68547
telemt_user_msgs_to_client{user="hello"} 285346
telemt_user_unique_ips_current{user="hello"} 941
telemt_user_unique_ips_recent_window{user="hello"} 442
```

## landvps.ru

```
telemt 3.3.20

telemt_uptime_seconds 11521.8 (3h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1313227
telemt_connections_bad_total 18917
telemt_handshake_timeouts_total 154919
telemt_upstream_connect_attempt_total 12217
telemt_upstream_connect_success_total 12056
telemt_upstream_connect_fail_total 161
telemt_upstream_connect_attempts_per_request{bucket="1"} 12217
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10797
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1220
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 161
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 699
telemt_me_reconnect_attempts_total 2824321
telemt_me_reconnect_success_total 1167
telemt_me_reader_eof_total 1539
telemt_me_idle_close_by_peer_total 1539
telemt_me_route_drop_no_conn_total 1940281
telemt_me_route_drop_channel_closed_total 20
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1025073
telemt_me_writer_pick_total{mode="p2c",result="success_fallback"} 8840
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_writer_pick_blocking_fallback_total 8840
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2057
telemt_desync_full_logged_total 669
telemt_desync_suppressed_total 1388
telemt_desync_frames_bucket_total{bucket="1_2"} 510
telemt_desync_frames_bucket_total{bucket="3_10"} 811
telemt_desync_frames_bucket_total{bucket="gt_10"} 736
telemt_me_writer_removed_unexpected_total 1583
telemt_me_refill_failed_total 99961
telemt_me_writer_restored_same_endpoint_total 1072
telemt_me_writer_restored_fallback_total 95
telemt_me_async_recovery_trigger_total 365465
telemt_me_writer_removed_unexpected_minus_restored_total 416
telemt_user_connections_total{user="hello"} 1043800
telemt_user_connections_current{user="hello"} 3092
telemt_user_octets_from_client{user="hello"} 7401822974 (6.89 GB)
telemt_user_octets_to_client{user="hello"} 174972219637 (162.96 GB)
telemt_user_msgs_from_client{user="hello"} 80007
telemt_user_msgs_to_client{user="hello"} 158054
telemt_user_unique_ips_current{user="hello"} 906
telemt_user_unique_ips_recent_window{user="hello"} 433
```

## rdp-onedash.ru

```
telemt 3.3.20

telemt_uptime_seconds 11416.5 (3h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 835452
telemt_connections_bad_total 32773
telemt_handshake_timeouts_total 14280
telemt_upstream_connect_attempt_total 11470
telemt_upstream_connect_success_total 11469
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 11470
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9997
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1249
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 223
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 61
telemt_me_reconnect_attempts_total 2983321
telemt_me_reconnect_success_total 1361
telemt_me_reader_eof_total 1352
telemt_me_idle_close_by_peer_total 1352
telemt_me_route_drop_no_conn_total 525710
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 714350
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2465
telemt_desync_full_logged_total 802
telemt_desync_suppressed_total 1663
telemt_desync_frames_bucket_total{bucket="1_2"} 376
telemt_desync_frames_bucket_total{bucket="3_10"} 967
telemt_desync_frames_bucket_total{bucket="gt_10"} 1122
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 1332
telemt_me_refill_failed_total 107153
telemt_me_writer_restored_same_endpoint_total 1246
telemt_me_writer_restored_fallback_total 115
telemt_me_async_recovery_trigger_total 267383
telemt_user_connections_total{user="hello"} 714688
telemt_user_connections_current{user="hello"} 3331
telemt_user_octets_from_client{user="hello"} 10096488973 (9.40 GB)
telemt_user_octets_to_client{user="hello"} 274013459457 (255.19 GB)
telemt_user_msgs_from_client{user="hello"} 86293
telemt_user_msgs_to_client{user="hello"} 266108
telemt_user_unique_ips_current{user="hello"} 1031
telemt_user_unique_ips_recent_window{user="hello"} 485
```

## hostvds.com

```
telemt 3.3.20

telemt_uptime_seconds 11301.3 (3h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 238283
telemt_connections_bad_total 22216
telemt_handshake_timeouts_total 1863
telemt_upstream_connect_attempt_total 2233
telemt_upstream_connect_success_total 2233
telemt_upstream_connect_attempts_per_request{bucket="1"} 2233
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1127
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1106
telemt_me_reconnect_attempts_total 1620
telemt_me_reconnect_success_total 1604
telemt_me_reader_eof_total 1639
telemt_me_idle_close_by_peer_total 1638
telemt_me_route_drop_no_conn_total 115245
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 205200
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 504
telemt_desync_full_logged_total 178
telemt_desync_suppressed_total 326
telemt_desync_frames_bucket_total{bucket="1_2"} 96
telemt_desync_frames_bucket_total{bucket="3_10"} 178
telemt_desync_frames_bucket_total{bucket="gt_10"} 230
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1616
telemt_me_writer_restored_same_endpoint_total 1596
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 130
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 195507
telemt_user_connections_current{user="hello"} 976
telemt_user_octets_from_client{user="hello"} 3846159412 (3.58 GB)
telemt_user_octets_to_client{user="hello"} 44963707792 (41.88 GB)
telemt_user_unique_ips_current{user="hello"} 343
telemt_user_unique_ips_recent_window{user="hello"} 142
```

## 4vps.su

```
telemt 3.3.20

telemt_uptime_seconds 11372.5 (3h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 627435
telemt_connections_bad_total 53481
telemt_handshake_timeouts_total 14742
telemt_upstream_connect_attempt_total 2103
telemt_upstream_connect_success_total 2082
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 2103
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1159
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 915
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_reconnect_attempts_total 1478
telemt_me_reconnect_success_total 1457
telemt_me_reader_eof_total 1481
telemt_me_idle_close_by_peer_total 1481
telemt_me_route_drop_no_conn_total 275295
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 510973
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1901
telemt_desync_full_logged_total 668
telemt_desync_suppressed_total 1233
telemt_desync_frames_bucket_total{bucket="1_2"} 320
telemt_desync_frames_bucket_total{bucket="3_10"} 685
telemt_desync_frames_bucket_total{bucket="gt_10"} 896
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 1458
telemt_me_writer_restored_same_endpoint_total 1447
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 510568
telemt_user_connections_current{user="hello"} 2847
telemt_user_octets_from_client{user="hello"} 10563345664 (9.84 GB)
telemt_user_octets_to_client{user="hello"} 261015025824 (243.09 GB)
telemt_user_unique_ips_current{user="hello"} 882
telemt_user_unique_ips_recent_window{user="hello"} 391
```