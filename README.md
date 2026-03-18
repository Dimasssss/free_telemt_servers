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

# Server Metrics 2026-03-18 11:58:30 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.20

telemt_uptime_seconds 11850.1 (3h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 421927
telemt_connections_bad_total 5597
telemt_handshake_timeouts_total 11467
telemt_upstream_connect_attempt_total 65306
telemt_upstream_connect_success_total 64370
telemt_upstream_connect_fail_total 936
telemt_upstream_connect_attempts_per_request{bucket="1"} 65306
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 60141
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3646
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 583
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 936
telemt_me_keepalive_timeout_total 6
telemt_me_reconnect_attempts_total 509569
telemt_me_reconnect_success_total 1768
telemt_me_reader_eof_total 1795
telemt_me_idle_close_by_peer_total 1793
telemt_me_route_drop_no_conn_total 224717
telemt_me_route_drop_channel_closed_total 80
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 312756
telemt_me_writer_pick_total{mode="p2c",result="full"} 21
telemt_me_writer_pick_total{mode="p2c",result="closed"} 54
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1279
telemt_desync_full_logged_total 413
telemt_desync_suppressed_total 866
telemt_desync_frames_bucket_total{bucket="1_2"} 371
telemt_desync_frames_bucket_total{bucket="3_10"} 463
telemt_desync_frames_bucket_total{bucket="gt_10"} 445
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 1806
telemt_me_refill_failed_total 16552
telemt_me_writer_restored_same_endpoint_total 1663
telemt_me_writer_restored_fallback_total 105
telemt_me_async_recovery_trigger_total 11769
telemt_me_writer_removed_unexpected_minus_restored_total 38
telemt_user_connections_total{user="hello"} 371055
telemt_user_connections_current{user="hello"} 1677
telemt_user_octets_from_client{user="hello"} 4953308120 (4.61 GB)
telemt_user_octets_to_client{user="hello"} 98430288401 (91.67 GB)
telemt_user_msgs_from_client{user="hello"} 846607
telemt_user_msgs_to_client{user="hello"} 1165163
telemt_user_unique_ips_current{user="hello"} 557
telemt_user_unique_ips_recent_window{user="hello"} 268
```

## psb.hosting

```
telemt 3.3.20

telemt_uptime_seconds 11880.8 (3h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1210908
telemt_connections_bad_total 89568
telemt_handshake_timeouts_total 27976
telemt_upstream_connect_attempt_total 2074
telemt_upstream_connect_success_total 2062
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 2074
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1123
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 923
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_failed_total 1
telemt_me_reconnect_attempts_total 1426
telemt_me_reconnect_success_total 1383
telemt_me_reader_eof_total 1400
telemt_me_idle_close_by_peer_total 1399
telemt_me_route_drop_no_conn_total 1128533
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1040338
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3326
telemt_desync_full_logged_total 958
telemt_desync_suppressed_total 2368
telemt_desync_frames_bucket_total{bucket="1_2"} 655
telemt_desync_frames_bucket_total{bucket="3_10"} 1351
telemt_desync_frames_bucket_total{bucket="gt_10"} 1320
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 1382
telemt_me_writer_restored_same_endpoint_total 1382
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 1068
telemt_user_connections_total{user="hello"} 1039614
telemt_user_connections_current{user="hello"} 3911
telemt_user_octets_from_client{user="hello"} 25408439856 (23.66 GB)
telemt_user_octets_to_client{user="hello"} 292156830364 (272.09 GB)
telemt_user_unique_ips_current{user="hello"} 1176
telemt_user_unique_ips_recent_window{user="hello"} 532
```

## koara.io

```
telemt 3.3.20

telemt_uptime_seconds 11795.8 (3h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 833723
telemt_connections_bad_total 60527
telemt_handshake_timeouts_total 20542
telemt_upstream_connect_attempt_total 10513
telemt_upstream_connect_success_total 10513
telemt_upstream_connect_attempts_per_request{bucket="1"} 10513
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8164
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2338
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 607339
telemt_me_reconnect_success_total 1649
telemt_me_reader_eof_total 1660
telemt_me_idle_close_by_peer_total 1659
telemt_me_route_drop_no_conn_total 367826
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 622030
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1558
telemt_desync_full_logged_total 553
telemt_desync_suppressed_total 1005
telemt_desync_frames_bucket_total{bucket="1_2"} 384
telemt_desync_frames_bucket_total{bucket="3_10"} 589
telemt_desync_frames_bucket_total{bucket="gt_10"} 585
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1654
telemt_me_refill_failed_total 19672
telemt_me_writer_restored_same_endpoint_total 1614
telemt_me_writer_restored_fallback_total 35
telemt_me_async_recovery_trigger_total 14895
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 629675
telemt_user_connections_current{user="hello"} 3095
telemt_user_octets_from_client{user="hello"} 7600211899 (7.08 GB)
telemt_user_octets_to_client{user="hello"} 258094636068 (240.37 GB)
telemt_user_msgs_from_client{user="hello"} 68547
telemt_user_msgs_to_client{user="hello"} 285346
telemt_user_unique_ips_current{user="hello"} 954
telemt_user_unique_ips_recent_window{user="hello"} 435
```

## landvps.ru

```
telemt 3.3.20

telemt_uptime_seconds 11826.4 (3h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1333231
telemt_connections_bad_total 19236
telemt_handshake_timeouts_total 155988
telemt_upstream_connect_attempt_total 12272
telemt_upstream_connect_success_total 12100
telemt_upstream_connect_fail_total 172
telemt_upstream_connect_attempts_per_request{bucket="1"} 12272
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10826
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1235
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 172
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 699
telemt_me_reconnect_attempts_total 2824424
telemt_me_reconnect_success_total 1174
telemt_me_reader_eof_total 1549
telemt_me_idle_close_by_peer_total 1549
telemt_me_route_drop_no_conn_total 1949083
telemt_me_route_drop_channel_closed_total 20
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1042115
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
telemt_desync_total 2099
telemt_desync_full_logged_total 684
telemt_desync_suppressed_total 1415
telemt_desync_frames_bucket_total{bucket="1_2"} 521
telemt_desync_frames_bucket_total{bucket="3_10"} 827
telemt_desync_frames_bucket_total{bucket="gt_10"} 751
telemt_me_writer_removed_unexpected_total 1593
telemt_me_refill_failed_total 99964
telemt_me_writer_restored_same_endpoint_total 1079
telemt_me_writer_restored_fallback_total 95
telemt_me_async_recovery_trigger_total 365465
telemt_me_writer_removed_unexpected_minus_restored_total 419
telemt_user_connections_total{user="hello"} 1060834
telemt_user_connections_current{user="hello"} 3007
telemt_user_octets_from_client{user="hello"} 7545409422 (7.03 GB)
telemt_user_octets_to_client{user="hello"} 180433404153 (168.04 GB)
telemt_user_msgs_from_client{user="hello"} 80007
telemt_user_msgs_to_client{user="hello"} 158054
telemt_user_unique_ips_current{user="hello"} 893
telemt_user_unique_ips_recent_window{user="hello"} 414
```

## rdp-onedash.ru

```
telemt 3.3.20

telemt_uptime_seconds 11721.0 (3h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 856158
telemt_connections_bad_total 33334
telemt_handshake_timeouts_total 14760
telemt_upstream_connect_attempt_total 11485
telemt_upstream_connect_success_total 11484
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 11485
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10009
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1252
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 223
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 61
telemt_me_reconnect_attempts_total 2983336
telemt_me_reconnect_success_total 1376
telemt_me_reader_eof_total 1367
telemt_me_idle_close_by_peer_total 1367
telemt_me_route_drop_no_conn_total 534042
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 732760
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2532
telemt_desync_full_logged_total 823
telemt_desync_suppressed_total 1709
telemt_desync_frames_bucket_total{bucket="1_2"} 380
telemt_desync_frames_bucket_total{bucket="3_10"} 995
telemt_desync_frames_bucket_total{bucket="gt_10"} 1157
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 1347
telemt_me_refill_failed_total 107153
telemt_me_writer_restored_same_endpoint_total 1261
telemt_me_writer_restored_fallback_total 115
telemt_me_async_recovery_trigger_total 267383
telemt_user_connections_total{user="hello"} 733025
telemt_user_connections_current{user="hello"} 3472
telemt_user_octets_from_client{user="hello"} 10291428037 (9.58 GB)
telemt_user_octets_to_client{user="hello"} 282305307317 (262.92 GB)
telemt_user_msgs_from_client{user="hello"} 86293
telemt_user_msgs_to_client{user="hello"} 266108
telemt_user_unique_ips_current{user="hello"} 1029
telemt_user_unique_ips_recent_window{user="hello"} 480
```

## hostvds.com

```
telemt 3.3.20

telemt_uptime_seconds 11606.1 (3h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 243690
telemt_connections_bad_total 22472
telemt_handshake_timeouts_total 1907
telemt_upstream_connect_attempt_total 2286
telemt_upstream_connect_success_total 2286
telemt_upstream_connect_attempts_per_request{bucket="1"} 2286
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1142
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1144
telemt_me_reconnect_attempts_total 1673
telemt_me_reconnect_success_total 1657
telemt_me_reader_eof_total 1692
telemt_me_idle_close_by_peer_total 1691
telemt_me_route_drop_no_conn_total 117404
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 210063
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 532
telemt_desync_full_logged_total 184
telemt_desync_suppressed_total 348
telemt_desync_frames_bucket_total{bucket="1_2"} 98
telemt_desync_frames_bucket_total{bucket="3_10"} 187
telemt_desync_frames_bucket_total{bucket="gt_10"} 247
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1669
telemt_me_writer_restored_same_endpoint_total 1649
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 130
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 200371
telemt_user_connections_current{user="hello"} 954
telemt_user_octets_from_client{user="hello"} 3876000040 (3.61 GB)
telemt_user_octets_to_client{user="hello"} 46314617120 (43.13 GB)
telemt_user_unique_ips_current{user="hello"} 322
telemt_user_unique_ips_recent_window{user="hello"} 140
```

## 4vps.su

```
telemt 3.3.20

telemt_uptime_seconds 11677.0 (3h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 643099
telemt_connections_bad_total 54561
telemt_handshake_timeouts_total 15096
telemt_upstream_connect_attempt_total 2120
telemt_upstream_connect_success_total 2099
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 2120
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1167
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 924
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_reconnect_attempts_total 1495
telemt_me_reconnect_success_total 1474
telemt_me_reader_eof_total 1500
telemt_me_idle_close_by_peer_total 1500
telemt_me_route_drop_no_conn_total 280624
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 524824
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1940
telemt_desync_full_logged_total 682
telemt_desync_suppressed_total 1258
telemt_desync_frames_bucket_total{bucket="1_2"} 327
telemt_desync_frames_bucket_total{bucket="3_10"} 699
telemt_desync_frames_bucket_total{bucket="gt_10"} 914
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 1477
telemt_me_writer_restored_same_endpoint_total 1464
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 524403
telemt_user_connections_current{user="hello"} 2859
telemt_user_octets_from_client{user="hello"} 10773442508 (10.03 GB)
telemt_user_octets_to_client{user="hello"} 267757617092 (249.37 GB)
telemt_user_unique_ips_current{user="hello"} 882
telemt_user_unique_ips_recent_window{user="hello"} 370
```