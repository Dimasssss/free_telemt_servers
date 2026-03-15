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

# Server Metrics 2026-03-15 07:09:10 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 32082.4 (8h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 97339
telemt_connections_bad_total 613
telemt_handshake_timeouts_total 2166
telemt_upstream_connect_attempt_total 7749
telemt_upstream_connect_success_total 7704
telemt_upstream_connect_fail_total 45
telemt_upstream_connect_attempts_per_request{bucket="1"} 7749
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3502
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4198
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 45
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 6128
telemt_me_reconnect_success_total 6107
telemt_me_reader_eof_total 6542
telemt_me_idle_close_by_peer_total 6542
telemt_me_route_drop_no_conn_total 122865
telemt_me_route_drop_channel_closed_total 24
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 106562
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 799
telemt_desync_full_logged_total 350
telemt_desync_suppressed_total 449
telemt_desync_frames_bucket_total{bucket="1_2"} 140
telemt_desync_frames_bucket_total{bucket="3_10"} 334
telemt_desync_frames_bucket_total{bucket="gt_10"} 325
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 6159
telemt_me_writer_restored_same_endpoint_total 6076
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 90708
telemt_user_connections_current{user="hello"} 322
telemt_user_octets_from_client{user="hello"} 1230962872 (1.15 GB)
telemt_user_octets_to_client{user="hello"} 62827873664 (58.51 GB)
telemt_user_unique_ips_current{user="hello"} 109
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 32089.5 (8h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 31697
telemt_connections_bad_total 208
telemt_handshake_timeouts_total 124
telemt_upstream_connect_attempt_total 8596
telemt_upstream_connect_success_total 8596
telemt_upstream_connect_attempts_per_request{bucket="1"} 8596
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3780
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4807
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 7016
telemt_me_reconnect_success_total 6987
telemt_me_reader_eof_total 7510
telemt_me_idle_close_by_peer_total 7510
telemt_me_route_drop_no_conn_total 16400
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 30111
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 7053
telemt_me_writer_restored_same_endpoint_total 6971
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 66
telemt_user_connections_total{user="hello"} 30114
telemt_user_connections_current{user="hello"} 173
telemt_user_octets_from_client{user="hello"} 769107408 (733.48 MB)
telemt_user_octets_to_client{user="hello"} 11603178080 (10.81 GB)
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 32082.3 (8h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 40520
telemt_connections_bad_total 458
telemt_handshake_timeouts_total 1799
telemt_upstream_connect_attempt_total 8508
telemt_upstream_connect_success_total 8507
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 8508
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3742
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4758
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 6931
telemt_me_reconnect_success_total 6901
telemt_me_reader_eof_total 7467
telemt_me_idle_close_by_peer_total 7467
telemt_me_route_drop_no_conn_total 13860
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 36431
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 6963
telemt_me_writer_restored_same_endpoint_total 6897
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 62
telemt_user_connections_total{user="hello"} 36369
telemt_user_connections_current{user="hello"} 127
telemt_user_octets_from_client{user="hello"} 8827973916 (8.22 GB)
telemt_user_octets_to_client{user="hello"} 19834989176 (18.47 GB)
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 32082.0 (8h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 46272
telemt_connections_bad_total 132
telemt_handshake_timeouts_total 322
telemt_upstream_connect_attempt_total 7499
telemt_upstream_connect_success_total 7498
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 7499
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3511
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3966
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 5927
telemt_me_reconnect_success_total 5904
telemt_me_reader_eof_total 6328
telemt_me_idle_close_by_peer_total 6328
telemt_me_route_drop_no_conn_total 20118
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 41683
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 81
telemt_desync_full_logged_total 22
telemt_desync_suppressed_total 59
telemt_desync_frames_bucket_total{bucket="1_2"} 21
telemt_desync_frames_bucket_total{bucket="3_10"} 33
telemt_desync_frames_bucket_total{bucket="gt_10"} 27
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 5966
telemt_me_writer_restored_same_endpoint_total 5893
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 62
telemt_user_connections_total{user="hello"} 41603
telemt_user_connections_current{user="hello"} 189
telemt_user_octets_from_client{user="hello"} 777363548 (741.35 MB)
telemt_user_octets_to_client{user="hello"} 26220904272 (24.42 GB)
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 7153.5 (1h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10277
telemt_connections_bad_total 1394
telemt_handshake_timeouts_total 156
telemt_upstream_connect_attempt_total 2796
telemt_upstream_connect_success_total 2762
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 2796
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1190
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1560
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_reconnect_attempts_total 96632
telemt_me_reconnect_success_total 2238
telemt_me_reader_eof_total 2249
telemt_me_idle_close_by_peer_total 2249
telemt_me_route_drop_no_conn_total 2782
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8386
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 2176
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 2134
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_user_connections_total{user="hello"} 8531
telemt_user_connections_current{user="hello"} 71
telemt_user_octets_from_client{user="hello"} 57371749 (54.71 MB)
telemt_user_octets_to_client{user="hello"} 4856377343 (4.52 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 32081.4 (8h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 126388
telemt_connections_bad_total 14503
telemt_handshake_timeouts_total 523
telemt_upstream_connect_attempt_total 6981
telemt_upstream_connect_success_total 6942
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 6981
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3492
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3449
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_reconnect_attempts_total 5363
telemt_me_reconnect_success_total 5337
telemt_me_reader_eof_total 5688
telemt_me_idle_close_by_peer_total 5688
telemt_me_route_drop_no_conn_total 61051
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 108071
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 25
telemt_desync_full_logged_total 11
telemt_desync_suppressed_total 14
telemt_desync_frames_bucket_total{bucket="1_2"} 8
telemt_desync_frames_bucket_total{bucket="3_10"} 9
telemt_desync_frames_bucket_total{bucket="gt_10"} 8
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 5363
telemt_me_writer_restored_same_endpoint_total 5310
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 26
telemt_user_connections_total{user="hello"} 106624
telemt_user_connections_current{user="hello"} 430
telemt_user_octets_from_client{user="hello"} 2755235884 (2.57 GB)
telemt_user_octets_to_client{user="hello"} 56062878764 (52.21 GB)
telemt_user_unique_ips_current{user="hello"} 175
telemt_user_unique_ips_recent_window{user="hello"} 64
```