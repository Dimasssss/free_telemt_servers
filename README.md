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

# Server Metrics 2026-03-18 06:17:15 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 127918.3 (35h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1563681
telemt_connections_bad_total 10693
telemt_handshake_timeouts_total 36217
telemt_upstream_connect_attempt_total 27789
telemt_upstream_connect_success_total 27270
telemt_upstream_connect_fail_total 519
telemt_upstream_connect_attempts_per_request{bucket="1"} 27789
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13948
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13114
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 519
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 279
telemt_me_reconnect_attempts_total 35751
telemt_me_reconnect_success_total 18599
telemt_me_reader_eof_total 20160
telemt_me_idle_close_by_peer_total 20159
telemt_me_route_drop_no_conn_total 625909
telemt_me_route_drop_channel_closed_total 171
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1363929
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8314
telemt_desync_full_logged_total 2506
telemt_desync_suppressed_total 5808
telemt_desync_frames_bucket_total{bucket="1_2"} 2176
telemt_desync_frames_bucket_total{bucket="3_10"} 3194
telemt_desync_frames_bucket_total{bucket="gt_10"} 2944
telemt_pool_swap_total 110
telemt_me_writer_removed_unexpected_total 19414
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 18577
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 815
telemt_user_connections_total{user="hello"} 1358148
telemt_user_connections_current{user="hello"} 1011
telemt_user_octets_from_client{user="hello"} 32262189563 (30.05 GB)
telemt_user_octets_to_client{user="hello"} 487482192287 (454.00 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 387
telemt_user_unique_ips_recent_window{user="hello"} 157
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 128169.5 (35h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1678432
telemt_connections_bad_total 81179
telemt_handshake_timeouts_total 54125
telemt_upstream_connect_attempt_total 471247
telemt_upstream_connect_success_total 469610
telemt_upstream_connect_fail_total 1637
telemt_upstream_connect_attempts_per_request{bucket="1"} 471247
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 391305
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34937
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43366
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1637
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 343
telemt_me_reconnect_attempts_total 127040
telemt_me_reconnect_success_total 20307
telemt_me_reader_eof_total 22618
telemt_me_idle_close_by_peer_total 22605
telemt_me_route_drop_no_conn_total 445782
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1021038
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4696
telemt_desync_full_logged_total 1632
telemt_desync_suppressed_total 3064
telemt_desync_frames_bucket_total{bucket="1_2"} 918
telemt_desync_frames_bucket_total{bucket="3_10"} 1887
telemt_desync_frames_bucket_total{bucket="gt_10"} 1891
telemt_pool_swap_total 75
telemt_me_writer_removed_unexpected_total 21939
telemt_me_refill_failed_total 3329
telemt_me_writer_restored_same_endpoint_total 20289
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 6668
telemt_me_writer_removed_unexpected_minus_restored_total 1632
telemt_user_connections_total{user="hello"} 1463402
telemt_user_connections_current{user="hello"} 2097
telemt_user_octets_from_client{user="hello"} 20356424385 (18.96 GB)
telemt_user_octets_to_client{user="hello"} 567544607570 (528.57 GB)
telemt_user_msgs_from_client{user="hello"} 7472583
telemt_user_msgs_to_client{user="hello"} 31958899
telemt_user_unique_ips_current{user="hello"} 654
telemt_user_unique_ips_recent_window{user="hello"} 295
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 127945.7 (35h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1169533
telemt_connections_bad_total 77278
telemt_handshake_timeouts_total 30713
telemt_upstream_connect_attempt_total 29076
telemt_upstream_connect_success_total 28912
telemt_upstream_connect_fail_total 164
telemt_upstream_connect_attempts_per_request{bucket="1"} 29076
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13289
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15521
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 97
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 164
telemt_me_keepalive_timeout_total 135
telemt_me_reconnect_attempts_total 43191
telemt_me_reconnect_success_total 22484
telemt_me_reader_eof_total 24430
telemt_me_idle_close_by_peer_total 24423
telemt_me_route_drop_no_conn_total 399496
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 892901
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3081
telemt_desync_full_logged_total 1001
telemt_desync_suppressed_total 2080
telemt_desync_frames_bucket_total{bucket="1_2"} 816
telemt_desync_frames_bucket_total{bucket="3_10"} 1198
telemt_desync_frames_bucket_total{bucket="gt_10"} 1067
telemt_pool_swap_total 108
telemt_me_writer_removed_unexpected_total 23435
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 22472
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 951
telemt_user_connections_total{user="hello"} 890985
telemt_user_connections_current{user="hello"} 1420
telemt_user_octets_from_client{user="hello"} 46989023428 (43.76 GB)
telemt_user_octets_to_client{user="hello"} 434603344524 (404.76 GB)
telemt_user_unique_ips_current{user="hello"} 447
telemt_user_unique_ips_recent_window{user="hello"} 187
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 128004.9 (35h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1566624
telemt_connections_bad_total 77518
telemt_handshake_timeouts_total 27182
telemt_upstream_connect_attempt_total 92161
telemt_upstream_connect_success_total 89709
telemt_upstream_connect_fail_total 2452
telemt_upstream_connect_attempts_per_request{bucket="1"} 92161
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 74044
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15249
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 383
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2452
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 320
telemt_me_reconnect_attempts_total 38982
telemt_me_reconnect_success_total 18560
telemt_me_reader_eof_total 20352
telemt_me_idle_close_by_peer_total 20349
telemt_me_route_drop_no_conn_total 628194
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1283053
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4967
telemt_desync_full_logged_total 1610
telemt_desync_suppressed_total 3357
telemt_desync_frames_bucket_total{bucket="1_2"} 1182
telemt_desync_frames_bucket_total{bucket="3_10"} 2070
telemt_desync_frames_bucket_total{bucket="gt_10"} 1715
telemt_pool_swap_total 102
telemt_me_writer_removed_unexpected_total 19541
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 18540
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 981
telemt_user_connections_total{user="hello"} 1346315
telemt_user_connections_current{user="hello"} 2082
telemt_user_octets_from_client{user="hello"} 22675332918 (21.12 GB)
telemt_user_octets_to_client{user="hello"} 656088873634 (611.03 GB)
telemt_user_msgs_from_client{user="hello"} 744103
telemt_user_msgs_to_client{user="hello"} 5214294
telemt_user_unique_ips_current{user="hello"} 560
telemt_user_unique_ips_recent_window{user="hello"} 254
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 127976.8 (35h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1117407
telemt_connections_bad_total 106101
telemt_handshake_timeouts_total 11385
telemt_upstream_connect_attempt_total 49093
telemt_upstream_connect_success_total 48415
telemt_upstream_connect_fail_total 678
telemt_upstream_connect_attempts_per_request{bucket="1"} 49093
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29850
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18140
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 425
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 678
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 60525
telemt_me_reconnect_success_total 25555
telemt_me_reader_eof_total 27632
telemt_me_idle_close_by_peer_total 27629
telemt_me_route_drop_no_conn_total 359687
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 919352
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3990
telemt_desync_full_logged_total 1227
telemt_desync_suppressed_total 2763
telemt_desync_frames_bucket_total{bucket="1_2"} 1117
telemt_desync_frames_bucket_total{bucket="3_10"} 1543
telemt_desync_frames_bucket_total{bucket="gt_10"} 1330
telemt_pool_swap_total 69
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 27041
telemt_me_refill_failed_total 1087
telemt_me_writer_restored_same_endpoint_total 25547
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1486
telemt_user_connections_total{user="hello"} 935794
telemt_user_connections_current{user="hello"} 1733
telemt_user_octets_from_client{user="hello"} 17496277048 (16.29 GB)
telemt_user_octets_to_client{user="hello"} 470478502800 (438.17 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 589
telemt_user_unique_ips_recent_window{user="hello"} 256
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 128138.1 (35h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1235835
telemt_connections_bad_total 128310
telemt_handshake_timeouts_total 10691
telemt_upstream_connect_attempt_total 25431
telemt_upstream_connect_success_total 25280
telemt_upstream_connect_fail_total 151
telemt_upstream_connect_attempts_per_request{bucket="1"} 25431
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12163
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12998
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 151
telemt_me_keepalive_timeout_total 151
telemt_me_reconnect_attempts_total 30207
telemt_me_reconnect_success_total 18910
telemt_me_reader_eof_total 20486
telemt_me_idle_close_by_peer_total 20484
telemt_me_route_drop_no_conn_total 835440
telemt_me_route_drop_channel_closed_total 92
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1212566
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2331
telemt_desync_full_logged_total 819
telemt_desync_suppressed_total 1512
telemt_desync_frames_bucket_total{bucket="1_2"} 519
telemt_desync_frames_bucket_total{bucket="3_10"} 893
telemt_desync_frames_bucket_total{bucket="gt_10"} 919
telemt_pool_swap_total 117
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 19553
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 18896
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 298
telemt_me_writer_removed_unexpected_minus_restored_total 643
telemt_user_connections_total{user="hello"} 1021236
telemt_user_connections_current{user="hello"} 824
telemt_user_octets_from_client{user="hello"} 16200422988 (15.09 GB)
telemt_user_octets_to_client{user="hello"} 455722406288 (424.42 GB)
telemt_user_unique_ips_current{user="hello"} 277
telemt_user_unique_ips_recent_window{user="hello"} 112
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 75905.0 (21h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 613542
telemt_connections_bad_total 57502
telemt_handshake_timeouts_total 13866
telemt_upstream_connect_attempt_total 26022
telemt_upstream_connect_success_total 25750
telemt_upstream_connect_fail_total 272
telemt_upstream_connect_attempts_per_request{bucket="1"} 26022
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13761
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11893
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 272
telemt_me_keepalive_timeout_total 98
telemt_me_reconnect_attempts_total 33435
telemt_me_reconnect_success_total 21819
telemt_me_reader_eof_total 23060
telemt_me_idle_close_by_peer_total 23060
telemt_me_seq_mismatch_total 35
telemt_me_route_drop_no_conn_total 152707
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 452327
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 39
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2000
telemt_desync_full_logged_total 668
telemt_desync_suppressed_total 1332
telemt_desync_frames_bucket_total{bucket="1_2"} 332
telemt_desync_frames_bucket_total{bucket="3_10"} 892
telemt_desync_frames_bucket_total{bucket="gt_10"} 776
telemt_pool_swap_total 54
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 22416
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 21774
telemt_me_writer_restored_fallback_total 45
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 597
telemt_user_connections_total{user="hello"} 452086
telemt_user_connections_current{user="hello"} 1287
telemt_user_octets_from_client{user="hello"} 27139476573 (25.28 GB)
telemt_user_octets_to_client{user="hello"} 348499007190 (324.56 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 411
telemt_user_unique_ips_recent_window{user="hello"} 159
```