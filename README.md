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

# Server Metrics 2026-03-19 03:50:30 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 21722.8 (6h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 278952
telemt_connections_bad_total 31936
telemt_connections_current 711
telemt_connections_me_current 711
telemt_handshake_timeouts_total 18177
telemt_upstream_connect_attempt_total 4289
telemt_upstream_connect_success_total 4221
telemt_upstream_connect_fail_total 68
telemt_upstream_connect_attempts_per_request{bucket="1"} 4289
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2053
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2165
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 68
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 3125
telemt_me_reconnect_success_total 3110
telemt_me_reader_eof_total 3264
telemt_me_idle_close_by_peer_total 3264
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 73393
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 211220
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1516
telemt_desync_full_logged_total 410
telemt_desync_suppressed_total 1106
telemt_desync_frames_bucket_total{bucket="1_2"} 559
telemt_desync_frames_bucket_total{bucket="3_10"} 627
telemt_desync_frames_bucket_total{bucket="gt_10"} 330
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 3131
telemt_me_writer_restored_same_endpoint_total 3093
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 21
telemt_user_connections_total{user="hello"} 208458
telemt_user_connections_current{user="hello"} 711
telemt_user_octets_from_client{user="hello"} 2258670320 (2.10 GB)
telemt_user_octets_to_client{user="hello"} 62067627688 (57.80 GB)
telemt_user_unique_ips_current{user="hello"} 300
telemt_user_unique_ips_recent_window{user="hello"} 96
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 21727.0 (6h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 515214
telemt_connections_bad_total 38325
telemt_connections_current 2255
telemt_connections_me_current 2255
telemt_handshake_timeouts_total 14413
telemt_upstream_connect_attempt_total 4128
telemt_upstream_connect_success_total 4054
telemt_upstream_connect_fail_total 74
telemt_upstream_connect_attempts_per_request{bucket="1"} 4128
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1926
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2120
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 74
telemt_me_reconnect_attempts_total 2947
telemt_me_reconnect_success_total 2933
telemt_me_reader_eof_total 3090
telemt_me_idle_close_by_peer_total 3090
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 152107
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 422808
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 29
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1590
telemt_desync_full_logged_total 543
telemt_desync_suppressed_total 1047
telemt_desync_frames_bucket_total{bucket="1_2"} 343
telemt_desync_frames_bucket_total{bucket="3_10"} 596
telemt_desync_frames_bucket_total{bucket="gt_10"} 651
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 2977
telemt_me_writer_restored_same_endpoint_total 2916
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 44
telemt_user_connections_total{user="hello"} 422783
telemt_user_connections_current{user="hello"} 2255
telemt_user_octets_from_client{user="hello"} 12981074976 (12.09 GB)
telemt_user_octets_to_client{user="hello"} 178872192800 (166.59 GB)
telemt_user_unique_ips_current{user="hello"} 805
telemt_user_unique_ips_recent_window{user="hello"} 267
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 21723.9 (6h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 419085
telemt_connections_bad_total 89208
telemt_connections_current 1549
telemt_connections_me_current 1549
telemt_handshake_timeouts_total 10567
telemt_upstream_connect_attempt_total 4084
telemt_upstream_connect_success_total 4084
telemt_upstream_connect_attempts_per_request{bucket="1"} 4084
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2054
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2023
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 2977
telemt_me_reconnect_success_total 2967
telemt_me_reader_eof_total 3137
telemt_me_idle_close_by_peer_total 3137
telemt_me_route_drop_no_conn_total 123282
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 306046
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1508
telemt_desync_full_logged_total 569
telemt_desync_suppressed_total 939
telemt_desync_frames_bucket_total{bucket="1_2"} 260
telemt_desync_frames_bucket_total{bucket="3_10"} 620
telemt_desync_frames_bucket_total{bucket="gt_10"} 628
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 3014
telemt_me_writer_restored_same_endpoint_total 2951
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 47
telemt_user_connections_total{user="hello"} 306041
telemt_user_connections_current{user="hello"} 1549
telemt_user_octets_from_client{user="hello"} 6458991192 (6.02 GB)
telemt_user_octets_to_client{user="hello"} 190809741304 (177.71 GB)
telemt_user_unique_ips_current{user="hello"} 600
telemt_user_unique_ips_recent_window{user="hello"} 191
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 21777.1 (6h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 508058
telemt_connections_bad_total 58588
telemt_connections_current 1495
telemt_connections_me_current 1495
telemt_handshake_timeouts_total 10212
telemt_upstream_connect_attempt_total 3977
telemt_upstream_connect_success_total 3977
telemt_upstream_connect_attempts_per_request{bucket="1"} 3977
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2007
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1962
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 2873
telemt_me_reconnect_success_total 2862
telemt_me_reader_eof_total 3016
telemt_me_idle_close_by_peer_total 3015
telemt_me_route_drop_no_conn_total 127971
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 306614
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 850
telemt_desync_full_logged_total 306
telemt_desync_suppressed_total 544
telemt_desync_frames_bucket_total{bucket="1_2"} 180
telemt_desync_frames_bucket_total{bucket="3_10"} 369
telemt_desync_frames_bucket_total{bucket="gt_10"} 301
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 2894
telemt_me_writer_restored_same_endpoint_total 2838
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 272
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 306357
telemt_user_connections_current{user="hello"} 1495
telemt_user_octets_from_client{user="hello"} 3587548868 (3.34 GB)
telemt_user_octets_to_client{user="hello"} 111957377892 (104.27 GB)
telemt_user_unique_ips_current{user="hello"} 564
telemt_user_unique_ips_recent_window{user="hello"} 187
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 21720.4 (6h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 506888
telemt_connections_bad_total 92787
telemt_connections_current 1551
telemt_connections_me_current 1551
telemt_handshake_timeouts_total 16735
telemt_upstream_connect_attempt_total 4094
telemt_upstream_connect_success_total 4066
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 4094
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2026
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2026
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_reconnect_attempts_total 2962
telemt_me_reconnect_success_total 2944
telemt_me_reader_eof_total 3106
telemt_me_idle_close_by_peer_total 3106
telemt_me_route_drop_no_conn_total 141275
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 335065
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1467
telemt_desync_full_logged_total 563
telemt_desync_suppressed_total 904
telemt_desync_frames_bucket_total{bucket="1_2"} 372
telemt_desync_frames_bucket_total{bucket="3_10"} 589
telemt_desync_frames_bucket_total{bucket="gt_10"} 506
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 2969
telemt_me_writer_restored_same_endpoint_total 2920
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 25
telemt_user_connections_total{user="hello"} 334982
telemt_user_connections_current{user="hello"} 1551
telemt_user_octets_from_client{user="hello"} 10635680920 (9.91 GB)
telemt_user_octets_to_client{user="hello"} 192830010916 (179.59 GB)
telemt_user_unique_ips_current{user="hello"} 667
telemt_user_unique_ips_recent_window{user="hello"} 198
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 21731.9 (6h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 103559
telemt_connections_bad_total 10132
telemt_connections_current 401
telemt_connections_me_current 401
telemt_handshake_timeouts_total 465
telemt_upstream_connect_attempt_total 6057
telemt_upstream_connect_success_total 5891
telemt_upstream_connect_fail_total 166
telemt_upstream_connect_attempts_per_request{bucket="1"} 6057
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2802
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3089
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 166
telemt_me_reconnect_attempts_total 6616
telemt_me_reconnect_success_total 4778
telemt_me_reader_eof_total 5024
telemt_me_idle_close_by_peer_total 5024
telemt_me_route_drop_no_conn_total 43105
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 89524
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 43
telemt_desync_full_logged_total 15
telemt_desync_suppressed_total 28
telemt_desync_frames_bucket_total{bucket="1_2"} 24
telemt_desync_frames_bucket_total{bucket="3_10"} 16
telemt_desync_frames_bucket_total{bucket="gt_10"} 3
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 4844
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 4748
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 66
telemt_user_connections_total{user="hello"} 89516
telemt_user_connections_current{user="hello"} 401
telemt_user_octets_from_client{user="hello"} 1697118504 (1.58 GB)
telemt_user_octets_to_client{user="hello"} 58980287768 (54.93 GB)
telemt_user_unique_ips_current{user="hello"} 169
telemt_user_unique_ips_recent_window{user="hello"} 60
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 21722.9 (6h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 315851
telemt_connections_bad_total 30512
telemt_connections_current 1648
telemt_connections_me_current 1648
telemt_handshake_timeouts_total 16917
telemt_upstream_connect_attempt_total 4593
telemt_upstream_connect_success_total 4593
telemt_upstream_connect_attempts_per_request{bucket="1"} 4593
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2421
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2169
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 3489
telemt_me_reconnect_success_total 3480
telemt_me_reader_eof_total 3669
telemt_me_idle_close_by_peer_total 3669
telemt_me_route_drop_no_conn_total 89840
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 259873
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1295
telemt_desync_full_logged_total 497
telemt_desync_suppressed_total 798
telemt_desync_frames_bucket_total{bucket="1_2"} 241
telemt_desync_frames_bucket_total{bucket="3_10"} 513
telemt_desync_frames_bucket_total{bucket="gt_10"} 541
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 3518
telemt_me_writer_restored_same_endpoint_total 3465
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 38
telemt_user_connections_total{user="hello"} 259893
telemt_user_connections_current{user="hello"} 1648
telemt_user_octets_from_client{user="hello"} 2794968640 (2.60 GB)
telemt_user_octets_to_client{user="hello"} 143571446344 (133.71 GB)
telemt_user_unique_ips_current{user="hello"} 582
telemt_user_unique_ips_recent_window{user="hello"} 192
```