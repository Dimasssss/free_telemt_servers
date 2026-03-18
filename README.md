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

# Server Metrics 2026-03-18 11:17:48 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.20

telemt_uptime_seconds 9407.5 (2h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 337710
telemt_connections_bad_total 3151
telemt_handshake_timeouts_total 8076
telemt_upstream_connect_attempt_total 64880
telemt_upstream_connect_success_total 63951
telemt_upstream_connect_fail_total 929
telemt_upstream_connect_attempts_per_request{bucket="1"} 64880
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 59918
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3450
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 583
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 929
telemt_me_keepalive_timeout_total 6
telemt_me_reconnect_attempts_total 509280
telemt_me_reconnect_success_total 1483
telemt_me_reader_eof_total 1494
telemt_me_idle_close_by_peer_total 1492
telemt_me_route_drop_no_conn_total 190039
telemt_me_route_drop_channel_closed_total 60
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 238892
telemt_me_writer_pick_total{mode="p2c",result="full"} 21
telemt_me_writer_pick_total{mode="p2c",result="closed"} 54
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1041
telemt_desync_full_logged_total 331
telemt_desync_suppressed_total 710
telemt_desync_frames_bucket_total{bucket="1_2"} 299
telemt_desync_frames_bucket_total{bucket="3_10"} 377
telemt_desync_frames_bucket_total{bucket="gt_10"} 365
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 1515
telemt_me_refill_failed_total 16552
telemt_me_writer_restored_same_endpoint_total 1378
telemt_me_writer_restored_fallback_total 105
telemt_me_async_recovery_trigger_total 11769
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 297347
telemt_user_connections_current{user="hello"} 1554
telemt_user_octets_from_client{user="hello"} 3842599892 (3.58 GB)
telemt_user_octets_to_client{user="hello"} 76815950565 (71.54 GB)
telemt_user_msgs_from_client{user="hello"} 846607
telemt_user_msgs_to_client{user="hello"} 1165163
telemt_user_unique_ips_current{user="hello"} 534
telemt_user_unique_ips_recent_window{user="hello"} 228
```

## psb.hosting

```
telemt 3.3.20

telemt_uptime_seconds 9438.6 (2h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1025697
telemt_connections_bad_total 83649
telemt_handshake_timeouts_total 23097
telemt_upstream_connect_attempt_total 1718
telemt_upstream_connect_success_total 1706
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 1718
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 937
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 754
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_failed_total 1
telemt_me_reconnect_attempts_total 1201
telemt_me_reconnect_success_total 1158
telemt_me_reader_eof_total 1156
telemt_me_idle_close_by_peer_total 1155
telemt_me_route_drop_no_conn_total 1048348
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 873935
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2819
telemt_desync_full_logged_total 799
telemt_desync_suppressed_total 2020
telemt_desync_frames_bucket_total{bucket="1_2"} 578
telemt_desync_frames_bucket_total{bucket="3_10"} 1118
telemt_desync_frames_bucket_total{bucket="gt_10"} 1123
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 1154
telemt_me_writer_restored_same_endpoint_total 1157
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 1068
telemt_user_connections_total{user="hello"} 873246
telemt_user_connections_current{user="hello"} 3841
telemt_user_octets_from_client{user="hello"} 20338448504 (18.94 GB)
telemt_user_octets_to_client{user="hello"} 230735341120 (214.89 GB)
telemt_user_unique_ips_current{user="hello"} 1143
telemt_user_unique_ips_recent_window{user="hello"} 540
```

## koara.io

Не удалось получить метрики для этого сервера.

## landvps.ru

```
telemt 3.3.20

telemt_uptime_seconds 9384.0 (2h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1156325
telemt_connections_bad_total 14372
telemt_handshake_timeouts_total 136727
telemt_upstream_connect_attempt_total 12063
telemt_upstream_connect_success_total 11920
telemt_upstream_connect_fail_total 143
telemt_upstream_connect_attempts_per_request{bucket="1"} 12063
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10700
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1182
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 143
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 699
telemt_me_reconnect_attempts_total 2821583
telemt_me_reconnect_success_total 1117
telemt_me_reader_eof_total 1403
telemt_me_idle_close_by_peer_total 1403
telemt_me_route_drop_no_conn_total 1868856
telemt_me_route_drop_channel_closed_total 16
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 904435
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
telemt_desync_total 1641
telemt_desync_full_logged_total 518
telemt_desync_suppressed_total 1123
telemt_desync_frames_bucket_total{bucket="1_2"} 404
telemt_desync_frames_bucket_total{bucket="3_10"} 671
telemt_desync_frames_bucket_total{bucket="gt_10"} 566
telemt_me_writer_removed_unexpected_total 1447
telemt_me_refill_failed_total 99877
telemt_me_writer_restored_same_endpoint_total 1022
telemt_me_writer_restored_fallback_total 95
telemt_me_async_recovery_trigger_total 365465
telemt_me_writer_removed_unexpected_minus_restored_total 330
telemt_user_connections_total{user="hello"} 923283
telemt_user_connections_current{user="hello"} 3022
telemt_user_octets_from_client{user="hello"} 6375236942 (5.94 GB)
telemt_user_octets_to_client{user="hello"} 135423954701 (126.12 GB)
telemt_user_msgs_from_client{user="hello"} 80007
telemt_user_msgs_to_client{user="hello"} 158054
telemt_user_unique_ips_current{user="hello"} 895
telemt_user_unique_ips_recent_window{user="hello"} 400
```

## rdp-onedash.ru

```
telemt 3.3.20

telemt_uptime_seconds 9278.9 (2h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 684313
telemt_connections_bad_total 20753
telemt_handshake_timeouts_total 9958
telemt_upstream_connect_attempt_total 11222
telemt_upstream_connect_success_total 11221
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 11222
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9867
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1134
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 220
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 61
telemt_me_reconnect_attempts_total 2983159
telemt_me_reconnect_success_total 1201
telemt_me_reader_eof_total 1178
telemt_me_idle_close_by_peer_total 1178
telemt_me_route_drop_no_conn_total 450743
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 583172
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2020
telemt_desync_full_logged_total 666
telemt_desync_suppressed_total 1354
telemt_desync_frames_bucket_total{bucket="1_2"} 321
telemt_desync_frames_bucket_total{bucket="3_10"} 786
telemt_desync_frames_bucket_total{bucket="gt_10"} 913
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 1164
telemt_me_refill_failed_total 107153
telemt_me_writer_restored_same_endpoint_total 1086
telemt_me_writer_restored_fallback_total 115
telemt_me_async_recovery_trigger_total 267383
telemt_user_connections_total{user="hello"} 589894
telemt_user_connections_current{user="hello"} 3364
telemt_user_octets_from_client{user="hello"} 8559880885 (7.97 GB)
telemt_user_octets_to_client{user="hello"} 224664611969 (209.24 GB)
telemt_user_msgs_from_client{user="hello"} 86293
telemt_user_msgs_to_client{user="hello"} 266108
telemt_user_unique_ips_current{user="hello"} 1030
telemt_user_unique_ips_recent_window{user="hello"} 463
```

## hostvds.com

```
telemt 3.3.20

telemt_uptime_seconds 9163.9 (2h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 199888
telemt_connections_bad_total 22188
telemt_handshake_timeouts_total 1382
telemt_upstream_connect_attempt_total 1777
telemt_upstream_connect_success_total 1777
telemt_upstream_connect_attempts_per_request{bucket="1"} 1777
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 947
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 830
telemt_me_reconnect_attempts_total 1252
telemt_me_reconnect_success_total 1238
telemt_me_reader_eof_total 1259
telemt_me_idle_close_by_peer_total 1258
telemt_me_route_drop_no_conn_total 101927
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 170068
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 428
telemt_desync_full_logged_total 146
telemt_desync_suppressed_total 282
telemt_desync_frames_bucket_total{bucket="1_2"} 81
telemt_desync_frames_bucket_total{bucket="3_10"} 153
telemt_desync_frames_bucket_total{bucket="gt_10"} 194
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1243
telemt_me_writer_restored_same_endpoint_total 1230
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 130
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 160397
telemt_user_connections_current{user="hello"} 911
telemt_user_octets_from_client{user="hello"} 2258327888 (2.10 GB)
telemt_user_octets_to_client{user="hello"} 38663584796 (36.01 GB)
telemt_user_unique_ips_current{user="hello"} 342
telemt_user_unique_ips_recent_window{user="hello"} 134
```

## 4vps.su

```
telemt 3.3.20

telemt_uptime_seconds 9234.7 (2h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 487283
telemt_connections_bad_total 25010
telemt_handshake_timeouts_total 11401
telemt_upstream_connect_attempt_total 1703
telemt_upstream_connect_success_total 1683
telemt_upstream_connect_fail_total 20
telemt_upstream_connect_attempts_per_request{bucket="1"} 1703
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 931
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 744
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 20
telemt_me_reconnect_attempts_total 1167
telemt_me_reconnect_success_total 1147
telemt_me_reader_eof_total 1160
telemt_me_idle_close_by_peer_total 1160
telemt_me_route_drop_no_conn_total 232072
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 412932
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1560
telemt_desync_full_logged_total 535
telemt_desync_suppressed_total 1025
telemt_desync_frames_bucket_total{bucket="1_2"} 284
telemt_desync_frames_bucket_total{bucket="3_10"} 548
telemt_desync_frames_bucket_total{bucket="gt_10"} 728
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1146
telemt_me_writer_restored_same_endpoint_total 1137
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 2494
telemt_user_connections_total{user="hello"} 412638
telemt_user_connections_current{user="hello"} 3004
telemt_user_octets_from_client{user="hello"} 6925330172 (6.45 GB)
telemt_user_octets_to_client{user="hello"} 210894613860 (196.41 GB)
telemt_user_unique_ips_current{user="hello"} 885
telemt_user_unique_ips_recent_window{user="hello"} 398
```