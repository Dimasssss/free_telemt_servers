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

# Server Metrics 2026-03-18 10:31:59 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.20

telemt_uptime_seconds 6658.7 (1h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 246107
telemt_connections_bad_total 1740
telemt_handshake_timeouts_total 5453
telemt_upstream_connect_attempt_total 64276
telemt_upstream_connect_success_total 63348
telemt_upstream_connect_fail_total 928
telemt_upstream_connect_attempts_per_request{bucket="1"} 64276
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 59608
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3157
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 583
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 928
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 507664
telemt_me_reconnect_success_total 1023
telemt_me_reader_eof_total 981
telemt_me_idle_close_by_peer_total 979
telemt_me_route_drop_no_conn_total 114107
telemt_me_route_drop_channel_closed_total 48
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 156375
telemt_me_writer_pick_total{mode="p2c",result="full"} 21
telemt_me_writer_pick_total{mode="p2c",result="closed"} 54
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 717
telemt_desync_full_logged_total 230
telemt_desync_suppressed_total 487
telemt_desync_frames_bucket_total{bucket="1_2"} 211
telemt_desync_frames_bucket_total{bucket="3_10"} 268
telemt_desync_frames_bucket_total{bucket="gt_10"} 238
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 1013
telemt_me_refill_failed_total 16516
telemt_me_writer_restored_same_endpoint_total 918
telemt_me_writer_restored_fallback_total 105
telemt_me_async_recovery_trigger_total 11769
telemt_user_connections_total{user="hello"} 214864
telemt_user_connections_current{user="hello"} 1454
telemt_user_octets_from_client{user="hello"} 2600627128 (2.42 GB)
telemt_user_octets_to_client{user="hello"} 56417004361 (52.54 GB)
telemt_user_msgs_from_client{user="hello"} 846607
telemt_user_msgs_to_client{user="hello"} 1165163
telemt_user_unique_ips_current{user="hello"} 502
telemt_user_unique_ips_recent_window{user="hello"} 224
```

## psb.hosting

```
telemt 3.3.20

telemt_uptime_seconds 6689.3 (1h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 594359
telemt_connections_bad_total 69218
telemt_handshake_timeouts_total 13928
telemt_upstream_connect_attempt_total 1137
telemt_upstream_connect_success_total 1127
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 1137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 644
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 472
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_failed_total 1
telemt_me_reconnect_attempts_total 759
telemt_me_reconnect_success_total 734
telemt_me_reader_eof_total 711
telemt_me_idle_close_by_peer_total 711
telemt_me_route_drop_no_conn_total 256464
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 479124
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2270
telemt_desync_full_logged_total 637
telemt_desync_suppressed_total 1633
telemt_desync_frames_bucket_total{bucket="1_2"} 430
telemt_desync_frames_bucket_total{bucket="3_10"} 895
telemt_desync_frames_bucket_total{bucket="gt_10"} 945
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 721
telemt_me_writer_restored_same_endpoint_total 733
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 1068
telemt_user_connections_total{user="hello"} 478286
telemt_user_connections_current{user="hello"} 4047
telemt_user_octets_from_client{user="hello"} 10045510540 (9.36 GB)
telemt_user_octets_to_client{user="hello"} 177233521684 (165.06 GB)
telemt_user_unique_ips_current{user="hello"} 1266
telemt_user_unique_ips_recent_window{user="hello"} 737
```

## koara.io

```
telemt 3.3.20

telemt_uptime_seconds 6604.4 (1h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 453790
telemt_connections_bad_total 29116
telemt_handshake_timeouts_total 11609
telemt_upstream_connect_attempt_total 9569
telemt_upstream_connect_success_total 9569
telemt_upstream_connect_attempts_per_request{bucket="1"} 9569
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7685
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1876
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 40
telemt_me_reconnect_attempts_total 606655
telemt_me_reconnect_success_total 982
telemt_me_reader_eof_total 968
telemt_me_idle_close_by_peer_total 967
telemt_me_route_drop_no_conn_total 211485
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 337742
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 787
telemt_desync_full_logged_total 277
telemt_desync_suppressed_total 510
telemt_desync_frames_bucket_total{bucket="1_2"} 183
telemt_desync_frames_bucket_total{bucket="3_10"} 324
telemt_desync_frames_bucket_total{bucket="gt_10"} 280
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 978
telemt_me_refill_failed_total 19672
telemt_me_writer_restored_same_endpoint_total 947
telemt_me_writer_restored_fallback_total 35
telemt_me_async_recovery_trigger_total 14895
telemt_user_connections_total{user="hello"} 345638
telemt_user_connections_current{user="hello"} 2621
telemt_user_octets_from_client{user="hello"} 3643184827 (3.39 GB)
telemt_user_octets_to_client{user="hello"} 127840273180 (119.06 GB)
telemt_user_msgs_from_client{user="hello"} 68547
telemt_user_msgs_to_client{user="hello"} 285346
telemt_user_unique_ips_current{user="hello"} 760
telemt_user_unique_ips_recent_window{user="hello"} 357
```

## landvps.ru

```
telemt 3.3.20

telemt_uptime_seconds 6634.8 (1h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 831861
telemt_connections_bad_total 9448
telemt_handshake_timeouts_total 100919
telemt_upstream_connect_attempt_total 11804
telemt_upstream_connect_success_total 11683
telemt_upstream_connect_fail_total 121
telemt_upstream_connect_attempts_per_request{bucket="1"} 11804
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10523
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1124
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 121
telemt_me_keepalive_timeout_total 699
telemt_me_reconnect_attempts_total 2817446
telemt_me_reconnect_success_total 1022
telemt_me_reader_eof_total 1190
telemt_me_idle_close_by_peer_total 1190
telemt_me_route_drop_no_conn_total 1418218
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 639227
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
telemt_desync_total 1040
telemt_desync_full_logged_total 311
telemt_desync_suppressed_total 729
telemt_desync_frames_bucket_total{bucket="1_2"} 262
telemt_desync_frames_bucket_total{bucket="3_10"} 419
telemt_desync_frames_bucket_total{bucket="gt_10"} 359
telemt_me_writer_removed_unexpected_total 1223
telemt_me_refill_failed_total 99751
telemt_me_writer_restored_same_endpoint_total 927
telemt_me_writer_restored_fallback_total 95
telemt_me_async_recovery_trigger_total 365465
telemt_me_writer_removed_unexpected_minus_restored_total 201
telemt_user_connections_total{user="hello"} 658150
telemt_user_connections_current{user="hello"} 2639
telemt_user_octets_from_client{user="hello"} 4792496910 (4.46 GB)
telemt_user_octets_to_client{user="hello"} 91800676601 (85.50 GB)
telemt_user_msgs_from_client{user="hello"} 80007
telemt_user_msgs_to_client{user="hello"} 158054
telemt_user_unique_ips_current{user="hello"} 817
telemt_user_unique_ips_recent_window{user="hello"} 432
```

## rdp-onedash.ru

```
telemt 3.3.20

telemt_uptime_seconds 6529.4 (1h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 449683
telemt_connections_bad_total 12192
telemt_handshake_timeouts_total 6725
telemt_upstream_connect_attempt_total 10795
telemt_upstream_connect_success_total 10794
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 10795
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9637
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 940
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 217
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 61
telemt_me_reconnect_attempts_total 2982862
telemt_me_reconnect_success_total 911
telemt_me_reader_eof_total 870
telemt_me_idle_close_by_peer_total 870
telemt_me_route_drop_no_conn_total 189452
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 375070
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1389
telemt_desync_full_logged_total 470
telemt_desync_suppressed_total 919
telemt_desync_frames_bucket_total{bucket="1_2"} 224
telemt_desync_frames_bucket_total{bucket="3_10"} 529
telemt_desync_frames_bucket_total{bucket="gt_10"} 636
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 865
telemt_me_refill_failed_total 107153
telemt_me_writer_restored_same_endpoint_total 796
telemt_me_writer_restored_fallback_total 115
telemt_me_async_recovery_trigger_total 267383
telemt_user_connections_total{user="hello"} 383439
telemt_user_connections_current{user="hello"} 3180
telemt_user_octets_from_client{user="hello"} 6156244593 (5.73 GB)
telemt_user_octets_to_client{user="hello"} 153560170005 (143.01 GB)
telemt_user_msgs_from_client{user="hello"} 86293
telemt_user_msgs_to_client{user="hello"} 266108
telemt_user_unique_ips_current{user="hello"} 980
telemt_user_unique_ips_recent_window{user="hello"} 458
```

## hostvds.com

```
telemt 3.3.20

telemt_uptime_seconds 6414.4 (1h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 135010
telemt_connections_bad_total 16518
telemt_handshake_timeouts_total 884
telemt_upstream_connect_attempt_total 1186
telemt_upstream_connect_success_total 1186
telemt_upstream_connect_attempts_per_request{bucket="1"} 1186
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 632
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 554
telemt_me_reconnect_attempts_total 801
telemt_me_reconnect_success_total 793
telemt_me_reader_eof_total 795
telemt_me_idle_close_by_peer_total 795
telemt_me_route_drop_no_conn_total 58931
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 109374
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 262
telemt_desync_full_logged_total 97
telemt_desync_suppressed_total 165
telemt_desync_frames_bucket_total{bucket="1_2"} 48
telemt_desync_frames_bucket_total{bucket="3_10"} 100
telemt_desync_frames_bucket_total{bucket="gt_10"} 114
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 791
telemt_me_writer_restored_same_endpoint_total 785
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 130
telemt_user_connections_total{user="hello"} 106521
telemt_user_connections_current{user="hello"} 857
telemt_user_octets_from_client{user="hello"} 1646784592 (1.53 GB)
telemt_user_octets_to_client{user="hello"} 24525547812 (22.84 GB)
telemt_user_unique_ips_current{user="hello"} 313
telemt_user_unique_ips_recent_window{user="hello"} 146
```

## 4vps.su

```
telemt 3.3.20

telemt_uptime_seconds 6485.5 (1h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 327961
telemt_connections_bad_total 20174
telemt_handshake_timeouts_total 6453
telemt_upstream_connect_attempt_total 1231
telemt_upstream_connect_success_total 1212
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 1231
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 687
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_reconnect_attempts_total 831
telemt_me_reconnect_success_total 818
telemt_me_reader_eof_total 814
telemt_me_idle_close_by_peer_total 814
telemt_me_route_drop_no_conn_total 178903
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 280147
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 989
telemt_desync_full_logged_total 348
telemt_desync_suppressed_total 641
telemt_desync_frames_bucket_total{bucket="1_2"} 198
telemt_desync_frames_bucket_total{bucket="3_10"} 372
telemt_desync_frames_bucket_total{bucket="gt_10"} 419
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 812
telemt_me_writer_restored_same_endpoint_total 808
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 2494
telemt_user_connections_total{user="hello"} 279950
telemt_user_connections_current{user="hello"} 2355
telemt_user_octets_from_client{user="hello"} 4672391248 (4.35 GB)
telemt_user_octets_to_client{user="hello"} 137944890784 (128.47 GB)
telemt_user_unique_ips_current{user="hello"} 733
telemt_user_unique_ips_recent_window{user="hello"} 382
```