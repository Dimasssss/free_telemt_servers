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

# Server Metrics 2026-03-18 11:22:53 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.20

telemt_uptime_seconds 9712.9 (2h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 347615
telemt_connections_bad_total 3815
telemt_handshake_timeouts_total 8356
telemt_upstream_connect_attempt_total 64895
telemt_upstream_connect_success_total 63966
telemt_upstream_connect_fail_total 929
telemt_upstream_connect_attempts_per_request{bucket="1"} 64895
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 59925
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3458
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 583
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 929
telemt_me_keepalive_timeout_total 6
telemt_me_reconnect_attempts_total 509295
telemt_me_reconnect_success_total 1497
telemt_me_reader_eof_total 1510
telemt_me_idle_close_by_peer_total 1508
telemt_me_route_drop_no_conn_total 193328
telemt_me_route_drop_channel_closed_total 63
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 247557
telemt_me_writer_pick_total{mode="p2c",result="full"} 21
telemt_me_writer_pick_total{mode="p2c",result="closed"} 54
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1063
telemt_desync_full_logged_total 339
telemt_desync_suppressed_total 724
telemt_desync_frames_bucket_total{bucket="1_2"} 301
telemt_desync_frames_bucket_total{bucket="3_10"} 384
telemt_desync_frames_bucket_total{bucket="gt_10"} 378
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 1531
telemt_me_refill_failed_total 16552
telemt_me_writer_restored_same_endpoint_total 1392
telemt_me_writer_restored_fallback_total 105
telemt_me_async_recovery_trigger_total 11769
telemt_me_writer_removed_unexpected_minus_restored_total 34
telemt_user_connections_total{user="hello"} 305968
telemt_user_connections_current{user="hello"} 1639
telemt_user_octets_from_client{user="hello"} 3961083980 (3.69 GB)
telemt_user_octets_to_client{user="hello"} 80081015145 (74.58 GB)
telemt_user_msgs_from_client{user="hello"} 846607
telemt_user_msgs_to_client{user="hello"} 1165163
telemt_user_unique_ips_current{user="hello"} 541
telemt_user_unique_ips_recent_window{user="hello"} 215
```

## psb.hosting

```
telemt 3.3.20

telemt_uptime_seconds 9744.1 (2h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1050228
telemt_connections_bad_total 85055
telemt_handshake_timeouts_total 23587
telemt_upstream_connect_attempt_total 1736
telemt_upstream_connect_success_total 1724
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 1736
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 946
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 763
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_failed_total 1
telemt_me_reconnect_attempts_total 1219
telemt_me_reconnect_success_total 1176
telemt_me_reader_eof_total 1174
telemt_me_idle_close_by_peer_total 1173
telemt_me_route_drop_no_conn_total 1057094
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 895595
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2887
telemt_desync_full_logged_total 818
telemt_desync_suppressed_total 2069
telemt_desync_frames_bucket_total{bucket="1_2"} 588
telemt_desync_frames_bucket_total{bucket="3_10"} 1148
telemt_desync_frames_bucket_total{bucket="gt_10"} 1151
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 1172
telemt_me_writer_restored_same_endpoint_total 1175
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 1068
telemt_user_connections_total{user="hello"} 894905
telemt_user_connections_current{user="hello"} 3828
telemt_user_octets_from_client{user="hello"} 22624740388 (21.07 GB)
telemt_user_octets_to_client{user="hello"} 236751623144 (220.49 GB)
telemt_user_unique_ips_current{user="hello"} 1164
telemt_user_unique_ips_recent_window{user="hello"} 544
```

## koara.io

```
telemt 3.3.20

telemt_uptime_seconds 9659.4 (2h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 682694
telemt_connections_bad_total 45836
telemt_handshake_timeouts_total 17201
telemt_upstream_connect_attempt_total 10213
telemt_upstream_connect_success_total 10213
telemt_upstream_connect_attempts_per_request{bucket="1"} 10213
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8018
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2184
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 40
telemt_me_reconnect_attempts_total 607162
telemt_me_reconnect_success_total 1473
telemt_me_reader_eof_total 1470
telemt_me_idle_close_by_peer_total 1469
telemt_me_route_drop_no_conn_total 328377
telemt_me_route_drop_channel_closed_total 15
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 511298
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1253
telemt_desync_full_logged_total 437
telemt_desync_suppressed_total 816
telemt_desync_frames_bucket_total{bucket="1_2"} 298
telemt_desync_frames_bucket_total{bucket="3_10"} 483
telemt_desync_frames_bucket_total{bucket="gt_10"} 472
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 1473
telemt_me_refill_failed_total 19672
telemt_me_writer_restored_same_endpoint_total 1438
telemt_me_writer_restored_fallback_total 35
telemt_me_async_recovery_trigger_total 14895
telemt_user_connections_total{user="hello"} 519055
telemt_user_connections_current{user="hello"} 3085
telemt_user_octets_from_client{user="hello"} 5840135411 (5.44 GB)
telemt_user_octets_to_client{user="hello"} 204637909096 (190.58 GB)
telemt_user_msgs_from_client{user="hello"} 68547
telemt_user_msgs_to_client{user="hello"} 285346
telemt_user_unique_ips_current{user="hello"} 918
telemt_user_unique_ips_recent_window{user="hello"} 446
```

## landvps.ru

```
telemt 3.3.20

telemt_uptime_seconds 9689.7 (2h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1182341
telemt_connections_bad_total 14693
telemt_handshake_timeouts_total 142414
telemt_upstream_connect_attempt_total 12070
telemt_upstream_connect_success_total 11927
telemt_upstream_connect_fail_total 143
telemt_upstream_connect_attempts_per_request{bucket="1"} 12070
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10707
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1182
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 143
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 699
telemt_me_reconnect_attempts_total 2821590
telemt_me_reconnect_success_total 1124
telemt_me_reader_eof_total 1412
telemt_me_idle_close_by_peer_total 1412
telemt_me_route_drop_no_conn_total 1878100
telemt_me_route_drop_channel_closed_total 17
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 921434
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
telemt_desync_total 1714
telemt_desync_full_logged_total 536
telemt_desync_suppressed_total 1178
telemt_desync_frames_bucket_total{bucket="1_2"} 419
telemt_desync_frames_bucket_total{bucket="3_10"} 703
telemt_desync_frames_bucket_total{bucket="gt_10"} 592
telemt_me_writer_removed_unexpected_total 1456
telemt_me_refill_failed_total 99877
telemt_me_writer_restored_same_endpoint_total 1029
telemt_me_writer_restored_fallback_total 95
telemt_me_async_recovery_trigger_total 365465
telemt_me_writer_removed_unexpected_minus_restored_total 332
telemt_user_connections_total{user="hello"} 940270
telemt_user_connections_current{user="hello"} 3032
telemt_user_octets_from_client{user="hello"} 6544984226 (6.10 GB)
telemt_user_octets_to_client{user="hello"} 141181137461 (131.49 GB)
telemt_user_msgs_from_client{user="hello"} 80007
telemt_user_msgs_to_client{user="hello"} 158054
telemt_user_unique_ips_current{user="hello"} 887
telemt_user_unique_ips_recent_window{user="hello"} 422
```

## rdp-onedash.ru

```
telemt 3.3.20

telemt_uptime_seconds 9584.3 (2h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 706589
telemt_connections_bad_total 22396
telemt_handshake_timeouts_total 10115
telemt_upstream_connect_attempt_total 11240
telemt_upstream_connect_success_total 11239
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 11240
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9876
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1143
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 220
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 61
telemt_me_reconnect_attempts_total 2983177
telemt_me_reconnect_success_total 1218
telemt_me_reader_eof_total 1197
telemt_me_idle_close_by_peer_total 1197
telemt_me_route_drop_no_conn_total 468342
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 604507
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2080
telemt_desync_full_logged_total 684
telemt_desync_suppressed_total 1396
telemt_desync_frames_bucket_total{bucket="1_2"} 325
telemt_desync_frames_bucket_total{bucket="3_10"} 807
telemt_desync_frames_bucket_total{bucket="gt_10"} 948
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 1183
telemt_me_refill_failed_total 107153
telemt_me_writer_restored_same_endpoint_total 1103
telemt_me_writer_restored_fallback_total 115
telemt_me_async_recovery_trigger_total 267383
telemt_user_connections_total{user="hello"} 608751
telemt_user_connections_current{user="hello"} 3281
telemt_user_octets_from_client{user="hello"} 8804529177 (8.20 GB)
telemt_user_octets_to_client{user="hello"} 232261775981 (216.31 GB)
telemt_user_msgs_from_client{user="hello"} 86293
telemt_user_msgs_to_client{user="hello"} 266108
telemt_user_unique_ips_current{user="hello"} 1002
telemt_user_unique_ips_recent_window{user="hello"} 496
```

## hostvds.com

```
telemt 3.3.20

telemt_uptime_seconds 9469.7 (2h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 205172
telemt_connections_bad_total 22192
telemt_handshake_timeouts_total 1492
telemt_upstream_connect_attempt_total 1811
telemt_upstream_connect_success_total 1811
telemt_upstream_connect_attempts_per_request{bucket="1"} 1811
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 954
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 857
telemt_me_reconnect_attempts_total 1286
telemt_me_reconnect_success_total 1272
telemt_me_reader_eof_total 1303
telemt_me_idle_close_by_peer_total 1302
telemt_me_route_drop_no_conn_total 103385
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 174627
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
telemt_me_writer_removed_unexpected_total 1279
telemt_me_writer_restored_same_endpoint_total 1264
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 130
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 164956
telemt_user_connections_current{user="hello"} 897
telemt_user_octets_from_client{user="hello"} 2293430080 (2.14 GB)
telemt_user_octets_to_client{user="hello"} 39518533700 (36.80 GB)
telemt_user_unique_ips_current{user="hello"} 337
telemt_user_unique_ips_recent_window{user="hello"} 140
```

## 4vps.su

```
telemt 3.3.20

telemt_uptime_seconds 9540.4 (2h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 504977
telemt_connections_bad_total 25678
telemt_handshake_timeouts_total 11905
telemt_upstream_connect_attempt_total 1740
telemt_upstream_connect_success_total 1720
telemt_upstream_connect_fail_total 20
telemt_upstream_connect_attempts_per_request{bucket="1"} 1740
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 948
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 764
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 20
telemt_me_reconnect_attempts_total 1204
telemt_me_reconnect_success_total 1184
telemt_me_reader_eof_total 1197
telemt_me_idle_close_by_peer_total 1197
telemt_me_route_drop_no_conn_total 237733
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 427274
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1593
telemt_desync_full_logged_total 551
telemt_desync_suppressed_total 1042
telemt_desync_frames_bucket_total{bucket="1_2"} 287
telemt_desync_frames_bucket_total{bucket="3_10"} 563
telemt_desync_frames_bucket_total{bucket="gt_10"} 743
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1183
telemt_me_writer_restored_same_endpoint_total 1174
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 2494
telemt_user_connections_total{user="hello"} 426922
telemt_user_connections_current{user="hello"} 2918
telemt_user_octets_from_client{user="hello"} 7162063852 (6.67 GB)
telemt_user_octets_to_client{user="hello"} 219120039068 (204.07 GB)
telemt_user_unique_ips_current{user="hello"} 858
telemt_user_unique_ips_recent_window{user="hello"} 385
```