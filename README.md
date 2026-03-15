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

# Server Metrics 2026-03-15 06:28:34 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 29645.8 (8h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 83592
telemt_connections_bad_total 448
telemt_handshake_timeouts_total 1608
telemt_upstream_connect_attempt_total 7244
telemt_upstream_connect_success_total 7201
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 7244
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3269
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3928
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 5755
telemt_me_reconnect_success_total 5735
telemt_me_reader_eof_total 6139
telemt_me_idle_close_by_peer_total 6139
telemt_me_route_drop_no_conn_total 85894
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 88556
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 679
telemt_desync_full_logged_total 297
telemt_desync_suppressed_total 382
telemt_desync_frames_bucket_total{bucket="1_2"} 119
telemt_desync_frames_bucket_total{bucket="3_10"} 280
telemt_desync_frames_bucket_total{bucket="gt_10"} 280
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 5781
telemt_me_writer_restored_same_endpoint_total 5704
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 78324
telemt_user_connections_current{user="hello"} 276
telemt_user_octets_from_client{user="hello"} 999733804 (953.42 MB)
telemt_user_octets_to_client{user="hello"} 42783698636 (39.85 GB)
telemt_user_unique_ips_current{user="hello"} 89
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 29653.1 (8h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 28095
telemt_connections_bad_total 67
telemt_handshake_timeouts_total 119
telemt_upstream_connect_attempt_total 7977
telemt_upstream_connect_success_total 7977
telemt_upstream_connect_attempts_per_request{bucket="1"} 7977
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3497
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4473
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 6526
telemt_me_reconnect_success_total 6500
telemt_me_reader_eof_total 6987
telemt_me_idle_close_by_peer_total 6987
telemt_me_route_drop_no_conn_total 14320
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 26762
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 6561
telemt_me_writer_restored_same_endpoint_total 6484
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 61
telemt_user_connections_total{user="hello"} 26765
telemt_user_connections_current{user="hello"} 145
telemt_user_octets_from_client{user="hello"} 736173076 (702.07 MB)
telemt_user_octets_to_client{user="hello"} 10186820116 (9.49 GB)
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 29645.5 (8h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 35830
telemt_connections_bad_total 455
telemt_handshake_timeouts_total 1773
telemt_upstream_connect_attempt_total 7893
telemt_upstream_connect_success_total 7892
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 7893
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3464
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4422
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 6445
telemt_me_reconnect_success_total 6417
telemt_me_reader_eof_total 6936
telemt_me_idle_close_by_peer_total 6936
telemt_me_route_drop_no_conn_total 12398
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 32417
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 6473
telemt_me_writer_restored_same_endpoint_total 6413
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 56
telemt_user_connections_total{user="hello"} 32366
telemt_user_connections_current{user="hello"} 72
telemt_user_octets_from_client{user="hello"} 8773767536 (8.17 GB)
telemt_user_octets_to_client{user="hello"} 17826146436 (16.60 GB)
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 29645.6 (8h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 38855
telemt_connections_bad_total 129
telemt_handshake_timeouts_total 255
telemt_upstream_connect_attempt_total 6964
telemt_upstream_connect_success_total 6963
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 6964
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3236
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3706
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 5522
telemt_me_reconnect_success_total 5502
telemt_me_reader_eof_total 5892
telemt_me_idle_close_by_peer_total 5892
telemt_me_route_drop_no_conn_total 17370
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 35492
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 78
telemt_desync_full_logged_total 21
telemt_desync_suppressed_total 57
telemt_desync_frames_bucket_total{bucket="1_2"} 19
telemt_desync_frames_bucket_total{bucket="3_10"} 32
telemt_desync_frames_bucket_total{bucket="gt_10"} 27
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 5559
telemt_me_writer_restored_same_endpoint_total 5491
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 35411
telemt_user_connections_current{user="hello"} 202
telemt_user_octets_from_client{user="hello"} 630832280 (601.61 MB)
telemt_user_octets_to_client{user="hello"} 23400148112 (21.79 GB)
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 4716.8 (1h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6798
telemt_connections_bad_total 909
telemt_handshake_timeouts_total 145
telemt_upstream_connect_attempt_total 1987
telemt_upstream_connect_success_total 1958
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 1987
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 860
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1088
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_reconnect_attempts_total 95915
telemt_me_reconnect_success_total 1523
telemt_me_reader_eof_total 1501
telemt_me_idle_close_by_peer_total 1501
telemt_me_route_drop_no_conn_total 1722
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5483
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 1450
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 1419
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_user_connections_total{user="hello"} 5628
telemt_user_connections_current{user="hello"} 64
telemt_user_octets_from_client{user="hello"} 32878829 (31.36 MB)
telemt_user_octets_to_client{user="hello"} 1829523311 (1.70 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 29644.6 (8h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 99894
telemt_connections_bad_total 1946
telemt_handshake_timeouts_total 433
telemt_upstream_connect_attempt_total 6513
telemt_upstream_connect_success_total 6476
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 6513
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3247
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3228
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_reconnect_attempts_total 5027
telemt_me_reconnect_success_total 5004
telemt_me_reader_eof_total 5326
telemt_me_idle_close_by_peer_total 5326
telemt_me_route_drop_no_conn_total 53741
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 94722
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 22
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 12
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 9
telemt_desync_frames_bucket_total{bucket="gt_10"} 7
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 5026
telemt_me_writer_restored_same_endpoint_total 4977
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 93280
telemt_user_connections_current{user="hello"} 323
telemt_user_octets_from_client{user="hello"} 2350563928 (2.19 GB)
telemt_user_octets_to_client{user="hello"} 49208826212 (45.83 GB)
telemt_user_unique_ips_current{user="hello"} 145
telemt_user_unique_ips_recent_window{user="hello"} 54
```