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

# Server Metrics 2026-03-15 00:07:27 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 6780.0 (1h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13824
telemt_connections_bad_total 283
telemt_handshake_timeouts_total 199
telemt_upstream_connect_attempt_total 1737
telemt_upstream_connect_success_total 1728
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 1737
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 820
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 904
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_reconnect_attempts_total 1363
telemt_me_reconnect_success_total 1357
telemt_me_reader_eof_total 1410
telemt_me_idle_close_by_peer_total 1410
telemt_me_route_drop_no_conn_total 3859
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12847
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 87
telemt_desync_full_logged_total 34
telemt_desync_suppressed_total 53
telemt_desync_frames_bucket_total{bucket="1_2"} 14
telemt_desync_frames_bucket_total{bucket="3_10"} 28
telemt_desync_frames_bucket_total{bucket="gt_10"} 45
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 1352
telemt_me_writer_restored_same_endpoint_total 1326
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_user_connections_total{user="hello"} 12846
telemt_user_connections_current{user="hello"} 260
telemt_user_octets_from_client{user="hello"} 169653272 (161.79 MB)
telemt_user_octets_to_client{user="hello"} 4007934232 (3.73 GB)
telemt_user_unique_ips_current{user="hello"} 77
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 6786.6 (1h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5972
telemt_connections_bad_total 12
telemt_handshake_timeouts_total 22
telemt_upstream_connect_attempt_total 1920
telemt_upstream_connect_success_total 1920
telemt_upstream_connect_attempts_per_request{bucket="1"} 1920
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 855
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1065
telemt_me_reconnect_attempts_total 1549
telemt_me_reconnect_success_total 1543
telemt_me_reader_eof_total 1628
telemt_me_idle_close_by_peer_total 1628
telemt_me_route_drop_no_conn_total 1895
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5618
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 1551
telemt_me_writer_restored_same_endpoint_total 1527
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 8
telemt_user_connections_total{user="hello"} 5619
telemt_user_connections_current{user="hello"} 125
telemt_user_octets_from_client{user="hello"} 56481816 (53.87 MB)
telemt_user_octets_to_client{user="hello"} 801968120 (764.82 MB)
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 6779.2 (1h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6564
telemt_connections_bad_total 69
telemt_handshake_timeouts_total 107
telemt_upstream_connect_attempt_total 1819
telemt_upstream_connect_success_total 1818
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 1819
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 808
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1006
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 1451
telemt_me_reconnect_success_total 1440
telemt_me_reader_eof_total 1539
telemt_me_idle_close_by_peer_total 1539
telemt_me_route_drop_no_conn_total 2234
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6176
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 1445
telemt_me_writer_restored_same_endpoint_total 1436
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 6157
telemt_user_connections_current{user="hello"} 87
telemt_user_octets_from_client{user="hello"} 1030195472 (982.47 MB)
telemt_user_octets_to_client{user="hello"} 9317478172 (8.68 GB)
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 6778.9 (1h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6346
telemt_connections_bad_total 38
telemt_handshake_timeouts_total 25
telemt_upstream_connect_attempt_total 1689
telemt_upstream_connect_success_total 1688
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 1689
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 771
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 915
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 1325
telemt_me_reconnect_success_total 1317
telemt_me_reader_eof_total 1380
telemt_me_idle_close_by_peer_total 1380
telemt_me_route_drop_no_conn_total 2784
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6116
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 12
telemt_desync_full_logged_total 2
telemt_desync_suppressed_total 10
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 5
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 1322
telemt_me_writer_restored_same_endpoint_total 1306
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 6116
telemt_user_connections_current{user="hello"} 120
telemt_user_octets_from_client{user="hello"} 164144720 (156.54 MB)
telemt_user_octets_to_client{user="hello"} 5630063976 (5.24 GB)
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 6779.0 (1h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8278
telemt_connections_bad_total 1509
telemt_handshake_timeouts_total 331
telemt_upstream_connect_attempt_total 2328
telemt_upstream_connect_success_total 2299
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 2328
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1137
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1158
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_reconnect_attempts_total 2000
telemt_me_reconnect_success_total 1929
telemt_me_reader_eof_total 1997
telemt_me_idle_close_by_peer_total 1997
telemt_me_route_drop_no_conn_total 1967
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6272
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 1927
telemt_me_refill_failed_total 2
telemt_me_writer_restored_same_endpoint_total 1917
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 29
telemt_user_connections_total{user="hello"} 6267
telemt_user_connections_current{user="hello"} 65
telemt_user_octets_from_client{user="hello"} 52882660 (50.43 MB)
telemt_user_octets_to_client{user="hello"} 3924408988 (3.65 GB)
telemt_user_unique_ips_current{user="hello"} 23
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 6778.0 (1h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21792
telemt_connections_bad_total 375
telemt_handshake_timeouts_total 82
telemt_upstream_connect_attempt_total 1555
telemt_upstream_connect_success_total 1549
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 1555
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 770
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 779
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_reconnect_attempts_total 1181
telemt_me_reconnect_success_total 1178
telemt_me_reader_eof_total 1211
telemt_me_idle_close_by_peer_total 1211
telemt_me_route_drop_no_conn_total 12062
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 21204
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16
telemt_desync_full_logged_total 5
telemt_desync_suppressed_total 11
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 4
telemt_desync_frames_bucket_total{bucket="gt_10"} 6
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 1161
telemt_me_writer_restored_same_endpoint_total 1151
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_user_connections_total{user="hello"} 20729
telemt_user_connections_current{user="hello"} 344
telemt_user_octets_from_client{user="hello"} 370003136 (352.86 MB)
telemt_user_octets_to_client{user="hello"} 16242945920 (15.13 GB)
telemt_user_unique_ips_current{user="hello"} 150
telemt_user_unique_ips_recent_window{user="hello"} 46
```