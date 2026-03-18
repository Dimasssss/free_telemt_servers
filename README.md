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

# Server Metrics 2026-03-18 11:07:37 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.20

telemt_uptime_seconds 8796.7 (2h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 318349
telemt_connections_bad_total 2451
telemt_handshake_timeouts_total 7479
telemt_upstream_connect_attempt_total 64741
telemt_upstream_connect_success_total 63813
telemt_upstream_connect_fail_total 928
telemt_upstream_connect_attempts_per_request{bucket="1"} 64741
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 59849
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3381
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 583
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 928
telemt_me_keepalive_timeout_total 6
telemt_me_reconnect_attempts_total 509185
telemt_me_reconnect_success_total 1388
telemt_me_reader_eof_total 1385
telemt_me_idle_close_by_peer_total 1383
telemt_me_route_drop_no_conn_total 185111
telemt_me_route_drop_channel_closed_total 60
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 221659
telemt_me_writer_pick_total{mode="p2c",result="full"} 21
telemt_me_writer_pick_total{mode="p2c",result="closed"} 54
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 956
telemt_desync_full_logged_total 304
telemt_desync_suppressed_total 652
telemt_desync_frames_bucket_total{bucket="1_2"} 276
telemt_desync_frames_bucket_total{bucket="3_10"} 356
telemt_desync_frames_bucket_total{bucket="gt_10"} 324
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 1419
telemt_me_refill_failed_total 16552
telemt_me_writer_restored_same_endpoint_total 1283
telemt_me_writer_restored_fallback_total 105
telemt_me_async_recovery_trigger_total 11769
telemt_me_writer_removed_unexpected_minus_restored_total 31
telemt_user_connections_total{user="hello"} 280124
telemt_user_connections_current{user="hello"} 1598
telemt_user_octets_from_client{user="hello"} 3590866124 (3.34 GB)
telemt_user_octets_to_client{user="hello"} 72358991981 (67.39 GB)
telemt_user_msgs_from_client{user="hello"} 846607
telemt_user_msgs_to_client{user="hello"} 1165163
telemt_user_unique_ips_current{user="hello"} 528
telemt_user_unique_ips_recent_window{user="hello"} 237
```

## psb.hosting

```
telemt 3.3.20

telemt_uptime_seconds 8827.9 (2h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 970826
telemt_connections_bad_total 79886
telemt_handshake_timeouts_total 21020
telemt_upstream_connect_attempt_total 1586
telemt_upstream_connect_success_total 1574
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 1586
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 876
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 684
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_failed_total 1
telemt_me_reconnect_attempts_total 1112
telemt_me_reconnect_success_total 1070
telemt_me_reader_eof_total 1054
telemt_me_idle_close_by_peer_total 1053
telemt_me_route_drop_no_conn_total 1025680
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 826566
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2713
telemt_desync_full_logged_total 768
telemt_desync_suppressed_total 1945
telemt_desync_frames_bucket_total{bucket="1_2"} 556
telemt_desync_frames_bucket_total{bucket="3_10"} 1077
telemt_desync_frames_bucket_total{bucket="gt_10"} 1080
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1066
telemt_me_writer_restored_same_endpoint_total 1069
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 1068
telemt_user_connections_total{user="hello"} 825841
telemt_user_connections_current{user="hello"} 4002
telemt_user_octets_from_client{user="hello"} 13819931748 (12.87 GB)
telemt_user_octets_to_client{user="hello"} 216637519864 (201.76 GB)
telemt_user_unique_ips_current{user="hello"} 1162
telemt_user_unique_ips_recent_window{user="hello"} 525
```

## koara.io

```
telemt 3.3.20

telemt_uptime_seconds 8742.8 (2h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 609214
telemt_connections_bad_total 42504
telemt_handshake_timeouts_total 14915
telemt_upstream_connect_attempt_total 10039
telemt_upstream_connect_success_total 10039
telemt_upstream_connect_attempts_per_request{bucket="1"} 10039
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7931
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2097
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 40
telemt_me_reconnect_attempts_total 607031
telemt_me_reconnect_success_total 1343
telemt_me_reader_eof_total 1324
telemt_me_idle_close_by_peer_total 1323
telemt_me_route_drop_no_conn_total 309842
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 462113
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1131
telemt_desync_full_logged_total 383
telemt_desync_suppressed_total 748
telemt_desync_frames_bucket_total{bucket="1_2"} 279
telemt_desync_frames_bucket_total{bucket="3_10"} 436
telemt_desync_frames_bucket_total{bucket="gt_10"} 416
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 1342
telemt_me_refill_failed_total 19672
telemt_me_writer_restored_same_endpoint_total 1308
telemt_me_writer_restored_fallback_total 35
telemt_me_async_recovery_trigger_total 14895
telemt_user_connections_total{user="hello"} 469904
telemt_user_connections_current{user="hello"} 3120
telemt_user_octets_from_client{user="hello"} 5159720851 (4.81 GB)
telemt_user_octets_to_client{user="hello"} 177862765500 (165.65 GB)
telemt_user_msgs_from_client{user="hello"} 68547
telemt_user_msgs_to_client{user="hello"} 285346
telemt_user_unique_ips_current{user="hello"} 944
telemt_user_unique_ips_recent_window{user="hello"} 458
```

## landvps.ru

```
telemt 3.3.20

telemt_uptime_seconds 8773.3 (2h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1105559
telemt_connections_bad_total 13299
telemt_handshake_timeouts_total 129649
telemt_upstream_connect_attempt_total 11998
telemt_upstream_connect_success_total 11858
telemt_upstream_connect_fail_total 140
telemt_upstream_connect_attempts_per_request{bucket="1"} 11998
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10657
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1165
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 140
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 699
telemt_me_reconnect_attempts_total 2820252
telemt_me_reconnect_success_total 1098
telemt_me_reader_eof_total 1344
telemt_me_idle_close_by_peer_total 1344
telemt_me_route_drop_no_conn_total 1847122
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 865931
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
telemt_desync_total 1525
telemt_desync_full_logged_total 474
telemt_desync_suppressed_total 1051
telemt_desync_frames_bucket_total{bucket="1_2"} 384
telemt_desync_frames_bucket_total{bucket="3_10"} 618
telemt_desync_frames_bucket_total{bucket="gt_10"} 523
telemt_me_writer_removed_unexpected_total 1387
telemt_me_refill_failed_total 99836
telemt_me_writer_restored_same_endpoint_total 1003
telemt_me_writer_restored_fallback_total 95
telemt_me_async_recovery_trigger_total 365465
telemt_me_writer_removed_unexpected_minus_restored_total 289
telemt_user_connections_total{user="hello"} 884799
telemt_user_connections_current{user="hello"} 3362
telemt_user_octets_from_client{user="hello"} 6003907750 (5.59 GB)
telemt_user_octets_to_client{user="hello"} 124235668441 (115.70 GB)
telemt_user_msgs_from_client{user="hello"} 80007
telemt_user_msgs_to_client{user="hello"} 158054
telemt_user_unique_ips_current{user="hello"} 934
telemt_user_unique_ips_recent_window{user="hello"} 431
```

## rdp-onedash.ru

```
telemt 3.3.20

telemt_uptime_seconds 8667.9 (2h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 637133
telemt_connections_bad_total 19406
telemt_handshake_timeouts_total 9472
telemt_upstream_connect_attempt_total 11103
telemt_upstream_connect_success_total 11102
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 11103
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9804
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1078
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 220
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 61
telemt_me_reconnect_attempts_total 2983083
telemt_me_reconnect_success_total 1125
telemt_me_reader_eof_total 1092
telemt_me_idle_close_by_peer_total 1092
telemt_me_route_drop_no_conn_total 408854
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 539788
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1889
telemt_desync_full_logged_total 624
telemt_desync_suppressed_total 1265
telemt_desync_frames_bucket_total{bucket="1_2"} 303
telemt_desync_frames_bucket_total{bucket="3_10"} 726
telemt_desync_frames_bucket_total{bucket="gt_10"} 860
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1086
telemt_me_refill_failed_total 107153
telemt_me_writer_restored_same_endpoint_total 1010
telemt_me_writer_restored_fallback_total 115
telemt_me_async_recovery_trigger_total 267383
telemt_user_connections_total{user="hello"} 548111
telemt_user_connections_current{user="hello"} 3876
telemt_user_octets_from_client{user="hello"} 8021070001 (7.47 GB)
telemt_user_octets_to_client{user="hello"} 208401839749 (194.09 GB)
telemt_user_msgs_from_client{user="hello"} 86293
telemt_user_msgs_to_client{user="hello"} 266108
telemt_user_unique_ips_current{user="hello"} 1075
telemt_user_unique_ips_recent_window{user="hello"} 567
```

## hostvds.com

```
telemt 3.3.20

telemt_uptime_seconds 8553.0 (2h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 187846
telemt_connections_bad_total 21553
telemt_handshake_timeouts_total 1291
telemt_upstream_connect_attempt_total 1623
telemt_upstream_connect_success_total 1623
telemt_upstream_connect_attempts_per_request{bucket="1"} 1623
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 868
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 755
telemt_me_reconnect_attempts_total 1142
telemt_me_reconnect_success_total 1128
telemt_me_reader_eof_total 1142
telemt_me_idle_close_by_peer_total 1141
telemt_me_route_drop_no_conn_total 98190
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 159931
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 406
telemt_desync_full_logged_total 139
telemt_desync_suppressed_total 267
telemt_desync_frames_bucket_total{bucket="1_2"} 81
telemt_desync_frames_bucket_total{bucket="3_10"} 145
telemt_desync_frames_bucket_total{bucket="gt_10"} 180
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 1133
telemt_me_writer_restored_same_endpoint_total 1120
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 130
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 150267
telemt_user_connections_current{user="hello"} 862
telemt_user_octets_from_client{user="hello"} 2177733556 (2.03 GB)
telemt_user_octets_to_client{user="hello"} 37023867668 (34.48 GB)
telemt_user_unique_ips_current{user="hello"} 325
telemt_user_unique_ips_recent_window{user="hello"} 141
```

## 4vps.su

```
telemt 3.3.20

telemt_uptime_seconds 8623.8 (2h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 446175
telemt_connections_bad_total 23027
telemt_handshake_timeouts_total 10457
telemt_upstream_connect_attempt_total 1567
telemt_upstream_connect_success_total 1548
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 1567
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 863
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 677
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_reconnect_attempts_total 1075
telemt_me_reconnect_success_total 1055
telemt_me_reader_eof_total 1058
telemt_me_idle_close_by_peer_total 1058
telemt_me_route_drop_no_conn_total 221158
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 382254
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1419
telemt_desync_full_logged_total 496
telemt_desync_suppressed_total 923
telemt_desync_frames_bucket_total{bucket="1_2"} 268
telemt_desync_frames_bucket_total{bucket="3_10"} 510
telemt_desync_frames_bucket_total{bucket="gt_10"} 641
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 1054
telemt_me_writer_restored_same_endpoint_total 1045
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 2494
telemt_user_connections_total{user="hello"} 382025
telemt_user_connections_current{user="hello"} 3222
telemt_user_octets_from_client{user="hello"} 6363586264 (5.93 GB)
telemt_user_octets_to_client{user="hello"} 194172540684 (180.84 GB)
telemt_user_unique_ips_current{user="hello"} 882
telemt_user_unique_ips_recent_window{user="hello"} 457
```