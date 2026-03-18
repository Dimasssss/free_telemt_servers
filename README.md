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

# Server Metrics 2026-03-18 22:53:59 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 3932.0 (1h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 47816
telemt_connections_bad_total 4676
telemt_connections_current 705
telemt_connections_me_current 705
telemt_handshake_timeouts_total 499
telemt_upstream_connect_attempt_total 733
telemt_upstream_connect_success_total 723
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 733
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 341
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 381
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 489
telemt_me_reconnect_success_total 487
telemt_me_reader_eof_total 482
telemt_me_idle_close_by_peer_total 482
telemt_me_route_drop_no_conn_total 18031
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 42901
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 182
telemt_desync_full_logged_total 69
telemt_desync_suppressed_total 113
telemt_desync_frames_bucket_total{bucket="1_2"} 40
telemt_desync_frames_bucket_total{bucket="3_10"} 68
telemt_desync_frames_bucket_total{bucket="gt_10"} 74
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 480
telemt_me_writer_restored_same_endpoint_total 477
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 136
telemt_user_connections_total{user="hello"} 40144
telemt_user_connections_current{user="hello"} 705
telemt_user_octets_from_client{user="hello"} 437303204 (417.04 MB)
telemt_user_octets_to_client{user="hello"} 17552605736 (16.35 GB)
telemt_user_unique_ips_current{user="hello"} 253
telemt_user_unique_ips_recent_window{user="hello"} 78
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 3935.6 (1h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 112211
telemt_connections_bad_total 2889
telemt_connections_current 1724
telemt_connections_me_current 1724
telemt_handshake_timeouts_total 897
telemt_upstream_connect_attempt_total 659
telemt_upstream_connect_success_total 643
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 659
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 327
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 313
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_reconnect_attempts_total 403
telemt_me_reconnect_success_total 402
telemt_me_reader_eof_total 407
telemt_me_idle_close_by_peer_total 407
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 39836
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 102543
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 366
telemt_desync_full_logged_total 127
telemt_desync_suppressed_total 239
telemt_desync_frames_bucket_total{bucket="1_2"} 69
telemt_desync_frames_bucket_total{bucket="3_10"} 129
telemt_desync_frames_bucket_total{bucket="gt_10"} 168
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 413
telemt_me_writer_restored_same_endpoint_total 391
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 102593
telemt_user_connections_current{user="hello"} 1724
telemt_user_octets_from_client{user="hello"} 6073322732 (5.66 GB)
telemt_user_octets_to_client{user="hello"} 42938962356 (39.99 GB)
telemt_user_unique_ips_current{user="hello"} 660
telemt_user_unique_ips_recent_window{user="hello"} 176
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 3932.8 (1h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 94945
telemt_connections_bad_total 13781
telemt_connections_current 1332
telemt_connections_me_current 1332
telemt_handshake_timeouts_total 2510
telemt_upstream_connect_attempt_total 782
telemt_upstream_connect_success_total 782
telemt_upstream_connect_attempts_per_request{bucket="1"} 782
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 420
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 362
telemt_me_reconnect_attempts_total 542
telemt_me_reconnect_success_total 541
telemt_me_reader_eof_total 544
telemt_me_idle_close_by_peer_total 544
telemt_me_route_drop_no_conn_total 32693
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 76023
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 324
telemt_desync_full_logged_total 128
telemt_desync_suppressed_total 196
telemt_desync_frames_bucket_total{bucket="1_2"} 60
telemt_desync_frames_bucket_total{bucket="3_10"} 137
telemt_desync_frames_bucket_total{bucket="gt_10"} 127
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 545
telemt_me_writer_restored_same_endpoint_total 525
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 76027
telemt_user_connections_current{user="hello"} 1332
telemt_user_octets_from_client{user="hello"} 932414652 (889.22 MB)
telemt_user_octets_to_client{user="hello"} 49034094856 (45.67 GB)
telemt_user_unique_ips_current{user="hello"} 550
telemt_user_unique_ips_recent_window{user="hello"} 120
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 3986.1 (1h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 110158
telemt_connections_bad_total 21560
telemt_connections_current 1144
telemt_connections_me_current 1144
telemt_handshake_timeouts_total 2212
telemt_upstream_connect_attempt_total 696
telemt_upstream_connect_success_total 696
telemt_upstream_connect_attempts_per_request{bucket="1"} 696
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 377
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 316
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 460
telemt_me_reconnect_success_total 458
telemt_me_reader_eof_total 461
telemt_me_idle_close_by_peer_total 461
telemt_me_route_drop_no_conn_total 46881
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 81676
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 189
telemt_desync_full_logged_total 63
telemt_desync_suppressed_total 126
telemt_desync_frames_bucket_total{bucket="1_2"} 41
telemt_desync_frames_bucket_total{bucket="3_10"} 73
telemt_desync_frames_bucket_total{bucket="gt_10"} 75
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 466
telemt_me_writer_restored_same_endpoint_total 434
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 268
telemt_me_writer_removed_unexpected_minus_restored_total 8
telemt_user_connections_total{user="hello"} 81605
telemt_user_connections_current{user="hello"} 1144
telemt_user_octets_from_client{user="hello"} 869030240 (828.77 MB)
telemt_user_octets_to_client{user="hello"} 29809837612 (27.76 GB)
telemt_user_unique_ips_current{user="hello"} 477
telemt_user_unique_ips_recent_window{user="hello"} 109
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 3929.7 (1h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 100617
telemt_connections_bad_total 4351
telemt_connections_current 1384
telemt_connections_me_current 1384
telemt_handshake_timeouts_total 3114
telemt_upstream_connect_attempt_total 716
telemt_upstream_connect_success_total 710
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 716
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 366
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 342
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_reconnect_attempts_total 469
telemt_me_reconnect_success_total 467
telemt_me_reader_eof_total 463
telemt_me_idle_close_by_peer_total 463
telemt_me_route_drop_no_conn_total 29453
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 79651
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 364
telemt_desync_full_logged_total 150
telemt_desync_suppressed_total 214
telemt_desync_frames_bucket_total{bucket="1_2"} 96
telemt_desync_frames_bucket_total{bucket="3_10"} 128
telemt_desync_frames_bucket_total{bucket="gt_10"} 140
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 466
telemt_me_writer_restored_same_endpoint_total 443
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_user_connections_total{user="hello"} 79615
telemt_user_connections_current{user="hello"} 1384
telemt_user_octets_from_client{user="hello"} 1017864476 (970.71 MB)
telemt_user_octets_to_client{user="hello"} 48598776060 (45.26 GB)
telemt_user_unique_ips_current{user="hello"} 591
telemt_user_unique_ips_recent_window{user="hello"} 137
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 3941.0 (1h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 22881
telemt_connections_bad_total 5000
telemt_connections_current 373
telemt_connections_me_current 373
telemt_handshake_timeouts_total 67
telemt_upstream_connect_attempt_total 1127
telemt_upstream_connect_success_total 1086
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 1127
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 655
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 431
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_reconnect_attempts_total 1652
telemt_me_reconnect_success_total 850
telemt_me_reader_eof_total 842
telemt_me_idle_close_by_peer_total 842
telemt_me_route_drop_no_conn_total 7113
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 17296
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 24
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 18
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 10
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 845
telemt_me_refill_failed_total 25
telemt_me_writer_restored_same_endpoint_total 820
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_user_connections_total{user="hello"} 17296
telemt_user_connections_current{user="hello"} 373
telemt_user_octets_from_client{user="hello"} 233491136 (222.67 MB)
telemt_user_octets_to_client{user="hello"} 10448114208 (9.73 GB)
telemt_user_unique_ips_current{user="hello"} 152
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 3931.9 (1h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 77643
telemt_connections_bad_total 11492
telemt_connections_current 1219
telemt_connections_me_current 1219
telemt_handshake_timeouts_total 2235
telemt_upstream_connect_attempt_total 711
telemt_upstream_connect_success_total 711
telemt_upstream_connect_attempts_per_request{bucket="1"} 711
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 386
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 325
telemt_me_reconnect_attempts_total 470
telemt_me_reconnect_success_total 470
telemt_me_reader_eof_total 475
telemt_me_idle_close_by_peer_total 475
telemt_me_route_drop_no_conn_total 22295
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 62188
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 510
telemt_desync_full_logged_total 190
telemt_desync_suppressed_total 320
telemt_desync_frames_bucket_total{bucket="1_2"} 95
telemt_desync_frames_bucket_total{bucket="3_10"} 203
telemt_desync_frames_bucket_total{bucket="gt_10"} 212
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 477
telemt_me_writer_restored_same_endpoint_total 455
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 62192
telemt_user_connections_current{user="hello"} 1219
telemt_user_octets_from_client{user="hello"} 706174628 (673.46 MB)
telemt_user_octets_to_client{user="hello"} 39006995344 (36.33 GB)
telemt_user_unique_ips_current{user="hello"} 514
telemt_user_unique_ips_recent_window{user="hello"} 124
```