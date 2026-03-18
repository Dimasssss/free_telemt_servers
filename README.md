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

# Server Metrics 2026-03-18 11:27:59 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.20

telemt_uptime_seconds 10018.6 (2h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 357504
telemt_connections_bad_total 4309
telemt_handshake_timeouts_total 8684
telemt_upstream_connect_attempt_total 64960
telemt_upstream_connect_success_total 64025
telemt_upstream_connect_fail_total 935
telemt_upstream_connect_attempts_per_request{bucket="1"} 64960
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 59962
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3480
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 583
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 935
telemt_me_keepalive_timeout_total 6
telemt_me_reconnect_attempts_total 509311
telemt_me_reconnect_success_total 1513
telemt_me_reader_eof_total 1526
telemt_me_idle_close_by_peer_total 1524
telemt_me_route_drop_no_conn_total 195583
telemt_me_route_drop_channel_closed_total 65
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 255827
telemt_me_writer_pick_total{mode="p2c",result="full"} 21
telemt_me_writer_pick_total{mode="p2c",result="closed"} 54
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1076
telemt_desync_full_logged_total 345
telemt_desync_suppressed_total 731
telemt_desync_frames_bucket_total{bucket="1_2"} 308
telemt_desync_frames_bucket_total{bucket="3_10"} 387
telemt_desync_frames_bucket_total{bucket="gt_10"} 381
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 1547
telemt_me_refill_failed_total 16552
telemt_me_writer_restored_same_endpoint_total 1408
telemt_me_writer_restored_fallback_total 105
telemt_me_async_recovery_trigger_total 11769
telemt_me_writer_removed_unexpected_minus_restored_total 34
telemt_user_connections_total{user="hello"} 314236
telemt_user_connections_current{user="hello"} 1731
telemt_user_octets_from_client{user="hello"} 4056771984 (3.78 GB)
telemt_user_octets_to_client{user="hello"} 83029202841 (77.33 GB)
telemt_user_msgs_from_client{user="hello"} 846607
telemt_user_msgs_to_client{user="hello"} 1165163
telemt_user_unique_ips_current{user="hello"} 541
telemt_user_unique_ips_recent_window{user="hello"} 229
```

## psb.hosting

```
telemt 3.3.20

telemt_uptime_seconds 10050.2 (2h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1072324
telemt_connections_bad_total 85547
telemt_handshake_timeouts_total 23907
telemt_upstream_connect_attempt_total 1810
telemt_upstream_connect_success_total 1798
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 1810
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 984
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 799
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_failed_total 1
telemt_me_reconnect_attempts_total 1249
telemt_me_reconnect_success_total 1206
telemt_me_reader_eof_total 1207
telemt_me_idle_close_by_peer_total 1206
telemt_me_route_drop_no_conn_total 1065966
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 916057
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2955
telemt_desync_full_logged_total 842
telemt_desync_suppressed_total 2113
telemt_desync_frames_bucket_total{bucket="1_2"} 606
telemt_desync_frames_bucket_total{bucket="3_10"} 1177
telemt_desync_frames_bucket_total{bucket="gt_10"} 1172
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 1202
telemt_me_writer_restored_same_endpoint_total 1205
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 1068
telemt_user_connections_total{user="hello"} 915370
telemt_user_connections_current{user="hello"} 3803
telemt_user_octets_from_client{user="hello"} 23640925208 (22.02 GB)
telemt_user_octets_to_client{user="hello"} 242740481288 (226.07 GB)
telemt_user_unique_ips_current{user="hello"} 1167
telemt_user_unique_ips_recent_window{user="hello"} 533
```

## koara.io

```
telemt 3.3.20

telemt_uptime_seconds 9964.9 (2h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 701137
telemt_connections_bad_total 47743
telemt_handshake_timeouts_total 17656
telemt_upstream_connect_attempt_total 10255
telemt_upstream_connect_success_total 10255
telemt_upstream_connect_attempts_per_request{bucket="1"} 10255
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8047
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2197
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 40
telemt_me_reconnect_attempts_total 607183
telemt_me_reconnect_success_total 1494
telemt_me_reader_eof_total 1491
telemt_me_idle_close_by_peer_total 1490
telemt_me_route_drop_no_conn_total 334266
telemt_me_route_drop_channel_closed_total 15
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 526679
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1306
telemt_desync_full_logged_total 452
telemt_desync_suppressed_total 854
telemt_desync_frames_bucket_total{bucket="1_2"} 312
telemt_desync_frames_bucket_total{bucket="3_10"} 507
telemt_desync_frames_bucket_total{bucket="gt_10"} 487
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 1494
telemt_me_refill_failed_total 19672
telemt_me_writer_restored_same_endpoint_total 1459
telemt_me_writer_restored_fallback_total 35
telemt_me_async_recovery_trigger_total 14895
telemt_user_connections_total{user="hello"} 534426
telemt_user_connections_current{user="hello"} 2958
telemt_user_octets_from_client{user="hello"} 6367450575 (5.93 GB)
telemt_user_octets_to_client{user="hello"} 212629089608 (198.03 GB)
telemt_user_msgs_from_client{user="hello"} 68547
telemt_user_msgs_to_client{user="hello"} 285346
telemt_user_unique_ips_current{user="hello"} 916
telemt_user_unique_ips_recent_window{user="hello"} 419
```

## landvps.ru

```
telemt 3.3.20

telemt_uptime_seconds 9994.7 (2h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1205119
telemt_connections_bad_total 15029
telemt_handshake_timeouts_total 146837
telemt_upstream_connect_attempt_total 12111
telemt_upstream_connect_success_total 11963
telemt_upstream_connect_fail_total 147
telemt_upstream_connect_attempts_per_request{bucket="1"} 12110
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10731
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1194
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 147
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 699
telemt_me_reconnect_attempts_total 2821597
telemt_me_reconnect_success_total 1131
telemt_me_reader_eof_total 1419
telemt_me_idle_close_by_peer_total 1419
telemt_me_route_drop_no_conn_total 1885867
telemt_me_route_drop_channel_closed_total 17
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 937803
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
telemt_desync_total 1763
telemt_desync_full_logged_total 555
telemt_desync_suppressed_total 1208
telemt_desync_frames_bucket_total{bucket="1_2"} 436
telemt_desync_frames_bucket_total{bucket="3_10"} 711
telemt_desync_frames_bucket_total{bucket="gt_10"} 616
telemt_me_writer_removed_unexpected_total 1463
telemt_me_refill_failed_total 99877
telemt_me_writer_restored_same_endpoint_total 1036
telemt_me_writer_restored_fallback_total 95
telemt_me_async_recovery_trigger_total 365465
telemt_me_writer_removed_unexpected_minus_restored_total 332
telemt_user_connections_total{user="hello"} 956627
telemt_user_connections_current{user="hello"} 2993
telemt_user_octets_from_client{user="hello"} 6727076726 (6.27 GB)
telemt_user_octets_to_client{user="hello"} 146881510705 (136.79 GB)
telemt_user_msgs_from_client{user="hello"} 80007
telemt_user_msgs_to_client{user="hello"} 158054
telemt_user_unique_ips_current{user="hello"} 914
telemt_user_unique_ips_recent_window{user="hello"} 425
```

## rdp-onedash.ru

```
telemt 3.3.20

telemt_uptime_seconds 9889.8 (2h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 726736
telemt_connections_bad_total 23540
telemt_handshake_timeouts_total 10604
telemt_upstream_connect_attempt_total 11255
telemt_upstream_connect_success_total 11254
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 11255
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9888
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1146
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 220
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 61
telemt_me_reconnect_attempts_total 2983192
telemt_me_reconnect_success_total 1233
telemt_me_reader_eof_total 1212
telemt_me_idle_close_by_peer_total 1212
telemt_me_route_drop_no_conn_total 485609
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 623991
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2137
telemt_desync_full_logged_total 705
telemt_desync_suppressed_total 1432
telemt_desync_frames_bucket_total{bucket="1_2"} 326
telemt_desync_frames_bucket_total{bucket="3_10"} 837
telemt_desync_frames_bucket_total{bucket="gt_10"} 974
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 1198
telemt_me_refill_failed_total 107153
telemt_me_writer_restored_same_endpoint_total 1118
telemt_me_writer_restored_fallback_total 115
telemt_me_async_recovery_trigger_total 267383
telemt_user_connections_total{user="hello"} 626080
telemt_user_connections_current{user="hello"} 3160
telemt_user_octets_from_client{user="hello"} 9039826369 (8.42 GB)
telemt_user_octets_to_client{user="hello"} 240022860977 (223.54 GB)
telemt_user_msgs_from_client{user="hello"} 86293
telemt_user_msgs_to_client{user="hello"} 266108
telemt_user_unique_ips_current{user="hello"} 1005
telemt_user_unique_ips_recent_window{user="hello"} 456
```

## hostvds.com

```
telemt 3.3.20

telemt_uptime_seconds 9775.0 (2h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 210596
telemt_connections_bad_total 22196
telemt_handshake_timeouts_total 1568
telemt_upstream_connect_attempt_total 1826
telemt_upstream_connect_success_total 1826
telemt_upstream_connect_attempts_per_request{bucket="1"} 1826
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 957
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 869
telemt_me_reconnect_attempts_total 1301
telemt_me_reconnect_success_total 1287
telemt_me_reader_eof_total 1318
telemt_me_idle_close_by_peer_total 1317
telemt_me_route_drop_no_conn_total 105066
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 179468
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 433
telemt_desync_full_logged_total 149
telemt_desync_suppressed_total 284
telemt_desync_frames_bucket_total{bucket="1_2"} 82
telemt_desync_frames_bucket_total{bucket="3_10"} 154
telemt_desync_frames_bucket_total{bucket="gt_10"} 197
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1294
telemt_me_writer_restored_same_endpoint_total 1279
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 130
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 169794
telemt_user_connections_current{user="hello"} 938
telemt_user_octets_from_client{user="hello"} 2334998944 (2.17 GB)
telemt_user_octets_to_client{user="hello"} 40324088688 (37.55 GB)
telemt_user_unique_ips_current{user="hello"} 339
telemt_user_unique_ips_recent_window{user="hello"} 125
```

## 4vps.su

```
telemt 3.3.20

telemt_uptime_seconds 9845.7 (2h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 523296
telemt_connections_bad_total 26286
telemt_handshake_timeouts_total 12405
telemt_upstream_connect_attempt_total 1754
telemt_upstream_connect_success_total 1734
telemt_upstream_connect_fail_total 20
telemt_upstream_connect_attempts_per_request{bucket="1"} 1754
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 957
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 769
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 20
telemt_me_reconnect_attempts_total 1218
telemt_me_reconnect_success_total 1198
telemt_me_reader_eof_total 1213
telemt_me_idle_close_by_peer_total 1213
telemt_me_route_drop_no_conn_total 243081
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 441415
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1647
telemt_desync_full_logged_total 571
telemt_desync_suppressed_total 1076
telemt_desync_frames_bucket_total{bucket="1_2"} 294
telemt_desync_frames_bucket_total{bucket="3_10"} 589
telemt_desync_frames_bucket_total{bucket="gt_10"} 764
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1199
telemt_me_writer_restored_same_endpoint_total 1188
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 441053
telemt_user_connections_current{user="hello"} 2957
telemt_user_octets_from_client{user="hello"} 7532202316 (7.01 GB)
telemt_user_octets_to_client{user="hello"} 225838033860 (210.33 GB)
telemt_user_unique_ips_current{user="hello"} 858
telemt_user_unique_ips_recent_window{user="hello"} 353
```