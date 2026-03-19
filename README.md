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

# Server Metrics 2026-03-19 02:38:58 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 17430.3 (4h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 212393
telemt_connections_bad_total 25570
telemt_connections_current 687
telemt_connections_me_current 687
telemt_handshake_timeouts_total 13003
telemt_upstream_connect_attempt_total 3480
telemt_upstream_connect_success_total 3425
telemt_upstream_connect_fail_total 55
telemt_upstream_connect_attempts_per_request{bucket="1"} 3480
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1646
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1776
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 55
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 2545
telemt_me_reconnect_success_total 2532
telemt_me_reader_eof_total 2649
telemt_me_idle_close_by_peer_total 2649
telemt_me_seq_mismatch_total 5
telemt_me_route_drop_no_conn_total 58410
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 164438
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1137
telemt_desync_full_logged_total 300
telemt_desync_suppressed_total 837
telemt_desync_frames_bucket_total{bucket="1_2"} 421
telemt_desync_frames_bucket_total{bucket="3_10"} 488
telemt_desync_frames_bucket_total{bucket="gt_10"} 228
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 2544
telemt_me_writer_restored_same_endpoint_total 2517
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 161666
telemt_user_connections_current{user="hello"} 687
telemt_user_octets_from_client{user="hello"} 1732794680 (1.61 GB)
telemt_user_octets_to_client{user="hello"} 51734916352 (48.18 GB)
telemt_user_unique_ips_current{user="hello"} 296
telemt_user_unique_ips_recent_window{user="hello"} 77
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 17434.1 (4h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 380648
telemt_connections_bad_total 23396
telemt_connections_current 1619
telemt_connections_me_current 1619
telemt_handshake_timeouts_total 9180
telemt_upstream_connect_attempt_total 3413
telemt_upstream_connect_success_total 3351
telemt_upstream_connect_fail_total 62
telemt_upstream_connect_attempts_per_request{bucket="1"} 3413
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1577
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1766
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 62
telemt_me_reconnect_attempts_total 2461
telemt_me_reconnect_success_total 2450
telemt_me_reader_eof_total 2575
telemt_me_idle_close_by_peer_total 2575
telemt_me_seq_mismatch_total 5
telemt_me_route_drop_no_conn_total 116183
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 324651
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1183
telemt_desync_full_logged_total 396
telemt_desync_suppressed_total 787
telemt_desync_frames_bucket_total{bucket="1_2"} 268
telemt_desync_frames_bucket_total{bucket="3_10"} 453
telemt_desync_frames_bucket_total{bucket="gt_10"} 462
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 2489
telemt_me_writer_restored_same_endpoint_total 2435
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 324690
telemt_user_connections_current{user="hello"} 1619
telemt_user_octets_from_client{user="hello"} 11887723116 (11.07 GB)
telemt_user_octets_to_client{user="hello"} 125780665936 (117.14 GB)
telemt_user_unique_ips_current{user="hello"} 653
telemt_user_unique_ips_recent_window{user="hello"} 166
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 17431.3 (4h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 309391
telemt_connections_bad_total 58860
telemt_connections_current 1303
telemt_connections_me_current 1303
telemt_handshake_timeouts_total 7357
telemt_upstream_connect_attempt_total 3365
telemt_upstream_connect_success_total 3365
telemt_upstream_connect_attempts_per_request{bucket="1"} 3365
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1698
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1662
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 2475
telemt_me_reconnect_success_total 2465
telemt_me_reader_eof_total 2606
telemt_me_idle_close_by_peer_total 2606
telemt_me_route_drop_no_conn_total 93130
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 234454
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1215
telemt_desync_full_logged_total 445
telemt_desync_suppressed_total 770
telemt_desync_frames_bucket_total{bucket="1_2"} 209
telemt_desync_frames_bucket_total{bucket="3_10"} 494
telemt_desync_frames_bucket_total{bucket="gt_10"} 512
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 2503
telemt_me_writer_restored_same_endpoint_total 2449
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 38
telemt_user_connections_total{user="hello"} 234449
telemt_user_connections_current{user="hello"} 1303
telemt_user_octets_from_client{user="hello"} 4078177380 (3.80 GB)
telemt_user_octets_to_client{user="hello"} 137125022052 (127.71 GB)
telemt_user_unique_ips_current{user="hello"} 524
telemt_user_unique_ips_recent_window{user="hello"} 126
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 17484.6 (4h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 367490
telemt_connections_bad_total 34888
telemt_connections_current 1007
telemt_connections_me_current 1007
telemt_handshake_timeouts_total 5581
telemt_upstream_connect_attempt_total 3227
telemt_upstream_connect_success_total 3227
telemt_upstream_connect_attempts_per_request{bucket="1"} 3227
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1653
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1566
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 2340
telemt_me_reconnect_success_total 2328
telemt_me_reader_eof_total 2448
telemt_me_idle_close_by_peer_total 2447
telemt_me_route_drop_no_conn_total 104530
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 235308
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 603
telemt_desync_full_logged_total 221
telemt_desync_suppressed_total 382
telemt_desync_frames_bucket_total{bucket="1_2"} 116
telemt_desync_frames_bucket_total{bucket="3_10"} 249
telemt_desync_frames_bucket_total{bucket="gt_10"} 238
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 2354
telemt_me_writer_restored_same_endpoint_total 2304
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 272
telemt_me_writer_removed_unexpected_minus_restored_total 26
telemt_user_connections_total{user="hello"} 235216
telemt_user_connections_current{user="hello"} 1007
telemt_user_octets_from_client{user="hello"} 2112836192 (1.97 GB)
telemt_user_octets_to_client{user="hello"} 79853665940 (74.37 GB)
telemt_user_unique_ips_current{user="hello"} 437
telemt_user_unique_ips_recent_window{user="hello"} 120
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 17428.0 (4h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 332639
telemt_connections_bad_total 19121
telemt_connections_current 1204
telemt_connections_me_current 1204
telemt_handshake_timeouts_total 11569
telemt_upstream_connect_attempt_total 3335
telemt_upstream_connect_success_total 3317
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 3335
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1602
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1704
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_reconnect_attempts_total 2430
telemt_me_reconnect_success_total 2416
telemt_me_reader_eof_total 2550
telemt_me_idle_close_by_peer_total 2550
telemt_me_route_drop_no_conn_total 101303
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 255796
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1096
telemt_desync_full_logged_total 413
telemt_desync_suppressed_total 683
telemt_desync_frames_bucket_total{bucket="1_2"} 301
telemt_desync_frames_bucket_total{bucket="3_10"} 406
telemt_desync_frames_bucket_total{bucket="gt_10"} 389
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 2431
telemt_me_writer_restored_same_endpoint_total 2392
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 15
telemt_user_connections_total{user="hello"} 255720
telemt_user_connections_current{user="hello"} 1204
telemt_user_octets_from_client{user="hello"} 8363687236 (7.79 GB)
telemt_user_octets_to_client{user="hello"} 142365374720 (132.59 GB)
telemt_user_unique_ips_current{user="hello"} 530
telemt_user_unique_ips_recent_window{user="hello"} 130
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 17439.5 (4h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 82589
telemt_connections_bad_total 9352
telemt_connections_current 334
telemt_connections_me_current 334
telemt_handshake_timeouts_total 349
telemt_upstream_connect_attempt_total 5096
telemt_upstream_connect_success_total 4946
telemt_upstream_connect_fail_total 150
telemt_upstream_connect_attempts_per_request{bucket="1"} 5096
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2361
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2585
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 150
telemt_me_reconnect_attempts_total 5888
telemt_me_reconnect_success_total 4053
telemt_me_reader_eof_total 4238
telemt_me_idle_close_by_peer_total 4238
telemt_me_route_drop_no_conn_total 33172
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 70254
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 34
telemt_desync_full_logged_total 12
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 20
telemt_desync_frames_bucket_total{bucket="3_10"} 13
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 4109
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 4023
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 56
telemt_user_connections_total{user="hello"} 70252
telemt_user_connections_current{user="hello"} 334
telemt_user_octets_from_client{user="hello"} 1544275516 (1.44 GB)
telemt_user_octets_to_client{user="hello"} 51799870348 (48.24 GB)
telemt_user_unique_ips_current{user="hello"} 161
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 17430.5 (4h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 235822
telemt_connections_bad_total 24341
telemt_connections_current 1198
telemt_connections_me_current 1198
telemt_handshake_timeouts_total 11595
telemt_upstream_connect_attempt_total 3744
telemt_upstream_connect_success_total 3744
telemt_upstream_connect_attempts_per_request{bucket="1"} 3744
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1966
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1776
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 2857
telemt_me_reconnect_success_total 2848
telemt_me_reader_eof_total 2998
telemt_me_idle_close_by_peer_total 2998
telemt_me_route_drop_no_conn_total 68690
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 193662
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1076
telemt_desync_full_logged_total 419
telemt_desync_suppressed_total 657
telemt_desync_frames_bucket_total{bucket="1_2"} 199
telemt_desync_frames_bucket_total{bucket="3_10"} 434
telemt_desync_frames_bucket_total{bucket="gt_10"} 443
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 2880
telemt_me_writer_restored_same_endpoint_total 2833
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 193686
telemt_user_connections_current{user="hello"} 1198
telemt_user_octets_from_client{user="hello"} 2009815992 (1.87 GB)
telemt_user_octets_to_client{user="hello"} 99072661244 (92.27 GB)
telemt_user_unique_ips_current{user="hello"} 475
telemt_user_unique_ips_recent_window{user="hello"} 116
```