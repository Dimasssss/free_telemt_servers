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

# Server Metrics 2026-03-18 05:21:16 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 124558.8 (34h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1453942
telemt_connections_bad_total 10580
telemt_handshake_timeouts_total 35142
telemt_upstream_connect_attempt_total 27197
telemt_upstream_connect_success_total 26680
telemt_upstream_connect_fail_total 517
telemt_upstream_connect_attempts_per_request{bucket="1"} 27197
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13677
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12795
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 517
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 266
telemt_me_reconnect_attempts_total 35336
telemt_me_reconnect_success_total 18188
telemt_me_reader_eof_total 19728
telemt_me_idle_close_by_peer_total 19727
telemt_me_route_drop_no_conn_total 607428
telemt_me_route_drop_channel_closed_total 167
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1316036
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8104
telemt_desync_full_logged_total 2432
telemt_desync_suppressed_total 5672
telemt_desync_frames_bucket_total{bucket="1_2"} 2133
telemt_desync_frames_bucket_total{bucket="3_10"} 3105
telemt_desync_frames_bucket_total{bucket="gt_10"} 2866
telemt_pool_swap_total 107
telemt_me_writer_removed_unexpected_total 18996
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 18166
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 808
telemt_user_connections_total{user="hello"} 1310267
telemt_user_connections_current{user="hello"} 896
telemt_user_octets_from_client{user="hello"} 30924357791 (28.80 GB)
telemt_user_octets_to_client{user="hello"} 464906327979 (432.98 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 360
telemt_user_unique_ips_recent_window{user="hello"} 129
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 124810.6 (34h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1567035
telemt_connections_bad_total 74330
telemt_handshake_timeouts_total 51734
telemt_upstream_connect_attempt_total 470634
telemt_upstream_connect_success_total 469008
telemt_upstream_connect_fail_total 1626
telemt_upstream_connect_attempts_per_request{bucket="1"} 470634
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 390996
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34645
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43365
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1626
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 343
telemt_me_reconnect_attempts_total 126611
telemt_me_reconnect_success_total 19882
telemt_me_reader_eof_total 22168
telemt_me_idle_close_by_peer_total 22155
telemt_me_route_drop_no_conn_total 410450
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 923076
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4121
telemt_desync_full_logged_total 1434
telemt_desync_suppressed_total 2687
telemt_desync_frames_bucket_total{bucket="1_2"} 813
telemt_desync_frames_bucket_total{bucket="3_10"} 1682
telemt_desync_frames_bucket_total{bucket="gt_10"} 1626
telemt_pool_swap_total 72
telemt_me_writer_removed_unexpected_total 21508
telemt_me_refill_failed_total 3329
telemt_me_writer_restored_same_endpoint_total 19864
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 6668
telemt_me_writer_removed_unexpected_minus_restored_total 1626
telemt_user_connections_total{user="hello"} 1365426
telemt_user_connections_current{user="hello"} 1593
telemt_user_octets_from_client{user="hello"} 18793615413 (17.50 GB)
telemt_user_octets_to_client{user="hello"} 516138288170 (480.69 GB)
telemt_user_msgs_from_client{user="hello"} 7472583
telemt_user_msgs_to_client{user="hello"} 31958899
telemt_user_unique_ips_current{user="hello"} 534
telemt_user_unique_ips_recent_window{user="hello"} 200
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 124586.6 (34h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1019540
telemt_connections_bad_total 70678
telemt_handshake_timeouts_total 28290
telemt_upstream_connect_attempt_total 28581
telemt_upstream_connect_success_total 28420
telemt_upstream_connect_fail_total 161
telemt_upstream_connect_attempts_per_request{bucket="1"} 28581
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13035
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15283
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 97
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 161
telemt_me_keepalive_timeout_total 124
telemt_me_reconnect_attempts_total 42872
telemt_me_reconnect_success_total 22170
telemt_me_reader_eof_total 24096
telemt_me_idle_close_by_peer_total 24089
telemt_me_route_drop_no_conn_total 372281
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 822238
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2740
telemt_desync_full_logged_total 899
telemt_desync_suppressed_total 1841
telemt_desync_frames_bucket_total{bucket="1_2"} 749
telemt_desync_frames_bucket_total{bucket="3_10"} 1065
telemt_desync_frames_bucket_total{bucket="gt_10"} 926
telemt_pool_swap_total 104
telemt_me_writer_removed_unexpected_total 23113
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 22158
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 943
telemt_user_connections_total{user="hello"} 820341
telemt_user_connections_current{user="hello"} 1250
telemt_user_octets_from_client{user="hello"} 45733938028 (42.59 GB)
telemt_user_octets_to_client{user="hello"} 391183037976 (364.32 GB)
telemt_user_unique_ips_current{user="hello"} 371
telemt_user_unique_ips_recent_window{user="hello"} 144
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 124645.9 (34h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1459030
telemt_connections_bad_total 71924
telemt_handshake_timeouts_total 24763
telemt_upstream_connect_attempt_total 91578
telemt_upstream_connect_success_total 89135
telemt_upstream_connect_fail_total 2443
telemt_upstream_connect_attempts_per_request{bucket="1"} 91578
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 73773
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14950
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 379
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2443
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 320
telemt_me_reconnect_attempts_total 38580
telemt_me_reconnect_success_total 18164
telemt_me_reader_eof_total 19931
telemt_me_idle_close_by_peer_total 19928
telemt_me_route_drop_no_conn_total 589673
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1189806
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4553
telemt_desync_full_logged_total 1487
telemt_desync_suppressed_total 3066
telemt_desync_frames_bucket_total{bucket="1_2"} 1094
telemt_desync_frames_bucket_total{bucket="3_10"} 1897
telemt_desync_frames_bucket_total{bucket="gt_10"} 1562
telemt_pool_swap_total 99
telemt_me_writer_removed_unexpected_total 19138
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 18144
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 974
telemt_user_connections_total{user="hello"} 1253081
telemt_user_connections_current{user="hello"} 1454
telemt_user_octets_from_client{user="hello"} 19967360550 (18.60 GB)
telemt_user_octets_to_client{user="hello"} 613185998486 (571.07 GB)
telemt_user_msgs_from_client{user="hello"} 744103
telemt_user_msgs_to_client{user="hello"} 5214294
telemt_user_unique_ips_current{user="hello"} 447
telemt_user_unique_ips_recent_window{user="hello"} 176
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 124617.7 (34h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1020419
telemt_connections_bad_total 103928
telemt_handshake_timeouts_total 9922
telemt_upstream_connect_attempt_total 48577
telemt_upstream_connect_success_total 47907
telemt_upstream_connect_fail_total 670
telemt_upstream_connect_attempts_per_request{bucket="1"} 48577
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29587
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17897
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 423
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 670
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 60191
telemt_me_reconnect_success_total 25225
telemt_me_reader_eof_total 27286
telemt_me_idle_close_by_peer_total 27283
telemt_me_route_drop_no_conn_total 327707
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 834648
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3699
telemt_desync_full_logged_total 1132
telemt_desync_suppressed_total 2567
telemt_desync_frames_bucket_total{bucket="1_2"} 1081
telemt_desync_frames_bucket_total{bucket="3_10"} 1436
telemt_desync_frames_bucket_total{bucket="gt_10"} 1182
telemt_pool_swap_total 66
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 26704
telemt_me_refill_failed_total 1087
telemt_me_writer_restored_same_endpoint_total 25217
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1479
telemt_user_connections_total{user="hello"} 851124
telemt_user_connections_current{user="hello"} 1366
telemt_user_octets_from_client{user="hello"} 16175021068 (15.06 GB)
telemt_user_octets_to_client{user="hello"} 431220335784 (401.61 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 470
telemt_user_unique_ips_recent_window{user="hello"} 178
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 124778.9 (34h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1198707
telemt_connections_bad_total 127375
telemt_handshake_timeouts_total 10469
telemt_upstream_connect_attempt_total 24831
telemt_upstream_connect_success_total 24686
telemt_upstream_connect_fail_total 145
telemt_upstream_connect_attempts_per_request{bucket="1"} 24831
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11848
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12719
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 145
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 29786
telemt_me_reconnect_success_total 18492
telemt_me_reader_eof_total 20038
telemt_me_idle_close_by_peer_total 20036
telemt_me_route_drop_no_conn_total 821713
telemt_me_route_drop_channel_closed_total 90
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1178297
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2249
telemt_desync_full_logged_total 783
telemt_desync_suppressed_total 1466
telemt_desync_frames_bucket_total{bucket="1_2"} 502
telemt_desync_frames_bucket_total{bucket="3_10"} 856
telemt_desync_frames_bucket_total{bucket="gt_10"} 891
telemt_pool_swap_total 113
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 19129
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 18478
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 298
telemt_me_writer_removed_unexpected_minus_restored_total 637
telemt_user_connections_total{user="hello"} 986978
telemt_user_connections_current{user="hello"} 697
telemt_user_octets_from_client{user="hello"} 15645835020 (14.57 GB)
telemt_user_octets_to_client{user="hello"} 440077508816 (409.85 GB)
telemt_user_unique_ips_current{user="hello"} 234
telemt_user_unique_ips_recent_window{user="hello"} 96
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 72545.9 (20h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 548698
telemt_connections_bad_total 54100
telemt_handshake_timeouts_total 13311
telemt_upstream_connect_attempt_total 25441
telemt_upstream_connect_success_total 25180
telemt_upstream_connect_fail_total 261
telemt_upstream_connect_attempts_per_request{bucket="1"} 25441
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13462
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11622
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 261
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 33038
telemt_me_reconnect_success_total 21425
telemt_me_reader_eof_total 22640
telemt_me_idle_close_by_peer_total 22640
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 134222
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 396558
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 37
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1722
telemt_desync_full_logged_total 570
telemt_desync_suppressed_total 1152
telemt_desync_frames_bucket_total{bucket="1_2"} 288
telemt_desync_frames_bucket_total{bucket="3_10"} 769
telemt_desync_frames_bucket_total{bucket="gt_10"} 665
telemt_pool_swap_total 50
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 22013
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 21382
telemt_me_writer_restored_fallback_total 43
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 588
telemt_user_connections_total{user="hello"} 396314
telemt_user_connections_current{user="hello"} 888
telemt_user_octets_from_client{user="hello"} 24630889201 (22.94 GB)
telemt_user_octets_to_client{user="hello"} 311677444734 (290.27 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 295
telemt_user_unique_ips_recent_window{user="hello"} 115
```