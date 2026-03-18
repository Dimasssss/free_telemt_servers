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

# Server Metrics 2026-03-18 06:27:26 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 128528.5 (35h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1593946
telemt_connections_bad_total 10699
telemt_handshake_timeouts_total 36372
telemt_upstream_connect_attempt_total 27869
telemt_upstream_connect_success_total 27350
telemt_upstream_connect_fail_total 519
telemt_upstream_connect_attempts_per_request{bucket="1"} 27869
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13982
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13160
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 208
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 519
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 279
telemt_me_reconnect_attempts_total 35831
telemt_me_reconnect_success_total 18676
telemt_me_reader_eof_total 20244
telemt_me_idle_close_by_peer_total 20243
telemt_me_route_drop_no_conn_total 629500
telemt_me_route_drop_channel_closed_total 173
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1373655
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8349
telemt_desync_full_logged_total 2516
telemt_desync_suppressed_total 5833
telemt_desync_frames_bucket_total{bucket="1_2"} 2182
telemt_desync_frames_bucket_total{bucket="3_10"} 3207
telemt_desync_frames_bucket_total{bucket="gt_10"} 2960
telemt_pool_swap_total 110
telemt_me_writer_removed_unexpected_total 19491
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 18654
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 815
telemt_user_connections_total{user="hello"} 1367903
telemt_user_connections_current{user="hello"} 1055
telemt_user_octets_from_client{user="hello"} 32404468835 (30.18 GB)
telemt_user_octets_to_client{user="hello"} 490725491359 (457.02 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 401
telemt_user_unique_ips_recent_window{user="hello"} 149
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 128780.6 (35h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1704012
telemt_connections_bad_total 83570
telemt_handshake_timeouts_total 54880
telemt_upstream_connect_attempt_total 471314
telemt_upstream_connect_success_total 469676
telemt_upstream_connect_fail_total 1638
telemt_upstream_connect_attempts_per_request{bucket="1"} 471314
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 391342
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34966
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43366
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1638
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 343
telemt_me_reconnect_attempts_total 127081
telemt_me_reconnect_success_total 20348
telemt_me_reader_eof_total 22659
telemt_me_idle_close_by_peer_total 22646
telemt_me_route_drop_no_conn_total 453910
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1042741
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4773
telemt_desync_full_logged_total 1664
telemt_desync_suppressed_total 3109
telemt_desync_frames_bucket_total{bucket="1_2"} 925
telemt_desync_frames_bucket_total{bucket="3_10"} 1931
telemt_desync_frames_bucket_total{bucket="gt_10"} 1917
telemt_pool_swap_total 75
telemt_me_writer_removed_unexpected_total 21980
telemt_me_refill_failed_total 3329
telemt_me_writer_restored_same_endpoint_total 20330
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 6668
telemt_me_writer_removed_unexpected_minus_restored_total 1632
telemt_user_connections_total{user="hello"} 1485023
telemt_user_connections_current{user="hello"} 2148
telemt_user_octets_from_client{user="hello"} 21413168969 (19.94 GB)
telemt_user_octets_to_client{user="hello"} 578225544210 (538.51 GB)
telemt_user_msgs_from_client{user="hello"} 7472583
telemt_user_msgs_to_client{user="hello"} 31958899
telemt_user_unique_ips_current{user="hello"} 685
telemt_user_unique_ips_recent_window{user="hello"} 303
```

## koara.io

Не удалось получить метрики для этого сервера.

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 128615.6 (35h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1596398
telemt_connections_bad_total 81121
telemt_handshake_timeouts_total 28160
telemt_upstream_connect_attempt_total 92215
telemt_upstream_connect_success_total 89763
telemt_upstream_connect_fail_total 2452
telemt_upstream_connect_attempts_per_request{bucket="1"} 92215
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 74069
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15278
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 383
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2452
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 320
telemt_me_reconnect_attempts_total 39036
telemt_me_reconnect_success_total 18614
telemt_me_reader_eof_total 20407
telemt_me_idle_close_by_peer_total 20404
telemt_me_route_drop_no_conn_total 637111
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1306825
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5095
telemt_desync_full_logged_total 1635
telemt_desync_suppressed_total 3460
telemt_desync_frames_bucket_total{bucket="1_2"} 1201
telemt_desync_frames_bucket_total{bucket="3_10"} 2112
telemt_desync_frames_bucket_total{bucket="gt_10"} 1782
telemt_pool_swap_total 102
telemt_me_writer_removed_unexpected_total 19596
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 18594
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 982
telemt_user_connections_total{user="hello"} 1370084
telemt_user_connections_current{user="hello"} 2336
telemt_user_octets_from_client{user="hello"} 23188786222 (21.60 GB)
telemt_user_octets_to_client{user="hello"} 665238616442 (619.55 GB)
telemt_user_msgs_from_client{user="hello"} 744103
telemt_user_msgs_to_client{user="hello"} 5214294
telemt_user_unique_ips_current{user="hello"} 608
telemt_user_unique_ips_recent_window{user="hello"} 277
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 128587.6 (35h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1138867
telemt_connections_bad_total 106533
telemt_handshake_timeouts_total 11851
telemt_upstream_connect_attempt_total 49204
telemt_upstream_connect_success_total 48526
telemt_upstream_connect_fail_total 678
telemt_upstream_connect_attempts_per_request{bucket="1"} 49204
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29897
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18203
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 426
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 678
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 60636
telemt_me_reconnect_success_total 25666
telemt_me_reader_eof_total 27744
telemt_me_idle_close_by_peer_total 27741
telemt_me_route_drop_no_conn_total 366779
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 937509
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4045
telemt_desync_full_logged_total 1241
telemt_desync_suppressed_total 2804
telemt_desync_frames_bucket_total{bucket="1_2"} 1121
telemt_desync_frames_bucket_total{bucket="3_10"} 1560
telemt_desync_frames_bucket_total{bucket="gt_10"} 1364
telemt_pool_swap_total 69
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 27153
telemt_me_refill_failed_total 1087
telemt_me_writer_restored_same_endpoint_total 25658
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1487
telemt_user_connections_total{user="hello"} 953939
telemt_user_connections_current{user="hello"} 1743
telemt_user_octets_from_client{user="hello"} 17721861192 (16.50 GB)
telemt_user_octets_to_client{user="hello"} 481329829732 (448.27 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 575
telemt_user_unique_ips_recent_window{user="hello"} 257
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 128748.8 (35h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1244039
telemt_connections_bad_total 129456
telemt_handshake_timeouts_total 10719
telemt_upstream_connect_attempt_total 25516
telemt_upstream_connect_success_total 25364
telemt_upstream_connect_fail_total 151
telemt_upstream_connect_attempts_per_request{bucket="1"} 25515
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12200
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13045
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 109
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 151
telemt_me_keepalive_timeout_total 152
telemt_me_reconnect_attempts_total 30274
telemt_me_reconnect_success_total 18977
telemt_me_reader_eof_total 20553
telemt_me_idle_close_by_peer_total 20551
telemt_me_route_drop_no_conn_total 838276
telemt_me_route_drop_channel_closed_total 92
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1219344
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2354
telemt_desync_full_logged_total 831
telemt_desync_suppressed_total 1523
telemt_desync_frames_bucket_total{bucket="1_2"} 525
telemt_desync_frames_bucket_total{bucket="3_10"} 903
telemt_desync_frames_bucket_total{bucket="gt_10"} 926
telemt_pool_swap_total 117
telemt_pool_stale_pick_total 2
telemt_me_writer_removed_unexpected_total 19620
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 18963
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 298
telemt_me_writer_removed_unexpected_minus_restored_total 643
telemt_user_connections_total{user="hello"} 1028009
telemt_user_connections_current{user="hello"} 777
telemt_user_octets_from_client{user="hello"} 16272463508 (15.15 GB)
telemt_user_octets_to_client{user="hello"} 457782975220 (426.34 GB)
telemt_user_unique_ips_current{user="hello"} 267
telemt_user_unique_ips_recent_window{user="hello"} 103
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 76515.7 (21h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 627470
telemt_connections_bad_total 57743
telemt_handshake_timeouts_total 14175
telemt_upstream_connect_attempt_total 26081
telemt_upstream_connect_success_total 25809
telemt_upstream_connect_fail_total 272
telemt_upstream_connect_attempts_per_request{bucket="1"} 26081
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13784
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11929
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 272
telemt_me_keepalive_timeout_total 98
telemt_me_reconnect_attempts_total 33494
telemt_me_reconnect_success_total 21878
telemt_me_reader_eof_total 23119
telemt_me_idle_close_by_peer_total 23119
telemt_me_seq_mismatch_total 35
telemt_me_route_drop_no_conn_total 156224
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 463784
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 39
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2035
telemt_desync_full_logged_total 683
telemt_desync_suppressed_total 1352
telemt_desync_frames_bucket_total{bucket="1_2"} 334
telemt_desync_frames_bucket_total{bucket="3_10"} 900
telemt_desync_frames_bucket_total{bucket="gt_10"} 801
telemt_pool_swap_total 54
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 22475
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 21833
telemt_me_writer_restored_fallback_total 45
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 597
telemt_user_connections_total{user="hello"} 463538
telemt_user_connections_current{user="hello"} 1249
telemt_user_octets_from_client{user="hello"} 27305678637 (25.43 GB)
telemt_user_octets_to_client{user="hello"} 358857727842 (334.21 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 391
telemt_user_unique_ips_recent_window{user="hello"} 167
```