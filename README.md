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

# Server Metrics 2026-03-18 10:47:16 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.20

telemt_uptime_seconds 7575.8 (2h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 279427
telemt_connections_bad_total 1788
telemt_handshake_timeouts_total 6378
telemt_upstream_connect_attempt_total 64476
telemt_upstream_connect_success_total 63548
telemt_upstream_connect_fail_total 928
telemt_upstream_connect_attempts_per_request{bucket="1"} 64476
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 59713
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3252
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 583
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 928
telemt_me_keepalive_timeout_total 6
telemt_me_reconnect_attempts_total 507818
telemt_me_reconnect_success_total 1176
telemt_me_reader_eof_total 1139
telemt_me_idle_close_by_peer_total 1137
telemt_me_route_drop_no_conn_total 160714
telemt_me_route_drop_channel_closed_total 53
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 186562
telemt_me_writer_pick_total{mode="p2c",result="full"} 21
telemt_me_writer_pick_total{mode="p2c",result="closed"} 54
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 831
telemt_desync_full_logged_total 266
telemt_desync_suppressed_total 565
telemt_desync_frames_bucket_total{bucket="1_2"} 243
telemt_desync_frames_bucket_total{bucket="3_10"} 309
telemt_desync_frames_bucket_total{bucket="gt_10"} 279
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 1171
telemt_me_refill_failed_total 16516
telemt_me_writer_restored_same_endpoint_total 1071
telemt_me_writer_restored_fallback_total 105
telemt_me_async_recovery_trigger_total 11769
telemt_user_connections_total{user="hello"} 245048
telemt_user_connections_current{user="hello"} 1596
telemt_user_octets_from_client{user="hello"} 3181331456 (2.96 GB)
telemt_user_octets_to_client{user="hello"} 62481169485 (58.19 GB)
telemt_user_msgs_from_client{user="hello"} 846607
telemt_user_msgs_to_client{user="hello"} 1165163
telemt_user_unique_ips_current{user="hello"} 531
telemt_user_unique_ips_recent_window{user="hello"} 251
```

## psb.hosting

```
telemt 3.3.20

telemt_uptime_seconds 7606.6 (2h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 830723
telemt_connections_bad_total 75102
telemt_handshake_timeouts_total 18613
telemt_upstream_connect_attempt_total 1307
telemt_upstream_connect_success_total 1295
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 1307
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 739
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 544
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_failed_total 1
telemt_me_reconnect_attempts_total 878
telemt_me_reconnect_success_total 849
telemt_me_reader_eof_total 828
telemt_me_idle_close_by_peer_total 828
telemt_me_route_drop_no_conn_total 851652
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 699478
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2525
telemt_desync_full_logged_total 702
telemt_desync_suppressed_total 1823
telemt_desync_frames_bucket_total{bucket="1_2"} 504
telemt_desync_frames_bucket_total{bucket="3_10"} 1008
telemt_desync_frames_bucket_total{bucket="gt_10"} 1013
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 839
telemt_me_writer_restored_same_endpoint_total 848
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 1068
telemt_user_connections_total{user="hello"} 698700
telemt_user_connections_current{user="hello"} 4129
telemt_user_octets_from_client{user="hello"} 10854077652 (10.11 GB)
telemt_user_octets_to_client{user="hello"} 190638979036 (177.55 GB)
telemt_user_unique_ips_current{user="hello"} 1166
telemt_user_unique_ips_recent_window{user="hello"} 560
```

## koara.io

```
telemt 3.3.20

telemt_uptime_seconds 7521.9 (2h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 521636
telemt_connections_bad_total 36668
telemt_handshake_timeouts_total 13068
telemt_upstream_connect_attempt_total 9742
telemt_upstream_connect_success_total 9742
telemt_upstream_connect_attempts_per_request{bucket="1"} 9742
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7772
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1962
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 40
telemt_me_reconnect_attempts_total 606783
telemt_me_reconnect_success_total 1107
telemt_me_reader_eof_total 1088
telemt_me_idle_close_by_peer_total 1087
telemt_me_route_drop_no_conn_total 266141
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 392738
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 950
telemt_desync_full_logged_total 323
telemt_desync_suppressed_total 627
telemt_desync_frames_bucket_total{bucket="1_2"} 237
telemt_desync_frames_bucket_total{bucket="3_10"} 371
telemt_desync_frames_bucket_total{bucket="gt_10"} 342
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 1105
telemt_me_refill_failed_total 19672
telemt_me_writer_restored_same_endpoint_total 1072
telemt_me_writer_restored_fallback_total 35
telemt_me_async_recovery_trigger_total 14895
telemt_user_connections_total{user="hello"} 400608
telemt_user_connections_current{user="hello"} 2973
telemt_user_octets_from_client{user="hello"} 4152158683 (3.87 GB)
telemt_user_octets_to_client{user="hello"} 145049901176 (135.09 GB)
telemt_user_msgs_from_client{user="hello"} 68547
telemt_user_msgs_to_client{user="hello"} 285346
telemt_user_unique_ips_current{user="hello"} 863
telemt_user_unique_ips_recent_window{user="hello"} 417
```

## landvps.ru

```
telemt 3.3.20

telemt_uptime_seconds 7551.7 (2h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 959158
telemt_connections_bad_total 11308
telemt_handshake_timeouts_total 110914
telemt_upstream_connect_attempt_total 11903
telemt_upstream_connect_success_total 11771
telemt_upstream_connect_fail_total 132
telemt_upstream_connect_attempts_per_request{bucket="1"} 11903
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10592
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1143
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 132
telemt_me_keepalive_timeout_total 699
telemt_me_reconnect_attempts_total 2818864
telemt_me_reconnect_success_total 1063
telemt_me_reader_eof_total 1270
telemt_me_idle_close_by_peer_total 1270
telemt_me_route_drop_no_conn_total 1716504
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 748630
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
telemt_desync_total 1213
telemt_desync_full_logged_total 357
telemt_desync_suppressed_total 856
telemt_desync_frames_bucket_total{bucket="1_2"} 303
telemt_desync_frames_bucket_total{bucket="3_10"} 484
telemt_desync_frames_bucket_total{bucket="gt_10"} 426
telemt_me_writer_removed_unexpected_total 1307
telemt_me_refill_failed_total 99794
telemt_me_writer_restored_same_endpoint_total 968
telemt_me_writer_restored_fallback_total 95
telemt_me_async_recovery_trigger_total 365465
telemt_me_writer_removed_unexpected_minus_restored_total 244
telemt_user_connections_total{user="hello"} 767536
telemt_user_connections_current{user="hello"} 2986
telemt_user_octets_from_client{user="hello"} 5280934754 (4.92 GB)
telemt_user_octets_to_client{user="hello"} 105389656981 (98.15 GB)
telemt_user_msgs_from_client{user="hello"} 80007
telemt_user_msgs_to_client{user="hello"} 158054
telemt_user_unique_ips_current{user="hello"} 846
telemt_user_unique_ips_recent_window{user="hello"} 472
```

## rdp-onedash.ru

```
telemt 3.3.20

telemt_uptime_seconds 7446.8 (2h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 513126
telemt_connections_bad_total 13370
telemt_handshake_timeouts_total 7458
telemt_upstream_connect_attempt_total 10912
telemt_upstream_connect_success_total 10911
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 10912
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9694
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 998
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 219
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 61
telemt_me_reconnect_attempts_total 2982936
telemt_me_reconnect_success_total 985
telemt_me_reader_eof_total 950
telemt_me_idle_close_by_peer_total 950
telemt_me_route_drop_no_conn_total 216149
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 432164
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1596
telemt_desync_full_logged_total 541
telemt_desync_suppressed_total 1055
telemt_desync_frames_bucket_total{bucket="1_2"} 251
telemt_desync_frames_bucket_total{bucket="3_10"} 620
telemt_desync_frames_bucket_total{bucket="gt_10"} 725
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 942
telemt_me_refill_failed_total 107153
telemt_me_writer_restored_same_endpoint_total 870
telemt_me_writer_restored_fallback_total 115
telemt_me_async_recovery_trigger_total 267383
telemt_user_connections_total{user="hello"} 440508
telemt_user_connections_current{user="hello"} 3717
telemt_user_octets_from_client{user="hello"} 6942889629 (6.47 GB)
telemt_user_octets_to_client{user="hello"} 176871947649 (164.72 GB)
telemt_user_msgs_from_client{user="hello"} 86293
telemt_user_msgs_to_client{user="hello"} 266108
telemt_user_unique_ips_current{user="hello"} 1080
telemt_user_unique_ips_recent_window{user="hello"} 518
```

## hostvds.com

```
telemt 3.3.20

telemt_uptime_seconds 7331.8 (2h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 158705
telemt_connections_bad_total 18018
telemt_handshake_timeouts_total 1005
telemt_upstream_connect_attempt_total 1322
telemt_upstream_connect_success_total 1322
telemt_upstream_connect_attempts_per_request{bucket="1"} 1322
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 710
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 612
telemt_me_reconnect_attempts_total 893
telemt_me_reconnect_success_total 884
telemt_me_reader_eof_total 894
telemt_me_idle_close_by_peer_total 893
telemt_me_route_drop_no_conn_total 72344
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 131142
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 326
telemt_desync_full_logged_total 119
telemt_desync_suppressed_total 207
telemt_desync_frames_bucket_total{bucket="1_2"} 65
telemt_desync_frames_bucket_total{bucket="3_10"} 118
telemt_desync_frames_bucket_total{bucket="gt_10"} 143
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 885
telemt_me_writer_restored_same_endpoint_total 876
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 130
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 127323
telemt_user_connections_current{user="hello"} 917
telemt_user_octets_from_client{user="hello"} 1914460136 (1.78 GB)
telemt_user_octets_to_client{user="hello"} 29489936196 (27.46 GB)
telemt_user_unique_ips_current{user="hello"} 339
telemt_user_unique_ips_recent_window{user="hello"} 148
```

## 4vps.su

```
telemt 3.3.20

telemt_uptime_seconds 7402.7 (2h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 373745
telemt_connections_bad_total 21105
telemt_handshake_timeouts_total 8376
telemt_upstream_connect_attempt_total 1374
telemt_upstream_connect_success_total 1355
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 1374
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 769
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 578
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_reconnect_attempts_total 931
telemt_me_reconnect_success_total 912
telemt_me_reader_eof_total 912
telemt_me_idle_close_by_peer_total 912
telemt_me_route_drop_no_conn_total 197753
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 321629
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1108
telemt_desync_full_logged_total 394
telemt_desync_suppressed_total 714
telemt_desync_frames_bucket_total{bucket="1_2"} 221
telemt_desync_frames_bucket_total{bucket="3_10"} 402
telemt_desync_frames_bucket_total{bucket="gt_10"} 485
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 908
telemt_me_writer_restored_same_endpoint_total 902
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 2494
telemt_user_connections_total{user="hello"} 321437
telemt_user_connections_current{user="hello"} 2724
telemt_user_octets_from_client{user="hello"} 5583416084 (5.20 GB)
telemt_user_octets_to_client{user="hello"} 160046050556 (149.05 GB)
telemt_user_unique_ips_current{user="hello"} 785
telemt_user_unique_ips_recent_window{user="hello"} 376
```