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

# Server Metrics 2026-03-18 05:16:11 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 124253.6 (34h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1445974
telemt_connections_bad_total 10574
telemt_handshake_timeouts_total 35052
telemt_upstream_connect_attempt_total 27123
telemt_upstream_connect_success_total 26609
telemt_upstream_connect_fail_total 514
telemt_upstream_connect_attempts_per_request{bucket="1"} 27123
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13636
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12765
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 514
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 266
telemt_me_reconnect_attempts_total 35290
telemt_me_reconnect_success_total 18142
telemt_me_reader_eof_total 19676
telemt_me_idle_close_by_peer_total 19675
telemt_me_route_drop_no_conn_total 605961
telemt_me_route_drop_channel_closed_total 167
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1312126
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8095
telemt_desync_full_logged_total 2428
telemt_desync_suppressed_total 5667
telemt_desync_frames_bucket_total{bucket="1_2"} 2133
telemt_desync_frames_bucket_total{bucket="3_10"} 3101
telemt_desync_frames_bucket_total{bucket="gt_10"} 2861
telemt_pool_swap_total 106
telemt_me_writer_removed_unexpected_total 18948
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 18120
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 806
telemt_user_connections_total{user="hello"} 1306358
telemt_user_connections_current{user="hello"} 901
telemt_user_octets_from_client{user="hello"} 30582814319 (28.48 GB)
telemt_user_octets_to_client{user="hello"} 463275756967 (431.46 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 350
telemt_user_unique_ips_recent_window{user="hello"} 143
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 124506.0 (34h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1559074
telemt_connections_bad_total 74317
telemt_handshake_timeouts_total 51574
telemt_upstream_connect_attempt_total 470603
telemt_upstream_connect_success_total 468977
telemt_upstream_connect_fail_total 1626
telemt_upstream_connect_attempts_per_request{bucket="1"} 470603
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 390985
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34625
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43365
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1626
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 343
telemt_me_reconnect_attempts_total 126580
telemt_me_reconnect_success_total 19852
telemt_me_reader_eof_total 22137
telemt_me_idle_close_by_peer_total 22124
telemt_me_route_drop_no_conn_total 408029
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 915837
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4080
telemt_desync_full_logged_total 1423
telemt_desync_suppressed_total 2657
telemt_desync_frames_bucket_total{bucket="1_2"} 801
telemt_desync_frames_bucket_total{bucket="3_10"} 1670
telemt_desync_frames_bucket_total{bucket="gt_10"} 1609
telemt_pool_swap_total 72
telemt_me_writer_removed_unexpected_total 21477
telemt_me_refill_failed_total 3329
telemt_me_writer_restored_same_endpoint_total 19834
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 6668
telemt_me_writer_removed_unexpected_minus_restored_total 1625
telemt_user_connections_total{user="hello"} 1358165
telemt_user_connections_current{user="hello"} 1533
telemt_user_octets_from_client{user="hello"} 18542609573 (17.27 GB)
telemt_user_octets_to_client{user="hello"} 512946819074 (477.72 GB)
telemt_user_msgs_from_client{user="hello"} 7472583
telemt_user_msgs_to_client{user="hello"} 31958899
telemt_user_unique_ips_current{user="hello"} 527
telemt_user_unique_ips_recent_window{user="hello"} 204
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 124281.9 (34h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1008890
telemt_connections_bad_total 70366
telemt_handshake_timeouts_total 28142
telemt_upstream_connect_attempt_total 28517
telemt_upstream_connect_success_total 28356
telemt_upstream_connect_fail_total 161
telemt_upstream_connect_attempts_per_request{bucket="1"} 28517
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13006
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15248
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 97
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 161
telemt_me_keepalive_timeout_total 124
telemt_me_reconnect_attempts_total 42821
telemt_me_reconnect_success_total 22119
telemt_me_reader_eof_total 24038
telemt_me_idle_close_by_peer_total 24031
telemt_me_route_drop_no_conn_total 370063
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 816412
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2717
telemt_desync_full_logged_total 887
telemt_desync_suppressed_total 1830
telemt_desync_frames_bucket_total{bucket="1_2"} 746
telemt_desync_frames_bucket_total{bucket="3_10"} 1052
telemt_desync_frames_bucket_total{bucket="gt_10"} 919
telemt_pool_swap_total 103
telemt_me_writer_removed_unexpected_total 23061
telemt_me_refill_failed_total 642
telemt_me_writer_restored_same_endpoint_total 22107
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 942
telemt_user_connections_total{user="hello"} 814520
telemt_user_connections_current{user="hello"} 1113
telemt_user_octets_from_client{user="hello"} 45654556344 (42.52 GB)
telemt_user_octets_to_client{user="hello"} 386097291944 (359.58 GB)
telemt_user_unique_ips_current{user="hello"} 357
telemt_user_unique_ips_recent_window{user="hello"} 125
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 124341.5 (34h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1451236
telemt_connections_bad_total 71576
telemt_handshake_timeouts_total 24642
telemt_upstream_connect_attempt_total 91534
telemt_upstream_connect_success_total 89091
telemt_upstream_connect_fail_total 2443
telemt_upstream_connect_attempts_per_request{bucket="1"} 91534
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 73751
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14928
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 379
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2443
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 320
telemt_me_reconnect_attempts_total 38536
telemt_me_reconnect_success_total 18120
telemt_me_reader_eof_total 19887
telemt_me_idle_close_by_peer_total 19884
telemt_me_route_drop_no_conn_total 585846
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1182961
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4519
telemt_desync_full_logged_total 1479
telemt_desync_suppressed_total 3040
telemt_desync_frames_bucket_total{bucket="1_2"} 1085
telemt_desync_frames_bucket_total{bucket="3_10"} 1885
telemt_desync_frames_bucket_total{bucket="gt_10"} 1549
telemt_pool_swap_total 99
telemt_me_writer_removed_unexpected_total 19094
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 18100
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 974
telemt_user_connections_total{user="hello"} 1246255
telemt_user_connections_current{user="hello"} 1530
telemt_user_octets_from_client{user="hello"} 19598964242 (18.25 GB)
telemt_user_octets_to_client{user="hello"} 609032910298 (567.21 GB)
telemt_user_msgs_from_client{user="hello"} 744103
telemt_user_msgs_to_client{user="hello"} 5214294
telemt_user_unique_ips_current{user="hello"} 461
telemt_user_unique_ips_recent_window{user="hello"} 183
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 124313.2 (34h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1013272
telemt_connections_bad_total 103731
telemt_handshake_timeouts_total 9765
telemt_upstream_connect_attempt_total 48518
telemt_upstream_connect_success_total 47848
telemt_upstream_connect_fail_total 670
telemt_upstream_connect_attempts_per_request{bucket="1"} 48518
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29557
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17868
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 423
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 670
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 60132
telemt_me_reconnect_success_total 25166
telemt_me_reader_eof_total 27221
telemt_me_idle_close_by_peer_total 27218
telemt_me_route_drop_no_conn_total 325019
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 828283
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3692
telemt_desync_full_logged_total 1128
telemt_desync_suppressed_total 2564
telemt_desync_frames_bucket_total{bucket="1_2"} 1080
telemt_desync_frames_bucket_total{bucket="3_10"} 1435
telemt_desync_frames_bucket_total{bucket="gt_10"} 1177
telemt_pool_swap_total 66
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 26645
telemt_me_refill_failed_total 1087
telemt_me_writer_restored_same_endpoint_total 25158
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1479
telemt_user_connections_total{user="hello"} 844762
telemt_user_connections_current{user="hello"} 1316
telemt_user_octets_from_client{user="hello"} 16003956520 (14.90 GB)
telemt_user_octets_to_client{user="hello"} 428557511416 (399.13 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 442
telemt_user_unique_ips_recent_window{user="hello"} 178
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 124474.2 (34h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1195859
telemt_connections_bad_total 127330
telemt_handshake_timeouts_total 10445
telemt_upstream_connect_attempt_total 24788
telemt_upstream_connect_success_total 24643
telemt_upstream_connect_fail_total 145
telemt_upstream_connect_attempts_per_request{bucket="1"} 24788
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11833
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12691
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 145
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 29743
telemt_me_reconnect_success_total 18449
telemt_me_reader_eof_total 19995
telemt_me_idle_close_by_peer_total 19993
telemt_me_route_drop_no_conn_total 820798
telemt_me_route_drop_channel_closed_total 90
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1175768
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2242
telemt_desync_full_logged_total 781
telemt_desync_suppressed_total 1461
telemt_desync_frames_bucket_total{bucket="1_2"} 498
telemt_desync_frames_bucket_total{bucket="3_10"} 854
telemt_desync_frames_bucket_total{bucket="gt_10"} 890
telemt_pool_swap_total 113
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 19086
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 18435
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 298
telemt_me_writer_removed_unexpected_minus_restored_total 637
telemt_user_connections_total{user="hello"} 984449
telemt_user_connections_current{user="hello"} 771
telemt_user_octets_from_client{user="hello"} 15621941772 (14.55 GB)
telemt_user_octets_to_client{user="hello"} 438927964560 (408.78 GB)
telemt_user_unique_ips_current{user="hello"} 244
telemt_user_unique_ips_recent_window{user="hello"} 98
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 72241.5 (20h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 543938
telemt_connections_bad_total 54082
telemt_handshake_timeouts_total 13292
telemt_upstream_connect_attempt_total 25401
telemt_upstream_connect_success_total 25140
telemt_upstream_connect_fail_total 261
telemt_upstream_connect_attempts_per_request{bucket="1"} 25401
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13442
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11602
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 261
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 32998
telemt_me_reconnect_success_total 21385
telemt_me_reader_eof_total 22600
telemt_me_idle_close_by_peer_total 22600
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 132994
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 392616
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 37
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1701
telemt_desync_full_logged_total 561
telemt_desync_suppressed_total 1140
telemt_desync_frames_bucket_total{bucket="1_2"} 279
telemt_desync_frames_bucket_total{bucket="3_10"} 761
telemt_desync_frames_bucket_total{bucket="gt_10"} 661
telemt_pool_swap_total 50
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 21973
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 21342
telemt_me_writer_restored_fallback_total 43
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 588
telemt_user_connections_total{user="hello"} 392372
telemt_user_connections_current{user="hello"} 873
telemt_user_octets_from_client{user="hello"} 24468157945 (22.79 GB)
telemt_user_octets_to_client{user="hello"} 310258812626 (288.95 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 291
telemt_user_unique_ips_recent_window{user="hello"} 99
```