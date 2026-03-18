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

# Server Metrics 2026-03-18 06:47:49 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 129751.4 (36h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1658805
telemt_connections_bad_total 11545
telemt_handshake_timeouts_total 36800
telemt_upstream_connect_attempt_total 28153
telemt_upstream_connect_success_total 27630
telemt_upstream_connect_fail_total 523
telemt_upstream_connect_attempts_per_request{bucket="1"} 28153
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14128
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13294
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 523
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 285
telemt_me_reconnect_attempts_total 36024
telemt_me_reconnect_success_total 18868
telemt_me_reader_eof_total 20444
telemt_me_idle_close_by_peer_total 20443
telemt_me_route_drop_no_conn_total 637810
telemt_me_route_drop_channel_closed_total 181
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1396307
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8450
telemt_desync_full_logged_total 2550
telemt_desync_suppressed_total 5900
telemt_desync_frames_bucket_total{bucket="1_2"} 2197
telemt_desync_frames_bucket_total{bucket="3_10"} 3262
telemt_desync_frames_bucket_total{bucket="gt_10"} 2991
telemt_pool_swap_total 111
telemt_me_writer_removed_unexpected_total 19688
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 18846
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 820
telemt_user_connections_total{user="hello"} 1390549
telemt_user_connections_current{user="hello"} 1119
telemt_user_octets_from_client{user="hello"} 32696209423 (30.45 GB)
telemt_user_octets_to_client{user="hello"} 498517224667 (464.28 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 420
telemt_user_unique_ips_recent_window{user="hello"} 167
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 130002.8 (36h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1758458
telemt_connections_bad_total 87654
telemt_handshake_timeouts_total 56407
telemt_upstream_connect_attempt_total 471664
telemt_upstream_connect_success_total 470024
telemt_upstream_connect_fail_total 1640
telemt_upstream_connect_attempts_per_request{bucket="1"} 471664
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 391517
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35139
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43366
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1640
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 411
telemt_me_reconnect_attempts_total 127365
telemt_me_reconnect_success_total 20631
telemt_me_reader_eof_total 22945
telemt_me_idle_close_by_peer_total 22932
telemt_me_route_drop_no_conn_total 473719
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1089040
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5017
telemt_desync_full_logged_total 1745
telemt_desync_suppressed_total 3272
telemt_desync_frames_bucket_total{bucket="1_2"} 953
telemt_desync_frames_bucket_total{bucket="3_10"} 2033
telemt_desync_frames_bucket_total{bucket="gt_10"} 2031
telemt_pool_swap_total 75
telemt_me_writer_removed_unexpected_total 22266
telemt_me_refill_failed_total 3329
telemt_me_writer_restored_same_endpoint_total 20613
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 6668
telemt_me_writer_removed_unexpected_minus_restored_total 1635
telemt_user_connections_total{user="hello"} 1531355
telemt_user_connections_current{user="hello"} 2216
telemt_user_octets_from_client{user="hello"} 23548459793 (21.93 GB)
telemt_user_octets_to_client{user="hello"} 600012028322 (558.80 GB)
telemt_user_msgs_from_client{user="hello"} 7472583
telemt_user_msgs_to_client{user="hello"} 31958899
telemt_user_unique_ips_current{user="hello"} 710
telemt_user_unique_ips_recent_window{user="hello"} 314
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 129778.8 (36h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1253161
telemt_connections_bad_total 81413
telemt_handshake_timeouts_total 31692
telemt_upstream_connect_attempt_total 29349
telemt_upstream_connect_success_total 29184
telemt_upstream_connect_fail_total 165
telemt_upstream_connect_attempts_per_request{bucket="1"} 29349
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13423
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15659
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 97
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 165
telemt_me_keepalive_timeout_total 159
telemt_me_reconnect_attempts_total 43376
telemt_me_reconnect_success_total 22665
telemt_me_reader_eof_total 24630
telemt_me_idle_close_by_peer_total 24622
telemt_me_route_drop_no_conn_total 418879
telemt_me_route_drop_channel_closed_total 20
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 940069
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3236
telemt_desync_full_logged_total 1049
telemt_desync_suppressed_total 2187
telemt_desync_frames_bucket_total{bucket="1_2"} 852
telemt_desync_frames_bucket_total{bucket="3_10"} 1250
telemt_desync_frames_bucket_total{bucket="gt_10"} 1134
telemt_pool_swap_total 109
telemt_me_writer_removed_unexpected_total 23626
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 22653
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 961
telemt_user_connections_total{user="hello"} 938133
telemt_user_connections_current{user="hello"} 1604
telemt_user_octets_from_client{user="hello"} 47975990712 (44.68 GB)
telemt_user_octets_to_client{user="hello"} 460326384180 (428.71 GB)
telemt_user_unique_ips_current{user="hello"} 489
telemt_user_unique_ips_recent_window{user="hello"} 215
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 129837.9 (36h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1648219
telemt_connections_bad_total 83601
telemt_handshake_timeouts_total 29272
telemt_upstream_connect_attempt_total 92471
telemt_upstream_connect_success_total 90016
telemt_upstream_connect_fail_total 2455
telemt_upstream_connect_attempts_per_request{bucket="1"} 92471
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 74202
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15398
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 383
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2455
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 350
telemt_me_reconnect_attempts_total 39201
telemt_me_reconnect_success_total 18776
telemt_me_reader_eof_total 20576
telemt_me_idle_close_by_peer_total 20573
telemt_me_route_drop_no_conn_total 657540
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1352937
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5285
telemt_desync_full_logged_total 1691
telemt_desync_suppressed_total 3594
telemt_desync_frames_bucket_total{bucket="1_2"} 1246
telemt_desync_frames_bucket_total{bucket="3_10"} 2181
telemt_desync_frames_bucket_total{bucket="gt_10"} 1858
telemt_pool_swap_total 103
telemt_me_writer_removed_unexpected_total 19760
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 18756
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 984
telemt_user_connections_total{user="hello"} 1416183
telemt_user_connections_current{user="hello"} 2122
telemt_user_octets_from_client{user="hello"} 23692487654 (22.07 GB)
telemt_user_octets_to_client{user="hello"} 680253076318 (633.54 GB)
telemt_user_msgs_from_client{user="hello"} 744103
telemt_user_msgs_to_client{user="hello"} 5214294
telemt_user_unique_ips_current{user="hello"} 593
telemt_user_unique_ips_recent_window{user="hello"} 260
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 129810.0 (36h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1182081
telemt_connections_bad_total 107211
telemt_handshake_timeouts_total 12642
telemt_upstream_connect_attempt_total 49544
telemt_upstream_connect_success_total 48862
telemt_upstream_connect_fail_total 682
telemt_upstream_connect_attempts_per_request{bucket="1"} 49544
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30077
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18355
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 430
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 682
telemt_me_keepalive_timeout_total 31
telemt_me_reconnect_attempts_total 62068
telemt_me_reconnect_success_total 25910
telemt_me_reader_eof_total 28031
telemt_me_idle_close_by_peer_total 28028
telemt_me_route_drop_no_conn_total 382088
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 975052
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4182
telemt_desync_full_logged_total 1290
telemt_desync_suppressed_total 2892
telemt_desync_frames_bucket_total{bucket="1_2"} 1141
telemt_desync_frames_bucket_total{bucket="3_10"} 1611
telemt_desync_frames_bucket_total{bucket="gt_10"} 1430
telemt_pool_swap_total 69
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 27440
telemt_me_refill_failed_total 1124
telemt_me_writer_restored_same_endpoint_total 25902
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1530
telemt_user_connections_total{user="hello"} 991464
telemt_user_connections_current{user="hello"} 1682
telemt_user_octets_from_client{user="hello"} 18489419200 (17.22 GB)
telemt_user_octets_to_client{user="hello"} 501794131540 (467.33 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 581
telemt_user_unique_ips_recent_window{user="hello"} 239
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 129971.3 (36h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1262303
telemt_connections_bad_total 132501
telemt_handshake_timeouts_total 10817
telemt_upstream_connect_attempt_total 25782
telemt_upstream_connect_success_total 25629
telemt_upstream_connect_fail_total 153
telemt_upstream_connect_attempts_per_request{bucket="1"} 25782
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12339
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13171
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 153
telemt_me_keepalive_timeout_total 269
telemt_me_reconnect_attempts_total 30468
telemt_me_reconnect_success_total 19169
telemt_me_reader_eof_total 20757
telemt_me_idle_close_by_peer_total 20755
telemt_me_route_drop_no_conn_total 844295
telemt_me_route_drop_channel_closed_total 92
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1233469
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2388
telemt_desync_full_logged_total 842
telemt_desync_suppressed_total 1546
telemt_desync_frames_bucket_total{bucket="1_2"} 532
telemt_desync_frames_bucket_total{bucket="3_10"} 918
telemt_desync_frames_bucket_total{bucket="gt_10"} 938
telemt_pool_swap_total 118
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 19816
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 19155
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 298
telemt_me_writer_removed_unexpected_minus_restored_total 647
telemt_user_connections_total{user="hello"} 1042128
telemt_user_connections_current{user="hello"} 834
telemt_user_octets_from_client{user="hello"} 16390632752 (15.26 GB)
telemt_user_octets_to_client{user="hello"} 461808623036 (430.09 GB)
telemt_user_unique_ips_current{user="hello"} 276
telemt_user_unique_ips_recent_window{user="hello"} 99
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 77738.1 (21h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 659961
telemt_connections_bad_total 57854
telemt_handshake_timeouts_total 14657
telemt_upstream_connect_attempt_total 26381
telemt_upstream_connect_success_total 26102
telemt_upstream_connect_fail_total 279
telemt_upstream_connect_attempts_per_request{bucket="1"} 26381
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13939
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12062
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 101
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 279
telemt_me_keepalive_timeout_total 149
telemt_me_reconnect_attempts_total 33701
telemt_me_reconnect_success_total 22082
telemt_me_reader_eof_total 23332
telemt_me_idle_close_by_peer_total 23332
telemt_me_seq_mismatch_total 36
telemt_me_route_drop_no_conn_total 184505
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 493584
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 40
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2129
telemt_desync_full_logged_total 729
telemt_desync_suppressed_total 1400
telemt_desync_frames_bucket_total{bucket="1_2"} 347
telemt_desync_frames_bucket_total{bucket="3_10"} 931
telemt_desync_frames_bucket_total{bucket="gt_10"} 851
telemt_pool_swap_total 55
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 22682
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 22036
telemt_me_writer_restored_fallback_total 46
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 600
telemt_user_connections_total{user="hello"} 493316
telemt_user_connections_current{user="hello"} 1444
telemt_user_octets_from_client{user="hello"} 27626901001 (25.73 GB)
telemt_user_octets_to_client{user="hello"} 371342345222 (345.84 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 420
telemt_user_unique_ips_recent_window{user="hello"} 186
```