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

# Server Metrics 2026-03-16 20:50:32 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 7510.7 (2h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 52418
telemt_connections_bad_total 526
telemt_handshake_timeouts_total 2707
telemt_upstream_connect_attempt_total 1419
telemt_upstream_connect_success_total 1407
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 1419
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 633
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 773
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_reconnect_attempts_total 994
telemt_me_reconnect_success_total 990
telemt_me_reader_eof_total 1019
telemt_me_idle_close_by_peer_total 1019
telemt_me_route_drop_no_conn_total 17873
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 47110
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 226
telemt_desync_full_logged_total 50
telemt_desync_suppressed_total 176
telemt_desync_frames_bucket_total{bucket="1_2"} 96
telemt_desync_frames_bucket_total{bucket="3_10"} 78
telemt_desync_frames_bucket_total{bucket="gt_10"} 52
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 987
telemt_me_writer_restored_same_endpoint_total 969
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 46
telemt_user_connections_total{user="hello"} 47066
telemt_user_connections_current{user="hello"} 519
telemt_user_octets_from_client{user="hello"} 889990964 (848.76 MB)
telemt_user_octets_to_client{user="hello"} 30031025372 (27.97 GB)
telemt_user_unique_ips_current{user="hello"} 175
telemt_user_unique_ips_recent_window{user="hello"} 55
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 7762.2 (2h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 42447
telemt_connections_bad_total 25
telemt_handshake_timeouts_total 1998
telemt_upstream_connect_attempt_total 1663
telemt_upstream_connect_success_total 1639
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 1663
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 692
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 886
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_reconnect_attempts_total 1228
telemt_me_reconnect_success_total 1225
telemt_me_reader_eof_total 1266
telemt_me_idle_close_by_peer_total 1266
telemt_me_route_drop_no_conn_total 16205
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 38442
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 91
telemt_desync_full_logged_total 25
telemt_desync_suppressed_total 66
telemt_desync_frames_bucket_total{bucket="1_2"} 24
telemt_desync_frames_bucket_total{bucket="3_10"} 35
telemt_desync_frames_bucket_total{bucket="gt_10"} 32
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1244
telemt_me_writer_restored_same_endpoint_total 1209
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 38427
telemt_user_connections_current{user="hello"} 301
telemt_user_octets_from_client{user="hello"} 569476824 (543.10 MB)
telemt_user_octets_to_client{user="hello"} 14758801368 (13.75 GB)
telemt_user_unique_ips_current{user="hello"} 95
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 7538.2 (2h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 22405
telemt_connections_bad_total 351
telemt_handshake_timeouts_total 148
telemt_upstream_connect_attempt_total 1697
telemt_upstream_connect_success_total 1685
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 1697
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 714
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 964
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_reconnect_attempts_total 1281
telemt_me_reconnect_success_total 1264
telemt_me_reader_eof_total 1322
telemt_me_idle_close_by_peer_total 1322
telemt_me_route_drop_no_conn_total 7438
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 21348
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16
telemt_desync_full_logged_total 7
telemt_desync_suppressed_total 9
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 6
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 1277
telemt_me_writer_restored_same_endpoint_total 1253
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 13
telemt_user_connections_total{user="hello"} 21344
telemt_user_connections_current{user="hello"} 135
telemt_user_octets_from_client{user="hello"} 554001728 (528.34 MB)
telemt_user_octets_to_client{user="hello"} 8315486452 (7.74 GB)
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 7597.5 (2h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 44932
telemt_connections_bad_total 2927
telemt_handshake_timeouts_total 362
telemt_upstream_connect_attempt_total 1552
telemt_upstream_connect_success_total 1532
telemt_upstream_connect_fail_total 20
telemt_upstream_connect_attempts_per_request{bucket="1"} 1552
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 747
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 775
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 20
telemt_me_reconnect_attempts_total 1121
telemt_me_reconnect_success_total 1109
telemt_me_reader_eof_total 1145
telemt_me_idle_close_by_peer_total 1145
telemt_me_route_drop_no_conn_total 13830
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 40323
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 121
telemt_desync_full_logged_total 29
telemt_desync_suppressed_total 92
telemt_desync_frames_bucket_total{bucket="1_2"} 24
telemt_desync_frames_bucket_total{bucket="3_10"} 48
telemt_desync_frames_bucket_total{bucket="gt_10"} 49
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1121
telemt_me_writer_restored_same_endpoint_total 1102
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 40316
telemt_user_connections_current{user="hello"} 253
telemt_user_octets_from_client{user="hello"} 613035248 (584.64 MB)
telemt_user_octets_to_client{user="hello"} 14087765028 (13.12 GB)
telemt_user_unique_ips_current{user="hello"} 87
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 7569.6 (2h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 29027
telemt_connections_bad_total 8610
telemt_handshake_timeouts_total 169
telemt_upstream_connect_attempt_total 1915
telemt_upstream_connect_success_total 1889
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 1915
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 864
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 957
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 68
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_reconnect_attempts_total 2568
telemt_me_reconnect_success_total 1473
telemt_me_reader_eof_total 1519
telemt_me_idle_close_by_peer_total 1519
telemt_me_route_drop_no_conn_total 7753
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 19190
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9
telemt_desync_full_logged_total 3
telemt_desync_suppressed_total 6
telemt_desync_frames_bucket_total{bucket="3_10"} 4
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 1510
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 1465
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 19188
telemt_user_connections_current{user="hello"} 128
telemt_user_octets_from_client{user="hello"} 196259512 (187.17 MB)
telemt_user_octets_to_client{user="hello"} 6539871640 (6.09 GB)
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 7730.7 (2h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 65806
telemt_connections_bad_total 805
telemt_handshake_timeouts_total 676
telemt_upstream_connect_attempt_total 1429
telemt_upstream_connect_success_total 1419
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 1429
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 692
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 723
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 1008
telemt_me_reconnect_success_total 1005
telemt_me_reader_eof_total 1049
telemt_me_idle_close_by_peer_total 1049
telemt_me_route_drop_no_conn_total 27685
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 61957
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 31
telemt_desync_full_logged_total 13
telemt_desync_suppressed_total 18
telemt_desync_frames_bucket_total{bucket="1_2"} 8
telemt_desync_frames_bucket_total{bucket="3_10"} 14
telemt_desync_frames_bucket_total{bucket="gt_10"} 9
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 1023
telemt_me_writer_restored_same_endpoint_total 995
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 18
telemt_user_connections_total{user="hello"} 61950
telemt_user_connections_current{user="hello"} 444
telemt_user_octets_from_client{user="hello"} 1373420624 (1.28 GB)
telemt_user_octets_to_client{user="hello"} 32889284292 (30.63 GB)
telemt_user_unique_ips_current{user="hello"} 164
telemt_user_unique_ips_recent_window{user="hello"} 43
```