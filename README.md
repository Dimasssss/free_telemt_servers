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

# Server Metrics 2026-03-17 17:07:28 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 80532.1 (22h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 957651
telemt_connections_bad_total 6498
telemt_handshake_timeouts_total 27117
telemt_upstream_connect_attempt_total 19075
telemt_upstream_connect_success_total 18599
telemt_upstream_connect_fail_total 476
telemt_upstream_connect_attempts_per_request{bucket="1"} 19075
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9703
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8735
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 161
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 476
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 169
telemt_me_reconnect_attempts_total 29369
telemt_me_reconnect_success_total 12253
telemt_me_reader_eof_total 13367
telemt_me_idle_close_by_peer_total 13366
telemt_me_route_drop_no_conn_total 440452
telemt_me_route_drop_channel_closed_total 120
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 876965
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5864
telemt_desync_full_logged_total 1653
telemt_desync_suppressed_total 4211
telemt_desync_frames_bucket_total{bucket="1_2"} 1640
telemt_desync_frames_bucket_total{bucket="3_10"} 2268
telemt_desync_frames_bucket_total{bucket="gt_10"} 1956
telemt_pool_swap_total 60
telemt_me_writer_removed_unexpected_total 12959
telemt_me_refill_failed_total 529
telemt_me_writer_restored_same_endpoint_total 12231
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 706
telemt_user_connections_total{user="hello"} 871238
telemt_user_connections_current{user="hello"} 1300
telemt_user_octets_from_client{user="hello"} 13453775731 (12.53 GB)
telemt_user_octets_to_client{user="hello"} 293565567639 (273.40 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 405
telemt_user_unique_ips_recent_window{user="hello"} 198
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 80783.8 (22h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 757442
telemt_connections_bad_total 44421
telemt_handshake_timeouts_total 29873
telemt_upstream_connect_attempt_total 267843
telemt_upstream_connect_success_total 267119
telemt_upstream_connect_fail_total 686
telemt_upstream_connect_attempts_per_request{bucket="1"} 267805
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 220793
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21715
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24609
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 686
telemt_me_keepalive_timeout_total 342
telemt_me_reconnect_attempts_total 48458
telemt_me_reconnect_success_total 13565
telemt_me_reader_eof_total 15207
telemt_me_idle_close_by_peer_total 15207
telemt_me_route_drop_no_conn_total 215874
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 399793
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1525
telemt_desync_full_logged_total 482
telemt_desync_suppressed_total 1043
telemt_desync_frames_bucket_total{bucket="1_2"} 345
telemt_desync_frames_bucket_total{bucket="3_10"} 663
telemt_desync_frames_bucket_total{bucket="gt_10"} 517
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 14818
telemt_me_refill_failed_total 1086
telemt_me_writer_restored_same_endpoint_total 13549
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 1253
telemt_user_connections_total{user="hello"} 649203
telemt_user_connections_current{user="hello"} 2906
telemt_user_octets_from_client{user="hello"} 8496699745 (7.91 GB)
telemt_user_octets_to_client{user="hello"} 176961032355 (164.81 GB)
telemt_user_msgs_from_client{user="hello"} 4029105
telemt_user_msgs_to_client{user="hello"} 16752010
telemt_user_unique_ips_current{user="hello"} 555
telemt_user_unique_ips_recent_window{user="hello"} 351
```

## koara.io

Не удалось получить метрики для этого сервера.

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 80618.7 (22h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 826001
telemt_connections_bad_total 15570
telemt_handshake_timeouts_total 15925
telemt_upstream_connect_attempt_total 80109
telemt_upstream_connect_success_total 79717
telemt_upstream_connect_fail_total 392
telemt_upstream_connect_attempts_per_request{bucket="1"} 80109
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 68586
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10785
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 28
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 318
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 392
telemt_me_keepalive_timeout_total 133
telemt_me_reconnect_attempts_total 32585
telemt_me_reconnect_success_total 12290
telemt_me_reader_eof_total 13585
telemt_me_idle_close_by_peer_total 13584
telemt_me_route_drop_no_conn_total 316989
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 656247
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2111
telemt_desync_full_logged_total 696
telemt_desync_suppressed_total 1415
telemt_desync_frames_bucket_total{bucket="1_2"} 513
telemt_desync_frames_bucket_total{bucket="3_10"} 951
telemt_desync_frames_bucket_total{bucket="gt_10"} 647
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 13140
telemt_me_refill_failed_total 629
telemt_me_writer_restored_same_endpoint_total 12281
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 850
telemt_user_connections_total{user="hello"} 719391
telemt_user_connections_current{user="hello"} 2480
telemt_user_octets_from_client{user="hello"} 8823963191 (8.22 GB)
telemt_user_octets_to_client{user="hello"} 228059305489 (212.40 GB)
telemt_user_msgs_from_client{user="hello"} 734453
telemt_user_msgs_to_client{user="hello"} 5166140
telemt_user_unique_ips_current{user="hello"} 527
telemt_user_unique_ips_recent_window{user="hello"} 331
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 80590.6 (22h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 420819
telemt_connections_bad_total 69062
telemt_handshake_timeouts_total 4233
telemt_upstream_connect_attempt_total 38470
telemt_upstream_connect_success_total 37971
telemt_upstream_connect_fail_total 498
telemt_upstream_connect_attempts_per_request{bucket="1"} 38469
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24916
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12703
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 352
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 498
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 48721
telemt_me_reconnect_success_total 17428
telemt_me_reader_eof_total 19002
telemt_me_idle_close_by_peer_total 19000
telemt_me_route_drop_no_conn_total 122343
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 312902
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1425
telemt_desync_full_logged_total 334
telemt_desync_suppressed_total 1091
telemt_desync_frames_bucket_total{bucket="1_2"} 628
telemt_desync_frames_bucket_total{bucket="3_10"} 568
telemt_desync_frames_bucket_total{bucket="gt_10"} 229
telemt_pool_swap_total 37
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 18693
telemt_me_refill_failed_total 973
telemt_me_writer_restored_same_endpoint_total 17420
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1265
telemt_user_connections_total{user="hello"} 329606
telemt_user_connections_current{user="hello"} 2075
telemt_user_octets_from_client{user="hello"} 4815206132 (4.48 GB)
telemt_user_octets_to_client{user="hello"} 141907940652 (132.16 GB)
telemt_user_msgs_from_client{user="hello"} 351047
telemt_user_msgs_to_client{user="hello"} 2469432
telemt_user_unique_ips_current{user="hello"} 483
telemt_user_unique_ips_recent_window{user="hello"} 263
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 80752.5 (22h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 811917
telemt_connections_bad_total 60223
telemt_handshake_timeouts_total 7663
telemt_upstream_connect_attempt_total 16289
telemt_upstream_connect_success_total 16199
telemt_upstream_connect_fail_total 90
telemt_upstream_connect_attempts_per_request{bucket="1"} 16289
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7771
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8372
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 90
telemt_me_keepalive_timeout_total 117
telemt_me_reconnect_attempts_total 23411
telemt_me_reconnect_success_total 12144
telemt_me_reader_eof_total 13213
telemt_me_idle_close_by_peer_total 13211
telemt_me_route_drop_no_conn_total 607956
telemt_me_route_drop_channel_closed_total 71
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 837015
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1421
telemt_desync_full_logged_total 499
telemt_desync_suppressed_total 922
telemt_desync_frames_bucket_total{bucket="1_2"} 335
telemt_desync_frames_bucket_total{bucket="3_10"} 552
telemt_desync_frames_bucket_total{bucket="gt_10"} 534
telemt_pool_swap_total 64
telemt_me_writer_removed_unexpected_total 12696
telemt_me_refill_failed_total 349
telemt_me_writer_restored_same_endpoint_total 12130
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 552
telemt_user_connections_total{user="hello"} 702157
telemt_user_connections_current{user="hello"} 939
telemt_user_octets_from_client{user="hello"} 10294454640 (9.59 GB)
telemt_user_octets_to_client{user="hello"} 311482193992 (290.09 GB)
telemt_user_unique_ips_current{user="hello"} 323
telemt_user_unique_ips_recent_window{user="hello"} 135
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 28518.7 (7h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 87559
telemt_connections_bad_total 5741
telemt_handshake_timeouts_total 633
telemt_upstream_connect_attempt_total 14108
telemt_upstream_connect_success_total 13990
telemt_upstream_connect_fail_total 118
telemt_upstream_connect_attempts_per_request{bucket="1"} 14108
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7539
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6398
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 118
telemt_me_keepalive_timeout_total 51
telemt_me_reconnect_attempts_total 23956
telemt_me_reconnect_success_total 12381
telemt_me_reader_eof_total 13109
telemt_me_idle_close_by_peer_total 13109
telemt_me_seq_mismatch_total 14
telemt_me_route_drop_no_conn_total 22861
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 75759
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 130
telemt_desync_full_logged_total 35
telemt_desync_suppressed_total 95
telemt_desync_frames_bucket_total{bucket="1_2"} 32
telemt_desync_frames_bucket_total{bucket="3_10"} 50
telemt_desync_frames_bucket_total{bucket="gt_10"} 48
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 12887
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 12361
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 506
telemt_user_connections_total{user="hello"} 75750
telemt_user_connections_current{user="hello"} 1782
telemt_user_octets_from_client{user="hello"} 3850835657 (3.59 GB)
telemt_user_octets_to_client{user="hello"} 81757198318 (76.14 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 354
telemt_user_unique_ips_recent_window{user="hello"} 194
```