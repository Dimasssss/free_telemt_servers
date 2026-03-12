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

# Server Metrics 2026-03-12 09:18:41 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 6318.6 (1h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 34506
telemt_connections_bad_total 21
telemt_handshake_timeouts_total 2061
telemt_upstream_connect_attempt_total 1307
telemt_upstream_connect_success_total 1301
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 1307
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 592
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 707
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 42
telemt_me_reconnect_attempts_total 978
telemt_me_reconnect_success_total 972
telemt_me_reader_eof_total 989
telemt_me_idle_close_by_peer_total 989
telemt_me_route_drop_no_conn_total 9058
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 30349
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 91
telemt_desync_full_logged_total 38
telemt_desync_suppressed_total 53
telemt_desync_frames_bucket_total{bucket="1_2"} 19
telemt_desync_frames_bucket_total{bucket="3_10"} 36
telemt_desync_frames_bucket_total{bucket="gt_10"} 36
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 969
telemt_me_writer_restored_same_endpoint_total 956
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_user_connections_total{user="hello"} 30345
telemt_user_connections_current{user="hello"} 380
telemt_user_octets_from_client{user="hello"} 426898440 (407.12 MB)
telemt_user_octets_to_client{user="hello"} 8953352288 (8.34 GB)
telemt_user_unique_ips_current{user="hello"} 106
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 6211.6 (1h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13083
telemt_connections_bad_total 16
telemt_handshake_timeouts_total 115
telemt_upstream_connect_attempt_total 2172
telemt_upstream_connect_success_total 2135
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 2172
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 685
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1450
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_keepalive_timeout_total 41
telemt_me_reconnect_attempts_total 4595
telemt_me_reconnect_success_total 1807
telemt_me_reader_eof_total 1885
telemt_me_idle_close_by_peer_total 1885
telemt_me_route_drop_no_conn_total 4771
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12485
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 13
telemt_desync_full_logged_total 3
telemt_desync_suppressed_total 10
telemt_desync_frames_bucket_total{bucket="3_10"} 6
telemt_desync_frames_bucket_total{bucket="gt_10"} 7
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 1885
telemt_me_refill_failed_total 87
telemt_me_writer_restored_same_endpoint_total 1792
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 78
telemt_user_connections_total{user="hello"} 12481
telemt_user_connections_current{user="hello"} 116
telemt_user_octets_from_client{user="hello"} 73758684 (70.34 MB)
telemt_user_octets_to_client{user="hello"} 2181876840 (2.03 GB)
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 6175.2 (1h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19359
telemt_connections_bad_total 55
telemt_handshake_timeouts_total 141
telemt_upstream_connect_attempt_total 1591
telemt_upstream_connect_success_total 1591
telemt_upstream_connect_attempts_per_request{bucket="1"} 1591
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 765
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 823
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 1265
telemt_me_reconnect_success_total 1258
telemt_me_reader_eof_total 1294
telemt_me_idle_close_by_peer_total 1294
telemt_me_route_drop_no_conn_total 6276
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 18007
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
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 1242
telemt_me_writer_restored_same_endpoint_total 1238
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_user_connections_total{user="hello"} 18001
telemt_user_connections_current{user="hello"} 189
telemt_user_octets_from_client{user="hello"} 173649396 (165.60 MB)
telemt_user_octets_to_client{user="hello"} 18387012644 (17.12 GB)
telemt_user_unique_ips_current{user="hello"} 64
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 6150.8 (1h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 22091
telemt_connections_bad_total 1022
telemt_handshake_timeouts_total 130
telemt_upstream_connect_attempt_total 1748
telemt_upstream_connect_success_total 1697
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 1748
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 717
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 974
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_keepalive_timeout_total 68
telemt_me_reconnect_attempts_total 1388
telemt_me_reconnect_success_total 1360
telemt_me_reader_eof_total 1396
telemt_me_idle_close_by_peer_total 1396
telemt_me_route_drop_no_conn_total 6419
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 19504
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 88
telemt_desync_full_logged_total 30
telemt_desync_suppressed_total 58
telemt_desync_frames_bucket_total{bucket="1_2"} 31
telemt_desync_frames_bucket_total{bucket="3_10"} 27
telemt_desync_frames_bucket_total{bucket="gt_10"} 30
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 1381
telemt_me_writer_restored_same_endpoint_total 1352
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 121
telemt_me_writer_removed_unexpected_minus_restored_total 21
telemt_user_connections_total{user="hello"} 19503
telemt_user_connections_current{user="hello"} 168
telemt_user_octets_from_client{user="hello"} 588887656 (561.61 MB)
telemt_user_octets_to_client{user="hello"} 6655834076 (6.20 GB)
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 6120.1 (1h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11762
telemt_connections_bad_total 1214
telemt_handshake_timeouts_total 168
telemt_upstream_connect_attempt_total 1918
telemt_upstream_connect_success_total 1841
telemt_upstream_connect_fail_total 77
telemt_upstream_connect_attempts_per_request{bucket="1"} 1918
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 634
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1204
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 77
telemt_me_keepalive_timeout_total 41
telemt_me_reconnect_attempts_total 6539
telemt_me_reconnect_success_total 1509
telemt_me_reader_eof_total 1644
telemt_me_idle_close_by_peer_total 1644
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 3325
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10128
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 183
telemt_desync_full_logged_total 51
telemt_desync_suppressed_total 132
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 159
telemt_desync_frames_bucket_total{bucket="gt_10"} 20
telemt_me_writer_removed_unexpected_total 1667
telemt_me_refill_failed_total 157
telemt_me_writer_restored_same_endpoint_total 1496
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 158
telemt_user_connections_total{user="hello"} 10127
telemt_user_connections_current{user="hello"} 115
telemt_user_octets_from_client{user="hello"} 41180940 (39.27 MB)
telemt_user_octets_to_client{user="hello"} 2221221120 (2.07 GB)
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 6107.3 (1h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 29293
telemt_connections_bad_total 528
telemt_handshake_timeouts_total 443
telemt_upstream_connect_attempt_total 1074
telemt_upstream_connect_success_total 1067
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 1074
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 521
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 544
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 747
telemt_me_reconnect_success_total 740
telemt_me_reader_eof_total 764
telemt_me_idle_close_by_peer_total 764
telemt_me_route_drop_no_conn_total 13043
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 27292
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 20
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 10
telemt_desync_frames_bucket_total{bucket="1_2"} 8
telemt_desync_frames_bucket_total{bucket="3_10"} 7
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 751
telemt_me_writer_restored_same_endpoint_total 733
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 27262
telemt_user_connections_current{user="hello"} 338
telemt_user_octets_from_client{user="hello"} 1509224556 (1.41 GB)
telemt_user_octets_to_client{user="hello"} 18441244328 (17.17 GB)
telemt_user_unique_ips_current{user="hello"} 107
telemt_user_unique_ips_recent_window{user="hello"} 52
```