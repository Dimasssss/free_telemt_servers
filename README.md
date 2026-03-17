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

# Server Metrics 2026-03-17 21:01:59 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 94602.5 (26h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1167523
telemt_connections_bad_total 8633
telemt_handshake_timeouts_total 30787
telemt_upstream_connect_attempt_total 21543
telemt_upstream_connect_success_total 21053
telemt_upstream_connect_fail_total 490
telemt_upstream_connect_attempts_per_request{bucket="1"} 21543
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10889
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9957
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 207
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 490
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 31132
telemt_me_reconnect_success_total 14002
telemt_me_reader_eof_total 15221
telemt_me_idle_close_by_peer_total 15220
telemt_me_route_drop_no_conn_total 521738
telemt_me_route_drop_channel_closed_total 155
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1070280
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7123
telemt_desync_full_logged_total 2043
telemt_desync_suppressed_total 5080
telemt_desync_frames_bucket_total{bucket="1_2"} 1912
telemt_desync_frames_bucket_total{bucket="3_10"} 2704
telemt_desync_frames_bucket_total{bucket="gt_10"} 2507
telemt_pool_swap_total 74
telemt_me_writer_removed_unexpected_total 14745
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 13980
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 743
telemt_user_connections_total{user="hello"} 1064515
telemt_user_connections_current{user="hello"} 684
telemt_user_octets_from_client{user="hello"} 19022383131 (17.72 GB)
telemt_user_octets_to_client{user="hello"} 375257629723 (349.49 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 257
telemt_user_unique_ips_recent_window{user="hello"} 82
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 94853.9 (26h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1205588
telemt_connections_bad_total 59450
telemt_handshake_timeouts_total 43402
telemt_upstream_connect_attempt_total 457076
telemt_upstream_connect_success_total 456191
telemt_upstream_connect_fail_total 885
telemt_upstream_connect_attempts_per_request{bucket="1"} 457076
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 382603
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30296
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43290
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 885
telemt_me_keepalive_timeout_total 342
telemt_me_reconnect_attempts_total 57589
telemt_me_reconnect_success_total 14436
telemt_me_reader_eof_total 16396
telemt_me_idle_close_by_peer_total 16396
telemt_me_route_drop_no_conn_total 305317
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 602988
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2635
telemt_desync_full_logged_total 847
telemt_desync_suppressed_total 1788
telemt_desync_frames_bucket_total{bucket="1_2"} 500
telemt_desync_frames_bucket_total{bucket="3_10"} 1104
telemt_desync_frames_bucket_total{bucket="gt_10"} 1031
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 15964
telemt_me_refill_failed_total 1344
telemt_me_writer_restored_same_endpoint_total 14420
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 1528
telemt_user_connections_total{user="hello"} 1039415
telemt_user_connections_current{user="hello"} 1365
telemt_user_octets_from_client{user="hello"} 14450415806 (13.46 GB)
telemt_user_octets_to_client{user="hello"} 344401786306 (320.75 GB)
telemt_user_msgs_from_client{user="hello"} 7417237
telemt_user_msgs_to_client{user="hello"} 31692884
telemt_user_unique_ips_current{user="hello"} 411
telemt_user_unique_ips_recent_window{user="hello"} 148
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 94630.0 (26h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 673885
telemt_connections_bad_total 38738
telemt_handshake_timeouts_total 22494
telemt_upstream_connect_attempt_total 22710
telemt_upstream_connect_success_total 22579
telemt_upstream_connect_fail_total 131
telemt_upstream_connect_attempts_per_request{bucket="1"} 22710
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10331
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12154
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 89
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 131
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 38452
telemt_me_reconnect_success_total 17777
telemt_me_reader_eof_total 19401
telemt_me_idle_close_by_peer_total 19394
telemt_me_route_drop_no_conn_total 286316
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 580441
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1851
telemt_desync_full_logged_total 557
telemt_desync_suppressed_total 1294
telemt_desync_frames_bucket_total{bucket="1_2"} 518
telemt_desync_frames_bucket_total{bucket="3_10"} 728
telemt_desync_frames_bucket_total{bucket="gt_10"} 605
telemt_pool_swap_total 71
telemt_me_writer_removed_unexpected_total 18665
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 17765
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 888
telemt_user_connections_total{user="hello"} 578712
telemt_user_connections_current{user="hello"} 1001
telemt_user_octets_from_client{user="hello"} 28641402104 (26.67 GB)
telemt_user_octets_to_client{user="hello"} 241526525688 (224.94 GB)
telemt_user_unique_ips_current{user="hello"} 284
telemt_user_unique_ips_recent_window{user="hello"} 87
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 94689.3 (26h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1175530
telemt_connections_bad_total 35977
telemt_handshake_timeouts_total 21204
telemt_upstream_connect_attempt_total 82287
telemt_upstream_connect_success_total 81872
telemt_upstream_connect_fail_total 415
telemt_upstream_connect_attempts_per_request{bucket="1"} 82287
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 69662
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11839
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 29
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 342
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 415
telemt_me_keepalive_timeout_total 273
telemt_me_reconnect_attempts_total 34056
telemt_me_reconnect_success_total 13742
telemt_me_reader_eof_total 15144
telemt_me_idle_close_by_peer_total 15143
telemt_me_route_drop_no_conn_total 489383
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 959479
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3301
telemt_desync_full_logged_total 1052
telemt_desync_suppressed_total 2249
telemt_desync_frames_bucket_total{bucket="1_2"} 812
telemt_desync_frames_bucket_total{bucket="3_10"} 1396
telemt_desync_frames_bucket_total{bucket="gt_10"} 1093
telemt_pool_swap_total 70
telemt_me_writer_removed_unexpected_total 14632
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 13733
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 890
telemt_user_connections_total{user="hello"} 1021997
telemt_user_connections_current{user="hello"} 1199
telemt_user_octets_from_client{user="hello"} 15243323379 (14.20 GB)
telemt_user_octets_to_client{user="hello"} 426634723885 (397.33 GB)
telemt_user_msgs_from_client{user="hello"} 734453
telemt_user_msgs_to_client{user="hello"} 5166140
telemt_user_unique_ips_current{user="hello"} 343
telemt_user_unique_ips_recent_window{user="hello"} 124
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 94661.3 (26h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 728991
telemt_connections_bad_total 90621
telemt_handshake_timeouts_total 6219
telemt_upstream_connect_attempt_total 41102
telemt_upstream_connect_success_total 40555
telemt_upstream_connect_fail_total 547
telemt_upstream_connect_attempts_per_request{bucket="1"} 41102
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26125
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14037
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 393
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 547
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 51796
telemt_me_reconnect_success_total 19311
telemt_me_reader_eof_total 21033
telemt_me_idle_close_by_peer_total 21031
telemt_me_route_drop_no_conn_total 228029
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 576370
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2669
telemt_desync_full_logged_total 772
telemt_desync_suppressed_total 1897
telemt_desync_frames_bucket_total{bucket="1_2"} 881
telemt_desync_frames_bucket_total{bucket="3_10"} 1066
telemt_desync_frames_bucket_total{bucket="gt_10"} 722
telemt_pool_swap_total 48
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 20654
telemt_me_refill_failed_total 1010
telemt_me_writer_restored_same_endpoint_total 19303
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1343
telemt_user_connections_total{user="hello"} 592984
telemt_user_connections_current{user="hello"} 1089
telemt_user_octets_from_client{user="hello"} 11586837224 (10.79 GB)
telemt_user_octets_to_client{user="hello"} 286483532856 (266.81 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 322
telemt_user_unique_ips_recent_window{user="hello"} 99
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 94822.2 (26h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 975882
telemt_connections_bad_total 69852
telemt_handshake_timeouts_total 9259
telemt_upstream_connect_attempt_total 18773
telemt_upstream_connect_success_total 18663
telemt_upstream_connect_fail_total 110
telemt_upstream_connect_attempts_per_request{bucket="1"} 18773
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8891
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9656
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 106
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 110
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 25185
telemt_me_reconnect_success_total 13908
telemt_me_reader_eof_total 15112
telemt_me_idle_close_by_peer_total 15110
telemt_me_route_drop_no_conn_total 679611
telemt_me_route_drop_channel_closed_total 86
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 974094
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1968
telemt_desync_full_logged_total 688
telemt_desync_suppressed_total 1280
telemt_desync_frames_bucket_total{bucket="1_2"} 453
telemt_desync_frames_bucket_total{bucket="3_10"} 746
telemt_desync_frames_bucket_total{bucket="gt_10"} 769
telemt_pool_swap_total 80
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 14490
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 13894
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 582
telemt_user_connections_total{user="hello"} 837127
telemt_user_connections_current{user="hello"} 640
telemt_user_octets_from_client{user="hello"} 12973342144 (12.08 GB)
telemt_user_octets_to_client{user="hello"} 361019308704 (336.23 GB)
telemt_user_unique_ips_current{user="hello"} 221
telemt_user_unique_ips_recent_window{user="hello"} 73
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 42589.4 (11h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 308748
telemt_connections_bad_total 40522
telemt_handshake_timeouts_total 9199
telemt_upstream_connect_attempt_total 17421
telemt_upstream_connect_success_total 17260
telemt_upstream_connect_fail_total 161
telemt_upstream_connect_attempts_per_request{bucket="1"} 17421
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9253
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7915
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 92
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 161
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 26536
telemt_me_reconnect_success_total 14944
telemt_me_reader_eof_total 15792
telemt_me_idle_close_by_peer_total 15792
telemt_me_seq_mismatch_total 20
telemt_me_route_drop_no_conn_total 76064
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 237017
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 740
telemt_desync_full_logged_total 209
telemt_desync_suppressed_total 531
telemt_desync_frames_bucket_total{bucket="1_2"} 199
telemt_desync_frames_bucket_total{bucket="3_10"} 285
telemt_desync_frames_bucket_total{bucket="gt_10"} 256
telemt_pool_swap_total 21
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 15481
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 14916
telemt_me_writer_restored_fallback_total 28
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 537
telemt_user_connections_total{user="hello"} 236963
telemt_user_connections_current{user="hello"} 679
telemt_user_octets_from_client{user="hello"} 20784901041 (19.36 GB)
telemt_user_octets_to_client{user="hello"} 199104249398 (185.43 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 204
telemt_user_unique_ips_recent_window{user="hello"} 68
```