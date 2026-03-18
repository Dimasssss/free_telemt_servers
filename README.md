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

# Server Metrics 2026-03-18 11:43:15 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.20

telemt_uptime_seconds 10935.1 (3h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 388289
telemt_connections_bad_total 5066
telemt_handshake_timeouts_total 10090
telemt_upstream_connect_attempt_total 65170
telemt_upstream_connect_success_total 64235
telemt_upstream_connect_fail_total 935
telemt_upstream_connect_attempts_per_request{bucket="1"} 65170
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 60069
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3583
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 583
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 935
telemt_me_keepalive_timeout_total 6
telemt_me_reconnect_attempts_total 509478
telemt_me_reconnect_success_total 1677
telemt_me_reader_eof_total 1700
telemt_me_idle_close_by_peer_total 1698
telemt_me_route_drop_no_conn_total 205644
telemt_me_route_drop_channel_closed_total 75
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 283044
telemt_me_writer_pick_total{mode="p2c",result="full"} 21
telemt_me_writer_pick_total{mode="p2c",result="closed"} 54
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1140
telemt_desync_full_logged_total 370
telemt_desync_suppressed_total 770
telemt_desync_frames_bucket_total{bucket="1_2"} 325
telemt_desync_frames_bucket_total{bucket="3_10"} 409
telemt_desync_frames_bucket_total{bucket="gt_10"} 406
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 1713
telemt_me_refill_failed_total 16552
telemt_me_writer_restored_same_endpoint_total 1572
telemt_me_writer_restored_fallback_total 105
telemt_me_async_recovery_trigger_total 11769
telemt_me_writer_removed_unexpected_minus_restored_total 36
telemt_user_connections_total{user="hello"} 341415
telemt_user_connections_current{user="hello"} 1565
telemt_user_octets_from_client{user="hello"} 4411987684 (4.11 GB)
telemt_user_octets_to_client{user="hello"} 91657285785 (85.36 GB)
telemt_user_msgs_from_client{user="hello"} 846607
telemt_user_msgs_to_client{user="hello"} 1165163
telemt_user_unique_ips_current{user="hello"} 537
telemt_user_unique_ips_recent_window{user="hello"} 223
```

## psb.hosting

```
telemt 3.3.20

telemt_uptime_seconds 10965.7 (3h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1144329
telemt_connections_bad_total 87540
telemt_handshake_timeouts_total 26577
telemt_upstream_connect_attempt_total 1938
telemt_upstream_connect_success_total 1926
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 1938
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1056
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 855
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_failed_total 1
telemt_me_reconnect_attempts_total 1334
telemt_me_reconnect_success_total 1291
telemt_me_reader_eof_total 1301
telemt_me_idle_close_by_peer_total 1300
telemt_me_route_drop_no_conn_total 1096736
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 980093
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3159
telemt_desync_full_logged_total 902
telemt_desync_suppressed_total 2257
telemt_desync_frames_bucket_total{bucket="1_2"} 628
telemt_desync_frames_bucket_total{bucket="3_10"} 1274
telemt_desync_frames_bucket_total{bucket="gt_10"} 1257
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 1289
telemt_me_writer_restored_same_endpoint_total 1290
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 1068
telemt_user_connections_total{user="hello"} 979401
telemt_user_connections_current{user="hello"} 3945
telemt_user_octets_from_client{user="hello"} 24736402224 (23.04 GB)
telemt_user_octets_to_client{user="hello"} 266911486048 (248.58 GB)
telemt_user_unique_ips_current{user="hello"} 1188
telemt_user_unique_ips_recent_window{user="hello"} 508
```

## koara.io

```
telemt 3.3.20

telemt_uptime_seconds 10881.0 (3h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 759092
telemt_connections_bad_total 54401
telemt_handshake_timeouts_total 19080
telemt_upstream_connect_attempt_total 10394
telemt_upstream_connect_success_total 10394
telemt_upstream_connect_attempts_per_request{bucket="1"} 10394
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8112
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2271
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 40
telemt_me_reconnect_attempts_total 607264
telemt_me_reconnect_success_total 1575
telemt_me_reader_eof_total 1581
telemt_me_idle_close_by_peer_total 1580
telemt_me_route_drop_no_conn_total 350971
telemt_me_route_drop_channel_closed_total 15
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 572250
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1398
telemt_desync_full_logged_total 500
telemt_desync_suppressed_total 898
telemt_desync_frames_bucket_total{bucket="1_2"} 332
telemt_desync_frames_bucket_total{bucket="3_10"} 535
telemt_desync_frames_bucket_total{bucket="gt_10"} 531
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 1578
telemt_me_refill_failed_total 19672
telemt_me_writer_restored_same_endpoint_total 1540
telemt_me_writer_restored_fallback_total 35
telemt_me_async_recovery_trigger_total 14895
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 579938
telemt_user_connections_current{user="hello"} 3028
telemt_user_octets_from_client{user="hello"} 6997568343 (6.52 GB)
telemt_user_octets_to_client{user="hello"} 233755857624 (217.70 GB)
telemt_user_msgs_from_client{user="hello"} 68547
telemt_user_msgs_to_client{user="hello"} 285346
telemt_user_unique_ips_current{user="hello"} 944
telemt_user_unique_ips_recent_window{user="hello"} 394
```

## landvps.ru

```
telemt 3.3.20

telemt_uptime_seconds 10911.0 (3h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1271763
telemt_connections_bad_total 17177
telemt_handshake_timeouts_total 153111
telemt_upstream_connect_attempt_total 12188
telemt_upstream_connect_success_total 12026
telemt_upstream_connect_fail_total 161
telemt_upstream_connect_attempts_per_request{bucket="1"} 12187
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10774
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1213
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 161
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 699
telemt_me_reconnect_attempts_total 2822931
telemt_me_reconnect_success_total 1153
telemt_me_reader_eof_total 1482
telemt_me_idle_close_by_peer_total 1482
telemt_me_route_drop_no_conn_total 1920938
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 991139
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
telemt_desync_total 1926
telemt_desync_full_logged_total 624
telemt_desync_suppressed_total 1302
telemt_desync_frames_bucket_total{bucket="1_2"} 479
telemt_desync_frames_bucket_total{bucket="3_10"} 770
telemt_desync_frames_bucket_total{bucket="gt_10"} 677
telemt_me_writer_removed_unexpected_total 1526
telemt_me_refill_failed_total 99918
telemt_me_writer_restored_same_endpoint_total 1058
telemt_me_writer_restored_fallback_total 95
telemt_me_async_recovery_trigger_total 365465
telemt_me_writer_removed_unexpected_minus_restored_total 373
telemt_user_connections_total{user="hello"} 1009893
telemt_user_connections_current{user="hello"} 3047
telemt_user_octets_from_client{user="hello"} 7129106110 (6.64 GB)
telemt_user_octets_to_client{user="hello"} 163680101133 (152.44 GB)
telemt_user_msgs_from_client{user="hello"} 80007
telemt_user_msgs_to_client{user="hello"} 158054
telemt_user_unique_ips_current{user="hello"} 897
telemt_user_unique_ips_recent_window{user="hello"} 383
```

## rdp-onedash.ru

```
telemt 3.3.20

telemt_uptime_seconds 10805.7 (3h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 794139
telemt_connections_bad_total 31669
telemt_handshake_timeouts_total 12882
telemt_upstream_connect_attempt_total 11373
telemt_upstream_connect_success_total 11372
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 11373
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9950
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1200
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 222
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 61
telemt_me_reconnect_attempts_total 2983267
telemt_me_reconnect_success_total 1308
telemt_me_reader_eof_total 1294
telemt_me_idle_close_by_peer_total 1294
telemt_me_route_drop_no_conn_total 513446
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 679094
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2304
telemt_desync_full_logged_total 756
telemt_desync_suppressed_total 1548
telemt_desync_frames_bucket_total{bucket="1_2"} 350
telemt_desync_frames_bucket_total{bucket="3_10"} 908
telemt_desync_frames_bucket_total{bucket="gt_10"} 1046
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 1277
telemt_me_refill_failed_total 107153
telemt_me_writer_restored_same_endpoint_total 1193
telemt_me_writer_restored_fallback_total 115
telemt_me_async_recovery_trigger_total 267383
telemt_user_connections_total{user="hello"} 679460
telemt_user_connections_current{user="hello"} 3365
telemt_user_octets_from_client{user="hello"} 9648424801 (8.99 GB)
telemt_user_octets_to_client{user="hello"} 261090215401 (243.16 GB)
telemt_user_msgs_from_client{user="hello"} 86293
telemt_user_msgs_to_client{user="hello"} 266108
telemt_user_unique_ips_current{user="hello"} 1022
telemt_user_unique_ips_recent_window{user="hello"} 469
```

## hostvds.com

```
telemt 3.3.20

telemt_uptime_seconds 10691.7 (2h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 227733
telemt_connections_bad_total 22212
telemt_handshake_timeouts_total 1769
telemt_upstream_connect_attempt_total 2034
telemt_upstream_connect_success_total 2034
telemt_upstream_connect_attempts_per_request{bucket="1"} 2034
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1042
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 992
telemt_me_reconnect_attempts_total 1465
telemt_me_reconnect_success_total 1450
telemt_me_reader_eof_total 1481
telemt_me_idle_close_by_peer_total 1480
telemt_me_route_drop_no_conn_total 110920
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 195304
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 473
telemt_desync_full_logged_total 168
telemt_desync_suppressed_total 305
telemt_desync_frames_bucket_total{bucket="1_2"} 95
telemt_desync_frames_bucket_total{bucket="3_10"} 164
telemt_desync_frames_bucket_total{bucket="gt_10"} 214
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1458
telemt_me_writer_restored_same_endpoint_total 1442
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 130
telemt_me_writer_removed_unexpected_minus_restored_total 8
telemt_user_connections_total{user="hello"} 185626
telemt_user_connections_current{user="hello"} 1023
telemt_user_octets_from_client{user="hello"} 3422850992 (3.19 GB)
telemt_user_octets_to_client{user="hello"} 42709502096 (39.78 GB)
telemt_user_unique_ips_current{user="hello"} 346
telemt_user_unique_ips_recent_window{user="hello"} 169
```

## 4vps.su

```
telemt 3.3.20

telemt_uptime_seconds 10761.9 (2h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 569490
telemt_connections_bad_total 28758
telemt_handshake_timeouts_total 13734
telemt_upstream_connect_attempt_total 1960
telemt_upstream_connect_success_total 1939
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 1960
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1075
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 856
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_reconnect_attempts_total 1379
telemt_me_reconnect_success_total 1358
telemt_me_reader_eof_total 1372
telemt_me_idle_close_by_peer_total 1372
telemt_me_route_drop_no_conn_total 259384
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 482108
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1782
telemt_desync_full_logged_total 625
telemt_desync_suppressed_total 1157
telemt_desync_frames_bucket_total{bucket="1_2"} 306
telemt_desync_frames_bucket_total{bucket="3_10"} 639
telemt_desync_frames_bucket_total{bucket="gt_10"} 837
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1359
telemt_me_writer_restored_same_endpoint_total 1348
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 481724
telemt_user_connections_current{user="hello"} 2974
telemt_user_octets_from_client{user="hello"} 9911203212 (9.23 GB)
telemt_user_octets_to_client{user="hello"} 245147044076 (228.31 GB)
telemt_user_unique_ips_current{user="hello"} 878
telemt_user_unique_ips_recent_window{user="hello"} 390
```