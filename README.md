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

# Server Metrics 2026-03-14 14:15:24 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.17

telemt_uptime_seconds 3544.5 (0h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18086
telemt_connections_bad_total 1107
telemt_handshake_timeouts_total 113
telemt_upstream_connect_attempt_total 851
telemt_upstream_connect_success_total 851
telemt_upstream_connect_attempts_per_request{bucket="1"} 851
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 369
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 479
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 648
telemt_me_reconnect_success_total 638
telemt_me_reader_eof_total 644
telemt_me_idle_close_by_peer_total 644
telemt_me_route_drop_no_conn_total 5675
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16445
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 23
telemt_desync_full_logged_total 13
telemt_desync_suppressed_total 10
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 11
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 648
telemt_me_writer_restored_same_endpoint_total 620
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 72
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 16441
telemt_user_connections_current{user="hello"} 371
telemt_user_octets_from_client{user="hello"} 309104724 (294.79 MB)
telemt_user_octets_to_client{user="hello"} 6557678880 (6.11 GB)
telemt_user_unique_ips_current{user="hello"} 116
telemt_user_unique_ips_recent_window{user="hello"} 50
```

## psb.hosting

```
telemt 3.3.17

telemt_uptime_seconds 3542.2 (0h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8352
telemt_connections_bad_total 33
telemt_handshake_timeouts_total 381
telemt_upstream_connect_attempt_total 862
telemt_upstream_connect_success_total 842
telemt_upstream_connect_fail_total 20
telemt_upstream_connect_attempts_per_request{bucket="1"} 862
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 341
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 492
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 20
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 659
telemt_me_reconnect_success_total 635
telemt_me_reader_eof_total 654
telemt_me_idle_close_by_peer_total 654
telemt_me_route_drop_no_conn_total 3634
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7711
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 651
telemt_me_writer_restored_same_endpoint_total 630
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 120
telemt_me_writer_removed_unexpected_minus_restored_total 16
telemt_user_connections_total{user="hello"} 7694
telemt_user_connections_current{user="hello"} 165
telemt_user_octets_from_client{user="hello"} 90950216 (86.74 MB)
telemt_user_octets_to_client{user="hello"} 2892775352 (2.69 GB)
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## koara.io

```
telemt 3.3.17

telemt_uptime_seconds 3546.6 (0h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8230
telemt_connections_bad_total 41
telemt_handshake_timeouts_total 131
telemt_upstream_connect_attempt_total 2228
telemt_upstream_connect_success_total 2217
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 2228
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1149
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1067
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 38
telemt_me_reconnect_attempts_total 92942
telemt_me_reconnect_success_total 1692
telemt_me_reader_eof_total 1704
telemt_me_idle_close_by_peer_total 1704
telemt_me_route_drop_no_conn_total 2829
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7276
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_writer_removed_unexpected_total 1721
telemt_me_refill_failed_total 2963
telemt_me_writer_restored_same_endpoint_total 1654
telemt_me_writer_restored_fallback_total 38
telemt_me_async_recovery_trigger_total 1685
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 7586
telemt_user_connections_current{user="hello"} 152
telemt_user_octets_from_client{user="hello"} 169803209 (161.94 MB)
telemt_user_octets_to_client{user="hello"} 4095597890 (3.81 GB)
telemt_user_msgs_from_client{user="hello"} 3762
telemt_user_msgs_to_client{user="hello"} 18362
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## landvps.ru

```
telemt 3.3.17

telemt_uptime_seconds 3551.5 (0h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11480
telemt_connections_bad_total 18
telemt_handshake_timeouts_total 84
telemt_upstream_connect_attempt_total 806
telemt_upstream_connect_success_total 804
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 806
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 356
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 441
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 606
telemt_me_reconnect_success_total 601
telemt_me_reader_eof_total 595
telemt_me_idle_close_by_peer_total 595
telemt_me_route_drop_no_conn_total 6056
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10929
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 133
telemt_desync_full_logged_total 33
telemt_desync_suppressed_total 100
telemt_desync_frames_bucket_total{bucket="1_2"} 14
telemt_desync_frames_bucket_total{bucket="3_10"} 62
telemt_desync_frames_bucket_total{bucket="gt_10"} 57
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 594
telemt_me_writer_restored_same_endpoint_total 599
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 60
telemt_user_connections_total{user="hello"} 10814
telemt_user_connections_current{user="hello"} 200
telemt_user_octets_from_client{user="hello"} 149166612 (142.26 MB)
telemt_user_octets_to_client{user="hello"} 3063674072 (2.85 GB)
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## rdp-onedash.ru

```
telemt 3.3.17

telemt_uptime_seconds 3544.7 (0h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7996
telemt_connections_bad_total 781
telemt_handshake_timeouts_total 82
telemt_upstream_connect_attempt_total 1003
telemt_upstream_connect_success_total 990
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 1003
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 438
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 552
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 1907
telemt_me_reconnect_success_total 779
telemt_me_reader_eof_total 789
telemt_me_idle_close_by_peer_total 789
telemt_me_route_drop_no_conn_total 2849
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6722
telemt_me_writer_pick_total{mode="p2c",result="full"} 2
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 46
telemt_desync_full_logged_total 4
telemt_desync_suppressed_total 42
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 17
telemt_desync_frames_bucket_total{bucket="gt_10"} 24
telemt_me_writer_removed_unexpected_total 808
telemt_me_refill_failed_total 35
telemt_me_writer_restored_same_endpoint_total 775
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 6718
telemt_user_connections_current{user="hello"} 93
telemt_user_octets_from_client{user="hello"} 47968280 (45.75 MB)
telemt_user_octets_to_client{user="hello"} 1475810100 (1.37 GB)
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## hostvds.com

```
telemt 3.3.17

telemt_uptime_seconds 3544.2 (0h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 26367
telemt_connections_bad_total 27
telemt_handshake_timeouts_total 131
telemt_upstream_connect_attempt_total 778
telemt_upstream_connect_success_total 756
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 778
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 417
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 338
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_keepalive_timeout_total 19
telemt_me_reconnect_attempts_total 566
telemt_me_reconnect_success_total 542
telemt_me_reader_eof_total 527
telemt_me_idle_close_by_peer_total 527
telemt_me_route_drop_no_conn_total 12511
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 24836
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 536
telemt_me_writer_restored_same_endpoint_total 538
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 136
telemt_user_connections_total{user="hello"} 24758
telemt_user_connections_current{user="hello"} 530
telemt_user_octets_from_client{user="hello"} 516229848 (492.32 MB)
telemt_user_octets_to_client{user="hello"} 10292564104 (9.59 GB)
telemt_user_unique_ips_current{user="hello"} 203
telemt_user_unique_ips_recent_window{user="hello"} 76
```