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

# Server Metrics 2026-03-18 11:02:32 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.20

telemt_uptime_seconds 8491.4 (2h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 306874
telemt_connections_bad_total 1928
telemt_handshake_timeouts_total 7237
telemt_upstream_connect_attempt_total 64690
telemt_upstream_connect_success_total 63762
telemt_upstream_connect_fail_total 928
telemt_upstream_connect_attempts_per_request{bucket="1"} 64690
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 59820
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3359
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 583
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 928
telemt_me_keepalive_timeout_total 6
telemt_me_reconnect_attempts_total 509134
telemt_me_reconnect_success_total 1338
telemt_me_reader_eof_total 1337
telemt_me_idle_close_by_peer_total 1335
telemt_me_route_drop_no_conn_total 177343
telemt_me_route_drop_channel_closed_total 59
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 211581
telemt_me_writer_pick_total{mode="p2c",result="full"} 21
telemt_me_writer_pick_total{mode="p2c",result="closed"} 54
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 929
telemt_desync_full_logged_total 294
telemt_desync_suppressed_total 635
telemt_desync_frames_bucket_total{bucket="1_2"} 270
telemt_desync_frames_bucket_total{bucket="3_10"} 342
telemt_desync_frames_bucket_total{bucket="gt_10"} 317
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 1370
telemt_me_refill_failed_total 16552
telemt_me_writer_restored_same_endpoint_total 1233
telemt_me_writer_restored_fallback_total 105
telemt_me_async_recovery_trigger_total 11769
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 270045
telemt_user_connections_current{user="hello"} 1497
telemt_user_octets_from_client{user="hello"} 3474948544 (3.24 GB)
telemt_user_octets_to_client{user="hello"} 69263123705 (64.51 GB)
telemt_user_msgs_from_client{user="hello"} 846607
telemt_user_msgs_to_client{user="hello"} 1165163
telemt_user_unique_ips_current{user="hello"} 513
telemt_user_unique_ips_recent_window{user="hello"} 278
```

## psb.hosting

```
telemt 3.3.20

telemt_uptime_seconds 8523.3 (2h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 912736
telemt_connections_bad_total 78591
telemt_handshake_timeouts_total 20434
telemt_upstream_connect_attempt_total 1530
telemt_upstream_connect_success_total 1518
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 1530
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 854
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 651
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_failed_total 1
telemt_me_reconnect_attempts_total 1056
telemt_me_reconnect_success_total 1020
telemt_me_reader_eof_total 1002
telemt_me_idle_close_by_peer_total 1002
telemt_me_route_drop_no_conn_total 903574
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 771820
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2653
telemt_desync_full_logged_total 755
telemt_desync_suppressed_total 1898
telemt_desync_frames_bucket_total{bucket="1_2"} 541
telemt_desync_frames_bucket_total{bucket="3_10"} 1056
telemt_desync_frames_bucket_total{bucket="gt_10"} 1056
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1014
telemt_me_writer_restored_same_endpoint_total 1019
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 1068
telemt_user_connections_total{user="hello"} 771070
telemt_user_connections_current{user="hello"} 3979
telemt_user_octets_from_client{user="hello"} 12942538800 (12.05 GB)
telemt_user_octets_to_client{user="hello"} 211528188868 (197.00 GB)
telemt_user_unique_ips_current{user="hello"} 1179
telemt_user_unique_ips_recent_window{user="hello"} 819
```

## koara.io

```
telemt 3.3.20

telemt_uptime_seconds 8438.4 (2h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 583187
telemt_connections_bad_total 41628
telemt_handshake_timeouts_total 14432
telemt_upstream_connect_attempt_total 9975
telemt_upstream_connect_success_total 9975
telemt_upstream_connect_attempts_per_request{bucket="1"} 9975
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7899
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2065
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 40
telemt_me_reconnect_attempts_total 606967
telemt_me_reconnect_success_total 1281
telemt_me_reader_eof_total 1263
telemt_me_idle_close_by_peer_total 1262
telemt_me_route_drop_no_conn_total 286399
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 441594
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1109
telemt_desync_full_logged_total 376
telemt_desync_suppressed_total 733
telemt_desync_frames_bucket_total{bucket="1_2"} 277
telemt_desync_frames_bucket_total{bucket="3_10"} 426
telemt_desync_frames_bucket_total{bucket="gt_10"} 406
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 1281
telemt_me_refill_failed_total 19672
telemt_me_writer_restored_same_endpoint_total 1246
telemt_me_writer_restored_fallback_total 35
telemt_me_async_recovery_trigger_total 14895
telemt_user_connections_total{user="hello"} 449403
telemt_user_connections_current{user="hello"} 3116
telemt_user_octets_from_client{user="hello"} 4906829967 (4.57 GB)
telemt_user_octets_to_client{user="hello"} 168888822448 (157.29 GB)
telemt_user_msgs_from_client{user="hello"} 68547
telemt_user_msgs_to_client{user="hello"} 285346
telemt_user_unique_ips_current{user="hello"} 916
telemt_user_unique_ips_recent_window{user="hello"} 472
```

## landvps.ru

```
telemt 3.3.20

telemt_uptime_seconds 8468.4 (2h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1055591
telemt_connections_bad_total 12952
telemt_handshake_timeouts_total 123343
telemt_upstream_connect_attempt_total 11981
telemt_upstream_connect_success_total 11841
telemt_upstream_connect_fail_total 140
telemt_upstream_connect_attempts_per_request{bucket="1"} 11981
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10640
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1165
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 140
telemt_me_keepalive_timeout_total 699
telemt_me_reconnect_attempts_total 2820235
telemt_me_reconnect_success_total 1088
telemt_me_reader_eof_total 1337
telemt_me_idle_close_by_peer_total 1337
telemt_me_route_drop_no_conn_total 1807531
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 824975
telemt_me_writer_pick_total{mode="p2c",result="success_fallback"} 8840
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_writer_pick_blocking_fallback_total 8840
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1443
telemt_desync_full_logged_total 438
telemt_desync_suppressed_total 1005
telemt_desync_frames_bucket_total{bucket="1_2"} 362
telemt_desync_frames_bucket_total{bucket="3_10"} 582
telemt_desync_frames_bucket_total{bucket="gt_10"} 499
telemt_me_writer_removed_unexpected_total 1375
telemt_me_refill_failed_total 99836
telemt_me_writer_restored_same_endpoint_total 993
telemt_me_writer_restored_fallback_total 95
telemt_me_async_recovery_trigger_total 365465
telemt_me_writer_removed_unexpected_minus_restored_total 287
telemt_user_connections_total{user="hello"} 843864
telemt_user_connections_current{user="hello"} 3429
telemt_user_octets_from_client{user="hello"} 5813192486 (5.41 GB)
telemt_user_octets_to_client{user="hello"} 119669309221 (111.45 GB)
telemt_user_msgs_from_client{user="hello"} 80007
telemt_user_msgs_to_client{user="hello"} 158054
telemt_user_unique_ips_current{user="hello"} 951
telemt_user_unique_ips_recent_window{user="hello"} 795
```

## rdp-onedash.ru

```
telemt 3.3.20

telemt_uptime_seconds 8363.6 (2h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 581792
telemt_connections_bad_total 17753
telemt_handshake_timeouts_total 8903
telemt_upstream_connect_attempt_total 11066
telemt_upstream_connect_success_total 11065
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 11066
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9783
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1063
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 219
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 61
telemt_me_reconnect_attempts_total 2983046
telemt_me_reconnect_success_total 1088
telemt_me_reader_eof_total 1055
telemt_me_idle_close_by_peer_total 1055
telemt_me_route_drop_no_conn_total 255988
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 490355
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1792
telemt_desync_full_logged_total 599
telemt_desync_suppressed_total 1193
telemt_desync_frames_bucket_total{bucket="1_2"} 277
telemt_desync_frames_bucket_total{bucket="3_10"} 691
telemt_desync_frames_bucket_total{bucket="gt_10"} 824
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1049
telemt_me_refill_failed_total 107153
telemt_me_writer_restored_same_endpoint_total 973
telemt_me_writer_restored_fallback_total 115
telemt_me_async_recovery_trigger_total 267383
telemt_user_connections_total{user="hello"} 498687
telemt_user_connections_current{user="hello"} 3676
telemt_user_octets_from_client{user="hello"} 7802342161 (7.27 GB)
telemt_user_octets_to_client{user="hello"} 202470460665 (188.57 GB)
telemt_user_msgs_from_client{user="hello"} 86293
telemt_user_msgs_to_client{user="hello"} 266108
telemt_user_unique_ips_current{user="hello"} 1080
telemt_user_unique_ips_recent_window{user="hello"} 674
```

## hostvds.com

```
telemt 3.3.20

telemt_uptime_seconds 8248.7 (2h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 179250
telemt_connections_bad_total 19716
telemt_handshake_timeouts_total 1244
telemt_upstream_connect_attempt_total 1527
telemt_upstream_connect_success_total 1527
telemt_upstream_connect_attempts_per_request{bucket="1"} 1527
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 823
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 704
telemt_me_reconnect_attempts_total 1052
telemt_me_reconnect_success_total 1042
telemt_me_reader_eof_total 1056
telemt_me_idle_close_by_peer_total 1055
telemt_me_route_drop_no_conn_total 90318
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 153657
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 379
telemt_desync_full_logged_total 132
telemt_desync_suppressed_total 247
telemt_desync_frames_bucket_total{bucket="1_2"} 74
telemt_desync_frames_bucket_total{bucket="3_10"} 137
telemt_desync_frames_bucket_total{bucket="gt_10"} 168
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 1047
telemt_me_writer_restored_same_endpoint_total 1034
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 130
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 143992
telemt_user_connections_current{user="hello"} 987
telemt_user_octets_from_client{user="hello"} 2100268944 (1.96 GB)
telemt_user_octets_to_client{user="hello"} 35953374136 (33.48 GB)
telemt_user_unique_ips_current{user="hello"} 351
telemt_user_unique_ips_recent_window{user="hello"} 182
```

## 4vps.su

```
telemt 3.3.20

telemt_uptime_seconds 8319.5 (2h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 424972
telemt_connections_bad_total 22376
telemt_handshake_timeouts_total 9537
telemt_upstream_connect_attempt_total 1524
telemt_upstream_connect_success_total 1505
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 1524
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 843
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 654
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_reconnect_attempts_total 1032
telemt_me_reconnect_success_total 1013
telemt_me_reader_eof_total 1015
telemt_me_idle_close_by_peer_total 1015
telemt_me_route_drop_no_conn_total 213022
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 364378
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1366
telemt_desync_full_logged_total 474
telemt_desync_suppressed_total 892
telemt_desync_frames_bucket_total{bucket="1_2"} 260
telemt_desync_frames_bucket_total{bucket="3_10"} 493
telemt_desync_frames_bucket_total{bucket="gt_10"} 613
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 1011
telemt_me_writer_restored_same_endpoint_total 1003
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 2494
telemt_user_connections_total{user="hello"} 364154
telemt_user_connections_current{user="hello"} 3077
telemt_user_octets_from_client{user="hello"} 6130650236 (5.71 GB)
telemt_user_octets_to_client{user="hello"} 184832077348 (172.14 GB)
telemt_user_unique_ips_current{user="hello"} 840
telemt_user_unique_ips_recent_window{user="hello"} 439
```