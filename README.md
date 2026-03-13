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

# Server Metrics 2026-03-13 17:27:52 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 122072.9 (33h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 514502
telemt_connections_bad_total 7097
telemt_handshake_timeouts_total 11676
telemt_upstream_connect_attempt_total 30468
telemt_upstream_connect_success_total 30317
telemt_upstream_connect_fail_total 151
telemt_upstream_connect_attempts_per_request{bucket="1"} 30468
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13736
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16508
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 73
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 151
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3414
telemt_me_reconnect_attempts_total 27760
telemt_me_reconnect_success_total 24210
telemt_me_reader_eof_total 25836
telemt_me_idle_close_by_peer_total 25835
telemt_me_route_drop_no_conn_total 167190
telemt_me_route_drop_channel_closed_total 28
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 447922
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1442
telemt_desync_full_logged_total 502
telemt_desync_suppressed_total 940
telemt_desync_frames_bucket_total{bucket="1_2"} 318
telemt_desync_frames_bucket_total{bucket="3_10"} 522
telemt_desync_frames_bucket_total{bucket="gt_10"} 602
telemt_pool_swap_total 110
telemt_me_writer_removed_unexpected_total 24584
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 24194
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 374
telemt_user_connections_total{user="hello"} 447491
telemt_user_connections_current{user="hello"} 402
telemt_user_octets_from_client{user="hello"} 8267095516 (7.70 GB)
telemt_user_octets_to_client{user="hello"} 209789814896 (195.38 GB)
telemt_user_unique_ips_current{user="hello"} 107
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 121967.0 (33h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 252340
telemt_connections_bad_total 1944
telemt_handshake_timeouts_total 1809
telemt_upstream_connect_attempt_total 106594
telemt_upstream_connect_success_total 105762
telemt_upstream_connect_fail_total 832
telemt_upstream_connect_attempts_per_request{bucket="1"} 106594
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 78239
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26034
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1489
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 832
telemt_me_keepalive_timeout_total 1513
telemt_me_reconnect_attempts_total 124576
telemt_me_reconnect_success_total 26033
telemt_me_reader_eof_total 29866
telemt_me_idle_close_by_peer_total 29866
telemt_me_route_drop_no_conn_total 82371
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 165453
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 30
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 32
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 18
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 29336
telemt_me_refill_failed_total 3075
telemt_me_writer_restored_same_endpoint_total 26016
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 3303
telemt_user_connections_total{user="hello"} 238875
telemt_user_connections_current{user="hello"} 194
telemt_user_octets_from_client{user="hello"} 2494836636 (2.32 GB)
telemt_user_octets_to_client{user="hello"} 73616029967 (68.56 GB)
telemt_user_msgs_from_client{user="hello"} 1154353
telemt_user_msgs_to_client{user="hello"} 6703732
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 121930.5 (33h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 298707
telemt_connections_bad_total 2490
telemt_handshake_timeouts_total 16415
telemt_upstream_connect_attempt_total 32576
telemt_upstream_connect_success_total 32572
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 32576
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15116
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17424
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2583
telemt_me_reconnect_attempts_total 27658
telemt_me_reconnect_success_total 26429
telemt_me_reader_eof_total 28336
telemt_me_idle_close_by_peer_total 28336
telemt_me_route_drop_no_conn_total 106924
telemt_me_route_drop_channel_closed_total 16
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 269262
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 104
telemt_desync_full_logged_total 48
telemt_desync_suppressed_total 56
telemt_desync_frames_bucket_total{bucket="1_2"} 9
telemt_desync_frames_bucket_total{bucket="3_10"} 34
telemt_desync_frames_bucket_total{bucket="gt_10"} 61
telemt_pool_swap_total 111
telemt_me_writer_removed_unexpected_total 26726
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 26409
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 297
telemt_user_connections_total{user="hello"} 269170
telemt_user_connections_current{user="hello"} 123
telemt_user_octets_from_client{user="hello"} 10144137504 (9.45 GB)
telemt_user_octets_to_client{user="hello"} 111654756748 (103.99 GB)
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 121906.0 (33h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 405442
telemt_connections_bad_total 15106
telemt_handshake_timeouts_total 3863
telemt_upstream_connect_attempt_total 58148
telemt_upstream_connect_success_total 47906
telemt_upstream_connect_fail_total 10242
telemt_upstream_connect_attempts_per_request{bucket="1"} 58148
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30030
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17600
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 267
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10242
telemt_me_keepalive_timeout_total 4566
telemt_me_reconnect_attempts_total 114185
telemt_me_reconnect_success_total 24533
telemt_me_reader_eof_total 28028
telemt_me_idle_close_by_peer_total 28021
telemt_me_route_drop_no_conn_total 140194
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 339469
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1350
telemt_desync_full_logged_total 402
telemt_desync_suppressed_total 948
telemt_desync_frames_bucket_total{bucket="1_2"} 331
telemt_desync_frames_bucket_total{bucket="3_10"} 520
telemt_desync_frames_bucket_total{bucket="gt_10"} 499
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 27643
telemt_me_refill_failed_total 2796
telemt_me_writer_restored_same_endpoint_total 24523
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3110
telemt_user_connections_total{user="hello"} 356606
telemt_user_connections_current{user="hello"} 192
telemt_user_octets_from_client{user="hello"} 8328559317 (7.76 GB)
telemt_user_octets_to_client{user="hello"} 128619744670 (119.79 GB)
telemt_user_msgs_from_client{user="hello"} 437079
telemt_user_msgs_to_client{user="hello"} 808056
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 72077.5 (20h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 117349
telemt_connections_bad_total 14983
telemt_handshake_timeouts_total 1388
telemt_upstream_connect_attempt_total 28612
telemt_upstream_connect_success_total 28352
telemt_upstream_connect_fail_total 260
telemt_upstream_connect_attempts_per_request{bucket="1"} 28612
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14685
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13580
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 87
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 260
telemt_me_keepalive_timeout_total 1151
telemt_me_reconnect_attempts_total 33225
telemt_me_reconnect_success_total 19839
telemt_me_reader_eof_total 21280
telemt_me_idle_close_by_peer_total 21280
telemt_me_route_drop_no_conn_total 36547
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 92287
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 408
telemt_desync_full_logged_total 82
telemt_desync_suppressed_total 326
telemt_desync_frames_bucket_total{bucket="1_2"} 53
telemt_desync_frames_bucket_total{bucket="3_10"} 222
telemt_desync_frames_bucket_total{bucket="gt_10"} 133
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 20437
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 19821
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 598
telemt_user_connections_total{user="hello"} 97185
telemt_user_connections_current{user="hello"} 122
telemt_user_octets_from_client{user="hello"} 1159112105 (1.08 GB)
telemt_user_octets_to_client{user="hello"} 30640674699 (28.54 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 121863.6 (33h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 743846
telemt_connections_bad_total 24648
telemt_handshake_timeouts_total 24402
telemt_upstream_connect_attempt_total 25458
telemt_upstream_connect_success_total 25325
telemt_upstream_connect_fail_total 133
telemt_upstream_connect_attempts_per_request{bucket="1"} 25458
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11874
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13420
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 133
telemt_me_keepalive_timeout_total 2887
telemt_me_reconnect_attempts_total 23904
telemt_me_reconnect_success_total 19262
telemt_me_reader_eof_total 20673
telemt_me_idle_close_by_peer_total 20670
telemt_me_route_drop_no_conn_total 351491
telemt_me_route_drop_channel_closed_total 15
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 697646
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 668
telemt_desync_full_logged_total 218
telemt_desync_suppressed_total 450
telemt_desync_frames_bucket_total{bucket="1_2"} 236
telemt_desync_frames_bucket_total{bucket="3_10"} 221
telemt_desync_frames_bucket_total{bucket="gt_10"} 211
telemt_pool_swap_total 112
telemt_me_writer_removed_unexpected_total 19658
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 19255
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 396
telemt_user_connections_total{user="hello"} 670530
telemt_user_connections_current{user="hello"} 439
telemt_user_octets_from_client{user="hello"} 11790510024 (10.98 GB)
telemt_user_octets_to_client{user="hello"} 337539158500 (314.36 GB)
telemt_user_unique_ips_current{user="hello"} 147
telemt_user_unique_ips_recent_window{user="hello"} 55
```