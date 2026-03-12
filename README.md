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

# Server Metrics 2026-03-12 08:27:36 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 3253.5 (0h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18932
telemt_connections_bad_total 3
telemt_handshake_timeouts_total 1918
telemt_upstream_connect_attempt_total 692
telemt_upstream_connect_success_total 690
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 692
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 321
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 368
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 37
telemt_me_reconnect_attempts_total 496
telemt_me_reconnect_success_total 494
telemt_me_reader_eof_total 482
telemt_me_idle_close_by_peer_total 482
telemt_me_route_drop_no_conn_total 4604
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 15893
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 59
telemt_desync_full_logged_total 19
telemt_desync_suppressed_total 40
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 27
telemt_desync_frames_bucket_total{bucket="gt_10"} 26
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 487
telemt_me_writer_restored_same_endpoint_total 478
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_user_connections_total{user="hello"} 15890
telemt_user_connections_current{user="hello"} 349
telemt_user_octets_from_client{user="hello"} 139981884 (133.50 MB)
telemt_user_octets_to_client{user="hello"} 5784225328 (5.39 GB)
telemt_user_unique_ips_current{user="hello"} 94
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 3146.6 (0h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6615
telemt_connections_bad_total 8
telemt_handshake_timeouts_total 59
telemt_upstream_connect_attempt_total 1211
telemt_upstream_connect_success_total 1185
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 1211
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 365
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 820
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_keepalive_timeout_total 27
telemt_me_reconnect_attempts_total 2495
telemt_me_reconnect_success_total 989
telemt_me_reader_eof_total 997
telemt_me_idle_close_by_peer_total 997
telemt_me_route_drop_no_conn_total 2082
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6283
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1
telemt_desync_full_logged_total 1
telemt_desync_frames_bucket_total{bucket="3_10"} 1
telemt_me_writer_removed_unexpected_total 1020
telemt_me_refill_failed_total 47
telemt_me_writer_restored_same_endpoint_total 974
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 31
telemt_user_connections_total{user="hello"} 6280
telemt_user_connections_current{user="hello"} 106
telemt_user_octets_from_client{user="hello"} 37264856 (35.54 MB)
telemt_user_octets_to_client{user="hello"} 1444787444 (1.35 GB)
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 3110.3 (0h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9916
telemt_connections_bad_total 8
telemt_handshake_timeouts_total 88
telemt_upstream_connect_attempt_total 721
telemt_upstream_connect_success_total 721
telemt_upstream_connect_attempts_per_request{bucket="1"} 721
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 364
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 356
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 528
telemt_me_reconnect_success_total 526
telemt_me_reader_eof_total 517
telemt_me_idle_close_by_peer_total 517
telemt_me_route_drop_no_conn_total 2842
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9431
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9
telemt_desync_full_logged_total 5
telemt_desync_suppressed_total 4
telemt_desync_frames_bucket_total{bucket="3_10"} 5
telemt_desync_frames_bucket_total{bucket="gt_10"} 4
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 505
telemt_me_writer_restored_same_endpoint_total 506
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_user_connections_total{user="hello"} 9431
telemt_user_connections_current{user="hello"} 194
telemt_user_octets_from_client{user="hello"} 100363780 (95.71 MB)
telemt_user_octets_to_client{user="hello"} 13408140804 (12.49 GB)
telemt_user_unique_ips_current{user="hello"} 68
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 3085.9 (0h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11422
telemt_connections_bad_total 1013
telemt_handshake_timeouts_total 36
telemt_upstream_connect_attempt_total 801
telemt_upstream_connect_success_total 763
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 801
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 330
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 432
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_keepalive_timeout_total 13
telemt_me_reconnect_attempts_total 583
telemt_me_reconnect_success_total 561
telemt_me_reader_eof_total 573
telemt_me_idle_close_by_peer_total 573
telemt_me_route_drop_no_conn_total 2927
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9614
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 21
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 12
telemt_desync_frames_bucket_total{bucket="1_2"} 8
telemt_desync_frames_bucket_total{bucket="3_10"} 6
telemt_desync_frames_bucket_total{bucket="gt_10"} 7
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 572
telemt_me_writer_restored_same_endpoint_total 553
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 121
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 9614
telemt_user_connections_current{user="hello"} 209
telemt_user_octets_from_client{user="hello"} 107549320 (102.57 MB)
telemt_user_octets_to_client{user="hello"} 2685598480 (2.50 GB)
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 3055.3 (0h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5816
telemt_connections_bad_total 629
telemt_handshake_timeouts_total 85
telemt_upstream_connect_attempt_total 1062
telemt_upstream_connect_success_total 1016
telemt_upstream_connect_fail_total 46
telemt_upstream_connect_attempts_per_request{bucket="1"} 1062
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 398
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 616
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 46
telemt_me_keepalive_timeout_total 22
telemt_me_reconnect_attempts_total 1943
telemt_me_reconnect_success_total 821
telemt_me_reader_eof_total 829
telemt_me_idle_close_by_peer_total 829
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 1533
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4962
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 20
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 83
telemt_desync_full_logged_total 26
telemt_desync_suppressed_total 57
telemt_desync_frames_bucket_total{bucket="1_2"} 1
telemt_desync_frames_bucket_total{bucket="3_10"} 70
telemt_desync_frames_bucket_total{bucket="gt_10"} 12
telemt_me_writer_removed_unexpected_total 851
telemt_me_refill_failed_total 35
telemt_me_writer_restored_same_endpoint_total 808
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 30
telemt_user_connections_total{user="hello"} 4962
telemt_user_connections_current{user="hello"} 86
telemt_user_octets_from_client{user="hello"} 15253404 (14.55 MB)
telemt_user_octets_to_client{user="hello"} 690330860 (658.35 MB)
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 3042.3 (0h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14352
telemt_connections_bad_total 491
telemt_handshake_timeouts_total 160
telemt_upstream_connect_attempt_total 509
telemt_upstream_connect_success_total 505
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 509
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 266
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 239
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 313
telemt_me_reconnect_success_total 312
telemt_me_reader_eof_total 310
telemt_me_idle_close_by_peer_total 310
telemt_me_route_drop_no_conn_total 6608
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13081
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4
telemt_desync_full_logged_total 2
telemt_desync_suppressed_total 2
telemt_desync_frames_bucket_total{bucket="3_10"} 4
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 316
telemt_me_writer_restored_same_endpoint_total 305
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 13055
telemt_user_connections_current{user="hello"} 306
telemt_user_octets_from_client{user="hello"} 1129138116 (1.05 GB)
telemt_user_octets_to_client{user="hello"} 11279669284 (10.51 GB)
telemt_user_unique_ips_current{user="hello"} 101
telemt_user_unique_ips_recent_window{user="hello"} 36
```