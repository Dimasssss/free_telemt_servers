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

# Server Metrics 2026-03-18 11:38:10 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.20

telemt_uptime_seconds 10629.4 (2h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 378463
telemt_connections_bad_total 4867
telemt_handshake_timeouts_total 9646
telemt_upstream_connect_attempt_total 65083
telemt_upstream_connect_success_total 64148
telemt_upstream_connect_fail_total 935
telemt_upstream_connect_attempts_per_request{bucket="1"} 65083
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 60025
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3540
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 583
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 935
telemt_me_keepalive_timeout_total 6
telemt_me_reconnect_attempts_total 509434
telemt_me_reconnect_success_total 1634
telemt_me_reader_eof_total 1648
telemt_me_idle_close_by_peer_total 1646
telemt_me_route_drop_no_conn_total 202223
telemt_me_route_drop_channel_closed_total 70
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 274351
telemt_me_writer_pick_total{mode="p2c",result="full"} 21
telemt_me_writer_pick_total{mode="p2c",result="closed"} 54
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1119
telemt_desync_full_logged_total 362
telemt_desync_suppressed_total 757
telemt_desync_frames_bucket_total{bucket="1_2"} 320
telemt_desync_frames_bucket_total{bucket="3_10"} 402
telemt_desync_frames_bucket_total{bucket="gt_10"} 397
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 1669
telemt_me_refill_failed_total 16552
telemt_me_writer_restored_same_endpoint_total 1529
telemt_me_writer_restored_fallback_total 105
telemt_me_async_recovery_trigger_total 11769
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 332747
telemt_user_connections_current{user="hello"} 1649
telemt_user_octets_from_client{user="hello"} 4328395900 (4.03 GB)
telemt_user_octets_to_client{user="hello"} 88193917057 (82.14 GB)
telemt_user_msgs_from_client{user="hello"} 846607
telemt_user_msgs_to_client{user="hello"} 1165163
telemt_user_unique_ips_current{user="hello"} 551
telemt_user_unique_ips_recent_window{user="hello"} 243
```

## psb.hosting

```
telemt 3.3.20

telemt_uptime_seconds 10660.9 (2h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1122090
telemt_connections_bad_total 86977
telemt_handshake_timeouts_total 26182
telemt_upstream_connect_attempt_total 1864
telemt_upstream_connect_success_total 1852
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 1864
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1012
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 825
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_failed_total 1
telemt_me_reconnect_attempts_total 1303
telemt_me_reconnect_success_total 1260
telemt_me_reader_eof_total 1266
telemt_me_idle_close_by_peer_total 1265
telemt_me_route_drop_no_conn_total 1086891
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 959709
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3082
telemt_desync_full_logged_total 878
telemt_desync_suppressed_total 2204
telemt_desync_frames_bucket_total{bucket="1_2"} 622
telemt_desync_frames_bucket_total{bucket="3_10"} 1238
telemt_desync_frames_bucket_total{bucket="gt_10"} 1222
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 1258
telemt_me_writer_restored_same_endpoint_total 1259
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 1068
telemt_user_connections_total{user="hello"} 959017
telemt_user_connections_current{user="hello"} 3881
telemt_user_octets_from_client{user="hello"} 24527389964 (22.84 GB)
telemt_user_octets_to_client{user="hello"} 259065199816 (241.27 GB)
telemt_user_unique_ips_current{user="hello"} 1173
telemt_user_unique_ips_recent_window{user="hello"} 514
```

## koara.io

```
telemt 3.3.20

telemt_uptime_seconds 10575.8 (2h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 739854
telemt_connections_bad_total 53025
telemt_handshake_timeouts_total 18620
telemt_upstream_connect_attempt_total 10346
telemt_upstream_connect_success_total 10346
telemt_upstream_connect_attempts_per_request{bucket="1"} 10346
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8087
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2248
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 40
telemt_me_reconnect_attempts_total 607251
telemt_me_reconnect_success_total 1562
telemt_me_reader_eof_total 1566
telemt_me_idle_close_by_peer_total 1565
telemt_me_route_drop_no_conn_total 345115
telemt_me_route_drop_channel_closed_total 15
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 557690
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1376
telemt_desync_full_logged_total 485
telemt_desync_suppressed_total 891
telemt_desync_frames_bucket_total{bucket="1_2"} 327
telemt_desync_frames_bucket_total{bucket="3_10"} 528
telemt_desync_frames_bucket_total{bucket="gt_10"} 521
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 1563
telemt_me_refill_failed_total 19672
telemt_me_writer_restored_same_endpoint_total 1527
telemt_me_writer_restored_fallback_total 35
telemt_me_async_recovery_trigger_total 14895
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 565392
telemt_user_connections_current{user="hello"} 2986
telemt_user_octets_from_client{user="hello"} 6814700511 (6.35 GB)
telemt_user_octets_to_client{user="hello"} 228073736104 (212.41 GB)
telemt_user_msgs_from_client{user="hello"} 68547
telemt_user_msgs_to_client{user="hello"} 285346
telemt_user_unique_ips_current{user="hello"} 931
telemt_user_unique_ips_recent_window{user="hello"} 400
```

## landvps.ru

```
telemt 3.3.20

telemt_uptime_seconds 10605.8 (2h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1249444
telemt_connections_bad_total 16123
telemt_handshake_timeouts_total 152222
telemt_upstream_connect_attempt_total 12145
telemt_upstream_connect_success_total 11993
telemt_upstream_connect_fail_total 152
telemt_upstream_connect_attempts_per_request{bucket="1"} 12145
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10752
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1202
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 152
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 699
telemt_me_reconnect_attempts_total 2822925
telemt_me_reconnect_success_total 1147
telemt_me_reader_eof_total 1476
telemt_me_idle_close_by_peer_total 1476
telemt_me_route_drop_no_conn_total 1905935
telemt_me_route_drop_channel_closed_total 17
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 972317
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
telemt_desync_total 1875
telemt_desync_full_logged_total 598
telemt_desync_suppressed_total 1277
telemt_desync_frames_bucket_total{bucket="1_2"} 463
telemt_desync_frames_bucket_total{bucket="3_10"} 750
telemt_desync_frames_bucket_total{bucket="gt_10"} 662
telemt_me_writer_removed_unexpected_total 1520
telemt_me_refill_failed_total 99918
telemt_me_writer_restored_same_endpoint_total 1052
telemt_me_writer_restored_fallback_total 95
telemt_me_async_recovery_trigger_total 365465
telemt_me_writer_removed_unexpected_minus_restored_total 373
telemt_user_connections_total{user="hello"} 991081
telemt_user_connections_current{user="hello"} 3143
telemt_user_octets_from_client{user="hello"} 6999775914 (6.52 GB)
telemt_user_octets_to_client{user="hello"} 158060264609 (147.21 GB)
telemt_user_msgs_from_client{user="hello"} 80007
telemt_user_msgs_to_client{user="hello"} 158054
telemt_user_unique_ips_current{user="hello"} 905
telemt_user_unique_ips_recent_window{user="hello"} 426
```

## rdp-onedash.ru

```
telemt 3.3.20

telemt_uptime_seconds 10500.8 (2h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 772507
telemt_connections_bad_total 29612
telemt_handshake_timeouts_total 11934
telemt_upstream_connect_attempt_total 11358
telemt_upstream_connect_success_total 11357
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 11358
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9942
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1193
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 222
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 61
telemt_me_reconnect_attempts_total 2983252
telemt_me_reconnect_success_total 1293
telemt_me_reader_eof_total 1276
telemt_me_idle_close_by_peer_total 1276
telemt_me_route_drop_no_conn_total 506712
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 661688
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2235
telemt_desync_full_logged_total 733
telemt_desync_suppressed_total 1502
telemt_desync_frames_bucket_total{bucket="1_2"} 344
telemt_desync_frames_bucket_total{bucket="3_10"} 871
telemt_desync_frames_bucket_total{bucket="gt_10"} 1020
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 1259
telemt_me_refill_failed_total 107153
telemt_me_writer_restored_same_endpoint_total 1178
telemt_me_writer_restored_fallback_total 115
telemt_me_async_recovery_trigger_total 267383
telemt_user_connections_total{user="hello"} 662061
telemt_user_connections_current{user="hello"} 3389
telemt_user_octets_from_client{user="hello"} 9459505749 (8.81 GB)
telemt_user_octets_to_client{user="hello"} 254741909101 (237.25 GB)
telemt_user_msgs_from_client{user="hello"} 86293
telemt_user_msgs_to_client{user="hello"} 266108
telemt_user_unique_ips_current{user="hello"} 1038
telemt_user_unique_ips_recent_window{user="hello"} 448
```

## hostvds.com

```
telemt 3.3.20

telemt_uptime_seconds 10386.1 (2h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 222221
telemt_connections_bad_total 22210
telemt_handshake_timeouts_total 1740
telemt_upstream_connect_attempt_total 1990
telemt_upstream_connect_success_total 1989
telemt_upstream_connect_attempts_per_request{bucket="1"} 1989
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1028
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 961
telemt_me_reconnect_attempts_total 1421
telemt_me_reconnect_success_total 1405
telemt_me_reader_eof_total 1437
telemt_me_idle_close_by_peer_total 1436
telemt_me_route_drop_no_conn_total 108594
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 190124
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 456
telemt_desync_full_logged_total 160
telemt_desync_suppressed_total 296
telemt_desync_frames_bucket_total{bucket="1_2"} 89
telemt_desync_frames_bucket_total{bucket="3_10"} 160
telemt_desync_frames_bucket_total{bucket="gt_10"} 207
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1414
telemt_me_writer_restored_same_endpoint_total 1397
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 130
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 180452
telemt_user_connections_current{user="hello"} 971
telemt_user_octets_from_client{user="hello"} 2801385808 (2.61 GB)
telemt_user_octets_to_client{user="hello"} 41846982032 (38.97 GB)
telemt_user_unique_ips_current{user="hello"} 350
telemt_user_unique_ips_recent_window{user="hello"} 145
```

## 4vps.su

```
telemt 3.3.20

telemt_uptime_seconds 10456.8 (2h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 553880
telemt_connections_bad_total 27853
telemt_handshake_timeouts_total 13213
telemt_upstream_connect_attempt_total 1917
telemt_upstream_connect_success_total 1896
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 1917
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1051
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 837
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_reconnect_attempts_total 1336
telemt_me_reconnect_success_total 1315
telemt_me_reader_eof_total 1329
telemt_me_idle_close_by_peer_total 1329
telemt_me_route_drop_no_conn_total 254047
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 468455
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1749
telemt_desync_full_logged_total 608
telemt_desync_suppressed_total 1141
telemt_desync_frames_bucket_total{bucket="1_2"} 303
telemt_desync_frames_bucket_total{bucket="3_10"} 628
telemt_desync_frames_bucket_total{bucket="gt_10"} 818
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1316
telemt_me_writer_restored_same_endpoint_total 1305
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 468084
telemt_user_connections_current{user="hello"} 2881
telemt_user_octets_from_client{user="hello"} 9641636412 (8.98 GB)
telemt_user_octets_to_client{user="hello"} 237513486716 (221.20 GB)
telemt_user_unique_ips_current{user="hello"} 855
telemt_user_unique_ips_recent_window{user="hello"} 397
```