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

# Server Metrics 2026-03-18 11:12:43 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.20

telemt_uptime_seconds 9102.3 (2h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 328405
telemt_connections_bad_total 2893
telemt_handshake_timeouts_total 7789
telemt_upstream_connect_attempt_total 64826
telemt_upstream_connect_success_total 63897
telemt_upstream_connect_fail_total 929
telemt_upstream_connect_attempts_per_request{bucket="1"} 64826
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 59894
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3420
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 583
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 929
telemt_me_keepalive_timeout_total 6
telemt_me_reconnect_attempts_total 509226
telemt_me_reconnect_success_total 1429
telemt_me_reader_eof_total 1428
telemt_me_idle_close_by_peer_total 1426
telemt_me_route_drop_no_conn_total 187667
telemt_me_route_drop_channel_closed_total 60
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 230471
telemt_me_writer_pick_total{mode="p2c",result="full"} 21
telemt_me_writer_pick_total{mode="p2c",result="closed"} 54
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 995
telemt_desync_full_logged_total 317
telemt_desync_suppressed_total 678
telemt_desync_frames_bucket_total{bucket="1_2"} 284
telemt_desync_frames_bucket_total{bucket="3_10"} 366
telemt_desync_frames_bucket_total{bucket="gt_10"} 345
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 1461
telemt_me_refill_failed_total 16552
telemt_me_writer_restored_same_endpoint_total 1324
telemt_me_writer_restored_fallback_total 105
telemt_me_async_recovery_trigger_total 11769
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 288930
telemt_user_connections_current{user="hello"} 1575
telemt_user_octets_from_client{user="hello"} 3704306088 (3.45 GB)
telemt_user_octets_to_client{user="hello"} 74472992581 (69.36 GB)
telemt_user_msgs_from_client{user="hello"} 846607
telemt_user_msgs_to_client{user="hello"} 1165163
telemt_user_unique_ips_current{user="hello"} 503
telemt_user_unique_ips_recent_window{user="hello"} 230
```

## psb.hosting

```
telemt 3.3.20

telemt_uptime_seconds 9133.6 (2h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 999567
telemt_connections_bad_total 82044
telemt_handshake_timeouts_total 21813
telemt_upstream_connect_attempt_total 1680
telemt_upstream_connect_success_total 1668
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 1680
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 918
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 736
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_failed_total 1
telemt_me_reconnect_attempts_total 1163
telemt_me_reconnect_success_total 1120
telemt_me_reader_eof_total 1110
telemt_me_idle_close_by_peer_total 1109
telemt_me_route_drop_no_conn_total 1039243
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 851411
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2762
telemt_desync_full_logged_total 783
telemt_desync_suppressed_total 1979
telemt_desync_frames_bucket_total{bucket="1_2"} 568
telemt_desync_frames_bucket_total{bucket="3_10"} 1098
telemt_desync_frames_bucket_total{bucket="gt_10"} 1096
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 1117
telemt_me_writer_restored_same_endpoint_total 1119
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 1068
telemt_user_connections_total{user="hello"} 850691
telemt_user_connections_current{user="hello"} 3784
telemt_user_octets_from_client{user="hello"} 17022378356 (15.85 GB)
telemt_user_octets_to_client{user="hello"} 223928130004 (208.55 GB)
telemt_user_unique_ips_current{user="hello"} 1129
telemt_user_unique_ips_recent_window{user="hello"} 544
```

## koara.io

```
telemt 3.3.20

telemt_uptime_seconds 9048.3 (2h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 635453
telemt_connections_bad_total 43368
telemt_handshake_timeouts_total 15459
telemt_upstream_connect_attempt_total 10111
telemt_upstream_connect_success_total 10111
telemt_upstream_connect_attempts_per_request{bucket="1"} 10111
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7967
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2133
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 40
telemt_me_reconnect_attempts_total 607085
telemt_me_reconnect_success_total 1397
telemt_me_reader_eof_total 1379
telemt_me_idle_close_by_peer_total 1378
telemt_me_route_drop_no_conn_total 315043
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 479075
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1186
telemt_desync_full_logged_total 403
telemt_desync_suppressed_total 783
telemt_desync_frames_bucket_total{bucket="1_2"} 287
telemt_desync_frames_bucket_total{bucket="3_10"} 455
telemt_desync_frames_bucket_total{bucket="gt_10"} 444
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 1397
telemt_me_refill_failed_total 19672
telemt_me_writer_restored_same_endpoint_total 1362
telemt_me_writer_restored_fallback_total 35
telemt_me_async_recovery_trigger_total 14895
telemt_user_connections_total{user="hello"} 486853
telemt_user_connections_current{user="hello"} 3112
telemt_user_octets_from_client{user="hello"} 5399907739 (5.03 GB)
telemt_user_octets_to_client{user="hello"} 188024794864 (175.11 GB)
telemt_user_msgs_from_client{user="hello"} 68547
telemt_user_msgs_to_client{user="hello"} 285346
telemt_user_unique_ips_current{user="hello"} 937
telemt_user_unique_ips_recent_window{user="hello"} 428
```

## landvps.ru

```
telemt 3.3.20

telemt_uptime_seconds 9078.4 (2h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1130714
telemt_connections_bad_total 13785
telemt_handshake_timeouts_total 133309
telemt_upstream_connect_attempt_total 12028
telemt_upstream_connect_success_total 11888
telemt_upstream_connect_fail_total 140
telemt_upstream_connect_attempts_per_request{bucket="1"} 12028
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10677
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1173
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 140
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 699
telemt_me_reconnect_attempts_total 2820259
telemt_me_reconnect_success_total 1105
telemt_me_reader_eof_total 1351
telemt_me_idle_close_by_peer_total 1351
telemt_me_route_drop_no_conn_total 1857327
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 885756
telemt_me_writer_pick_total{mode="p2c",result="success_fallback"} 8840
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_writer_pick_blocking_fallback_total 8840
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1589
telemt_desync_full_logged_total 502
telemt_desync_suppressed_total 1087
telemt_desync_frames_bucket_total{bucket="1_2"} 395
telemt_desync_frames_bucket_total{bucket="3_10"} 649
telemt_desync_frames_bucket_total{bucket="gt_10"} 545
telemt_me_writer_removed_unexpected_total 1394
telemt_me_refill_failed_total 99836
telemt_me_writer_restored_same_endpoint_total 1010
telemt_me_writer_restored_fallback_total 95
telemt_me_async_recovery_trigger_total 365465
telemt_me_writer_removed_unexpected_minus_restored_total 289
telemt_user_connections_total{user="hello"} 904617
telemt_user_connections_current{user="hello"} 3223
telemt_user_octets_from_client{user="hello"} 6177631326 (5.75 GB)
telemt_user_octets_to_client{user="hello"} 129819439181 (120.90 GB)
telemt_user_msgs_from_client{user="hello"} 80007
telemt_user_msgs_to_client{user="hello"} 158054
telemt_user_unique_ips_current{user="hello"} 917
telemt_user_unique_ips_recent_window{user="hello"} 440
```

## rdp-onedash.ru

```
telemt 3.3.20

telemt_uptime_seconds 8973.4 (2h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 662149
telemt_connections_bad_total 19935
telemt_handshake_timeouts_total 9588
telemt_upstream_connect_attempt_total 11134
telemt_upstream_connect_success_total 11133
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 11134
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9820
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1093
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 220
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 61
telemt_me_reconnect_attempts_total 2983114
telemt_me_reconnect_success_total 1156
telemt_me_reader_eof_total 1125
telemt_me_idle_close_by_peer_total 1125
telemt_me_route_drop_no_conn_total 431238
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 562476
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1957
telemt_desync_full_logged_total 642
telemt_desync_suppressed_total 1315
telemt_desync_frames_bucket_total{bucket="1_2"} 313
telemt_desync_frames_bucket_total{bucket="3_10"} 756
telemt_desync_frames_bucket_total{bucket="gt_10"} 888
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1119
telemt_me_refill_failed_total 107153
telemt_me_writer_restored_same_endpoint_total 1041
telemt_me_writer_restored_fallback_total 115
telemt_me_async_recovery_trigger_total 267383
telemt_user_connections_total{user="hello"} 570341
telemt_user_connections_current{user="hello"} 3500
telemt_user_octets_from_client{user="hello"} 8268111125 (7.70 GB)
telemt_user_octets_to_client{user="hello"} 216714503445 (201.83 GB)
telemt_user_msgs_from_client{user="hello"} 86293
telemt_user_msgs_to_client{user="hello"} 266108
telemt_user_unique_ips_current{user="hello"} 1051
telemt_user_unique_ips_recent_window{user="hello"} 529
```

## hostvds.com

```
telemt 3.3.20

telemt_uptime_seconds 8858.9 (2h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 194006
telemt_connections_bad_total 22182
telemt_handshake_timeouts_total 1335
telemt_upstream_connect_attempt_total 1678
telemt_upstream_connect_success_total 1678
telemt_upstream_connect_attempts_per_request{bucket="1"} 1678
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 890
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 788
telemt_me_reconnect_attempts_total 1197
telemt_me_reconnect_success_total 1183
telemt_me_reader_eof_total 1197
telemt_me_idle_close_by_peer_total 1196
telemt_me_route_drop_no_conn_total 100130
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 164887
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 423
telemt_desync_full_logged_total 143
telemt_desync_suppressed_total 280
telemt_desync_frames_bucket_total{bucket="1_2"} 81
telemt_desync_frames_bucket_total{bucket="3_10"} 150
telemt_desync_frames_bucket_total{bucket="gt_10"} 192
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 1188
telemt_me_writer_restored_same_endpoint_total 1175
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 130
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 155217
telemt_user_connections_current{user="hello"} 917
telemt_user_octets_from_client{user="hello"} 2220515080 (2.07 GB)
telemt_user_octets_to_client{user="hello"} 37760118964 (35.17 GB)
telemt_user_unique_ips_current{user="hello"} 329
telemt_user_unique_ips_recent_window{user="hello"} 152
```

## 4vps.su

```
telemt 3.3.20

telemt_uptime_seconds 8929.2 (2h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 467356
telemt_connections_bad_total 24150
telemt_handshake_timeouts_total 10966
telemt_upstream_connect_attempt_total 1598
telemt_upstream_connect_success_total 1579
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 1598
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 876
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 695
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_reconnect_attempts_total 1106
telemt_me_reconnect_success_total 1086
telemt_me_reader_eof_total 1089
telemt_me_idle_close_by_peer_total 1089
telemt_me_route_drop_no_conn_total 226718
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 398110
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1505
telemt_desync_full_logged_total 517
telemt_desync_suppressed_total 988
telemt_desync_frames_bucket_total{bucket="1_2"} 274
telemt_desync_frames_bucket_total{bucket="3_10"} 533
telemt_desync_frames_bucket_total{bucket="gt_10"} 698
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 1085
telemt_me_writer_restored_same_endpoint_total 1076
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 2494
telemt_user_connections_total{user="hello"} 397828
telemt_user_connections_current{user="hello"} 3013
telemt_user_octets_from_client{user="hello"} 6649245300 (6.19 GB)
telemt_user_octets_to_client{user="hello"} 203862606296 (189.86 GB)
telemt_user_unique_ips_current{user="hello"} 856
telemt_user_unique_ips_recent_window{user="hello"} 388
```